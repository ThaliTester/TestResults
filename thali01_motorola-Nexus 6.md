#### Test 8461863721be5f3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 13:53:18.426   874  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:53:19.087  3843  3843 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:53:19.093  3843  3843 D AndroidRuntime: CheckJNI is OFF
09-09 13:53:19.129  3843  3843 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:53:19.172  3843  3843 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:53:19.193  3843  3843 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 13:53:19.202   874   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:53:19.251  2010  2023 W SearchService: Abort, client detached.
09-09 13:53:19.254  3843  3843 D AndroidRuntime: Shutting down VM
09-09 13:53:19.263  2010  2325 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@55f6856
09-09 13:53:19.264  2010  2342 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 13:53:19.264  2010  2010 I HotwordDetector: Closing mic
09-09 13:53:19.270   874  1987 I ActivityManager: Start proc 3853:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 13:53:19.322   378  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:53:19.323   378  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 13:53:19.327   378  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 13:53:19.329  2010  2340 I MicroRecognitionRnrImpl: Detection finished
09-09 13:53:19.330  2010  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 13:53:19.355  3853  3853 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 13:53:19.377  3853  3853 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 13:53:19.383  3853  3853 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9619-9621)
09-09 13:53:19.383  3853  3853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:53:19.395  3853  3853 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f3abff}
09-09 13:53:19.395  3853  3853 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:53:19.396  3853  3853 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:53:19.400  3853  3853 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 13:53:19.402  3853  3853 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 13:53:19.415  3853  3853 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 13:53:19.427  3853  3853 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:53:19.428  3853  3853 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:53:19.428  3853  3853 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:53:19.428  3853  3853 I Adreno  : Build Date                       : 10/20/15
09-09 13:53:19.428  3853  3853 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:53:19.428  3853  3853 I Adreno  : Local Branch                     : M14
09-09 13:53:19.428  3853  3853 I Adreno  : Remote Branch                    : 
09-09 13:53:19.428  3853  3853 I Adreno  : Remote Branch                    : 
09-09 13:53:19.428  3853  3853 I Adreno  : Reconstruct Branch               : 
09-09 13:53:19.483   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c4760d6:true
,09-09 13:53:19.531  3853  3853 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:53:19.543  3853  3853 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 13:53:19.622  3853  3891 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:53:19.632  3853  3878 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:53:19.653  3853  3891 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:53:19.724   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +468ms
,09-09 13:53:19.727  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-09 13:53:19.813  3853  3853 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3853
,09-09 13:53:19.905  3853  3853 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:53:20.088  3853  3893 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1697646288
,09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:53:20.094  3853  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f415042 added. We now have 1 listener(s)
,09-09 13:53:20.097  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 13:53:20.098  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:53:20.099  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:53:20.099  3853  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000,
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:53:20.102  3853  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75c5e89 added. We now have 1 listener(s)
09-09 13:53:20.102  3853  3893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:53:20.107   874  2043 I ActivityManager: Killing 3311:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 13:53:20.108   874  1310 D WifiService: New client listening to asynchronous messages
09-09 13:53:20.109  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:53:20.109  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 13:53:20.109  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 13:53:20.110  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:53:20.110  3853  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:53:20.150   874  2043 I ActivityManager: Killing 3134:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-09 13:53:20.184  3853  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:53:20.185  3853  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 13:53:20.190  3853  3893 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:20.191  3853  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:53:20.191  3853  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
09-09 13:53:20.191  3853  3893 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:53:20.191  3853  3893 I io.jxcore.node.LifeCycleMonitor: start: OK,
,09-09 13:53:20.334  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:20.335  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:20.338  3853  3853 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-09 13:53:21.572  3853  3902 W jxcore-log: Initializing JXcore engine
09-09 13:53:21.572  3853  3902 W jxcore-log: JXcore engine is ready
09-09 13:53:21.608  3902  3902 W Thread-350: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-09 13:53:21.608  3902  3902 W Thread-350: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9806]" dev="sockfs" ino=9806 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-09 13:53:21.608  3902  3902 W Thread-350: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:53:21.619  3853  3902 W jxcore-log: Starting JXcore engine
09-09 13:53:21.608  3902  3902 W Thread-350: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26444]" dev="sockfs" ino=26444 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-09 13:53:21.701  3853  3902 W jxcore-log: Platform android
09-09 13:53:21.701  3853  3902 W jxcore-log: 
09-09 13:53:21.701  3853  3902 W jxcore-log: Process ARCH arm
09-09 13:53:21.701  3853  3902 W jxcore-log: 
09-09 13:53:21.893  3853  3902 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:53:21.893  3853  3902 I jxcore-log: 
09-09 13:53:21.894  3853  3902 W jxcore-log: JXcore engine is started
09-09 13:53:21.908  3853  3893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 13:53:21.914  3853  3853 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:53:22.726   874  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 13:53:29.468  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:29.473  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:29.474  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:29.490  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 13:53:29.490  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:53:29.490  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:53:29.490  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:53:29.501  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:53:29.501  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:53:29.501  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 13:53:29.746  3152  3914 V KeepSync: Connecting to GoogleApiClient
,09-09 13:53:29.747   874  2044 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:53:29.848  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:53:29.848  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 13:53:29.848  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:53:29.850  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:53:29.894  1738  3915 V BaseAuthAsyncOperation: access token request failed
,09-09 13:53:29.899  3152  3914 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:53:29.997  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:53:29.998  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:53:29.998  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:53:29.998  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:53:30.041  3152  3914 E KeepSync: IOException
09-09 13:53:30.041  3152  3914 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:53:30.041  3152  3914 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:53:30.041  3152  3914 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:53:30.041  3152  3914 E KeepSync: 	... 10 more
,09-09 13:53:30.041  3152  3914 W KeepSync: Sync result 2
,09-09 13:53:30.057   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129908, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:53:35.787  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:53:35.787  3853  3902 I jxcore-log: 
,09-09 13:53:35.790  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:53:35.790  3853  3902 I jxcore-log: 
,09-09 13:53:35.792  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
,09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:35.792  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:53:35.793  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:53:35.793  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:35.795  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:53:35.795  3853  3902 I jxcore-log: 
09-09 13:53:35.797  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:53:35.797  3853  3902 I jxcore-log: 
,09-09 13:53:36.144  3853  3902 I jxcore-log: Running unit tests
09-09 13:53:36.144  3853  3902 I jxcore-log: 
,09-09 13:53:36.145  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:53:36.145  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3826ad3 added. We now have 2 listener(s)
,09-09 13:53:36.146  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:53:36.146  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:53:36.146  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:53:36.147  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:53:36.147  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d45f610 added. We now have 2 listener(s)
,09-09 13:53:36.147  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:53:36.147  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:53:36.149  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:53:36.164  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:36.164  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:53:36.164  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:36.164  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:53:36.164  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:53:36.165  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:36.166  3853  3902 D executeNativeTests: Running unit tests
,09-09 13:53:36.167  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:36.256  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:53:36.256  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe added. We now have 3 listener(s)
,09-09 13:53:36.257  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:53:36.257  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:53:36.257  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:53:36.257  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:53:36.257  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f added. We now have 3 listener(s)
09-09 13:53:36.257  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:53:36.258  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:53:36.260  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:53:36.262  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:36.262  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:53:36.262  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:36.262  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:53:36.263  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:53:36.266  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:53:36.266  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:36.267  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:36.267  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:36.267  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:53:36.269  3853  3902 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 13:53:36.269  3853  3902 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:53:36.269  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:53:36.269  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:36.269  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:36.269  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:53:36.270  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:36.270  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:36.270  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:36.270  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:36.271  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.271  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:53:36.271  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:53:36.271  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe removed from the list
09-09 13:53:36.271  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:36.271  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f removed from the list
09-09 13:53:36.271  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:36.272  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:36.272  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.272  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.272  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.273  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:36.273  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:36.273  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:36.273  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:36.276  3853  3902 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 13:53:36.276  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:36.276  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:36.276  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:36.277  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:36.277  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.277  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.277  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:36.277  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:36.277  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:36.277  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:36.277  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.277  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.277  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.277  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.278  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:36.278  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:36.278  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:36.278  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:53:36.282  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:53:36.283  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:53:36.284  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:53:36.284  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:36.284  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:36.284  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:36.284  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:36.284  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.284  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.284  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:36.285  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:36.285  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:36.285  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:36.285  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.285  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.285  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:36.285  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:36.285  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:36.285  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:36.285  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:36.285  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:36.286  3853  3902 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 13:53:36.288  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:53:36.290  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:36.290  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:53:36.290  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:53:36.290  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:36.290  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:53:36.291  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:53:36.291  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:53:36.291  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:53:36.291  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:53:36.292  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:53:36.292  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:36.294  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:53:36.295  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-09 13:53:36.295  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:53:36.295  3853  3902 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:53:36.295  3853  3902 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:53:36.295  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:53:36.797  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:53:41.299  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:41.300  3853  3902 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-09 13:53:41.305  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:53:41.305  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:41.306  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:53:41.306  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:41.306  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:53:41.307  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:53:41.307  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:53:41.307  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:53:41.308  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:53:41.310  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:53:41.312  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:53:41.313  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:53:41.314  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:53:41.314  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:53:41.315  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:53:41.317  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:53:41.319  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:41.319  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:53:41.319  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:41.320  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:41.321  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:41.321  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:41.321  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:41.322  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:41.322  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:41.322  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:41.323  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:53:41.323  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:41.323  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:41.324  3853  3902 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 13:53:41.327  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:53:41.329  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:41.329  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:53:41.329  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:53:41.330  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:41.330  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:53:41.331  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:53:41.331  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:53:41.331  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:53:41.331  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:53:41.331  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:53:41.337  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:53:41.337  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:53:41.337  3853  3902 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:53:41.338  3853  3902 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:53:41.338  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:41.340  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:41.341  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:53:41.842  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:53:46.338  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:46.339  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:53:46.339  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:53:46.340  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:46.340  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:53:46.340  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:53:46.340  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:53:46.341  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:53:46.341  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:53:46.342  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:53:46.344  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:53:46.346  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:53:46.346  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:53:46.347  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:53:46.347  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:53:46.849  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 13:53:46.849  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:46.850  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:53:49.809   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:53:49.820  1872  1872 I Keyboard.Facilitator: onFinishInput()
,09-09 13:53:49.836   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:53:49.836   874   894 I Adreno  : Build Date                       : 10/20/15
09-09 13:53:49.836   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:53:49.836   874   894 I Adreno  : Local Branch                     : M14
09-09 13:53:49.836   874   894 I Adreno  : Remote Branch                    : 
09-09 13:53:49.836   874   894 I Adreno  : Remote Branch                    : 
09-09 13:53:49.836   874   894 I Adreno  : Reconstruct Branch               : 
,09-09 13:53:49.880   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (207 us)
,09-09 13:53:50.520  3853  3853 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:53:50.520  3853  3853 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:53:50.559   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 13:53:50.566  3853  3853 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@64d24cd Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@39a97b1, 16908290=android.view.AbsSavedState$1@39a97b1}, android:focusedViewId=100}]}]
,09-09 13:53:50.567  3853  3853 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:53:50.567  3853  3853 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:53:50.567  3853  3853 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:53:50.581   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 13:53:50.586   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF,
09-09 13:53:50.587   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-09 13:53:50.587   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 13:53:50.816   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 13:53:50.820   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 13:53:50.824   874  1335 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,09-09 13:53:50.827   874   894 I DreamManagerService: Entering dreamland.
09-09 13:53:50.828   874   894 I PowerManagerService: Dozing...
,09-09 13:53:50.829   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 13:53:50.911   378  2049 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 13:53:50.911   378  2049 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 13:53:50.923   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:53:50.937  1926  3921 D NfcService: Discovery configuration equal, not updating.
,09-09 13:53:50.939   874  1309 E native  : do suspend false
,09-09 13:53:50.957   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:53:50.983   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:53:50.988   874  1309 E native  : do suspend true
,09-09 13:53:51.030   378  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 13:53:51.031   378  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 13:53:51.349  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.350  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.350  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:53:51.351  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:53:51.351  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.352  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:53:51.352  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:51.352  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.353  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:51.353  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.353  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:51.355  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.355  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:51.356  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:53:51.357  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:53:51.357  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.357  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.360  3853  3902 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:53:51.362  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:53:51.362  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.363  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.364  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.364  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.364  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.364  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.365  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.365  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.365  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:53:51.366  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.366  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.366  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.366  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.368  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.368  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:53:51.368  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.369  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.371  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:53:51.371  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.371  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:53:51.371  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.372  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.372  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.372  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:51.372  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.372  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.372  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.372  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.372  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.372  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:51.372  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.372  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.373  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.373  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.373  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.373  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.374  3853  3902 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:53:51.374  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:53:51.374  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.374  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.374  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.374  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.374  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.374  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:51.375  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.375  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.375  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.375  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.375  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.375  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.375  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.375  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.376  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.376  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.376  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:51.376  3853  3902 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:53:51.376  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.377  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.377  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.377  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.377  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.377  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.377  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:51.377  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.377  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.377  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.377  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.378  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.378  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.378  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.378  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:53:51.378  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.378  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.378  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.379  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:53:51.379  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:51.379  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:51.379  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:53:51.379  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:51.380  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:51.380  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:53:51.380  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:51.380  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:53:51.380  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.380  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.380  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.380  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.380  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.381  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.381  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.381  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:51.381  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:51.381  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.381  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.381  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.381  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:51.381  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:51.382  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:53:51.382  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:53:51.382  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:51.382  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:51.383  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:53:51.383  3853  3902 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 13:53:51.383  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:53:51.386  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 13:53:51.387  3853  3902 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-09 13:53:51.387  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 13:53:51.388  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:53:51.389  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 13:53:51.389  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:53:51.390  3853  3902 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:53:51.390  3853  3902 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:53:51.390  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:53:51.390  3853  3902 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:53:51.390  3853  3902 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:53:51.390  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:53:51.390  3853  3902 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:53:51.390  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:53:51.392  3853  3902 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-09 13:53:51.392  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:53:51.393  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:53:51.393  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:53:51.394  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:53:51.394  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:53:51.394  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:53:51.395  3853  3902 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:53:51.395  3853  3902 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:53:51.396  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.396  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.396  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.396  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.396  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.396  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.396  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:53:51.397  3853  3925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 414)
09-09 13:53:51.397  3853  3925 E BluetoothDevice: Bluetooth is not enabled
09-09 13:53:51.398  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.398  3853  3902 I org.thaliproject.p2p.btcon,nectorlib.DiscoveryManager: dispose
09-09 13:53:51.398  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.398  3853  3925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 414)
09-09 13:53:51.398  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.398  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.398  3853  3925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 414)
09-09 13:53:51.398  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.398  3853  3925 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 414)
09-09 13:53:51.398  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.399  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.399  3853  3925 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 414
09-09 13:53:51.399  3853  3925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 414)
09-09 13:53:51.399  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.399  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.399  3853  3853 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-09 13:53:51.399  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.399  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.400  3853  3853 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-09 13:53:51.400  3853  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:53:51.401  3853  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:51.401  3853  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:51.402  3853  3902 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:53:51.403  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.403  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.403  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.404  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.404  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.404  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.404  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.404  3853  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 414
09-09 13:53:51.404  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.404  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.404  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.404  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.404  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.405  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.405  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.405  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.405  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.405  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.405  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.406  3853  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:53:51.406  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.407  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.407  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.407  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.407  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.407  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.407  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.407  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.407  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.407  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.407  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.408  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.408  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.408  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.410  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.410  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.410  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.410  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.410  3853  3902 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:53:51.411  3853  3902 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:53:51.411  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:53:51.411  3853  3902 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:53:51.411  3853  3902 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:53:51.411  3853  3902 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:53:51.411  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:53:51.411  3853  3902 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:53:51.411  3853  3902 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:53:51.411  3853  3902 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:53:51.411  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:53:51.411  3853  3902 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:53:51.412  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:51.412  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:51.412  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:51.412  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.412  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.412  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.412  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.412  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.412  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.412  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.412  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.412  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.412  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.412  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.413  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:51.413  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:51.413  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.413  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.414  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:51.414  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.414  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.414  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:51.414  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:51.414  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:51.414  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:51.414  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:51.414  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:51.427   874  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 13:53:55.095  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:55.105  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:55.109  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:53:55.166  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:53:55.167  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:53:55.167  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:53:55.167  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:53:55.239  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 13:53:55.245  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:53:55.246  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 13:53:56.415  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:56.416  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.416  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.416  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:56.416  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.417  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:56.417  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:56.418  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:53:56.418  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:56.418  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:53:56.419  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.419  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.419  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:56.420  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.420  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.420  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:53:56.420  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:56.421  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:53:56.421  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.423  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.425  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:56.425  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:56.425  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.426  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.430  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:53:56.432  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:53:56.432  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-09 13:53:56.432  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:53:56.433  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:53:56.433  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-09 13:53:56.434  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.434  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:53:56.435  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.435  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-09 13:53:56.435  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:53:56.435  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:56.436  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.436  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:53:56.436  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:53:56.436  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:53:56.437  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.437  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.438  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:53:56.439  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:56.439  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 13:53:56.439  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-09 13:53:56.441  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:53:56.441  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:53:56.441  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.441  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.441  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:53:56.442  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.442  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:56.442  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.442  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:53:56.446  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:56.446  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:56.446  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.446  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.446  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.446  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.447  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 13:53:56.447  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:56.447  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.447  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:56.448  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:53:56.448  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:53:56.448  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:53:56.448  3853  3902 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:53:56.449  3853  3902 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:53:56.449  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:53:56.449  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:53:56.449  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:53:56.449  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:56.449  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:56.449  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:56.449  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.449  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:56.449  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.449  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:56.450  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:56.450  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.450  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:56.450  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.450  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.450  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:56.450  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.450  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:56.451  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:56.451  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.451  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
,09-09 13:53:56.453  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:53:56.453  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:53:56.453  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:53:56.454  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.454  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.454  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.454  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
,09-09 13:53:56.454  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.454  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.454  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:56.454  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:53:56.454  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.455  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.455  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.455  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:56.455  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:53:56.455  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:53:56.455  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.457  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 13:53:56.457  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:53:56.457  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:53:56.457  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:53:56.457  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.457  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.458  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4ebbe not in the list
09-09 13:53:56.458  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.458  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.459  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:53:56.459  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.459  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.459  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:53:56.459  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:53:56.460  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:53:56.460  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:53:56.460  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:53:56.460  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d70741f not in the list
09-09 13:53:56.462  3853  3902 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:53:56.462  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:53:56.462  3853  3902 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:53:56.462  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:53:56.462  3853  3902 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:53:56.462  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:53:56.465  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:53:56.465  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:53:56.466  3853  3902 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:53:56.466  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:53:56.466  3853  3902 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:53:56.466  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:53:56.467  3853  3902 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:53:56.467  3853  3902 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 13:53:56.468  3853  3902 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 13:53:56.468  3853  3902 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 13:53:56.469  3853  3902 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:53:56.470  3853  3902 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-09 13:53:56.470  3853  3902 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:53:56.470  3853  3902 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-09 13:53:56.471  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:53:56.471  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f0b496 added. We now have 3 listener(s)
09-09 13:53:56.472  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:53:56.473   874  1918 D WifiService: setWifiEnabled: true pid=3853, uid=10000
,09-09 13:53:56.473   874  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:53:56.494   874   891 I ActivityManager: Start proc 3930:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 13:53:56.619  3930  3930 D AdapterServiceConfig: Adding HeadsetService
,09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding A2dpService
,09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding HidService
09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding HealthService
09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding PanService
,09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding GattService
09-09 13:53:56.620  3930  3930 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:53:56.677   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7901871:true
,09-09 13:53:56.681  3930  3930 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:53:56.685  3930  3930 I bt_bluedroid: init
09-09 13:53:56.685  3930  3942 I BluetoothAdapterState: Entering OffState
,09-09 13:53:56.693  3930  3943 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:53:56.696  3930  3943 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:53:56.696  3930  3943 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:53:56.696  3930  3943 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:53:56.699  3930  3930 I bt_bluedroid: get_profile_interface socket
,09-09 13:53:56.701  3930  3930 I bt_bluedroid: get_profile_interface sdp
,09-09 13:53:56.704  3930  3941 I bt_bluedroid: config_hci_snoop_log
,09-09 13:53:56.704  3930  3946 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:53:56.707   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-09 13:53:56.708  3930  3946 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:53:56.712  3930  3942 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:53:56.712  3930  3942 D BluetoothAdapterProperties: Setting state to 14
09-09 13:53:56.712  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 13:53:56.716  3930  3942 D BluetoothBondStateMachine: make
,09-09 13:53:56.719  3930  3947 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:53:56.727  3930  3942 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:53:56.728  3930  3930 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:53:56.733  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:56.734  3930  3930 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:53:56.735  3930  3930 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:53:56.735  3930  3930 D BtGatt.GattService: start()
09-09 13:53:56.736  3930  3930 I bt_bluedroid: get_profile_interface gatt
09-09 13:53:56.737  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:56.737  3930  3930 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:53:56.746  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:53:56.746  3930  3930 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:53:56.746  3930  3930 V BluetoothAdapterState: isBleTurningOn()=true
09-09 13:53:56.746  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:56.748  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 13:53:56.749  3930  3942 I bt_bluedroid: enable,
09-09 13:53:56.749  3930  3943 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 13:53:56.749  3930  3943 I bt_hci  : start_up
,09-09 13:53:56.765  3930  3943 I bt_vendor: alloc value 0xb39d7189
,09-09 13:53:56.765  3930  3943 I bt_vendor: init
09-09 13:53:56.765  3930  3943 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 13:53:56.765  3930  3943 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:53:56.874  3930  3943 D bt_hci  : start_up starting async portion
,09-09 13:53:56.875  3930  3950 I bt_hci  : event_finish_startup
09-09 13:53:56.875  3930  3950 I bt_hci_h4: hal_open
09-09 13:53:56.875  3930  3950 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:53:56.883  3930  3950 I bt_userial_vendor: device fd = 51 open
,09-09 13:53:56.916  3930  3950 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:53:56.947  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:53:56.947  3930  3950 D bt_hwcfg: Chipset BCM4354A2
09-09 13:53:56.948  3930  3950 D bt_hwcfg: Target name = [BCM4354A2]
09-09 13:53:56.949  3930  3950 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:53:57.612  3930  3950 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 13:53:57.613  3930  3950 D bt_hwcfg: Settlement delay -- 100 ms
09-09 13:53:57.614  3930  3950 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:53:57.730  3930  3950 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:53:57.732  3930  3950 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:53:57.760  3930  3950 I bt_hwcfg: vendor lib fwcfg completed
,09-09 13:53:57.761  3930  3950 I bt_vendor: firmware callback
,09-09 13:53:57.761  3930  3950 I bt_hci  : firmware_config_callback
,09-09 13:53:57.772  3930  3952 I bt_btu  : btu_task pending for preload complete event
,09-09 13:53:57.772  3930  3952 I bt_btu_task: Bluetooth chip preload is complete
09-09 13:53:57.772  3930  3952 I bt_btu  : btu_task received preload complete event
,09-09 13:53:57.785  3930  3952 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 13:53:57.785  3930  3952 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 13:53:57.786  3930  3952 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:53:57.786  3930  3952 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:53:57.786  3930  3952 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:53:57.786  3930  3952 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:53:57.787  3930  3952 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:53:57.787  3930  3952 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:53:57.788  3930  3952 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:53:57.789  3930  3952 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 13:53:57.789  3930  3952 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 13:53:57.789  3930  3952 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 13:53:57.789  3930  3952 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 13:53:57.790  3930  3952 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-09 13:53:57.790  3930  3952 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:53:57.923  3930  3952 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,09-09 13:53:57.923  3930  3952 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,09-09 13:53:57.935  3930  3946 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 13:53:57.938  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 13:53:57.939  3930  3946 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 13:53:57.942  3930  3946 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:53:57.945  3930  3946 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:53:57.946  3930  3946 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:53:57.946  3930  3946 D bt_hci  : do_postload posting postload work item
09-09 13:53:57.947  3930  3950 I bt_hci  : event_postload
09-09 13:53:57.947  3930  3950 I bt_vendor: sco_config_cb
09-09 13:53:57.947  3930  3950 I bt_hci  : sco_config_callback postload finished.
,09-09 13:53:57.954  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:57.957  3930  3946 D bt_bte_conf: Device ID record 1 : primary
,09-09 13:53:57.957  3930  3946 D bt_bte_conf:   vendorId            = 000f
,09-09 13:53:57.958  3930  3946 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 13:53:57.958  3930  3946 D bt_bte_conf:   product             = 1200
09-09 13:53:57.958  3930  3946 D bt_bte_conf:   version             = 1436
09-09 13:53:57.958  3930  3946 D bt_bte_conf:   clientExecutableURL = 
,09-09 13:53:57.958  3930  3946 D bt_bte_conf:   serviceDescription  = 
,09-09 13:53:57.960  3930  3946 D bt_bte_conf:   documentationURL    = 
,09-09 13:53:57.960  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:57.962  3930  3950 I bt_vendor: low_power_mode_cb
09-09 13:53:57.961  3930  3946 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:53:57.962  3930  3943 D bt_stack_manager: event_start_up_stack finished
09-09 13:53:57.963  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-09 13:53:57.963  3930  3942 D BluetoothAdapterProperties: Setting state to 15
09-09 13:53:57.963  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 13:53:57.964  3930  3942 I BluetoothAdapterState: Entering BleOnState
,09-09 13:53:57.971  3930  3942 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 13:53:57.971  3930  3942 D BluetoothAdapterProperties: Setting state to 11
,09-09 13:53:57.971  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 13:53:57.977  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:57.978  3930  3930 D HeadsetService: Received start request. Starting profile...
09-09 13:53:57.988  3930  3930 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 13:53:57.989  3930  3930 D HeadsetStateMachine: make
,09-09 13:53:57.993  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:57.997  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:58.005   874   887 I ActivityManager: Start proc 3960:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-09 13:53:58.008  3930  3930 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:53:58.008  3930  3930 I bt_bluedroid: get_profile_interface handsfree
09-09 13:53:58.008  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:53:58.009  3930  3946 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-09 13:53:58.011  3930  3942 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:53:58.012  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:53:58.013   874   874 D BluetoothA2dp: Proxy object connected
09-09 13:53:58.014  3930  3930 D A2dpService: Received start request. Starting profile...
09-09 13:53:58.015  3930  3930 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 13:53:58.016  3930  3930 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:53:58.023  3930  3930 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:53:58.023  3930  3930 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:53:58.023  3930  3930 D A2dpStateMachine: make
,09-09 13:53:58.025  3930  3930 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:53:58.026  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-09 13:53:58.028  3930  3973 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:53:58.029  3930  3930 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 13:53:58.030  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:58.031  1366  1366 D BluetoothInputDevice: Proxy object connected
,09-09 13:53:58.032  3930  3930 D HidService: Received start request. Starting profile...
09-09 13:53:58.032  3930  3930 I bt_bluedroid: get_profile_interface hidhost
,09-09 13:53:58.032  3930  3930 D HidService: setHidService(): set to: null
,09-09 13:53:58.032  3930  3946 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
09-09 13:53:58.032  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 13:53:58.032  1366  1366 D HidProfile: Bluetooth service connected
09-09 13:53:58.033  3930  3930 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 13:53:58.034  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:58.035  3930  3930 D HealthService: Received start request. Starting profile...
,09-09 13:53:58.036  3930  3930 I bt_bluedroid: get_profile_interface health
,09-09 13:53:58.037  3930  3930 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 13:53:58.037  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:58.039  3930  3930 D PanService: Received start request. Starting profile...
,09-09 13:53:58.039  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:53:58.039  3930  3930 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:53:58.039  3930  3930 I bt_bluedroid: get_profile_interface pan
09-09 13:53:58.039  3930  3946 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:53:58.040  1366  1366 D PanProfile: Bluetooth service connected
,09-09 13:53:58.041  3930  3930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:53:58.042  2155  2736 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
09-09 13:53:58.042  1366  1366 D BluetoothMap: Proxy object connected
09-09 13:53:58.043  3930  3930 D BluetoothMapService: Received start request. Starting profile...
09-09 13:53:58.043  3930  3930 D BluetoothMapService: start()
09-09 13:53:58.043  1366  1366 D MapProfile: Bluetooth service connected
09-09 13:53:58.043  1366  1366 D BluetoothMap: getConnectedDevices()
09-09 13:53:58.043  1366  1366 D BluetoothMap: Bluetooth is Not enabled
,09-09 13:53:58.045  3930  3930 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 13:53:58.045  3930  3930 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 13:53:58.045  3930  3930 D BluetoothMapAppObserver: createReceiver()
,09-09 13:53:58.046  3930  3930 D BluetoothMapAppObserver: initObservers()
09-09 13:53:58.047  3930  3930 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:53:58.051  3960  3960 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 13:53:58.052  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:53:58.052  3930  3930 V BluetoothAdapterState: isTurningOn()=true
09-09 13:53:58.052  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.052  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isTurningOn()=true
09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.054  3930  3958 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isTurningOn()=true
09-09 13:53:58.054  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isTurningOff()=false
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isTurningOn()=true
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:58.055  3930  3930 V BluetoothAdapterState: isTurningOff()=false
09-09 13:53:58.056  3930  3930 V BluetoothAdapterState: isTurningOn()=true
09-09 13:53:58.056  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:53:58.056  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:53:58.056  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 13:53:58.056  3930  3942 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:53:58.056  3930  3942 D BluetoothAdapterProperties: State =  11
09-09 13:53:58.057  3930  3942 D BluetoothAdapterProperties: Setting state to 12
09-09 13:53:58.057  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 13:53:58.057  3930  3942 I BluetoothAdapterState: Entering OnState
,09-09 13:53:58.057  3930  3946 D BluetoothAdapterProperties: Scan Mode:21
09-09 13:53:58.057  3930  3946 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:53:58.057  1366  1379 D BluetoothPan: onBluetoothStateChange on: true
,09-09 13:53:58.058   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:53:58.059  1366  2075 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:53:58.060  1366  1380 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:53:58.060  1938  1949 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:53:58.061   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:53:58.061   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:53:58.061  3853  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 13:53:58.061  1366  1388 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:53:58.064  3853  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 13:53:58.064   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:53:58.066   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 13:53:58.067  3930  3930 D BluetoothMapService: onReceive
09-09 13:53:58.067  3930  3930 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:53:58.067  3930  3930 D BluetoothMapService: STATE_ON
09-09 13:53:58.068  3853  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:53:58.071  1366  1654 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:58.073  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:53:58.073  3930  3930 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:53:58.073  3930  3930 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 13:53:58.075  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:53:58.075  3930  3930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:53:58.077   874  1921 I ActivityManager: Killing 3493:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:53:58.079  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:53:58.081  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:53:58.083  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:58.084  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:53:58.110  3930  3930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:53:58.110  1366  1366 D BluetoothA2dp: Proxy object connected
,09-09 13:53:58.112  3930  3930 D ObexServerSockets: Succeed to create listening sockets 
,09-09 13:53:58.112  3930  3930 D ObexServerSockets0: startAccept()
09-09 13:53:58.112  3930  3930 D ObexServerSockets0: prepareForNewConnect()
,09-09 13:53:58.112  1366  1654 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 13:53:58.114  3930  3930 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 13:53:58.115  3930  3930 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 13:53:58.116  3930  3930 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 13:53:58.116  3930  3930 D ObexServerSockets0: prepareForNewConnect()
,09-09 13:53:58.117  3930  3979 D ObexServerSockets0: Accepting socket connection...
09-09 13:53:58.117  3930  3980 D ObexServerSockets0: Accepting socket connection...
,09-09 13:53:58.119  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:53:58.134   874  2044 I ActivityManager: Start proc 3981:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 13:53:58.159   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:53:58.162  1938  1948 D BluetoothHeadset: Proxy object connected
09-09 13:53:58.163   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:53:58.164   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:53:58.197  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 13:53:58.215  1366  2075 D BluetoothHeadset: Proxy object connected
,09-09 13:53:58.217  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared,.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(Ac,tivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.357  3981  3981 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:53:58.357  3981  3981 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:53:58.374  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 13:53:58.383  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:53:58.389  1366  1366 D BluetoothPbap: Proxy object connected
09-09 13:53:58.391  1366  1366 D PbapServerProfile: Bluetooth service connected
09-09 13:53:58.393   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7242a66:true
,09-09 13:53:58.397  3930  4006 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:53:58.410  3960  3960 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 13:53:58.415  3960  3960 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 13:53:58.433  3960  3960 D LocalBluetoothProfileManager: Adding local MAP profile
09-09 13:53:58.434  3960  3960 D BluetoothMap: Create BluetoothMap proxy object
09-09 13:53:58.440  3960  3960 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:53:58.443  3930  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:53:58.446  3930  4012 I BtOppRfcommListener: Accept thread started.
,09-09 13:53:58.461  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:53:58.462  3960  3960 D BluetoothA2dp: Proxy object connected
,09-09 13:53:58.466  3960  3960 D BluetoothInputDevice: Proxy object connected
,09-09 13:53:58.467  3960  3960 D HidProfile: Bluetooth service connected
,09-09 13:53:58.469  3960  3960 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:53:58.470  3960  3960 D PanProfile: Bluetooth service connected
,09-09 13:53:58.470  3960  3960 D BluetoothMap: Proxy object connected
09-09 13:53:58.470  3960  3960 D MapProfile: Bluetooth service connected
,09-09 13:53:58.471  3960  3960 D BluetoothMap: getConnectedDevices()
,09-09 13:53:58.473  3960  3960 D BluetoothPbap: Proxy object connected
,09-09 13:53:58.473  3960  3960 D PbapServerProfile: Bluetooth service connected
,09-09 13:53:58.475   874  1986 I ActivityManager: Killing 2467:com.google.android.talk/u0a61 (adj 15): empty #17
,09-09 13:53:58.519  3960  3970 D BluetoothHeadset: Proxy object connected
,09-09 13:53:58.520  3960  3960 D HeadsetProfile: Bluetooth service connected
,09-09 13:53:58.610  3981  4001 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:53:58.655   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9dabd23:true
,09-09 13:54:01.482  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:54:01.482  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d86c817 added. We now have 4 listener(s)
09-09 13:54:01.483  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:54:01.500  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:01.500  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d86c817 removed from the list
09-09 13:54:01.501  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:01.501  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:54:01.501  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:01.504  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:54:01.504  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c246404 added. We now have 4 listener(s)
09-09 13:54:01.505  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:54:01.509  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:01.510  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c246404 removed from the list
09-09 13:54:01.510  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:01.510  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:54:01.510  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:01.514  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:54:01.515  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10ffded added. We now have 4 listener(s)
09-09 13:54:01.515  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:54:01.522   874  2042 D WifiService: setWifiEnabled: false pid=3853, uid=10000
,09-09 13:54:01.522   874  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:54:01.536  3930  3942 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 13:54:01.537  3930  3942 D BluetoothAdapterProperties: Setting state to 13
,09-09 13:54:01.537  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:54:01.537  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:54:01.539  3930  3942 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:54:01.543  3930  3942 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:01.558  3930  3930 D BluetoothMapService: onReceive
09-09 13:54:01.558  3930  3930 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:54:01.560  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:01.559  3930  3930 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:01.560  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:54:01.561  3930  3946 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:54:01.561  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 13:54:01.562  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.562  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:54:01.562  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:54:01.563  3930  3930 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:54:01.567  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.567  3930  3930 D BluetoothMapService: MAP Service closeService in
,09-09 13:54:01.567  3930  3930 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 13:54:01.567   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:01.567  3930  3930 D ObexServerSockets0: shutdown(block = true)
09-09 13:54:01.567  3930  3979 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 13:54:01.568  1938  1949 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:01.568  1366  1380 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:01.569   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:01.569  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:01.569   874   874 D BluetoothHeadset: Proxy object disconnected,
,09-09 13:54:01.569  3960  3972 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:01.570  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.570  3930  3930 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:54:01.570  3930  3930 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:54:01.571  3930  3980 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:54:01.571  3930  3955 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 13:54:01.572  3930  3930 I BtOppRfcommListener: stopping Accept Thread
09-09 13:54:01.573  3930  4012 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:54:01.574  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.574  3930  4012 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:01.574  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:54:01.575  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 13:54:01.576  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.576  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:01.577  3930  3930 D A2dpService: Received stop request...Stopping profile...
09-09 13:54:01.578  3930  3973 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:54:01.578   874  1309 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 13:54:01.579   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 13:54:01.579   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:54:01.579   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:01.580   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 13:54:01.580  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:01.580  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:54:01.581  3930  3930 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:01.581  3930  3930 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:01.581  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:01.581  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:01.582  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.582  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:01.582  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-09 13:54:01.582  1366  1366 D BluetoothA2dp: Proxy object disconnected
09-09 13:54:01.583  3930  3930 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:54:01.584  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:01.584  3960  3960 D HeadsetProfile: Bluetooth service disconnected
09-09 13:54:01.584  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:01.584  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:54:01.584  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 13:54:01.584  3930  3946 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 13:54:01.584  3930  3930 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:54:01.585  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.587  3930  3930 D HidService: Received stop request...Stopping profile...
,09-09 13:54:01.587  3930  3930 D HidService: Stopping Bluetooth HidService
,09-09 13:54:01.589  1366  1366 D BluetoothInputDevice: Proxy object disconnected
,09-09 13:54:01.589  1366  1366 D HidProfile: Bluetooth service disconnected
09-09 13:54:01.590  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.591  3930  3930 D HealthService: Received stop request...Stopping profile...
09-09 13:54:01.592  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.592   874  1309 E native  : do suspend true
,09-09 13:54:01.594  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:01.595  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:54:01.597  3930  3930 D PanService: Received stop request...Stopping profile...
,09-09 13:54:01.597  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:54:01.597  1366  1366 D PanProfile: Bluetooth service disconnected
,09-09 13:54:01.600  3930  3930 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 13:54:01.600  3930  3930 D BluetoothMapService: stop()
09-09 13:54:01.600  3930  3930 D BluetoothMapAppObserver: deinitObservers()
09-09 13:54:01.600  3930  3930 D BluetoothMapAppObserver: removeReceiver()
,09-09 13:54:01.601  1366  1366 D BluetoothMap: Proxy object disconnected
09-09 13:54:01.601  1366  1366 D MapProfile: Bluetooth service disconnected
09-09 13:54:01.601  3960  3960 D BluetoothA2dp: Proxy object disconnected
09-09 13:54:01.602  3960  3960 D BluetoothInputDevice: Proxy object disconnected
09-09 13:54:01.602  3930  3930 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:54:01.602  3960  3960 D HidProfile: Bluetooth service disconnected
09-09 13:54:01.602  3930  3930 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:01.602  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:01.602  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:01.603  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 13:54:01.603  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:01.603  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:01.603  3930  3952 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:54:01.604  3930  3952 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:54:01.604  3930  3952 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:54:01.604  3930  3952 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:54:01.604  3960  3960 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 13:54:01.604  3960  3960 D PanProfile: Bluetooth service disconnected
09-09 13:54:01.604  3960  3960 D BluetoothMap: Proxy object disconnected
09-09 13:54:01.604   874  1888 D DhcpClient: Clearing IP address
09-09 13:54:01.605   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:54:01.606  3930  3930 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:01.606  3930  3930 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:01.606  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:01.607  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:01.607  3930  3930 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 13:54:01.607  3930  3946 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 13:54:01.607  3930  3930 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 13:54:01.607  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:54:01.604  3960  3960 D MapProfile: Bluetooth service disconnected
09-09 13:54:01.608   374   872 D CommandListener: Setting iface cfg,
09-09 13:54:01.608  3930  3930 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:54:01.608  3930  3930 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:54:01.608  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:01.608  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:01.609  3930  3930 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 13:54:01.609  3930  3946 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:54:01.609  3930  3930 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:54:01.609  3930  3930 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:01.610  1515  3547 V NativeCrypto: Read error: ssl=0x9b2bf400: I/O error during system call, Connection timed out
09-09 13:54:01.609  3930  3930 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:01.610  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:01.610  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:01.611  1515  3547 V NativeCrypto: SSL shutdown failed: ssl=0x9b2bf400: I/O error during system call, Broken pipe
,09-09 13:54:01.612   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-09 13:54:01.612   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:54:01.612   874  1309 E native  : do suspend true
,09-09 13:54:01.612  3930  3930 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 13:54:01.612  3930  3930 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:54:01.613   874  2043 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-09 13:54:01.613   874  1877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011,
09-09 13:54:01.614  3930  3930 D BluetoothMapService: MAP Service closeService in
,09-09 13:54:01.615   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:54:01.615   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-09 13:54:01.617   397   397 E Parcel  : Reading a NULL string not supported here.
,09-09 13:54:01.617   874  1877 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-09 13:54:01.618  3930  3930 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:54:01.618  3930  3930 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:54:01.618  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:01.618  3930  3930 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:01.619  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 13:54:01.619  3930  3942 D BluetoothAdapterProperties: Setting state to 15
,09-09 13:54:01.619  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:54:01.619  3930  3930 D BluetoothMapService: cleanup()
,09-09 13:54:01.619  3930  3930 D BluetoothMapService: MAP Service closeService in
09-09 13:54:01.619   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 13:54:01.619  1366  2075 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:54:01.620  3930  3942 I BluetoothAdapterState: Entering BleOnState
,09-09 13:54:01.620   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:01.621  1366  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:54:01.621  1366  1366 D BluetoothPbap: Proxy object disconnected
09-09 13:54:01.621  1366  1366 D PbapServerProfile: Bluetooth service disconnected
09-09 13:54:01.622  1366  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:54:01.622  3960  3960 D BluetoothPbap: Proxy object disconnected
09-09 13:54:01.622  3960  3960 D PbapServerProfile: Bluetooth service disconnected
09-09 13:54:01.626  3960  3972 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:54:01.627  1366  1380 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:54:01.632   874  1891 D DhcpClient: Receive thread stopped
09-09 13:54:01.637   874   884 I ActivityManager: Start proc 4026:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 13:54:01.639  1938  2088 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:54:01.639   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:54:01.639   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:54:01.639  3960  3970 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 13:54:01.640  1366  2075 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:54:01.640   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:54:01.640  3960  3972 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:01.640  1366  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:01.641  3960  3970 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:54:01.641  3960  3972 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:54:01.642  3960  3970 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:54:01.642  3930  3942 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 13:54:01.643  3930  3942 D BluetoothAdapterProperties: Setting state to 16
,09-09 13:54:01.643  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 13:54:01.643  3930  3942 D BluetoothAdapterProperties: onBleDisable
09-09 13:54:01.644  3930  3942 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:01.644  3930  3943 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-09 13:54:01.644  3930  3952 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 13:54:01.644  3930  3952 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:01.644  3930  3946 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:54:01.647  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.647  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:01.647  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.647  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:01.651  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.651  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:01.652  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.652  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:01.653  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.653  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:01.654  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.654  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:01.655  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.656  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.657  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.672   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:54:01.684  4026  4026 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
09-09 13:54:01.687   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-09 13:54:01.687   374   872 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:54:01.689   874  1311 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 N,etworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 13:54:01.689   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-09 13:54:01.692   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 13:54:01.692  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.693  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:01.694  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:01.735   374   872 E Netd    : netlink response contains error (No such file or directory)
,09-09 13:54:01.736   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 13:54:01.736   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:54:01.750   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:54:01.752  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.752  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:01.753  2155  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:54:01.753  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.753  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:01.753   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:54:01.754  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.754  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:01.754  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.754  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:01.756  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:01.756  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:01.756  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:01.756  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:01.841  4026  4051 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-09 13:54:01.841  4026  4051 I Babel_SMS: MmsConfig.loadMmsSettings
,09-09 13:54:01.846  3930  3946 I bt_hci  : shut_down
,09-09 13:54:01.846  4026  4051 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 13:54:01.846  4026  4051 I Babel_SMS: MmsConfig.loadFromDatabase
09-09 13:54:01.846  3930  3950 D bt_hwcfg: hw_epilog_process
,09-09 13:54:01.848  3930  3950 I bt_vendor: low_power_mode_cb
,09-09 13:54:01.871  4026  4051 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 13:54:01.871  4026  4051 I Babel_SMS: MmsConfig.loadFromResources
,09-09 13:54:01.876  4026  4051 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:54:01.876  4026  4051 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 13:54:01.879  3930  3950 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 13:54:01.879  3930  3950 I bt_vendor: epilog_cb
09-09 13:54:01.879  3930  3950 I bt_hci  : epilog_finished_callback
,09-09 13:54:01.884  3930  3946 I bt_hci_h4: hal_close
,09-09 13:54:01.885  3930  3946 I bt_userial_vendor: device fd = 51 close
,09-09 13:54:01.909  4026  4026 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:54:01.912  4026  4026 I Babel_Crash: startup - clean
,09-09 13:54:01.937  4026  4026 I Babel_telephony: TeleModule.launchCompleted
,09-09 13:54:01.949   874  1922 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 13:54:01.959  4026  4026 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 13:54:01.967  4026  4026 W Babel   : BAM#gBA: invalid account id: -1
,09-09 13:54:01.967  4026  4026 W Babel   : BAM#gBA: invalid account id: -1
,09-09 13:54:01.968  4026  4026 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 13:54:01.978  4026  4056 I Babel   : deleted: false for 0
,09-09 13:54:01.989   874  1386 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 13:54:02.001  3930  3943 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:54:02.001  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 13:54:02.003  3930  3942 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 13:54:02.003  3930  3930 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:54:02.004  3930  3930 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 13:54:02.005  3930  3930 D BtGatt.GattService: stop()
09-09 13:54:02.005  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:02.005  3930  3930 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 13:54:02.018  3930  3930 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:54:02.019  3930  3930 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:02.019  3930  3930 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:02.019  3930  3930 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 13:54:02.020  3930  3942 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 13:54:02.020  3930  3942 D BluetoothAdapterProperties: Setting state to 10
09-09 13:54:02.020  3930  3942 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 13:54:02.021  3930  3942 I BluetoothAdapterState: Entering OffState
09-09 13:54:02.023   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-09 13:54:02.023  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:54:02.045  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:54:02.055  3930  3930 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 13:54:02.055  3930  3930 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-09 13:54:02.055  3930  3943 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 13:54:02.057  3930  3943 D bt_stack_manager: event_clean_up_stack finished.
09-09 13:54:02.057  3930  3930 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 13:54:02.061  3930  3930 I art     : System.exit called, status: 0
09-09 13:54:02.061  3930  3930 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 13:54:02.063  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:54:02.073  1738  1738 D SystemUpdateService: onCreate
,09-09 13:54:02.082  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:54:02.100  1738  4060 I SystemUpdateService: active receiver: enabled
,09-09 13:54:02.107  1738  4060 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:54:02.111  1738  4060 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 13:54:02.112  1738  4060 I SystemUpdateService: now status is 0 (complete)
,09-09 13:54:02.112  1738  4060 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 13:54:02.112  1738  4060 I SystemUpdateService: file has been verified
,09-09 13:54:02.113  1738  4060 I SystemUpdateService: OTA package size = 12249756
,09-09 13:54:02.118  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:54:02.123  1738  2430 I iu.UploadsManager: num queued entries: 0
,09-09 13:54:02.124  1738  4060 I SystemUpdateService: showing system update notification
,09-09 13:54:02.129  1738  2430 I iu.UploadsManager: num updated entries: 0
,09-09 13:54:02.134  4026  4026 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:54:02.137  1738  2430 I iu.SyncManager: NEXT; no task
,09-09 13:54:02.149   874  1921 I ActivityManager: Process com.android.bluetooth (pid 3930) has died,
,09-09 13:54:02.159  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:54:02.161  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 13:54:02.161  1738  1738 D SystemUpdateService: onDestroy
,09-09 13:54:02.179   874  1987 I ActivityManager: Start proc 4062:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 13:54:02.229  4062  4062 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 13:54:02.233  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:54:02.235  4026  4026 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:54:02.248  4026  4026 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:54:02.252  4062  4062 D SprintDMHelper: simOperator: 
,09-09 13:54:02.252  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:54:02.270  4026  4026 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:54:02.274  4026  4026 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:54:02.276   874  1918 I ActivityManager: Start proc 4074:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 13:54:02.282  4026  4026 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:54:02.290   874  1922 I ActivityManager: Killing 3634:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 13:54:02.344  4026  4026 I vclib   : onServiceConnected
,09-09 13:54:02.443   874  1987 I ActivityManager: Start proc 4089:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 13:54:02.447  4026  4088 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 13:54:02.459   874  2042 I ActivityManager: Killing 2898:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 13:54:02.526  4089  4089 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 13:54:02.588  4089  4089 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:54:02.588  4089  4089 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:54:02.588  4089  4089 I GAv4    :   adb logcat -s GAv4
,09-09 13:54:02.606  4089  4089 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:54:02.613  4089  4089 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:54:02.644  4089  4106 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:54:02.748  4089  4089 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 13:54:02.790  4089  4089 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 13:54:02.802  4089  4089 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3034-3040)
,09-09 13:54:02.803  4089  4089 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:54:02.813  4089  4089 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f71c43}
,09-09 13:54:02.813  4089  4089 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:54:02.813  4089  4089 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:54:02.823  4089  4089 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:54:02.824  4089  4089 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:54:02.842  4089  4089 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:54:02.858  4089  4089 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:54:02.858  4089  4089 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:54:02.858  4089  4089 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:54:02.858  4089  4089 I Adreno  : Build Date                       : 10/20/15
09-09 13:54:02.858  4089  4089 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:54:02.858  4089  4089 I Adreno  : Local Branch                     : M14
09-09 13:54:02.858  4089  4089 I Adreno  : Remote Branch                    : 
09-09 13:54:02.858  4089  4089 I Adreno  : Remote Branch                    : 
09-09 13:54:02.858  4089  4089 I Adreno  : Reconstruct Branch               : 
,09-09 13:54:02.925  4089  4089 I NSApplication: Starting up...
,09-09 13:54:02.935  4089  4135 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:54:02.966   874  1386 I ActivityManager: Start proc 4140:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 13:54:02.967   874  1386 I ActivityManager: Killing 3576:android.process.acore/u0a5 (adj 15): empty #17
,09-09 13:54:03.059  4140  4140 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 13:54:03.332   874  1386 I ActivityManager: Killing 3707:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 13:54:03.413   874   885 I ActivityManager: Start proc 4154:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 13:54:03.493  4154  4154 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 13:54:03.536  4154  4154 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 13:54:03.547   874  1918 I ActivityManager: Killing 3723:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 13:54:03.732   874  1918 I ActivityManager: Killing 2238:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 13:54:06.566   874  1922 D WifiService: setWifiEnabled: true pid=3853, uid=10000
09-09 13:54:06.566   874  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:54:06.580   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:54:06.587  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:06.587  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:06.587  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:06.588  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:06.590  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:06.590  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:06.591  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:06.591  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:06.593  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:06.594  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:06.594  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:06.594  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:06.620   874  1309 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:54:06.626   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 13:54:06.626   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:54:06.627   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:54:06.628   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 13:54:06.628   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:54:06.628   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:54:06.650   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:54:06.651   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.12 rxSuccessRate=14.62 delta 1000 -> 994
09-09 13:54:06.651   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:54:06.652   374   872 D CommandListener: Setting iface cfg
,09-09 13:54:06.653   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-09 13:54:06.653   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:54:06.664   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 13:54:06.664   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:54:06.665   874  1309 E native  : do suspend true
,09-09 13:54:06.693   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 13:54:06.693   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:06.720   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:54:06.788   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:54:06.794  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:54:07.582  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:54:07.633  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:54:07.633  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:54:07.636   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:54:07.653   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:54:07.654   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:54:07.654   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 13:54:07.680   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:07.697   374   872 D CommandListener: Setting iface cfg
,09-09 13:54:07.699   874  1309 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:54:07.704   874  4191 D DhcpClient: Receive thread started
,09-09 13:54:07.706   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:54:07.792   874  1309 E native  : do suspend false
,09-09 13:54:07.814   874  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:54:11.575   874  1918 D WifiService: setWifiEnabled: false pid=3853, uid=10000
,09-09 13:54:11.576   874  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:54:11.605  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:54:11.614   874  1309 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:54:11.615   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:54:11.615   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:11.636   874  1309 E native  : do suspend true
,09-09 13:54:11.649   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:54:11.657   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
09-09 13:54:11.657   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,09-09 13:54:11.667   874  1309 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-09 13:54:11.671   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:54:11.672   874  1309 E native  : do suspend true
,09-09 13:54:11.675   874  4191 D DhcpClient: Receive thread stopped
,09-09 13:54:11.676   874  1311 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 13:54:11.676   874  1311 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 13:54:11.680   374   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:54:11.690   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:54:11.706   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:54:11.710  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:11.710  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:11.710  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:11.710  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:11.710   874  1309 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 13:54:11.710  2155  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:54:11.711  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:11.711  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:11.712  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:11.712  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:11.713  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:11.713  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:11.713  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:11.713  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:16.630   874   891 I ActivityManager: Start proc 4197:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 13:54:16.760  4197  4197 D AdapterServiceConfig: Adding HeadsetService
,09-09 13:54:16.760  4197  4197 D AdapterServiceConfig: Adding A2dpService
09-09 13:54:16.761  4197  4197 D AdapterServiceConfig: Adding HidService
,09-09 13:54:16.761  4197  4197 D AdapterServiceConfig: Adding HealthService
,09-09 13:54:16.761  4197  4197 D AdapterServiceConfig: Adding PanService
,09-09 13:54:16.761  4197  4197 D AdapterServiceConfig: Adding GattService
,09-09 13:54:16.762  4197  4197 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:54:16.777   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48e432f:true
,09-09 13:54:16.779  4197  4197 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:54:16.787  4197  4209 I BluetoothAdapterState: Entering OffState
09-09 13:54:16.787  4197  4197 I bt_bluedroid: init
,09-09 13:54:16.795  4197  4210 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:54:16.795  4197  4210 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:54:16.795  4197  4210 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:54:16.814  4197  4210 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:54:16.816  4197  4197 I bt_bluedroid: get_profile_interface socket
,09-09 13:54:16.818  4197  4197 I bt_bluedroid: get_profile_interface sdp
,09-09 13:54:16.822  4197  4207 I bt_bluedroid: config_hci_snoop_log
,09-09 13:54:16.823   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 13:54:16.823  4197  4213 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:54:16.828  4197  4213 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:54:16.836  4197  4209 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:54:16.836  4197  4209 D BluetoothAdapterProperties: Setting state to 14
09-09 13:54:16.836  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-09 13:54:16.838  4197  4209 D BluetoothBondStateMachine: make
,09-09 13:54:16.845  4197  4214 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:54:16.851  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:16.852  4197  4197 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:54:16.857  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:16.857  4197  4197 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:54:16.858  4197  4197 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:54:16.859  4197  4197 D BtGatt.GattService: start()
09-09 13:54:16.859  4197  4197 I bt_bluedroid: get_profile_interface gatt
,09-09 13:54:16.860  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:16.860  4197  4197 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:54:16.868  4197  4197 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:16.868  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:16.868  4197  4197 V BluetoothAdapterState: isBleTurningOn()=true
09-09 13:54:16.868  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:16.869  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 13:54:16.869  4197  4209 I bt_bluedroid: enable
09-09 13:54:16.869  4197  4210 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 13:54:16.870  4197  4210 I bt_hci  : start_up
,09-09 13:54:16.890  4197  4210 I bt_vendor: alloc value 0xb39d7189
,09-09 13:54:16.891  4197  4210 I bt_vendor: init
09-09 13:54:16.891  4197  4210 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 13:54:16.891  4197  4210 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:54:16.999  4197  4210 D bt_hci  : start_up starting async portion
,09-09 13:54:17.000  4197  4217 I bt_hci  : event_finish_startup
09-09 13:54:17.000  4197  4217 I bt_hci_h4: hal_open
09-09 13:54:17.001  4197  4217 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:54:17.009  4197  4217 I bt_userial_vendor: device fd = 51 open
,09-09 13:54:17.042  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:54:17.074  4197  4217 D bt_hwcfg: Chipset BCM4354A2
,09-09 13:54:17.074  4197  4217 D bt_hwcfg: Target name = [BCM4354A2]
09-09 13:54:17.075  4197  4217 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:54:17.730  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 13:54:17.731  4197  4217 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 13:54:17.732  4197  4217 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:54:17.848  4197  4217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:54:17.849  4197  4217 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:54:17.879  4197  4217 I bt_hwcfg: vendor lib fwcfg completed
,09-09 13:54:17.879  4197  4217 I bt_vendor: firmware callback
,09-09 13:54:17.879  4197  4217 I bt_hci  : firmware_config_callback
,09-09 13:54:17.891  4197  4219 I bt_btu  : btu_task pending for preload complete event
,09-09 13:54:17.892  4197  4219 I bt_btu_task: Bluetooth chip preload is complete
09-09 13:54:17.892  4197  4219 I bt_btu  : btu_task received preload complete event
,09-09 13:54:17.903  4197  4219 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:54:17.904  4197  4219 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:54:17.904  4197  4219 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 13:54:17.904  4197  4219 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 13:54:17.905  4197  4219 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:54:17.905  4197  4219 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:54:17.905  4197  4219 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:54:17.905  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 13:54:17.906  4197  4219 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:54:17.906  4197  4219 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 13:54:17.906  4197  4219 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:54:17.906  4197  4219 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:54:17.907  4197  4219 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 13:54:17.907  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 13:54:17.907  4197  4219 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:54:18.043  4197  4219 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d,
09-09 13:54:18.043  4197  4219 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,09-09 13:54:18.053  4197  4213 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-09 13:54:18.055  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 13:54:18.056  4197  4213 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,09-09 13:54:18.063  4197  4213 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:54:18.067  4197  4213 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:54:18.067  4197  4213 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:54:18.068  4197  4213 D bt_hci  : do_postload posting postload work item
,09-09 13:54:18.068  4197  4217 I bt_hci  : event_postload
,09-09 13:54:18.068  4197  4217 I bt_vendor: sco_config_cb
,09-09 13:54:18.068  4197  4217 I bt_hci  : sco_config_callback postload finished.
,09-09 13:54:18.071  4197  4213 D bt_bte_conf: Device ID record 1 : primary
09-09 13:54:18.071  4197  4213 D bt_bte_conf:   vendorId            = 000f
09-09 13:54:18.071  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:18.072  4197  4213 D bt_bte_conf:   vendorIdSource      = 0001
09-09 13:54:18.072  4197  4213 D bt_bte_conf:   product             = 1200
09-09 13:54:18.072  4197  4213 D bt_bte_conf:   version             = 1436
,09-09 13:54:18.072  4197  4213 D bt_bte_conf:   clientExecutableURL = 
09-09 13:54:18.072  4197  4213 D bt_bte_conf:   serviceDescription  = 
09-09 13:54:18.073  4197  4213 D bt_bte_conf:   documentationURL    = 
09-09 13:54:18.073  4197  4213 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:54:18.073  4197  4210 D bt_stack_manager: event_start_up_stack finished
09-09 13:54:18.074  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 13:54:18.074  4197  4217 I bt_vendor: low_power_mode_cb
09-09 13:54:18.075  4197  4209 D BluetoothAdapterProperties: Setting state to 15
,09-09 13:54:18.075  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 13:54:18.075  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:18.078  4197  4209 I BluetoothAdapterState: Entering BleOnState
09-09 13:54:18.080  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:18.082  4197  4209 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 13:54:18.082  4197  4209 D BluetoothAdapterProperties: Setting state to 11
09-09 13:54:18.084  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 13:54:18.089  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:18.091  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:18.092  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:54:18.093  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:18.094  4197  4197 D HeadsetService: Received start request. Starting profile...
,09-09 13:54:18.097  4197  4197 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 13:54:18.097  4197  4197 D HeadsetStateMachine: make
,09-09 13:54:18.100  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:18.104  4197  4197 D HeadsetStateMachine: max_hf_connections = 1
,09-09 13:54:18.105  4197  4197 I bt_bluedroid: get_profile_interface handsfree
,09-09 13:54:18.105  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:54:18.105  4197  4213 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 13:54:18.112  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:18.112  4197  4197 D A2dpService: Received start request. Starting profile...
,09-09 13:54:18.113  4197  4197 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:54:18.113  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:54:18.113  4197  4197 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:54:18.119  4197  4197 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:54:18.119  4197  4197 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:54:18.120  4197  4197 D A2dpStateMachine: make
,09-09 13:54:18.121  4197  4197 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:54:18.122  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 13:54:18.126  4197  4230 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:54:18.127  4197  4197 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 13:54:18.127  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:18.128  4197  4197 D HidService: Received start request. Starting profile...
09-09 13:54:18.128  4197  4197 I bt_bluedroid: get_profile_interface hidhost
09-09 13:54:18.128  4197  4213 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
09-09 13:54:18.128  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 13:54:18.129  4197  4197 D HidService: setHidService(): set to: null
09-09 13:54:18.129  4197  4197 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 13:54:18.130  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:54:18.130  4197  4197 D HealthService: Received start request. Starting profile...
,09-09 13:54:18.133  4197  4197 I bt_bluedroid: get_profile_interface health
09-09 13:54:18.133  4197  4197 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 13:54:18.134  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:54:18.134  4197  4197 D PanService: Received start request. Starting profile...
,09-09 13:54:18.134  4197  4197 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:54:18.135  4197  4197 I bt_bluedroid: get_profile_interface pan
,09-09 13:54:18.135  4197  4213 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:54:18.141  4197  4197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:18.142  4197  4197 D BluetoothMapService: Received start request. Starting profile...
,09-09 13:54:18.142  4197  4197 D BluetoothMapService: start()
,09-09 13:54:18.147  4197  4197 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 13:54:18.149  4197  4197 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-09 13:54:18.149  4197  4197 D BluetoothMapAppObserver: createReceiver()
,09-09 13:54:18.151  4197  4197 D BluetoothMapAppObserver: initObservers()
,09-09 13:54:18.151  4197  4197 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:54:18.169  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:54:18.169  4197  4197 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:54:18.169  4197  4228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:54:18.169  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:18.170  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:18.172  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:54:18.173  4197  4197 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:18.173  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:18.173  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:18.173  4197  4197 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:18.174  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:18.175  4197  4197 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:18.175  4197  4197 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:18.175  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:18.175  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:18.175  4197  4197 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:18.176  4197  4197 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:18.176  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:18.176  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:18.177  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 13:54:18.177  4197  4209 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:54:18.177  4197  4209 D BluetoothAdapterProperties: State =  11
09-09 13:54:18.179  4197  4213 D BluetoothAdapterProperties: Scan Mode:21
,09-09 13:54:18.179  4197  4209 D BluetoothAdapterProperties: Setting state to 12
09-09 13:54:18.179  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:54:18.179  4197  4213 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:54:18.179  4197  4209 I BluetoothAdapterState: Entering OnState
,09-09 13:54:18.180  1366  1380 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:54:18.182   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:18.182  1366  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:54:18.183  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:54:18.183  1366  1366 D PanProfile: Bluetooth service connected
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:18.184  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:18.185  1366  1366 D BluetoothInputDevice: Proxy object connected
09-09 13:54:18.185  1366  1366 D HidProfile: Bluetooth service connected
,09-09 13:54:18.185  1366  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:54:18.187  4197  4197 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:54:18.188  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:18.188  4197  4197 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 13:54:18.188  3960  4042 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:54:18.190  4197  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:54:18.193  4197  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:18.193  1366  1388 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:18.194  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:18.195  4197  4197 D ObexServerSockets: Succeed to create listening sockets 
09-09 13:54:18.195  4197  4197 D ObexServerSockets0: startAccept()
,09-09 13:54:18.196  4197  4197 D ObexServerSockets0: prepareForNewConnect()
,09-09 13:54:18.198  1938  1948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:18.198  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:18.198  4197  4197 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 13:54:18.198  4197  4197 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-09 13:54:18.200  4197  4236 D ObexServerSockets0: Accepting socket connection...
09-09 13:54:18.200  1366  1366 D BluetoothA2dp: Proxy object connected
09-09 13:54:18.201  4197  4235 D ObexServerSockets0: Accepting socket connection...
09-09 13:54:18.202   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:18.202   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:54:18.203   874   874 D BluetoothA2dp: Proxy object connected
,09-09 13:54:18.205  1366  1366 D BluetoothMap: Proxy object connected
,09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:18.205  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:18.205  1366  1366 D MapProfile: Bluetooth service connected
09-09 13:54:18.205  1366  1366 D BluetoothMap: getConnectedDevices()
09-09 13:54:18.205  3960  3972 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:54:18.208  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:18.208  1366  1380 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 13:54:18.211   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:18.212  3960  4042 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:18.213  1366  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:18.213  3960  3970 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:54:18.216  3960  4042 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 13:54:18.217  3960  3960 D BluetoothInputDevice: Proxy object connected
,09-09 13:54:18.217  3960  3960 D HidProfile: Bluetooth service connected
09-09 13:54:18.218  3960  3970 D BluetoothPan: onBluetoothStateChange on: true
,09-09 13:54:18.221   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 13:54:18.222  4197  4197 D BluetoothMapService: onReceive
09-09 13:54:18.222  4197  4197 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:54:18.223  4197  4197 D BluetoothMapService: STATE_ON
,09-09 13:54:18.225  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:18.225  3960  3960 D BluetoothA2dp: Proxy object connected
,09-09 13:54:18.227  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:18.228  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:18.228  3960  3960 D BluetoothMap: Proxy object connected
,09-09 13:54:18.229  3960  3960 D MapProfile: Bluetooth service connected
09-09 13:54:18.229  3960  3960 D BluetoothMap: getConnectedDevices()
,09-09 13:54:18.231  3960  3960 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:54:18.232  3960  3960 D PanProfile: Bluetooth service connected
,09-09 13:54:18.237  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:18.243  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:54:18.244  4197  4197 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 13:54:18.245  4197  4197 D ObexServerSockets0: prepareForNewConnect()
09-09 13:54:18.248  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:54:18.259  3960  3960 D BluetoothPbap: Proxy object connected
,09-09 13:54:18.259  3960  3960 D PbapServerProfile: Bluetooth service connected
09-09 13:54:18.259  1366  1366 D BluetoothPbap: Proxy object connected
09-09 13:54:18.259  1366  1366 D PbapServerProfile: Bluetooth service connected
,09-09 13:54:18.270  4197  4240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:18.299   874   874 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.300  1938  2088 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.302  1366  1388 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.302   874   891 D BluetoothHeadset: Proxy object connected
09-09 13:54:18.302  1366  1366 D HeadsetProfile: Bluetooth service connected
09-09 13:54:18.302   874   874 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.302   874   874 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.303  3960  3972 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.303  3960  3960 D HeadsetProfile: Bluetooth service connected
,09-09 13:54:18.311   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.312  3960  3970 D BluetoothHeadset: Proxy object connected
,09-09 13:54:18.313  3960  3960 D HeadsetProfile: Bluetooth service connected
09-09 13:54:18.314  1366  1379 D BluetoothHeadset: Proxy object connected
09-09 13:54:18.314  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-09 13:54:18.317  4197  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:18.319  4197  4244 I BtOppRfcommListener: Accept thread started.
,09-09 13:54:20.278  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:20.307  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:20.310  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:20.353  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:54:20.353  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:54:20.353  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:20.354  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:20.386  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:54:20.387  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:54:20.387  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 13:54:21.593  4197  4209 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 13:54:21.594  4197  4209 D BluetoothAdapterProperties: Setting state to 13
09-09 13:54:21.594  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 13:54:21.596  4197  4209 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 13:54:21.599  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:21.604  4197  4213 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:54:21.604  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 13:54:21.613  4197  4197 D BluetoothMapService: onReceive
09-09 13:54:21.613  4197  4197 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:54:21.614  4197  4197 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:54:21.614  4197  4197 D BluetoothMapService: MAP Service closeService in
,09-09 13:54:21.615  4197  4197 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 13:54:21.615  4197  4197 D ObexServerSockets0: shutdown(block = true)
09-09 13:54:21.617  4197  4197 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:54:21.618  4197  4197 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:54:21.618  4197  4236 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:54:21.619  4197  4235 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-09 13:54:21.620  4197  4221 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 13:54:21.620  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:21.621  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:21.622  4197  4197 I BtOppRfcommListener: stopping Accept Thread
09-09 13:54:21.623  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:21.623  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:21.623  4197  4244 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:54:21.624  4197  4244 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:54:21.627  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:21.627  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:21.627  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:21.628  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:21.628  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:21.629  4197  4197 D HeadsetService: Received stop request...Stopping profile...
09-09 13:54:21.630  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:21.630  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:21.631  3853  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:54:21.631  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:54:21.633  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:21.634  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.636  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.636   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:21.637  1938  1949 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:21.637  1366  1388 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:21.638   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 13:54:21.638   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:21.638  1366  1366 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:54:21.638  3960  3972 D BluetoothHeadset: Proxy object disconnected
09-09 13:54:21.639  4197  4197 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:21.639  4197  4197 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:54:21.639  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:21.639  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:21.641  4197  4197 D A2dpService: Received stop request...Stopping profile...
09-09 13:54:21.641  4197  4230 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:54:21.643   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 13:54:21.644  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-09 13:54:21.645  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 13:54:21.645  3960  3960 D DockEventReceiver: finishStartingService: stopping service
09-09 13:54:21.645  4197  4197 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:54:21.645  4197  4197 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:54:21.645  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-09 13:54:21.646  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:21.646  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:21.646  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 13:54:21.646  4197  4213 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 13:54:21.647  4197  4197 D HidService: Received stop request...Stopping profile...
09-09 13:54:21.647  4197  4197 D HidService: Stopping Bluetooth HidService
09-09 13:54:21.648  4197  4197 D HealthService: Received stop request...Stopping profile...
,09-09 13:54:21.649  3960  3960 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:54:21.650  3960  3960 D BluetoothA2dp: Proxy object disconnected
,09-09 13:54:21.651  3960  3960 D BluetoothInputDevice: Proxy object disconnected
09-09 13:54:21.651  3960  3960 D HidProfile: Bluetooth service disconnected
,09-09 13:54:21.652  4197  4197 D PanService: Received stop request...Stopping profile...
,09-09 13:54:21.653  3960  3960 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 13:54:21.653  3960  3960 D PanProfile: Bluetooth service disconnected
,09-09 13:54:21.653  1366  1366 D BluetoothInputDevice: Proxy object disconnected
09-09 13:54:21.653  1366  1366 D HidProfile: Bluetooth service disconnected
,09-09 13:54:21.653  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:54:21.654  1366  1366 D PanProfile: Bluetooth service disconnected
09-09 13:54:21.655  4197  4197 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:54:21.655  4197  4197 D BluetoothMapService: stop()
09-09 13:54:21.656  3960  3960 D BluetoothPbap: Proxy object disconnected
09-09 13:54:21.656  3960  3960 D PbapServerProfile: Bluetooth service disconnected
,09-09 13:54:21.656  4197  4197 D BluetoothMapAppObserver: deinitObservers()
09-09 13:54:21.656  4197  4197 D BluetoothMapAppObserver: removeReceiver()
09-09 13:54:21.656  1366  1366 D BluetoothPbap: Proxy object disconnected
09-09 13:54:21.657  1366  1366 D PbapServerProfile: Bluetooth service disconnected
09-09 13:54:21.658  1366  1366 D BluetoothMap: Proxy object disconnected
,09-09 13:54:21.658  1366  1366 D MapProfile: Bluetooth service disconnected
09-09 13:54:21.658  4197  4197 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:54:21.658  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:21.658  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:21.658  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:21.659  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:21.659  4197  4197 V BluetoothAdapterState: isTurningOff()=true
,09-09 13:54:21.660  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:21.660  4197  4219 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:21.660  4197  4219 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:54:21.660  4197  4219 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:54:21.660  4197  4219 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:54:21.660  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 13:54:21.660  4197  4197 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:54:21.660  4197  4197 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:54:21.660  4197  4213 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:21.660  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:21.661  4197  4197 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:54:21.659  3960  3960 D BluetoothMap: Proxy object disconnected
,09-09 13:54:21.661  3960  3960 D MapProfile: Bluetooth service disconnected
09-09 13:54:21.661  4197  4197 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:54:21.661  4197  4213 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:54:21.662  4197  4197 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:21.662  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:21.662  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:21.662  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:21.663  4197  4197 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:54:21.663  4197  4197 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:54:21.664  4197  4197 D BluetoothMapService: MAP Service closeService in
09-09 13:54:21.664  4197  4197 V BluetoothAdapterState: isTurningOff()=true
09-09 13:54:21.664  4197  4197 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:21.664  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:21.664  4197  4197 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:21.664  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 13:54:21.664  4197  4197 D BluetoothMapService: cleanup()
09-09 13:54:21.664  4197  4209 D BluetoothAdapterProperties: Setting state to 15
09-09 13:54:21.664  4197  4197 D BluetoothMapService: MAP Service closeService in
09-09 13:54:21.664  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:54:21.665  4197  4209 I BluetoothAdapterState: Entering BleOnState
09-09 13:54:21.665  1366  1380 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:54:21.666   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:21.666  1366  1388 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:54:21.669  1366  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:54:21.670  3960  3970 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:54:21.671  1366  2075 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:54:21.671  1938  1948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:54:21.671   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:21.671   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:54:21.672  3960  4042 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:54:21.672  1366  1380 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:54:21.673   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:54:21.673  3960  3972 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:21.673  1366  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 13:54:21.673  3960  3970 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:54:21.674  3960  4042 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:54:21.675  3960  3972 D BluetoothPan: onBluetoothStateChange on: false
,09-09 13:54:21.676  4197  4209 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 13:54:21.676  4197  4209 D BluetoothAdapterProperties: Setting state to 16
,09-09 13:54:21.676  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 13:54:21.676  4197  4209 D BluetoothAdapterProperties: onBleDisable
09-09 13:54:21.677  4197  4210 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 13:54:21.677  4197  4209 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:54:21.678  4197  4219 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 13:54:21.678  4197  4219 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:54:21.678  4197  4213 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:54:21.681  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.682  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:21.684  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:21.684  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:21.686  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.687  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.688  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:21.688  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:54:21.693  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:54:21.886  4197  4213 I bt_hci  : shut_down
,09-09 13:54:21.898  4197  4217 I bt_vendor: low_power_mode_cb
,09-09 13:54:21.899  4197  4217 D bt_hwcfg: hw_epilog_process
,09-09 13:54:21.922  4197  4217 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 13:54:21.922  4197  4217 I bt_vendor: epilog_cb
,09-09 13:54:21.923  4197  4217 I bt_hci  : epilog_finished_callback
,09-09 13:54:21.930  4197  4213 I bt_hci_h4: hal_close
,09-09 13:54:21.932  4197  4213 I bt_userial_vendor: device fd = 51 close
,09-09 13:54:22.048  4197  4210 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:54:22.049  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 13:54:22.054  4197  4209 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 13:54:22.055  4197  4197 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:54:22.057  4197  4197 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 13:54:22.057  4197  4197 D BtGatt.GattService: stop()
,09-09 13:54:22.058  4197  4197 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 13:54:22.063  4197  4197 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:54:22.063  4197  4197 V BluetoothAdapterState: isTurningOn()=false
,09-09 13:54:22.064  4197  4197 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:22.064  4197  4197 V BluetoothAdapterState: isBleTurningOff()=true
09-09 13:54:22.065  4197  4209 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 13:54:22.066  4197  4209 D BluetoothAdapterProperties: Setting state to 10
,09-09 13:54:22.066  4197  4209 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 13:54:22.068  4197  4209 I BluetoothAdapterState: Entering OffState
09-09 13:54:22.070   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 13:54:22.096  4197  4197 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-09 13:54:22.096  4197  4197 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 13:54:22.097  4197  4210 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 13:54:22.107  4197  4210 D bt_stack_manager: event_clean_up_stack finished.
,09-09 13:54:22.109  4197  4197 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 13:54:22.120  4197  4197 I art     : System.exit called, status: 0
09-09 13:54:22.120  4197  4197 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 13:54:22.179   874  3237 I ActivityManager: Process com.android.bluetooth (pid 4197) has died
,09-09 13:54:26.590  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:54:26.590  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:26.595  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:26.595  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10ffded removed from the list
,09-09 13:54:26.596  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:26.596  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:26.596  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:26.599  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:54:26.600  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c25ceb3 added. We now have 4 listener(s)
,09-09 13:54:26.600  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:54:26.602  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:26.602  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c25ceb3 removed from the list
,09-09 13:54:26.602  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:26.602  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:54:26.603  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:26.605  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:54:26.605  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@285bc70 added. We now have 4 listener(s)
,09-09 13:54:26.606  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:54:31.620  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:31.666   874   891 I ActivityManager: Start proc 4255:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 13:54:31.805  4255  4255 D AdapterServiceConfig: Adding HeadsetService
,09-09 13:54:31.806  4255  4255 D AdapterServiceConfig: Adding A2dpService
09-09 13:54:31.806  4255  4255 D AdapterServiceConfig: Adding HidService
09-09 13:54:31.807  4255  4255 D AdapterServiceConfig: Adding HealthService
,09-09 13:54:31.808  4255  4255 D AdapterServiceConfig: Adding PanService
09-09 13:54:31.808  4255  4255 D AdapterServiceConfig: Adding GattService
,09-09 13:54:31.809  4255  4255 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 13:54:31.829   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5bbb07e:true
09-09 13:54:31.829  4255  4255 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 13:54:31.833  4255  4255 I bt_bluedroid: init
,09-09 13:54:31.834  4255  4267 I BluetoothAdapterState: Entering OffState
,09-09 13:54:31.843  4255  4268 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 13:54:31.843  4255  4268 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:54:31.843  4255  4268 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 13:54:31.844  4255  4268 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:54:31.847  4255  4255 I bt_bluedroid: get_profile_interface socket
,09-09 13:54:31.849  4255  4255 I bt_bluedroid: get_profile_interface sdp
,09-09 13:54:31.856  4255  4271 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:54:31.858  4255  4266 I bt_bluedroid: config_hci_snoop_log
,09-09 13:54:31.859   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 13:54:31.860  4255  4271 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:54:31.874  4255  4267 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 13:54:31.874  4255  4267 D BluetoothAdapterProperties: Setting state to 14
,09-09 13:54:31.875  4255  4267 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 13:54:31.879  4255  4267 D BluetoothBondStateMachine: make
,09-09 13:54:31.885  4255  4272 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:54:31.893  4255  4267 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:31.894  4255  4255 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 13:54:31.898  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:54:31.899  4255  4255 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:54:31.899  4255  4255 D BtGatt.GattService: Received start request. Starting profile...
,09-09 13:54:31.900  4255  4255 D BtGatt.GattService: start()
09-09 13:54:31.900  4255  4255 I bt_bluedroid: get_profile_interface gatt
,09-09 13:54:31.901  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:31.901  4255  4255 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:54:31.912  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:31.912  4255  4255 V BluetoothAdapterState: isTurningOn()=false
09-09 13:54:31.913  4255  4255 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 13:54:31.913  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:31.914  4255  4267 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 13:54:31.914  4255  4267 I bt_bluedroid: enable
,09-09 13:54:31.915  4255  4268 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 13:54:31.916  4255  4268 I bt_hci  : start_up
,09-09 13:54:31.939  4255  4268 I bt_vendor: alloc value 0xb39d7189
09-09 13:54:31.939  4255  4268 I bt_vendor: init
,09-09 13:54:31.939  4255  4268 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 13:54:31.940  4255  4268 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 13:54:32.047  4255  4268 D bt_hci  : start_up starting async portion
,09-09 13:54:32.048  4255  4275 I bt_hci  : event_finish_startup
09-09 13:54:32.049  4255  4275 I bt_hci_h4: hal_open
,09-09 13:54:32.049  4255  4275 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 13:54:32.058  4255  4275 I bt_userial_vendor: device fd = 51 open
,09-09 13:54:32.090  4255  4275 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:54:32.122  4255  4275 D bt_hwcfg: Chipset BCM4354A2
,09-09 13:54:32.122  4255  4275 D bt_hwcfg: Target name = [BCM4354A2]
09-09 13:54:32.123  4255  4275 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 13:54:32.956  4255  4275 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 13:54:32.958  4255  4275 D bt_hwcfg: Settlement delay -- 100 ms
09-09 13:54:32.958  4255  4275 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 13:54:33.076  4255  4275 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 13:54:33.078  4255  4275 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 13:54:33.104  4255  4275 I bt_hwcfg: vendor lib fwcfg completed
,09-09 13:54:33.105  4255  4275 I bt_vendor: firmware callback
09-09 13:54:33.105  4255  4275 I bt_hci  : firmware_config_callback
,09-09 13:54:33.117  4255  4277 I bt_btu  : btu_task pending for preload complete event
09-09 13:54:33.118  4255  4277 I bt_btu_task: Bluetooth chip preload is complete
,09-09 13:54:33.119  4255  4277 I bt_btu  : btu_task received preload complete event
,09-09 13:54:33.129  4255  4277 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 13:54:33.129  4255  4277 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:54:33.129  4255  4277 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 13:54:33.130  4255  4277 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:54:33.130  4255  4277 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 13:54:33.130  4255  4277 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:54:33.130  4255  4277 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:54:33.131  4255  4277 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 13:54:33.131  4255  4277 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:54:33.131  4255  4277 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 13:54:33.131  4255  4277 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 13:54:33.132  4255  4277 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 13:54:33.132  4255  4277 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:54:33.132  4255  4277 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-09 13:54:33.132  4255  4277 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 13:54:33.280  4255  4277 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3954d9d
,09-09 13:54:33.281  4255  4277 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3954d9d 
,09-09 13:54:33.294  4255  4271 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 13:54:33.295  4255  4271 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 13:54:33.296  4255  4271 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 13:54:33.300  4255  4271 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 13:54:33.304  4255  4271 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:54:33.305  4255  4271 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:54:33.306  4255  4271 D bt_hci  : do_postload posting postload work item
09-09 13:54:33.306  4255  4275 I bt_hci  : event_postload
09-09 13:54:33.306  4255  4275 I bt_vendor: sco_config_cb
,09-09 13:54:33.306  4255  4275 I bt_hci  : sco_config_callback postload finished.,
09-09 13:54:33.311  4255  4271 D bt_bte_conf: Device ID record 1 : primary
09-09 13:54:33.311  4255  4271 D bt_bte_conf:   vendorId            = 000f
09-09 13:54:33.311  4255  4271 D bt_bte_conf:   vendorIdSource      = 0001
09-09 13:54:33.312  4255  4271 D bt_bte_conf:   product             = 1200
,09-09 13:54:33.312  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:33.312  4255  4271 D bt_bte_conf:   version             = 1436
,09-09 13:54:33.312  4255  4271 D bt_bte_conf:   clientExecutableURL = 
09-09 13:54:33.312  4255  4271 D bt_bte_conf:   serviceDescription  = 
09-09 13:54:33.313  4255  4271 D bt_bte_conf:   documentationURL    = 
,09-09 13:54:33.313  4255  4271 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:54:33.314  4255  4268 D bt_stack_manager: event_start_up_stack finished
09-09 13:54:33.316  4255  4267 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 13:54:33.316  4255  4267 D BluetoothAdapterProperties: Setting state to 15
09-09 13:54:33.316  4255  4267 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 13:54:33.317  4255  4267 I BluetoothAdapterState: Entering BleOnState
09-09 13:54:33.317  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:33.322  4255  4275 I bt_vendor: low_power_mode_cb
09-09 13:54:33.325  4255  4267 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-09 13:54:33.325  4255  4267 D BluetoothAdapterProperties: Setting state to 11
09-09 13:54:33.326  4255  4267 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 13:54:33.331  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
09-09 13:54:33.332  4255  4255 D HeadsetService: Received start request. Starting profile...
,09-09 13:54:33.337  4255  4255 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 13:54:33.337  4255  4255 D HeadsetStateMachine: make
,09-09 13:54:33.339  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:33.341  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:33.354  4255  4267 I BluetoothAdapterState: Entering PendingCommandState
,09-09 13:54:33.354  4255  4255 D HeadsetStateMachine: max_hf_connections = 1
09-09 13:54:33.354  4255  4255 I bt_bluedroid: get_profile_interface handsfree
09-09 13:54:33.354  4255  4271 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 13:54:33.355  4255  4271 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 13:54:33.358  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:33.359  4255  4255 D A2dpService: Received start request. Starting profile...
,09-09 13:54:33.360  4255  4255 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 13:54:33.360  4255  4255 I bt_bluedroid: get_profile_interface avrcp
,09-09 13:54:33.367  4255  4255 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 13:54:33.367  4255  4255 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-09 13:54:33.367  4255  4255 D A2dpStateMachine: make
,09-09 13:54:33.368  4255  4255 I bt_bluedroid: get_profile_interface a2dp
,09-09 13:54:33.369  4255  4271 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 13:54:33.371  4255  4286 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:54:33.372  4255  4255 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 13:54:33.373  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:33.373  4255  4255 D HidService: Received start request. Starting profile...
09-09 13:54:33.373  4255  4255 I bt_bluedroid: get_profile_interface hidhost
09-09 13:54:33.373  4255  4271 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39363e5
,09-09 13:54:33.373  4255  4271 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 13:54:33.374  4255  4255 D HidService: setHidService(): set to: null
09-09 13:54:33.374  4255  4255 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 13:54:33.375  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:33.376  4255  4255 D HealthService: Received start request. Starting profile...
,09-09 13:54:33.377  4255  4255 I bt_bluedroid: get_profile_interface health
,09-09 13:54:33.379  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:54:33.380  4255  4255 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 13:54:33.381  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:33.381  4255  4255 D PanService: Received start request. Starting profile...
09-09 13:54:33.381  4255  4255 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 13:54:33.381  4255  4255 I bt_bluedroid: get_profile_interface pan
09-09 13:54:33.382  4255  4271 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:54:33.387  4255  4255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:33.388  4255  4255 D BluetoothMapService: Received start request. Starting profile...
09-09 13:54:33.388  4255  4255 D BluetoothMapService: start()
,09-09 13:54:33.390  4255  4255 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 13:54:33.391  4255  4255 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 13:54:33.391  4255  4255 D BluetoothMapAppObserver: createReceiver()
09-09 13:54:33.392  4255  4255 D BluetoothMapAppObserver: initObservers()
09-09 13:54:33.392  4255  4255 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 13:54:33.397  4255  4255 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:54:33.397  4255  4255 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:33.397  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:33.397  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:33.397  4255  4283 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:33.399  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isTurningOn()=true
,09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:33.400  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 13:54:33.401  4255  4255 V BluetoothAdapterState: isTurningOff()=false
09-09 13:54:33.401  4255  4255 V BluetoothAdapterState: isTurningOn()=true
09-09 13:54:33.401  4255  4255 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:54:33.401  4255  4255 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:54:33.401  4255  4267 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 13:54:33.402  4255  4267 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:54:33.402  4255  4267 D BluetoothAdapterProperties: State =  11
,09-09 13:54:33.404  4255  4271 D BluetoothAdapterProperties: Scan Mode:21
,09-09 13:54:33.404  4255  4267 D BluetoothAdapterProperties: Setting state to 12
09-09 13:54:33.404  4255  4271 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 13:54:33.404  4255  4267 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:54:33.405  4255  4267 I BluetoothAdapterState: Entering OnState,
09-09 13:54:33.405  1366  1379 D BluetoothPan: onBluetoothStateChange on: true
09-09 13:54:33.406   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:33.407  1366  2075 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:33.407  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:33.409  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:33.409  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:54:33.410  1366  1366 D PanProfile: Bluetooth service connected
09-09 13:54:33.410  1366  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:54:33.412  3960  4042 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:33.412  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:33.413  1366  1366 D BluetoothInputDevice: Proxy object connected
,09-09 13:54:33.413  1366  1366 D HidProfile: Bluetooth service connected
,09-09 13:54:33.414  1366  1388 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:54:33.414  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:33.416  1366  1366 D BluetoothA2dp: Proxy object connected
,09-09 13:54:33.416  1938  1948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:33.416   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:33.417   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 13:54:33.417  4255  4255 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 13:54:33.417  1366  1366 D BluetoothMap: Proxy object connected
09-09 13:54:33.417  1366  1366 D MapProfile: Bluetooth service connected
09-09 13:54:33.417  1366  1366 D BluetoothMap: getConnectedDevices()
09-09 13:54:33.417  3960  3972 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 13:54:33.418  4255  4255 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 13:54:33.418   874   874 D BluetoothA2dp: Proxy object connected
,09-09 13:54:33.419  4255  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:33.420  3960  3960 D BluetoothInputDevice: Proxy object connected
09-09 13:54:33.420  1366  2075 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:54:33.420  3960  3960 D HidProfile: Bluetooth service connected
09-09 13:54:33.421  4255  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:54:33.421   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:33.421  3960  4042 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 13:54:33.422  4255  4255 D ObexServerSockets: Succeed to create listening sockets 
,09-09 13:54:33.422  4255  4255 D ObexServerSockets0: startAccept()
09-09 13:54:33.422  4255  4255 D ObexServerSockets0: prepareForNewConnect()
09-09 13:54:33.422  1366  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 13:54:33.423  3960  3970 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:54:33.424  4255  4255 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 13:54:33.424  4255  4255 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 13:54:33.424  4255  4292 D ObexServerSockets0: Accepting socket connection...
09-09 13:54:33.424  4255  4293 D ObexServerSockets0: Accepting socket connection...
09-09 13:54:33.425  3960  4042 D BluetoothMap: onBluetoothStateChange: up=true
09-09 13:54:33.427  3960  3970 D BluetoothPan: onBluetoothStateChange on: true
,09-09 13:54:33.430  3960  3960 D BluetoothA2dp: Proxy object connected
09-09 13:54:33.430   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 13:54:33.431  4255  4255 D BluetoothMapService: onReceive
,09-09 13:54:33.431  4255  4255 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:54:33.431  4255  4255 D BluetoothMapService: STATE_ON
09-09 13:54:33.431  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:33.432  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:33.435  3960  3960 D BluetoothMap: Proxy object connected
09-09 13:54:33.435  3960  3960 D MapProfile: Bluetooth service connected
09-09 13:54:33.435  3960  3960 D BluetoothMap: getConnectedDevices()
09-09 13:54:33.437  3960  3960 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:54:33.437  3960  3960 D PanProfile: Bluetooth service connected
,09-09 13:54:33.441  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:54:33.447  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:54:33.448  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:54:33.457  1366  1366 D BluetoothPbap: Proxy object connected
,09-09 13:54:33.457  1366  1366 D PbapServerProfile: Bluetooth service connected
09-09 13:54:33.457  3960  3960 D BluetoothPbap: Proxy object connected
09-09 13:54:33.457  3960  3960 D PbapServerProfile: Bluetooth service connected
,09-09 13:54:33.462  4255  4255 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 13:54:33.462  4255  4255 D ObexServerSockets0: prepareForNewConnect()
,09-09 13:54:33.464  4255  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:33.479  4255  4302 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:54:33.480  4255  4302 I BtOppRfcommListener: Accept thread started.
,09-09 13:54:33.508   874   874 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.508  1938  2088 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.509  1366  1388 D BluetoothHeadset: Proxy object connected
09-09 13:54:33.509  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-09 13:54:33.509   874   874 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.509   874   874 D BluetoothHeadset: Proxy object connected
09-09 13:54:33.510  3960  3972 D BluetoothHeadset: Proxy object connected
09-09 13:54:33.510  3960  3960 D HeadsetProfile: Bluetooth service connected
,09-09 13:54:33.517  1938  1949 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.517   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.521   874   891 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.522  3960  3970 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.523  3960  3960 D HeadsetProfile: Bluetooth service connected
09-09 13:54:33.523  1366  1379 D BluetoothHeadset: Proxy object connected
,09-09 13:54:33.528  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:36.640  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:36.647  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:36.648  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:36.648  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@285bc70 removed from the list
,09-09 13:54:36.648  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:36.649  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:36.649  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:36.652  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:54:36.652  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb8be9 added. We now have 4 listener(s)
09-09 13:54:36.652  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:54:36.656   874  1987 D WifiService: setWifiEnabled: false pid=3853, uid=10000
09-09 13:54:36.656   874  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:54:40.627  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:40.637  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:40.640  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:40.685  1515  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:54:40.686  1515  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:54:40.686  1515  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:54:40.686  1515  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:40.728  3593  3593 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:54:40.729  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:54:40.730  3593  3593 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 13:54:41.669  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:41.670   874  1373 D WifiService: setWifiEnabled: true pid=3853, uid=10000
09-09 13:54:41.670   874  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:54:41.687   874  1309 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:41.707  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:54:41.713  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:41.715   874  1309 D WifiConfigStore: loaded 0 passpoint configs
09-09 13:54:41.716   874  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 13:54:41.717   874  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:54:41.718   874  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:54:41.718   874  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 13:54:41.718   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:54:41.719   874  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:54:41.722  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:54:41.730  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:54:41.741   374   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:54:41.741   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 13:54:41.743   374   872 D CommandListener: Setting iface cfg
,09-09 13:54:41.794   874  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '143 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 143 Failed to set address (No such device)'
,09-09 13:54:41.794   874  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:54:41.800   874  1309 E native  : do suspend true
,09-09 13:54:41.831   874  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 13:54:41.831   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:54:41.832   874  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:54:43.125   874  1309 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 13:54:43.271   874  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.50 rxSuccessRate=7.56 delta 1000 -> 1000
,09-09 13:54:43.273   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 13:54:43.273   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:43.286   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:54:43.336   874  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:54:43.337  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:54:43.778  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:54:43.823  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:54:43.824  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:54:43.832   874  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:54:43.848   874  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:54:43.848   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-09 13:54:43.848   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:43.877   874  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:54:43.897   374   872 D CommandListener: Setting iface cfg
09-09 13:54:43.898   874  1309 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 13:54:43.914   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 13:54:43.939   874  4312 D DhcpClient: Receive thread started
,09-09 13:54:44.041   874  1309 E native  : do suspend false
,09-09 13:54:44.072   874  1888 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:54:44.085   874  4312 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
,09-09 13:54:44.087   874  1888 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 13:54:44.091   874  1888 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:54:44.109   874  4312 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-09 13:54:44.111   874  1888 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 13:54:44.117   374   872 D CommandListener: Setting iface cfg
,09-09 13:54:44.129   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:54:44.131   874  1888 D DhcpClient: Scheduling renewal in 86399s
09-09 13:54:44.132   874  1309 E native  : do suspend true
,09-09 13:54:44.158   874  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-09 13:54:44.161   874  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:54:44.162   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:54:44.166   874  1311 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 13:54:44.170   874  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:54:44.236   874  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 13:54:44.236   874  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 13:54:44.240   874  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 13:54:44.243   874  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 13:54:44.250   874  1311 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 13:54:44.282   874  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 13:54:44.294   874  1311 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 13:54:44.295   874  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 13:54:44.295   874  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 13:54:44.295   874  1311 D ConnectivityService:    accepting network in place of null
,09-09 13:54:44.295   874  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:54:44.298   874  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 13:54:44.298   874  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 13:54:44.315   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=204553, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:54:44.363   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:54:44.396   374   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:54:44.406   874  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 13:54:44.407   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:54:44.407   874  4310 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-09 13:54:44.418   874  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-09 13:54:44.420   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:44.438  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:54:44.441  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:44.447  3853  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:54:44.448  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:54:44.450  3853  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:44.455  1738  1738 D SystemUpdateService: onCreate
,09-09 13:54:44.465  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:54:44.484  1738  4323 I SystemUpdateService: active receiver: enabled
,09-09 13:54:44.488  1738  4323 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:54:44.488   874  4310 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:54:44 GMT], X-Android-Received-Millis=[1473422084488], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473422084454]}
09-09 13:54:44.489  1738  4323 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 13:54:44.490  1738  4323 I SystemUpdateService: now status is 0 (complete)
09-09 13:54:44.490  1738  4323 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:54:44.490  1738  4323 I SystemUpdateService: file has been verified
,09-09 13:54:44.490  1738  4323 I SystemUpdateService: OTA package size = 12249756
09-09 13:54:44.493   874  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:54:44.493   874  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 13:54:44.493   874  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 13:54:44.494   874  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:54:44.499  1738  4323 I SystemUpdateService: showing system update notification
,09-09 13:54:44.515  3805  4329 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:54:44.516  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:54:44.605  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:54:44.621  1738  1738 D SystemUpdateService: onDestroy
,09-09 13:54:44.626  1738  2430 I iu.UploadsManager: num queued entries: 0
,09-09 13:54:44.634  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:54:44.656  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:54:44.666  4062  4062 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:54:44.673  1738  4332 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 13:54:44.673  1738  4332 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 13:54:44.680  1738  4332 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:54:44.696  4062  4062 D SprintDMHelper: simOperator: 
,09-09 13:54:44.696  4062  4062 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:54:44.749  1738  2430 I iu.UploadsManager: num updated entries: 0
,09-09 13:54:44.766  1738  2430 I iu.SyncManager: NEXT; no task
,09-09 13:54:44.796  3805  4338 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:54:44.869  4026  4335 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:54:44.879  1515  4340 I VacuumService: Vacuum at: now=1473422084879 tag=VacuumService
,09-09 13:54:44.910  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:54:44.910  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:54:44.910  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:44.910  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:44.987  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:54:44.987  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:54:44.987  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:44.987  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:45.009  3108  4330 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:54:45.009  3108  4330 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:54:45.009  3108  4330 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	... 12 more
09-09 13:54:45.009  3108  4330 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at fal.a(PG:38)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:54:45.009  3108  4330 E HttpOperation: 	... 14 more
,09-09 13:54:45.023  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:54:45.023  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:54:45.023  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:54:45.023  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:45.055  3805  4338 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:54:45.056  3805  4329 E BooksSync: Soft error
09-09 13:54:45.056  3805  4329 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:54:45.056  3805  4329 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:54:45.057  3805  4329 E BooksSync: Sync error
09-09 13:54:45.057  3805  4329 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:54:45.057  3805  4329 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:54:45.057  3805  4329 I BooksSync: Finished books sync
,09-09 13:54:45.083   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163317, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:54:45.126  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 13:54:45.126  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 13:54:45.126  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:45.127  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 13:54:45.133  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:54:45.133  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:54:45.133  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:45.133  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:45.156  3108  4330 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:54:45.156  3108  4330 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at hec.a(PG:42)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at hee.a(PG:102)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at czr.a(PG:65)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at kka.a(PG:108)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:54:45.156  3108  4330 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	... 15 more
09-09 13:54:45.156  3108  4330 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at fal.a(PG:38)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:54:45.156  3108  4330 E HttpOperation: 	... 17 more
09-09 13:54:45.157  3108  4330 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:54:45.157  3108  4330 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	... 15 more
09-09 13:54:45.157  3108  4330 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:54:45.157  3108  4330 E ExperimentLoader: 	... 17 more
,09-09 13:54:45.189  1738  4332 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-09 13:54:45.341  1515  4342 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 13:54:45.344  1515  4342 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:54:45.376   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 162373, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:54:45.398  1515  4342 W Uploader:  no longer exists, so no auth token.
,09-09 13:54:45.404   874  1311 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:46.703  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:54:46.707  1515  4342 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:54:46.707  1515  4342 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:54:46.707  1515  4342 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:46.707  1515  4342 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:46.709  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:54:46.711  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:54:46.711  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb8be9 removed from the list
09-09 13:54:46.711  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:46.711  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:54:46.712  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:46.721  3853  4353 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 13:54:46.721  3853  4353 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:54:46.726  1515  4342 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:54:46.726  1515  4342 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:54:46.726  1515  4342 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:54:47.054  1515  4342 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:54:47.054  1515  4342 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:54:47.054  1515  4342 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:47.054  1515  4342 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:47.073  1515  4342 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:54:47.073  1515  4342 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:54:47.073  1515  4342 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:54:47.667  1515  4342 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 13:54:47.667  1515  4342 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 13:54:47.667  1515  4342 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:54:47.667  1515  4342 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:54:47.687  1515  4342 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:54:47.687  1515  4342 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 13:54:47.687  1515  4342 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 13:54:49.721  3853  4357 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 13:54:49.722  3853  4357 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:54:49.722  3853  4357 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:54:49.723  3853  4353 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-09 13:54:49.723  3853  4357 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:54:49.723  3853  4353 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:54:49.724  3853  4353 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:54:49.724  3853  4357 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:54:49.727  3853  4359 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Sender)
,09-09 13:54:49.728  3853  4353 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:54:49.730  3853  4360 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: IncomingSocketThread/Receiver)
09-09 13:54:49.730  3853  4361 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: OutgoingSocketThread/Sender)
09-09 13:54:49.731  3853  4353 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:54:49.731  3853  4360 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 445, thread name: IncomingSocketThread/Receiver)
09-09 13:54:49.731  3853  4360 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:54:49.732  3853  4360 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 445, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:54:49.733  3853  4362 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: OutgoingSocketThread/Receiver)
,09-09 13:54:49.736  3853  4362 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: OutgoingSocketThread/Receiver)
,09-09 13:54:49.736  3853  4362 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 13:54:49.737  3853  4362 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:54:49.861  1872  1966 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-09 13:54:49.861  1872  1966 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 13:54:49.909  1515  1515 I ConfigService: onCreate
,09-09 13:54:52.302   874  1311 D ConnectivityService: handlePromptUnvalidated 102
,09-09 13:54:52.729  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 13:54:52.732  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:54:52.740  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@64d24cd Bundle[{}]
,09-09 13:54:52.741  3853  3902 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:54:52.741  3853  3902 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:54:52.742  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:54:52.742  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:54:52.743  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:54:52.743  3853  3902 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:54:52.747  3853  3902 I System.out: Running OutgoingSocketThread
,09-09 13:54:52.751  3853  4364 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:54:52.751  3853  4364 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:54:54.980  1515  1515 I ConfigService: onDestroy
,09-09 13:54:55.760  3853  4366 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:54:55.760  3853  4366 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:54:55.761  3853  4366 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:54:55.762  3853  4364 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-09 13:54:55.762  3853  4366 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:54:55.762  3853  4364 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:54:55.763  3853  4364 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:54:55.765  3853  4368 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: IncomingSocketThread/Sender)
,09-09 13:54:55.766  3853  4364 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:54:55.767  3853  4366 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:54:55.771  3853  4364 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-09 13:54:55.773  3853  4369 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: OutgoingSocketThread/Sender)
,09-09 13:54:55.777  3853  4370 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: IncomingSocketThread/Receiver)
,09-09 13:54:55.778  3853  4370 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 457, thread name: IncomingSocketThread/Receiver)
09-09 13:54:55.778  3853  4370 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:54:55.779  3853  4370 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:54:55.779  3853  4371 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: OutgoingSocketThread/Receiver)
,09-09 13:54:55.780  3853  4371 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: OutgoingSocketThread/Receiver)
09-09 13:54:55.780  3853  4371 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:54:55.781  3853  4371 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:54:57.569  1515  2224 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:54:58.762  3853  3902 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 468)
,09-09 13:54:58.765  3853  3902 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 13:54:58.765  3853  3902 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 469)
,09-09 13:54:58.771  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:54:58.771  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1c06e added. We now have 3 listener(s)
,09-09 13:54:58.773  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:54:58.773  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:54:58.773  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:54:58.773  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:54:58.774  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a4a30f added. We now have 4 listener(s)
09-09 13:54:58.774  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:54:58.774  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:54:58.782  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:58.795  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:54:58.802  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:54:58.803  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:54:58.804  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:54:58.805  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:54:58.806  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:54:58.807  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:58.807  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:54:58.807  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:58.807  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:54:58.809  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:54:58.809  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1c06e removed from the list
,09-09 13:54:58.810  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:58.810  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a4a30f removed from the list
09-09 13:54:58.815  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:54:58.815  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:54:58.815  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:54:58.817  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:58.817  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:54:58.821  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:54:58.821  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:54:58.821  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:54:58.822  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a4a30f not in the list
09-09 13:54:58.822  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:58.822  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:54:58.825  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:54:58.825  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:54:58.825  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:54:58.825  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a4a30f not in the list
09-09 13:54:58.825  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:54:58.825  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:58.826  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:54:58.826  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1c06e not in the list
09-09 13:54:58.827  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:54:58.827  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f7fda5 added. We now have 3 listener(s)
,09-09 13:54:58.831  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:54:58.831  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:54:58.831  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:54:58.832  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:54:58.832  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97d757a added. We now have 4 listener(s)
09-09 13:54:58.832  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:54:58.833  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:54:58.838  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:54:58.853  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:54:58.858  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:54:58.859  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:54:58.859  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:54:58.859  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:54:58.860  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:54:58.860  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:54:58.860  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:54:58.864  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:58.868  3853  3902 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:54:58.868  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:54:58.869  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:54:58.884  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:54:58.889  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:54:58.890  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:54:58.903  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:54:58.904  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:54:58.906  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:54:58.908  3853  3902 D BluetoothAdapter: STATE_ON
,09-09 13:54:58.925  4255  4266 D BtGatt.GattService: registerClient() - UUID=92ddba5d-3791-4160-80c4-007bd7e281ac
,09-09 13:54:58.928  4255  4271 D BtGatt.GattService: onClientRegistered() - UUID=92ddba5d-3791-4160-80c4-007bd7e281ac, clientIf=5
,09-09 13:54:58.930  3853  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:54:58.936  4255  4265 D BtGatt.GattService: start scan with filters
,09-09 13:54:58.950  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:54:58.950  4255  4274 D BtGatt.ScanManager: handling starting scan
,09-09 13:54:58.951  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:54:58.952  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 13:54:58.953  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 13:54:58.957  4255  4274 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b91091
,09-09 13:54:58.965  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:54:58.966  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:54:58.966  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:54:58.973  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:54:58.978  4255  4271 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:54:58.978  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:54:58.980  4255  4274 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:54:58.986  3853  3902 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:54:58.987  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:54:58.987  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:54:58.987  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:54:58.988  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:54:58.988  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:54:58.990  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:54:58.990  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:54:58.990  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:54:58.993  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:54:58.993  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:54:58.995  3853  3902 D BluetoothAdapter: STATE_ON
,09-09 13:54:58.996  4255  4266 D BtGatt.GattService: stopScan() - queue size =1
09-09 13:54:58.997  4255  4271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 13:54:58.997  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:54:58.998  4255  4265 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:54:58.998  4255  4274 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 13:54:58.998  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:54:58.998  4255  4274 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 13:54:58.998  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:54:58.999  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 13:54:59.001  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:54:59.001  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:54:59.004  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:54:59.004  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:54:59.005  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:54:59.005  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-09 13:54:59.006  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:54:59.009  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:54:59.009  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:54:59.009  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:54:59.017  4255  4271 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:54:59.017  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:54:59.027  4255  4271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:54:59.027  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:54:59.045  4255  4271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 13:54:59.046  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:54:59.047  4255  4274 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:54:59.063  4255  4271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 13:54:59.063  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:54:59.064  4255  4274 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:54:59.080  4255  4271 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 13:54:59.081  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:54:59.510  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:54:59.511  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:54:59.511  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:55:02.009  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:55:02.010  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:55:02.010  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 13:55:02.011  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:55:02.011  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:55:02.012  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:55:02.012  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:55:02.012  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f7fda5 removed from the list
09-09 13:55:02.012  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:55:02.013  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97d757a removed from the list
09-09 13:55:02.013  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:55:02.013  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:02.015  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:02.015  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:02.019  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:02.019  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 13:55:02.020  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:55:02.020  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97d757a not in the list
,09-09 13:55:02.020  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:55:02.021  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:02.024  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:02.024  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:02.024  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:02.025  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97d757a not in the list
09-09 13:55:02.025  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:55:02.025  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:02.026  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:02.026  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f7fda5 not in the list
09-09 13:55:02.029  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:55:02.030  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@953e507 added. We now have 3 listener(s)
,09-09 13:55:02.032  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:55:02.033  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:55:02.033  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:55:02.033  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:55:02.033  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ead634 added. We now have 4 listener(s)
09-09 13:55:02.034  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:55:02.034  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:55:02.039  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:55:02.046  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:55:02.049  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:55:02.049  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:55:02.049  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:55:02.050  3853  3902 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:55:02.051  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-09 13:55:02.053  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:55:02.053  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:55:02.053  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything,
,09-09 13:55:02.053  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:55:02.053  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:55:02.055  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:55:02.056  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:55:02.056  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:55:02.056  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:55:02.057  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-09 13:55:02.057  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:55:02.057  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:55:02.057  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:55:02.057  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:55:02.063  3853  3902 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:55:02.063  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:55:02.066  3853  4372 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:55:02.069  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:55:02.070  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:55:02.070  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:55:02.071  3853  4372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:55:02.073  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:55:02.074  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:55:02.074  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-09 13:55:02.075  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:55:02.076  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:55:02.076  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:55:02.076  3853  3902 D BluetoothAdapter: STATE_ON
,09-09 13:55:02.083  4255  4294 D BtGatt.GattService: registerClient() - UUID=c1394b99-f47d-487d-8df6-9baf77b921ef
,09-09 13:55:02.083  4255  4271 D BtGatt.GattService: onClientRegistered() - UUID=c1394b99-f47d-487d-8df6-9baf77b921ef, clientIf=5
09-09 13:55:02.084  3853  3898 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:55:02.087  4255  4273 D BtGatt.AdvertiseManager: message : 0
,09-09 13:55:02.091  4255  4273 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:55:02.113  4255  4271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:55:02.124  4255  4271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:55:02.126  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:55:02.126  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:55:02.133  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:55:02.136  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:55:02.137  3853  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:55:02.137  3853  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:55:02.138  3853  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:55:02.138  3853  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:55:02.139  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:55:02.141  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:55:02.147  3853  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:55:02.148  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:55:02.648  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:55:02.649  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:55:02.649  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:55:05.142  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:55:05.143  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:55:05.143  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:55:05.143  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:55:05.144  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:55:05.144  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:55:05.146  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:55:05.146  3853  4372 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:55:05.146  3853  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:55:05.147  3853  4372 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:55:05.147  3853  4372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:55:05.148  3853  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:55:05.149  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:55:05.149  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:55:05.150  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:55:05.150  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:55:05.151  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:55:05.156  3853  3902 D BluetoothAdapter: STATE_ON
09-09 13:55:05.156  3853  3902 D BluetoothLeScanner: could not find callback wrapper
09-09 13:55:05.156  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:55:05.157  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:55:05.159  4255  4273 D BtGatt.AdvertiseManager: message : 1
09-09 13:55:05.161  4255  4273 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:55:05.167  4255  4271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:55:05.168  4255  4271 D BtGatt.GattService: Client app is not null!
,09-09 13:55:05.169  4255  4265 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:55:05.170  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:55:05.170  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:55:05.170  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:55:05.171  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:55:05.171  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:55:05.173  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:55:05.173  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:55:05.173  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-09 13:55:05.174  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:55:05.177  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:55:05.178  3853  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:55:05.178  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:05.178  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:55:05.178  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:55:05.178  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:55:05.178  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:55:05.178  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:55:05.179  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@953e507 removed from the list
09-09 13:55:05.179  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:05.179  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ead634 removed from the list
09-09 13:55:05.179  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:55:05.180  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:05.181  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:05.181  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:05.183  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:05.183  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:05.184  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:05.184  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ead634 not in the list
,09-09 13:55:05.184  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:05.184  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:05.186  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:05.186  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:05.187  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:55:05.187  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ead634 not in the list
09-09 13:55:05.187  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:55:05.187  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:55:05.188  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:05.188  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@953e507 not in the list
,09-09 13:55:05.190  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:55:05.190  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e924159 added. We now have 3 listener(s)
,09-09 13:55:05.196  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:55:05.196  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:55:05.196  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:55:05.197  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:55:05.197  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@805211e added. We now have 4 listener(s)
09-09 13:55:05.197  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:55:05.198  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:55:05.204  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:55:05.212  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:55:05.215  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:55:05.215  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:55:05.215  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:55:05.215  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 13:55:05.215  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:55:05.215  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:55:05.215  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:55:05.219  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:55:05.221  3853  3902 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:55:05.221  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:55:05.222  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:55:05.227  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:55:05.228  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:55:05.228  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:55:05.233  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:55:05.233  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 13:55:05.234  3853  3902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 13:55:05.235  3853  3902 D BluetoothAdapter: STATE_ON
,09-09 13:55:05.238  4255  4284 D BtGatt.GattService: registerClient() - UUID=4a243095-feac-4716-85a7-a14671d73179
,09-09 13:55:05.239  4255  4271 D BtGatt.GattService: onClientRegistered() - UUID=4a243095-feac-4716-85a7-a14671d73179, clientIf=5
09-09 13:55:05.239  3853  3898 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 13:55:05.240  4255  4265 D BtGatt.GattService: start scan with filters
,09-09 13:55:05.244  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 13:55:05.244  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 13:55:05.245  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 13:55:05.245  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 13:55:05.245  4255  4274 D BtGatt.ScanManager: handling starting scan
09-09 13:55:05.248  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:55:05.248  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:55:05.248  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 13:55:05.250  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:55:05.257  4255  4271 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 13:55:05.257  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:55:05.257  4255  4274 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 13:55:05.271  4255  4271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 13:55:05.272  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:55:05.272  4255  4274 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:55:05.272  4255  4274 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 13:55:05.296  4255  4271 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 13:55:05.296  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:55:05.309  4255  4271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 13:55:05.309  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:55:05.680  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:55:05.748  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:55:05.749  3853  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:55:05.749  3853  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:55:06.818  4255  4255 D BtGatt.ScanManager: awakened up at time 227056
,09-09 13:55:06.821  4255  4274 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 13:55:06.869  4255  4271 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 13:55:06.869  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:55:06.869  4255  4271 D BtGatt.GattService: current time is 227107981695
,09-09 13:55:06.873  4255  4271 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -103, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 78, -20, -96, 83, -39, -56, 1, -128, -78, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39, 0, 81, 34, 97, 112, -14, -5, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:55:06.877  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 13:55:06.879  4255  4271 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39]
,09-09 13:55:06.880  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-09 13:55:06.880  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 13:55:06.881  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 13:55:06.882  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:55:06.887  3853  3853 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 1], added - the peer count is 1
,09-09 13:55:06.888  3853  3853 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 1], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-09 13:55:08.269  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:55:08.269  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:55:08.270  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
09-09 13:55:08.270  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.270  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:55:08.271  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:55:08.271  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:55:08.271  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:55:08.271  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:55:08.273  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:55:08.273  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:55:08.275  3853  3902 D BluetoothAdapter: STATE_ON
09-09 13:55:08.277  4255  4284 D BtGatt.GattService: stopScan() - queue size =1
,09-09 13:55:08.280  4255  4265 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:55:08.281  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:55:08.282  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:55:08.282  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:55:08.282  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:55:08.283  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 13:55:08.286  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:55:08.287  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:55:08.287  3853  3902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:55:08.287  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:55:08.291  4255  4255 D BtGatt.ScanManager: awakened up at time 228529
,09-09 13:55:08.294  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:55:08.294  3853  3902 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-09 13:55:08.298  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:55:08.299  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:55:08.299  3853  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:55:08.299  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:55:08.299  3853  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:55:08.300  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:55:08.300  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:55:08.300  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e924159 removed from the list
09-09 13:55:08.300  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:55:08.301  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@805211e removed from the list
09-09 13:55:08.301  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:55:08.301  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:08.303  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.303  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:08.306  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:08.306  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:08.306  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:08.306  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@805211e not in the list
09-09 13:55:08.306  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.306  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:08.307  4255  4271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 13:55:08.307  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 13:55:08.307  4255  4274 D BtGatt.ScanManager: stopping BLe Batch
,09-09 13:55:08.308  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:08.308  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:08.308  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:08.308  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@805211e not in the list
09-09 13:55:08.308  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:55:08.308  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:55:08.308  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:08.308  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e924159 not in the list
,09-09 13:55:08.309  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:55:08.309  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2584b8 added. We now have 3 listener(s)
09-09 13:55:08.311  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:55:08.311  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:55:08.311  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:55:08.311  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:55:08.312  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b9c291 added. We now have 4 listener(s)
09-09 13:55:08.312  3853  3902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:55:08.312  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:55:08.316  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:55:08.322  4255  4271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 13:55:08.323  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:55:08.323  4255  4274 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:55:08.323  3853  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:55:08.326  3853  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:55:08.327  3853  3902 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:55:08.327  3853  3902 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:55:08.327  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:55:08.327  3853  3902 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 13:55:08.327  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:55:08.328  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.328  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:55:08.328  3853  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:55:08.329  3853  3902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2584b8 removed from the list
09-09 13:55:08.329  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:55:08.329  3853  3902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b9c291 removed from the list
09-09 13:55:08.330  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:55:08.333  3853  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:55:08.333  3853  3902 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:55:08.333  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:08.334  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.334  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:08.335  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:08.335  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:08.335  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 13:55:08.335  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b9c291 not in the list
09-09 13:55:08.335  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.335  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:55:08.336  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 13:55:08.336  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 13:55:08.336  3853  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:55:08.336  3853  3902 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b9c291 not in the list
,09-09 13:55:08.336  3853  3902 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:55:08.336  3853  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:55:08.336  3853  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:55:08.337  3853  3902 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2584b8 not in the list
,09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:55:08.338  3853  3902 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 13:55:08.338  4255  4271 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-09 13:55:08.339  4255  4271 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 13:55:08.339  4255  4271 D BtGatt.GattService: current time is 228577450929,
09-09 13:55:08.339  4255  4271 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 13:55:08.339  4255  4271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 13:55:08.801  3853  3853 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:55:10.356  3853  4373 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 478, name: My test thread name)
,09-09 13:55:12.353  3853  3902 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 478
,09-09 13:55:12.353  3853  3902 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 478, name: My test thread name)
,09-09 13:55:12.360  3853  4374 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 479, name: My test thread name)
,09-09 13:55:12.361  3853  4374 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 479, thread name: My test thread name)
09-09 13:55:12.361  3853  4374 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 479, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:55:12.366  3853  3902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:55:12.374  3853  4375 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 483, name: My test thread name)
,09-09 13:55:12.375  3853  4375 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 483, thread name: My test thread name): Test exception.
,09-09 13:55:12.377  3853  4375 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 483, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 13:55:12.386  3853  3902 I jxcore-log: Total number of executed tests:  82
09-09 13:55:12.386  3853  3902 I jxcore-log: 
,09-09 13:55:12.387  3853  3902 I jxcore-log: Number of passed tests:  81
09-09 13:55:12.387  3853  3902 I jxcore-log: 
,09-09 13:55:12.388  3853  3902 I jxcore-log: Number of failed tests:  1
09-09 13:55:12.388  3853  3902 I jxcore-log: 
09-09 13:55:12.389  3853  3902 I jxcore-log: Number of ignored tests:  0
09-09 13:55:12.389  3853  3902 I jxcore-log: 
09-09 13:55:12.389  3853  3902 I jxcore-log: Total duration:  96126
09-09 13:55:12.389  3853  3902 I jxcore-log: 
,09-09 13:55:12.391  3853  3902 I jxcore-log: Failures: 
09-09 13:55:12.391  3853  3902 I jxcore-log:  DiscoveryManager1 isRunning should return true
09-09 13:55:12.391  3853  3902 I jxcore-log: Expected: is <true>
09-09 13:55:12.391  3853  3902 I jxcore-log:      but: was <false>
09-09 13:55:12.391  3853  3902 I jxcore-log: 
09-09 13:55:12.391  3853  3902 I jxcore-log: 
,09-09 13:55:12.392  3853  3902 I jxcore-log: Failed to execute UT.
09-09 13:55:12.392  3853  3902 I jxcore-log: 
,09-09 13:55:12.400  3853  3902 I jxcore-log: Unit Test app is loaded
09-09 13:55:12.400  3853  3902 I jxcore-log: 
,09-09 13:55:12.416  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.416  3853  3902 I jxcore-log: 
,09-09 13:55:12.421  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.421  3853  3902 I jxcore-log: 
,09-09 13:55:12.423  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.423  3853  3902 I jxcore-log: 
,09-09 13:55:12.424  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.424  3853  3902 I jxcore-log: 
,09-09 13:55:12.425  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.425  3853  3902 I jxcore-log: 
09-09 13:55:12.426  3853  3853 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:55:12.427  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.427  3853  3902 I jxcore-log: 
09-09 13:55:12.430  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.430  3853  3902 I jxcore-log: 
,09-09 13:55:12.432  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.432  3853  3902 I jxcore-log: 
,09-09 13:55:12.434  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.434  3853  3902 I jxcore-log: 
09-09 13:55:12.435  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.435  3853  3902 I jxcore-log: 
,09-09 13:55:12.435  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.435  3853  3902 I jxcore-log: 
09-09 13:55:12.436  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.436  3853  3902 I jxcore-log: 
,09-09 13:55:12.437  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.437  3853  3902 I jxcore-log: 
09-09 13:55:12.438  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.438  3853  3902 I jxcore-log: 
,09-09 13:55:12.439  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.439  3853  3902 I jxcore-log: 
09-09 13:55:12.440  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.440  3853  3902 I jxcore-log: 
,09-09 13:55:12.441  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.441  3853  3902 I jxcore-log: 
09-09 13:55:12.442  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.442  3853  3902 I jxcore-log: 
,09-09 13:55:12.442  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.442  3853  3902 I jxcore-log: 
09-09 13:55:12.443  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.443  3853  3902 I jxcore-log: 
,09-09 13:55:12.444  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.444  3853  3902 I jxcore-log: 
09-09 13:55:12.445  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.445  3853  3902 I jxcore-log: 
09-09 13:55:12.445  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.445  3853  3902 I jxcore-log: 
,09-09 13:55:12.446  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.446  3853  3902 I jxcore-log: 
09-09 13:55:12.447  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.447  3853  3902 I jxcore-log: 
,09-09 13:55:12.448  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.448  3853  3902 I jxcore-log: 
09-09 13:55:12.448  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.448  3853  3902 I jxcore-log: 
09-09 13:55:12.449  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.449  3853  3902 I jxcore-log: 
,09-09 13:55:12.450  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.450  3853  3902 I jxcore-log: 
,09-09 13:55:12.451  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.451  3853  3902 I jxcore-log: 
09-09 13:55:12.453  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.453  3853  3902 I jxcore-log: 
,09-09 13:55:12.453  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.453  3853  3902 I jxcore-log: 
09-09 13:55:12.454  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.454  3853  3902 I jxcore-log: 
,09-09 13:55:12.454  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.454  3853  3902 I jxcore-log: 
09-09 13:55:12.454  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:55:12.454  3853  3902 I jxcore-log: 
09-09 13:55:12.455  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.455  3853  3902 I jxcore-log: 
09-09 13:55:12.455  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:55:12.455  3853  3902 I jxcore-log: 
,09-09 13:55:12.456  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.456  3853  3902 I jxcore-log: 
09-09 13:55:12.456  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.456  3853  3902 I jxcore-log: 
09-09 13:55:12.457  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.457  3853  3902 I jxcore-log: 
09-09 13:55:12.458  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.458  3853  3902 I jxcore-log: 
,09-09 13:55:12.458  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.458  3853  3902 I jxcore-log: 
09-09 13:55:12.459  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.459  3853  3902 I jxcore-log: 
09-09 13:55:12.459  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.459  3853  3902 I jxcore-log: 
,09-09 13:55:12.460  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:55:12.460  3853  3902 I jxcore-log: 
09-09 13:55:12.460  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.460  3853  3902 I jxcore-log: 
09-09 13:55:12.461  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.461  3853  3902 I jxcore-log: 
,09-09 13:55:12.461  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:55:12.461  3853  3902 I jxcore-log: 
09-09 13:55:12.462  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-09 13:55:12.462  3853  3902 I jxcore-log: 
09-09 13:55:12.463  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:55:12.463  3853  3902 I jxcore-log: 
09-09 13:55:12.463  3853  3902 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:55:12.463  3853  3902 I jxcore-log: 
,09-09 13:55:12.468  3853  3902 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'off',
09-09 13:55:12.468  3853  3902 I jxcore-log:   bluetooth: 'off',
09-09 13:55:12.468  3853  3902 I jxcore-log:   wifi: 'on',
09-09 13:55:12.468  3853  3902 I jxcore-log:   cellular: 'doNotCare',
09-09 13:55:12.468  3853  3902 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 13:55:12.468  3853  3902 I jxcore-log: 
,09-09 13:55:12.468  3853  3902 I jxcore-log: Toggling BLUETOOTH ON
09-09 13:55:12.468  3853  3902 I jxcore-log: 
,09-09 13:55:12.470  3853  3902 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 13:55:12.471  3853  4373 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 478, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-09 13:55:12.477  3853  3902 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-09 13:55:12.477  3853  3902 I jxcore-log:   bluetooth: 'on',
09-09 13:55:12.477  3853  3902 I jxcore-log:   wifi: 'on',
09-09 13:55:12.477  3853  3902 I jxcore-log:   cellular: 'doNotCare',
09-09 13:55:12.477  3853  3902 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-09 13:55:12.477  3853  3902 I jxcore-log: 
,09-09 13:55:12.478  3853  3902 I jxcore-log: My device name is: motorola-Nexus 6
09-09 13:55:12.478  3853  3902 I jxcore-log: 
09-09 13:55:12.479  3853  3902 I jxcore-log: Running for WIFI network type
09-09 13:55:12.479  3853  3902 I jxcore-log: 
,09-09 13:55:14.947  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 13:55:14.947  3853  3902 I jxcore-log: 
,09-09 13:55:15.388  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 13:55:15.388  3853  3902 I jxcore-log: 
,09-09 13:55:15.421  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 13:55:15.421  3853  3902 I jxcore-log: 
,09-09 13:55:16.452  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:55:16.457  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:55:16.494  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:55:16.494  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:55:16.494  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:55:16.494  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:16.516  3108  4377 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:55:16.516  3108  4377 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
,09-09 13:55:16.516  3108  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:55:16.516  3108  4377 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	... 12 more
09-09 13:55:16.516  3108  4377 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at fal.a(PG:38)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:55:16.516  3108  4377 E HttpOperation: 	... 14 more
,09-09 13:55:16.560  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:55:16.560  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:55:16.560  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:55:16.560  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:16.587  3108  4377 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:55:16.587  3108  4377 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at hec.a(PG:42)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at hee.a(PG:102)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at czr.a(PG:65)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at kka.a(PG:108)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:55:16.587  3108  4377 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	... 15 more
09-09 13:55:16.587  3108  4377 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at fal.a(PG:38)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:55:16.587  3108  4377 E HttpOperation: 	... 17 more
,09-09 13:55:16.587  3108  4377 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:55:16.587  3108  4377 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	... 15 more
09-09 13:55:16.587  3108  43,77 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:55:16.587  3108  4377 E ExperimentLoader: 	... 17 more
,09-09 13:55:16.721   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 236379, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:55:16.755  3805  4379 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:55:16.778  3805  4380 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:55:16.809  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:55:16.809  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:55:16.809  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:55:16.809  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:16.848  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:55:16.848  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:55:16.848  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:55:16.849  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:16.862  3805  4380 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:55:16.864  3805  4379 E BooksSync: Soft error
09-09 13:55:16.864  3805  4379 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:55:16.864  3805  4379 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:55:16.864  3805  4379 E BooksSync: Sync error
09-09 13:55:16.864  3805  4379 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:55:16.864  3805  4379 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:55:16.864  3805  4379 I BooksSync: Finished books sync
,09-09 13:55:16.875   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 236957, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:55:16.938  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 13:55:16.938  3853  3902 I jxcore-log: 
,09-09 13:55:17.175  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 13:55:17.175  3853  3902 I jxcore-log: 
,09-09 13:55:17.180  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-09 13:55:17.180  3853  3902 I jxcore-log: 
,09-09 13:55:17.187  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-09 13:55:17.187  3853  3902 I jxcore-log: 
,09-09 13:55:17.263  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 13:55:17.263  3853  3902 I jxcore-log: 
,09-09 13:55:17.283  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 13:55:17.283  3853  3902 I jxcore-log: 
,09-09 13:55:17.288  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-09 13:55:17.288  3853  3902 I jxcore-log: 
,09-09 13:55:18.215  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-09 13:55:18.215  3853  3902 I jxcore-log: 
,09-09 13:55:18.381  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 13:55:18.381  3853  3902 I jxcore-log: 
,09-09 13:55:18.709  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 13:55:18.709  3853  3902 I jxcore-log: 
,09-09 13:55:18.720  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 13:55:18.720  3853  3902 I jxcore-log: 
,09-09 13:55:18.727  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-09 13:55:18.727  3853  3902 I jxcore-log: 
,09-09 13:55:18.735  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-09 13:55:18.735  3853  3902 I jxcore-log: 
,09-09 13:55:18.774  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-09 13:55:18.774  3853  3902 I jxcore-log: 
,09-09 13:55:18.822  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-09 13:55:18.822  3853  3902 I jxcore-log: 
,09-09 13:55:18.830  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-09 13:55:18.830  3853  3902 I jxcore-log: 
,09-09 13:55:18.838  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-09 13:55:18.838  3853  3902 I jxcore-log: 
,09-09 13:55:18.858  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-09 13:55:18.858  3853  3902 I jxcore-log: 
,09-09 13:55:18.864  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-09 13:55:18.864  3853  3902 I jxcore-log: 
,09-09 13:55:18.870  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-09 13:55:18.870  3853  3902 I jxcore-log: 
,09-09 13:55:18.886  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-09 13:55:18.886  3853  3902 I jxcore-log: 
,09-09 13:55:18.913  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-09 13:55:18.913  3853  3902 I jxcore-log: 
,09-09 13:55:18.925  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-09 13:55:18.925  3853  3902 I jxcore-log: 
,09-09 13:55:18.939  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-09 13:55:18.939  3853  3902 I jxcore-log: 
,09-09 13:55:18.951  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-09 13:55:18.951  3853  3902 I jxcore-log: 
,09-09 13:55:18.968  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-09 13:55:18.968  3853  3902 I jxcore-log: 
,09-09 13:55:18.979  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-09 13:55:18.979  3853  3902 I jxcore-log: 
,09-09 13:55:18.985  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-09 13:55:18.985  3853  3902 I jxcore-log: 
,09-09 13:55:19.015  3853  3902 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-09 13:55:19.015  3853  3902 I jxcore-log: 
,09-09 13:55:19.029  3853  3902 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 13:55:19.030  3853  3902 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 13:55:19.030  3853  3902 I jxcore-log: 
,09-09 13:55:19.033  3853  3902 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-09 13:55:19.033  3853  3902 I jxcore-log: 
,09-09 13:55:19.034  3853  3902 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 13:55:19.034  3853  3902 I jxcore-log: 
,09-09 13:55:19.039  3853  3902 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 13:55:19.039  3853  3902 I jxcore-log: 
,09-09 13:55:19.110  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:19.110  3853  3902 I jxcore-log: 
,09-09 13:55:19.111  3853  3902 I jxcore-log: websocket error
09-09 13:55:19.111  3853  3902 I jxcore-log: 
09-09 13:55:19.111  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:19.111  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:19.111  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:19.111  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:19.111  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:19.111  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:19.111  3853  3902 I jxcore-log: 
,09-09 13:55:20.441  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:20.441  3853  3902 I jxcore-log: 
,09-09 13:55:20.441  3853  3902 I jxcore-log: websocket error
09-09 13:55:20.441  3853  3902 I jxcore-log: 
09-09 13:55:20.442  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:20.442  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:20.442  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:20.442  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:20.442  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:20.442  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:20.442  3853  3902 I jxcore-log: 
,09-09 13:55:23.095  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:23.095  3853  3902 I jxcore-log: 
,09-09 13:55:23.096  3853  3902 I jxcore-log: websocket error
09-09 13:55:23.096  3853  3902 I jxcore-log: 
09-09 13:55:23.096  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:23.096  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:23.096  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:23.096  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:23.096  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:23.096  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:23.096  3853  3902 I jxcore-log: 
,09-09 13:55:25.412  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:25.412  3853  3902 I jxcore-log: 
,09-09 13:55:25.412  3853  3902 I jxcore-log: websocket error
09-09 13:55:25.412  3853  3902 I jxcore-log: 
09-09 13:55:25.413  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:25.413  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:25.413  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:25.413  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:25.413  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:25.413  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:25.413  3853  3902 I jxcore-log: 
,09-09 13:55:26.320   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:55:30.479  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:30.479  3853  3902 I jxcore-log: 
,09-09 13:55:30.479  3853  3902 I jxcore-log: websocket error
09-09 13:55:30.479  3853  3902 I jxcore-log: 
09-09 13:55:30.480  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:30.480  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:30.480  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:30.480  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:30.480  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:30.480  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:30.480  3853  3902 I jxcore-log: 
,09-09 13:55:35.453   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255691, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 13:55:35.539  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:35.539  3853  3902 I jxcore-log: 
,09-09 13:55:35.539  3853  3902 I jxcore-log: websocket error
09-09 13:55:35.539  3853  3902 I jxcore-log: 
09-09 13:55:35.539  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:35.539  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:35.539  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:35.539  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:35.539  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:35.539  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:35.539  3853  3902 I jxcore-log: 
,09-09 13:55:40.597  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:40.597  3853  3902 I jxcore-log: 
09-09 13:55:40.597  3853  3902 I jxcore-log: websocket error
09-09 13:55:40.597  3853  3902 I jxcore-log: 
09-09 13:55:40.597  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:40.597  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:40.597  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:40.597  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:40.597  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:40.597  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:40.597  3853  3902 I jxcore-log: 
,09-09 13:55:45.655  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:45.655  3853  3902 I jxcore-log: 
,09-09 13:55:45.656  3853  3902 I jxcore-log: websocket error
09-09 13:55:45.656  3853  3902 I jxcore-log: 
09-09 13:55:45.656  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:45.656  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:45.656  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:45.656  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:45.656  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:45.656  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:45.656  3853  3902 I jxcore-log: 
,09-09 13:55:47.120  3152  4382 V KeepSync: Connecting to GoogleApiClient
09-09 13:55:47.120   874  3237 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:55:47.203  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:55:47.209  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:55:47.248  1515  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:55:47.248  1515  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:55:47.248  1515  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:55:47.248  1515  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:47.269  1738  4383 V BaseAuthAsyncOperation: access token request failed
,09-09 13:55:47.270  3152  4382 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:55:47.320  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 13:55:47.320  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:55:47.320  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:55:47.320  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:55:47.337  3152  4382 E KeepSync: IOException
09-09 13:55:47.337  3152  4382 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:55:47.337  3152  4382 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:55:47.337  3152  4382 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:55:47.337  3152  4382 E KeepSync: 	... 10 more
09-09 13:55:47.338  3152  4382 W KeepSync: Sync result 2
,09-09 13:55:47.349   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 255404, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:55:50.708  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:50.708  3853  3902 I jxcore-log: 
09-09 13:55:50.708  3853  3902 I jxcore-log: websocket error
09-09 13:55:50.708  3853  3902 I jxcore-log: 
09-09 13:55:50.709  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:50.709  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:50.709  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:50.709  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:50.709  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:50.709  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:50.709  3853  3902 I jxcore-log: 
,09-09 13:55:55.764  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:55:55.764  3853  3902 I jxcore-log: 
09-09 13:55:55.764  3853  3902 I jxcore-log: websocket error
09-09 13:55:55.764  3853  3902 I jxcore-log: 
09-09 13:55:55.765  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:55:55.765  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:55:55.765  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:55:55.765  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:55.765  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:55:55.765  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:55:55.765  3853  3902 I jxcore-log: 
,09-09 13:56:00.869  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:56:00.869  3853  3902 I jxcore-log: 
,09-09 13:56:00.869  3853  3902 I jxcore-log: websocket error
09-09 13:56:00.869  3853  3902 I jxcore-log: 
09-09 13:56:00.870  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:56:00.870  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:56:00.870  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:56:00.870  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:00.870  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:56:00.870  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:00.870  3853  3902 I jxcore-log: 
,09-09 13:56:05.949  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:56:05.949  3853  3902 I jxcore-log: 
,09-09 13:56:05.950  3853  3902 I jxcore-log: websocket error
09-09 13:56:05.950  3853  3902 I jxcore-log: 
09-09 13:56:05.950  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:56:05.950  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:56:05.950  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:56:05.950  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:05.950  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:56:05.950  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:05.950  3853  3902 I jxcore-log: 
,09-09 13:56:11.015  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:56:11.015  3853  3902 I jxcore-log: 
,09-09 13:56:11.016  3853  3902 I jxcore-log: websocket error
09-09 13:56:11.016  3853  3902 I jxcore-log: 
09-09 13:56:11.017  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:56:11.017  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:56:11.017  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:56:11.017  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:11.017  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:56:11.017  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:11.017  3853  3902 I jxcore-log: 
,09-09 13:56:13.999   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:56:16.081  3853  3902 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 13:56:16.081  3853  3902 I jxcore-log: 
,09-09 13:56:16.081  3853  3902 I jxcore-log: websocket error
09-09 13:56:16.081  3853  3902 I jxcore-log: 
09-09 13:56:16.081  3853  3902 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 13:56:16.081  3853  3902 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 13:56:16.081  3853  3902 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 13:56:16.081  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:16.081  3853  3902 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 13:56:16.081  3853  3902 I jxcore-log: emit@events.js:82:1
09-09 13:56:16.081  3853  3902 I jxcore-log: 
,09-09 13:56:17.686  3152  4389 V KeepSync: Connecting to GoogleApiClient
09-09 13:56:17.687   874  1922 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:56:17.734  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:17.735  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:17.754  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:56:17.754  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 13:56:17.754  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:56:17.754  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:17.770  1738  4390 V BaseAuthAsyncOperation: access token request failed
,09-09 13:56:17.771  3152  4389 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:56:17.817  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:56:17.817  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:56:17.817  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:56:17.817  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:17.830  3152  4389 E KeepSync: IOException
09-09 13:56:17.830  3152  4389 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:56:17.830  3152  4389 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:56:17.830  3152  4389 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:56:17.830  3152  4389 E KeepSync: 	... 10 more
09-09 13:56:17.830  3152  4389 W KeepSync: Sync result 2
,09-09 13:56:17.841   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 297596, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:56:21.052   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=301290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 13:56:21.239  3853  3902 I jxcore-log: ThaliTape :: Reconnected to the test server
09-09 13:56:21.239  3853  3902 I jxcore-log: 
,09-09 13:56:21.257  3853  3902 I jxcore-log: ThaliTape :: Connected to the test server
09-09 13:56:21.257  3853  3902 I jxcore-log: 
,09-09 13:56:47.983  3805  4401 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:56:48.098  3805  4403 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:56:48.106  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:48.111  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:48.143  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:56:48.143  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:56:48.144  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:56:48.144  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:48.169  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:48.170  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:56:48.228  1515  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:56:48.228  1515  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:56:48.228  1515  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:56:48.228  1515  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:48.243  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:56:48.244  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:56:48.244  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:56:48.244  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:48.268  3805  4403 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:56:48.268  3805  4401 E BooksSync: Soft error
09-09 13:56:48.268  3805  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:56:48.268  3805  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:56:48.268  3805  4401 E BooksSync: Sync error
09-09 13:56:48.268  3805  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:56:48.268  3805  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:56:48.268  3805  4401 I BooksSync: Finished books sync
,09-09 13:56:48.283   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 300385, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:56:48.291  3108  4402 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:56:48.291  3108  4402 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:56:48.291  3108  4402 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	... 12 more
09-09 13:56:48.291  3108  4402 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:56:48.291  3108  4402 E HttpOperation: 	at fal.a(PG:38)
09-09 13:56:48.291  3108  4402 E HttpOperation: ,	at jdj.a(PG:4089)
09-09 13:56:48.291  3108  4402 E HttpOperation: 	... 14 more
,09-09 13:56:48.333  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:56:48.333  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:56:48.333  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:56:48.333  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:56:48.347  3108  4402 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:56:48.347  3108  4402 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at hec.a(PG:42)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at hee.a(PG:102)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at czr.a(PG:65)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at kka.a(PG:108)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:56:48.347  3108  4402 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	... 15 more
09-09 13:56:48.347  3108  4402 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at fal.a(PG:38)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:56:48.347  3108  4402 E HttpOperation: 	... 17 more
09-09 13:56:48.347  3108  4402 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:56:48.347  3108  4402 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	... 15 more
09-09 13:56:48.347  3108  4402 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:56:48.347  3108  4402 E ExperimentLoader: 	... 17 more
,09-09 13:56:48.450   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 298487, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:57:04.701  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:57:04.713  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:57:04.715  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:57:04.761  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 13:57:04.761  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 13:57:04.761  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:57:04.761  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:57:04.788  1515  2123 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 13:57:04.788  1515  2123 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 13:57:04.794  3593  3622 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 13:57:04.794  3593  3622 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 13:57:04.794  3593  3622 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 13:57:04.794  3593  3622 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 13:57:04.794  3593  3622 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 13:57:04.794  3593  3622 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 13:57:04.794  3593  3622 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 13:57:18.656  3152  4409 V KeepSync: Connecting to GoogleApiClient
09-09 13:57:18.657   874  1922 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:57:18.720  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:57:18.723  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:57:18.753  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:57:18.754  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:57:18.754  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:57:18.754  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:57:18.785  1738  4410 V BaseAuthAsyncOperation: access token request failed
,09-09 13:57:18.786  3152  4409 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:57:18.858  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:57:18.859  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 13:57:18.859  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:57:18.859  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:57:18.877  3152  4409 E KeepSync: IOException
09-09 13:57:18.877  3152  4409 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:57:18.877  3152  4409 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:57:18.877  3152  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:57:18.877  3152  4409 E KeepSync: 	... 10 more
,09-09 13:57:18.878  3152  4409 W KeepSync: Sync result 2
,09-09 13:57:18.886   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 358098, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:58:51.785  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:58:51.787  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:58:51.842  1515  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 13:58:51.842  1515  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:58:51.843  1515  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:58:51.843  1515  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:58:51.862  3108  4417 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:58:51.862  3108  4417 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:58:51.862  3108  4417 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	... 12 more
09-09 13:58:51.862  3108  4417 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at fal.a(PG:38)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:58:51.862  3108  4417 E HttpOperation: 	... 14 more
,09-09 13:58:51.919  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:58:51.919  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 13:58:51.919  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:58:51.919  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:58:51.943  3108  4417 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:58:51.943  3108  4417 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at hec.a(PG:42)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at hee.a(PG:102)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at czr.a(PG:65)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at kka.a(PG:108)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:58:51.943  3108  4417 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	... 15 more
09-09 13:58:51.943  3108  4417 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at fal.a(PG:38)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:58:51.943  3108  4417 E HttpOperation: 	... 17 more
09-09 13:58:51.943  3108  4417 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 13:58:51.943  3108  4417 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	... 15 more
09-09 13:58:51.943  3108  4417 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:58:51.943  3108  4417 E ExperimentLoader: 	... 17 more
,09-09 13:58:52.053   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 451744, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:59:18.775  1515  2224 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:59:22.349  3805  4422 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:59:22.376  3805  4424 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:59:22.395  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.397  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.418  1515  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 13:59:22.418  1515  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:59:22.418  1515  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:59:22.418  1515  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:59:22.446  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.448  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.473  3152  4423 V KeepSync: Connecting to GoogleApiClient
,09-09 13:59:22.473   874  1918 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:59:22.502  1515  2123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:59:22.502  1515  2123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:59:22.502  1515  2123 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:59:22.503  1515  2123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:59:22.536  3805  4424 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:59:22.537  3805  4422 E BooksSync: Soft error
09-09 13:59:22.537  3805  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:59:22.537  3805  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:59:22.537  3805  4422 E BooksSync: Sync error
09-09 13:59:22.537  3805  4422 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:59:22.537  3805  4422 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:59:22.537  3805  4422 I BooksSync: Finished books sync
,09-09 13:59:22.560   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 455066, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:59:22.595  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.596  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:59:22.623  1515  3236 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:59:22.623  1515  3236 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:59:22.623  1515  3236 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:59:22.623  1515  3236 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:59:22.638  1738  4425 V BaseAuthAsyncOperation: access token request failed
,09-09 13:59:22.639  3152  4423 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:59:22.687  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 13:59:22.687  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:59:22.687  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:59:22.687  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:59:22.709  3152  4423 E KeepSync: IOException
09-09 13:59:22.709  3152  4423 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:59:22.709  3152  4423 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:59:22.709  3152  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:59:22.709  3152  4423 E KeepSync: 	... 10 more
09-09 13:59:22.709  3152  4423 W KeepSync: Sync result 2
,09-09 13:59:22.723   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 479161, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 14:02:58.222   874   874 I ActivityManager: Start proc 4440:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-09 14:02:58.325  4440  4440 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-09 14:02:58.356  4440  4440 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-09 14:02:58.356  4440  4440 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 14:02:58.356  4440  4440 I GAv4    :   adb logcat -s GAv4
,09-09 14:02:58.375  4440  4440 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:02:58.382  4440  4440 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:02:58.397  4440  4455 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 14:02:58.497   874  1921 I ActivityManager: Killing 3751:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 14:06:11.226   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:06:27.760   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=907997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:06:31.479   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=911717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:06:52.826   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=933064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:06:56.559   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:07:17.892   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=958130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:07:21.612   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=961850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:07:42.959   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=983197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:07:46.679   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:08:08.012   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1008250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:08:11.746   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:08:33.079   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1033317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:08:36.812   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1037050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:08:58.146   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:09:01.866   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:09:23.213   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1083450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:09:26.973   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:09:45.052   874  2043 I ActivityManager: Start proc 4472:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-09 14:09:45.147  4472  4472 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,09-09 14:09:45.209  4472  4485 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-09 14:09:45.288  4472  4485 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-09 14:09:45.366  4472  4485 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 14:09:45.426  4472  4472 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-09 14:09:45.629  4472  4472 W InstanceID/Rpc: Found 10011
,09-09 14:09:45.744  4513  4513 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1384650969.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1384650969.dex
,09-09 14:09:45.792  4513  4513 I dex2oat : dex2oat took 49.020ms (threads: 4) arena alloc=242KB java alloc=29KB native alloc=1258KB free=1301KB
,09-09 14:09:48.306   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:09:53.839   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1114077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:10:00.065   874   887 I ActivityManager: Waited long enough for: ServiceRecord{b793c5d u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-09 14:10:13.373   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1133610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:10:17.105   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:10:38.439   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1158677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:10:41.433  4472  4524 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-09 14:10:41.433  4472  4524 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-09 14:10:41.433  4472  4524 E YouTube : 	at iyz.a(SourceFile:100)
09-09 14:10:41.433  4472  4524 E YouTube : 	at iza.b(SourceFile:178)
09-09 14:10:41.433  4472  4524 E YouTube : 	at cch.a(SourceFile:2101)
09-09 14:10:41.433  4472  4524 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-09 14:10:41.433  4472  4524 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-09 14:10:41.433  4472  4524 E YouTube : 	at evv.run(Unknown Source)
09-09 14:10:41.433  4472  4524 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-09 14:10:41.433  4472  4524 E YouTube : 	at ain.a(SourceFile:117)
09-09 14:10:41.433  4472  4524 E YouTube : 	at ain.get(SourceFile:88)
09-09 14:10:41.433  4472  4524 E YouTube : 	at kdf.get(SourceFile:69)
09-09 14:10:41.433  4472  4524 E YouTube : 	at iyz.a(SourceFile:98)
09-09 14:10:41.433  4472  4524 E YouTube : 	... 5 more
09-09 14:10:41.433  4472  4524 E YouTube : Caused by: ahm
09-09 14:10:41.433  4472  4524 E YouTube : 	at ahr.a(SourceFile:142)
09-09 14:10:41.433  4472  4524 E YouTube : 	at kcq.a(SourceFile:49)
09-09 14:10:41.433  4472  4524 E YouTube : 	at agx.run(SourceFile:112)
,09-09 14:10:41.460  4472  4525 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,09-09 14:10:41.466   874  1386 I ActivityManager: Killing 3672:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-09 14:10:42.159   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1162397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:10:56.622   874   887 I ActivityManager: Waited long enough for: ServiceRecord{def5683 u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-09 14:11:03.505   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1183743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:11:20.399   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1200637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:11:28.559   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1208797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:11:37.093  4472  4561 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,09-09 14:11:38.344   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 14:11:45.466   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1225704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:11:47.074  4472  4564 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-09 14:11:47.074  4472  4564 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-09 14:11:47.074  4472  4564 E YouTube : 	at iyz.a(SourceFile:100)
09-09 14:11:47.074  4472  4564 E YouTube : 	at iza.b(SourceFile:178)
09-09 14:11:47.074  4472  4564 E YouTube : 	at cch.a(SourceFile:2101)
09-09 14:11:47.074  4472  4564 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-09 14:11:47.074  4472  4564 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-09 14:11:47.074  4472  4564 E YouTube : 	at evv.run(Unknown Source)
09-09 14:11:47.074  4472  4564 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-09 14:11:47.074  4472  4564 E YouTube : 	at ain.a(SourceFile:117)
09-09 14:11:47.074  4472  4564 E YouTube : 	at ain.get(SourceFile:88)
09-09 14:11:47.074  4472  4564 E YouTube : 	at kdf.get(SourceFile:69)
09-09 14:11:47.074  4472  4564 E YouTube : 	at iyz.a(SourceFile:98)
09-09 14:11:47.074  4472  4564 E YouTube : 	... 5 more
09-09 14:11:47.074  4472  4564 E YouTube : Caused by: ahm
09-09 14:11:47.074  4472  4564 E YouTube : 	at ahr.a(SourceFile:142)
09-09 14:11:47.074  4472  4564 E YouTube : 	at kcq.a(SourceFile:49)
09-09 14:11:47.074  4472  4564 E YouTube : 	at agx.run(SourceFile:112)
,09-09 14:11:53.612   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1233850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:12:10.533   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1250770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:12:18.693   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:12:32.254   874   887 I ActivityManager: Waited long enough for: ServiceRecord{795f000 u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-09 14:12:35.599   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1275837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:12:43.786   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1284024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:12:52.505  4472  4569 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,09-09 14:13:00.666   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1300904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:13:08.839   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1309077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:13:22.624  4472  4572 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-09 14:13:22.624  4472  4572 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-09 14:13:22.624  4472  4572 E YouTube : 	at iyz.a(SourceFile:100)
09-09 14:13:22.624  4472  4572 E YouTube : 	at iza.b(SourceFile:178)
09-09 14:13:22.624  4472  4572 E YouTube : 	at cch.a(SourceFile:2101)
09-09 14:13:22.624  4472  4572 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-09 14:13:22.624  4472  4572 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-09 14:13:22.624  4472  4572 E YouTube : 	at evv.run(Unknown Source)
09-09 14:13:22.624  4472  4572 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-09 14:13:22.624  4472  4572 E YouTube : 	at ain.a(SourceFile:117)
09-09 14:13:22.624  4472  4572 E YouTube : 	at ain.get(SourceFile:88)
09-09 14:13:22.624  4472  4572 E YouTube : 	at kdf.get(SourceFile:69)
09-09 14:13:22.624  4472  4572 E YouTube : 	at iyz.a(SourceFile:98)
09-09 14:13:22.624  4472  4572 E YouTube : 	... 5 more
09-09 14:13:22.624  4472  4572 E YouTube : Caused by: ahm
09-09 14:13:22.624  4472  4572 E YouTube : 	at ahr.a(SourceFile:142)
09-09 14:13:22.624  4472  4572 E YouTube : 	at kcq.a(SourceFile:49)
09-09 14:13:22.624  4472  4572 E YouTube : 	at agx.run(SourceFile:112)
,09-09 14:13:25.732   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1325970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:13:33.893   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1334131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:13:50.799   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1351037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:13:58.959   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1359197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:14:07.883   874   887 I ActivityManager: Waited long enough for: ServiceRecord{96a0c2c u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-09 14:14:15.866   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1376103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:14:24.026   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1384264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:14:28.188  4472  4577 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,09-09 14:14:40.879   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1401117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:14:49.079   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1409317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:15:05.999   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1426237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:15:14.159   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1434397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:15:31.012   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1451250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:15:37.804   874   887 I ActivityManager: Waited long enough for: ServiceRecord{7e4c6f5 u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-09 14:15:39.212   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1459450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:15:56.079   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1476317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:15:57.937  4472  4583 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
09-09 14:15:57.937  4472  4583 E YouTube : izh: java.util.concurrent.ExecutionException: ahm
09-09 14:15:57.937  4472  4583 E YouTube : 	at iyz.a(SourceFile:100)
09-09 14:15:57.937  4472  4583 E YouTube : 	at iza.b(SourceFile:178)
09-09 14:15:57.937  4472  4583 E YouTube : 	at cch.a(SourceFile:2101)
09-09 14:15:57.937  4472  4583 E YouTube : 	at com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask(SourceFile:1033)
09-09 14:15:57.937  4472  4583 E YouTube : 	at com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator.a(SourceFile:65)
09-09 14:15:57.937  4472  4583 E YouTube : 	at evv.run(Unknown Source)
09-09 14:15:57.937  4472  4583 E YouTube : Caused by: java.util.concurrent.ExecutionException: ahm
09-09 14:15:57.937  4472  4583 E YouTube : 	at ain.a(SourceFile:117)
09-09 14:15:57.937  4472  4583 E YouTube : 	at ain.get(SourceFile:88)
09-09 14:15:57.937  4472  4583 E YouTube : 	at kdf.get(SourceFile:69)
09-09 14:15:57.937  4472  4583 E YouTube : 	at iyz.a(SourceFile:98)
09-09 14:15:57.937  4472  4583 E YouTube : 	... 5 more
09-09 14:15:57.937  4472  4583 E YouTube : Caused by: ahm
09-09 14:15:57.937  4472  4583 E YouTube : 	at ahr.a(SourceFile:142)
09-09 14:15:57.937  4472  4583 E YouTube : 	at kcq.a(SourceFile:49)
09-09 14:15:57.937  4472  4583 E YouTube : 	at agx.run(SourceFile:112)
,09-09 14:16:04.279   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:16:21.146   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1501384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:16:29.346   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 14:16:43.013   874  4311 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1523250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 14:16:43.352   874   887 I ActivityManager: Waited long enough for: ServiceRecord{7858c8a u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,TIME-OUT KILL (timeout was 1400000ms),09-09 14:16:52.869  4591  4591 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 14:16:52.874  4591  4591 D AndroidRuntime: CheckJNI is OFF
09-09 14:16:52.910  4591  4591 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 14:16:52.953  4591  4591 I Radio-JNI: register_android_hardware_Radio DONE
09-09 14:16:52.973  4591  4591 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 14:16:52.983   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 14:16:52.984   874   887 I ActivityManager: Killing 3853:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 14:16:53.100   874   897 W PackageSettings: Skipping PackageSetting{c5c97fa com.example.hello/10273} due to missing metadata
09-09 14:16:53.113   874  2044 D GraphicsStats: Buffer count: 2
09-09 14:16:53.114   874  1921 I WindowState: WIN DEATH: Window{d57ab86 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 14:16:53.114   874  1310 D WifiService: Client connection lost with reason: 4
09-09 14:16:53.140   874   897 I art     : Starting a blocking GC Explicit
09-09 14:16:53.172   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 14:16:53.172   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 14:16:53.173   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-09 14:16:53.173   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 14:16:53.173   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:16:53.173   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.173   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.173   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 14:16:53.173   874   887 I ActivityManager:   Force finishing activity ActivityRecord{e1cc06f u0 com.test.thalitest/.MainActivity t4}
09-09 14:16:53.179   874  2044 W ActivityManager: Spurious death for ProcessRecord{16b12fb 0:com.test.thalitest/u0a0}, curProc for 3853: null
09-09 14:16:53.197   874   897 I art     : Explicit concurrent mark sweep GC freed 19731(1492KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 721us total 56.009ms
09-09 14:16:53.216   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 14:16:53.219  4591  4591 I art     : System.exit called, status: 0
09-09 14:16:53.219  4591  4591 I AndroidRuntime: VM exiting with result code 0.
09-09 14:16:53.280   874   897 I ActivityManager: Start proc 4603:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-09 14:16:53.289   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 14:16:53.324   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 14:16:53.330  1872  1872 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 14:16:53.331  4255  4255 D BluetoothMapAppObserver: onReceive
09-09 14:16:53.331  4255  4255 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 14:16:53.336  1872  4618 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 14:16:53.348  3693  3693 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 14:16:53.352   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 14:16:53.353  2155  2295 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 14:16:53.358  1872  4618 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-09 14:16:53.358  1872  4618 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-09 14:16:53.360  1872  4618 I Decoder : createOrResetDecoder
09-09 14:16:53.370   874  1307 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-09 14:16:53.380   874   885 I ActivityManager: Start proc 4621:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 14:16:53.386  1938  1938 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 14:16:53.410  1515  1515 I ConfigService: onCreate
09-09 14:16:53.428   874  1987 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3853 uid 10000
09-09 14:16:53.436  1872  1872 I Keyboard.Facilitator: onFinishInput()
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:16:53.438  1515  4632 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 14:16:53.439  1515  4632 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:16:53.440  1515  4632 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 14:16:53.445   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 14:16:53.451  4621  4621 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 14:16:53.453  1872  4618 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 14:16:53.481  1872  4618 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 14:16:53.482  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 14:16:53.482  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 14:16:53.484  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 14:16:53.484  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 14:16:53.486  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 14:16:53.486  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 14:16:53.487  1950  2046 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 14:16:53.487   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 14:16:53.487  1872  4618 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 14:16:53.487  1872  4618 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 14:16:53.487  1872  4618 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 14:16:53.487  1872  4618 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 14:16:53.487  1872  4618 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 14:16:53.487  1872  4618 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
09-09 14:16:53.487  1872  4618 I PeriodicStatsRecorder: shouldRecordStats() = Time to Run
09-09 14:16:53.487   874   886 E PackageManager: Failed to write settings, restoring backup
09-09 14:16:53.487   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 14:16:53.487   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 14:16:53.487   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 14:16:53.487   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 14:16:53.487   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 14:16:53.487   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:16:53.487   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.487   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.490  1872  4618 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml to backup file /data/user/0/com.google.android.inputmethod.latin/shared_prefs/local_prefs.xml.bak
09-09 14:16:53.490   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-09 14:16:53.490   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 14:16:53.490   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:16:53.490   874   887 E DropBoxManagerService: 	... 13 more
09-09 14:16:53.499   874  2043 I ActivityManager: Start proc 4638:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 14:16:53.500  1950  2046 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 14:16:53.500  1950  2046 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1950
09-09 14:16:53.500  1950  2046 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.500  1950  2046 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.503   874  1373 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 14:16:53.504   874  4648 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:16:53.504   874  4648 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:16:53.504   874  4648 E DropBoxManagerService: 	... 5 more
09-09 14:16:53.509  1950  2046 I Process : Sending signal. PID: 1950 SIG: 9
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:16:53.512  1515  4649 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:100)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:16:53.512  1515  4649 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:16:53.513  1515  4649 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
09-09 14:16:53.513  1515  4649 E SQLiteLog: (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: attempt to write a readonly database (code 8)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 14:16:53.513  1515  4649 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
09-09 14:16:53.531  4621  4621 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 14:16:53.554  4621  4654 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 14:16:53.555   874   884 I ActivityManager: Start proc 4655:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 14:16:53.600  4655  4655 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 14:16:53.616   874   885 D GraphicsStats: Buffer count: 1
09-09 14:16:53.616   874  1984 I WindowState: WIN DEATH: Window{fdf4b93 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 14:16:53.627   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1950) has died
09-09 14:16:53.628   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 14:16:53.629   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 14:16:53.632  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 14:16:53.633  1515  1515 D AndroidRuntime: Shutting down VM
09-09 14:16:53.633  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
09-09 14:16:53.633  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
09-09 14:16:53.633  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 14:16:53.633  1515  1515 E AndroidRuntime: 	... 8 more
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.644  4621  4637 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 14:16:53.644  4621  4637 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 14:16:53.653   874   887 I ActivityManager: Start proc 4672:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 14:16:53.656   874  4677 E DropBoxManagerService: Can't write: system_app_crash
09-09 14:16:53.656   874  4677 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 14:16:53.656   874  4677 E DropBoxManagerService: 	... 5 more
09-09 14:16:53.658  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
09-09 14:16:53.677   874  1921 I ActivityManager: Killing 2010:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-09 14:16:53.697   874  1310 D WifiService: Client connection lost with reason: 4
09-09 14:16:53.702   874  1310 D WifiService: Client connection lost with reason: 4

```
