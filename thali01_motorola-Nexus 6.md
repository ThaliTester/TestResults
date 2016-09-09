#### Test 8464874088320bd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 16:36:45.127  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:36:45.135  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 16:36:45.140  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 16:36:45.173  1511  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 16:36:45.173  1511  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 16:36:45.173  1511  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:36:45.173  1511  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-09 16:36:45.194  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-09 16:36:45.194  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 16:36:45.195  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-09 16:36:45.751   871  2181 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-09 16:36:45.790  3767  3767 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 16:36:45.794  3767  3767 D AndroidRuntime: CheckJNI is OFF
09-09 16:36:45.837  3767  3767 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 16:36:45.909  3767  3767 I Radio-JNI: register_android_hardware_Radio DONE
09-09 16:36:45.935  3767  3767 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 16:36:45.938   871   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 16:36:45.973  2031  2326 W SearchService: Abort, client detached.
09-09 16:36:45.977  2031  2031 I HotwordDetector: Closing mic
09-09 16:36:45.977  2031  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c23bff8
09-09 16:36:45.977  2031  2351 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 16:36:45.981  3767  3767 D AndroidRuntime: Shutting down VM
09-09 16:36:46.004   871   881 I ActivityManager: Start proc 3777:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 16:36:46.030   376  2354 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 16:36:46.031   376  2354 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 16:36:46.034   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 16:36:46.036  2031  2350 I MicroRecognitionRnrImpl: Detection finished
09-09 16:36:46.036  2031  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 16:36:46.084  3777  3777 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 16:36:46.108  3777  3777 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 16:36:46.115  3777  3777 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9518-9520)
09-09 16:36:46.115  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:36:46.135  3777  3777 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e04a62}
09-09 16:36:46.136  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 16:36:46.137  3777  3777 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 16:36:46.160  3777  3777 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 16:36:46.162  3777  3777 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 16:36:46.184  3777  3777 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 16:36:46.200  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:36:46.200  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:36:46.200  3777  3777 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:36:46.200  3777  3777 I Adreno  : Build Date                       : 10/20/15
09-09 16:36:46.200  3777  3777 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:36:46.200  3777  3777 I Adreno  : Local Branch                     : M14
09-09 16:36:46.200  3777  3777 I Adreno  : Remote Branch                    : 
09-09 16:36:46.200  3777  3777 I Adreno  : Remote Branch                    : 
09-09 16:36:46.200  3777  3777 I Adreno  : Reconstruct Branch               : 
,09-09 16:36:46.269   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f6c167:true
,09-09 16:36:46.330  3777  3777 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 16:36:46.348  3777  3777 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 16:36:46.439  3777  3816 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 16:36:46.451  3777  3802 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 16:36:46.497  3777  3816 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 16:36:46.573   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +583ms
,09-09 16:36:46.581  1889  1889 I Keyboard.Facilitator: onFinishInput()
,09-09 16:36:46.630  3777  3777 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3777
,09-09 16:36:46.750  3777  3777 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 16:36:46.820   871  2003 I ActivityManager: Killing 2971:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 16:36:46.869   871  2003 I ActivityManager: Killing 3101:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-09 16:36:46.968  3777  3818 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1681917648
,09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 16:36:46.978  3777  3818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6490446 added. We now have 1 listener(s)
09-09 16:36:46.982  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 16:36:46.982  3777  3818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:36:46.983  3777  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:36:46.983  3777  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 16:36:46.986  3777  3818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df5955d added. We now have 1 listener(s)
09-09 16:36:46.986  3777  3818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:36:46.989   871  1307 D WifiService: New client listening to asynchronous messages
,09-09 16:36:46.990  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:36:46.990  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 16:36:46.990  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 16:36:46.990  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 16:36:46.990  3777  3818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 16:36:46.992  3777  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:46.993  3777  3818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 16:36:46.998  3777  3818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:46.998  3777  3818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:36:46.998  3777  3818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 16:36:46.998  3777  3818 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:36:46.998  3777  3818 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 16:36:47.119  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:47.122  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:47.124  3777  3777 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 16:36:47.943  3777  3827 W jxcore-log: Initializing JXcore engine
,09-09 16:36:47.943  3777  3827 W jxcore-log: JXcore engine is ready
,09-09 16:36:47.980  3827  3827 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 16:36:47.980  3827  3827 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10731]" dev="sockfs" ino=10731 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 16:36:47.980  3827  3827 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 16:36:47.980  3827  3827 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25985]" dev="sockfs" ino=25985 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 16:36:47.995  3777  3827 W jxcore-log: Starting JXcore engine
,09-09 16:36:48.078  3777  3827 W jxcore-log: Platform android
09-09 16:36:48.078  3777  3827 W jxcore-log: 
,09-09 16:36:48.078  3777  3827 W jxcore-log: Process ARCH arm
09-09 16:36:48.078  3777  3827 W jxcore-log: 
,09-09 16:36:48.312  3777  3827 I jxcore-log: JXcore Cordova bridge is ready!
09-09 16:36:48.312  3777  3827 I jxcore-log: 
,09-09 16:36:48.313  3777  3827 W jxcore-log: JXcore engine is started
,09-09 16:36:48.317  3777  3818 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 16:36:48.320  3777  3777 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 16:36:50.344   871  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 16:36:56.432  3024  3838 V KeepSync: Connecting to GoogleApiClient
,09-09 16:36:56.433   871  2280 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011,
,09-09 16:36:56.485  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:36:56.487  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:36:56.505  1511  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 16:36:56.505  1511  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 16:36:56.505  1511  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:36:56.505  1511  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:36:56.517  1717  3839 V BaseAuthAsyncOperation: access token request failed
,09-09 16:36:56.518  3024  3838 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 16:36:56.562  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 16:36:56.562  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 16:36:56.562  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:36:56.562  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:36:56.582  3024  3838 E KeepSync: IOException
09-09 16:36:56.582  3024  3838 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 16:36:56.582  3024  3838 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 16:36:56.582  3024  3838 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 16:36:56.582  3024  3838 E KeepSync: 	... 10 more
,09-09 16:36:56.582  3024  3838 W KeepSync: Sync result 2
,09-09 16:36:56.594   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129752, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:36:58.064  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 16:36:58.064  3777  3827 I jxcore-log: 
,09-09 16:36:58.066  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 16:36:58.066  3777  3827 I jxcore-log: 
,09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:58.076  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:36:58.082  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:36:58.085  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 16:36:58.085  3777  3827 I jxcore-log: 
,09-09 16:36:58.087  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 16:36:58.087  3777  3827 I jxcore-log: 
,09-09 16:36:58.592  3777  3827 D executeNativeTests: Running unit tests
,09-09 16:36:58.651  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:36:58.651  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed added. We now have 2 listener(s)
,09-09 16:36:58.652  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:36:58.652  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:36:58.652  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:36:58.652  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:36:58.652  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 added. We now have 2 listener(s)
09-09 16:36:58.652  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:36:58.653  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:36:58.660  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:58.673  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:36:58.678  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:36:58.678  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:36:58.681  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-09 16:36:58.681  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:36:58.681  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:36:58.682  3777  3827 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-09 16:36:58.683  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 16:36:58.683  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:36:58.683  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:36:58.683  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:36:58.683  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.684  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.684  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:36:58.684  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:36:58.684  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.684  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:36:58.684  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:36:58.685  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed removed from the list
,09-09 16:36:58.685  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.685  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 removed from the list
,09-09 16:36:58.685  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 16:36:58.686  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.686  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.687  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.687  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.688  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.688  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.688  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.688  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.689  3777  3827 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 16:36:58.690  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:36:58.690  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:36:58.690  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.690  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:36:58.690  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.690  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 16:36:58.690  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.690  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.690  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.696  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 16:36:58.697  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.697  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:36:58.697  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.697  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.697  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.698  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.698  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:36:58.698  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.698  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 16:36:58.703  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 16:36:58.704  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:36:58.705  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 16:36:58.705  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.705  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.705  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.706  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.706  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.706  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.706  3777  3827 E org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.706  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.706  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.706  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.706  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.706  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.707  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.707  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.708  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.708  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.708  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.708  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.709  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:36:58.712  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:58.720  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:36:58.722  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.722  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:36:58.722  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:36:58.723  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:36:58.723  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:36:58.723  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:36:58.723  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:36:58.728  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:36:58.728  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:36:58.729  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:58.748  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 16:36:58.749  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:58.750  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:36:58.751  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 16:36:58.752  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 16:36:58.756  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 16:36:58.757  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:36:58.758  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:36:58.759  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:36:58.761  3777  3827 D BluetoothAdapter: STATE_ON
09-09 16:36:58.770  2663  2807 D BtGatt.GattService: registerClient() - UUID=e37af7c6-b308-4a83-b1f7-42eaaa4cc6cc
09-09 16:36:58.771  2663  2691 D BtGatt.GattService: onClientRegistered() - UUID=e37af7c6-b308-4a83-b1f7-42eaaa4cc6cc, clientIf=5
09-09 16:36:58.772  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:36:58.773  2663  2674 D BtGatt.GattService: start scan with filters
09-09 16:36:58.776  2663  2694 D BtGatt.ScanManager: handling starting scan
09-09 16:36:58.777  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:36:58.778  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:36:58.778  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:36:58.778  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:36:58.784  2663  2694 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:36:58.785  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:36:58.785  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:36:58.786  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:36:58.786  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 16:36:58.788  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 16:36:58.795  2663  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 16:36:58.795  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.796  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.796  2663  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:36:58.796  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:36:58.797  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:36:58.797  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:36:58.797  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.798  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:36:58.798  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:36:58.798  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 16:36:58.798  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:36:58.799  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:36:58.800  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 16:36:58.800  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:36:58.802  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:36:58.804  2663  2673 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:36:58.805  2663  2815 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:36:58.807  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:36:58.807  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:36:58.808  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 16:36:58.808  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:36:58.808  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:36:58.811  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:36:58.811  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:36:58.812  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:36:58.812  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.812  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:36:58.813  2663  2694 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 16:36:58.813  2663  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:36:58.813  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:36:58.814  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:36:58.818  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:36:58.818  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.818  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.818  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.818  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.818  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:36:58.818  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.818  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.819  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.819  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:36:58.819  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.820  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 16:36:58.824  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:58.829  2663  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 16:36:58.829  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:58.832  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:36:58.835  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:36:58.837  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:36:58.837  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:36:58.837  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 16:36:58.837  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:36:58.837  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:58.837  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:36:58.838  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:36:58.838  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.840  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:58.841  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:58.842  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:36:58.842  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:36:58.847  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:36:58.847  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.847  2663  2694 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:36:58.848  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:36:58.849  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 16:36:58.849  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:36:58.854  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:36:58.854  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.854  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:36:58.854  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:36:58.854  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:36:58.854  2663  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:36:58.855  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:36:58.859  2663  2674 D BtGatt.GattService: registerClient() - UUID=78c837fe-5d73-40d6-bcf7-4b1995e92442
,09-09 16:36:58.859  2663  2691 D BtGatt.GattService: onClientRegistered() - UUID=78c837fe-5d73-40d6-bcf7-4b1995e92442, clientIf=5
,09-09 16:36:58.860  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:36:58.860  2663  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:36:58.860  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.861  2663  2673 D BtGatt.GattService: start scan with filters
,09-09 16:36:58.864  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:36:58.865  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 16:36:58.865  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:36:58.865  2663  2694 D BtGatt.ScanManager: handling starting scan
,09-09 16:36:58.865  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 16:36:58.870  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:36:58.870  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:36:58.870  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:36:58.871  2663  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:36:58.871  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.871  2663  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:36:58.873  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:36:58.876  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:36:58.877  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:36:58.877  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.877  2663  2694 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:36:58.877  2663  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:36:58.879  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.879  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:36:58.879  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.879  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:36:58.880  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.880  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:36:58.880  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:36:58.880  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:36:58.880  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:36:58.880  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:36:58.880  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:36:58.880  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:36:58.881  3777  3827 D BluetoothAdapter: STATE_ON
09-09 16:36:58.882  2663  2815 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:36:58.883  2663  2673 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:36:58.883  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:36:58.883  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:36:58.883  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 16:36:58.883  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:36:58.883  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:36:58.884  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.884  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:36:58.884  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:36:58.884  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:36:58.885  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:36:58.886  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.886  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.886  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.886  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.886  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:36:58.887  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.887  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.887  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:36:58.887  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.891  2663  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:36:58.891  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.887  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.891  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.892  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.892  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.893  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.893  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.893  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.893  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.894  3777  3827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 16:36:58.895  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:58.897  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:36:58.897  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:58.900  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:36:58.902  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:58.902  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:36:58.902  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:36:58.902  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 16:36:58.902  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 16:36:58.902  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:36:58.902  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:36:58.904  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:36:58.904  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.904  2663  2694 D BtGatt.ScanManager: stopping BLe Batch
09-09 16:36:58.904  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:58.906  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:58.907  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:36:58.907  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:36:58.910  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:36:58.910  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.911  2663  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 16:36:58.911  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:36:58.912  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:36:58.912  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:36:58.916  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:36:58.916  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:36:58.916  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:36:58.916  2663  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:36:58.916  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.916  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:36:58.919  2663  2807 D BtGatt.GattService: registerClient() - UUID=7d66386f-6041-4fe6-a40f-42872caaa19f
,09-09 16:36:58.919  2663  2691 D BtGatt.GattService: onClientRegistered() - UUID=7d66386f-6041-4fe6-a40f-42872caaa19f, clientIf=5
,09-09 16:36:58.919  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 16:36:58.920  2663  2815 D BtGatt.GattService: start scan with filters
,09-09 16:36:58.923  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:36:58.923  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:36:58.923  2663  2694 D BtGatt.ScanManager: handling starting scan
09-09 16:36:58.923  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:36:58.923  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 16:36:58.927  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:36:58.927  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:36:58.927  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:36:58.928  2663  2691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:36:58.928  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:36:58.929  2663  2694 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:36:58.929  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:36:58.931  3777  3827 I io.jxcore.node.ConnectionHelper: start: OK
09-09 16:36:58.931  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:36:58.931  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:36:58.931  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.931  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 16:36:58.931  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.931  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:36:58.931  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:36:58.931  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 16:36:58.931  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:36:58.931  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:36:58.932  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:36:58.932  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:36:58.933  3777  3827 D BluetoothAdapter: STATE_ON
09-09 16:36:58.933  2663  2674 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:36:58.933  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:36:58.934  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.934  2663  2694 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:36:58.934  2663  2694 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:36:58.934  2663  2673 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:36:58.934  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:36:58.934  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:36:58.934  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 16:36:58.934  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:36:58.934  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:36:58.935  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.935  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:36:58.935  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:36:58.936  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:36:58.936  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:36:58.937  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.937  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.937  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.937  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.937  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 16:36:58.937  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.937  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.937  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.937  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.937  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:36:58.937  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.938  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:36:58.938  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.938  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.938  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.938  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.938  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.939  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.939  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.939  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.939  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.940  3777  3827 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 16:36:58.940  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.940  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.940  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.940  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.940  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:36:58.941  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.941  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.941  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.941  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.941  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.941  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.941  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.941  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.941  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.942  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.942  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.942  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:36:58.942  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.943  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 16:36:58.944  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.944  2663  2691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:36:58.944  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.944  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.944  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:36:58.944  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.944  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.944  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.944  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.944  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.944  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.944  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.944  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.944  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.945  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.945  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.946  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.946  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.946  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.946  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.946  3777  3827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 16:36:58.946  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.947  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.947  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.947  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.947  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.947  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.947  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.947  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.947  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.947  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.947  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.947  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.947  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.947  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.948  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.948  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 16:36:58.948  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.948  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.949  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:36:58.949  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.949  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 16:36:58.949  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.949  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.949  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.950  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:36:58.950  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.950  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.950  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.950  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.950  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.950  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.950  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.950  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.950  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:36:58.950  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.951  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.951  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.951  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.951  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.952  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:36:58.952  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 16:36:58.952  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 16:36:58.952  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:36:58.952  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 16:36:58.952  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 16:36:58.953  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.953  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.953  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:36:58.953  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.953  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.953  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.953  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.953  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.953  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.953  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.953  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.953  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.953  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.953  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.954  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.954  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.954  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.954  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.955  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 16:36:58.955  3777  3827 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:36:58.955  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 16:36:58.956  2663  2691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:36:58.957  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.957  2663  2694 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:36:58.959  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:36:58.959  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 16:36:58.959  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-09 16:36:58.960  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 16:36:58.961  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 16:36:58.961  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 16:36:58.961  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:36:58.961  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 16:36:58.962  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:36:58.962  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:36:58.962  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 16:36:58.962  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:36:58.962  3777  3827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 16:36:58.962  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 16:36:58.964  2663  2691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:36:58.964  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.964  2663  2694 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:36:58.966  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 16:36:58.966  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 16:36:58.966  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 16:36:58.967  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 16:36:58.967  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 16:36:58.967  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 16:36:58.967  3777  3827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 16:36:58.968  3777  3827 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 16:36:58.968  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:36:58.968  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.968  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.968  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.969  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.969  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.969  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-09 16:36:58.969  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
,09-09 16:36:58.969  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.969  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.969  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.970  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.970  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.970  3777  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
09-09 16:36:58.970  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.970  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.970  2663  2691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 16:36:58.970  2663  2691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:36:58.971  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.971  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.971  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.971  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.972  3777  3827 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 16:36:58.972  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.972  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.973  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.973  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.973  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.973  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.973  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.973  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.973  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.973  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.973  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.973  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.973  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.973  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.974  3777  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
09-09 16:36:58.974  3777  3840 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
09-09 16:36:58.974  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.974  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.974  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.974  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.975  3777  3827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 16:36:58.975  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.975  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:36:58.975  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.975  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.975  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.975  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.976  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.976  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.976  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.976  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.976  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.976  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.976  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.976  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.977  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.977  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.977  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.977  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 16:36:58.978  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:36:58.978  3777  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 16:36:58.978  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:36:58.978  3777  3827 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 16:36:58.978  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 16:36:58.978  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 16:36:58.979  3777  3827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 16:36:58.979  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:36:58.979  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.979  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.979  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.979  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.979  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.979  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.979  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.979  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.979  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.979  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:36:58.979  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.979  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.979  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.981  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.981  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.981  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.981  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.982  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.982  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.982  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.982  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
,09-09 16:36:58.982  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.982  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.982  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.982  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.982  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.982  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.982  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.983  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.983  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.983  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.983  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
,09-09 16:36:58.983  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.983  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.983  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.983  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.983  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.983  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.983  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.983  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.983  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.983  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.983  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.983  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.984  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.984  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.985  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.985  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.985  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.985  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.986  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 16:36:58.986  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:58.987  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 16:36:58.988  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 16:36:58.988  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 16:36:58.988  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 16:36:58.988  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:36:58.988  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 16:36:58.989  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.989  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 16:36:58.989  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 16:36:58.989  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 16:36:58.989  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.989  3777  3827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 16:36:58.989  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.989  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 16:36:58.989  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.989  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:36:58.989  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:36:58.989  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:36:58.989  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.990  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.990  3777  3842 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:36:58.991  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.991  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:36:58.991  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.991  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:36:58.991  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.991  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:36:58.991  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.991  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.991  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.991  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.991  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.991  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.991  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.991  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:58.991  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.991  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.992  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.992  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.992  3777  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 16:36:58.992  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.992  3777  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 16:36:58.992  3777  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 16:36:58.992  3777  3777 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 16:36:58.992  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:36:58.993  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.993  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.993  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.994  3777  3827 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 16:36:58.994  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 16:36:58.994  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 16:36:58.994  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 16:36:58.994  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:58.994  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:58.994  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:58.994  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:58.994  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.995  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.995  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:58.995  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.995  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:58.995  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:58.995  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.995  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:58.995  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:58.995  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:58.996  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:58.996  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:58.997  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:58.997  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:59.000  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:59.000  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:36:59.000  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:59.000  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:36:59.000  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:59.000  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:59.000  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:59.000  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:59.000  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:59.000  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:59.000  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:36:59.000  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:59.000  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:59.001  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:59.001  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:59.001  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:59.001  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:59.001  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:59.002  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:36:59.002  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:36:59.002  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:36:59.002  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:36:59.002  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:59.003  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:59.003  3777  3827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f24daed not in the list
09-09 16:36:59.003  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:59.003  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
09-09 16:36:59.003  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:36:59.003  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:59.003  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:36:59.003  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:36:59.003  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:36:59.004  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:36:59.004  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:36:59.004  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:36:59.004  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db39d22 not in the list
,09-09 16:36:59.005  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 16:36:59.005  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:36:59.005  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 16:36:59.005  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 16:36:59.005  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-09 16:36:59.005  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 16:36:59.007  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 16:36:59.007  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 16:36:59.008  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 16:36:59.008  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 16:36:59.008  3777  3827 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 16:36:59.008  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 16:36:59.008  3777  3827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 16:36:59.008  3777  3827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 16:36:59.009  3777  3827 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 16:36:59.010  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:36:59.010  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4734734 added. We now have 2 listener(s)
09-09 16:36:59.010  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:36:59.012  3777  3827 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 16:36:59.012   871  1383 D WifiService: setWifiEnabled: true pid=3777, uid=10000
09-09 16:36:59.012   871  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-09 16:36:59.013  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:36:59.013  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aff595d added. We now have 3 listener(s)
09-09 16:36:59.013  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:36:59.021  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:36:59.021  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e192d2 added. We now have 4 listener(s)
09-09 16:36:59.021  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:36:59.023  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:36:59.023  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@933afa3 added. We now have 5 listener(s)
09-09 16:36:59.023  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:36:59.027   871  2068 D WifiService: setWifiEnabled: false pid=3777, uid=10000
09-09 16:36:59.027   871  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:36:59.032  2663  2687 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 16:36:59.032  2663  2687 D BluetoothAdapterProperties: Setting state to 13
09-09 16:36:59.032  2663  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 16:36:59.033  2663  2687 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 16:36:59.033  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:36:59.035  2663  2687 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:36:59.037  2663  2691 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:36:59.037  2663  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 16:36:59.038  2663  2663 D BluetoothMapService: onReceive
09-09 16:36:59.038  2663  2663 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:36:59.038  2663  2663 D BluetoothMapService: STATE_TURNING_OFF
09-09 16:36:59.039  2663  2663 D BluetoothMapService: MAP Service closeService in
,09-09 16:36:59.039  2663  2663 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 16:36:59.039  2663  2663 D ObexServerSockets0: shutdown(block = true)
09-09 16:36:59.040  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:59.040  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:36:59.041  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 16:36:59.041  2663  2663 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:36:59.041  2663  2804 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 16:36:59.042  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:36:59.042  2663  2816 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 16:36:59.042  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:59.042  2663  2817 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 16:36:59.042  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:36:59.044  2663  2663 I BtOppRfcommListener: stopping Accept Thread
,09-09 16:36:59.044  2663  3440 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 16:36:59.045  2663  3440 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 16:36:59.045  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.049  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:59.054  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:36:59.054  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:36:59.055  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:36:59.055  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:36:59.059  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:59.060   871   884 I ActivityManager: Start proc 3845:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 16:36:59.062  2663  2663 D HeadsetService: Received stop request...Stopping profile...
09-09 16:36:59.065  1365  1377 D BluetoothHeadset: Proxy object disconnected
09-09 16:36:59.065  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-09 16:36:59.065  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 16:36:59.066  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.066   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 16:36:59.066   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 16:36:59.066   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:36:59.066   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:36:59.069   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 16:36:59.069   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 16:36:59.070  1960  1971 D BluetoothHeadset: Proxy object disconnected
09-09 16:36:59.071   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 16:36:59.071  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.073   871  2183 D DhcpClient: Clearing IP address
09-09 16:36:59.073   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-09 16:36:59.074  2663  2663 D A2dpService: Received stop request...Stopping profile...
09-09 16:36:59.074  2663  2810 D A2dpStateMachine: Exit Disconnected: -1
09-09 16:36:59.076   372   869 D CommandListener: Setting iface cfg
09-09 16:36:59.076   871   871 D BluetoothA2dp: Proxy object disconnected
09-09 16:36:59.078  2663  2663 D HidService: Received stop request...Stopping profile...
09-09 16:36:59.078  2663  2663 D HidService: Stopping Bluetooth HidService
09-09 16:36:59.079  1365  1365 D BluetoothA2dp: Proxy object disconnected
09-09 16:36:59.079  1365  1365 D BluetoothInputDevice: Proxy object disconnected
09-09 16:36:59.079  1365  1365 D HidProfile: Bluetooth service disconnected
09-09 16:36:59.079  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.079  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.079  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.079  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:36:59.079  1511  2546 V NativeCrypto: Read error: ssl=0xaecc2600: I/O error during system call, Connection timed out
09-09 16:36:59.081  1511  2546 V NativeCrypto: SSL shutdown failed: ssl=0xaecc2600: I/O error during system call, Broken pipe
09-09 16:36:59.084   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 16:36:59.084   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 16:36:59.085   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 16:36:59.085  2663  2663 D HealthService: Received stop request...Stopping profile...
09-09 16:36:59.089   406   406 E Parcel  : Reading a NULL string not supported here.
09-09 16:36:59.089   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:36:59.091   871  2189 D DhcpClient: Receive thread stopped
09-09 16:36:59.092   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:36:59.094  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 16:36:59.094  2663  2663 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 16:36:59.095  2663  2663 D PanService: Received stop request...Stopping profile...
09-09 16:36:59.095   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 16:36:59.097  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 16:36:59.097  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:36:59.097  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:36:59.097  2663  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:36:59.097  2663  2691 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
09-09 16:36:59.099  2663  2663 D BluetoothMapService: Received stop request...Stopping profile...
09-09 16:36:59.099  2663  2663 D BluetoothMapService: stop()
09-09 16:36:59.102  2663  2663 D BluetoothMapAppObserver: deinitObservers()
09-09 16:36:59.102  2663  2663 D BluetoothMapAppObserver: removeReceiver()
09-09 16:36:59.102   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 16:36:59.105  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:36:59.105  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:36:59.105  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.105  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.105  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.105  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:36:59.106  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:36:59.106  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:36:59.106  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 16:36:59.106  2663  2663 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.106  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.107  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.107  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:36:59.107  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:36:59.107  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:36:59.107  2663  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:36:59.107  2663  2691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:36:59.107  2663  2788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 16:36:59.107  2663  2788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 16:36:59.107  2663  2788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:36:59.107  2663  2788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:36:59.107  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:36:59.107  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:36:59.107  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:36:59.108  2663  2691 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-09 16:36:59.108  2663  2663 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 16:36:59.108  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.108  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.108  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.108  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:36:59.108  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:36:59.108  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 16:36:59.108  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:36:59.108  2663  2663 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 16:36:59.109  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:36:59.109  1365  1365 D PanProfile: Bluetooth service disconnected
09-09 16:36:59.110  2663  2663 D BluetoothMapService: MAP Service closeService in
09-09 16:36:59.110  2663  2663 V BluetoothAdapterState: isTurningOff()=true
09-09 16:36:59.110  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.110  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.110  2663  2663 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:36:59.110  2663  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 16:36:59.110  2663  2687 D BluetoothAdapterProperties: Setting state to 15
09-09 16:36:59.110  2663  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 16:36:59.110  1365  1365 D BluetoothMap: Proxy object disconnected
09-09 16:36:59.111  1365  1365 D MapProfile: Bluetooth service disconnected
09-09 16:36:59.111   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:36:59.111  2663  2687 I BluetoothAdapterState: Entering BleOnState
09-09 16:36:59.111  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:36:59.111   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:36:59.111   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:36:59.112  1365  1376 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 16:36:59.112  2663  2663 D BluetoothMapService: cleanup()
09-09 16:36:59.112  2663  2663 D BluetoothMapService: MAP Service closeService in
09-09 16:36:59.113  1960  1970 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:36:59.113  1860  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 16:36:59.113   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 16:36:59.114  1365  2080 D BluetoothPan: onBluetoothStateChange on: false
09-09 16:36:59.116  1365  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:36:59.116   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:36:59.116  1365  1377 D BluetoothMap: onBluetoothStateChange: up=false
09-09 16:36:59.117  1365  2080 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 16:36:59.118  2663  2687 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 16:36:59.118  2663  2687 D BluetoothAdapterProperties: Setting state to 16
09-09 16:36:59.118  2663  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 16:36:59.118  2663  2687 D BluetoothAdapterProperties: onBleDisable
09-09 16:36:59.119  2663  2687 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:36:59.119  2663  2688 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:36:59.120  2663  2691 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:36:59.120  2663  2788 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 16:36:59.120  2663  2788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:36:59.120  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.121  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.122  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.123  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.136  3845  3845 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 16:36:59.141   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:36:59.157  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:36:59.157   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:36:59.158   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 16:36:59.158   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:36:59.165   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:36:59.165  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:36:59.168  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:36:59.168  3397  3397 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6490446 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-09 16:36:59.169  2031  2031 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-09 16:36:59.173  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:36:59.185   871  2068 I ActivityManager: Start proc 3863:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 16:36:59.192   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@186e72b:true
,09-09 16:36:59.205  3845  3845 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 16:36:59.209  3845  3845 D BluetoothMap: Create BluetoothMap proxy object
,09-09 16:36:59.221   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:36:59.225  3845  3845 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 16:36:59.230  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 16:36:59.239  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:36:59.249   871  2280 I ActivityManager: Killing 3204:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 16:36:59.320  2663  2691 I bt_hci  : shut_down
,09-09 16:36:59.321  2663  2695 D bt_hwcfg: hw_epilog_process
,09-09 16:36:59.322  2663  2695 I bt_vendor: low_power_mode_cb
,09-09 16:36:59.351  2663  2695 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 16:36:59.352  2663  2695 I bt_vendor: epilog_cb
,09-09 16:36:59.352  2663  2695 I bt_hci  : epilog_finished_callback
,09-09 16:36:59.361  2663  2691 I bt_hci_h4: hal_close
,09-09 16:36:59.362  2663  2691 I bt_userial_vendor: device fd = 51 close
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.391  3863  3863 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.391  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.392  3863  3863 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:36:59.392  3863  3863 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:36:59.440   871  2003 I ActivityManager: Start proc 3895:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 16:36:59.441   871  2003 I ActivityManager: Killing 3397:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 16:36:59.494  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:36:59.537  2663  2688 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:36:59.538  2663  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:36:59.539  3895  3895 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 16:36:59.542  2663  2663 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:36:59.542  2663  2687 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 16:36:59.542  2663  2663 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 16:36:59.542  2663  2663 D BtGatt.GattService: stop()
09-09 16:36:59.543  2663  2663 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:36:59.546  2663  2663 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:36:59.546  2663  2663 V BluetoothAdapterState: isTurningOn()=false
09-09 16:36:59.546  2663  2663 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:36:59.546  2663  2663 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 16:36:59.547  2663  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 16:36:59.548  2663  2687 D BluetoothAdapterProperties: Setting state to 10
09-09 16:36:59.548  2663  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 16:36:59.549  2663  2687 I BluetoothAdapterState: Entering OffState
,09-09 16:36:59.550   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 16:36:59.563  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:36:59.564  2663  2663 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 16:36:59.564  2663  2663 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:36:59.565  2663  2688 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:36:59.567  2663  2688 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:36:59.568  2663  2663 I art     : System.exit called, status: 0
,09-09 16:36:59.568  2663  2663 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:36:59.640   871  1689 I ActivityManager: Process com.android.bluetooth (pid 2663) has died
,09-09 16:36:59.672  3895  3895 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 16:36:59.691  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:36:59.707   871  1385 I ActivityManager: Start proc 3923:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-09 16:36:59.708  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:36:59.761  3863  3891 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 16:36:59.772  3923  3923 D AdapterServiceConfig: Adding HeadsetService
,09-09 16:36:59.772  3923  3923 D AdapterServiceConfig: Adding A2dpService
,09-09 16:36:59.772  3923  3923 D AdapterServiceConfig: Adding HidService
,09-09 16:36:59.772  3923  3923 D AdapterServiceConfig: Adding HealthService
,09-09 16:36:59.772  3923  3923 D AdapterServiceConfig: Adding PanService,
09-09 16:36:59.773  3923  3923 D AdapterServiceConfig: Adding GattService
09-09 16:36:59.773  3923  3923 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:36:59.775   871  2068 I ActivityManager: Killing 3588:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-09 16:36:59.787   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e5fc885:true
,09-09 16:36:59.815  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:36:59.849  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:36:59.854  1717  1717 D SystemUpdateService: onCreate
09-09 16:36:59.856  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:36:59.863  1717  3937 I SystemUpdateService: active receiver: enabled
,09-09 16:36:59.867  1717  3937 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:36:59.874  1717  3937 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 16:36:59.874  1717  3937 I SystemUpdateService: now status is 0 (complete)
09-09 16:36:59.874  1717  3937 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:36:59.874  1717  3937 I SystemUpdateService: file has been verified
09-09 16:36:59.874  1717  3937 I SystemUpdateService: OTA package size = 12249756
,09-09 16:36:59.878  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 16:36:59.880  1717  3937 I SystemUpdateService: showing system update notification
,09-09 16:36:59.882  1717  2522 I iu.UploadsManager: num queued entries: 0
,09-09 16:36:59.883  1717  2522 I iu.UploadsManager: num updated entries: 0
,09-09 16:36:59.886  1717  2522 I iu.SyncManager: NEXT; no task
,09-09 16:36:59.900  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:36:59.901  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:36:59.920   871   881 I ActivityManager: Start proc 3939:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 16:36:59.922  1717  1717 D SystemUpdateService: onDestroy
,09-09 16:36:59.963  3939  3939 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 16:36:59.965  3939  3939 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:36:59.973  3939  3939 D SprintDMHelper: simOperator: 
09-09 16:36:59.973  3939  3939 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:36:59.995   871  3907 I ActivityManager: Start proc 3951:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 16:36:59.996   871  3907 I ActivityManager: Killing 2776:com.android.providers.calendar/u0a3 (adj 15): empty #17,
,09-09 16:37:00.154   871  1690 I ActivityManager: Start proc 3966:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 16:37:00.157   871  1972 I ActivityManager: Killing 1704:android.process.acore/u0a5 (adj 15): empty #17
,09-09 16:37:00.236  3966  3966 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 16:37:00.294  3966  3966 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 16:37:00.294  3966  3966 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:37:00.294  3966  3966 I GAv4    :   adb logcat -s GAv4
,09-09 16:37:00.307  3966  3966 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:37:00.313  3966  3966 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:37:00.337  3966  3984 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:37:00.441  3966  3966 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 16:37:00.474  3966  3966 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 16:37:00.481  3966  3966 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3884-3887)
,09-09 16:37:00.481  3966  3966 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 16:37:00.493  3966  3966 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b810af6}
,09-09 16:37:00.494  3966  3966 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 16:37:00.494  3966  3966 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:37:00.502  3966  3966 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 16:37:00.503  3966  3966 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:37:00.521  3966  3966 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 16:37:00.532  3966  3966 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 16:37:00.532  3966  3966 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:37:00.532  3966  3966 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:37:00.532  3966  3966 I Adreno  : Build Date                       : 10/20/15
09-09 16:37:00.532  3966  3966 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:37:00.532  3966  3966 I Adreno  : Local Branch                     : M14
09-09 16:37:00.532  3966  3966 I Adreno  : Remote Branch                    : 
09-09 16:37:00.532  3966  3966 I Adreno  : Remote Branch                    : 
09-09 16:37:00.532  3966  3966 I Adreno  : Reconstruct Branch               : 
,09-09 16:37:00.586  3966  3966 I NSApplication: Starting up...
,09-09 16:37:00.596  3966  4013 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 16:37:00.618   871  1690 I ActivityManager: Start proc 4018:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 16:37:00.620   871  1690 I ActivityManager: Killing 3663:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 16:37:00.709  4018  4018 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 16:37:00.899   871  2003 I ActivityManager: Killing 3678:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 16:37:02.045   871  1385 D WifiService: setWifiEnabled: true pid=3777, uid=10000
,09-09 16:37:02.045   871  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:37:02.065   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:37:02.071  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:02.072  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:02.072  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:37:02.072  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:02.076  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:02.076  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:02.076  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:02.077  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:02.098   871  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-09 16:37:02.099   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 16:37:02.100   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 16:37:02.101   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 16:37:02.101   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 16:37:02.101   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 16:37:02.101   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:37:02.116   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 16:37:02.116   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.88 rxSuccessRate=26.38 delta 1000 -> 994
09-09 16:37:02.117   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:02.118   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 16:37:02.119   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 16:37:02.125   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 16:37:02.126   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:02.133   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:37:02.191   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:37:02.191   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:37:02.241   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:37:02.244  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:37:02.729  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 16:37:02.814  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:37:02.816  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 16:37:02.825   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:37:02.846   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:37:02.846   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:02.846   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 16:37:02.866   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:02.877   372   869 D CommandListener: Setting iface cfg
09-09 16:37:02.878   871  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 16:37:02.904   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:37:02.904   871  1308 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-09 16:37:02.906   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:37:02.911   871  4041 D DhcpClient: Receive thread started
,09-09 16:37:02.997   871  1306 E native  : do suspend false
,09-09 16:37:03.018   871  2183 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:37:03.031   871  4041 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,09-09 16:37:03.032   871  2183 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,09-09 16:37:03.036   871  2183 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 16:37:03.048   871  4041 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 16:37:03.050   871  2183 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 16:37:03.055   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:03.068   871  2183 D DhcpClient: Scheduling renewal in 86399s
,09-09 16:37:03.070   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:37:03.080   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 16:37:03.081   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 16:37:03.082   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-09 16:37:03.084   871  1308 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 16:37:03.090   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 16:37:03.158   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 16:37:03.158   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 16:37:03.162   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 16:37:03.166   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 16:37:03.177   871  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 16:37:03.186   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 16:37:03.192   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 16:37:03.192   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-09 16:37:03.192   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 16:37:03.193   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:37:03.193   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 16:37:03.193   871  1308 D ConnectivityService:    accepting network in place of null
,09-09 16:37:03.195   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -61]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:37:03.210   871  4040 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136616, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:37:03.249   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:03.283   871  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 16:37:03.302   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:03.307   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 16:37:03.307   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:03.311   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 16:37:03.314   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:37:03.321  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:03.321  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:37:03.321  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:03.321  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:03.324  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:03.324  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:03.324  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:03.324  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:03.339  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:37:03.341  2031  2031 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-09 16:37:03.343  1717  1717 D SystemUpdateService: onCreate
,09-09 16:37:03.346  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:37:03.349  1717  4051 I SystemUpdateService: active receiver: enabled
,09-09 16:37:03.351  1717  4051 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:37:03.356  1717  4051 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 16:37:03.356  1717  4051 I SystemUpdateService: now status is 0 (complete)
09-09 16:37:03.356  1717  4051 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:37:03.356  1717  4051 I SystemUpdateService: file has been verified
09-09 16:37:03.356  1717  4051 I SystemUpdateService: OTA package size = 12249756
,09-09 16:37:03.363  1717  4051 I SystemUpdateService: showing system update notification
,09-09 16:37:03.363   871  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:37:03 GMT], X-Android-Received-Millis=[1473431823363], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473431823326]}
,09-09 16:37:03.366   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 16:37:03.366   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 16:37:03.366   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 16:37:03.367   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 16:37:03.369  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:37:03.372  1717  2522 I iu.UploadsManager: num queued entries: 0
,09-09 16:37:03.372  1717  2522 I iu.UploadsManager: num updated entries: 0
09-09 16:37:03.373  1717  2522 I iu.SyncManager: NEXT; no task
,09-09 16:37:03.378  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:37:03.380  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:37:03.379  1717  4055 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 16:37:03.380  1717  4055 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 16:37:03.383  1717  4055 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:37:03.387  3939  3939 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:03.388  1717  1717 D SystemUpdateService: onDestroy
,09-09 16:37:03.390  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:03.393  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:03.397  3939  3939 D SprintDMHelper: simOperator: 
09-09 16:37:03.398  3939  3939 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:37:03.404   871   883 I ActivityManager: Start proc 4058:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-09 16:37:03.433  4058  4058 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
09-09 16:37:03.435  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 16:37:03.435  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 16:37:03.435  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:03.436  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:03.454  1717  4055 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-09 16:37:03.508  4058  4058 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 16:37:03.516  4058  4058 I BooksApp: Created application version: 3.6.9 (30609)
,09-09 16:37:03.518  2135  4070 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:37:03.561  1511  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:37:03.561  1511  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:37:03.561  1511  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:03.561  1511  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:03.581  3546  4073 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 16:37:03.581  3546  4073 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at blb.a(PG:3937)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at czp.a(PG:18188)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:37:03.581  3546  4073 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	... 12 more
09-09 16:37:03.581  3546  4073 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at fal.a(PG:38)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:37:03.581  3546  4073 E HttpOperation: 	... 14 more
,09-09 16:37:03.607  4058  4084 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 16:37:03.623  1511  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 16:37:03.623  1511  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 16:37:03.624  1511  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:03.624  1511  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:03.642  3546  4073 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 16:37:03.642  3546  4073 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jdm.a(PG:82)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jcs.o(PG:406)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jcn.a(PG:1379)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jcs.i(PG:143)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at hec.a(PG:42)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at hee.a(PG:102)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at czr.a(PG:65)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at kka.a(PG:108)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at czp.a(PG:19176)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at czp.a(PG:9081)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at czq.run(PG:1686)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:37:03.642  3546  4073 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jdj.a(PG:4091)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jdj.a(PG:1125)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jdm.a(PG:77)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	... 15 more
09-09 16:37:03.642  3546  4073 E HttpOperation: Caused by: faj: BadAuthentication
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at fal.a(PG:38)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	at jdj.a(PG:4089)
09-09 16:37:03.642  3546  4073 E HttpOperation: 	... 17 more
09-09 16:37:03.643  3546  4073 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 16:37:03.643  3546  4073 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at hec.a(PG:42)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at hee.a(PG:102)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at czr.a(PG:65)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at kka.a(PG:108)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	... 15 more
09-09 16:37:03.643  3546  4073 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at fal.a(PG:38)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 16:37:03.643  3546  4073 E ExperimentLoader: 	... 17 more
,09-09 16:37:03.764   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130425, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:37:03.778  4058  4092 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 16:37:03.830  1511  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:37:03.830  1511  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 16:37:03.830  1511  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:03.830  1511  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:03.878  1511  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 16:37:03.879  1511  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 16:37:03.879  1511  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:03.879  1511  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:03.906  4058  4092 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 16:37:03.909  4058  4084 E BooksSync: Soft error
09-09 16:37:03.909  4058  4084 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:37:03.909  4058  4084 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 16:37:03.910  4058  4084 E BooksSync: Sync error
09-09 16:37:03.910  4058  4084 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 16:37:03.910  4058  4084 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 16:37:03.910  4058  4084 I BooksSync: Finished books sync
,09-09 16:37:03.918   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130108, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 16:37:03.918   871  1972 I ActivityManager: Killing 3422:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 16:37:04.308   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 16:37:04.768   871  2068 I ActivityManager: Killing 3705:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 16:37:05.051   871  1691 D WifiService: setWifiEnabled: false pid=3777, uid=10000
09-09 16:37:05.051   871  1691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:37:05.077  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 16:37:05.080   871  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 16:37:05.081   871  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 16:37:05.081   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:37:05.081   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:05.098   871  2183 D DhcpClient: Clearing IP address
,09-09 16:37:05.098   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-09 16:37:05.101   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:05.105  1511  4081 V NativeCrypto: Read error: ssl=0x9b3d0400: I/O error during system call, Connection timed out
,09-09 16:37:05.111  1511  4081 V NativeCrypto: SSL shutdown failed: ssl=0x9b3d0400: I/O error during system call, Broken pipe
,09-09 16:37:05.117   871   882 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-09 16:37:05.118   871  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-09 16:37:05.119   871  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-09 16:37:05.119   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 16:37:05.119   871  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 16:37:05.119   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-09 16:37:05.119   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 16:37:05.131   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-09 16:37:05.133   871  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-09 16:37:05.135   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 16:37:05.135   871  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-09 16:37:05.137   871  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 16:37:05.140  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:05.140  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 16:37:05.140  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:05.140  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:05.141  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:05.141  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:05.141  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:05.141  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:05.141   406   406 E Parcel  : Reading a NULL string not supported here.
09-09 16:37:05.147  1860  2288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 16:37:05.154   871  4041 D DhcpClient: Receive thread stopped
,09-09 16:37:05.181   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:05.200   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:05.201   871  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 16:37:05.201   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:05.203   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:37:05.218  2031  2031 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-09 16:37:05.219  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:05.219  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:05.220  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:05.220  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:05.227  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:37:05.231  1717  1717 D SystemUpdateService: onCreate
,09-09 16:37:05.233  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:37:05.237  1717  4101 I SystemUpdateService: active receiver: enabled
,09-09 16:37:05.248  1717  4101 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:37:05.250  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 16:37:05.258  1717  4101 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 16:37:05.258  1717  4101 I SystemUpdateService: now status is 0 (complete)
,09-09 16:37:05.258  1717  4101 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:37:05.258  1717  4101 I SystemUpdateService: file has been verified
09-09 16:37:05.258  1717  4101 I SystemUpdateService: OTA package size = 12249756
,09-09 16:37:05.269  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:37:05.270  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:37:05.272  3939  3939 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:05.276  3939  3939 D SprintDMHelper: simOperator: 
,09-09 16:37:05.276  3939  3939 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-09 16:37:05.276  1717  2522 I iu.UploadsManager: num queued entries: 0
,09-09 16:37:05.277  1717  2522 I iu.UploadsManager: num updated entries: 0
,09-09 16:37:05.289   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-09 16:37:05.291   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 16:37:05.301  2135  4105 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 16:37:05.305  1717  4101 I SystemUpdateService: showing system update notification
,09-09 16:37:05.306  1717  2522 I iu.SyncManager: NEXT; no task
,09-09 16:37:05.319  3966  3966 I art     : Waiting for a blocking GC DisableMovingGc
,09-09 16:37:05.321  3966  3966 I art     : Starting a blocking GC DisableMovingGc
,09-09 16:37:05.345  1717  1717 D SystemUpdateService: onDestroy
,09-09 16:37:08.087  3923  3923 D BluetoothAdapterState: make() - Creating AdapterState
09-09 16:37:08.087   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2490444:true
,09-09 16:37:08.092  3923  3923 I bt_bluedroid: init
,09-09 16:37:08.093  3923  4108 I BluetoothAdapterState: Entering OffState
,09-09 16:37:08.098  3923  4109 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:37:08.099  3923  4109 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 16:37:08.099  3923  4109 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 16:37:08.100  3923  4109 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 16:37:08.101  3923  3923 I bt_bluedroid: get_profile_interface socket
,09-09 16:37:08.104  3923  3923 I bt_bluedroid: get_profile_interface sdp
,09-09 16:37:08.107  3923  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:37:08.110  3923  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:37:08.110  3923  3934 I bt_bluedroid: config_hci_snoop_log
,09-09 16:37:08.112   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 16:37:08.120  3923  4108 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 16:37:08.120  3923  4108 D BluetoothAdapterProperties: Setting state to 14
,09-09 16:37:08.121  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 16:37:08.123  3923  4108 D BluetoothBondStateMachine: make
,09-09 16:37:08.126  3923  4113 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:37:08.131  3923  4108 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:37:08.131  3923  3923 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:37:08.135  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:08.135  3923  3923 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:37:08.136  3923  3923 D BtGatt.GattService: Received start request. Starting profile...
09-09 16:37:08.136  3923  3923 D BtGatt.GattService: start()
09-09 16:37:08.136  3923  3923 I bt_bluedroid: get_profile_interface gatt
09-09 16:37:08.137  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:08.137  3923  3923 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:37:08.143  3923  3923 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:08.143  3923  3923 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:37:08.143  3923  3923 V BluetoothAdapterState: isBleTurningOn()=true
09-09 16:37:08.143  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:08.143  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 16:37:08.143  3923  4108 I bt_bluedroid: enable
09-09 16:37:08.144  3923  4109 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 16:37:08.144  3923  4109 I bt_hci  : start_up
,09-09 16:37:08.158  3923  4109 I bt_vendor: alloc value 0xb39e9189
09-09 16:37:08.158  3923  4109 I bt_vendor: init
,09-09 16:37:08.158  3923  4109 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-09 16:37:08.158  3923  4109 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:37:08.266  3923  4109 D bt_hci  : start_up starting async portion
,09-09 16:37:08.266  3923  4116 I bt_hci  : event_finish_startup
,09-09 16:37:08.267  3923  4116 I bt_hci_h4: hal_open
09-09 16:37:08.267  3923  4116 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 16:37:08.279  3923  4116 I bt_userial_vendor: device fd = 51 open
,09-09 16:37:08.308  3923  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:37:08.340  3923  4116 D bt_hwcfg: Chipset BCM4354A2
09-09 16:37:08.340  3923  4116 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 16:37:08.341  3923  4116 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:37:08.500  4058  4080 I art     : Waiting for a blocking GC DisableMovingGc
,09-09 16:37:08.508  4058  4080 I art     : WaitForGcToComplete blocked for 7.442ms for cause DisableMovingGc
,09-09 16:37:08.508  4058  4080 I art     : Starting a blocking GC DisableMovingGc
,09-09 16:37:08.520  4058  4080 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 16:37:08.965  3923  4116 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 16:37:08.967  3923  4116 D bt_hwcfg: Settlement delay -- 100 ms
09-09 16:37:08.967  3923  4116 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:37:09.084  3923  4116 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:37:09.085  3923  4116 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:37:09.114  3923  4116 I bt_hwcfg: vendor lib fwcfg completed
09-09 16:37:09.115  3923  4116 I bt_vendor: firmware callback
,09-09 16:37:09.115  3923  4116 I bt_hci  : firmware_config_callback
,09-09 16:37:09.126  3923  4120 I bt_btu  : btu_task pending for preload complete event
,09-09 16:37:09.126  3923  4120 I bt_btu_task: Bluetooth chip preload is complete
09-09 16:37:09.126  3923  4120 I bt_btu  : btu_task received preload complete event
,09-09 16:37:09.136  3923  4120 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 16:37:09.136  3923  4120 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 16:37:09.137  3923  4120 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 16:37:09.137  3923  4120 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 16:37:09.137  3923  4120 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 16:37:09.138  3923  4120 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:37:09.138  3923  4120 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 16:37:09.138  3923  4120 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 16:37:09.138  3923  4120 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:37:09.139  3923  4120 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 16:37:09.139  3923  4120 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:37:09.139  3923  4120 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 16:37:09.139  3923  4120 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:37:09.140  3923  4120 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:37:09.140  3923  4120 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:37:09.275  3923  4120 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,09-09 16:37:09.275  3923  4120 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,09-09 16:37:09.296  3923  4112 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 16:37:09.298  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:37:09.298  3923  4112 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:37:09.301  3923  4112 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:37:09.304  3923  4112 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:37:09.304  3923  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:37:09.305  3923  4112 D bt_hci  : do_postload posting postload work item
,09-09 16:37:09.305  3923  4116 I bt_hci  : event_postload
09-09 16:37:09.305  3923  4116 I bt_vendor: sco_config_cb
09-09 16:37:09.306  3923  4116 I bt_hci  : sco_config_callback postload finished.
,09-09 16:37:09.310  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:09.313  3923  4112 D bt_bte_conf: Device ID record 1 : primary
09-09 16:37:09.314  3923  4112 D bt_bte_conf:   vendorId            = 000f
,09-09 16:37:09.314  3923  4112 D bt_bte_conf:   vendorIdSource      = 0001
09-09 16:37:09.314  3923  4112 D bt_bte_conf:   product             = 1200
09-09 16:37:09.315  3923  4112 D bt_bte_conf:   version             = 1436
09-09 16:37:09.316  3923  4112 D bt_bte_conf:   clientExecutableURL = 
,09-09 16:37:09.316  3923  4116 I bt_vendor: low_power_mode_cb
09-09 16:37:09.316  3923  4112 D bt_bte_conf:   serviceDescription  = 
09-09 16:37:09.316  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:09.317  3923  4112 D bt_bte_conf:   documentationURL    = 
,09-09 16:37:09.317  3923  4112 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 16:37:09.318  3923  4109 D bt_stack_manager: event_start_up_stack finished
,09-09 16:37:09.318  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 16:37:09.319  3923  4108 D BluetoothAdapterProperties: Setting state to 15
,09-09 16:37:09.319  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 16:37:09.320  3923  4108 I BluetoothAdapterState: Entering BleOnState
,09-09 16:37:09.324  3923  4108 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 16:37:09.324  3923  4108 D BluetoothAdapterProperties: Setting state to 11
,09-09 16:37:09.324  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-09 16:37:09.332  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:09.334  3923  3923 D HeadsetService: Received start request. Starting profile...
09-09 16:37:09.340  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:09.341  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:09.342  3923  3923 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 16:37:09.343  3923  3923 D HeadsetStateMachine: make
,09-09 16:37:09.350  3923  4108 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:37:09.355  3923  3923 D HeadsetStateMachine: max_hf_connections = 1
09-09 16:37:09.355  3923  3923 I bt_bluedroid: get_profile_interface handsfree
09-09 16:37:09.356  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 16:37:09.356  3923  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 16:37:09.362  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:09.363  3923  3923 D A2dpService: Received start request. Starting profile...
09-09 16:37:09.363  3923  3923 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 16:37:09.364  3923  3923 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:37:09.372  3923  3923 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 16:37:09.372  3923  3923 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 16:37:09.372  3923  3923 D A2dpStateMachine: make
09-09 16:37:09.373  3923  3923 I bt_bluedroid: get_profile_interface a2dp
09-09 16:37:09.374  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 16:37:09.378  3923  4129 D A2dpStateMachine: Enter Disconnected: -2
,09-09 16:37:09.378  3923  3923 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 16:37:09.379  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:09.380  3923  3923 D HidService: Received start request. Starting profile...
09-09 16:37:09.380  3845  3845 D BluetoothInputDevice: Proxy object connected
,09-09 16:37:09.381  3923  3923 I bt_bluedroid: get_profile_interface hidhost
,09-09 16:37:09.381  3923  4112 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
09-09 16:37:09.381  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 16:37:09.381  3923  3923 D HidService: setHidService(): set to: null
,09-09 16:37:09.381  3845  3845 D HidProfile: Bluetooth service connected
09-09 16:37:09.382  3923  3923 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 16:37:09.382  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:09.383  3923  3923 D HealthService: Received start request. Starting profile...
09-09 16:37:09.384  3923  3923 I bt_bluedroid: get_profile_interface health
,09-09 16:37:09.385  3923  3923 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:37:09.385  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:09.386  3845  3845 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:37:09.386  3923  3923 D PanService: Received start request. Starting profile...
09-09 16:37:09.387  3923  3923 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 16:37:09.387  3923  3923 I bt_bluedroid: get_profile_interface pan
,09-09 16:37:09.387  3845  3845 D PanProfile: Bluetooth service connected
09-09 16:37:09.387  3923  4112 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 16:37:09.394  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:37:09.399  3923  3923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:09.400  3923  3923 D BluetoothMapService: Received start request. Starting profile...
,09-09 16:37:09.400  3845  3845 D BluetoothMap: Proxy object connected
09-09 16:37:09.400  3923  3923 D BluetoothMapService: start()
09-09 16:37:09.400  3845  3845 D MapProfile: Bluetooth service connected
09-09 16:37:09.401  3845  3845 D BluetoothMap: getConnectedDevices()
,09-09 16:37:09.401  3845  3845 D BluetoothMap: Bluetooth is Not enabled
,09-09 16:37:09.402  3923  3923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 16:37:09.403  3923  3923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 16:37:09.403  3923  3923 D BluetoothMapAppObserver: createReceiver()
,09-09 16:37:09.404  3923  3923 D BluetoothMapAppObserver: initObservers()
09-09 16:37:09.404  3923  3923 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:37:09.411  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:09.411  3923  3923 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:09.411  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:09.411  3923  4127 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:37:09.411  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:09.413  3923  3923 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:09.414  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:09.415  3923  3923 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:09.415  3923  3923 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:37:09.415  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:09.415  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:09.415  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 16:37:09.415  3923  4108 D BluetoothAdapterProperties: ScanMode =  20
09-09 16:37:09.415  3923  4108 D BluetoothAdapterProperties: State =  11
09-09 16:37:09.416  3923  4108 D BluetoothAdapterProperties: Setting state to 12
,09-09 16:37:09.416  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 16:37:09.416  3923  4108 I BluetoothAdapterState: Entering OnState
09-09 16:37:09.416  3845  3857 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:37:09.417   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:37:09.417  1365  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:37:09.419  3923  4112 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:37:09.419  3923  4112 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 16:37:09.420   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:09.420  3845  3855 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:37:09.420   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 16:37:09.420  1365  2080 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:37:09.420  1365  1365 D BluetoothA2dp: Proxy object connected
09-09 16:37:09.421  1960  2283 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:09.422  3845  3857 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:09.423  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:09.423  1365  1376 D BluetoothPan: onBluetoothStateChange on: true
09-09 16:37:09.425  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:37:09.425  3845  3855 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:37:09.425  1365  1365 D PanProfile: Bluetooth service connected
09-09 16:37:09.425  1365  2080 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:09.425  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:09.425   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:37:09.426  1365  1376 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 16:37:09.426   871   871 D BluetoothA2dp: Proxy object connected
09-09 16:37:09.427  1365  1365 D BluetoothMap: Proxy object connected
,09-09 16:37:09.427  1365  1365 D MapProfile: Bluetooth service connected
09-09 16:37:09.427  1365  1365 D BluetoothMap: getConnectedDevices()
09-09 16:37:09.428  1365  2080 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:09.428  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:09.430  3923  3923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:37:09.430  3923  3923 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 16:37:09.431   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 16:37:09.432  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:09.433  3923  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:37:09.433  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:09.434  1365  1365 D BluetoothInputDevice: Proxy object connected
09-09 16:37:09.434  1365  1365 D HidProfile: Bluetooth service connected
09-09 16:37:09.435  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:09.436  3845  3845 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-09 16:37:09.436  3923  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:37:09.437  3923  3923 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:37:09.437  3923  3923 D ObexServerSockets0: startAccept()
,09-09 16:37:09.438  3923  3923 D ObexServerSockets0: prepareForNewConnect()
09-09 16:37:09.439  3923  3923 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 16:37:09.439  3923  3923 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 16:37:09.440  3923  3923 D BluetoothMapService: onReceive
09-09 16:37:09.440  3923  3923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:37:09.440  3923  3923 D BluetoothMapService: STATE_ON
09-09 16:37:09.440  3923  4137 D ObexServerSockets0: Accepting socket connection...
09-09 16:37:09.440  3923  4136 D ObexServerSockets0: Accepting socket connection...
09-09 16:37:09.441  3845  3845 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-09 16:37:09.445  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:37:09.448  3845  3845 D BluetoothA2dp: Proxy object connected
,09-09 16:37:09.453  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:37:09.458  1365  1365 D BluetoothPbap: Proxy object connected
,09-09 16:37:09.458  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-09 16:37:09.463  3923  3923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 16:37:09.463  3923  3923 D ObexServerSockets0: prepareForNewConnect()
09-09 16:37:09.465  3923  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:37:09.473  3845  3845 D DockEventReceiver: finishStartingService: stopping service
09-09 16:37:09.473  3845  3845 D BluetoothPbap: Proxy object connected
09-09 16:37:09.474  3845  3845 D PbapServerProfile: Bluetooth service connected
,09-09 16:37:09.477  3923  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:37:09.478  3923  4145 I BtOppRfcommListener: Accept thread started.
,09-09 16:37:09.518  1365  1377 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.518   871   871 D BluetoothHeadset: Proxy object connected
09-09 16:37:09.518  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:09.518   871   871 D BluetoothHeadset: Proxy object connected
09-09 16:37:09.518  1960  1971 D BluetoothHeadset: Proxy object connected
09-09 16:37:09.518   871   871 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.520   871   888 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.521   871   888 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.521  1960  2107 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.526  1365  2080 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.526  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:09.542  3845  3857 D BluetoothHeadset: Proxy object connected
,09-09 16:37:09.543  3845  3845 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:10.056  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:10.068  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:10.070  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:10.096  1511  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 16:37:10.096  1511  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 16:37:10.096  1511  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:10.096  1511  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:10.114  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 16:37:10.114  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 16:37:10.115  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 16:37:11.071  3923  4108 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 16:37:11.072  3923  4108 D BluetoothAdapterProperties: Setting state to 13
09-09 16:37:11.072  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 16:37:11.074  3923  4108 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 16:37:11.080  3923  4108 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:37:11.086  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:11.086  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:11.086  3923  3923 D BluetoothMapService: onReceive
09-09 16:37:11.086  3923  3923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:37:11.086  3923  3923 D BluetoothMapService: STATE_TURNING_OFF
09-09 16:37:11.087  3923  3923 D BluetoothMapService: MAP Service closeService in
09-09 16:37:11.087  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:11.087  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:11.087  3923  3923 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 16:37:11.090  3923  3923 D ObexServerSockets0: shutdown(block = true)
,09-09 16:37:11.095  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:11.095  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:11.095  3923  3923 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:37:11.096  3923  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 16:37:11.096  3923  3923 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 16:37:11.096  3923  4137 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 16:37:11.097  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 16:37:11.097  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:11.097  3923  3923 I BtOppRfcommListener: stopping Accept Thread
,09-09 16:37:11.098  3923  4122 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 16:37:11.098  3923  4145 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 16:37:11.099  3923  4145 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 16:37:11.101  3923  4112 D BluetoothAdapterProperties: Scan Mode:20
,09-09 16:37:11.101  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-09 16:37:11.104  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:11.104  3923  3923 D HeadsetService: Received stop request...Stopping profile...
09-09 16:37:11.105  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:11.105  1365  1377 D BluetoothHeadset: Proxy object disconnected
09-09 16:37:11.106   871   871 D BluetoothHeadset: Proxy object disconnected
,09-09 16:37:11.106   871   871 D BluetoothHeadset: Proxy object disconnected
09-09 16:37:11.106  1960  1970 D BluetoothHeadset: Proxy object disconnected
,09-09 16:37:11.107   871   871 D BluetoothHeadset: Proxy object disconnected
,09-09 16:37:11.107  3923  3923 D A2dpService: Received stop request...Stopping profile...
09-09 16:37:11.107  3845  3855 D BluetoothHeadset: Proxy object disconnected
,09-09 16:37:11.107  3923  4129 D A2dpStateMachine: Exit Disconnected: -1
09-09 16:37:11.109   871   871 D BluetoothA2dp: Proxy object disconnected
09-09 16:37:11.110  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.110  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.110  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:11.110  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:11.110  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 16:37:11.111  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-09 16:37:11.111  3923  3923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 16:37:11.111  1365  1365 D BluetoothA2dp: Proxy object disconnected
09-09 16:37:11.111  3923  3923 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 16:37:11.112  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 16:37:11.112  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:37:11.112  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:37:11.112  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 16:37:11.112  3923  4112 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 16:37:11.113  3923  3923 D HidService: Received stop request...Stopping profile...
09-09 16:37:11.113  3923  3923 D HidService: Stopping Bluetooth HidService
09-09 16:37:11.115  3845  3845 D HeadsetProfile: Bluetooth service disconnected
09-09 16:37:11.115  3845  3845 D BluetoothA2dp: Proxy object disconnected
09-09 16:37:11.116  3923  3923 D HealthService: Received stop request...Stopping profile...
09-09 16:37:11.116  1365  1365 D BluetoothInputDevice: Proxy object disconnected
,09-09 16:37:11.116  1365  1365 D HidProfile: Bluetooth service disconnected
09-09 16:37:11.118  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.118  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.118  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:11.118  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:11.119  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:37:11.119  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:37:11.120  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:37:11.120  3923  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:37:11.120  3923  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:37:11.120  3923  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 16:37:11.120  3923  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 16:37:11.120  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-09 16:37:11.120  3923  3923 D PanService: Received stop request...Stopping profile...
09-09 16:37:11.121  3845  3845 D BluetoothInputDevice: Proxy object disconnected
09-09 16:37:11.121  3845  3845 D HidProfile: Bluetooth service disconnected
,09-09 16:37:11.123  3923  3923 D BluetoothMapService: Received stop request...Stopping profile...
09-09 16:37:11.123  3923  3923 D BluetoothMapService: stop()
,09-09 16:37:11.124  3845  3845 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:37:11.124  3845  3845 D PanProfile: Bluetooth service disconnected
09-09 16:37:11.124  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 16:37:11.125  1365  1365 D PanProfile: Bluetooth service disconnected
09-09 16:37:11.127  3923  3923 D BluetoothMapAppObserver: deinitObservers()
,09-09 16:37:11.127  3923  3923 D BluetoothMapAppObserver: removeReceiver()
,09-09 16:37:11.128  1365  1365 D BluetoothMap: Proxy object disconnected
09-09 16:37:11.128  1365  1365 D MapProfile: Bluetooth service disconnected
09-09 16:37:11.129  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.129  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.129  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:11.130  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:11.130  3923  3923 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 16:37:11.130  3923  3923 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 16:37:11.130  3923  4112 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 16:37:11.130  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.130  3923  3923 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:37:11.130  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:11.130  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:11.131  3845  3845 D BluetoothMap: Proxy object disconnected
,09-09 16:37:11.131  3845  3845 D MapProfile: Bluetooth service disconnected
09-09 16:37:11.132  3923  3923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 16:37:11.132  3923  4112 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 16:37:11.132  3923  3923 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 16:37:11.133  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.133  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.133  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:11.133  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:11.133  3923  3923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 16:37:11.134  3923  3923 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 16:37:11.134  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:37:11.135  3923  3923 D BluetoothMapService: MAP Service closeService in
09-09 16:37:11.135  3923  3923 V BluetoothAdapterState: isTurningOff()=true
09-09 16:37:11.135  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.135  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:11.135  3923  3923 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:11.136  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-09 16:37:11.136  3923  4108 D BluetoothAdapterProperties: Setting state to 15
09-09 16:37:11.136  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 16:37:11.137  3923  4108 I BluetoothAdapterState: Entering BleOnState
,09-09 16:37:11.137  3845  3857 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 16:37:11.137  3923  3923 D BluetoothMapService: cleanup()
09-09 16:37:11.137  3923  3923 D BluetoothMapService: MAP Service closeService in
09-09 16:37:11.138   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:37:11.139  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:37:11.140   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:37:11.140  3845  3855 D BluetoothPan: onBluetoothStateChange on: false
,09-09 16:37:11.141  1365  1365 D BluetoothPbap: Proxy object disconnected
,09-09 16:37:11.141  1365  1365 D PbapServerProfile: Bluetooth service disconnected
09-09 16:37:11.142   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:37:11.143  1365  1377 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 16:37:11.146  1960  2283 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 16:37:11.147  3845  3857 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:37:11.148  3845  3845 D BluetoothPbap: Proxy object disconnected
09-09 16:37:11.148  3845  3845 D PbapServerProfile: Bluetooth service disconnected
09-09 16:37:11.149  3845  3855 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 16:37:11.150  1365  2080 D BluetoothPan: onBluetoothStateChange on: false
09-09 16:37:11.150  3845  3857 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:37:11.151  3845  3855 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 16:37:11.151  1365  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 16:37:11.151   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 16:37:11.152  1365  1377 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 16:37:11.152  1365  2080 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 16:37:11.153  3923  4108 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-09 16:37:11.153  3923  4108 D BluetoothAdapterProperties: Setting state to 16
,09-09 16:37:11.153  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 16:37:11.154  3923  4108 D BluetoothAdapterProperties: onBleDisable
09-09 16:37:11.154  3923  4109 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 16:37:11.154  3923  4108 I BluetoothAdapterState: Entering PendingCommandState
09-09 16:37:11.155  3923  4120 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 16:37:11.155  3923  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 16:37:11.157  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:11.158  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:11.158  3923  4112 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:37:11.159  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:37:11.162  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:11.163  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:11.166  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:37:11.170  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:37:11.197   871  1308 D ConnectivityService: handlePromptUnvalidated 101
,09-09 16:37:11.362  3923  4112 I bt_hci  : shut_down
,09-09 16:37:11.362  3923  4116 D bt_hwcfg: hw_epilog_process
,09-09 16:37:11.373  3923  4116 I bt_vendor: low_power_mode_cb
,09-09 16:37:11.395  3923  4116 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 16:37:11.395  3923  4116 I bt_vendor: epilog_cb
09-09 16:37:11.396  3923  4116 I bt_hci  : epilog_finished_callback
,09-09 16:37:11.403  3923  4112 I bt_hci_h4: hal_close
,09-09 16:37:11.405  3923  4112 I bt_userial_vendor: device fd = 51 close
,09-09 16:37:11.528  3923  4109 D bt_stack_manager: event_shut_down_stack finished.
,09-09 16:37:11.531  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 16:37:11.537  3923  4108 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 16:37:11.537  3923  3923 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:37:11.539  3923  3923 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 16:37:11.539  3923  3923 D BtGatt.GattService: stop()
09-09 16:37:11.539  3923  3923 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 16:37:11.544  3923  3923 V BluetoothAdapterState: isTurningOff()=false,
09-09 16:37:11.544  3923  3923 V BluetoothAdapterState: isTurningOn()=false
09-09 16:37:11.545  3923  3923 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:11.545  3923  3923 V BluetoothAdapterState: isBleTurningOff()=true
09-09 16:37:11.546  3923  4108 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 16:37:11.546  3923  4108 D BluetoothAdapterProperties: Setting state to 10
,09-09 16:37:11.547  3923  4108 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 16:37:11.548  3923  4108 I BluetoothAdapterState: Entering OffState
,09-09 16:37:11.551   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 16:37:11.566  3923  3923 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 16:37:11.567  3923  3923 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 16:37:11.567  3923  4109 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 16:37:11.570  3923  4109 D bt_stack_manager: event_clean_up_stack finished.
,09-09 16:37:11.570  3923  3923 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 16:37:11.572  3923  3923 I art     : System.exit called, status: 0
,09-09 16:37:11.572  3923  3923 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 16:37:11.636   871  2068 I ActivityManager: Process com.android.bluetooth (pid 3923) has died
,09-09 16:37:13.598  3507  3519 D Finsky  : [265] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-09 16:37:13.614  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:13.671  1511  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 16:37:13.672  1511  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 16:37:13.672  1511  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:13.672  1511  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:13.727  3507  3519 D Finsky  : [265] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-09 16:37:14.068  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:37:14.069  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:37:16.728   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 16:37:16.758   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 16:37:16.758   871   891 I Adreno  : Build Date                       : 10/20/15
09-09 16:37:16.758   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 16:37:16.758   871   891 I Adreno  : Local Branch                     : M14
09-09 16:37:16.758   871   891 I Adreno  : Remote Branch                    : 
09-09 16:37:16.758   871   891 I Adreno  : Remote Branch                    : 
09-09 16:37:16.758   871   891 I Adreno  : Reconstruct Branch               : 
,09-09 16:37:16.757  1889  1889 I Keyboard.Facilitator: onFinishInput()
,09-09 16:37:16.796   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (720 us)
,09-09 16:37:17.076  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:17.077  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdd2e59 added. We now have 6 listener(s)
09-09 16:37:17.077  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:37:17.082  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:17.083  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@220a1e added. We now have 7 listener(s)
09-09 16:37:17.083  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:37:17.085  3777  3827 I System.out: IsBluetoothEnabled
,09-09 16:37:17.091  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:17.133   871   888 I ActivityManager: Start proc 4160:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 16:37:17.235  4160  4160 D AdapterServiceConfig: Adding HeadsetService
,09-09 16:37:17.235  4160  4160 D AdapterServiceConfig: Adding A2dpService
09-09 16:37:17.235  4160  4160 D AdapterServiceConfig: Adding HidService
,09-09 16:37:17.235  4160  4160 D AdapterServiceConfig: Adding HealthService
,09-09 16:37:17.236  4160  4160 D AdapterServiceConfig: Adding PanService
09-09 16:37:17.236  4160  4160 D AdapterServiceConfig: Adding GattService
,09-09 16:37:17.237  4160  4160 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 16:37:17.256  4160  4160 D BluetoothAdapterState: make() - Creating AdapterState
09-09 16:37:17.256   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c6e53cd:true
,09-09 16:37:17.262  4160  4160 I bt_bluedroid: init
,09-09 16:37:17.265  4160  4172 I BluetoothAdapterState: Entering OffState
,09-09 16:37:17.270  4160  4173 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 16:37:17.270  4160  4173 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 16:37:17.270  4160  4173 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 16:37:17.271  4160  4173 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-09 16:37:17.271  4160  4160 I bt_bluedroid: get_profile_interface socket
,09-09 16:37:17.276  4160  4160 I bt_bluedroid: get_profile_interface sdp
,09-09 16:37:17.283  4160  4171 I bt_bluedroid: config_hci_snoop_log
,09-09 16:37:17.286  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-09 16:37:17.286   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-09 16:37:17.289  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 16:37:17.300  4160  4172 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 16:37:17.301  4160  4172 D BluetoothAdapterProperties: Setting state to 14
09-09 16:37:17.302  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 16:37:17.305  4160  4172 D BluetoothBondStateMachine: make
,09-09 16:37:17.309  4160  4177 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 16:37:17.316  4160  4160 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 16:37:17.316  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:37:17.322  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:17.324  4160  4160 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 16:37:17.326  4160  4160 D BtGatt.GattService: Received start request. Starting profile...
09-09 16:37:17.326  4160  4160 D BtGatt.GattService: start()
09-09 16:37:17.326  4160  4160 I bt_bluedroid: get_profile_interface gatt
,09-09 16:37:17.328  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:17.328  4160  4160 D BtGatt.AdvertiseManager: advertise manager created
,09-09 16:37:17.340  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:17.341  4160  4160 V BluetoothAdapterState: isTurningOn()=false
,09-09 16:37:17.341  4160  4160 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 16:37:17.341  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:17.344  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-09 16:37:17.345  4160  4172 I bt_bluedroid: enable
09-09 16:37:17.345  4160  4173 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 16:37:17.346  4160  4173 I bt_hci  : start_up
,09-09 16:37:17.362  4160  4173 I bt_vendor: alloc value 0xb3a41189
,09-09 16:37:17.363  4160  4173 I bt_vendor: init
09-09 16:37:17.363  4160  4173 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 16:37:17.363  4160  4173 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 16:37:17.471  4160  4173 D bt_hci  : start_up starting async portion,
,09-09 16:37:17.472  4160  4180 I bt_hci  : event_finish_startup
,09-09 16:37:17.472  4160  4180 I bt_hci_h4: hal_open
,09-09 16:37:17.473  4160  4180 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-09 16:37:17.477  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 16:37:17.477  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 16:37:17.482  4160  4180 I bt_userial_vendor: device fd = 51 open
,09-09 16:37:17.511  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6ea41c8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ec7a2ff, 16908290=android.view.AbsSavedState$1@ec7a2ff}, android:focusedViewId=100}]}]
,09-09 16:37:17.511  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 16:37:17.511  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 16:37:17.511  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 16:37:17.512   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 16:37:17.514  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:37:17.524   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 16:37:17.527   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-09 16:37:17.527   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-09 16:37:17.527   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 16:37:17.546  4160  4180 D bt_hwcfg: Chipset BCM4354A2
,09-09 16:37:17.546  4160  4180 D bt_hwcfg: Target name = [BCM4354A2]
09-09 16:37:17.546  4160  4180 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 16:37:17.556   871   880 I art     : Background partial concurrent mark sweep GC freed 18151(1483KB) AllocSpace objects, 9(296KB) LOS objects, 33% free, 29MB/43MB, paused 1.239ms total 108.832ms
,09-09 16:37:17.757   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 16:37:17.763   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 16:37:17.768   871  1333 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,09-09 16:37:17.772   871   891 I DreamManagerService: Entering dreamland.
09-09 16:37:17.773   871   891 I PowerManagerService: Dozing...
,09-09 16:37:17.776   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 16:37:17.861   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 16:37:17.861   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 16:37:17.871   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:37:17.882   871  1306 E native  : do suspend false
,09-09 16:37:17.903  1939  4183 D NfcService: Discovery configuration equal, not updating.
,09-09 16:37:17.947   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:37:17.958   871  1306 E native  : do suspend true
,09-09 16:37:17.990   376  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 16:37:17.991   376  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 16:37:18.329  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-09 16:37:18.330  4160  4180 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 16:37:18.331  4160  4180 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 16:37:18.449  4160  4180 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 16:37:18.450  4160  4180 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 16:37:18.478  4160  4180 I bt_hwcfg: vendor lib fwcfg completed
,09-09 16:37:18.479  4160  4180 I bt_vendor: firmware callback
09-09 16:37:18.479  4160  4180 I bt_hci  : firmware_config_callback
,09-09 16:37:18.494  4160  4187 I bt_btu  : btu_task pending for preload complete event
,09-09 16:37:18.494  4160  4187 I bt_btu_task: Bluetooth chip preload is complete
09-09 16:37:18.494  4160  4187 I bt_btu  : btu_task received preload complete event
,09-09 16:37:18.504  4160  4187 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 16:37:18.504  4160  4187 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 16:37:18.505  4160  4187 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 16:37:18.505  4160  4187 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 16:37:18.505  4160  4187 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 16:37:18.505  4160  4187 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 16:37:18.506  4160  4187 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 16:37:18.506  4160  4187 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 16:37:18.506  4160  4187 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 16:37:18.506  4160  4187 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 16:37:18.507  4160  4187 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 16:37:18.507  4160  4187 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 16:37:18.507  4160  4187 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 16:37:18.508  4160  4187 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 16:37:18.508  4160  4187 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 16:37:18.658  4160  4187 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bed9d
,09-09 16:37:18.659  4160  4187 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bed9d 
,09-09 16:37:18.685  4160  4176 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 16:37:18.700  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 16:37:18.701  4160  4176 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 16:37:18.706  4160  4176 D BluetoothAdapterProperties: Name is: Nexus 6
09-09 16:37:18.711  4160  4176 D BluetoothAdapterProperties: Scan Mode:20
09-09 16:37:18.712  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 16:37:18.712  4160  4176 D bt_hci  : do_postload posting postload work item
09-09 16:37:18.713  4160  4180 I bt_hci  : event_postload
09-09 16:37:18.713  4160  4180 I bt_vendor: sco_config_cb
,09-09 16:37:18.713  4160  4180 I bt_hci  : sco_config_callback postload finished.
09-09 16:37:18.720  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:18.721  4160  4176 D bt_bte_conf: Device ID record 1 : primary
,09-09 16:37:18.721  4160  4176 D bt_bte_conf:   vendorId            = 000f
,09-09 16:37:18.722  4160  4176 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 16:37:18.722  4160  4176 D bt_bte_conf:   product             = 1200
09-09 16:37:18.723  4160  4176 D bt_bte_conf:   version             = 1436
,09-09 16:37:18.723  4160  4176 D bt_bte_conf:   clientExecutableURL = 
,09-09 16:37:18.723  4160  4176 D bt_bte_conf:   serviceDescription  = 
09-09 16:37:18.724  4160  4176 D bt_bte_conf:   documentationURL    = 
09-09 16:37:18.724  4160  4176 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 16:37:18.725  4160  4173 D bt_stack_manager: event_start_up_stack finished
,09-09 16:37:18.725  4160  4180 I bt_vendor: low_power_mode_cb
09-09 16:37:18.726  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 16:37:18.727  4160  4172 D BluetoothAdapterProperties: Setting state to 15
09-09 16:37:18.727  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 16:37:18.728  4160  4172 I BluetoothAdapterState: Entering BleOnState
09-09 16:37:18.731  4160  4172 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 16:37:18.731  4160  4172 D BluetoothAdapterProperties: Setting state to 11
09-09 16:37:18.732  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 16:37:18.737  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:18.738  4160  4160 D HeadsetService: Received start request. Starting profile...
09-09 16:37:18.742  4160  4160 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 16:37:18.744  4160  4160 D HeadsetStateMachine: make
09-09 16:37:18.750  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:18.757  4160  4160 D HeadsetStateMachine: max_hf_connections = 1
09-09 16:37:18.757  4160  4160 I bt_bluedroid: get_profile_interface handsfree
09-09 16:37:18.757  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 16:37:18.758  4160  4176 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-09 16:37:18.761  4160  4172 I BluetoothAdapterState: Entering PendingCommandState
,09-09 16:37:18.764  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:18.765  4160  4160 D A2dpService: Received start request. Starting profile...
,09-09 16:37:18.765  4160  4160 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 16:37:18.766  4160  4160 I bt_bluedroid: get_profile_interface avrcp
,09-09 16:37:18.772  4160  4160 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 16:37:18.772  4160  4160 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-09 16:37:18.772  4160  4160 D A2dpStateMachine: make
,09-09 16:37:18.774  4160  4160 I bt_bluedroid: get_profile_interface a2dp
,09-09 16:37:18.774  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 16:37:18.776  4160  4160 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 16:37:18.776  4160  4197 D A2dpStateMachine: Enter Disconnected: -2
09-09 16:37:18.777  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:18.777  4160  4160 D HidService: Received start request. Starting profile...
09-09 16:37:18.777  4160  4160 I bt_bluedroid: get_profile_interface hidhost
09-09 16:37:18.777  4160  4160 D HidService: setHidService(): set to: null
09-09 16:37:18.778  4160  4160 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 16:37:18.778  4160  4176 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a03e5
09-09 16:37:18.778  4160  4176 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 16:37:18.779  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:18.779  4160  4160 D HealthService: Received start request. Starting profile...
09-09 16:37:18.781  4160  4160 I bt_bluedroid: get_profile_interface health
,09-09 16:37:18.783  4160  4160 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 16:37:18.784  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
09-09 16:37:18.784  4160  4160 D PanService: Received start request. Starting profile...
09-09 16:37:18.784  4160  4160 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 16:37:18.784  4160  4160 I bt_bluedroid: get_profile_interface pan
,09-09 16:37:18.785  4160  4176 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 16:37:18.788  4160  4160 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:18.789  4160  4160 D BluetoothMapService: Received start request. Starting profile...
09-09 16:37:18.789  4160  4160 D BluetoothMapService: start()
,09-09 16:37:18.792  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 16:37:18.793  4160  4160 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 16:37:18.793  4160  4160 D BluetoothMapAppObserver: createReceiver()
,09-09 16:37:18.794  4160  4160 D BluetoothMapAppObserver: initObservers()
09-09 16:37:18.794  4160  4160 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 16:37:18.800  4160  4160 V BluetoothAdapterState: isTurningOff()=false
,09-09 16:37:18.800  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:18.800  4160  4193 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 16:37:18.800  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:18.800  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:18.803  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:18.803  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isTurningOn()=true
,09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 16:37:18.804  4160  4160 V BluetoothAdapterState: isTurningOff()=false
09-09 16:37:18.805  4160  4160 V BluetoothAdapterState: isTurningOn()=true
09-09 16:37:18.805  4160  4160 V BluetoothAdapterState: isBleTurningOn()=false
09-09 16:37:18.805  4160  4160 V BluetoothAdapterState: isBleTurningOff()=false
09-09 16:37:18.805  4160  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 16:37:18.805  4160  4172 D BluetoothAdapterProperties: ScanMode =  20
,09-09 16:37:18.805  4160  4172 D BluetoothAdapterProperties: State =  11
09-09 16:37:18.806  4160  4172 D BluetoothAdapterProperties: Setting state to 12
09-09 16:37:18.806  4160  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 16:37:18.806  4160  4172 I BluetoothAdapterState: Entering OnState
09-09 16:37:18.806  3845  3855 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 16:37:18.807  4160  4176 D BluetoothAdapterProperties: Scan Mode:21
09-09 16:37:18.809   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.809  4160  4176 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 16:37:18.809  1365  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:18.811  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 16:37:18.812   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.813  3845  4151 D BluetoothPan: onBluetoothStateChange on: true
,09-09 16:37:18.813  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 16:37:18.813  1365  1365 D BluetoothA2dp: Proxy object connected
09-09 16:37:18.814   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.815  1365  2080 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 16:37:18.816  1960  2107 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.817  3845  3857 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 16:37:18.819  3845  3855 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 16:37:18.820  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 16:37:18.820  1365  1377 D BluetoothPan: onBluetoothStateChange on: true
,09-09 16:37:18.821  4160  4160 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 16:37:18.823  3845  4151 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.823  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 16:37:18.823  1365  1365 D PanProfile: Bluetooth service connected
09-09 16:37:18.823  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 16:37:18.823  3845  3857 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:37:18.825  1365  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 16:37:18.825  4160  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:37:18.825   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 16:37:18.826  1365  2080 D BluetoothMap: onBluetoothStateChange: up=true
09-09 16:37:18.826   871   871 D BluetoothA2dp: Proxy object connected
,09-09 16:37:18.827  4160  4160 D ObexServerSockets: Succeed to create listening sockets 
09-09 16:37:18.827  4160  4160 D ObexServerSockets0: startAccept()
09-09 16:37:18.827  4160  4160 D ObexServerSockets0: prepareForNewConnect()
09-09 16:37:18.827  1365  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 16:37:18.829  1365  1365 D BluetoothInputDevice: Proxy object connected
,09-09 16:37:18.829  1365  1365 D HidProfile: Bluetooth service connected
,09-09 16:37:18.830  4160  4160 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 16:37:18.830  4160  4160 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 16:37:18.830   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 16:37:18.830  3845  3845 D BluetoothInputDevice: Proxy object connected
09-09 16:37:18.832  3845  3845 D HidProfile: Bluetooth service connected
09-09 16:37:18.832  4160  4203 D ObexServerSockets0: Accepting socket connection...
09-09 16:37:18.833  4160  4202 D ObexServerSockets0: Accepting socket connection...
09-09 16:37:18.833  4160  4160 D BluetoothMapService: onReceive
,09-09 16:37:18.834  4160  4160 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 16:37:18.834  4160  4160 D BluetoothMapService: STATE_ON
09-09 16:37:18.834  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:18.834  1365  1365 D BluetoothMap: Proxy object connected
09-09 16:37:18.834  1365  1365 D MapProfile: Bluetooth service connected
09-09 16:37:18.834  1365  1365 D BluetoothMap: getConnectedDevices()
,09-09 16:37:18.835  3845  3845 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 16:37:18.835  3845  3845 D PanProfile: Bluetooth service connected
09-09 16:37:18.835  3845  3845 D BluetoothA2dp: Proxy object connected
,09-09 16:37:18.841  3845  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 16:37:18.845  3845  3845 D BluetoothMap: Proxy object connected
,09-09 16:37:18.845  3845  3845 D MapProfile: Bluetooth service connected
09-09 16:37:18.845  3845  3845 D BluetoothMap: getConnectedDevices()
,09-09 16:37:18.848  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 16:37:18.853  3845  3845 D DockEventReceiver: finishStartingService: stopping service
,09-09 16:37:18.856  3845  3845 D BluetoothPbap: Proxy object connected
,09-09 16:37:18.856  3845  3845 D PbapServerProfile: Bluetooth service connected
,09-09 16:37:18.862  1365  1365 D BluetoothPbap: Proxy object connected
,09-09 16:37:18.862  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-09 16:37:18.864  4160  4160 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 16:37:18.864  4160  4160 D ObexServerSockets0: prepareForNewConnect()
,09-09 16:37:18.868  4160  4207 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:37:18.882  4160  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 16:37:18.884  4160  4211 I BtOppRfcommListener: Accept thread started.
,09-09 16:37:18.911  1365  1377 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.911  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:18.911   871   871 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.911   871   871 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.912  1960  2108 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.912   871   871 D BluetoothHeadset: Proxy object connected
,09-09 16:37:18.912  3845  3857 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.913   871   888 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.913  3845  3845 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:18.915   871   888 D BluetoothHeadset: Proxy object connected
,09-09 16:37:18.916  1960  1970 D BluetoothHeadset: Proxy object connected
,09-09 16:37:18.924  3845  3855 D BluetoothHeadset: Proxy object connected
09-09 16:37:18.925  3845  3845 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:18.926  1365  1376 D BluetoothHeadset: Proxy object connected
,09-09 16:37:18.927  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:19.120  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:19.129  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:19.132  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:19.133  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee448cc added. We now have 8 listener(s)
,09-09 16:37:19.133  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:37:19.140   871  1385 D WifiService: setWifiEnabled: false pid=3777, uid=10000
,09-09 16:37:19.141   871  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:37:19.155  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:19.156   871  2280 D WifiService: setWifiEnabled: true pid=3777, uid=10000
09-09 16:37:19.156   871  2280 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 16:37:19.169   871  1306 D WifiConfigStore: Loading config and enabling all networks 
,09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:19.190  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:19.197  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:19.205   871  1306 D WifiConfigStore: loaded 0 passpoint configs
,09-09 16:37:19.206   871  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 16:37:19.207   871  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 16:37:19.209   871  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 16:37:19.209   871  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 16:37:19.209   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 16:37:19.209   871  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 16:37:19.229   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 16:37:19.230   871  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.11 delta 1000 -> 1000
,09-09 16:37:19.230   871  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 16:37:19.231   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:19.242   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-09 16:37:19.242   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 16:37:19.248   871  1306 E native  : do suspend true
,09-09 16:37:19.257   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 16:37:19.257   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 16:37:19.266   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 16:37:19.267   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:19.296   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 16:37:19.365   871  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 16:37:19.370  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 16:37:19.810  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 16:37:19.932  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 16:37:19.934  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 16:37:19.944   871  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 16:37:19.960   871  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:37:19.961   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 16:37:19.961   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 16:37:19.988   871  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 16:37:20.011   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:20.013   871  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 16:37:20.025   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 16:37:20.075   871  4221 D DhcpClient: Receive thread started
,09-09 16:37:20.169   871  1306 E native  : do suspend false
,09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 16:37:20.183  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 16:37:20.191  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 16:37:20.198   871  2183 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 16:37:20.211  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 16:37:20.214  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 16:37:20.217  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6ea41c8 Bundle[{}]
09-09 16:37:20.217  3777  3827 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 16:37:20.218  3777  3827 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 16:37:20.218  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 16:37:20.219  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 16:37:20.219  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 16:37:20.220  3777  3827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 16:37:20.225  3777  3827 I System.out: Running OutgoingSocketThread
,09-09 16:37:20.227   871  4221 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-09 16:37:20.228   871  2183 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-09 16:37:20.228  3777  4222 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,09-09 16:37:20.230  3777  4222 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37172
09-09 16:37:20.231  3777  4222 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-09 16:37:20.231   871  2183 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 16:37:20.244   871  4221 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 16:37:20.244   871  2183 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 16:37:20.248   372   869 D CommandListener: Setting iface cfg
,09-09 16:37:20.253   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 16:37:20.258   871  1306 E native  : do suspend true
,09-09 16:37:20.259   871  2183 D DhcpClient: Scheduling renewal in 86399s
,09-09 16:37:20.273   871  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 16:37:20.275   871  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 16:37:20.275   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 16:37:20.278   871  1308 D ConnectivityService: Adding iface wlan0 to network 102
09-09 16:37:20.279   871  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 16:37:20.338   871  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 16:37:20.339   871  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 16:37:20.340   871  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 16:37:20.341   871  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 16:37:20.345   871  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 16:37:20.355   871  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 16:37:20.368   871  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 16:37:20.369   871  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-09 16:37:20.369   871  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 16:37:20.369   871  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 16:37:20.370   871  1308 D ConnectivityService:    accepting network in place of null
09-09 16:37:20.370   871  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 16:37:20.372   871  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 16:37:20.404   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:20.422   871  4220 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153828, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 16:37:20.440   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 16:37:20.447   871  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-09 16:37:20.448   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:20.457   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-09 16:37:20.459   871  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:20.475  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:20.478  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:20.485  2031  2031 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-09 16:37:20.493  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 16:37:20.499  1717  1717 D SystemUpdateService: onCreate
,09-09 16:37:20.503  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 16:37:20.519  1717  4231 I SystemUpdateService: active receiver: enabled
,09-09 16:37:20.522  1717  4231 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 16:37:20.527  1717  4231 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 16:37:20.527  1717  4231 I SystemUpdateService: now status is 0 (complete)
09-09 16:37:20.527  1717  4231 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 16:37:20.528  1717  4231 I SystemUpdateService: file has been verified
09-09 16:37:20.528  1717  4231 I SystemUpdateService: OTA package size = 12249756
,09-09 16:37:20.531  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 16:37:20.533  1717  2522 I iu.UploadsManager: num queued entries: 0
,09-09 16:37:20.548  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 16:37:20.549  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 16:37:20.534  1717  2522 I iu.UploadsManager: num updated entries: 0
,09-09 16:37:20.543  1717  4231 I SystemUpdateService: showing system update notification
,09-09 16:37:20.552  1717  2522 I iu.SyncManager: NEXT; no task
,09-09 16:37:20.554  3939  3939 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 16:37:20.557  1717  4234 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 16:37:20.557  1717  4234 W BaseAppContext: Using Auth Proxy for data requests.
09-09 16:37:20.559  1717  4234 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 16:37:20.559  3939  3939 D SprintDMHelper: simOperator: 
,09-09 16:37:20.560  3939  3939 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 16:37:20.580  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:20.587  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 16:37:20.588   871  4219 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-09 16:37:20.611  1717  1717 D SystemUpdateService: onDestroy
,09-09 16:37:20.625  1511  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 16:37:20.625  1511  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-09 16:37:20.625  1511  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 16:37:20.625  1511  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 16:37:20.639  1717  4234 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-09 16:37:20.678   871  4219 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 14:37:20 GMT], X-Android-Received-Millis=[1473431840678], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473431840642]}
,09-09 16:37:20.679   871  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 16:37:20.679   871  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 16:37:20.679   871  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-09 16:37:20.680   871  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 16:37:20.714  2135  4236 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 16:37:21.231  3777  3827 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,09-09 16:37:21.231  3777  3827 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,09-09 16:37:21.240  3777  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,09-09 16:37:21.241  3777  3827 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 16:37:21.242  3777  3827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,09-09 16:37:21.248  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:37:21.248  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f295715 added. We now have 2 listener(s)
,09-09 16:37:21.254  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:37:21.254  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:37:21.255  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.255  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:21.255  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c60aa2a added. We now have 9 listener(s)
09-09 16:37:21.256  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:37:21.257  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:37:21.263  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:21.271  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:21.274  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:21.274  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:37:21.274  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:37:21.274  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7325b8 added. We now have 3 listener(s)
,09-09 16:37:21.276  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.276  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:37:21.277  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.277  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:21.277  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad54f91 added. We now have 10 listener(s)
,09-09 16:37:21.277  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.277  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:37:21.277  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:21.277  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:37:21.277  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:37:21.277  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.278  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.278  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:37:21.278  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.278  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f295715 removed from the list
09-09 16:37:21.278  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.278  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c60aa2a removed from the list
,09-09 16:37:21.283  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.284  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:37:21.284  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.285  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.285  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:37:21.286  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.286  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.286  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.286  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c60aa2a not in the list
09-09 16:37:21.286  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.286  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.287  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.287  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.287  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.288  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad54f91 removed from the list
09-09 16:37:21.288  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.288  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.288  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.288  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.288  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7325b8 removed from the list
09-09 16:37:21.289  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.289  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6373ef6 added. We now have 2 listener(s)
,09-09 16:37:21.291  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.291  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:37:21.291  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.291  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:21.291  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8f2f7 added. We now have 9 listener(s)
09-09 16:37:21.291  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.292  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:37:21.295  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:21.300  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:21.302  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:21.302  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:37:21.302  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.302  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6e53cd added. We now have 3 listener(s)
,09-09 16:37:21.305  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:37:21.305  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:37:21.305  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.305  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:21.306  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:21.306  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6105482 added. We now have 10 listener(s)
09-09 16:37:21.306  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.306  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:37:21.306  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 16:37:21.306  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:37:21.306  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:37:21.306  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 16:37:21.309  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 16:37:21.310  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 16:37:21.310  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.316  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:37:21.317  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:37:21.317  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:37:21.321  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:37:21.321  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:37:21.321  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:37:21.322  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:37:21.325  4160  4170 D BtGatt.GattService: registerClient() - UUID=c22dc5ce-519e-4300-8d72-a5d1b152b9c8
,09-09 16:37:21.326  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=c22dc5ce-519e-4300-8d72-a5d1b152b9c8, clientIf=5
,09-09 16:37:21.327  3777  4001 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:37:21.328  4160  4194 D BtGatt.GattService: start scan with filters
,09-09 16:37:21.332  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:37:21.332  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 16:37:21.332  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:37:21.332  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:37:21.333  4160  4179 D BtGatt.ScanManager: handling starting scan
,09-09 16:37:21.335  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:37:21.335  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:37:21.335  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 16:37:21.337  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:37:21.337  4160  4179 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9c6c3dc
,09-09 16:37:21.340  3777  3827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 16:37:21.340  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:37:21.340  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 16:37:21.340  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.340  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:37:21.340  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 16:37:21.340  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:37:21.341  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 16:37:21.341  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 16:37:21.341  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:37:21.341  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:37:21.342  3777  3827 D BluetoothAdapter: STATE_ON
09-09 16:37:21.343  4160  4171 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:37:21.344  4160  4176 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:37:21.344  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.344  4160  4195 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:37:21.345  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:37:21.345  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:37:21.345  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 16:37:21.345  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 16:37:21.345  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 16:37:21.345  4160  4179 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-09 16:37:21.346  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:37:21.346  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:37:21.346  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:37:21.346  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 16:37:21.348  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:37:21.350  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:37:21.350  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:37:21.350  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 16:37:21.353  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:37:21.353  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.355  4160  4179 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 16:37:21.355  4160  4179 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:37:21.355  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:37:21.356  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:37:21.356  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:37:21.356  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:37:21.356  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.356  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:37:21.357  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.357  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6373ef6 removed from the list
09-09 16:37:21.357  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.357  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8f2f7 removed from the list
09-09 16:37:21.357  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:37:21.357  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.358  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.358  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.360  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:37:21.360  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.361  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:37:21.361  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8f2f7 not in the list
09-09 16:37:21.361  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.361  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.362  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.362  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:37:21.362  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:37:21.362  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6105482 removed from the list
09-09 16:37:21.362  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.362  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.362  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:37:21.362  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.362  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6e53cd removed from the list
09-09 16:37:21.363  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.363  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7336ce added. We now have 2 listener(s)
,09-09 16:37:21.365  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 16:37:21.365  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:37:21.365  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.365  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:21.365  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31549ef added. We now have 9 listener(s)
09-09 16:37:21.366  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.367  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:37:21.370  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:21.378  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:21.378  4160  4176 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:37:21.378  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.381  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:21.382  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:37:21.382  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.382  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4f2f85 added. We now have 3 listener(s)
09-09 16:37:21.385  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.385  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 16:37:21.385  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.387  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.387  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:37:21.387  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.387  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:21.387  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ff1da added. We now have 10 listener(s)
,09-09 16:37:21.387  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.387  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 16:37:21.388  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.388  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:37:21.389  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-09 16:37:21.389  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:37:21.389  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:37:21.389  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-09 16:37:21.393  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:37:21.393  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:37:21.398  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:37:21.399  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:37:21.399  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:37:21.399  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.399  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:37:21.399  4160  4179 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:37:21.403  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 16:37:21.403  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 16:37:21.403  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 16:37:21.405  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:37:21.407  4160  4195 D BtGatt.GattService: registerClient() - UUID=c64659fc-94aa-40cc-a331-6ab19e6b8bda
09-09 16:37:21.407  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 16:37:21.407  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.408  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=c64659fc-94aa-40cc-a331-6ab19e6b8bda, clientIf=5
,09-09 16:37:21.408  3777  3788 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:37:21.408  4160  4179 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:37:21.411  4160  4194 D BtGatt.GattService: start scan with filters
,09-09 16:37:21.415  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 16:37:21.415  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 16:37:21.415  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 16:37:21.415  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 16:37:21.417  4160  4176 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:37:21.417  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.419  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 16:37:21.419  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:37:21.420  4160  4179 D BtGatt.ScanManager: handling starting scan
09-09 16:37:21.420  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:37:21.421  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 16:37:21.424  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:37:21.424  3777  3827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 16:37:21.424  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:37:21.424  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:37:21.424  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:37:21.425  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.425  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.425  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 16:37:21.425  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.425  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7336ce removed from the list
,09-09 16:37:21.425  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.425  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31549ef removed from the list
09-09 16:37:21.425  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 16:37:21.425  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:37:21.426  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.426  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-09 16:37:21.426  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.426  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:37:21.426  4160  4176 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-09 16:37:21.427  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.427  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.427  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.427  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:37:21.427  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31549ef not in the list
,09-09 16:37:21.428  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 16:37:21.428  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:37:21.428  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-09 16:37:21.428  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 16:37:21.428  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 16:37:21.429  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:37:21.429  4160  4179 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:37:21.429  4160  4170 D BtGatt.GattService: stopScan() - queue size =1
,09-09 16:37:21.430  4160  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 16:37:21.432  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 16:37:21.432  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 16:37:21.432  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:37:21.432  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 16:37:21.433  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:37:21.435  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 16:37:21.436  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-09 16:37:21.436  4160  4179 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 16:37:21.436  4160  4179 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 16:37:21.437  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:37:21.437  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 16:37:21.437  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 16:37:21.438  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:37:21.438  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.439  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.439  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:37:21.439  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:37:21.440  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ff1da removed from the list
09-09 16:37:21.440  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.440  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.440  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:37:21.440  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:37:21.440  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:37:21.440  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.440  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.440  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d4f2f85 removed from the list
09-09 16:37:21.441  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.441  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b51a6 added. We now have 2 listener(s)
,09-09 16:37:21.443  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.443  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:37:21.443  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:37:21.443  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:21.444  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29687e7 added. We now have 9 listener(s)
,09-09 16:37:21.444  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.445  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 16:37:21.447   871  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-09 16:37:21.448  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:37:21.450  4160  4176 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:37:21.450  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:21.454  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:21.456  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:21.457  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:37:21.457  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:37:21.457  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f88ca3d added. We now have 3 listener(s)
09-09 16:37:21.458  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:37:21.458  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.458  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.458  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:37:21.459  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.459  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:21.459  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30ae232 added. We now have 10 listener(s)
,09-09 16:37:21.459  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.459  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:37:21.459  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 16:37:21.459  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 16:37:21.459  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 16:37:21.459  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 16:37:21.460  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:21.463  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.466  3777  3827 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 16:37:21.466  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 16:37:21.469  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 16:37:21.469  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.469  4160  4179 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:37:21.471  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 16:37:21.472  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 16:37:21.472  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 16:37:21.476  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:37:21.476  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.477  4160  4179 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:37:21.477  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 16:37:21.478  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 16:37:21.478  3777  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 16:37:21.478  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:37:21.481  4160  4171 D BtGatt.GattService: registerClient() - UUID=4696057f-a702-4478-b2ca-541bd7beb068
,09-09 16:37:21.482  4160  4176 D BtGatt.GattService: onClientRegistered() - UUID=4696057f-a702-4478-b2ca-541bd7beb068, clientIf=5
,09-09 16:37:21.483  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 16:37:21.484  4160  4170 D BtGatt.GattService: start scan with filters
,09-09 16:37:21.484  4160  4176 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:37:21.484  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 16:37:21.486  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 16:37:21.486  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 16:37:21.487  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 16:37:21.487  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 16:37:21.487  4160  4179 D BtGatt.ScanManager: handling starting scan
09-09 16:37:21.489  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:37:21.489  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 16:37:21.490  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 16:37:21.491  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 16:37:21.493  4160  4176 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 16:37:21.493  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.494  4160  4179 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 16:37:21.502  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 16:37:21.502  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:37:21.502  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 16:37:21.502  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:37:21.503  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.503  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 16:37:21.503  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-09 16:37:21.503  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b51a6 removed from the list
09-09 16:37:21.503  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.503  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29687e7 removed from the list
09-09 16:37:21.503  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 16:37:21.503  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 16:37:21.504  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.504  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-09 16:37:21.504  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.504  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:37:21.505  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 16:37:21.505  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.505  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29687e7 not in the list
,09-09 16:37:21.505  4160  4179 D BtGatt.ScanManager: Starting BLE batch scan
09-09 16:37:21.505  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 16:37:21.505  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 16:37:21.505  4160  4179 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 16:37:21.505  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 16:37:21.506  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 16:37:21.506  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 16:37:21.507  3777  3827 D BluetoothAdapter: STATE_ON
,09-09 16:37:21.507  4160  4171 D BtGatt.GattService: stopScan() - queue size =1
09-09 16:37:21.508  4160  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 16:37:21.508  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 16:37:21.508  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 16:37:21.508  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 16:37:21.509  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 16:37:21.509  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 16:37:21.509  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:37:21.510  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 16:37:21.510  3777  3827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 16:37:21.510  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 16:37:21.510  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.511  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 16:37:21.511  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 16:37:21.511  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 16:37:21.512  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.512  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.512  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.512  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30ae232 removed from the list
,09-09 16:37:21.512  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.512  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.512  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.512  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 16:37:21.512  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f88ca3d removed from the list
09-09 16:37:21.513  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 16:37:21.513  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@980ef7e added. We now have 2 listener(s)
09-09 16:37:21.515  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.515  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 16:37:21.515  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.515  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 16:37:21.516  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e528cdf added. We now have 9 listener(s)
09-09 16:37:21.516  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:37:21.516  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:37:21.519  4160  4176 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 16:37:21.519  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.520  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:37:21.525  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 16:37:21.525  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:37:21.525  3777  3827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:37:21.529  3777  3827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 16:37:21.529  3777  3827 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 16:37:21.530  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 16:37:21.531  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9403f5 added. We now have 3 listener(s)
,09-09 16:37:21.532  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 16:37:21.533  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:37:21.533  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 16:37:21.533  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 16:37:21.533  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8858a added. We now have 10 listener(s)
,09-09 16:37:21.533  3777  3827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 16:37:21.533  3777  3827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 16:37:21.534  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 16:37:21.534  3777  3827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 16:37:21.534  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 16:37:21.534  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.534  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 16:37:21.534  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 16:37:21.535  4160  4176 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 16:37:21.535  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.535  4160  4179 D BtGatt.ScanManager: stopping BLe Batch
,09-09 16:37:21.535  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.535  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@980ef7e removed from the list
09-09 16:37:21.535  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.536  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e528cdf removed from the list
,09-09 16:37:21.542  4160  4176 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 16:37:21.542  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.542  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:37:21.544  3777  3827 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:37:21.544  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.545  4160  4179 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-09 16:37:21.545  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:37:21.545  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:37:21.547  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 16:37:21.547  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.547  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 16:37:21.549  3777  3827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e528cdf not in the list
,09-09 16:37:21.549  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.549  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 16:37:21.551  4160  4176 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 16:37:21.551  4160  4176 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 16:37:21.552  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 16:37:21.552  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 16:37:21.552  3777  3827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:37:21.552  3777  3827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb8858a removed from the list
,09-09 16:37:21.552  3777  3827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:37:21.552  3777  3827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 16:37:21.552  3777  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:37:21.552  3777  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:37:21.552  3777  3827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9403f5 removed from the list
,09-09 16:37:21.553  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 16:37:21.553  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 16:37:21.553  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 16:37:21.554  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 16:37:21.554  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-09 16:37:21.554  3777  3827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 16:37:21.562  3777  4244 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
,09-09 16:37:21.562  3777  4244 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
09-09 16:37:21.563  3777  4244 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 16:37:21.565  3777  4245 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,09-09 16:37:21.565  3777  4245 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
09-09 16:37:21.565  3777  4245 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 16:37:21.568  3777  3827 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-09 16:37:21.568  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-09 16:37:21.568  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 16:37:21.568  3777  3827 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 16:37:21.568  3777  3827 D com.test.thalitest.ThaliTestRunner: Total duration: 22918 ms
,09-09 16:37:21.571  3777  3827 I jxcore-log: *Native tests were executed*
09-09 16:37:21.571  3777  3827 I jxcore-log: 
09-09 16:37:21.571  3777  3827 I jxcore-log: Total number of executed tests:  80
09-09 16:37:21.571  3777  3827 I jxcore-log: 
09-09 16:37:21.571  3777  3827 I jxcore-log: Number of passed tests:  80
09-09 16:37:21.571  3777  3827 I jxcore-log: 
,09-09 16:37:21.572  3777  3827 I jxcore-log: Number of failed tests:  0
09-09 16:37:21.572  3777  3827 I jxcore-log: 
,09-09 16:37:21.572  3777  3827 I jxcore-log: Number of ignored tests:  0
09-09 16:37:21.572  3777  3827 I jxcore-log: 
,09-09 16:37:21.573  3777  3827 I jxcore-log: Total duration:  22918
09-09 16:37:21.573  3777  3827 I jxcore-log: 
,09-09 16:37:21.573  3777  3827 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 16:37:21.573  3777  3827 I jxcore-log: 
,09-09 16:37:21.578  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.578  3777  3827 I jxcore-log: 
09-09 16:37:21.582  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.582  3777  3827 I jxcore-log: 
09-09 16:37:21.583  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.583  3777  3827 I jxcore-log: 
09-09 16:37:21.585  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.585  3777  3827 I jxcore-log: 
09-09 16:37:21.586  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.586  3777  3827 I jxcore-log: 
,09-09 16:37:21.588  3777  3777 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 16:37:21.589  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.589  3777  3827 I jxcore-log: 
09-09 16:37:21.592  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.592  3777  3827 I jxcore-log: 
09-09 16:37:21.594  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.594  3777  3827 I jxcore-log: 
09-09 16:37:21.595  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.595  3777  3827 I jxcore-log: 
,09-09 16:37:21.596  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:37:21.596  3777  3827 I jxcore-log: 
,09-09 16:37:21.598  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:37:21.598  3777  3827 I jxcore-log: 
,09-09 16:37:21.599  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 16:37:21.599  3777  3827 I jxcore-log: 
09-09 16:37:21.600  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.600  3777  3827 I jxcore-log: 
,09-09 16:37:21.601  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.601  3777  3827 I jxcore-log: 
,09-09 16:37:21.603  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.603  3777  3827 I jxcore-log: 
09-09 16:37:21.603  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.603  3777  3827 I jxcore-log: 
09-09 16:37:21.604  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.604  3777  3827 I jxcore-log: 
09-09 16:37:21.605  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.605  3777  3827 I jxcore-log: 
,09-09 16:37:21.606  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.606  3777  3827 I jxcore-log: 
09-09 16:37:21.606  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.606  3777  3827 I jxcore-log: 
09-09 16:37:21.607  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.607  3777  3827 I jxcore-log: 
09-09 16:37:21.608  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 16:37:21.608  3777  3827 I jxcore-log: 
,09-09 16:37:21.610  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:37:21.610  3777  3827 I jxcore-log: 
09-09 16:37:21.611  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 16:37:21.611  3777  3827 I jxcore-log: 
09-09 16:37:21.612  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.612  3777  3827 I jxcore-log: 
09-09 16:37:21.613  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.613  3777  3827 I jxcore-log: 
09-09 16:37:21.615  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.615  3777  3827 I jxcore-log: 
09-09 16:37:21.616  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.616  3777  3827 I jxcore-log: 
09-09 16:37:21.617  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.617  3777  3827 I jxcore-log: 
09-09 16:37:21.618  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 16:37:21.618  3777  3827 I jxcore-log: 
,09-09 16:37:21.851  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:37:21.854  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:37:21.854  3777  3827 I jxcore-log: 
,09-09 16:37:21.940  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:37:21.944  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:37:21.944  3777  3827 I jxcore-log: 
,09-09 16:37:22.012  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 16:37:22.015  3777  3827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 16:37:22.015  3777  3827 I jxcore-log: 
,09-09 16:37:22.224  4246  4246 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 16:37:22.229  4246  4246 D AndroidRuntime: CheckJNI is OFF
,09-09 16:37:22.272  4246  4246 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 16:37:22.319  4246  4246 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 16:37:22.342  4246  4246 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 16:37:22.354   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-09 16:37:22.355   871   884 I ActivityManager: Killing 3777:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 16:37:22.466   871  1689 D GraphicsStats: Buffer count: 2
,09-09 16:37:22.466   871  1689 I WindowState: WIN DEATH: Window{e9cd257 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 16:37:22.467   871  1307 D WifiService: Client connection lost with reason: 4
,09-09 16:37:22.498   871   894 W PackageSettings: Skipping PackageSetting{6d01439 com.example.hello/10273} due to missing metadata
,09-09 16:37:22.531   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 16:37:22.531   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-09 16:37:22.532   871   884 E ActivityManager: Failure starting process com.test.thalitest,
09-09 16:37:22.532   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 16:37:22.532   871   884 E ActivityManager: ,	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 16:37:22.532   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.532   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.532   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:37:22.532   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 16:37:22.533   871   884 I ActivityManager:   Force finishing activity ActivityRecord{be9f44c u0 com.test.thalitest/.MainActivity t4}
09-09 16:37:22.537   871   894 I art     : Starting a blocking GC Explicit
09-09 16:37:22.541   871  3907 W ActivityManager: Spurious death for ProcessRecord{6792476 0:com.test.thalitest/u0a0}, curProc for 3777: null
,09-09 16:37:22.583   871   894 I art     : Explicit concurrent mark sweep GC freed 56173(3MB) AllocSpace objects, 10(296KB) LOS objects, 33% free, 29MB/43MB, paused 725us total 43.898ms
,09-09 16:37:22.583   871   880 I art     : WaitForGcToComplete blocked for 26.070ms for cause HeapTrim
,09-09 16:37:22.585  1860  2641 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 16:37:22.615   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 16:37:22.619  4246  4246 I art     : System.exit called, status: 0
,09-09 16:37:22.619  4246  4246 I AndroidRuntime: VM exiting with result code 0.
,09-09 16:37:22.627   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 16:37:22.659   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 16:37:22.665  4160  4160 D BluetoothMapAppObserver: onReceive
,09-09 16:37:22.665  4160  4160 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-09 16:37:22.668  1889  1889 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 16:37:22.668  1860  2193 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 16:37:22.675  3647  3647 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-09 16:37:22.679   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 16:37:22.700  1889  4260 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 16:37:22.705  1889  4260 I Decoder : createOrResetDecoder
,09-09 16:37:22.728   871  3907 I ActivityManager: Start proc 4261:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 16:37:22.730  1960  1960 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 16:37:22.755  1511  1511 I ConfigService: onCreate
,09-09 16:37:22.758  1511  4273 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 16:37:22.758  1511  4273 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 16:37:22.758  1511  4273 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 16:37:22.760  1511  4273 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 16:37:22.769  1889  4260 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 16:37:22.775   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 16:37:22.784   871  1689 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3777 uid 10000
09-09 16:37:22.786  1889  1889 I Keyboard.Facilitator: onFinishInput()
,09-09 16:37:22.798  1973  2079 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 16:37:22.799   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 16:37:22.800   871   883 E PackageManager: Failed to write settings, restoring backup
09-09 16:37:22.800   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 16:37:22.800   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 16:37:22.800   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 16:37:22.800   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 16:37:22.800   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 16:37:22.800   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.800   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.800   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:37:22.804  4261  4261 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 16:37:22.808   871   884 E DropBoxManagerService: Can't write: system_server_wtf
09-09 16:37:22.808   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 16:37:22.808   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:22.808   871   884 E DropBoxManagerService: 	... 13 more
09-09 16:37:22.815   871  1383 I ActivityManager: Start proc 4275:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 16:37:22.816  1973  2079 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 16:37:22.816  1973  2079 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1973
09-09 16:37:22.816  1973  2079 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.816  1973  2079 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 16:37:22.818   871  2280 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 16:37:22.819   871  4281 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:37:22.819   871  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:22.819   871  4281 E DropBoxManagerService: 	... 5 more
09-09 16:37:22.821  1973  2079 I Process : Sending signal. PID: 1973 SIG: 9
,09-09 16:37:22.855  1889  4260 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 16:37:22.856  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 16:37:22.856  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 16:37:22.859  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 16:37:22.859  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 16:37:22.860  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 16:37:22.860  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 16:37:22.860  1889  4260 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 16:37:22.864  1889  4260 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 16:37:22.864  1889  4260 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 16:37:22.864  1889  4260 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 16:37:22.864  1889  4260 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 16:37:22.864  1889  4260 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 16:37:22.891  4261  4261 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 16:37:22.895   871   881 I WindowState: WIN DEATH: Window{dee83b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-09 16:37:22.897   871  1972 D GraphicsStats: Buffer count: 1
,09-09 16:37:22.912   871  2068 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1973) has died
,09-09 16:37:22.914   871  2068 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 16:37:22.916   871  2068 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 16:37:22.927  4261  4289 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.927  4261  4289 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.927  4261  4289 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 16:37:22.934   871   884 I ActivityManager: Start proc 4292:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 16:37:22.955   871  1972 I ActivityManager: Start proc 4305:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 16:37:22.963  4261  4302 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 16:37:22.988  4292  4292 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:37:22.988  4292  4292 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:37:22.988  4292  4292 D AndroidRuntime: Shutting down VM
09-09 16:37:22.992  4292  4292 E AndroidRuntime: FATAL EXCEPTION: main
09-09 16:37:22.992  4292  4292 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4292
09-09 16:37:22.992  4292  4292 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 16:37:22.992  4292  4292 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 16:37:22.992  4292  4292 E AndroidRuntime: 	... 10 more
09-09 16:37:22.994   871  1690 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 16:37:22.994  4292  4292 I Process : Sending signal. PID: 4292 SIG: 9
09-09 16:37:22.995   871  4318 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:37:22.995   871  4318 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:22.995   871  4318 E DropBoxManagerService: 	... 5 more
,09-09 16:37:23.021  4305  4305 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 16:37:23.025  1717  4319 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-09 16:37:23.026  1717  4319 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 16:37:23.029   871  1383 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4292) has died
,09-09 16:37:23.030   871  1383 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 16:37:23.037  1717  4319 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-09 16:37:23.038  1717  4319 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-09 16:37:23.047   871   884 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 16:37:23.068  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 16:37:23.069  1511  1511 D AndroidRuntime: Shutting down VM
09-09 16:37:23.070  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
09-09 16:37:23.070  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
09-09 16:37:23.070  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 16:37:23.070  1511  1511 E AndroidRuntime: 	... 8 more
,09-09 16:37:23.073  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
,09-09 16:37:23.078  4261  4289 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-09 16:37:23.078   871  4335 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:37:23.078   871  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:23.078   871  4335 E DropBoxManagerService: 	... 5 more
,09-09 16:37:23.083  4261  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:23.083  4261  4302 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 16:37:23.084  4261  4302 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 16:37:23.084  4261  4302 E AndroidRuntime: Process: android.process.acore, PID: 4261
09-09 16:37:23.084  4261  4302 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:23.084  4261  4302 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 16:37:23.085  4261  4289 I Process : Sending signal. PID: 4261 SIG: 9
,09-09 16:37:23.089   871  4336 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:37:23.089   871  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:23.089   871  4336 E DropBoxManagerService: 	... 5 more
,09-09 16:37:23.105  4322  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:37:23.105  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 16:37:23.105  4322  4322 D AndroidRuntime: Shutting down VM
,09-09 16:37:23.113  4322  4322 E AndroidRuntime: FATAL EXCEPTION: main
09-09 16:37:23.113  4322  4322 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4322
09-09 16:37:23.113  4322  4322 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 16:37:23.113  4322  4322 E AndroidRuntime: 	... 10 more
,09-09 16:37:23.114   871  1383 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 16:37:23.115  4322  4322 I Process : Sending signal. PID: 4322 SIG: 9
09-09 16:37:23.115   871  4337 E DropBoxManagerService: Can't write: system_app_crash
09-09 16:37:23.115   871  4337 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 16:37:23.115   871  4337 E DropBoxManagerService: 	... 5 more
,09-09 16:37:23.120   871  1307 D WifiService: Client connection lost with reason: 4
,09-09 16:37:23.125   871  1972 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
,09-09 16:37:23.126   871  1972 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
09-09 16:37:23.126   871  1972 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-09 16:37:23.126   871  1972 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
09-09 16:37:23.126   871  1972 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,09-09 16:37:23.129   871  2003 I ActivityManager: Process android.process.acore (pid 4261) has died
09-09 16:37:23.129   871  2003 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40996ms
,09-09 16:37:23.135  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-09 16:37:23.137  1717  4319 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-09 16:37:23.138  1717  4319 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-09 16:37:23.141   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
