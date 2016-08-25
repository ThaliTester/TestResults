#### Test 82728424ebd9a7c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 17:39:01.133   872  2100 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 17:39:02.186  3773  3773 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 17:39:02.191  3773  3773 D AndroidRuntime: CheckJNI is OFF
08-25 17:39:02.227  3773  3773 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 17:39:02.295  3773  3773 I Radio-JNI: register_android_hardware_Radio DONE
08-25 17:39:02.346  3773  3773 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 17:39:02.356   872  1920 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 17:39:02.392  2000  3728 W SearchService: Abort, client detached.
08-25 17:39:02.397  2000  2000 I HotwordDetector: Closing mic
08-25 17:39:02.398  2000  2317 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@eb4b0d3
08-25 17:39:02.399  2000  2330 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 17:39:02.403  3773  3773 D AndroidRuntime: Shutting down VM
08-25 17:39:02.421   872  2019 I ActivityManager: Start proc 3782:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 17:39:02.449   375  2333 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 17:39:02.450   375  2333 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 17:39:02.457   375  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 17:39:02.463  2000  2329 I MicroRecognitionRnrImpl: Detection finished
08-25 17:39:02.463  2000  2325 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 17:39:02.554  3782  3782 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 17:39:02.591  3782  3782 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 17:39:02.608  3782  3782 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 8636-8646)
08-25 17:39:02.608  3782  3782 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:39:02.636  3782  3782 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e5ed047}
08-25 17:39:02.636  3782  3782 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:39:02.636  3782  3782 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:39:02.654  3782  3782 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 17:39:02.656  3782  3782 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 17:39:02.686  3782  3782 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 17:39:02.722  3782  3782 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:39:02.722  3782  3782 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:39:02.722  3782  3782 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:39:02.722  3782  3782 I Adreno  : Build Date                       : 10/20/15
08-25 17:39:02.722  3782  3782 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:39:02.722  3782  3782 I Adreno  : Local Branch                     : M14
08-25 17:39:02.722  3782  3782 I Adreno  : Remote Branch                    : 
08-25 17:39:02.722  3782  3782 I Adreno  : Remote Branch                    : 
08-25 17:39:02.722  3782  3782 I Adreno  : Reconstruct Branch               : 
,08-25 17:39:02.811   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8935280:true
,08-25 17:39:02.891  3782  3782 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 17:39:02.910  3782  3782 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 17:39:03.000  3782  3822 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 17:39:03.008  3782  3808 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 17:39:03.075  3782  3822 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 17:39:03.181   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +780ms
,08-25 17:39:03.193  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-25 17:39:03.265  3782  3782 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3782
,08-25 17:39:03.303   872  1398 I ActivityManager: Killing 3217:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 17:39:03.348   872  1398 I ActivityManager: Killing 3090:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-25 17:39:03.404  3782  3782 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 17:39:03.565  3782  3825 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684272848
,08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 17:39:03.573  3782  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21df42a added. We now have 1 listener(s)
,08-25 17:39:03.588  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 17:39:03.593  3782  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:03.593  3782  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:03.593  3782  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 17:39:03.600  3782  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e02a191 added. We now have 1 listener(s)
08-25 17:39:03.600  3782  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:03.608   872  1312 D WifiService: New client listening to asynchronous messages
,08-25 17:39:03.610  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:03.610  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 17:39:03.612  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-25 17:39:03.613  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-25 17:39:03.614  3782  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 17:39:03.617  3782  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:03.617  3782  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 17:39:03.623  3782  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:03.623  3782  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:03.623  3782  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 17:39:03.624  3782  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:03.626  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:03.627  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:03.630  3782  3825 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 17:39:03.820  3782  3782 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 17:39:04.601  3782  3833 W jxcore-log: Initializing JXcore engine
,08-25 17:39:04.601  3782  3833 W jxcore-log: JXcore engine is ready
,08-25 17:39:04.642  3833  3833 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 17:39:04.642  3833  3833 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11788]" dev="sockfs" ino=11788 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-25 17:39:04.642  3833  3833 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 17:39:04.642  3833  3833 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26423]" dev="sockfs" ino=26423 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,08-25 17:39:04.678  3782  3833 W jxcore-log: Starting JXcore engine
,08-25 17:39:04.788  3782  3833 W jxcore-log: Platform android
08-25 17:39:04.788  3782  3833 W jxcore-log: 
,08-25 17:39:04.788  3782  3833 W jxcore-log: Process ARCH arm
08-25 17:39:04.788  3782  3833 W jxcore-log: 
,08-25 17:39:04.989  3782  3833 I jxcore-log: JXcore Cordova bridge is ready!
08-25 17:39:04.989  3782  3833 I jxcore-log: 
,08-25 17:39:04.989  3782  3833 W jxcore-log: JXcore engine is started
,08-25 17:39:04.997  3782  3825 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 17:39:05.000  3782  3782 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 17:39:07.246   872  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 17:39:10.760  3042  3840 V KeepSync: Connecting to GoogleApiClient
,08-25 17:39:10.760   872  1922 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 17:39:10.814  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:10.817  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:10.855  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 17:39:10.856  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-25 17:39:10.856  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 17:39:10.856  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:10.884  1728  3841 V BaseAuthAsyncOperation: access token request failed
,08-25 17:39:10.885  3042  3840 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 17:39:10.960  1511  2424 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 17:39:10.960  1511  2424 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 17:39:10.961  1511  2424 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 17:39:10.961  1511  2424 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:10.987  3042  3840 E KeepSync: IOException
08-25 17:39:10.987  3042  3840 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 17:39:10.987  3042  3840 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 17:39:10.987  3042  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 17:39:10.987  3042  3840 E KeepSync: 	... 10 more
,08-25 17:39:10.988  3042  3840 W KeepSync: Sync result 2
,08-25 17:39:11.000   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126025, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 17:39:12.665  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:12.682  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 17:39:12.682  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 17:39:12.682  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:39:12.682  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:12.693  3512  3512 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 17:39:12.693  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 17:39:12.694  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-25 17:39:14.776  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 17:39:14.776  3782  3833 I jxcore-log: 
,08-25 17:39:14.778  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 17:39:14.778  3782  3833 I jxcore-log: 
,08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:14.789  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:14.794  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:14.796  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 17:39:14.796  3782  3833 I jxcore-log: 
,08-25 17:39:14.799  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 17:39:14.799  3782  3833 I jxcore-log: 
,08-25 17:39:15.339  3782  3833 D executeNativeTests: Running unit tests
,08-25 17:39:15.393  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:15.394  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b added. We now have 2 listener(s)
08-25 17:39:15.395  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:15.395  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:15.395  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:15.395  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:15.395  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 added. We now have 2 listener(s)
,08-25 17:39:15.395  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:15.396  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:15.398  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.414  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:15.417  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:15.417  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:15.419  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 17:39:15.419  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:39:15.420  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:39:15.423  3782  3833 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 17:39:15.424  3782  3833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-25 17:39:15.424  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 17:39:15.424  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 17:39:15.425  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 17:39:15.425  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.426  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.427  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.427  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.427  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.428  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.428  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.429  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:15.429  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:15.430  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b removed from the list
08-25 17:39:15.430  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.431  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 removed from the list
,08-25 17:39:15.431  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.431  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.433  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.433  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 17:39:15.435  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.435  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:15.435  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.435  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.436  3782  3833 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 17:39:15.437  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.437  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.437  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.437  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.437  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.437  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.437  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.437  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.437  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.438  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.438  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.438  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.438  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.438  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.439  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.439  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:15.439  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.439  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:39:15.444  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:39:15.445  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:39:15.445  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.446  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:15.446  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.446  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.446  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.446  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.446  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.446  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.446  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.446  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.446  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.446  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.446  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.446  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.447  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.447  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.447  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.447  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.448  3782  3833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 17:39:15.449  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.453  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:15.455  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.457  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:15.458  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:15.459  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:15.459  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 17:39:15.459  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.459  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.459  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:15.460  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.463  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:39:15.463  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:15.467  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:15.469  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 17:39:15.469  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 17:39:15.470  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 17:39:15.472  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 17:39:15.472  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:15.472  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:15.473  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 17:39:15.473  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:15.477  2667  2801 D BtGatt.GattService: registerClient() - UUID=cced25fc-2d45-48bf-8880-98cd4f589490
08-25 17:39:15.478  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=cced25fc-2d45-48bf-8880-98cd4f589490, clientIf=5
,08-25 17:39:15.479  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:39:15.480  2667  2821 D BtGatt.GattService: start scan with filters
,08-25 17:39:15.482  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:15.482  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:15.482  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 17:39:15.483  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:15.483  2667  2703 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:15.485  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:15.485  2667  2703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:15.485  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:15.485  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:15.486  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:15.488  3782  3833 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:39:15.490  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:15.490  3782  3833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:15.490  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.490  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:15.490  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.490  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 17:39:15.490  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:15.490  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:15.490  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:15.490  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:15.491  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 17:39:15.491  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:15.491  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:15.493  2667  2801 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:39:15.493  2667  2821 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 17:39:15.494  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 17:39:15.494  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:15.494  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.494  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 17:39:15.494  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:15.494  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:15.494  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:15.494  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 17:39:15.495  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.495  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:15.495  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:15.495  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:15.496  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:15.497  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:15.497  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.497  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.497  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:15.497  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.497  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.497  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.497  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.497  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.497  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.497  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.498  3782  3833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:39:15.499  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.500  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:15.501  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.501  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 17:39:15.501  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.505  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:15.508  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.508  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:15.508  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:15.508  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:15.508  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 17:39:15.508  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.508  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:15.510  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:39:15.511  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.512  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:39:15.512  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:15.512  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.516  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 17:39:15.516  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.517  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.519  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:15.520  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:39:15.520  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:15.527  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 17:39:15.527  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:15.527  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:15.528  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:15.530  2667  2821 D BtGatt.GattService: registerClient() - UUID=fa98f6bf-14b5-40dd-bf6f-c73a1e6f2954
,08-25 17:39:15.531  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=fa98f6bf-14b5-40dd-bf6f-c73a1e6f2954, clientIf=5
08-25 17:39:15.531  3782  3794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:39:15.531  2667  2801 D BtGatt.GattService: start scan with filters
08-25 17:39:15.532  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 17:39:15.532  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.532  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:15.535  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:15.535  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:15.535  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:15.535  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:15.538  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:15.538  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:39:15.538  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:15.539  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:15.541  3782  3833 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:39:15.544  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:15.544  3782  3833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:15.544  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.544  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:15.544  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.544  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 17:39:15.544  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:15.544  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:15.544  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:15.544  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:39:15.544  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:39:15.544  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.545  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 17:39:15.544  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:15.545  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:15.545  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:15.546  2667  2679 D BtGatt.GattService: stopScan() - queue size =0
08-25 17:39:15.548  2667  2801 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:39:15.548  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:15.548  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:15.549  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:15.549  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 17:39:15.549  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 17:39:15.552  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.552  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 17:39:15.552  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:15.552  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:15.553  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:15.555  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.555  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 17:39:15.555  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.555  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.555  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:15.555  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.555  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.555  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.556  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.556  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.556  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.557  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.557  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.557  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:15.558  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.560  2667  2703 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:15.560  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.560  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.560  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.561  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.561  3782  3833 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:39:15.564  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:15.570  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 17:39:15.570  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.570  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.574  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:15.578  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:15.578  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.578  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 17:39:15.578  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:39:15.579  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.579  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:15.580  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:15.580  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 17:39:15.580  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:15.580  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.580  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:15.582  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.587  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:39:15.587  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.587  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:15.594  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 17:39:15.594  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.596  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:15.597  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:39:15.597  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:15.603  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:15.603  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:15.603  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:15.604  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:39:15.604  3782  3833 D BluetoothAdapter: STATE_ON
08-25 17:39:15.604  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.606  2667  2678 D BtGatt.GattService: registerClient() - UUID=ddbc1b8d-e200-4aab-b042-d5b993671298
08-25 17:39:15.607  2667  2700 D BtGatt.GattService: onClientRegistered() - UUID=ddbc1b8d-e200-4aab-b042-d5b993671298, clientIf=5
,08-25 17:39:15.608  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 17:39:15.609  2667  2679 D BtGatt.GattService: start scan with filters
,08-25 17:39:15.612  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:39:15.613  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.613  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:39:15.616  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 17:39:15.616  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:15.616  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:15.617  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:15.619  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:15.620  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 17:39:15.620  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.621  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:15.621  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:39:15.621  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:39:15.622  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:15.624  3782  3833 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:39:15.624  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.624  3782  3833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:39:15.624  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:15.624  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:39:15.625  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.625  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:15.625  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:39:15.625  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 17:39:15.625  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:15.625  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:15.625  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:15.625  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:15.626  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:15.626  2667  2679 D BtGatt.GattService: stopScan() - queue size =0
08-25 17:39:15.626  2667  2821 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 17:39:15.627  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:15.627  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 17:39:15.627  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:15.627  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:15.627  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 17:39:15.628  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.628  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:15.628  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:15.628  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:15.629  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:15.630  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.630  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.630  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:15.631  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.631  3782  3833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 17:39:15.631  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.631  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.631  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.631  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.631  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:15.631  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.631  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.631  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.631  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.631  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.632  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.632  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:15.632  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.632  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.635  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:15.635  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.635  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.635  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.635  3782  3833 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 17:39:15.636  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.636  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:15.636  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.636  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.636  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.636  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.636  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.636  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.636  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.636  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.636  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.636  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.636  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.637  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.637  2667  2703 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:15.638  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.638  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.638  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.638  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.642  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 17:39:15.642  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.643  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.643  2667  2700 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:39:15.643  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.644  2667  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:39:15.643  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.645  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.645  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.645  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.646  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.646  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.646  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.646  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.646  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.646  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.647  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.647  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.648  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:15.648  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.649  2667  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:15.649  2667  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 17:39:15.655  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:15.655  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.655  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.655  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.656  3782  3833 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 17:39:15.657  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.657  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.657  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.657  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:15.657  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.657  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.657  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
,08-25 17:39:15.657  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.657  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.658  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.658  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.658  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.658  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.658  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.659  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.659  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.659  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.659  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.660  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-25 17:39:15.660  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.660  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.660  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:15.660  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:15.661  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.661  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.661  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.661  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.662  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.662  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.662  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.662  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.662  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.662  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.665  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.665  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.666  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.668  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.668  2667  2700 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:39:15.668  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.670  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:39:15.673  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:39:15.674  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:39:15.674  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.673  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:39:15.675  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:15.677  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:39:15.677  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:39:15.678  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:15.681  2667  2700 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:39:15.681  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.680  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.681  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.681  2667  2703 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:39:15.681  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:15.682  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.682  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.682  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
,08-25 17:39:15.682  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.682  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.682  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.682  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.683  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.684  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.684  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.685  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.686  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.686  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.686  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.686  2667  2700 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 17:39:15.686  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:15.687  2667  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:39:15.687  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:15.687  3782  3833 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:39:15.687  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 17:39:15.691  2667  2700 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:15.691  2667  2700 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:15.695  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 17:39:15.695  3782  3833 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 17:39:15.695  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:39:15.695  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:39:15.696  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:39:15.697  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:39:15.697  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 17:39:15.698  3782  3833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:15.698  3782  3833 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 17:39:15.698  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:15.698  3782  3833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:15.698  3782  3833 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-25 17:39:15.699  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:15.700  3782  3833 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:39:15.700  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 17:39:15.703  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 17:39:15.704  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 17:39:15.704  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 17:39:15.705  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 17:39:15.705  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-25 17:39:15.705  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 17:39:15.705  3782  3833 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:39:15.705  3782  3833 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 17:39:15.706  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.706  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.706  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:15.706  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.706  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.706  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.707  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 17:39:15.707  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
,08-25 17:39:15.707  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.707  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.707  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.707  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.707  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.708  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.708  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.708  3782  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
,08-25 17:39:15.709  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.709  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.709  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.709  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.709  3782  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-25 17:39:15.709  3782  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-25 17:39:15.709  3782  3833 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 17:39:15.710  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:15.710  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.710  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.710  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:15.710  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.710  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.710  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.710  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.710  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.710  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.711  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.711  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.711  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.711  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.712  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.712  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.712  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.712  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.713  3782  3833 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 17:39:15.713  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.713  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:15.713  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.713  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.713  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.713  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.713  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.714  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.714  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.714  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.714  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.714  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.714  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.714  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.715  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.715  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.715  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.715  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.716  3782  3833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 17:39:15.716  3782  3833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 17:39:15.716  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:15.716  3782  3833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 17:39:15.716  3782  3833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:39:15.716  3782  3833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 17:39:15.716  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 17:39:15.717  3782  3833 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 17:39:15.717  3782  3833 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-25 17:39:15.717  3782  3833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:39:15.717  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:39:15.717  3782  3833 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-25 17:39:15.717  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.717  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.717  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.717  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.717  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.717  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.718  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.718  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.718  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.718  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:15.718  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.718  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.718  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.718  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.719  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:15.719  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.719  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.719  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.720  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.720  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.720  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.720  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.720  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.720  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.720  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.720  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.720  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.720  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.720  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.720  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.720  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.720  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:15.721  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.721  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:15.721  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.721  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.721  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.721  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.721  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.721  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.721  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.722  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.722  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.722  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.722  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.722  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.722  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.722  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:15.723  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.723  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.723  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.724  3782  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 17:39:15.724  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.725  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 17:39:15.725  3782  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 17:39:15.725  3782  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 17:39:15.726  3782  3782 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 17:39:15.726  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 17:39:15.726  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:39:15.726  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.726  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 17:39:15.726  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 17:39:15.726  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 17:39:15.726  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.726  3782  3833 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 17:39:15.727  3782  3782 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 17:39:15.727  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.727  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.727  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:15.727  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:15.727  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:15.727  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.727  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.728  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.728  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.728  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:15.728  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:15.729  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.729  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.729  3782  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:39:15.729  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.729  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.729  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.730  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.730  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.730  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
,08-25 17:39:15.730  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.730  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
,08-25 17:39:15.730  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.730  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.730  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.730  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.731  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.731  3782  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 17:39:15.731  3782  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 17:39:15.731  3782  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 17:39:15.732  3782  3782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 17:39:15.732  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.732  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.733  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:15.733  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.734  3782  3833 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 17:39:15.734  3782  3833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:39:15.734  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:39:15.735  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:39:15.735  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.735  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.735  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.735  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.735  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:15.735  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.735  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.735  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.735  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.735  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.735  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.735  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.736  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.736  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.737  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.737  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.737  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.737  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.740  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.740  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:15.740  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.741  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.741  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.741  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.741  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
08-25 17:39:15.741  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.741  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.741  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.741  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.741  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.741  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.741  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.742  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:15.742  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.742  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.742  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.743  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:15.743  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:15.743  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:15.743  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:15.743  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.743  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.743  3782  3833 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d38c2b not in the list
,08-25 17:39:15.743  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.743  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.743  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:15.744  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.744  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.744  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:15.744  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:15.744  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:15.744  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:15.744  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:15.744  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e09f888 not in the list
08-25 17:39:15.745  3782  3833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 17:39:15.745  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:15.745  3782  3833 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-25 17:39:15.745  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:39:15.745  3782  3833 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 17:39:15.745  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:39:15.747  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:39:15.747  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 17:39:15.747  3782  3833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 17:39:15.747  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-25 17:39:15.747  3782  3833 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 17:39:15.747  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-25 17:39:15.747  3782  3833 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 17:39:15.747  3782  3833 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-25 17:39:15.748  3782  3833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-25 17:39:15.748  3782  3833 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-25 17:39:15.749  3782  3833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 17:39:15.749  3782  3833 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 17:39:15.749  3782  3833 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-25 17:39:15.749  3782  3833 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 17:39:15.749  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:15.750  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@638e82a added. We now have 2 listener(s)
08-25 17:39:15.750  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:15.752  3782  3833 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 17:39:15.752   872  1694 D WifiService: setWifiEnabled: true pid=3782, uid=10000
08-25 17:39:15.752   872  1694 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:39:15.753  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:15.753  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@773d61b added. We now have 3 listener(s)
08-25 17:39:15.753  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:15.758  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:15.758  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7093b8 added. We now have 4 listener(s)
08-25 17:39:15.758  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:15.759  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:15.759  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4412591 added. We now have 5 listener(s)
08-25 17:39:15.759  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:15.761   872   882 D WifiService: setWifiEnabled: false pid=3782, uid=10000
08-25 17:39:15.761   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:39:15.763  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:15.764  2667  2696 D BluetoothAdapterState: Current state: ON, message: 23
08-25 17:39:15.764  2667  2696 D BluetoothAdapterProperties: Setting state to 13
08-25 17:39:15.764  2667  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:39:15.765  2667  2696 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:39:15.765  2667  2696 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:15.767  2667  2667 D BluetoothMapService: onReceive
08-25 17:39:15.767  2667  2667 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:15.767  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.767  2667  2667 D BluetoothMapService: STATE_TURNING_OFF
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.767  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:15.768  2667  2667 D BluetoothMapService: MAP Service closeService in
08-25 17:39:15.768  2667  2667 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 17:39:15.768  2667  2667 D ObexServerSockets0: shutdown(block = true)
08-25 17:39:15.768  2667  2822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 17:39:15.768  2667  2667 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 17:39:15.769  2667  2667 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 17:39:15.769  2667  2823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 17:39:15.769  2667  2796 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 17:39:15.769  2667  2667 I BtOppRfcommListener: stopping Accept Thread
08-25 17:39:15.770  2667  3456 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:39:15.770  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.770  2667  3456 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:39:15.770  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.770  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:39:15.772  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.773  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.776  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:15.776  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:15.776  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.776  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:15.777  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:39:15.778   872  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:39:15.778   872  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 17:39:15.778   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:15.778   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:39:15.778  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.784   872   885 I ActivityManager: Start proc 3852:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-25 17:39:15.785  2667  2700 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:39:15.785  2667  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 17:39:15.789  2667  2667 D HeadsetService: Received stop request...Stopping profile...
,08-25 17:39:15.789  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.790  1927  1939 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:15.791   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 17:39:15.791   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:15.791  1357  1369 D BluetoothHeadset: Proxy object disconnected
,08-25 17:39:15.791  2667  2667 D A2dpService: Received stop request...Stopping profile...
08-25 17:39:15.792  2667  2804 D A2dpStateMachine: Exit Disconnected: -1
08-25 17:39:15.792   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:15.793  2667  2667 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:15.793  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:15.793  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:15.793  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:15.793   872   872 D BluetoothA2dp: Proxy object disconnected
,08-25 17:39:15.795  2667  2667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:39:15.794   872  2103 D DhcpClient: Clearing IP address
08-25 17:39:15.794   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:39:15.795  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 17:39:15.795  2667  2667 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:39:15.795  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:15.795  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:15.795  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:39:15.795  2667  2700 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 17:39:15.796  2667  2667 D HidService: Received stop request...Stopping profile...
08-25 17:39:15.796  2667  2667 D HidService: Stopping Bluetooth HidService
08-25 17:39:15.797  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.798  2667  2667 V BluetoothAdapterState: isTurningOff()=true
08-25 17:39:15.798  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:15.798  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:15.798  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:15.799  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 17:39:15.799  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:15.799  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:15.799  2667  2775 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:39:15.799  2667  2775 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:15.799  2667  2775 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:15.799  2667  2667 D HealthService: Received stop request...Stopping profile...
08-25 17:39:15.799  2667  2775 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 17:39:15.800   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:15.802  2667  2667 D PanService: Received stop request...Stopping profile...
08-25 17:39:15.802   872  2106 D DhcpClient: Receive thread stopped
08-25 17:39:15.803  1511  2546 V NativeCrypto: Read error: ssl=0x9b053c00: I/O error during system call, Connection timed out
08-25 17:39:15.803  2667  2667 V BluetoothAdapterState: isTurningOff()=true
08-25 17:39:15.803  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:15.803  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:15.803  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:15.803  2667  2667 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:39:15.803  2667  2667 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-25 17:39:15.803  2667  2700 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 17:39:15.804  2667  2667 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:39:15.804  2667  2667 D BluetoothMapService: stop()
08-25 17:39:15.805  1511  2546 V NativeCrypto: SSL shutdown failed: ssl=0x9b053c00: I/O error during system call, Broken pipe
,08-25 17:39:15.805  2667  2667 D BluetoothMapAppObserver: deinitObservers()
08-25 17:39:15.805  2667  2667 D BluetoothMapAppObserver: removeReceiver()
08-25 17:39:15.807   872  1694 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 17:39:15.807   872  2096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-25 17:39:15.810   402   402 E Parcel  : Reading a NULL string not supported here.
08-25 17:39:15.810   872  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-25 17:39:15.811   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:39:15.811   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-25 17:39:15.812   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:15.815  2667  2667 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:15.815  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:15.815  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:15.815  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:15.816  2667  2667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 17:39:15.816  2667  2700 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 17:39:15.816  2667  2667 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:39:15.816  2667  2667 V BluetoothAdapterState: isTurningOff()=true
08-25 17:39:15.816  2667  2667 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:15.816  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:15.816  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:15.817  2667  2667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:39:15.817  2667  2667 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:39:15.818  2667  2667 D BluetoothMapService: MAP Service closeService in
08-25 17:39:15.818  2667  2667 V BluetoothAdapterState: isTurningOff()=true
08-25 17:39:15.818  2667  2667 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:15.819  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:15.819  2667  2667 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:15.819  2667  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 17:39:15.819  2667  2696 D BluetoothAdapterProperties: Setting state to 15
08-25 17:39:15.819  2667  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 17:39:15.820   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:15.820   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:15.821  2667  2696 I BluetoothAdapterState: Entering BleOnState
08-25 17:39:15.821  1357  1372 D BluetoothPan: onBluetoothStateChange on: false
08-25 17:39:15.822  2667  2667 D BluetoothMapService: cleanup()
08-25 17:39:15.822  2667  2667 D BluetoothMapService: MAP Service closeService in
08-25 17:39:15.823   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:39:15.822   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:15.822   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 17:39:15.824  1357  2023 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:15.827  1357  1369 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:15.828  1927  2062 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:15.828   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:15.828  1357  2023 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:39:15.829  1357  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:39:15.829  1357  1357 D HeadsetProfile: Bluetooth service disconnected
08-25 17:39:15.829  1357  1372 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:39:15.830  2667  2696 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 17:39:15.830  2667  2696 D BluetoothAdapterProperties: Setting state to 16
08-25 17:39:15.830  2667  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 17:39:15.831   872  2096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 17:39:15.832  2667  2696 D BluetoothAdapterProperties: onBleDisable
08-25 17:39:15.832  2667  2697 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 17:39:15.832  2667  2696 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:39:15.833  2667  2775 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 17:39:15.833  2667  2700 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:39:15.833  2667  2775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:15.834  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is ,Wi-Fi enabled: true
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:15.834  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:15.835  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.835  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:15.836  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:15.836  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:15.837  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.837  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:15.839  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.840  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:15.840  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:15.841  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.841  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:15.842  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:15.842  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:15.844  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:15.844  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:15.845   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 17:39:15.845  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.846  2042  2306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:39:15.847   872  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 17:39:15.862   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 17:39:15.868  3852  3852 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-25 17:39:15.876  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:15.881  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:15.885   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99e0e91:true
08-25 17:39:15.889   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 17:39:15.889   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 17:39:15.890   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:15.893   872  1956 I ActivityManager: Start proc 3869:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-25 17:39:15.896   872   889 D Tethering: MasterInitialState.processMessage what=3
08-25 17:39:15.900  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:15.900  3400  3400 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9a1f21b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 17:39:15.901  2000  2000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-25 17:39:15.902  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:15.942   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-25 17:39:15.943   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 17:39:15.945  3852  3852 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 17:39:15.947  3852  3852 D BluetoothMap: Create BluetoothMap proxy object
,08-25 17:39:15.954  3852  3852 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 17:39:15.959  3869  3869 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 17:39:15.968  3852  3852 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:15.987   872  1932 I ActivityManager: Killing 2990:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 17:39:16.039  2667  2700 I bt_hci  : shut_down
,08-25 17:39:16.052  2667  2704 I bt_vendor: low_power_mode_cb
,08-25 17:39:16.056  2667  2704 D bt_hwcfg: hw_epilog_process
,08-25 17:39:16.073  2667  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 17:39:16.073  2667  2704 I bt_vendor: epilog_cb
08-25 17:39:16.073  2667  2704 I bt_hci  : epilog_finished_callback
,08-25 17:39:16.077  2667  2700 I bt_hci_h4: hal_close
,08-25 17:39:16.078  2667  2700 I bt_userial_vendor: device fd = 51 close
,08-25 17:39:16.117  3869  3869 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:39:16.117  3869  3869 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.117  3869  3869 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.117  3869  3869 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.117  3869  3869 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.117  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.118  3869  3869 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.118  3869  3869 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.118  3869  3869 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:39:16.118  3869  3869 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:39:16.138  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:16.143  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:16.145  3852  3852 D DockEventReceiver: finishStartingService: stopping service
08-25 17:39:16.146   872  1957 I ActivityManager: Killing 3400:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 17:39:16.229  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:16.248   872  1957 I ActivityManager: Start proc 3903:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 17:39:16.260  2667  2697 D bt_stack_manager: event_shut_down_stack finished.
,08-25 17:39:16.261  2667  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 17:39:16.263  2667  2696 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 17:39:16.263  2667  2667 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:39:16.264  2667  2667 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:39:16.264  2667  2667 D BtGatt.GattService: stop()
,08-25 17:39:16.264  2667  2667 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 17:39:16.265  2667  2667 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:16.266  2667  2667 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:16.266  2667  2667 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:16.266  2667  2667 V BluetoothAdapterState: isBleTurningOff()=true
08-25 17:39:16.266  2667  2696 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 17:39:16.266  2667  2696 D BluetoothAdapterProperties: Setting state to 10
,08-25 17:39:16.266  2667  2696 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 17:39:16.266  2667  2696 I BluetoothAdapterState: Entering OffState
08-25 17:39:16.267   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 17:39:16.272  2667  2667 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 17:39:16.273  2667  2667 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 17:39:16.273  2667  2667 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 17:39:16.274  2667  2697 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 17:39:16.275  2667  2697 D bt_stack_manager: event_clean_up_stack finished.
,08-25 17:39:16.277  2667  2667 I art     : System.exit called, status: 0
,08-25 17:39:16.277  2667  2667 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 17:39:16.301  3903  3903 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 17:39:16.318   872  2019 I ActivityManager: Process com.android.bluetooth (pid 2667) has died
,08-25 17:39:16.389  3903  3903 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 17:39:16.430  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:39:16.436  1728  1728 D SystemUpdateService: onCreate
,08-25 17:39:16.448  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:39:16.452  1728  3931 I SystemUpdateService: active receiver: enabled
,08-25 17:39:16.453  3869  3892 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 17:39:16.456  1728  3931 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:39:16.458  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 17:39:16.466  1728  3931 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 17:39:16.469  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 17:39:16.470  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 17:39:16.473  1728  3931 I SystemUpdateService: now status is 0 (complete)
,08-25 17:39:16.476  1728  3931 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 17:39:16.476  1728  3931 I SystemUpdateService: file has been verified
08-25 17:39:16.476  1728  3931 I SystemUpdateService: OTA package size = 12249756
,08-25 17:39:16.479  1728  2523 I iu.UploadsManager: num queued entries: 0
,08-25 17:39:16.480  1728  2523 I iu.UploadsManager: num updated entries: 0
,08-25 17:39:16.481  1728  2523 I iu.SyncManager: NEXT; no task
08-25 17:39:16.483  1728  3931 I SystemUpdateService: showing system update notification
08-25 17:39:16.487   872  1694 I ActivityManager: Start proc 3933:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 17:39:16.496   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e73ee2:true
,08-25 17:39:16.500  1728  1728 D SystemUpdateService: onDestroy
,08-25 17:39:16.517  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 17:39:16.519  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:16.528  3933  3933 D SprintDMHelper: simOperator: 
,08-25 17:39:16.528  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,08-25 17:39:16.542   872  1955 I ActivityManager: Start proc 3945:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 17:39:16.543   872  1955 I ActivityManager: Killing 3466:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 17:39:16.656  2405  3959 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 17:39:16.666   872  1387 I ActivityManager: Start proc 3960:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 17:39:16.671   872  1387 I ActivityManager: Killing 1708:android.process.acore/u0a5 (adj 15): empty #17
,08-25 17:39:16.750  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 17:39:16.813  3960  3960 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 17:39:16.813  3960  3960 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 17:39:16.813  3960  3960 I GAv4    :   adb logcat -s GAv4
,08-25 17:39:16.828  3960  3960 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:39:16.835  3960  3960 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:39:16.861  3960  3977 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:39:16.979  3960  3960 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 17:39:17.020  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 17:39:17.030  3960  3960 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3065-3068)
,08-25 17:39:17.030  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:39:17.039  3960  3960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d5f980b}
,08-25 17:39:17.039  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:39:17.039  3960  3960 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:39:17.048  3960  3960 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 17:39:17.050  3960  3960 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 17:39:17.067  3960  3960 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 17:39:17.081  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:39:17.081  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:39:17.081  3960  3960 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:39:17.081  3960  3960 I Adreno  : Build Date                       : 10/20/15
08-25 17:39:17.081  3960  3960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:39:17.081  3960  3960 I Adreno  : Local Branch                     : M14
08-25 17:39:17.081  3960  3960 I Adreno  : Remote Branch                    : 
08-25 17:39:17.081  3960  3960 I Adreno  : Remote Branch                    : 
08-25 17:39:17.081  3960  3960 I Adreno  : Reconstruct Branch               : 
,08-25 17:39:17.150  3960  3960 I NSApplication: Starting up...
,08-25 17:39:17.164  3960  4006 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 17:39:17.200   872  2015 I ActivityManager: Start proc 4011:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 17:39:17.201   872  2015 I ActivityManager: Killing 3632:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 17:39:17.288  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 17:39:17.519   872  2015 I ActivityManager: Killing 3647:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 17:39:17.534  3551  3561 W art     : Suspending all threads took: 5.684ms
,08-25 17:39:18.775   872  1956 D WifiService: setWifiEnabled: true pid=3782, uid=10000
,08-25 17:39:18.776   872  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-25 17:39:18.787   872  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-25 17:39:18.798  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:18.799  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:18.799  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:18.800  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:18.804  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:18.805  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:18.805  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:18.806  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:18.834   872  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-25 17:39:18.835   872  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 17:39:18.835   872  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 17:39:18.836   872  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 17:39:18.836   872  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 17:39:18.836   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 17:39:18.837   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 17:39:18.850   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 17:39:18.851   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:18.852   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 17:39:18.852   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 17:39:18.852   872  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.88 rxSuccessRate=13.38 delta 1000 -> 994
,08-25 17:39:18.855   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 17:39:18.855   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62,
,08-25 17:39:18.873   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 17:39:18.874   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:18.881   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 17:39:18.930   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 17:39:18.934  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 17:39:19.355  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:39:19.395  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:39:19.395  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 17:39:19.400   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:39:19.413   872  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:39:19.413   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 17:39:19.414   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:19.432   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:19.442   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:19.447   872  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 17:39:19.459   872  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 17:39:19.461   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 17:39:19.485   872  4034 D DhcpClient: Receive thread started
,08-25 17:39:19.568   872  1311 E native  : do suspend false
,08-25 17:39:19.588   872  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 17:39:19.601   872  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,08-25 17:39:19.602   872  2103 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,08-25 17:39:19.606   872  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 17:39:19.619   872  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 17:39:19.621   872  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 17:39:19.625   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:19.637   872  2103 D DhcpClient: Scheduling renewal in 86399s
,08-25 17:39:19.637   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 17:39:19.657   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 17:39:19.660   872  1311 D WifiConfigStore: No blacklist allowed without epno enabled
08-25 17:39:19.661   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.662   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 17:39:19.670   872  1313 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 17:39:19.676   872  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:39:19.716   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 17:39:19.716   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 17:39:19.717   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-25 17:39:19.719   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 17:39:19.720   872  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 17:39:19.727   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.733   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 17:39:19.733   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.733   872  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 17:39:19.733   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.733   872  1313 D ConnectivityService:    accepting network in place of null
,08-25 17:39:19.734   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:19.735   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:39:19.746   872  4033 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135785, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 17:39:19.765   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:19.799   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:19.807   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 17:39:19.808   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:19.812   872  4032 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:4001:815::200e
,08-25 17:39:19.819   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:39:19.824   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.831  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:19.831  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:19.831  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:19.832  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:19.838  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:19.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:19.838  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:19.838  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:19.843  2000  2000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-25 17:39:19.847  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:39:19.853  1728  1728 D SystemUpdateService: onCreate
,08-25 17:39:19.857  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-25 17:39:19.859  1728  4044 I SystemUpdateService: active receiver: enabled
,08-25 17:39:19.864  1728  4044 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:39:19.865  1728  4044 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 17:39:19.866  1728  4044 I SystemUpdateService: now status is 0 (complete)
08-25 17:39:19.866  1728  4044 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 17:39:19.866  1728  4044 I SystemUpdateService: file has been verified
08-25 17:39:19.866  1728  4044 I SystemUpdateService: OTA package size = 12249756
,08-25 17:39:19.870  1728  4044 I SystemUpdateService: showing system update notification
,08-25 17:39:19.874   872  4032 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:39:19 GMT], X-Android-Received-Millis=[1472139559873], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472139559852]}
,08-25 17:39:19.876  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 17:39:19.879   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 17:39:19.879   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-25 17:39:19.879   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:19.880   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 17:39:19.882  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 17:39:19.883  1728  2523 I iu.UploadsManager: num queued entries: 0
,08-25 17:39:19.884  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 17:39:19.885  1728  4050 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 17:39:19.885  1728  4050 W BaseAppContext: Using Auth Proxy for data requests.
08-25 17:39:19.885  1728  2523 I iu.UploadsManager: num updated entries: 0
08-25 17:39:19.886  1728  2523 I iu.SyncManager: NEXT; no task
08-25 17:39:19.886  1728  4050 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 17:39:19.890  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE,
,08-25 17:39:19.891  1728  1728 D SystemUpdateService: onDestroy
,08-25 17:39:19.897  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:19.900  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:19.906  3933  3933 D SprintDMHelper: simOperator: 
,08-25 17:39:19.907  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:39:19.937  1511  2020 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 17:39:19.938  1511  2020 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 17:39:19.938  1511  2020 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:39:19.938  1511  2020 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:19.956  1728  4050 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-25 17:39:20.014  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 17:39:20.014  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 17:39:20.014  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 17:39:20.014  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:20.018  2405  4053 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 17:39:20.036  3551  4046 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 17:39:20.036  3551  4046 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jdm.a(PG:82)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jcs.o(PG:406)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jcn.a(PG:1379)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jcs.i(PG:143)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at blb.a(PG:3937)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at czp.a(PG:18188)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at czp.a(PG:9081)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at czq.run(PG:1686)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 17:39:20.036  3551  4046 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jdj.a(PG:4091)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jdj.a(PG:1125)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jdm.a(PG:77)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	... 12 more
08-25 17:39:20.036  3551  4046 E HttpOperation: Caused by: faj: BadAuthentication
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at fal.a(PG:38)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	at jdj.a(PG:4089)
08-25 17:39:20.036  3551  4046 E HttpOperation: 	... 14 more
,08-25 17:39:20.103  1511  2020 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 17:39:20.103  1511  2020 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 17:39:20.104  1511  2020 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:39:20.104  1511  2020 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:20.123  3551  4046 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 17:39:20.123  3551  4046 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jdm.a(PG:82)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jcs.o(PG:406)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jcn.a(PG:1379)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jcs.i(PG:143)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at hec.a(PG:42)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at hee.a(PG:102)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at czr.a(PG:65)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at kka.a(PG:108)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at czp.a(PG:19176)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at czp.a(PG:9081)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at czq.run(PG:1686)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 17:39:20.123  3551  4046 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jdj.a(PG:4091)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jdj.a(PG:1125)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jdm.a(PG:77)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	... 15 more
08-25 17:39:20.123  3551  4046 E HttpOperation: Caused by: faj: BadAuthentication
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at fal.a(PG:38)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	at jdj.a(PG:4089)
08-25 17:39:20.123  3551  4046 E HttpOperation: 	... 17 more
,08-25 17:39:20.124  3551  4046 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 17:39:20.124  3551  4046 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at hec.a(PG:42)
,08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at hee.a(PG:102)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at czr.a(PG:65)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at kka.a(PG:108)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588),
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	,at java.lang.Thread.run(Thread.java:818)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	... 15 more
08-25 17:39:20.124  3551  4046 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at fal.a(PG:38)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 17:39:20.124  3551  4046 E ExperimentLoader: 	... 17 more
,08-25 17:39:20.216   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128979, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 17:39:20.808   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 17:39:21.498   872  1922 I ActivityManager: Killing 2184:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 17:39:21.783   872  1387 D WifiService: setWifiEnabled: false pid=3782, uid=10000
08-25 17:39:21.784   872  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:39:21.818  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 17:39:21.827   872  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 17:39:21.828   872  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-25 17:39:21.828   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:21.828   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:21.846   872  2103 D DhcpClient: Clearing IP address
,08-25 17:39:21.848   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:21.850   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:21.852  1511  4057 V NativeCrypto: Read error: ssl=0x9b0c4a00: I/O error during system call, Connection timed out
,08-25 17:39:21.855   872  4034 D DhcpClient: Receive thread stopped
08-25 17:39:21.857   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:39:21.858   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-25 17:39:21.859  1511  4057 V NativeCrypto: SSL shutdown failed: ssl=0x9b0c4a00: I/O error during system call, Broken pipe
08-25 17:39:21.861   402   402 E Parcel  : Reading a NULL string not supported here.,
,08-25 17:39:21.866   872  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 17:39:21.870   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:21.874   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:39:21.876   872  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 17:39:21.886  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:21.886  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:21.886  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:21.886  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:21.887  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:21.887  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:21.887  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:21.887  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:21.888   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:39:21.892   872  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 17:39:21.898  2042  2306 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:39:21.911   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:21.928   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:21.929   872  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 17:39:21.930   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:21.932   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:39:21.950  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:21.953  2000  2000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-25 17:39:21.953  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:21.960  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 17:39:21.965  1728  1728 D SystemUpdateService: onCreate
08-25 17:39:21.967  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-25 17:39:21.974  1728  4069 I SystemUpdateService: active receiver: enabled
,08-25 17:39:21.977  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 17:39:21.979  1728  2523 I iu.UploadsManager: num queued entries: 0
08-25 17:39:21.980  1728  2523 I iu.UploadsManager: num updated entries: 0
08-25 17:39:21.980  1728  2523 I iu.SyncManager: NEXT; no task
,08-25 17:39:21.986  1728  4069 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:39:21.987  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 17:39:21.988  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 17:39:21.991  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:22.003   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-25 17:39:22.005  3933  3933 D SprintDMHelper: simOperator: 
08-25 17:39:22.005  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:39:22.018  1728  4069 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 17:39:22.029  1728  4069 I SystemUpdateService: now status is 0 (complete)
,08-25 17:39:22.029  1728  4069 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 17:39:22.029  1728  4069 I SystemUpdateService: file has been verified
08-25 17:39:22.030  1728  4069 I SystemUpdateService: OTA package size = 12249756
,08-25 17:39:22.031  2405  4073 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 17:39:22.052  1728  4069 I SystemUpdateService: showing system update notification
,08-25 17:39:22.065  1728  1728 D SystemUpdateService: onDestroy
,08-25 17:39:24.840   872   889 I ActivityManager: Start proc 4076:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 17:39:24.980  4076  4076 D AdapterServiceConfig: Adding HeadsetService
08-25 17:39:24.981  4076  4076 D AdapterServiceConfig: Adding A2dpService
,08-25 17:39:24.981  4076  4076 D AdapterServiceConfig: Adding HidService
08-25 17:39:24.981  4076  4076 D AdapterServiceConfig: Adding HealthService
08-25 17:39:24.981  4076  4076 D AdapterServiceConfig: Adding PanService
08-25 17:39:24.981  4076  4076 D AdapterServiceConfig: Adding GattService
,08-25 17:39:24.982  4076  4076 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 17:39:24.995   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2f5cbd:true
,08-25 17:39:24.996  4076  4076 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 17:39:25.000  4076  4076 I bt_bluedroid: init
,08-25 17:39:25.001  4076  4088 I BluetoothAdapterState: Entering OffState
,08-25 17:39:25.007  4076  4089 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 17:39:25.007  4076  4089 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 17:39:25.007  4076  4089 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 17:39:25.008  4076  4089 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 17:39:25.010  4076  4076 I bt_bluedroid: get_profile_interface socket
,08-25 17:39:25.012  4076  4076 I bt_bluedroid: get_profile_interface sdp
08-25 17:39:25.012  4076  4092 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 17:39:25.014  4076  4092 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:39:25.018  4076  4087 I bt_bluedroid: config_hci_snoop_log
,08-25 17:39:25.021   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 17:39:25.026  4076  4088 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 17:39:25.026  4076  4088 D BluetoothAdapterProperties: Setting state to 14
08-25 17:39:25.027  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 17:39:25.031  4076  4088 D BluetoothBondStateMachine: make
,08-25 17:39:25.034  4076  4093 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:39:25.040  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:25.041  4076  4076 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 17:39:25.044  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:25.044  4076  4076 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:39:25.045  4076  4076 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:39:25.045  4076  4076 D BtGatt.GattService: start()
08-25 17:39:25.045  4076  4076 I bt_bluedroid: get_profile_interface gatt
,08-25 17:39:25.046  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:25.046  4076  4076 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:39:25.053  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:25.053  4076  4076 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:25.053  4076  4076 V BluetoothAdapterState: isBleTurningOn()=true
08-25 17:39:25.054  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:25.054  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 17:39:25.054  4076  4088 I bt_bluedroid: enable
08-25 17:39:25.055  4076  4089 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 17:39:25.055  4076  4089 I bt_hci  : start_up
,08-25 17:39:25.074  4076  4089 I bt_vendor: alloc value 0xb39db189
08-25 17:39:25.074  4076  4089 I bt_vendor: init
,08-25 17:39:25.075  4076  4089 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 17:39:25.075  4076  4089 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 17:39:25.183  4076  4089 D bt_hci  : start_up starting async portion
,08-25 17:39:25.185  4076  4096 I bt_hci  : event_finish_startup
08-25 17:39:25.185  4076  4096 I bt_hci_h4: hal_open
,08-25 17:39:25.186  4076  4096 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 17:39:25.196  4076  4096 I bt_userial_vendor: device fd = 51 open
,08-25 17:39:25.226  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:39:25.258  4076  4096 D bt_hwcfg: Chipset BCM4354A2
,08-25 17:39:25.258  4076  4096 D bt_hwcfg: Target name = [BCM4354A2]
08-25 17:39:25.259  4076  4096 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 17:39:25.921  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 17:39:25.923  4076  4096 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 17:39:25.923  4076  4096 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 17:39:26.039  4076  4096 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:39:26.041  4076  4096 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 17:39:26.070  4076  4096 I bt_hwcfg: vendor lib fwcfg completed
08-25 17:39:26.071  4076  4096 I bt_vendor: firmware callback
,08-25 17:39:26.071  4076  4096 I bt_hci  : firmware_config_callback
,08-25 17:39:26.082  4076  4098 I bt_btu  : btu_task pending for preload complete event
,08-25 17:39:26.083  4076  4098 I bt_btu_task: Bluetooth chip preload is complete
,08-25 17:39:26.083  4076  4098 I bt_btu  : btu_task received preload complete event
,08-25 17:39:26.094  4076  4098 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 17:39:26.094  4076  4098 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:39:26.095  4076  4098 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 17:39:26.095  4076  4098 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:39:26.095  4076  4098 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 17:39:26.096  4076  4098 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:39:26.096  4076  4098 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 17:39:26.096  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:39:26.096  4076  4098 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:39:26.097  4076  4098 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 17:39:26.097  4076  4098 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:39:26.097  4076  4098 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 17:39:26.097  4076  4098 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:39:26.098  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 17:39:26.098  4076  4098 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:39:26.232  4076  4098 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3958d9d
,08-25 17:39:26.232  4076  4098 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3958d9d 
,08-25 17:39:26.243  4076  4092 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 17:39:26.245  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 17:39:26.246  4076  4092 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 17:39:26.251  4076  4092 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:39:26.255  4076  4092 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:26.255  4076  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:26.255  4076  4092 D bt_hci  : do_postload posting postload work item
,08-25 17:39:26.257  4076  4096 I bt_hci  : event_postload
,08-25 17:39:26.257  4076  4096 I bt_vendor: sco_config_cb
,08-25 17:39:26.257  4076  4096 I bt_hci  : sco_config_callback postload finished.
,08-25 17:39:26.259  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.262  4076  4092 D bt_bte_conf: Device ID record 1 : primary
08-25 17:39:26.262  4076  4092 D bt_bte_conf:   vendorId            = 000f
08-25 17:39:26.263  4076  4092 D bt_bte_conf:   vendorIdSource      = 0001
08-25 17:39:26.263  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.263  4076  4092 D bt_bte_conf:   product             = 1200
08-25 17:39:26.263  4076  4092 D bt_bte_conf:   version             = 1436
08-25 17:39:26.263  4076  4092 D bt_bte_conf:   clientExecutableURL = 
,08-25 17:39:26.264  4076  4092 D bt_bte_conf:   serviceDescription  = 
08-25 17:39:26.264  4076  4092 D bt_bte_conf:   documentationURL    = 
08-25 17:39:26.264  4076  4092 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 17:39:26.265  4076  4089 D bt_stack_manager: event_start_up_stack finished,
08-25 17:39:26.266  4076  4096 I bt_vendor: low_power_mode_cb
08-25 17:39:26.266  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 17:39:26.267  4076  4088 D BluetoothAdapterProperties: Setting state to 15
,08-25 17:39:26.267  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 17:39:26.271  4076  4088 I BluetoothAdapterState: Entering BleOnState
08-25 17:39:26.275  4076  4088 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 17:39:26.276  4076  4088 D BluetoothAdapterProperties: Setting state to 11
,08-25 17:39:26.276  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 17:39:26.282  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.284  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:26.289  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:26.290  4076  4076 D HeadsetService: Received start request. Starting profile...
08-25 17:39:26.293  4076  4076 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:39:26.293  4076  4076 D HeadsetStateMachine: make
,08-25 17:39:26.298  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:26.300  4076  4076 D HeadsetStateMachine: max_hf_connections = 1
,08-25 17:39:26.300  4076  4076 I bt_bluedroid: get_profile_interface handsfree
08-25 17:39:26.300  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 17:39:26.301  4076  4092 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 17:39:26.305  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:26.306  4076  4076 D A2dpService: Received start request. Starting profile...
,08-25 17:39:26.307  4076  4076 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:39:26.307  4076  4076 I bt_bluedroid: get_profile_interface avrcp
,08-25 17:39:26.312  4076  4076 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 17:39:26.313  4076  4076 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:39:26.313  4076  4076 D A2dpStateMachine: make
08-25 17:39:26.314  4076  4076 I bt_bluedroid: get_profile_interface a2dp
,08-25 17:39:26.314  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 17:39:26.321  4076  4107 D A2dpStateMachine: Enter Disconnected: -2
,08-25 17:39:26.322  4076  4076 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:39:26.323  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:26.323  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:26.324  4076  4076 D HidService: Received start request. Starting profile...
08-25 17:39:26.323  3852  3852 D BluetoothInputDevice: Proxy object connected
08-25 17:39:26.324  4076  4076 I bt_bluedroid: get_profile_interface hidhost
08-25 17:39:26.324  4076  4076 D HidService: setHidService(): set to: null
08-25 17:39:26.324  4076  4092 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393a3e5
08-25 17:39:26.324  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 17:39:26.324  4076  4076 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 17:39:26.325  3852  3852 D HidProfile: Bluetooth service connected
08-25 17:39:26.325  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:26.326  4076  4076 D HealthService: Received start request. Starting profile...
,08-25 17:39:26.327  4076  4076 I bt_bluedroid: get_profile_interface health
,08-25 17:39:26.328  4076  4076 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 17:39:26.328  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:26.329  4076  4076 D PanService: Received start request. Starting profile...
,08-25 17:39:26.329  3852  3852 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:26.330  4076  4076 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:39:26.330  4076  4076 I bt_bluedroid: get_profile_interface pan,
08-25 17:39:26.330  4076  4092 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:39:26.331  3852  3852 D PanProfile: Bluetooth service connected
,08-25 17:39:26.333  4076  4076 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:26.334  4076  4076 D BluetoothMapService: Received start request. Starting profile...
,08-25 17:39:26.335  3852  3852 D BluetoothMap: Proxy object connected
08-25 17:39:26.335  4076  4076 D BluetoothMapService: start()
08-25 17:39:26.335  3852  3852 D MapProfile: Bluetooth service connected
08-25 17:39:26.335  3852  3852 D BluetoothMap: getConnectedDevices()
,08-25 17:39:26.335  3852  3852 D BluetoothMap: Bluetooth is Not enabled
08-25 17:39:26.336  4076  4076 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 17:39:26.337  4076  4076 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 17:39:26.337  4076  4076 D BluetoothMapAppObserver: createReceiver()
,08-25 17:39:26.338  4076  4076 D BluetoothMapAppObserver: initObservers()
08-25 17:39:26.338  4076  4076 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 17:39:26.345  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:26.345  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:26.345  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:26.346  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:26.347  4076  4105 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:26.347  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:26.349  4076  4076 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:26.349  4076  4076 V BluetoothAdapterState: isTurningOn()=true
,08-25 17:39:26.349  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:26.349  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:26.349  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:26.350  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:26.350  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 17:39:26.350  4076  4088 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:39:26.351  4076  4088 D BluetoothAdapterProperties: State =  11
,08-25 17:39:26.351  4076  4088 D BluetoothAdapterProperties: Setting state to 12
08-25 17:39:26.351  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:39:26.351   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:26.351  4076  4088 I BluetoothAdapterState: Entering OnState
08-25 17:39:26.352   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:26.352  4076  4092 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:39:26.352  4076  4092 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:39:26.352  1357  1372 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:39:26.353   872   872 D BluetoothA2dp: Proxy object connected
,08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:26.356  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:26.358  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:26.358  1357  1357 D PanProfile: Bluetooth service connected
08-25 17:39:26.358   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:26.358  1357  2023 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:26.358  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:26.360  1357  1357 D BluetoothA2dp: Proxy object connected
,08-25 17:39:26.360  3852  3862 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:39:26.361  1357  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:26.361  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:26.362  1927  2072 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:26.363   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:26.363  3852  3863 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:39:26.363  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:26.363  3852  3862 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 17:39:26.364  4076  4076 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:39:26.365  3852  3863 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:39:26.365  4076  4076 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 17:39:26.365  1357  1369 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:39:26.366  4076  4076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:26.366  1357  2023 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:39:26.368  1357  1357 D BluetoothInputDevice: Proxy object connected
,08-25 17:39:26.368  1357  1369 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:39:26.368  1357  1357 D HidProfile: Bluetooth service connected
,08-25 17:39:26.368  4076  4076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:26.369  4076  4076 D ObexServerSockets: Succeed to create listening sockets 
08-25 17:39:26.369  4076  4076 D ObexServerSockets0: startAccept()
08-25 17:39:26.369  1357  1357 D BluetoothMap: Proxy object connected
08-25 17:39:26.370  1357  1357 D MapProfile: Bluetooth service connected
,08-25 17:39:26.370  4076  4076 D ObexServerSockets0: prepareForNewConnect()
08-25 17:39:26.370  1357  1357 D BluetoothMap: getConnectedDevices()
,08-25 17:39:26.371   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 17:39:26.372  4076  4076 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 17:39:26.372  4076  4076 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 17:39:26.372  4076  4076 D BluetoothMapService: onReceive
08-25 17:39:26.372  4076  4076 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:26.373  4076  4076 D BluetoothMapService: STATE_ON
08-25 17:39:26.373  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:26.374  4076  4113 D ObexServerSockets0: Accepting socket connection...
,08-25 17:39:26.374  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:26.375  4076  4114 D ObexServerSockets0: Accepting socket connection...
,08-25 17:39:26.376  3852  3852 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-25 17:39:26.379  3852  3852 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 17:39:26.384  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:39:26.386  3852  3852 D BluetoothA2dp: Proxy object connected
,08-25 17:39:26.388  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:26.392  3852  3852 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:26.397  3852  3852 D BluetoothPbap: Proxy object connected
,08-25 17:39:26.397  3852  3852 D PbapServerProfile: Bluetooth service connected
08-25 17:39:26.397  1357  1357 D BluetoothPbap: Proxy object connected
08-25 17:39:26.397  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-25 17:39:26.402  4076  4076 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:39:26.403  4076  4076 D ObexServerSockets0: prepareForNewConnect()
,08-25 17:39:26.404  4076  4119 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:26.422  4076  4123 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:26.423  4076  4123 I BtOppRfcommListener: Accept thread started.
,08-25 17:39:26.453  1927  2062 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.453   872   872 D BluetoothHeadset: Proxy object connected
08-25 17:39:26.453   872   872 D BluetoothHeadset: Proxy object connected
08-25 17:39:26.453  1357  1372 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.453  1357  1357 D HeadsetProfile: Bluetooth service connected
08-25 17:39:26.453   872   872 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.458   872   889 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.462  1357  1369 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.462  1357  1357 D HeadsetProfile: Bluetooth service connected
08-25 17:39:26.463  1927  1945 D BluetoothHeadset: Proxy object connected
08-25 17:39:26.463   872   889 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.481  3852  3862 D BluetoothHeadset: Proxy object connected
,08-25 17:39:26.482  3852  3852 D HeadsetProfile: Bluetooth service connected
,08-25 17:39:27.739   872  1313 D ConnectivityService: handlePromptUnvalidated 101
,08-25 17:39:27.803  4076  4088 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 17:39:27.803  4076  4088 D BluetoothAdapterProperties: Setting state to 13
,08-25 17:39:27.804  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 17:39:27.805  4076  4088 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 17:39:27.808  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:27.815  4076  4092 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:27.815  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 17:39:27.819  4076  4076 D BluetoothMapService: onReceive
08-25 17:39:27.820  4076  4076 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 17:39:27.820  4076  4076 D BluetoothMapService: STATE_TURNING_OFF
,08-25 17:39:27.821  4076  4076 D BluetoothMapService: MAP Service closeService in
08-25 17:39:27.821  4076  4076 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 17:39:27.821  4076  4076 D ObexServerSockets0: shutdown(block = true)
,08-25 17:39:27.822  4076  4113 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-25 17:39:27.825  4076  4076 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 17:39:27.825  4076  4076 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 17:39:27.826  4076  4114 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 17:39:27.826  4076  4101 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 17:39:27.828  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:27.828  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:27.830  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:39:27.831  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:27.832  4076  4076 I BtOppRfcommListener: stopping Accept Thread
,08-25 17:39:27.833  4076  4123 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:39:27.834  4076  4123 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:39:27.837  4076  4076 D HeadsetService: Received stop request...Stopping profile...
,08-25 17:39:27.838  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:27.838  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:27.839  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:39:27.839  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:27.840  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:27.840  1927  1945 D BluetoothHeadset: Proxy object disconnected
,08-25 17:39:27.840   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 17:39:27.841   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:27.841  1357  1372 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:27.841  4076  4076 D A2dpService: Received stop request...Stopping profile...
08-25 17:39:27.841   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 17:39:27.842  4076  4107 D A2dpStateMachine: Exit Disconnected: -1
08-25 17:39:27.843  3852  3862 D BluetoothHeadset: Proxy object disconnected
08-25 17:39:27.844   872   872 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:27.844  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:27.845  4076  4076 D HidService: Received stop request...Stopping profile...,
,08-25 17:39:27.845  4076  4076 D HidService: Stopping Bluetooth HidService
,08-25 17:39:27.846  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:27.849  4076  4076 D HealthService: Received stop request...Stopping profile...
08-25 17:39:27.850  4076  4076 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:27.850  4076  4076 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:27.850  3852  3852 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:27.850  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:27.850  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:27.850  3852  3852 D HeadsetProfile: Bluetooth service disconnected
,08-25 17:39:27.851  4076  4076 D PanService: Received stop request...Stopping profile...
08-25 17:39:27.851  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,08-25 17:39:27.852  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-25 17:39:27.852  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-25 17:39:27.852  1357  1357 D HidProfile: Bluetooth service disconnected
08-25 17:39:27.852  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 17:39:27.852  1357  1357 D PanProfile: Bluetooth service disconnected
08-25 17:39:27.853  4076  4076 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:39:27.854  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 17:39:27.854  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:39:27.854  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:27.854  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:27.855  4076  4092 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-25 17:39:27.855  4076  4076 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 17:39:27.857  4076  4076 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:39:27.857  4076  4076 D BluetoothMapService: stop()
08-25 17:39:27.857  4076  4076 D BluetoothMapAppObserver: deinitObservers()
08-25 17:39:27.858  4076  4076 D BluetoothMapAppObserver: removeReceiver()
,08-25 17:39:27.859  1357  1357 D BluetoothMap: Proxy object disconnected
08-25 17:39:27.859  4076  4076 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:27.859  1357  1357 D MapProfile: Bluetooth service disconnected
08-25 17:39:27.859  4076  4076 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:27.859  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:27.860  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:27.861  3852  3852 D DockEventReceiver: finishStartingService: stopping service
08-25 17:39:27.861  4076  4076 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:27.861  4076  4076 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:27.861  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:27.861  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:27.861  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-25 17:39:27.861  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:27.862  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:39:27.862  4076  4098 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:39:27.862  4076  4098 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:27.862  3852  3852 D BluetoothInputDevice: Proxy object disconnected
08-25 17:39:27.862  4076  4098 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:39:27.862  3852  3852 D HidProfile: Bluetooth service disconnected
08-25 17:39:27.862  4076  4098 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:39:27.862  3852  3852 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:39:27.862  3852  3852 D PanProfile: Bluetooth service disconnected
08-25 17:39:27.863  3852  3852 D BluetoothMap: Proxy object disconnected
,08-25 17:39:27.863  3852  3852 D MapProfile: Bluetooth service disconnected
08-25 17:39:27.865  4076  4076 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:39:27.865  4076  4092 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 17:39:27.865  4076  4076 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:39:27.865  4076  4076 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:27.866  4076  4076 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:27.866  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:27.866  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:27.868  4076  4076 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 17:39:27.868  4076  4092 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 17:39:27.868  4076  4076 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:39:27.868  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:27.869  4076  4076 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:39:27.869  4076  4076 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:27.869  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:27.869  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:27.869  4076  4076 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 17:39:27.869  4076  4076 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:39:27.872  4076  4076 D BluetoothMapService: MAP Service closeService in
08-25 17:39:27.873  4076  4076 V BluetoothAdapterState: isTurningOff()=true
08-25 17:39:27.873  4076  4076 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:27.873  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:27.873  4076  4076 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:27.873  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 17:39:27.873  4076  4088 D BluetoothAdapterProperties: Setting state to 15
08-25 17:39:27.873  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 17:39:27.874  4076  4076 D BluetoothMapService: cleanup()
,08-25 17:39:27.874  4076  4076 D BluetoothMapService: MAP Service closeService in
08-25 17:39:27.874   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:27.874   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:27.875  4076  4088 I BluetoothAdapterState: Entering BleOnState
,08-25 17:39:27.875  3852  4128 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:27.876  1357  2023 D BluetoothPan: onBluetoothStateChange on: false
08-25 17:39:27.877   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:39:27.877  1357  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:39:27.878  3852  3862 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:39:27.878  1357  1357 D BluetoothPbap: Proxy object disconnected
,08-25 17:39:27.878  1357  1357 D PbapServerProfile: Bluetooth service disconnected
08-25 17:39:27.878  3852  3852 D BluetoothPbap: Proxy object disconnected
08-25 17:39:27.878  3852  3852 D PbapServerProfile: Bluetooth service disconnected
,08-25 17:39:27.881  1357  1369 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:39:27.882  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=false,
,08-25 17:39:27.882   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:39:27.882  3852  3863 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:39:27.885  3852  4128 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:39:27.885  3852  3862 D BluetoothPan: onBluetoothStateChange on: false
,08-25 17:39:27.886  3852  3863 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:39:27.886  1357  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:39:27.887  1357  2023 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:39:27.887  1357  1369 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 17:39:27.888  4076  4088 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-25 17:39:27.888  4076  4088 D BluetoothAdapterProperties: Setting state to 16
,08-25 17:39:27.888  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 17:39:27.890  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:27.891  4076  4088 D BluetoothAdapterProperties: onBleDisable
08-25 17:39:27.892  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:27.892  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:39:27.892  4076  4088 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:39:27.892  4076  4089 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 17:39:27.892  4076  4092 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:39:27.893  4076  4098 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 17:39:27.893  4076  4098 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:39:27.897  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:27.898  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:39:27.898  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:27.903  3852  3852 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:28.095  4076  4092 I bt_hci  : shut_down
,08-25 17:39:28.110  4076  4096 D bt_hwcfg: hw_epilog_process
,08-25 17:39:28.111  4076  4096 I bt_vendor: low_power_mode_cb
,08-25 17:39:28.126  4076  4096 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-25 17:39:28.127  4076  4096 I bt_vendor: epilog_cb
08-25 17:39:28.127  4076  4096 I bt_hci  : epilog_finished_callback
,08-25 17:39:28.135  4076  4092 I bt_hci_h4: hal_close
,08-25 17:39:28.136  4076  4092 I bt_userial_vendor: device fd = 51 close
,08-25 17:39:28.257  4076  4089 D bt_stack_manager: event_shut_down_stack finished.
,08-25 17:39:28.258  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 17:39:28.264  4076  4088 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-25 17:39:28.264  4076  4076 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:39:28.265  4076  4076 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:39:28.266  4076  4076 D BtGatt.GattService: stop()
08-25 17:39:28.266  4076  4076 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 17:39:28.270  4076  4076 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:28.271  4076  4076 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:39:28.271  4076  4076 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:28.271  4076  4076 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 17:39:28.272  4076  4088 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 17:39:28.273  4076  4088 D BluetoothAdapterProperties: Setting state to 10
08-25 17:39:28.274  4076  4088 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 17:39:28.276  4076  4088 I BluetoothAdapterState: Entering OffState
08-25 17:39:28.277   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 17:39:28.305  4076  4076 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-25 17:39:28.306  4076  4076 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 17:39:28.306  4076  4089 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 17:39:28.316  4076  4089 D bt_stack_manager: event_clean_up_stack finished.
,08-25 17:39:28.316  4076  4076 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 17:39:28.323  4076  4076 I art     : System.exit called, status: 0
08-25 17:39:28.324  4076  4076 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 17:39:28.379   872  1920 I ActivityManager: Process com.android.bluetooth (pid 4076) has died
,08-25 17:39:30.799  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:30.800  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:33.807  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:33.808  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aefb8f7 added. We now have 6 listener(s)
,08-25 17:39:33.808  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:33.812  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:33.812  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8773364 added. We now have 7 listener(s)
,08-25 17:39:33.813  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:33.814  3782  3833 I System.out: IsBluetoothEnabled
,08-25 17:39:33.827  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:33.880   872   889 I ActivityManager: Start proc 4135:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 17:39:34.002  4135  4135 D AdapterServiceConfig: Adding HeadsetService
08-25 17:39:34.002  4135  4135 D AdapterServiceConfig: Adding A2dpService
08-25 17:39:34.003  4135  4135 D AdapterServiceConfig: Adding HidService
08-25 17:39:34.003  4135  4135 D AdapterServiceConfig: Adding HealthService
08-25 17:39:34.003  4135  4135 D AdapterServiceConfig: Adding PanService
08-25 17:39:34.003  4135  4135 D AdapterServiceConfig: Adding GattService
08-25 17:39:34.003  4135  4135 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 17:39:34.020  4135  4135 D BluetoothAdapterState: make() - Creating AdapterState
08-25 17:39:34.020   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0cece6:true
,08-25 17:39:34.025  4135  4135 I bt_bluedroid: init
,08-25 17:39:34.026  4135  4147 I BluetoothAdapterState: Entering OffState
,08-25 17:39:34.031  4135  4148 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:39:34.032  4135  4148 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 17:39:34.032  4135  4148 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 17:39:34.033  4135  4148 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 17:39:34.034  4135  4135 I bt_bluedroid: get_profile_interface socket
,08-25 17:39:34.038  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 17:39:34.040  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:39:34.040  4135  4135 I bt_bluedroid: get_profile_interface sdp
,08-25 17:39:34.047  4135  4146 I bt_bluedroid: config_hci_snoop_log
,08-25 17:39:34.051   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 17:39:34.063  4135  4147 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 17:39:34.063  4135  4147 D BluetoothAdapterProperties: Setting state to 14
08-25 17:39:34.064  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 17:39:34.068  4135  4147 D BluetoothBondStateMachine: make
,08-25 17:39:34.074  4135  4152 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:39:34.084  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:34.085  4135  4135 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 17:39:34.092  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:34.094  4135  4135 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:39:34.095  4135  4135 D BtGatt.GattService: Received start request. Starting profile...
08-25 17:39:34.096  4135  4135 D BtGatt.GattService: start()
08-25 17:39:34.096  4135  4135 I bt_bluedroid: get_profile_interface gatt
08-25 17:39:34.097  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:34.098  4135  4135 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:39:34.110  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:34.110  4135  4135 V BluetoothAdapterState: isTurningOn()=false
08-25 17:39:34.111  4135  4135 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 17:39:34.111  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:34.113  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 17:39:34.113  4135  4147 I bt_bluedroid: enable
08-25 17:39:34.113  4135  4148 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 17:39:34.114  4135  4148 I bt_hci  : start_up
,08-25 17:39:34.121  4135  4148 I bt_vendor: alloc value 0xb39db189
08-25 17:39:34.121  4135  4148 I bt_vendor: init
,08-25 17:39:34.122  4135  4148 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 17:39:34.122  4135  4148 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 17:39:34.135   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 17:39:34.140  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-25 17:39:34.152   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:39:34.152   872   892 I Adreno  : Build Date                       : 10/20/15
08-25 17:39:34.152   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:39:34.152   872   892 I Adreno  : Local Branch                     : M14
08-25 17:39:34.152   872   892 I Adreno  : Remote Branch                    : 
08-25 17:39:34.152   872   892 I Adreno  : Remote Branch                    : 
08-25 17:39:34.152   872   892 I Adreno  : Reconstruct Branch               : 
,08-25 17:39:34.203   281   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (210 us)
,08-25 17:39:34.230  4135  4148 D bt_hci  : start_up starting async portion
,08-25 17:39:34.232  4135  4155 I bt_hci  : event_finish_startup
08-25 17:39:34.233  4135  4155 I bt_hci_h4: hal_open
08-25 17:39:34.236  4135  4155 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 17:39:34.242  4135  4155 I bt_userial_vendor: device fd = 51 open
,08-25 17:39:34.272  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:39:34.304  4135  4155 D bt_hwcfg: Chipset BCM4354A2
,08-25 17:39:34.304  4135  4155 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 17:39:34.305  4135  4155 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 17:39:34.969  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:39:34.969  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 17:39:35.024  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d5ff55 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@fc189cd, 16908290=android.view.AbsSavedState$1@fc189cd}, android:focusedViewId=100}]}]
,08-25 17:39:35.024  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 17:39:35.025  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 17:39:35.025  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-25 17:39:35.026   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
08-25 17:39:35.031   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 17:39:35.040   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 17:39:35.044   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-25 17:39:35.047   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 17:39:35.055  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 17:39:35.055  4135  4155 D bt_hwcfg: Settlement delay -- 100 ms
08-25 17:39:35.055  4135  4155 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 17:39:35.172  4135  4155 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:39:35.173  4135  4155 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 17:39:35.205  4135  4155 I bt_hwcfg: vendor lib fwcfg completed
,08-25 17:39:35.205  4135  4155 I bt_vendor: firmware callback
,08-25 17:39:35.205  4135  4155 I bt_hci  : firmware_config_callback
,08-25 17:39:35.218  4135  4158 I bt_btu  : btu_task pending for preload complete event
,08-25 17:39:35.218  4135  4158 I bt_btu_task: Bluetooth chip preload is complete
,08-25 17:39:35.219  4135  4158 I bt_btu  : btu_task received preload complete event
,08-25 17:39:35.228  4135  4158 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 17:39:35.228  4135  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 17:39:35.228  4135  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:39:35.229  4135  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:39:35.229  4135  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:39:35.229  4135  4158 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 17:39:35.229  4135  4158 I         : BTE_InitTraceLevels -- TRC_BNEP,
,08-25 17:39:35.230  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 17:39:35.230  4135  4158 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:39:35.230  4135  4158 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 17:39:35.230  4135  4158 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:39:35.231  4135  4158 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 17:39:35.231  4135  4158 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 17:39:35.231  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-25 17:39:35.231  4135  4158 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-25 17:39:35.271   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 17:39:35.274   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 17:39:35.276   872  1337 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-25 17:39:35.280   872   892 I DreamManagerService: Entering dreamland.
,08-25 17:39:35.282   872   892 I PowerManagerService: Dozing...
,08-25 17:39:35.282   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 17:39:35.335   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 17:39:35.335   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 17:39:35.341   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:39:35.352   872  1311 E native  : do suspend false
08-25 17:39:35.354  1908  4161 D NfcService: Discovery configuration equal, not updating.
,08-25 17:39:35.359  4135  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3958d9d
08-25 17:39:35.359  4135  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3958d9d 
,08-25 17:39:35.373  4135  4151 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 17:39:35.377  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 17:39:35.378  4135  4151 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 17:39:35.379  4135  4151 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:39:35.381  4135  4151 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:39:35.381  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:39:35.381  4135  4151 D bt_hci  : do_postload posting postload work item
08-25 17:39:35.381  4135  4155 I bt_hci  : event_postload
08-25 17:39:35.381  4135  4155 I bt_vendor: sco_config_cb
08-25 17:39:35.381  4135  4155 I bt_hci  : sco_config_callback postload finished.
08-25 17:39:35.382  4135  4151 D bt_bte_conf: Device ID record 1 : primary
08-25 17:39:35.382  4135  4151 D bt_bte_conf:   vendorId            = 000f
08-25 17:39:35.382  4135  4151 D bt_bte_conf:   vendorIdSource      = 0001
08-25 17:39:35.382  4135  4151 D bt_bte_conf:   product             = 1200
08-25 17:39:35.382  4135  4151 D bt_bte_conf:   version             = 1436
,08-25 17:39:35.382  4135  4151 D bt_bte_conf:   clientExecutableURL = 
08-25 17:39:35.382  4135  4151 D bt_bte_conf:   serviceDescription  = 
08-25 17:39:35.383  4135  4151 D bt_bte_conf:   documentationURL    = 
08-25 17:39:35.383  4135  4151 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 17:39:35.383  4135  4148 D bt_stack_manager: event_start_up_stack finished
08-25 17:39:35.383  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 17:39:35.384  4135  4147 D BluetoothAdapterProperties: Setting state to 15
08-25 17:39:35.384  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 17:39:35.386  4135  4147 I BluetoothAdapterState: Entering BleOnState
08-25 17:39:35.386  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:35.389  4135  4155 I bt_vendor: low_power_mode_cb
,08-25 17:39:35.423   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:39:35.427   872  1311 E native  : do suspend true
,08-25 17:39:35.479   375  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 17:39:35.480   375  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 17:39:35.488  4135  4147 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 17:39:35.488  4135  4147 D BluetoothAdapterProperties: Setting state to 11
,08-25 17:39:35.489  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 17:39:35.501  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:35.505  4135  4135 D HeadsetService: Received start request. Starting profile...
,08-25 17:39:35.517  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:35.518  4135  4135 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:39:35.518  4135  4135 D HeadsetStateMachine: make
,08-25 17:39:35.533  4135  4147 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:39:35.539  4135  4135 D HeadsetStateMachine: max_hf_connections = 1
,08-25 17:39:35.539  4135  4135 I bt_bluedroid: get_profile_interface handsfree
08-25 17:39:35.540  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 17:39:35.540  4135  4151 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 17:39:35.547  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:35.548  4135  4135 D A2dpService: Received start request. Starting profile...
,08-25 17:39:35.548  4135  4135 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:39:35.549  4135  4135 I bt_bluedroid: get_profile_interface avrcp
,08-25 17:39:35.567  4135  4135 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 17:39:35.567  4135  4135 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:39:35.567  4135  4135 D A2dpStateMachine: make
,08-25 17:39:35.569  4135  4135 I bt_bluedroid: get_profile_interface a2dp
08-25 17:39:35.570  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 17:39:35.573  4135  4135 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:39:35.574  4135  4173 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:39:35.574  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
08-25 17:39:35.575  4135  4135 D HidService: Received start request. Starting profile...
08-25 17:39:35.575  4135  4135 I bt_bluedroid: get_profile_interface hidhost
,08-25 17:39:35.575  4135  4135 D HidService: setHidService(): set to: null
08-25 17:39:35.575  4135  4151 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393a3e5
08-25 17:39:35.575  4135  4151 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 17:39:35.576  4135  4135 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:39:35.577  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:35.577  4135  4135 D HealthService: Received start request. Starting profile...
,08-25 17:39:35.579  4135  4135 I bt_bluedroid: get_profile_interface health
,08-25 17:39:35.581  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:35.582  4135  4135 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 17:39:35.583  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:35.584  4135  4135 D PanService: Received start request. Starting profile...
,08-25 17:39:35.584  4135  4135 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 17:39:35.584  4135  4135 I bt_bluedroid: get_profile_interface pan
08-25 17:39:35.584  4135  4151 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:39:35.587  4135  4135 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:35.588  4135  4135 D BluetoothMapService: Received start request. Starting profile...
08-25 17:39:35.588  4135  4135 D BluetoothMapService: start()
,08-25 17:39:35.590  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 17:39:35.592  4135  4135 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 17:39:35.592  4135  4135 D BluetoothMapAppObserver: createReceiver()
,08-25 17:39:35.593  4135  4135 D BluetoothMapAppObserver: initObservers()
08-25 17:39:35.593  4135  4135 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 17:39:35.601  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:35.601  4135  4135 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:35.601  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:35.601  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:35.604  4135  4169 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isTurningOn()=true
,08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:35.604  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:35.605  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:35.605  4135  4135 V BluetoothAdapterState: isTurningOn()=true
,08-25 17:39:35.605  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:39:35.605  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isTurningOff()=false
08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isTurningOn()=true
08-25 17:39:35.607  4135  4135 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:39:35.608  4135  4135 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:39:35.608  4135  4147 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 17:39:35.609  4135  4147 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:39:35.609  4135  4147 D BluetoothAdapterProperties: State =  11
08-25 17:39:35.610  4135  4147 D BluetoothAdapterProperties: Setting state to 12
08-25 17:39:35.611  4135  4147 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 17:39:35.611   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:35.611   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:35.612  4135  4147 I BluetoothAdapterState: Entering OnState
08-25 17:39:35.612  4135  4151 D BluetoothAdapterProperties: Scan Mode:21
08-25 17:39:35.612  4135  4151 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:39:35.613  3852  3862 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:35.613   872   872 D BluetoothA2dp: Proxy object connected
08-25 17:39:35.615  3852  3852 D BluetoothA2dp: Proxy object connected
08-25 17:39:35.615  1357  2023 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:35.616  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:39:35.617   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:39:35.617  1357  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:39:35.618  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:35.619  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:35.619  1357  1357 D PanProfile: Bluetooth service connected
08-25 17:39:35.619  3852  4128 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:39:35.619  1357  1357 D BluetoothA2dp: Proxy object connected
,08-25 17:39:35.621  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 17:39:35.621  1357  2023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:35.622  1927  1939 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:35.622  4135  4135 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 17:39:35.623   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:35.623  3852  3863 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:39:35.625  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:35.625  3852  3862 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 17:39:35.628  4135  4135 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:35.628  3852  4128 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:39:35.629  4135  4135 D ObexServerSockets: Succeed to create listening sockets 
08-25 17:39:35.629  4135  4135 D ObexServerSockets0: startAccept()
08-25 17:39:35.629  4135  4135 D ObexServerSockets0: prepareForNewConnect()
08-25 17:39:35.630  3852  3852 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:39:35.630  3852  3852 D PanProfile: Bluetooth service connected
,08-25 17:39:35.631  3852  3862 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:39:35.631  1357  1369 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:39:35.631  4135  4135 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 17:39:35.632  4135  4135 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 17:39:35.632  4135  4178 D ObexServerSockets0: Accepting socket connection...
,08-25 17:39:35.633  4135  4179 D ObexServerSockets0: Accepting socket connection...
08-25 17:39:35.633  1357  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:39:35.633  3852  3852 D BluetoothInputDevice: Proxy object connected
08-25 17:39:35.634  3852  3852 D HidProfile: Bluetooth service connected
,08-25 17:39:35.635  1357  1357 D BluetoothInputDevice: Proxy object connected
08-25 17:39:35.635  1357  1357 D HidProfile: Bluetooth service connected
,08-25 17:39:35.636  1357  1369 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:39:35.636  3852  3852 D BluetoothMap: Proxy object connected
,08-25 17:39:35.636  3852  3852 D MapProfile: Bluetooth service connected
08-25 17:39:35.636  3852  3852 D BluetoothMap: getConnectedDevices()
,08-25 17:39:35.639  1357  1357 D BluetoothMap: Proxy object connected
,08-25 17:39:35.639  1357  1357 D MapProfile: Bluetooth service connected
,08-25 17:39:35.639  1357  1357 D BluetoothMap: getConnectedDevices()
,08-25 17:39:35.640   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 17:39:35.641  4135  4135 D BluetoothMapService: onReceive
08-25 17:39:35.641  4135  4135 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:39:35.641  4135  4135 D BluetoothMapService: STATE_ON
08-25 17:39:35.642  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:35.647  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:39:35.654  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:39:35.655  3852  3852 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:39:35.662  3852  3852 D BluetoothPbap: Proxy object connected
08-25 17:39:35.663  3852  3852 D PbapServerProfile: Bluetooth service connected
,08-25 17:39:35.666  1357  1357 D BluetoothPbap: Proxy object connected
,08-25 17:39:35.666  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-25 17:39:35.669  4135  4135 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:39:35.669  4135  4135 D ObexServerSockets0: prepareForNewConnect()
,08-25 17:39:35.671  4135  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:35.691  4135  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:39:35.693  4135  4189 I BtOppRfcommListener: Accept thread started.
,08-25 17:39:35.713  1927  2072 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.714   872   872 D BluetoothHeadset: Proxy object connected
08-25 17:39:35.714   872   872 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.714  1357  1372 D BluetoothHeadset: Proxy object connected
08-25 17:39:35.714  1357  1357 D HeadsetProfile: Bluetooth service connected
,08-25 17:39:35.715   872   872 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.716  3852  3863 D BluetoothHeadset: Proxy object connected
08-25 17:39:35.716   872   889 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.717  3852  3852 D HeadsetProfile: Bluetooth service connected
,08-25 17:39:35.722  1357  1369 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.722  1357  1357 D HeadsetProfile: Bluetooth service connected
08-25 17:39:35.722  1927  2062 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.723   872   889 D BluetoothHeadset: Proxy object connected
,08-25 17:39:35.731  3852  4128 D BluetoothHeadset: Proxy object connected
08-25 17:39:35.732  3852  3852 D HeadsetProfile: Bluetooth service connected
,08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:35.850  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:35.857  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:35.861  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:35.861  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef25282 added. We now have 8 listener(s)
08-25 17:39:35.862  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:35.868   872  1920 D WifiService: setWifiEnabled: false pid=3782, uid=10000
08-25 17:39:35.868   872  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:39:35.881  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:35.882   872   882 D WifiService: setWifiEnabled: true pid=3782, uid=10000
08-25 17:39:35.882   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:39:35.894   872  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:35.914  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:35.918  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:39:35.929   872  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-25 17:39:35.930   872  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 17:39:35.931   872  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 17:39:35.932   872  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 17:39:35.933   872  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 17:39:35.933   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 17:39:35.933   872  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 17:39:35.943   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 17:39:35.944   371   870 D CommandListener: Setting iface cfg
08-25 17:39:35.944   872  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,08-25 17:39:35.945   872  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-25 17:39:35.945   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 17:39:35.945   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 17:39:35.954   872  1311 E native  : do suspend true
,08-25 17:39:35.955   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 17:39:35.962   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 17:39:35.969   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 17:39:35.969   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:35.990   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 17:39:36.036   872  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 17:39:36.040  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 17:39:36.464  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:39:36.501  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:39:36.503  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 17:39:36.510   872  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:39:36.528   872  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:39:36.529   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:39:36.529   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 17:39:36.556   872  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:39:36.582   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:36.583   872  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 17:39:36.600   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[],
,08-25 17:39:36.609   872  4196 D DhcpClient: Receive thread started
,08-25 17:39:36.693   872  1311 E native  : do suspend false
,08-25 17:39:36.715   872  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 17:39:36.729   872  4196 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-25 17:39:36.731   872  2103 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 17:39:36.736   872  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 17:39:36.750   872  4196 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 17:39:36.751   872  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 17:39:36.758   371   870 D CommandListener: Setting iface cfg
,08-25 17:39:36.769   872  2103 D DhcpClient: Scheduling renewal in 86399s
,08-25 17:39:36.772   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 17:39:36.777   872  1311 E native  : do suspend true
,08-25 17:39:36.798   872  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-25 17:39:36.802   872  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 17:39:36.803   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 17:39:36.805   872  1313 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 17:39:36.814   872  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:39:36.902   872  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 17:39:36.902   872  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:39:36.903  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:39:36.905   872  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 17:39:36.906   872  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 17:39:36.907   872  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-25 17:39:36.914  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:39:36.918  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 17:39:36.918   872  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 17:39:36.919  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 17:39:36.920  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2d5ff55 Bundle[{}]
08-25 17:39:36.921  3782  3833 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:39:36.921  3782  3833 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 17:39:36.922  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 17:39:36.922  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 17:39:36.923  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 17:39:36.923  3782  3833 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 17:39:36.927  3782  3833 I System.out: Running OutgoingSocketThread
08-25 17:39:36.931  3782  4200 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
08-25 17:39:36.932  3782  4200 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48288
,08-25 17:39:36.932  3782  4200 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 17:39:36.934   872  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 17:39:36.935   872  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-25 17:39:36.935   872  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 17:39:36.935   872  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 17:39:36.935   872  1313 D ConnectivityService:    accepting network in place of null
08-25 17:39:36.935   872  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:39:36.936   872  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:39:36.947   872  4195 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152985, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 17:39:36.974   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:37.005   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:39:37.009   872  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 17:39:37.009   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:37.011   872  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 17:39:37.015   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:39:37.032   872  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:37.033  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:39:37.035  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:37.043  2000  2000 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-25 17:39:37.046  1728  1728 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:39:37.054  1728  1728 D SystemUpdateService: onCreate
,08-25 17:39:37.057  1728  1728 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:39:37.074  1728  4207 I SystemUpdateService: active receiver: enabled
,08-25 17:39:37.076  1728  1728 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-25 17:39:37.078  1728  2523 I iu.UploadsManager: num queued entries: 0
08-25 17:39:37.079  1728  2523 I iu.UploadsManager: num updated entries: 0
08-25 17:39:37.079  1728  2523 I iu.SyncManager: NEXT; no task
,08-25 17:39:37.088   872  4194 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:39:37 GMT], X-Android-Received-Millis=[1472139577086], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472139577063]}
,08-25 17:39:37.089  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 17:39:37.090  1728  1728 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 17:39:37.090   872  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 17:39:37.090   872  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 17:39:37.090   872  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 17:39:37.092   872  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 17:39:37.092  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:39:37.099  3933  3933 D SprintDMHelper: simOperator: 
08-25 17:39:37.099  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:39:37.103  1728  4210 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 17:39:37.109  1728  4210 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 17:39:37.111  1728  4210 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 17:39:37.129  1728  4207 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:39:37.134  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:37.136  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:39:37.149  1728  4207 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 17:39:37.151  1728  4207 I SystemUpdateService: now status is 0 (complete)
,08-25 17:39:37.151  1728  4207 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 17:39:37.151  1728  4207 I SystemUpdateService: file has been verified
08-25 17:39:37.152  1728  4207 I SystemUpdateService: OTA package size = 12249756
,08-25 17:39:37.156  1728  4207 I SystemUpdateService: showing system update notification
,08-25 17:39:37.172  1728  1728 D SystemUpdateService: onDestroy
,08-25 17:39:37.188  1511  2424 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 17:39:37.188  1511  2424 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 17:39:37.189  1511  2424 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 17:39:37.190  1511  2424 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:39:37.210  1728  4210 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-25 17:39:37.217  2405  4213 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 17:39:37.930  3782  3833 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,08-25 17:39:37.930  3782  3833 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-25 17:39:37.940  3782  3833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-25 17:39:37.942  3782  3833 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 17:39:37.943  3782  3833 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-25 17:39:37.947  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:37.948  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dced93 added. We now have 2 listener(s)
,08-25 17:39:37.949  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:37.950  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:37.950  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:37.950  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:37.950  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52621d0 added. We now have 9 listener(s)
08-25 17:39:37.950  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:37.951  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:37.954  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:37.962  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:37.965  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:37.966  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:37.966  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:37.967  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67714ce added. We now have 3 listener(s)
,08-25 17:39:37.970  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:37.974  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:37.976  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:37.976  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:37.977  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:37.978  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:37.979  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5ecfef added. We now have 10 listener(s)
,08-25 17:39:37.979  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:37.981  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:37.981  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:37.982  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:37.982  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:37.983  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:37.983  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:37.984  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:39:37.985  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4dced93 removed from the list
08-25 17:39:37.986  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:37.986  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52621d0 removed from the list
08-25 17:39:37.987  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:39:37.988  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:37.990  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:37.991  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:37.993  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:37.993  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:37.993  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:37.993  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52621d0 not in the list
08-25 17:39:37.993  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:37.993  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:37.994  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:37.994  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:37.994  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:37.995  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5ecfef removed from the list
08-25 17:39:37.995  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:37.995  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:37.995  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:37.995  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:37.995  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67714ce removed from the list
08-25 17:39:37.996  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:39:37.996  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3938afc added. We now have 2 listener(s)
08-25 17:39:37.998  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:37.998  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:37.998  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:37.998  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:37.998  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5132585 added. We now have 9 listener(s)
08-25 17:39:37.998  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:37.999  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:39:38.003  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:38.008   872  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:38.010  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:38.012  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:38.013  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:38.013  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.013  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5727c0b added. We now have 3 listener(s)
,08-25 17:39:38.015  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:38.015  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.015  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:38.015  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:38.015  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0c5ae8 added. We now have 10 listener(s)
08-25 17:39:38.015  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:38.016  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:38.016  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:38.016  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:38.016  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:38.016  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:39:38.020  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:38.021  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:39:38.022  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:38.027  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:38.027  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:38.027  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 17:39:38.027  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:38.032  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:38.032  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 17:39:38.033  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:38.033  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:38.037  4135  4145 D BtGatt.GattService: registerClient() - UUID=3d9ede6b-7280-41ab-bfe9-6ee5cf3cb46a
,08-25 17:39:38.039  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=3d9ede6b-7280-41ab-bfe9-6ee5cf3cb46a, clientIf=5
,08-25 17:39:38.040  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:39:38.041  4135  4180 D BtGatt.GattService: start scan with filters
,08-25 17:39:38.046  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:38.046  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 17:39:38.046  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 17:39:38.046  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:39:38.046  4135  4154 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:38.049  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:38.049  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:38.049  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:38.051  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 17:39:38.051  4135  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@723d299
,08-25 17:39:38.054  3782  3833 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 17:39:38.055  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:38.055  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 17:39:38.055  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:38.055  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 17:39:38.055  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:39:38.055  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-25 17:39:38.055  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:38.055  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:38.056  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:38.056  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:38.058  3782  3833 D BluetoothAdapter: STATE_ON
08-25 17:39:38.059  4135  4167 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:39:38.059  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 17:39:38.059  4135  4145 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:39:38.059  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.060  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:39:38.060  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 17:39:38.060  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:38.060  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 17:39:38.060  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:38.060  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 17:39:38.061  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:38.061  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:38.062  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 17:39:38.062  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:39:38.062  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:38.064  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:38.064  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 17:39:38.065  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:39:38.067  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:38.067  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:38.067  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:38.069  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.069  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:38.069  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:38.069  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:39:38.069  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3938afc removed from the list
08-25 17:39:38.069  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:38.069  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5132585 removed from the list
,08-25 17:39:38.069  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:38.069  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:39:38.070  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.070  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.071  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:38.071  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:39:38.071  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:38.071  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5132585 not in the list
08-25 17:39:38.071  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:38.071  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.072  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.072  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:38.072  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.073  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0c5ae8 removed from the list
08-25 17:39:38.073  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.073  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.073  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:38.073  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.073  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.073  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.073  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5727c0b removed from the list
08-25 17:39:38.073  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:38.074  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:39:38.074  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.074  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c03d94 added. We now have 2 listener(s)
08-25 17:39:38.075  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:38.075  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.075  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:38.076  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:38.076  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115803d added. We now have 9 listener(s)
,08-25 17:39:38.076  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:38.078  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:38.080  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:38.084  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:38.086  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:38.087  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:38.087  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:39:38.087  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.087  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.087  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c6183 added. We now have 3 listener(s)
,08-25 17:39:38.089  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:38.089  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:38.089  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.089  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:38.089  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:38.089  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d9f00 added. We now have 10 listener(s)
08-25 17:39:38.090  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:38.090  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:38.091  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:38.091  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:38.091  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:38.091  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:38.091  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:38.091  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:38.094  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:39:38.094  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:39:38.095  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-25 17:39:38.095  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.098  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:38.098  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:39:38.099  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-25 17:39:38.102  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:39:38.102  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:38.102  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:38.102  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:39:38.102  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.103  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:39:38.103  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:38.104  4135  4146 D BtGatt.GattService: registerClient() - UUID=8660a88f-8b07-4016-bd2b-f3d4d8e7c59b
,08-25 17:39:38.105  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=8660a88f-8b07-4016-bd2b-f3d4d8e7c59b, clientIf=5
08-25 17:39:38.105  3782  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:39:38.105  4135  4168 D BtGatt.GattService: start scan with filters
,08-25 17:39:38.107  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:39:38.108  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.108  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:38.108  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:39:38.108  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:38.108  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:38.108  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-25 17:39:38.110  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:38.111  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:38.111  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:39:38.113  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:38.113  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:38.113  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.114  4135  4154 D BtGatt.ScanManager: handling starting scan
,08-25 17:39:38.115  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:38.115  3782  3833 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 17:39:38.115  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:38.115  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:38.116  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:38.116  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.116  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.116  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:38.117  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.117  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8c03d94 removed from the list
08-25 17:39:38.117  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.117  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115803d removed from the list
08-25 17:39:38.117  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:38.117  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:38.117  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.117  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 17:39:38.117  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.117  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:38.119  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:38.119  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.119  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.119  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@115803d not in the list
,08-25 17:39:38.119  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:39:38.119  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 17:39:38.119  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.119  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:39:38.119  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:39:38.119  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:39:38.120  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:39:38.120  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:38.120  3782  3833 D BluetoothAdapter: STATE_ON
08-25 17:39:38.121  4135  4146 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:39:38.121  4135  4168 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:39:38.122  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:39:38.122  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 17:39:38.122  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:39:38.122  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 17:39:38.122  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:38.123  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:38.123  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:38.123  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:38.123  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:38.124  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.124  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:38.124  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.125  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:38.125  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:38.125  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:38.125  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.125  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:38.125  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:38.125  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:39:38.125  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:39:38.125  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d9f00 removed from the list
08-25 17:39:38.125  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:39:38.125  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.125  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.125  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:39:38.125  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56c6183 removed from the list
08-25 17:39:38.126  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.126  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84dab2c added. We now have 2 listener(s)
,08-25 17:39:38.127  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:38.128  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:39:38.128  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:38.128  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:39:38.128  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34179f5 added. We now have 9 listener(s)
08-25 17:39:38.128  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:38.128  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:38.131  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:38.135  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:39:38.135  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:38.135  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:38.137  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:38.137  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:38.139  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:38.140  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:39:38.140  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.140  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.140  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e7dfb added. We now have 3 listener(s)
08-25 17:39:38.141  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:38.141  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:38.141  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.141  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:39:38.142  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:38.142  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6804e18 added. We now have 10 listener(s)
08-25 17:39:38.142  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:39:38.142  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:39:38.142  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:39:38.142  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:39:38.142  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:39:38.142  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:39:38.145  3782  3833 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:39:38.146  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:39:38.146  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 17:39:38.146  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.146  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:39:38.149  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:39:38.150  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:39:38.150  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:39:38.151  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:39:38.151  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.151  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 17:39:38.152  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 17:39:38.152  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:39:38.153  3782  3833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:39:38.153  3782  3833 D BluetoothAdapter: STATE_ON
08-25 17:39:38.154  4135  4146 D BtGatt.GattService: registerClient() - UUID=9423904e-8071-4bea-8554-14a1d34af716
08-25 17:39:38.155  4135  4151 D BtGatt.GattService: onClientRegistered() - UUID=9423904e-8071-4bea-8554-14a1d34af716, clientIf=5
08-25 17:39:38.155  3782  3849 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 17:39:38.155  4135  4168 D BtGatt.GattService: start scan with filters
,08-25 17:39:38.156  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:38.156  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.157  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:39:38.157  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:39:38.157  4135  4154 D BtGatt.ScanManager: handling starting scan
08-25 17:39:38.158  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:39:38.158  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 17:39:38.159  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:39:38.159  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:39:38.160  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:39:38.160  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:39:38.163  4135  4151 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:39:38.163  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.163  4135  4154 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:39:38.166  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:39:38.166  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:39:38.166  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:39:38.166  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.166  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.166  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:39:38.166  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.166  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84dab2c removed from the list
08-25 17:39:38.167  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.167  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34179f5 removed from the list
,08-25 17:39:38.167  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:38.167  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:39:38.167  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:39:38.168  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.168  4135  4154 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:39:38.168  4135  4154 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:39:38.168  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:38.168  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-25 17:39:38.168  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.168  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:38.169  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:38.169  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.169  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.169  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34179f5 not in the list
,08-25 17:39:38.169  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:39:38.169  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 17:39:38.170  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:39:38.170  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 17:39:38.170  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:39:38.170  3782  3833 D BluetoothAdapter: STATE_ON
,08-25 17:39:38.171  4135  4167 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:39:38.171  4135  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:39:38.171  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-25 17:39:38.171  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:39:38.171  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 17:39:38.172  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:39:38.172  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:39:38.172  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:38.172  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:39:38.172  3782  3833 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:39:38.172  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:39:38.173  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.174  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.174  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 17:39:38.175  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:39:38.175  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:39:38.175  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:39:38.175  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.175  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6804e18 removed from the list
08-25 17:39:38.175  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.175  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.175  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.175  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.175  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e7dfb removed from the list
08-25 17:39:38.176  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.176  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3833c4 added. We now have 2 listener(s)
08-25 17:39:38.177  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:39:38.177  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.177  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:38.177  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:38.177  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54bf2ad added. We now have 9 listener(s)
08-25 17:39:38.177  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:38.178  4135  4151 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:39:38.178  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:39:38.178  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.181  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:39:38.183  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:39:38.183  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:39:38.184  3782  3833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:39:38.186  3782  3833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:39:38.186  3782  3833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:39:38.186  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:39:38.186  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b78b173 added. We now have 3 listener(s)
,08-25 17:39:38.188  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:39:38.188  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:39:38.188  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:39:38.188  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:39:38.188  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:39:38.188  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66c830 added. We now have 10 listener(s)
,08-25 17:39:38.188  3782  3833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:39:38.188  4135  4151 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:39:38.188  3782  3833 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:39:38.188  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:39:38.188  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:38.189  3782  3833 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:39:38.189  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.189  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:39:38.189  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:39:38.189  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.189  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3833c4 removed from the list
08-25 17:39:38.189  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.189  4135  4154 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:39:38.189  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54bf2ad removed from the list
08-25 17:39:38.189  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:39:38.189  3782  3833 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:39:38.189  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.190  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.190  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.190  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:38.190  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.190  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.191  3782  3833 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54bf2ad not in the list
08-25 17:39:38.191  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.191  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.192  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:39:38.192  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:39:38.192  3782  3833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:39:38.192  3782  3833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a66c830 removed from the list
08-25 17:39:38.192  3782  3833 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:39:38.192  3782  3833 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:39:38.192  3782  3833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:39:38.192  3782  3833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:39:38.192  3782  3833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b78b173 removed from the list
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 17:39:38.193  3782  3833 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:39:38.194  4135  4151 D BtGatt.GattService: onBatchScanStartStopped() - clientIf,=5, status=0, startStopAction=0
08-25 17:39:38.194  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.194  4135  4154 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:39:38.197  3782  4219 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
08-25 17:39:38.197  3782  4219 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
08-25 17:39:38.198  3782  4219 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 17:39:38.198  4135  4151 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:39:38.199  4135  4151 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:39:38.199  3782  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
08-25 17:39:38.199  3782  4220 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
08-25 17:39:38.199  3782  4220 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 17:39:38.200  3782  3833 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 17:39:38.200  3782  3833 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 17:39:38.200  3782  3833 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 17:39:38.200  3782  3833 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 17:39:38.200  3782  3833 D com.test.thalitest.ThaliTestRunner: Total duration: 22809 ms
08-25 17:39:38.202  3782  3833 I jxcore-log: Total number of executed tests:  80
08-25 17:39:38.202  3782  3833 I jxcore-log: 
08-25 17:39:38.202  3782  3833 I jxcore-log: Number of passed tests:  80
08-25 17:39:38.202  3782  3833 I jxcore-log: 
08-25 17:39:38.202  3782  3833 I jxcore-log: Number of failed tests:  0
08-25 17:39:38.202  3782  3833 I jxcore-log: 
,08-25 17:39:38.202  3782  3833 I jxcore-log: Number of ignored tests:  0
08-25 17:39:38.202  3782  3833 I jxcore-log: 
08-25 17:39:38.202  3782  3833 I jxcore-log: Total duration:  22809
08-25 17:39:38.202  3782  3833 I jxcore-log: 
08-25 17:39:38.203  3782  3833 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 17:39:38.203  3782  3833 I jxcore-log: 
08-25 17:39:38.205  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.205  3782  3833 I jxcore-log: 
,08-25 17:39:38.208  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.208  3782  3833 I jxcore-log: 
08-25 17:39:38.209  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.209  3782  3833 I jxcore-log: 
08-25 17:39:38.209  3782  3782 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 17:39:38.209  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.209  3782  3833 I jxcore-log: 
08-25 17:39:38.210  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.210  3782  3833 I jxcore-log: 
08-25 17:39:38.211  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.211  3782  3833 I jxcore-log: 
08-25 17:39:38.212  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.212  3782  3833 I jxcore-log: 
08-25 17:39:38.213  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.213  3782  3833 I jxcore-log: 
08-25 17:39:38.214  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.214  3782  3833 I jxcore-log: 
08-25 17:39:38.214  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.214  3782  3833 I jxcore-log: 
08-25 17:39:38.215  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.215  3782  3833 I jxcore-log: 
08-25 17:39:38.216  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:38.216  3782  3833 I jxcore-log: 
08-25 17:39:38.216  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.216  3782  3833 I jxcore-log: 
08-25 17:39:38.217  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.217  3782  3833 I jxcore-log: 
08-25 17:39:38.217  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.217  3782  3833 I jxcore-log: 
08-25 17:39:38.218  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.218  3782  3833 I jxcore-log: 
08-25 17:39:38.218  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.218  3782  3833 I jxcore-log: 
08-25 17:39:38.219  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.219  3782  3833 I jxcore-log: 
08-25 17:39:38.219  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.219  3782  3833 I jxcore-log: 
08-25 17:39:38.220  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.220  3782  3833 I jxcore-log: 
08-25 17:39:38.220  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.220  3782  3833 I jxcore-log: 
08-25 17:39:38.221  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.221  3782  3833 I jxcore-log: 
,08-25 17:39:38.221  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.221  3782  3833 I jxcore-log: 
08-25 17:39:38.222  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:39:38.222  3782  3833 I jxcore-log: 
08-25 17:39:38.222  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.222  3782  3833 I jxcore-log: 
08-25 17:39:38.223  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:39:38.223  3782  3833 I jxcore-log: 
08-25 17:39:38.223  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.223  3782  3833 I jxcore-log: 
08-25 17:39:38.224  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.224  3782  3833 I jxcore-log: 
08-25 17:39:38.224  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.224  3782  3833 I jxcore-log: 
08-25 17:39:38.225  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.225  3782  3833 I jxcore-log: 
08-25 17:39:38.225  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.225  3782  3833 I jxcore-log: 
08-25 17:39:38.226  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:39:38.226  3782  3833 I jxcore-log: 
,08-25 17:39:38.565  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:38.568  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:38.568  3782  3833 I jxcore-log: 
,08-25 17:39:38.625  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:38.628  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:38.628  3782  3833 I jxcore-log: 
,08-25 17:39:38.675  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:39:38.678  3782  3833 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:39:38.678  3782  3833 I jxcore-log: 
,08-25 17:39:38.879  4221  4221 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 17:39:38.883  4221  4221 D AndroidRuntime: CheckJNI is OFF
,08-25 17:39:38.926  4221  4221 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 17:39:38.973  4221  4221 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 17:39:38.996  4221  4221 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 17:39:39.006   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 17:39:39.007   872   885 I ActivityManager: Killing 3782:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 17:39:39.127   872   895 W PackageSettings: Skipping PackageSetting{a0f84e2 com.example.hello/10273} due to missing metadata
,08-25 17:39:39.130   872  1956 D GraphicsStats: Buffer count: 2
,08-25 17:39:39.131   872  2015 I WindowState: WIN DEATH: Window{4605bb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:39:39.130   872  1312 D WifiService: Client connection lost with reason: 4
,08-25 17:39:39.182   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 17:39:39.182   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-25 17:39:39.183   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-25 17:39:39.183   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 17:39:39.183   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:39.183   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:39.183   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:39:39.183   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 17:39:39.183   872   885 I ActivityManager:   Force finishing activity ActivityRecord{fb30311 u0 com.test.thalitest/.MainActivity t2}
08-25 17:39:39.184   872   895 I art     : Starting a blocking GC Explicit
08-25 17:39:39.191   872  1956 W ActivityManager: Spurious death for ProcessRecord{edb266 0:com.test.thalitest/u0a0}, curProc for 3782: null
,08-25 17:39:39.228   872   895 I art     : Explicit concurrent mark sweep GC freed 57596(3MB) AllocSpace objects, 10(304KB) LOS objects, 33% free, 29MB/43MB, paused 820us total 42.691ms
,08-25 17:39:39.256   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 17:39:39.261  4221  4221 I art     : System.exit called, status: 0
,08-25 17:39:39.261  4221  4221 I AndroidRuntime: VM exiting with result code 0.
,08-25 17:39:39.263   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 17:39:39.280   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 17:39:39.288  4135  4135 D BluetoothMapAppObserver: onReceive,
08-25 17:39:39.288  4135  4135 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 17:39:39.291  1868  1868 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 17:39:39.292   872  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 17:39:39.293  1868  4232 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 17:39:39.294  3618  3618 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-25 17:39:39.296  2042  2245 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 17:39:39.301  1868  4232 I Decoder : createOrResetDecoder
,08-25 17:39:39.315   872  1932 I ActivityManager: Start proc 4234:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 17:39:39.317  1927  1927 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 17:39:39.360  1511  1511 I ConfigService: onCreate
,08-25 17:39:39.363  4234  4234 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 17:39:39.369   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 17:39:39.382   872  1932 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3782 uid 10000
,08-25 17:39:39.384  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-25 17:39:39.393  1868  4232 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 17:39:39.404   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 17:39:39.405   872   884 E PackageManager: Failed to write settings, restoring backup
08-25 17:39:39.405   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 17:39:39.405   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 17:39:39.405   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 17:39:39.405   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 17:39:39.405   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 17:39:39.405   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:39:39.405   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:39.405   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 17:39:39.410   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-25 17:39:39.410   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 17:39:39.410   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:39:39.410   872   885 E DropBoxManagerService: 	... 13 more
,08-25 17:39:39.433  1938  2022 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 17:39:39.444  1868  4232 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 17:39:39.445   872  1693 I ActivityManager: Start proc 4252:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 17:39:39.445  1938  2022 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 17:39:39.445  1938  2022 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-25 17:39:39.445  1938  2022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:39:39.445  1938  2022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 17:39:39.447   872  1956 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 17:39:39.447   872  4258 E DropBoxManagerService: Can't write: system_app_crash
08-25 17:39:39.447   872  4258 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:39:39.447   872  4258 E DropBoxManagerService: 	... 5 more
08-25 17:39:39.448  4234  4234 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-25 17:39:39.448  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-25 17:39:39.448  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 17:39:39.452  1938  2022 I Process : Sending signal. PID: 1938 SIG: 9
,08-25 17:39:39.455  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-25 17:39:39.455  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 17:39:39.456  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 17:39:39.456  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 17:39:39.457  1868  4232 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 17:39:39.457  1868  4232 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 17:39:39.457  1868  4232 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 17:39:39.457  1868  4232 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-25 17:39:39.457  1868  4232 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 17:39:39.457  1868  4232 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 17:39:39.470   872  2015 I ActivityManager: Start proc 4267:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 17:39:39.481  4234  4266 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 17:39:39.720   872  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-25 17:39:39.778   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
