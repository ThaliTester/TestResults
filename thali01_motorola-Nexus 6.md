#### Test 79763830e2067e4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 14:17:08.838  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:08.854  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 14:17:08.858  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 14:17:08.904  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 14:17:08.905  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 14:17:08.905  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:08.905  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 14:17:08.940  3543  3543 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 14:17:08.941  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 14:17:08.941  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-26 14:17:09.530  3787  3787 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 14:17:09.536  3787  3787 D AndroidRuntime: CheckJNI is OFF
08-26 14:17:09.579  3787  3787 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 14:17:09.630  3787  3787 I Radio-JNI: register_android_hardware_Radio DONE
08-26 14:17:09.651  3787  3787 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 14:17:09.655   872  2005 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 14:17:09.687  2068  2081 W SearchService: Abort, client detached.
08-26 14:17:09.691  3787  3787 D AndroidRuntime: Shutting down VM
08-26 14:17:09.692  2068  2068 I HotwordDetector: Closing mic
08-26 14:17:09.692  2068  2355 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@40534d0
08-26 14:17:09.693  2068  2365 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 14:17:09.722   872  2124 I ActivityManager: Start proc 3796:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 14:17:09.749   375  2367 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 14:17:09.750   375  2367 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 14:17:09.753   375  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 14:17:09.755  2068  2362 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 14:17:09.755  2068  2364 I MicroRecognitionRnrImpl: Detection finished
08-26 14:17:09.816  3796  3796 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 14:17:09.849  3796  3796 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 14:17:09.857  3796  3796 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 638-641)
08-26 14:17:09.857  3796  3796 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:09.874  3796  3796 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c92f5d}
08-26 14:17:09.874  3796  3796 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:09.874  3796  3796 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 14:17:09.885  3796  3796 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 14:17:09.886  3796  3796 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 14:17:09.903  3796  3796 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 14:17:09.914  3796  3796 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:17:09.914  3796  3796 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:17:09.914  3796  3796 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 14:17:09.914  3796  3796 I Adreno  : Build Date                       : 10/20/15
08-26 14:17:09.914  3796  3796 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 14:17:09.914  3796  3796 I Adreno  : Local Branch                     : M14
08-26 14:17:09.914  3796  3796 I Adreno  : Remote Branch                    : 
08-26 14:17:09.914  3796  3796 I Adreno  : Remote Branch                    : 
08-26 14:17:09.914  3796  3796 I Adreno  : Reconstruct Branch               : 
,08-26 14:17:09.963   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@684e41f:true
,08-26 14:17:10.020  3796  3796 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 14:17:10.041  3796  3796 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 14:17:10.116  3796  3834 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 14:17:10.132  3796  3821 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 14:17:10.183  3796  3834 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 14:17:10.279   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +586ms
,08-26 14:17:10.282  1882  1882 I Keyboard.Facilitator: onFinishInput()
,08-26 14:17:10.363  3796  3796 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3796
,08-26 14:17:10.537   872   882 I ActivityManager: Killing 3234:com.google.android.gm/u0a78 (adj 15): empty #17
,08-26 14:17:10.567  3796  3796 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:17:10.590   872   882 I ActivityManager: Killing 3144:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-26 14:17:10.736  3796  3836 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680672464
,08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 14:17:10.740  3796  3836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e556b51 added. We now have 1 listener(s)
,08-26 14:17:10.743  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 14:17:10.744  3796  3836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 14:17:10.744  3796  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:10.744  3796  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 14:17:10.749  3796  3836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac58424 added. We now have 1 listener(s)
08-26 14:17:10.749  3796  3836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:10.752   872  1317 D WifiService: New client listening to asynchronous messages
,08-26 14:17:10.753  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:10.753  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:17:10.753  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 14:17:10.753  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-26 14:17:10.753  3796  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:17:10.755  3796  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:10.755  3796  3836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 14:17:10.762  3796  3836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:10.762  3796  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:10.762  3796  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 14:17:10.762  3796  3836 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:10.763  3796  3836 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 14:17:10.776  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:10.778  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:10.795  3796  3796 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:17:11.668  3796  3847 W jxcore-log: Initializing JXcore engine
,08-26 14:17:11.668  3796  3847 W jxcore-log: JXcore engine is ready
,08-26 14:17:11.702  3847  3847 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 14:17:11.702  3847  3847 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9671]" dev="sockfs" ino=9671 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 14:17:11.702  3847  3847 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 14:17:11.702  3847  3847 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25269]" dev="sockfs" ino=25269 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 14:17:11.719  3796  3847 W jxcore-log: Starting JXcore engine
,08-26 14:17:11.838  3796  3847 W jxcore-log: Platform android
08-26 14:17:11.838  3796  3847 W jxcore-log: 
,08-26 14:17:11.839  3796  3847 W jxcore-log: Process ARCH arm
08-26 14:17:11.839  3796  3847 W jxcore-log: 
,08-26 14:17:12.009   872  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 14:17:12.103  3796  3847 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:17:12.103  3796  3847 I jxcore-log: 
,08-26 14:17:12.104  3796  3847 W jxcore-log: JXcore engine is started
,08-26 14:17:12.109  3796  3836 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 14:17:12.113  3796  3796 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:17:14.614   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 14:17:17.601  3039  3854 V KeepSync: Connecting to GoogleApiClient
08-26 14:17:17.602   872  1716 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 14:17:17.637   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 14:17:17.682  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:17.690  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-26 14:17:17.732  1504  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-26 14:17:17.733  1504  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 14:17:17.733  1504  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:17.734  1504  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:17.774  1701  3855 V BaseAuthAsyncOperation: access token request failed
,08-26 14:17:17.776  3039  3854 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 14:17:17.868  1504  1516 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 14:17:17.868  1504  1516 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 14:17:17.868  1504  1516 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:17.869  1504  1516 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:17.898  3039  3854 E KeepSync: IOException
08-26 14:17:17.898  3039  3854 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 14:17:17.898  3039  3854 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 14:17:17.898  3039  3854 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 14:17:17.898  3039  3854 E KeepSync: 	... 10 more
,08-26 14:17:17.898  3039  3854 W KeepSync: Sync result 2
,08-26 14:17:17.909   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 127199, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-26 14:17:21.781  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 14:17:21.781  3796  3847 I jxcore-log: 
,08-26 14:17:21.784  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 14:17:21.784  3796  3847 I jxcore-log: 
,08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.797  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.803  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:21.805  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 14:17:21.805  3796  3847 I jxcore-log: 
,08-26 14:17:21.807  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 14:17:21.807  3796  3847 I jxcore-log: 
,08-26 14:17:22.304  3796  3847 D executeNativeTests: Running unit tests
,08-26 14:17:22.362  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:22.362  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 added. We now have 2 listener(s)
08-26 14:17:22.364  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:22.364  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:22.364  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:22.364  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:22.364  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 added. We now have 2 listener(s)
08-26 14:17:22.364  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:22.365  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:22.370  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.380  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:22.385  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:22.385  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:22.388  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 14:17:22.388  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 14:17:22.388  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 14:17:22.390  3796  3847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 14:17:22.390  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 14:17:22.390  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 14:17:22.390  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 14:17:22.390  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:22.391  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:22.392  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.392  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:22.392  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.392  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.392  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.393  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:22.393  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:22.393  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 removed from the list
,08-26 14:17:22.393  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.393  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 removed from the list
,08-26 14:17:22.398  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.398  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.398  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.400  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.400  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.401  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.402  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:22.402  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.402  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.404  3796  3847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 14:17:22.405  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.405  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.405  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.405  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.405  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.405  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.406  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.406  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.406  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.406  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.406  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.406  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.406  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.406  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.407  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.407  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.407  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.407  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:22.412  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:22.413  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:22.414  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:22.414  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:22.414  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:22.414  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:22.414  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.414  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.414  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.414  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.414  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.415  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.415  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.415  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.415  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.415  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.415  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.415  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.415  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.415  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.417  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.417  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.417  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.418  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.420  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:22.424  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.436  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:22.440  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.440  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:22.441  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:22.441  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:22.441  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:22.441  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.441  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:22.445  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.446  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 14:17:22.446  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:22.448  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.453  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:22.456  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:22.456  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:22.459  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 14:17:22.463  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 14:17:22.463  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:22.463  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:22.464  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:22.465  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:22.472  2712  2917 D BtGatt.GattService: registerClient() - UUID=c9195b95-29cb-4348-a446-ec7bc7dd86fb
08-26 14:17:22.474  2712  2766 D BtGatt.GattService: onClientRegistered() - UUID=c9195b95-29cb-4348-a446-ec7bc7dd86fb, clientIf=5
08-26 14:17:22.475  3796  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 14:17:22.476  2712  2725 D BtGatt.GattService: start scan with filters
08-26 14:17:22.479  2712  2783 D BtGatt.ScanManager: handling starting scan
08-26 14:17:22.479  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:22.480  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:22.480  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:22.481  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 14:17:22.481  2712  2783 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:22.483  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:22.484  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 14:17:22.484  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:22.486  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 14:17:22.490  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:22.492  2712  2766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 14:17:22.492  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.493  2712  2783 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 14:17:22.494  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.494  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:22.494  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.494  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:22.494  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.494  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:22.494  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:22.494  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:22.494  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:22.494  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:22.495  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:22.495  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:22.496  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:22.496  2712  2726 D BtGatt.GattService: stopScan() - queue size =1
08-26 14:17:22.497  2712  2725 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 14:17:22.497  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:22.497  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:22.497  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:22.497  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:22.497  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:22.499  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:22.499  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 14:17:22.499  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:22.499  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:22.499  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.500  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:22.500  2712  2783 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:22.500  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:22.500  2712  2783 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 14:17:22.503  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.503  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.504  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:22.504  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.505  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.505  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:22.506  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
,08-26 14:17:22.506  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.506  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.506  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.507  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.507  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 14:17:22.511  2712  2766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 14:17:22.511  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.513  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:22.517  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 14:17:22.517  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.522  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:22.525  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 14:17:22.525  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.525  2712  2783 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:22.526  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:22.526  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:22.527  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:22.527  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:22.527  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:22.527  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.527  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:22.529  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.531  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.532  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 14:17:22.532  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.533  2712  2783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 14:17:22.533  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 14:17:22.533  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:22.537  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:22.538  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:22.539  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:22.539  2712  2766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 14:17:22.539  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:22.543  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:22.543  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:22.543  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:22.544  3796  3847 D BluetoothAdapter: STATE_ON
,08-26 14:17:22.546  2712  2726 D BtGatt.GattService: registerClient() - UUID=427416be-c9e7-400c-a8da-a07053d4e719
,08-26 14:17:22.546  2712  2766 D BtGatt.GattService: onClientRegistered() - UUID=427416be-c9e7-400c-a8da-a07053d4e719, clientIf=5
08-26 14:17:22.547  3796  3807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 14:17:22.547  2712  2725 D BtGatt.GattService: start scan with filters
,08-26 14:17:22.550  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:22.550  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:22.550  2712  2783 D BtGatt.ScanManager: handling starting scan
08-26 14:17:22.550  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:22.550  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:22.552  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:22.552  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 14:17:22.552  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:22.554  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 14:17:22.556  2712  2766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 14:17:22.556  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.556  2712  2783 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 14:17:22.556  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:22.559  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:22.559  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:22.559  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.559  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:22.560  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.560  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:22.560  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:22.560  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 14:17:22.560  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:22.560  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:22.560  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:22.560  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:22.561  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:22.561  2712  2917 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:22.561  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 14:17:22.562  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.562  2712  2783 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:22.562  2712  2783 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 14:17:22.562  2712  2726 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 14:17:22.563  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:22.563  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:22.563  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:22.563  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:22.563  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 14:17:22.564  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:22.564  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:22.564  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:22.564  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:22.565  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:22.566  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.566  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.567  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:22.567  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.567  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.567  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:22.567  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.567  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.567  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.567  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.567  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.567  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.568  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.571  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.571  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.571  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.571  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.572  3796  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:22.573  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.574  2712  2766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 14:17:22.574  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.578  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:22.579  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 14:17:22.579  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.580  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:22.580  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:22.581  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:22.581  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:22.581  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:22.581  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.581  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:22.585  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.586  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 14:17:22.586  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:22.586  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 14:17:22.586  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.587  2712  2783 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:22.588  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.590  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:22.591  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:22.591  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:22.593  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 14:17:22.593  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.593  2712  2783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 14:17:22.596  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:22.596  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:22.596  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:22.597  3796  3847 D BluetoothAdapter: STATE_ON
,08-26 14:17:22.598  2712  2766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 14:17:22.598  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.599  2712  2725 D BtGatt.GattService: registerClient() - UUID=06f27ff3-d390-4306-932b-9017bfb319a3
,08-26 14:17:22.600  2712  2766 D BtGatt.GattService: onClientRegistered() - UUID=06f27ff3-d390-4306-932b-9017bfb319a3, clientIf=5
08-26 14:17:22.600  3796  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 14:17:22.600  2712  2917 D BtGatt.GattService: start scan with filters
,08-26 14:17:22.603  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:22.603  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:22.603  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:22.603  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:22.603  2712  2783 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:22.606  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:22.606  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:22.606  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:22.608  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:22.611  3796  3847 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:22.611  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:22.611  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:22.611  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.611  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:22.611  2712  2766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 14:17:22.611  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.611  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.611  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:22.611  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:22.611  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:22.611  2712  2783 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 14:17:22.611  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:22.611  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:22.612  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:22.612  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:22.612  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:22.613  2712  2726 D BtGatt.GattService: stopScan() - queue size =1
08-26 14:17:22.614  2712  2725 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 14:17:22.615  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:22.615  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:22.615  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:22.615  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:22.615  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:22.616  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:22.616  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:22.616  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:22.616  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:22.617  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:22.618  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 14:17:22.618  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.618  2712  2783 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:22.618  2712  2783 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 14:17:22.619  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.619  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.619  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:22.619  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.619  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:22.620  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.620  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.620  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.620  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.620  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:22.620  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.620  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.620  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.620  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.620  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.621  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.621  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.622  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.622  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.622  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.622  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.623  3796  3847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 14:17:22.623  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.624  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.624  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.624  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.624  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.624  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.624  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.624  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.624  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.624  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.624  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.625  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.625  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.625  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.626  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.626  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.626  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.626  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.627  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:22.628  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.628  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.628  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.628  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.628  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.628  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.629  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.629  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.629  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.629  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.629  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.629  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.629  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.629  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.630  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.630  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.630  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.631  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.631  3796  3847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 14:17:22.631  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.632  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.632  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:22.632  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.632  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.632  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.632  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.632  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.632  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.632  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.633  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.633  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.633  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.633  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.634  2712  2766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 14:17:22.634  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.634  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.634  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.634  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.634  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.635  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 14:17:22.635  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.635  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.635  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:22.636  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.636  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.636  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.637  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.637  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.637  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.637  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.637  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.637  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.637  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.637  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.639  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.639  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.639  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.639  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.640  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:22.640  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:22.640  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 14:17:22.640  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 14:17:22.640  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:22.641  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:22.641  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.641  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.641  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.642  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.642  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 14:17:22.642  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:22.642  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.642  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.642  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.642  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:22.642  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.645  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:22.645  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.645  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.645  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.645  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.646  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.647  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.647  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.647  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.648  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:22.649  3796  3847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:22.649  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 14:17:22.653  2712  2766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 14:17:22.653  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.654  2712  2783 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:22.654  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:22.654  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 14:17:22.655  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 14:17:22.655  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 14:17:22.656  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:22.656  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 14:17:22.656  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:22.657  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:22.658  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:22.659  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:22.659  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 14:17:22.659  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:22.659  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 14:17:22.659  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:22.659  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 14:17:22.659  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 14:17:22.660  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:22.660  3796  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:22.660  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:22.663  2712  2766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 14:17:22.663  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:22.663  2712  2783 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 14:17:22.664  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-26 14:17:22.665  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 14:17:22.665  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-26 14:17:22.666  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-26 14:17:22.666  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 14:17:22.666  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 14:17:22.666  3796  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 14:17:22.666  3796  3847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-26 14:17:22.666  3796  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 390)
08-26 14:17:22.667  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.667  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.667  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.668  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:22.668  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.668  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.668  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 14:17:22.669  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.669  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.669  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.669  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:22.669  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.669  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.669  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.669  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.669  3796  3860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:22.670  3796  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 390
08-26 14:17:22.670  3796  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 390)
08-26 14:17:22.670  3796  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 390)
,08-26 14:17:22.670  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.670  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.670  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.671  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.671  2712  2766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 14:17:22.671  2712  2766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:22.672  3796  3847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-26 14:17:22.673  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.673  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.673  3796  3860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 390)
08-26 14:17:22.673  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:22.673  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.673  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.674  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.674  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.674  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.674  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.674  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.674  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.674  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.674  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.674  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.675  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.675  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.675  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.675  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.676  3796  3847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 14:17:22.676  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.676  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.677  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.677  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.677  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.677  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.677  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.677  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.677  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.677  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.677  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.677  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.677  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.677  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.679  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.679  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.679  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.679  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 14:17:22.680  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:22.680  3796  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:22.680  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:22.680  3796  3847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:22.680  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 14:17:22.680  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:22.681  3796  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 14:17:22.681  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.681  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.681  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.681  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.681  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.681  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.681  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.681  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.682  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.682  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.682  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.682  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.682  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.682  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.683  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.683  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.683  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.684  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.684  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.684  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.684  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.684  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.684  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.684  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.684  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.684  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:22.685  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.685  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.685  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.685  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.685  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.685  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.685  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.685  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.685  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.685  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.686  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.686  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.686  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.686  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
,08-26 14:17:22.686  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.686  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.686  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.686  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.686  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.686  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.686  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.687  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.687  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.688  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.688  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.689  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 14:17:22.689  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:22.690  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 14:17:22.691  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-26 14:17:22.691  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 14:17:22.691  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-26 14:17:22.691  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 14:17:22.691  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:22.691  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.692  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 14:17:22.692  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 14:17:22.692  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 14:17:22.692  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.692  3796  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 14:17:22.692  3796  3796 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-26 14:17:22.692  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.692  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.692  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:22.692  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:22.692  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:22.692  3796  3862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:22.693  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.693  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.693  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:22.694  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:22.694  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:22.694  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:22.694  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.694  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.694  3796  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 14:17:22.694  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.694  3796  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 14:17:22.694  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.694  3796  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 14:17:22.695  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.695  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.695  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.695  3796  3796 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 14:17:22.695  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.695  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.695  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.695  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:22.695  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.695  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.695  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.695  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.696  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.696  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.696  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.696  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.697  3796  3847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 14:17:22.698  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:22.698  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:22.698  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:22.698  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.698  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:22.698  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.698  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.699  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.699  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.699  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
,08-26 14:17:22.699  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.699  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.699  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.699  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.699  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.699  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.699  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.700  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.700  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.700  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.701  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
,08-26 14:17:22.704  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.704  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.704  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.704  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.705  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.705  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.705  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.705  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.705  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.705  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.705  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.705  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.705  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.705  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.706  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.706  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.706  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.706  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.707  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:22.707  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:22.707  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:22.707  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:22.707  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.707  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.707  3796  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a954be1 not in the list
08-26 14:17:22.707  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.707  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.708  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:22.708  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.708  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:22.708  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:22.708  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:22.709  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:22.709  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:22.709  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:22.709  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb60d06 not in the list
08-26 14:17:22.710  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 14:17:22.710  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 14:17:22.710  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 14:17:22.710  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:22.710  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 14:17:22.710  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 14:17:22.712  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:22.712  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 14:17:22.712  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 14:17:22.713  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:22.713  3796  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 14:17:22.713  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:22.713  3796  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 14:17:22.713  3796  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 14:17:22.713  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 14:17:22.713  3796  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-26 14:17:22.714  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 14:17:22.714  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 14:17:22.714  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 14:17:22.714  3796  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 14:17:22.715  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:22.715  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2016c78 added. We now have 2 listener(s)
08-26 14:17:22.715  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:22.717  3796  3847 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 14:17:22.718   872  1716 D WifiService: setWifiEnabled: true pid=3796, uid=10000
08-26 14:17:22.718   872  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:22.718  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:22.718  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@677ef51 added. We now have 3 listener(s)
08-26 14:17:22.719  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:22.724  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:22.724  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a1c3b6 added. We now have 4 listener(s)
08-26 14:17:22.724  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:22.725  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:22.725  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@445f8b7 added. We now have 5 listener(s)
08-26 14:17:22.725  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:22.727   872  1397 D WifiService: setWifiEnabled: false pid=3796, uid=10000
08-26 14:17:22.727   872  1397 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:22.731  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:22.733  2712  2761 D BluetoothAdapterState: Current state: ON, message: 23
08-26 14:17:22.733  2712  2761 D BluetoothAdapterProperties: Setting state to 13
,08-26 14:17:22.733  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 14:17:22.734  2712  2761 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:22.734  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.734  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:22.735  2712  2761 I BluetoothAdapterState: Entering PendingCommandState
08-26 14:17:22.736  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.736  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.736  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:22.738  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.739  2712  2712 D BluetoothMapService: onReceive
08-26 14:17:22.739  2712  2712 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.739  2712  2712 D BluetoothMapService: STATE_TURNING_OFF
08-26 14:17:22.739  2712  2712 D BluetoothMapService: MAP Service closeService in
08-26 14:17:22.739  2712  2712 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 14:17:22.739  2712  2712 D ObexServerSockets0: shutdown(block = true)
08-26 14:17:22.740  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 14:17:22.740  2712  2918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 14:17:22.740  2712  2712 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 14:17:22.740  2712  2907 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 14:17:22.741  2712  2919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 14:17:22.741  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.742  2712  2712 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:22.742  2712  3456 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:22.743  2712  3456 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 14:17:22.744  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.744  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:22.745  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.745  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:22.747  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 14:17:22.748  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.749   872  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 14:17:22.749   872  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 14:17:22.749   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 14:17:22.749   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:22.757   872  1877 D DhcpClient: Clearing IP address
,08-26 14:17:22.757   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:22.764  1504  2447 V NativeCrypto: Read error: ssl=0x9aeddc00: I/O error during system call, Connection timed out
,08-26 14:17:22.766  1504  2447 V NativeCrypto: SSL shutdown failed: ssl=0x9aeddc00: I/O error during system call, Broken pipe
,08-26 14:17:22.766   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:22.768   872   882 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-26 14:17:22.769   872   885 I ActivityManager: Start proc 3865:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 14:17:22.770  2712  2766 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:22.770  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 14:17:22.773   872  1859 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 14:17:22.777   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 14:17:22.777   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 14:17:22.778  2712  2712 D HeadsetService: Received stop request...Stopping profile...
08-26 14:17:22.779   872  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 14:17:22.779   395   395 E Parcel  : Reading a NULL string not supported here.
08-26 14:17:22.779   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 14:17:22.780  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:22.780  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:22.781  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.781  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:22.783   872  1859 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-26 14:17:22.784  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:22.784  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:22.786   872  1890 D DhcpClient: Receive thread stopped
08-26 14:17:22.787  1375  2110 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.787  1375  1375 D HeadsetProfile: Bluetooth service disconnected
,08-26 14:17:22.787   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.787   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.788  1969  2165 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.788   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:22.788  2712  2712 D A2dpService: Received stop request...Stopping profile...
,08-26 14:17:22.788  2712  2912 D A2dpStateMachine: Exit Disconnected: -1
,08-26 14:17:22.788  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:22.788  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:22.790   872   872 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:22.790  1375  1375 D BluetoothA2dp: Proxy object disconnected
,08-26 14:17:22.791   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:22.792  2712  2712 D HidService: Received stop request...Stopping profile...
,08-26 14:17:22.793  2712  2712 D HidService: Stopping Bluetooth HidService
08-26 14:17:22.794  1375  1375 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:22.794  1375  1375 D HidProfile: Bluetooth service disconnected
,08-26 14:17:22.794  2712  2712 V BluetoothAdapterState: isTurningOff()=true
,08-26 14:17:22.794  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.794  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.794  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.797  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:22.797  2712  2766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 14:17:22.797  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:22.797  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:22.797  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 14:17:22.797  2712  2766 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 14:17:22.798  2712  2712 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:22.799  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:22.800   872  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 14:17:22.801  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.801  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.803  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.803  2712  2712 D HealthService: Received stop request...Stopping profile...
08-26 14:17:22.805   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 14:17:22.808  2712  2766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 14:17:22.808  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:22.809  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:22.809  2712  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:22.809  2712  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:22.809  2712  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:22.809  2712  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:22.808  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:22.809  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:22.810  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.810  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:22.811  2712  2712 D PanService: Received stop request...Stopping profile...
08-26 14:17:22.812  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:22.812  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:22.812  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:22.812  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.812  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.812  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.813  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:22.813  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:22.813  2712  2712 D BluetoothMapService: Received stop request...Stopping profile...
08-26 14:17:22.813  2712  2712 D BluetoothMapService: stop()
08-26 14:17:22.814  2712  2712 D BluetoothMapAppObserver: deinitObservers()
08-26 14:17:22.814  2712  2712 D BluetoothMapAppObserver: removeReceiver()
08-26 14:17:22.816  1375  1375 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:22.816   872  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 14:17:22.816  1375  1375 D PanProfile: Bluetooth service disconnected
,08-26 14:17:22.816  1375  1375 D BluetoothMap: Proxy object disconnected
08-26 14:17:22.816  1375  1375 D MapProfile: Bluetooth service disconnected
08-26 14:17:22.817  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:22.817  2712  2766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 14:17:22.817  2712  2712 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 14:17:22.818  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:22.818  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.818  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.818  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.818  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:22.818  2712  2766 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 14:17:22.819  2712  2712 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 14:17:22.819  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:22.819  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.819  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.819  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.821  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:22.822  2712  2712 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 14:17:22.822  2712  2712 D BluetoothMapService: MAP Service closeService in
08-26 14:17:22.823  2712  2712 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:22.823  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:22.823  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:22.823  2712  2712 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:22.824  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 14:17:22.824  2712  2761 D BluetoothAdapterProperties: Setting state to 15
08-26 14:17:22.824  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 14:17:22.825  1375  2110 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 14:17:22.826  2712  2761 I BluetoothAdapterState: Entering BleOnState
08-26 14:17:22.826  1969  1989 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.826  1375  1386 D BluetoothPan: onBluetoothStateChange on: false
08-26 14:17:22.827  1375  1399 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 14:17:22.828  1375  2110 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.828  2712  2712 D BluetoothMapService: cleanup()
08-26 14:17:22.828  1375  1386 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:22.828  2712  2712 D BluetoothMapService: MAP Service closeService in
,08-26 14:17:22.829   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.829   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.829   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.829   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:22.829  1375  1399 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.830  2712  2761 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 14:17:22.830  2712  2761 D BluetoothAdapterProperties: Setting state to 16
08-26 14:17:22.830  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 14:17:22.831  2712  2761 D BluetoothAdapterProperties: onBleDisable
08-26 14:17:22.831  2712  2761 I BluetoothAdapterState: Entering PendingCommandState
08-26 14:17:22.832  2712  2762 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 14:17:22.832  2712  2766 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:22.833  2712  2893 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 14:17:22.833  2712  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:22.834  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.841  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.841  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.842  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.846  1896  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:22.852   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 14:17:22.860  3865  3865 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 14:17:22.869   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:22.870   872  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 14:17:22.870   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:22.874   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:22.875  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:22.876  3406  3406 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2790cbf and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 14:17:22.877  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.885  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:22.891  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:22.903   872  2039 I ActivityManager: Start proc 3885:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 14:17:22.904   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b27c263:true
,08-26 14:17:22.920  3865  3865 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 14:17:22.924  3865  3865 D BluetoothMap: Create BluetoothMap proxy object
,08-26 14:17:22.926   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 14:17:22.927   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 14:17:22.932  3865  3865 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 14:17:22.938  3885  3885 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 14:17:22.947  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:22.957   872  2005 I ActivityManager: Killing 2985:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 14:17:23.035  2712  2766 I bt_hci  : shut_down
,08-26 14:17:23.036  2712  2784 D bt_hwcfg: hw_epilog_process
,08-26 14:17:23.049  2712  2784 I bt_vendor: low_power_mode_cb
,08-26 14:17:23.070  2712  2784 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 14:17:23.070  2712  2784 I bt_vendor: epilog_cb
,08-26 14:17:23.070  2712  2784 I bt_hci  : epilog_finished_callback
,08-26 14:17:23.077  2712  2766 I bt_hci_h4: hal_close
,08-26 14:17:23.078  2712  2766 I bt_userial_vendor: device fd = 51 close
,08-26 14:17:23.096  3885  3885 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 14:17:23.096  3885  3885 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 14:17:23.096  3885  3885 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 14:17:23.096  3885  3885 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:23.096  3885  3885 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.,java:290)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.096  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:23.097  3885  3885 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08,-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:23.097  3885  3885 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:23.097  3885  3885 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:23.097  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:23.137   872  1397 I ActivityManager: Start proc 3915:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-26 14:17:23.139   872  1397 I ActivityManager: Killing 3406:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 14:17:23.195  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:23.248  3915  3915 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 14:17:23.256  2712  2762 D bt_stack_manager: event_shut_down_stack finished.
08-26 14:17:23.256  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-26 14:17:23.258  2712  2712 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:23.258  2712  2761 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 14:17:23.259  2712  2712 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:23.259  2712  2712 D BtGatt.GattService: stop()
08-26 14:17:23.259  2712  2712 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 14:17:23.260  2712  2712 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:23.260  2712  2712 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:23.260  2712  2712 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:23.260  2712  2712 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 14:17:23.260  2712  2761 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 14:17:23.261  2712  2761 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:23.261  2712  2761 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 14:17:23.261  2712  2761 I BluetoothAdapterState: Entering OffState
,08-26 14:17:23.262   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 14:17:23.273  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 14:17:23.273  2712  2712 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-26 14:17:23.273  2712  2712 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 14:17:23.274  2712  2762 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 14:17:23.275  2712  2762 D bt_stack_manager: event_clean_up_stack finished.
,08-26 14:17:23.286  2712  2712 I art     : System.exit called, status: 0
,08-26 14:17:23.286  2712  2712 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:23.333  3885  3903 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 14:17:23.339  3915  3915 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 14:17:23.343   872  2016 I ActivityManager: Process com.android.bluetooth (pid 2712) has died
,08-26 14:17:23.353   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ce38f54:true
,08-26 14:17:23.372  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:23.389   872  1919 I ActivityManager: Start proc 3944:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 14:17:23.392  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:23.448  3944  3944 D AdapterServiceConfig: Adding HeadsetService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding A2dpService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding HidService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding HealthService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding PanService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding GattService
08-26 14:17:23.449  3944  3944 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 14:17:23.454   872  1397 I ActivityManager: Killing 3491:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 14:17:23.492  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:23.512  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 14:17:23.516  1701  1701 D SystemUpdateService: onCreate
08-26 14:17:23.517  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 14:17:23.521  1701  3956 I SystemUpdateService: active receiver: enabled
,08-26 14:17:23.524  1701  3956 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 14:17:23.525  1701  3956 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 14:17:23.525  1701  3956 I SystemUpdateService: now status is 0 (complete)
,08-26 14:17:23.525  1701  3956 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 14:17:23.525  1701  3956 I SystemUpdateService: file has been verified
08-26 14:17:23.526  1701  3956 I SystemUpdateService: OTA package size = 12249756
,08-26 14:17:23.531  1701  3956 I SystemUpdateService: showing system update notification
,08-26 14:17:23.550  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 14:17:23.552  1701  2408 I iu.UploadsManager: num queued entries: 0
,08-26 14:17:23.555  1701  2408 I iu.UploadsManager: num updated entries: 0
,08-26 14:17:23.555  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 14:17:23.557  1701  2408 I iu.SyncManager: NEXT; no task
,08-26 14:17:23.557  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 14:17:23.573   872  2015 I ActivityManager: Start proc 3958:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 14:17:23.576  1701  1701 D SystemUpdateService: onDestroy
,08-26 14:17:23.618  3958  3958 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 14:17:23.622  3958  3958 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:23.629  3958  3958 D SprintDMHelper: simOperator: 
08-26 14:17:23.629  3958  3958 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 14:17:23.643   872  2016 I ActivityManager: Start proc 3970:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-26 14:17:23.644   872  2016 I ActivityManager: Killing 1718:android.process.acore/u0a5 (adj 15): empty #17
,08-26 14:17:23.831   872   882 I ActivityManager: Start proc 3985:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 14:17:23.836  3082  3984 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 14:17:23.840   872  2123 I ActivityManager: Killing 3652:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 14:17:23.914  3985  3985 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 14:17:23.964  3985  3985 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 14:17:23.964  3985  3985 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 14:17:23.964  3985  3985 I GAv4    :   adb logcat -s GAv4
,08-26 14:17:23.984  3985  3985 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:17:23.990  3985  3985 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:17:24.022  3985  4002 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 14:17:24.114  3985  3985 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 14:17:24.156  3985  3985 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 14:17:24.166  3985  3985 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4945-4951)
08-26 14:17:24.167  3985  3985 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:24.174  3985  3985 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8f6cac1}
08-26 14:17:24.175  3985  3985 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:24.175  3985  3985 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:17:24.181  3985  3985 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 14:17:24.182  3985  3985 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 14:17:24.202  3985  3985 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 14:17:24.213  3985  3985 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:17:24.213  3985  3985 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:17:24.213  3985  3985 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 14:17:24.213  3985  3985 I Adreno  : Build Date                       : 10/20/15
08-26 14:17:24.213  3985  3985 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 14:17:24.213  3985  3985 I Adreno  : Local Branch                     : M14
08-26 14:17:24.213  3985  3985 I Adreno  : Remote Branch                    : 
08-26 14:17:24.213  3985  3985 I Adreno  : Remote Branch                    : 
08-26 14:17:24.213  3985  3985 I Adreno  : Reconstruct Branch               : 
,08-26 14:17:24.262  3985  3985 I NSApplication: Starting up...
,08-26 14:17:24.276  3985  4031 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 14:17:24.303   872  2016 I ActivityManager: Start proc 4036:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 14:17:24.305   872  2016 I ActivityManager: Killing 3667:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 14:17:24.390  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 14:17:24.548   872  2123 I ActivityManager: Killing 3475:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 14:17:25.740   872   883 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,08-26 14:17:25.740   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:25.754   872  1316 D WifiConfigStore: Loading config and enabling all networks 
08-26 14:17:25.764  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:25.764  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:25.764  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.765  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:25.767  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:25.768  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:25.768  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:25.768  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:25.790   872  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-26 14:17:25.791   872  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 14:17:25.792   872  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 14:17:25.793   872  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 14:17:25.793   872  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 14:17:25.793   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 14:17:25.794   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 14:17:25.807   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 14:17:25.809   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:25.810   872  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-26 14:17:25.810   872  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 14:17:25.813   872  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 14:17:25.813   872  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 14:17:25.831   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:25.844   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:27.427   872  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.02 rxSuccessRate=1.61 delta 1000 -> 1000
,08-26 14:17:27.429   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 14:17:27.429   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:27.443   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 14:17:27.506   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 14:17:27.512  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 14:17:27.954  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 14:17:27.990  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 14:17:27.991  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 14:17:27.999   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:28.012   872  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 14:17:28.013   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 14:17:28.013   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:28.028   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:28.035   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:28.035   872  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 14:17:28.045   872  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 14:17:28.046   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 14:17:28.062   872  4061 D DhcpClient: Receive thread started
,08-26 14:17:28.141   872  1316 E native  : do suspend false
,08-26 14:17:28.163   872  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 14:17:28.179   872  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172683, domain null
,08-26 14:17:28.180   872  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172683 seconds
,08-26 14:17:28.185   872  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 14:17:28.197   872  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 14:17:28.198   872  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 14:17:28.205   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:28.217   872  1877 D DhcpClient: Scheduling renewal in 86399s
,08-26 14:17:28.217   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 14:17:28.235   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 14:17:28.238   872  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 14:17:28.238   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:28.239   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 14:17:28.244   872  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 14:17:28.257   872  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 14:17:28.297   872  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 14:17:28.298   872  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 14:17:28.299   872  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 14:17:28.300   872  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 14:17:28.301   872  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 14:17:28.309   872  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 14:17:28.313   872  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 14:17:28.313   872  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 14:17:28.314   872  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-26 14:17:28.314   872  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 14:17:28.314   872  1318 D ConnectivityService:    accepting network in place of null
,08-26 14:17:28.314   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 14:17:28.315   872  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 14:17:28.349   872  4060 D NetlinkSocketObserver: NeighborEvent{elapsedMs=139134, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 14:17:28.352   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:28.400   872   883 I ActivityManager: Killing 3690:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 14:17:28.411   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:28.416   872  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 14:17:28.416   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:28.428   872  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 14:17:28.430   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:28.436   872   885 W BroadcastQueue: Failure sending broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 14:17:28.436   872   885 W BroadcastQueue: android.os.RemoteException: app.thread must not be null
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:594)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:667)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:28.436   872   885 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 14:17:28.438  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:28.438  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:28.438  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.438  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:28.440  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:28.441  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:28.441  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:28.441  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:28.442   872  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:814::200e
,08-26 14:17:28.451  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 14:17:28.456  1701  1701 D SystemUpdateService: onCreate
,08-26 14:17:28.463  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 14:17:28.488  1701  4071 I SystemUpdateService: active receiver: enabled
,08-26 14:17:28.491  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 14:17:28.493  1701  2408 I iu.UploadsManager: num queued entries: 0
,08-26 14:17:28.493  1701  2408 I iu.UploadsManager: num updated entries: 0
08-26 14:17:28.494  1701  2408 I iu.SyncManager: NEXT; no task
,08-26 14:17:28.509  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 14:17:28.510  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 14:17:28.512  3958  3958 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:28.515   872  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:28 GMT], X-Android-Received-Millis=[1472213848515], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472213848487]}
,08-26 14:17:28.517   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 14:17:28.517   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-26 14:17:28.518   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 14:17:28.520   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 14:17:28.521  1701  4074 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 14:17:28.522  1701  4074 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 14:17:28.523  3958  3958 D SprintDMHelper: simOperator: 
08-26 14:17:28.523  3958  3958 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 14:17:28.528  1701  4074 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 14:17:28.539  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:28.541  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:28.555  1701  4071 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 14:17:28.569  1701  4071 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-26 14:17:28.569  1701  4071 I SystemUpdateService: now status is 0 (complete)
08-26 14:17:28.569  1701  4071 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 14:17:28.569  1701  4071 I SystemUpdateService: file has been verified
08-26 14:17:28.570  1701  4071 I SystemUpdateService: OTA package size = 12249756
,08-26 14:17:28.590  1701  4071 I SystemUpdateService: showing system update notification
,08-26 14:17:28.606  1504  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 14:17:28.606  1504  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 14:17:28.606  1504  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:28.606  1504  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:28.623  1701  1701 D SystemUpdateService: onDestroy
,08-26 14:17:28.656  1701  4074 E MDM     : [172] SitrepService.a: Error sending sitrep.
,08-26 14:17:28.718  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-26 14:17:28.718  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-26 14:17:28.718  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:28.718  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:28.730  3000  4080 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 14:17:28.730  3000  4080 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jdm.a(PG:82)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jcs.o(PG:406)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jcn.a(PG:1379)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jcs.i(PG:143)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at blb.a(PG:3937)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at czp.a(PG:18188)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at czp.a(PG:9081)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at czq.run(PG:1686)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:28.730  3000  4080 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jdj.a(PG:4091)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jdj.a(PG:1125)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jdm.a(PG:77)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	... 12 more
08-26 14:17:28.730  3000  4080 E HttpOperation: Caused by: faj: BadAuthentication
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at fal.a(PG:38)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	at jdj.a(PG:4089)
08-26 14:17:28.730  3000  4080 E HttpOperation: 	... 14 more
,08-26 14:17:28.749   872  1919 D WifiService: setWifiEnabled: false pid=3796, uid=10000
,08-26 14:17:28.749   872  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 14:17:28.750  3082  4078 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 14:17:28.770  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 14:17:28.772   872  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 14:17:28.772   872  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 14:17:28.772   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 14:17:28.772   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:28.775  1504  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 14:17:28.775  1504  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 14:17:28.776  1504  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:28.776  1504  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 14:17:28.780   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:28.780   872  1877 D DhcpClient: Clearing IP address
08-26 14:17:28.782   371   870 D CommandListener: Setting iface cfg
08-26 14:17:28.785  1504  4084 V NativeCrypto: Read error: ssl=0x9b4cc800: I/O error during system call, Connection timed out
08-26 14:17:28.786  1504  4084 V NativeCrypto: SSL shutdown failed: ssl=0x9b4cc800: I/O error during system call, Broken pipe
08-26 14:17:28.787   872  4061 D DhcpClient: Receive thread stopped
,08-26 14:17:28.790   872  2005 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-26 14:17:28.790   872  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-26 14:17:28.790   872  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:814::200e
08-26 14:17:28.793   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 14:17:28.794   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 14:17:28.794   872  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-26 14:17:28.794   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 14:17:28.797   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 14:17:28.797   872  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:814::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 14:17:28.798   395   395 E Parcel  : Reading a NULL string not supported here.
,08-26 14:17:28.803   872  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 14:17:28.811   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:28.814  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:28.814  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:28.814  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.815  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:28.815   872  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 14:17:28.815  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:28.815  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:28.815  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:28.815  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:28.816  1896  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:28.827  3000  4080 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 14:17:28.827  3000  4080 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jdm.a(PG:82)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jcs.o(PG:406)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jcn.a(PG:1379)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jcs.i(PG:143)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at hec.a(PG:42)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at hee.a(PG:102)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at czr.a(PG:65)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at kka.a(PG:108)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at czp.a(PG:19176)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at czp.a(PG:9081)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at czq.run(PG:1686)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:28.827  3000  4080 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jdj.a(PG:4091)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jdj.a(PG:1125)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jdm.a(PG:77)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	... 15 more
08-26 14:17:28.827  3000  4080 E HttpOperation: Caused by: faj: BadAuthentication
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at fal.a(PG:38)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	at jdj.a(PG:4089)
08-26 14:17:28.827  3000  4080 E HttpOperation: 	... 17 more
,08-26 14:17:28.828  3000  4080 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 14:17:28.828  3000  4080 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at hec.a(PG:42)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at hee.a(PG:102)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at czr.a(PG:65)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at kka.a(PG:108)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	... 15 more
08-26 14:17:28.828  3000  4080 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at fal.a(PG:38)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 14:17:28.828  3000  4080 E ExperimentLoader: 	... 17 more
08-26 14:17:28.835   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:28.858   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:28.859   872  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 14:17:28.859   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:28.860   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:28.862  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:28.863  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:28.870  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 14:17:28.873  1701  1701 D SystemUpdateService: onCreate
,08-26 14:17:28.875  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 14:17:28.882  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-26 14:17:28.884  1701  2408 I iu.UploadsManager: num queued entries: 0
,08-26 14:17:28.899  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 14:17:28.900  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 14:17:28.903  3958  3958 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:28.909  3958  3958 D SprintDMHelper: simOperator: 
,08-26 14:17:28.909  3958  3958 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 14:17:28.915  1701  2408 I iu.UploadsManager: num updated entries: 0
,08-26 14:17:28.919   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 14:17:28.920   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 14:17:28.922  1701  4096 I SystemUpdateService: active receiver: enabled
,08-26 14:17:28.932   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130374, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-26 14:17:28.930  1701  2408 I iu.SyncManager: NEXT; no task
,08-26 14:17:28.959  1701  4096 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 14:17:28.961  3082  4101 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 14:17:28.982  1701  4096 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 14:17:28.982  1701  4096 I SystemUpdateService: now status is 0 (complete)
08-26 14:17:28.982  1701  4096 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 14:17:28.982  1701  4096 I SystemUpdateService: file has been verified
08-26 14:17:28.982  1701  4096 I SystemUpdateService: OTA package size = 12249756
,08-26 14:17:28.992  1701  4096 I SystemUpdateService: showing system update notification
,08-26 14:17:29.003  1701  1701 D SystemUpdateService: onDestroy
,08-26 14:17:29.417   872  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 14:17:31.800  3944  3944 D BluetoothAdapterState: make() - Creating AdapterState,
08-26 14:17:31.800   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f9a02f:true
,08-26 14:17:31.806  3944  3944 I bt_bluedroid: init
,08-26 14:17:31.807  3944  4103 I BluetoothAdapterState: Entering OffState
,08-26 14:17:31.809  3944  4104 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 14:17:31.809  3944  4104 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:31.809  3944  4104 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 14:17:31.809  3944  4104 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 14:17:31.810  3944  3944 I bt_bluedroid: get_profile_interface socket
,08-26 14:17:31.815  3944  3944 I bt_bluedroid: get_profile_interface sdp
,08-26 14:17:31.816  3944  4107 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 14:17:31.819  3944  4107 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 14:17:31.819  3944  3954 I bt_bluedroid: config_hci_snoop_log
,08-26 14:17:31.822   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 14:17:31.829  3944  4103 D BluetoothAdapterState: Current state: OFF, message: 0
08-26 14:17:31.830  3944  4103 D BluetoothAdapterProperties: Setting state to 14
,08-26 14:17:31.830  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 14:17:31.835  3944  4103 D BluetoothBondStateMachine: make
,08-26 14:17:31.838  3944  4108 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 14:17:31.845  3944  3944 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 14:17:31.846  3944  4103 I BluetoothAdapterState: Entering PendingCommandState
,08-26 14:17:31.849  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:31.850  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:31.851  3944  3944 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:31.851  3944  3944 D BtGatt.GattService: start()
08-26 14:17:31.851  3944  3944 I bt_bluedroid: get_profile_interface gatt
08-26 14:17:31.853  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:31.853  3944  3944 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:31.862  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:31.862  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:31.863  3944  3944 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 14:17:31.863  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:31.865  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 14:17:31.866  3944  4103 I bt_bluedroid: enable
08-26 14:17:31.866  3944  4104 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 14:17:31.866  3944  4104 I bt_hci  : start_up
,08-26 14:17:31.872  3944  4104 I bt_vendor: alloc value 0xb3a29189
08-26 14:17:31.872  3944  4104 I bt_vendor: init
08-26 14:17:31.872  3944  4104 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 14:17:31.872  3944  4104 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 14:17:31.979  3944  4104 D bt_hci  : start_up starting async portion
,08-26 14:17:31.980  3944  4111 I bt_hci  : event_finish_startup
,08-26 14:17:31.980  3944  4111 I bt_hci_h4: hal_open
08-26 14:17:31.980  3944  4111 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 14:17:31.991  3944  4111 I bt_userial_vendor: device fd = 51 open
,08-26 14:17:32.023  3944  4111 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 14:17:32.054  3944  4111 D bt_hwcfg: Chipset BCM4354A2
,08-26 14:17:32.055  3944  4111 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 14:17:32.056  3944  4111 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 14:17:32.766  3944  4111 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 14:17:32.768  3944  4111 D bt_hwcfg: Settlement delay -- 100 ms
08-26 14:17:32.768  3944  4111 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 14:17:32.884  3944  4111 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 14:17:32.886  3944  4111 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 14:17:32.916  3944  4111 I bt_hwcfg: vendor lib fwcfg completed
,08-26 14:17:32.916  3944  4111 I bt_vendor: firmware callback
,08-26 14:17:32.916  3944  4111 I bt_hci  : firmware_config_callback
,08-26 14:17:32.928  3944  4113 I bt_btu  : btu_task pending for preload complete event
,08-26 14:17:32.928  3944  4113 I bt_btu_task: Bluetooth chip preload is complete
08-26 14:17:32.928  3944  4113 I bt_btu  : btu_task received preload complete event
,08-26 14:17:32.938  3944  4113 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:32.938  3944  4113 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 14:17:32.939  3944  4113 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 14:17:32.939  3944  4113 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 14:17:32.939  3944  4113 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 14:17:32.940  3944  4113 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 14:17:32.940  3944  4113 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:32.940  3944  4113 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 14:17:32.940  3944  4113 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 14:17:32.941  3944  4113 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 14:17:32.941  3944  4113 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 14:17:32.941  3944  4113 I         : BTE_InitTraceLevels -- TRC_GATT,
08-26 14:17:32.941  3944  4113 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 14:17:32.942  3944  4113 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 14:17:32.942  3944  4113 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 14:17:33.077  3944  4113 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a6d9d
,08-26 14:17:33.077  3944  4113 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a6d9d 
,08-26 14:17:33.088  3944  4107 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 14:17:33.090  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 14:17:33.092  3944  4107 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 14:17:33.096  3944  4107 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 14:17:33.102  3944  4107 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:33.103  3944  4107 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:33.103  3944  4107 D bt_hci  : do_postload posting postload work item
,08-26 14:17:33.103  3944  4111 I bt_hci  : event_postload
,08-26 14:17:33.103  3944  4111 I bt_vendor: sco_config_cb
,08-26 14:17:33.104  3944  4111 I bt_hci  : sco_config_callback postload finished.
,08-26 14:17:33.106  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:33.107  3944  4107 D bt_bte_conf: Device ID record 1 : primary
,08-26 14:17:33.107  3944  4107 D bt_bte_conf:   vendorId            = 000f
08-26 14:17:33.107  3944  4107 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 14:17:33.107  3944  4107 D bt_bte_conf:   product             = 1200
,08-26 14:17:33.107  3944  4107 D bt_bte_conf:   version             = 1436
08-26 14:17:33.107  3944  4107 D bt_bte_conf:   clientExecutableURL = 
,08-26 14:17:33.107  3944  4107 D bt_bte_conf:   serviceDescription  = 
,08-26 14:17:33.107  3944  4107 D bt_bte_conf:   documentationURL    = 
08-26 14:17:33.107  3944  4107 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 14:17:33.107  3944  4104 D bt_stack_manager: event_start_up_stack finished
,08-26 14:17:33.108  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 14:17:33.108  3944  4103 D BluetoothAdapterProperties: Setting state to 15
,08-26 14:17:33.108  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 14:17:33.111  3944  4111 I bt_vendor: low_power_mode_cb
,08-26 14:17:33.111  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.112  3944  4103 I BluetoothAdapterState: Entering BleOnState
08-26 14:17:33.116  3944  4103 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 14:17:33.117  3944  4103 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:33.117  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 14:17:33.124  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:33.126  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.127  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:33.131  3944  3944 D HeadsetService: Received start request. Starting profile...
,08-26 14:17:33.133  3944  4103 I BluetoothAdapterState: Entering PendingCommandState
08-26 14:17:33.136  3944  3944 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:33.137  3944  3944 D HeadsetStateMachine: make
,08-26 14:17:33.151  3944  3944 D HeadsetStateMachine: max_hf_connections = 1
,08-26 14:17:33.151  3944  3944 I bt_bluedroid: get_profile_interface handsfree
08-26 14:17:33.151  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 14:17:33.151  3944  4107 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 14:17:33.157  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:33.157  3944  3944 D A2dpService: Received start request. Starting profile...
08-26 14:17:33.158  3944  3944 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 14:17:33.158  3944  3944 I bt_bluedroid: get_profile_interface avrcp
,08-26 14:17:33.163  3944  3944 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:33.163  3944  3944 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:33.163  3944  3944 D A2dpStateMachine: make
,08-26 14:17:33.164  3944  3944 I bt_bluedroid: get_profile_interface a2dp
08-26 14:17:33.164  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 14:17:33.168  3944  4122 D A2dpStateMachine: Enter Disconnected: -2
,08-26 14:17:33.169  3944  3944 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 14:17:33.170  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:33.171  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:33.172  3865  3865 D BluetoothInputDevice: Proxy object connected
08-26 14:17:33.173  3944  3944 D HidService: Received start request. Starting profile...
08-26 14:17:33.173  3944  3944 I bt_bluedroid: get_profile_interface hidhost
08-26 14:17:33.173  3944  3944 D HidService: setHidService(): set to: null
08-26 14:17:33.173  3944  4107 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39883e5
08-26 14:17:33.173  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 14:17:33.173  3865  3865 D HidProfile: Bluetooth service connected
08-26 14:17:33.173  3944  3944 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 14:17:33.174  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:33.175  3944  3944 D HealthService: Received start request. Starting profile...
,08-26 14:17:33.179  3944  3944 I bt_bluedroid: get_profile_interface health
,08-26 14:17:33.180  3944  3944 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 14:17:33.180  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:33.181  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:33.181  3944  3944 D PanService: Received start request. Starting profile...
,08-26 14:17:33.181  3944  3944 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 14:17:33.182  3944  3944 I bt_bluedroid: get_profile_interface pan
,08-26 14:17:33.183  3944  4107 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 14:17:33.183  3865  3865 D PanProfile: Bluetooth service connected
,08-26 14:17:33.190  3944  3944 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:33.191  3944  3944 D BluetoothMapService: Received start request. Starting profile...
,08-26 14:17:33.191  3944  3944 D BluetoothMapService: start()
08-26 14:17:33.192  3865  3865 D BluetoothMap: Proxy object connected
,08-26 14:17:33.192  3865  3865 D MapProfile: Bluetooth service connected
,08-26 14:17:33.193  3865  3865 D BluetoothMap: getConnectedDevices()
08-26 14:17:33.193  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-26 14:17:33.193  3865  3865 D BluetoothMap: Bluetooth is Not enabled
,08-26 14:17:33.193  3944  3944 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 14:17:33.194  3944  3944 D BluetoothMapAppObserver: createReceiver()
,08-26 14:17:33.194  3944  3944 D BluetoothMapAppObserver: initObservers()
,08-26 14:17:33.194  3944  3944 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 14:17:33.200  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:33.200  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:33.200  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:33.200  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:33.201  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:33.201  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:33.201  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:33.201  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:33.201  3944  4120 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false,
,08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOn()=true
,08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:33.202  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:33.203  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:33.203  3944  3944 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:33.203  3944  3944 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:33.203  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:33.203  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:33.203  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 14:17:33.203  3944  4103 D BluetoothAdapterProperties: ScanMode =  20
08-26 14:17:33.203  3944  4103 D BluetoothAdapterProperties: State =  11
08-26 14:17:33.203  3944  4103 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:33.203  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 14:17:33.204  3944  4103 I BluetoothAdapterState: Entering OnState
08-26 14:17:33.204  1375  2110 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 14:17:33.205  3944  4107 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:33.205  3944  4107 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:33.207  1375  1375 D BluetoothInputDevice: Proxy object connected
08-26 14:17:33.207  1375  1375 D HidProfile: Bluetooth service connected
08-26 14:17:33.208  1969  1989 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:33.208  1375  1386 D BluetoothPan: onBluetoothStateChange on: true
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.208  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:33.210  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:33.210  1375  1375 D PanProfile: Bluetooth service connected
08-26 14:17:33.210  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:33.210  1375  2110 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:33.211  1375  1399 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:33.212  3865  3878 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.213  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:33.214  1375  1386 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:33.214  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:33.215  1375  1375 D BluetoothMap: Proxy object connected
08-26 14:17:33.215  1375  1375 D MapProfile: Bluetooth service connected
08-26 14:17:33.215  3865  3877 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 14:17:33.215  1375  1375 D BluetoothMap: getConnectedDevices()
08-26 14:17:33.216  3865  3878 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:33.216   872   889 D BluetoothHeadset: onBlue,toothStateChange: up=true
08-26 14:17:33.216   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:33.216   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:33.216   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:33.217  1375  1399 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:33.217   872   872 D BluetoothA2dp: Proxy object connected
08-26 14:17:33.218  1375  1375 D BluetoothA2dp: Proxy object connected
08-26 14:17:33.219  3865  3877 D BluetoothPan: onBluetoothStateChange on: true
08-26 14:17:33.220  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 14:17:33.220   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 14:17:33.220  3944  3944 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 14:17:33.223  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:33.223  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.224  3865  3865 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 14:17:33.224  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:33.225  3944  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:33.226  3944  3944 D ObexServerSockets: Succeed to create listening sockets 
08-26 14:17:33.226  3944  3944 D ObexServerSockets0: startAccept()
08-26 14:17:33.226  3944  3944 D ObexServerSockets0: prepareForNewConnect()
08-26 14:17:33.227  3865  3865 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 14:17:33.228  3944  3944 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 14:17:33.228  3944  4128 D ObexServerSockets0: Accepting socket connection...
08-26 14:17:33.229  3944  3944 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 14:17:33.230  3944  3944 D BluetoothMapService: onReceive
08-26 14:17:33.230  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.230  3944  3944 D BluetoothMapService: STATE_ON
08-26 14:17:33.230  3944  4129 D ObexServerSockets0: Accepting socket connection...
,08-26 14:17:33.236  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:33.239  3865  3865 D BluetoothA2dp: Proxy object connected
,08-26 14:17:33.243  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:33.247  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:33.252  3865  3865 D BluetoothPbap: Proxy object connected
,08-26 14:17:33.252  1375  1375 D BluetoothPbap: Proxy object connected
08-26 14:17:33.252  1375  1375 D PbapServerProfile: Bluetooth service connected
08-26 14:17:33.252  3865  3865 D PbapServerProfile: Bluetooth service connected
,08-26 14:17:33.257  3944  3944 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 14:17:33.257  3944  3944 D ObexServerSockets0: prepareForNewConnect()
,08-26 14:17:33.262  3944  4133 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:33.278  3944  4137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:33.278  3944  4137 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:33.309  1375  1386 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.309  1375  1375 D HeadsetProfile: Bluetooth service connected
08-26 14:17:33.309   872   872 D BluetoothHeadset: Proxy object connected
08-26 14:17:33.309   872   872 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.309  1969  2171 D BluetoothHeadset: Proxy object connected
08-26 14:17:33.310   872   872 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.312  1375  1399 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.312  1375  1375 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:33.316   872   889 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.317   872   889 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.317   872   889 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.332  3865  3878 D BluetoothHeadset: Proxy object connected
,08-26 14:17:33.333  3865  3865 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:34.764  3944  4103 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 14:17:34.765  3944  4103 D BluetoothAdapterProperties: Setting state to 13
,08-26 14:17:34.765  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:34.767  3944  4103 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 14:17:34.775  3944  4103 I BluetoothAdapterState: Entering PendingCommandState
08-26 14:17:34.779  3944  4107 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:34.783  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 14:17:34.794  3944  3944 D BluetoothMapService: onReceive
,08-26 14:17:34.794  3944  3944 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:34.795  3944  3944 D BluetoothMapService: STATE_TURNING_OFF
08-26 14:17:34.796  3944  3944 D BluetoothMapService: MAP Service closeService in
08-26 14:17:34.796  3944  3944 D BluetoothMapMasInstance0: MAP Service shutdown
,08-26 14:17:34.796  3944  3944 D ObexServerSockets0: shutdown(block = true)
,08-26 14:17:34.797  3944  4128 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 14:17:34.798  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:34.798  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:34.801  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 14:17:34.801  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:34.801  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:34.802  3944  4129 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 14:17:34.803  3944  4115 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 14:17:34.804  3944  3944 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 14:17:34.804  3944  3944 I BtOppRfcommListener: stopping Accept Thread
,08-26 14:17:34.805  3944  4137 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:34.807  3944  4137 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 14:17:34.809  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 14:17:34.810  3944  3944 D HeadsetService: Received stop request...Stopping profile...
08-26 14:17:34.811  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:34.811  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:34.812  3796  3796 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:34.812  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:34.814  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:34.816  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.820  3865  3878 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:34.820  1375  2110 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.821   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:34.821   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 14:17:34.821  1969  2165 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:34.822   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 14:17:34.822  1375  1375 D HeadsetProfile: Bluetooth service disconnected
08-26 14:17:34.824  3944  3944 D A2dpService: Received stop request...Stopping profile...
,08-26 14:17:34.825  3944  4122 D A2dpStateMachine: Exit Disconnected: -1
,08-26 14:17:34.830   872   872 D BluetoothA2dp: Proxy object disconnected
,08-26 14:17:34.831  1375  1375 D BluetoothA2dp: Proxy object disconnected
,08-26 14:17:34.832  3944  3944 D HidService: Received stop request...Stopping profile...
,08-26 14:17:34.832  3944  3944 D HidService: Stopping Bluetooth HidService
,08-26 14:17:34.834  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:34.834  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 14:17:34.835  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:34.835  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:34.838  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:34.840  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:34.840  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:34.841  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 14:17:34.841  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 14:17:34.841  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 14:17:34.841  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 14:17:34.842  3944  4107 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-26 14:17:34.842  3944  3944 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 14:17:34.843  3865  3865 D HeadsetProfile: Bluetooth service disconnected
,08-26 14:17:34.843  3865  3865 D BluetoothA2dp: Proxy object disconnected
,08-26 14:17:34.843  3944  3944 D HealthService: Received stop request...Stopping profile...
08-26 14:17:34.844  3865  3865 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:34.844  3865  3865 D HidProfile: Bluetooth service disconnected
08-26 14:17:34.844  1375  1375 D BluetoothInputDevice: Proxy object disconnected
,08-26 14:17:34.844  1375  1375 D HidProfile: Bluetooth service disconnected
08-26 14:17:34.845  3944  3944 D PanService: Received stop request...Stopping profile...
08-26 14:17:34.846  1375  1375 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 14:17:34.847  3865  3865 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:34.847  1375  1375 D PanProfile: Bluetooth service disconnected
,08-26 14:17:34.847  3865  3865 D PanProfile: Bluetooth service disconnected
08-26 14:17:34.847  3944  3944 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 14:17:34.847  3944  3944 D BluetoothMapService: stop()
08-26 14:17:34.847  3944  3944 D BluetoothMapAppObserver: deinitObservers()
08-26 14:17:34.848  3944  3944 D BluetoothMapAppObserver: removeReceiver()
,08-26 14:17:34.849  1375  1375 D BluetoothMap: Proxy object disconnected
08-26 14:17:34.849  3865  3865 D BluetoothMap: Proxy object disconnected
08-26 14:17:34.849  3865  3865 D MapProfile: Bluetooth service disconnected
08-26 14:17:34.849  1375  1375 D MapProfile: Bluetooth service disconnected,
08-26 14:17:34.849  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:34.849  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 14:17:34.849  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:34.849  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:34.850  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:34.850  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 14:17:34.850  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:34.850  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 14:17:34.850  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
08-26 14:17:34.850  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:34.850  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
08-26 14:17:34.851  3944  4113 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.851  3944  4113 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.851  3944  4113 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:34.851  3944  4113 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.852  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:34.852  3944  4107 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 14:17:34.852  3944  3944 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 14:17:34.854  3865  3865 D BluetoothPbap: Proxy object disconnected
08-26 14:17:34.854  3865  3865 D PbapServerProfile: Bluetooth service disconnected
,08-26 14:17:34.854  3944  3944 V BluetoothAdapterState: isTurningOff()=true
,08-26 14:17:34.854  1375  1375 D BluetoothPbap: Proxy object disconnected
08-26 14:17:34.855  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:34.855  1375  1375 D PbapServerProfile: Bluetooth service disconnected
08-26 14:17:34.855  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:34.855  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:34.855  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:34.855  3944  4107 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 14:17:34.855  3944  3944 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 14:17:34.855  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:34.856  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:34.856  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:34.856  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:34.856  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:34.856  3944  3944 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 14:17:34.857  3944  3944 D BluetoothMapService: MAP Service closeService in,
08-26 14:17:34.857  3944  3944 V BluetoothAdapterState: isTurningOff()=true
08-26 14:17:34.857  3944  3944 V BluetoothAdapterState: isTurningOn()=false
08-26 14:17:34.857  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:34.857  3944  3944 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:34.858  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 14:17:34.858  3944  4103 D BluetoothAdapterProperties: Setting state to 15
08-26 14:17:34.858  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-26 14:17:34.858  3944  4103 I BluetoothAdapterState: Entering BleOnState
08-26 14:17:34.858  3944  3944 D BluetoothMapService: cleanup()
08-26 14:17:34.858  3944  3944 D BluetoothMapService: MAP Service closeService in
,08-26 14:17:34.859  1375  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 14:17:34.860  1969  1980 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.860  1375  1399 D BluetoothPan: onBluetoothStateChange on: false
,08-26 14:17:34.860  1375  2110 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 14:17:34.864  1375  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.864  3865  3877 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 14:17:34.864  1375  1399 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:34.865  3865  3878 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 14:17:34.865  3865  3877 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:34.866   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 14:17:34.866   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 14:17:34.866  3865  3878 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 14:17:34.866  3865  3877 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:34.866   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:34.867   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 14:17:34.867  1375  2110 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-26 14:17:34.867  3865  3878 D BluetoothPan: onBluetoothStateChange on: false
,08-26 14:17:34.868  3944  4103 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 14:17:34.868  3944  4103 D BluetoothAdapterProperties: Setting state to 16
08-26 14:17:34.868  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 14:17:34.868  3944  4103 D BluetoothAdapterProperties: onBleDisable
08-26 14:17:34.869  3944  4103 I BluetoothAdapterState: Entering PendingCommandState
,08-26 14:17:34.869  3944  4104 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 14:17:34.871  3944  4113 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 14:17:34.871  3944  4113 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 14:17:34.871  3944  4107 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:34.872  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:34.873  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 14:17:34.875  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.876  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.877  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 14:17:34.879  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:34.885  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:35.071  3944  4107 I bt_hci  : shut_down
,08-26 14:17:35.082  3944  4111 D bt_hwcfg: hw_epilog_process
,08-26 14:17:35.082  3944  4111 I bt_vendor: low_power_mode_cb
,08-26 14:17:35.109  3944  4111 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 14:17:35.109  3944  4111 I bt_vendor: epilog_cb
,08-26 14:17:35.109  3944  4111 I bt_hci  : epilog_finished_callback
,08-26 14:17:35.117  3944  4107 I bt_hci_h4: hal_close
,08-26 14:17:35.119  3944  4107 I bt_userial_vendor: device fd = 51 close
,08-26 14:17:35.236  3944  4104 D bt_stack_manager: event_shut_down_stack finished.
,08-26 14:17:35.237  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 14:17:35.245  3944  3944 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:35.246  3944  4103 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 14:17:35.247  3944  3944 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 14:17:35.248  3944  3944 D BtGatt.GattService: stop()
08-26 14:17:35.248  3944  3944 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 14:17:35.252  3944  3944 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:35.252  3944  3944 V BluetoothAdapterState: isTurningOn()=false
,08-26 14:17:35.253  3944  3944 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:35.253  3944  3944 V BluetoothAdapterState: isBleTurningOff()=true
08-26 14:17:35.254  3944  4103 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 14:17:35.255  3944  4103 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:35.255  3944  4103 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 14:17:35.256  3944  4103 I BluetoothAdapterState: Entering OffState
08-26 14:17:35.258   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 14:17:35.272  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 14:17:35.272  3944  3944 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 14:17:35.272  3944  4104 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 14:17:35.275  3944  4104 D bt_stack_manager: event_clean_up_stack finished.
,08-26 14:17:35.275  3944  3944 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 14:17:35.277  3944  3944 I art     : System.exit called, status: 0
,08-26 14:17:35.278  3944  3944 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:35.336   872   883 I ActivityManager: Process com.android.bluetooth (pid 3944) has died
,08-26 14:17:36.321   872  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-26 14:17:36.569  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:36.586  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:36.594  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:36.676  1504  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 14:17:36.677  1504  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 14:17:36.678  1504  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:36.678  1504  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:36.731  3543  3543 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 14:17:36.732  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 14:17:36.737  3543  3543 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 14:17:37.762  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:37.762  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:40.771  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:40.771  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dfb2f8d added. We now have 6 listener(s)
,08-26 14:17:40.772  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:40.776  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:40.776  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e6542 added. We now have 7 listener(s)
08-26 14:17:40.777  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:40.778  3796  3847 I System.out: IsBluetoothEnabled
,08-26 14:17:40.791  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:40.839   872   889 I ActivityManager: Start proc 4148:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 14:17:40.956  4148  4148 D AdapterServiceConfig: Adding HeadsetService
,08-26 14:17:40.956  4148  4148 D AdapterServiceConfig: Adding A2dpService
,08-26 14:17:40.956  4148  4148 D AdapterServiceConfig: Adding HidService
,08-26 14:17:40.956  4148  4148 D AdapterServiceConfig: Adding HealthService
,08-26 14:17:40.957  4148  4148 D AdapterServiceConfig: Adding PanService
,08-26 14:17:40.957  4148  4148 D AdapterServiceConfig: Adding GattService
,08-26 14:17:40.957  4148  4148 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 14:17:40.976   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa07432:true
,08-26 14:17:40.976  4148  4148 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 14:17:40.981  4148  4148 I bt_bluedroid: init
,08-26 14:17:40.981  4148  4160 I BluetoothAdapterState: Entering OffState
,08-26 14:17:40.987  4148  4161 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 14:17:40.987  4148  4161 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 14:17:40.988  4148  4161 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 14:17:40.988  4148  4161 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 14:17:40.990  4148  4148 I bt_bluedroid: get_profile_interface socket
,08-26 14:17:40.992  4148  4148 I bt_bluedroid: get_profile_interface sdp
,08-26 14:17:40.997  4148  4159 I bt_bluedroid: config_hci_snoop_log
,08-26 14:17:40.998  4148  4164 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 14:17:40.999   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 14:17:41.002  4148  4164 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 14:17:41.007  4148  4160 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 14:17:41.007  4148  4160 D BluetoothAdapterProperties: Setting state to 14
,08-26 14:17:41.008  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 14:17:41.011  4148  4160 D BluetoothBondStateMachine: make
,08-26 14:17:41.017  4148  4165 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 14:17:41.024  4148  4160 I BluetoothAdapterState: Entering PendingCommandState
,08-26 14:17:41.025  4148  4148 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 14:17:41.029  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:41.030  4148  4148 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:41.031  4148  4148 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:41.031  4148  4148 D BtGatt.GattService: start()
08-26 14:17:41.031  4148  4148 I bt_bluedroid: get_profile_interface gatt
,08-26 14:17:41.032  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:41.033  4148  4148 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:41.044  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:41.044  4148  4148 V BluetoothAdapterState: isTurningOn()=false
,08-26 14:17:41.044  4148  4148 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 14:17:41.044  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:41.045  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 14:17:41.045  4148  4160 I bt_bluedroid: enable
08-26 14:17:41.046  4148  4161 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 14:17:41.047  4148  4161 I bt_hci  : start_up
,08-26 14:17:41.069  4148  4161 I bt_vendor: alloc value 0xb3a79189
08-26 14:17:41.069  4148  4161 I bt_vendor: init
08-26 14:17:41.070  4148  4161 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 14:17:41.070  4148  4161 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 14:17:41.178  4148  4161 D bt_hci  : start_up starting async portion
,08-26 14:17:41.178  4148  4168 I bt_hci  : event_finish_startup
08-26 14:17:41.179  4148  4168 I bt_hci_h4: hal_open
08-26 14:17:41.179  4148  4168 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 14:17:41.189  4148  4168 I bt_userial_vendor: device fd = 51 open
,08-26 14:17:41.219  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 14:17:41.251  4148  4168 D bt_hwcfg: Chipset BCM4354A2
,08-26 14:17:41.251  4148  4168 D bt_hwcfg: Target name = [BCM4354A2]
08-26 14:17:41.252  4148  4168 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 14:17:41.923  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 14:17:41.925  4148  4168 D bt_hwcfg: Settlement delay -- 100 ms
08-26 14:17:41.925  4148  4168 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 14:17:42.042  4148  4168 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 14:17:42.043  4148  4168 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 14:17:42.072  4148  4168 I bt_hwcfg: vendor lib fwcfg completed
,08-26 14:17:42.073  4148  4168 I bt_vendor: firmware callback
08-26 14:17:42.073  4148  4168 I bt_hci  : firmware_config_callback
,08-26 14:17:42.084  4148  4172 I bt_btu  : btu_task pending for preload complete event
,08-26 14:17:42.084  4148  4172 I bt_btu_task: Bluetooth chip preload is complete
08-26 14:17:42.084  4148  4172 I bt_btu  : btu_task received preload complete event
,08-26 14:17:42.097  4148  4172 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 14:17:42.097  4148  4172 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 14:17:42.097  4148  4172 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 14:17:42.097  4148  4172 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 14:17:42.098  4148  4172 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 14:17:42.098  4148  4172 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:42.098  4148  4172 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:42.100  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 14:17:42.101  4148  4172 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 14:17:42.102  4148  4172 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:42.102  4148  4172 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 14:17:42.103  4148  4172 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:42.103  4148  4172 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 14:17:42.103  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 14:17:42.103  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 14:17:42.151   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 14:17:42.161  1882  1882 I Keyboard.Facilitator: onFinishInput()
,08-26 14:17:42.169   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 14:17:42.169   872   892 I Adreno  : Build Date                       : 10/20/15
08-26 14:17:42.169   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 14:17:42.169   872   892 I Adreno  : Local Branch                     : M14
08-26 14:17:42.169   872   892 I Adreno  : Remote Branch                    : 
08-26 14:17:42.169   872   892 I Adreno  : Remote Branch                    : 
08-26 14:17:42.169   872   892 I Adreno  : Reconstruct Branch               : 
,08-26 14:17:42.215   280   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (317 us)
,08-26 14:17:42.243  4148  4172 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,08-26 14:17:42.246  4148  4172 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-26 14:17:42.267  4148  4164 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 14:17:42.271  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 14:17:42.271  4148  4164 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 14:17:42.273  4148  4164 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 14:17:42.274  4148  4164 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:42.274  4148  4164 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:42.274  4148  4164 D bt_hci  : do_postload posting postload work item
08-26 14:17:42.274  4148  4168 I bt_hci  : event_postload
08-26 14:17:42.274  4148  4168 I bt_vendor: sco_config_cb
,08-26 14:17:42.274  4148  4168 I bt_hci  : sco_config_callback postload finished.
,08-26 14:17:42.275  4148  4164 D bt_bte_conf: Device ID record 1 : primary
08-26 14:17:42.275  4148  4164 D bt_bte_conf:   vendorId            = 000f
,08-26 14:17:42.275  4148  4164 D bt_bte_conf:   vendorIdSource      = 0001
08-26 14:17:42.275  4148  4164 D bt_bte_conf:   product             = 1200
08-26 14:17:42.275  4148  4164 D bt_bte_conf:   version             = 1436
,08-26 14:17:42.275  4148  4164 D bt_bte_conf:   clientExecutableURL = 
,08-26 14:17:42.275  4148  4164 D bt_bte_conf:   serviceDescription  = 
08-26 14:17:42.275  4148  4164 D bt_bte_conf:   documentationURL    = 
08-26 14:17:42.275  4148  4164 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 14:17:42.275  4148  4161 D bt_stack_manager: event_start_up_stack finished
08-26 14:17:42.276  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 14:17:42.276  4148  4160 D BluetoothAdapterProperties: Setting state to 15
08-26 14:17:42.276  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 14:17:42.277  4148  4160 I BluetoothAdapterState: Entering BleOnState
08-26 14:17:42.282  4148  4160 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 14:17:42.282  4148  4160 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:42.282  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 14:17:42.283  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:42.285  4148  4168 I bt_vendor: low_power_mode_cb
08-26 14:17:42.292  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:42.294  4148  4148 D HeadsetService: Received start request. Starting profile...
08-26 14:17:42.297  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:42.300  4148  4160 I BluetoothAdapterState: Entering PendingCommandState
08-26 14:17:42.300  4148  4148 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 14:17:42.300  4148  4148 D HeadsetStateMachine: make
,08-26 14:17:42.311  4148  4148 D HeadsetStateMachine: max_hf_connections = 1
08-26 14:17:42.311  4148  4148 I bt_bluedroid: get_profile_interface handsfree
,08-26 14:17:42.311  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 14:17:42.311  4148  4164 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-26 14:17:42.315  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff,
08-26 14:17:42.316  4148  4148 D A2dpService: Received start request. Starting profile...
08-26 14:17:42.317  4148  4148 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 14:17:42.317  4148  4148 I bt_bluedroid: get_profile_interface avrcp
,08-26 14:17:42.322  4148  4148 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:42.323  4148  4148 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 14:17:42.323  4148  4148 D A2dpStateMachine: make
,08-26 14:17:42.324  4148  4148 I bt_bluedroid: get_profile_interface a2dp
,08-26 14:17:42.325  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 14:17:42.327  4148  4148 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 14:17:42.327  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:42.328  4148  4182 D A2dpStateMachine: Enter Disconnected: -2
08-26 14:17:42.328  4148  4148 D HidService: Received start request. Starting profile...
,08-26 14:17:42.329  4148  4148 I bt_bluedroid: get_profile_interface hidhost
08-26 14:17:42.329  4148  4164 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
08-26 14:17:42.329  4148  4164 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 14:17:42.329  4148  4148 D HidService: setHidService(): set to: null
,08-26 14:17:42.330  4148  4148 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:42.330  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:42.331  4148  4148 D HealthService: Received start request. Starting profile...
,08-26 14:17:42.332  4148  4148 I bt_bluedroid: get_profile_interface health
08-26 14:17:42.333  4148  4148 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 14:17:42.334  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:42.334  4148  4148 D PanService: Received start request. Starting profile...
08-26 14:17:42.334  4148  4148 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:42.334  4148  4148 I bt_bluedroid: get_profile_interface pan
08-26 14:17:42.335  4148  4164 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 14:17:42.339  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
08-26 14:17:42.342  4148  4148 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:42.342  4148  4148 D BluetoothMapService: start()
,08-26 14:17:42.345  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 14:17:42.348  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 14:17:42.349  4148  4148 D BluetoothMapAppObserver: createReceiver()
,08-26 14:17:42.357  4148  4148 D BluetoothMapAppObserver: initObservers()
08-26 14:17:42.360  4148  4148 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 14:17:42.367  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:42.367  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:42.367  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:42.367  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:42.367  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:42.367  4148  4180 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:42.369  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isTurningOn()=true
,08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-26 14:17:42.370  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-26 14:17:42.370  4148  4160 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 14:17:42.370  4148  4160 D BluetoothAdapterProperties: ScanMode =  20
08-26 14:17:42.370  4148  4160 D BluetoothAdapterProperties: State =  11
08-26 14:17:42.371  4148  4160 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:42.371  4148  4160 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 14:17:42.371  4148  4164 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:42.371  4148  4164 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 14:17:42.371  1375  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 14:17:42.377  1969  2157 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 14:17:42.377  4148  4160 I BluetoothAdapterState: Entering OnState
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.378  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:42.378  1375  1399 D BluetoothPan: onBluetoothStateChange on: true
,08-26 14:17:42.380  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:42.381  1375  2110 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:42.382  1375  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:42.383  3865  3878 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 14:17:42.387  1375  1375 D BluetoothInputDevice: Proxy object connected
,08-26 14:17:42.387  1375  1375 D HidProfile: Bluetooth service connected
,08-26 14:17:42.388  1375  2110 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 14:17:42.390  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 14:17:42.390  4148  4148 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-26 14:17:42.391  3865  3877 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 14:17:42.391  1375  1375 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:42.391  1375  1375 D PanProfile: Bluetooth service connected
08-26 14:17:42.392  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:42.393  3865  3877 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 14:17:42.394  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:42.396  4148  4148 D ObexServerSockets: Succeed to create listening sockets 
08-26 14:17:42.396  4148  4148 D ObexServerSockets0: startAccept()
,08-26 14:17:42.396  4148  4148 D ObexServerSockets0: prepareForNewConnect()
08-26 14:17:42.397  4148  4148 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 14:17:42.397   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:42.397  4148  4148 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 14:17:42.398   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 14:17:42.398  3865  3878 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:42.398  4148  4188 D ObexServerSockets0: Accepting socket connection...
08-26 14:17:42.398  4148  4189 D ObexServerSockets0: Accepting socket connection...
08-26 14:17:42.399  1375  1375 D BluetoothMap: Proxy object connected
08-26 14:17:42.399  1375  1375 D MapProfile: Bluetooth service connected
08-26 14:17:42.399  1375  1375 D BluetoothMap: getConnectedDevices()
,08-26 14:17:42.400  3865  3878 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:42.402   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:42.405   872   872 D BluetoothA2dp: Proxy object connected
,08-26 14:17:42.405   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 14:17:42.405  1375  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:42.405  3865  3865 D BluetoothInputDevice: Proxy object connected
08-26 14:17:42.405  3865  3865 D HidProfile: Bluetooth service connected
08-26 14:17:42.406  1375  1375 D BluetoothA2dp: Proxy object connected
08-26 14:17:42.407  3865  3865 D BluetoothMap: Proxy object connected
08-26 14:17:42.407  3865  3865 D MapProfile: Bluetooth service connected
,08-26 14:17:42.407  3865  4190 D BluetoothPan: onBluetoothStateChange on: true
08-26 14:17:42.407  3865  3865 D BluetoothMap: getConnectedDevices()
,08-26 14:17:42.410   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 14:17:42.410  4148  4148 D BluetoothMapService: onReceive
08-26 14:17:42.410  4148  4148 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:42.411  4148  4148 D BluetoothMapService: STATE_ON
08-26 14:17:42.411  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:42.411  3865  3865 D BluetoothA2dp: Proxy object connected
,08-26 14:17:42.412  3865  3865 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:42.413  3865  3865 D PanProfile: Bluetooth service connected
,08-26 14:17:42.416  3865  3865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:42.421  3865  3865 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:42.424  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:42.430  3865  3865 D BluetoothPbap: Proxy object connected
,08-26 14:17:42.430  3865  3865 D PbapServerProfile: Bluetooth service connected
08-26 14:17:42.430  1375  1375 D BluetoothPbap: Proxy object connected
08-26 14:17:42.430  1375  1375 D PbapServerProfile: Bluetooth service connected
,08-26 14:17:42.436  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 14:17:42.436  4148  4148 D ObexServerSockets0: prepareForNewConnect()
,08-26 14:17:42.437  4148  4195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:42.450  4148  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:42.451  4148  4199 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:42.479  3865  3878 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.479  3865  3865 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:42.479  1375  1386 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.479  1375  1375 D HeadsetProfile: Bluetooth service connected
08-26 14:17:42.479   872   872 D BluetoothHeadset: Proxy object connected
08-26 14:17:42.479   872   872 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.480  1969  1980 D BluetoothHeadset: Proxy object connected
08-26 14:17:42.480   872   872 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.483  1375  2110 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.483  1375  1375 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:42.498   872   889 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.498   872   889 D BluetoothHeadset: Proxy object connected
08-26 14:17:42.499  3865  3877 D BluetoothHeadset: Proxy object connected
08-26 14:17:42.499  3865  3865 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:42.506   872   889 D BluetoothHeadset: Proxy object connected
,08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.819  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:42.826  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:42.832  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:42.833  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb76953 added. We now have 8 listener(s)
,08-26 14:17:42.839  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:42.844   872   883 D WifiService: setWifiEnabled: false pid=3796, uid=10000
08-26 14:17:42.844   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:42.851  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:42.862   872  2122 D WifiService: setWifiEnabled: true pid=3796, uid=10000
,08-26 14:17:42.863   872  2122 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 14:17:42.866  3796  3796 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:42.866  3796  3796 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.878  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:42.880  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:42.884  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 14:17:42.886  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 14:17:42.889  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@814f61b Bundle[{}]
,08-26 14:17:42.889  3796  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:17:42.890  3796  3847 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 14:17:42.891  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:17:42.893  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 14:17:42.893  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 14:17:42.894  3796  3847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:42.899  3796  3847 I System.out: Running OutgoingSocketThread
,08-26 14:17:42.900  3796  4203 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-26 14:17:42.901  3796  4203 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44680
,08-26 14:17:42.901   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 14:17:42.902  3796  3796 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@814f61b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8615290, 16908290=android.view.AbsSavedState$1@8615290}, android:focusedViewId=100}]}]
,08-26 14:17:42.902  3796  3796 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 14:17:42.902  3796  3796 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 14:17:42.902  3796  3796 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 14:17:42.904   872  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-26 14:17:42.908   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:42.910  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:42.912  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:42.901  3796  4203 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 14:17:42.915   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 14:17:42.922   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-26 14:17:42.922   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-26 14:17:42.923   872  1316 D WifiConfigStore: loaded 0 passpoint configs
08-26 14:17:42.924   872  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 14:17:42.925   872  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 14:17:42.926   872  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 14:17:42.926   872  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 14:17:42.927   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 14:17:42.927   872  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 14:17:42.938   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 14:17:42.939   872  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.70 rxSuccessRate=0.95 delta 1000 -> 1000
,08-26 14:17:42.941   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:42.943   872  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-26 14:17:42.943   872  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 14:17:42.951   872   881 I art     : Background partial concurrent mark sweep GC freed 25963(1886KB) AllocSpace objects, 10(336KB) LOS objects, 33% free, 29MB/43MB, paused 1.767ms total 100.886ms
,08-26 14:17:42.953   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 14:17:42.953   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:42.957   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 14:17:42.984   872  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 14:17:42.985  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 14:17:43.044   872  1315 D WifiNative-HAL: p2pGetDeviceAddress
08-26 14:17:43.046   872  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 14:17:43.153   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 14:17:43.155   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 14:17:43.155   872  1343 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,08-26 14:17:43.159   872   892 I DreamManagerService: Entering dreamland.
,08-26 14:17:43.161   872   892 I PowerManagerService: Dozing...
,08-26 14:17:43.162   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 14:17:43.239   375  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 14:17:43.239   375  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 14:17:43.244   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:43.252   872  1316 E native  : do suspend false
,08-26 14:17:43.266   872  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 14:17:43.270  1957  4206 D NfcService: Discovery configuration equal, not updating.
,08-26 14:17:43.316   872  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 14:17:43.319  1458  1458 E wpa_supplicant: PNO: In assoc process
,08-26 14:17:43.320   872  1316 E WifiStateMachine:  Fail to set up pno, want true now false
,08-26 14:17:43.327   872  1316 E native  : do suspend true
,08-26 14:17:43.369   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 14:17:43.369   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 14:17:43.463  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 14:17:43.503  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 14:17:43.504  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 14:17:43.508   872  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 14:17:43.519   872  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 14:17:43.519   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:43.519   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 14:17:43.537   872  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:43.549   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:43.550   872  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 14:17:43.559   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 14:17:43.573   872  4213 D DhcpClient: Receive thread started
,08-26 14:17:43.657   872  1316 E native  : do suspend false
,08-26 14:17:43.677   872  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 14:17:43.725   872  4213 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172785, domain null
,08-26 14:17:43.727   872  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172785 seconds
,08-26 14:17:43.730   872  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 14:17:43.801   872  4213 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 14:17:43.803   872  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 14:17:43.808   371   870 D CommandListener: Setting iface cfg
,08-26 14:17:43.820   872  1877 D DhcpClient: Scheduling renewal in 86399s
,08-26 14:17:43.821   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 14:17:43.827   872  1316 E native  : do suspend true
,08-26 14:17:43.845   872  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 14:17:43.846   872  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 14:17:43.847   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 14:17:43.849   872  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 14:17:43.856   872  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 14:17:43.902  3796  3847 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-26 14:17:43.902  3796  3847 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-26 14:17:43.910  3796  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-26 14:17:43.911  3796  3847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 14:17:43.911  3796  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-26 14:17:43.916  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:43.916  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f83789 added. We now have 2 listener(s)
,08-26 14:17:43.920  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:43.920  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.920  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.921  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:43.921  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91938e added. We now have 9 listener(s)
08-26 14:17:43.921  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.922  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:43.927  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:43.932  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:43.934  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:43.934  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:43.934  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.935  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3107bc added. We now have 3 listener(s)
,08-26 14:17:43.936  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:43.937  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:43.937  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:43.937  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:43.937  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.937  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a3c345 added. We now have 10 listener(s)
,08-26 14:17:43.938  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.938  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:43.938  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:43.938  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:43.938  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:43.938  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:43.938  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.938   872  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 14:17:43.938  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:43.938   872  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 14:17:43.938  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:43.939  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f83789 removed from the list
08-26 14:17:43.939  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.939  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91938e removed from the list
08-26 14:17:43.939  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:43.939  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.939   872  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
08-26 14:17:43.939  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.939  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.940  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:43.940  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.941  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.941  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e91938e not in the list
08-26 14:17:43.941  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.941  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.941   872  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 14:17:43.942  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:43.942  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:43.942  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:43.942  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a3c345 removed from the list
08-26 14:17:43.942  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:43.942  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:43.942  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:43.942  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:43.942  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3107bc removed from the list
08-26 14:17:43.943   872  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 14:17:43.943  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.943  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f975a9a added. We now have 2 listener(s)
08-26 14:17:43.944   872  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 14:17:43.945  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 14:17:43.945  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.945  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:43.945  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.945  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e28afcb added. We now have 9 listener(s)
,08-26 14:17:43.945  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.946  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:43.962  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:43.962   872  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:43.965  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:43.967  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:43.967  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:43.967  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:43.968  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c24ec1 added. We now have 3 listener(s)
08-26 14:17:43.969  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.970  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:43.970   872  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 14:17:43.971   872  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.971   872  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:43.971   872  1318 D ConnectivityService:    accepting network in place of null
08-26 14:17:43.971  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 14:17:43.971  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:43.971   872  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 14:17:43.971  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:43.971  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:43.972  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1008666 added. We now have 10 listener(s)
08-26 14:17:43.972  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:43.972  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:43.972  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:43.972   872  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 14:17:43.972  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:43.972  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:43.972  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:43.973   872  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 14:17:43.975  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 14:17:43.975  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:43.979  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:43.979  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:43.980  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:43.983  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:43.983  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:43.983  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:43.984  3796  3847 D BluetoothAdapter: STATE_ON
,08-26 14:17:43.986  4148  4177 D BtGatt.GattService: registerClient() - UUID=54c1d05a-5861-47e8-86d7-32fcb415b367
,08-26 14:17:43.987  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=54c1d05a-5861-47e8-86d7-32fcb415b367, clientIf=5
,08-26 14:17:43.988  3796  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 14:17:43.989  4148  4159 D BtGatt.GattService: start scan with filters
,08-26 14:17:43.992  4148  4167 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:43.993  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:43.993  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:43.993  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:43.993  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 14:17:43.994  4148  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad2c8ff
,08-26 14:17:43.996  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 14:17:43.996  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:43.997  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 14:17:43.997  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:43.997  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:43.997  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:43.998  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 14:17:43.998  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:43.999  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:43.999  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 14:17:44.000  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:44.001  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 14:17:44.001  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.002  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 14:17:44.002  3796  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 14:17:44.002  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.003  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:44.003  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:44.004  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.004  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:44.004  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:44.004  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:44.004  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 14:17:44.004  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:44.004  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:44.005  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:44.005   872  4212 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154789, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 14:17:44.005  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:44.006  4148  4177 D BtGatt.GattService: stopScan() - queue size =1
08-26 14:17:44.007  4148  4159 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 14:17:44.007  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:44.007  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:44.007  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:44.007  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:44.007  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 14:17:44.008  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:44.008  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:44.009  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:44.009  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:44.009  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 14:17:44.009  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.009  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
08-26 14:17:44.010  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:44.010  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:44.011  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:44.011  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:44.012  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:44.012  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:44.012  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:44.012  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.012  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.012  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:44.012  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.013  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f975a9a removed from the list
,08-26 14:17:44.013   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 14:17:44.013  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:44.013  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e28afcb removed from the list
08-26 14:17:44.013  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:44.013  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:44.013  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 14:17:44.013  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.013  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 14:17:44.014  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.014  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.015  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 14:17:44.015  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.015  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:44.015  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.015  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:44.015  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e28afcb not in the list
08-26 14:17:44.015  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.015  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:44.016  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.016  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:44.016  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.016  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1008666 removed from the list
,08-26 14:17:44.016  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.016  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:44.017  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.017  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.017  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c24ec1 removed from the list
08-26 14:17:44.017  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:44.017  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47ea2f2 added. We now have 2 listener(s)
08-26 14:17:44.019  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:44.019  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:44.019  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:44.019  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:44.019  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bd4d43 added. We now have 9 listener(s)
,08-26 14:17:44.019  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:44.020  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:44.021  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:44.025  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:44.027  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:44.027  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:44.027  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:44.027  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46114f9 added. We now have 3 listener(s)
,08-26 14:17:44.029  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:44.029  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:44.029  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:44.029  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:44.029  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ffc3e added. We now have 10 listener(s)
08-26 14:17:44.029  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:44.029  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:44.030  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:44.030  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:44.030  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:44.030  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 14:17:44.030  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:44.030  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:44.032  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:44.033  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 14:17:44.033  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:44.036  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:44.037  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:44.037  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:44.040  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:44.040  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:44.040  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:44.041  3796  3847 D BluetoothAdapter: STATE_ON
,08-26 14:17:44.042  4148  4191 D BtGatt.GattService: registerClient() - UUID=eeb1e317-5ea4-46f6-8a16-ae81b3b71c46
,08-26 14:17:44.043  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=eeb1e317-5ea4-46f6-8a16-ae81b3b71c46, clientIf=5
08-26 14:17:44.043  3796  3807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 14:17:44.043  4148  4187 D BtGatt.GattService: start scan with filters
,08-26 14:17:44.046  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:44.046  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:44.046  4148  4167 D BtGatt.ScanManager: handling starting scan
08-26 14:17:44.046  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 14:17:44.046  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:44.048  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 14:17:44.048  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.049  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 14:17:44.049  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:44.049  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:44.049   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 14:17:44.049  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 14:17:44.050  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 14:17:44.050  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.050  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:44.050  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 14:17:44.051  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:44.052  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 14:17:44.052  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.053   872  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 14:17:44.053  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:44.054  3796  3847 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 14:17:44.054  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:44.054  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:44.054   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:44.054  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:44.054  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 14:17:44.054  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.055  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.055  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:44.055  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:44.055  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.056  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47ea2f2 removed from the list
08-26 14:17:44.056  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:44.056  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bd4d43 removed from the list
08-26 14:17:44.056  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:44.056  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:44.060   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 14:17:44.061  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.061  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 14:17:44.061  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:44.057   872  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 14:17:44.061  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:44.063  3796  3796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.064  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bd4d43 not in the list
08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:44.064  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:44.064  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:44.064  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:44.065  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:44.065  4148  4191 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:44.066  3796  3796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.067  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 14:17:44.067  4148  4177 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 14:17:44.067  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.068  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:44.068  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
08-26 14:17:44.068  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:44.068  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:44.068  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 14:17:44.068  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 14:17:44.069  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:44.069  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:44.069  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:44.069  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:44.070  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.071  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:44.071  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:44.071  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:44.071  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.071  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:44.071  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:44.071  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ffc3e removed from the list
08-26 14:17:44.071  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.071  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.071  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.071  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.072  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46114f9 removed from the list
,08-26 14:17:44.072  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:44.072  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b9e4a added. We now have 2 listener(s)
08-26 14:17:44.074  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:44.074  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:44.074  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:44.074  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:44.074  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a921bb added. We now have 9 listener(s)
08-26 14:17:44.074  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:44.074  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 14:17:44.075  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.075  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:44.075  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 14:17:44.076  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 14:17:44.076  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.076  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:44.080  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:44.082  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:44.082  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:44.082  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:44.082  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6a31 added. We now have 3 listener(s)
,08-26 14:17:44.083  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 14:17:44.083  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:44.083  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:44.084  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:44.084  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:44.084  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aad5516 added. We now have 10 listener(s)
08-26 14:17:44.084  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:44.084  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:44.084  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:44.084  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 14:17:44.084  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:44.084  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:44.085  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:44.087  3796  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 14:17:44.087  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:44.090  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:44.090  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 14:17:44.090  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:44.092  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 14:17:44.092  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:44.092  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 14:17:44.093  3796  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:44.093  3796  3847 D BluetoothAdapter: STATE_ON
,08-26 14:17:44.094  4148  4191 D BtGatt.GattService: registerClient() - UUID=23f9696f-94f0-45e8-8563-1f4915f2f3b3
,08-26 14:17:44.095  4148  4164 D BtGatt.GattService: onClientRegistered() - UUID=23f9696f-94f0-45e8-8563-1f4915f2f3b3, clientIf=5
08-26 14:17:44.095  3796  3808 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 14:17:44.095  4148  4187 D BtGatt.GattService: start scan with filters
,08-26 14:17:44.097  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:44.097  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:44.097  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:44.097  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:44.098  4148  4167 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:44.101  1701  1701 D SystemUpdateService: onCreate
,08-26 14:17:44.101  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:44.102  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:44.102  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:44.103  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:44.104  4148  4164 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 14:17:44.104  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.104  4148  4167 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 14:17:44.107  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 14:17:44.107  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:44.107  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:44.107  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:44.108  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.108  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:44.108  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:44.108  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.108  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b9e4a removed from the list
,08-26 14:17:44.108  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.108  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a921bb removed from the list
08-26 14:17:44.108  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:44.108  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:44.109  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.109  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 14:17:44.109  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.109  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:44.109  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 14:17:44.109  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.109  4148  4167 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:44.109  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:44.109  4148  4167 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 14:17:44.109  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.110  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.110  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a921bb not in the list
,08-26 14:17:44.110  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 14:17:44.110  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:44.110  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:44.110  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:44.110  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 14:17:44.111  3796  3847 D BluetoothAdapter: STATE_ON
08-26 14:17:44.111  4148  4159 D BtGatt.GattService: stopScan() - queue size =1
08-26 14:17:44.112  4148  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 14:17:44.112  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:44.113  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:44.113  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:44.113  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:44.113  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:44.114  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:44.114  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:44.114  3796  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:44.114  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:44.116  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.118  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:44.118  3796  3796 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:44.118  3796  3796 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:44.118  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:44.118  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:44.118  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.119  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aad5516 removed from the list
08-26 14:17:44.119  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:44.119  4148  4164 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 14:17:44.119  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.119  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:44.119  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.119  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:44.119  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db6a31 removed from the list
,08-26 14:17:44.120  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:44.120  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1aca2 added. We now have 2 listener(s)
,08-26 14:17:44.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 14:17:44.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:44.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:44.122  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:44.122  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbc0d33 added. We now have 9 listener(s),
,08-26 14:17:44.122   872  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:805::200e
,08-26 14:17:44.122  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:44.122  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:44.124  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 14:17:44.124  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.124  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:44.130  3796  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:44.130  4148  4164 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 14:17:44.130  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 14:17:44.130  4148  4167 D BtGatt.ScanManager: stopping BLe Batch
08-26 14:17:44.131  3796  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:44.132  3796  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:44.133  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:44.133  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6342e69 added. We now have 3 listener(s)
,08-26 14:17:44.134  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:44.136  4148  4164 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 14:17:44.136  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.136  3796  3796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:44.136  4148  4167 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 14:17:44.137  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 14:17:44.137  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:44.137  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:44.137  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:44.137  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@891f0ee added. We now have 10 listener(s)
08-26 14:17:44.137  3796  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:44.137  3796  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:44.138  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:44.138  3796  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:44.138  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:44.138  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.138  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:44.138  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:44.138  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1aca2 removed from the list
08-26 14:17:44.138  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.138  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbc0d33 removed from the list
08-26 14:17:44.138  3796  3847 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:44.138  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.139  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.139  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:44.140  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:44.140  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.140  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.140  3796  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbc0d33 not in the list
08-26 14:17:44.140  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.140  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:44.141  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:44.141  4148  4164 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 14:17:44.141  4148  4164 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 14:17:44.141  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:44.142  3796  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:44.142  3796  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@891f0ee removed from the list
08-26 14:17:44.142  3796  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:44.142  3796  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:44.142  3796  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:44.142  3796  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:44.142  3796  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6342e69 removed from the list
08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 14:17:44.143  3796  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:44.146  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 14:17:44.150  3796  4226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
,08-26 14:17:44.150  3796  4226 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
08-26 14:17:44.150  3796  4226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:44.147  1701  4222 I SystemUpdateService: active receiver: enabled
,08-26 14:17:44.152  3796  4228 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,08-26 14:17:44.153  3796  4228 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
,08-26 14:17:44.153  3796  4228 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:44.154  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 14:17:44.154  3796  3847 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 14:17:44.155  3796  3847 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 14:17:44.155  3796  3847 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0,
,08-26 14:17:44.155  3796  3847 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-26 14:17:44.155  3796  3847 D com.test.thalitest.ThaliTestRunner: Total duration: 21794 ms
08-26 14:17:44.155  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-26 14:17:44.157  3796  3847 I jxcore-log: *Native tests were executed*
08-26 14:17:44.157  3796  3847 I jxcore-log: 
,08-26 14:17:44.157  3796  3847 I jxcore-log: Total number of executed tests:  80
08-26 14:17:44.157  3796  3847 I jxcore-log: 
08-26 14:17:44.157  3958  3958 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-26 14:17:44.157  3796  3847 I jxcore-log: Number of passed tests:  80
08-26 14:17:44.157  3796  3847 I jxcore-log: 
08-26 14:17:44.157  3796  3847 I jxcore-log: Number of failed tests:  0
08-26 14:17:44.157  3796  3847 I jxcore-log: 
08-26 14:17:44.157  3796  3847 I jxcore-log: Number of ignored tests:  0
08-26 14:17:44.157  3796  3847 I jxcore-log: 
,08-26 14:17:44.158  3796  3847 I jxcore-log: Total duration:  21794
08-26 14:17:44.158  3796  3847 I jxcore-log: 
08-26 14:17:44.158  3796  3847 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 14:17:44.158  3796  3847 I jxcore-log: 
08-26 14:17:44.161  3958  3958 D SprintDMHelper: simOperator: 
08-26 14:17:44.161  3958  3958 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-26 14:17:44.163  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.163  3796  3847 I jxcore-log: 
08-26 14:17:44.166  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.166  3796  3847 I jxcore-log: 
08-26 14:17:44.167  3796  3796 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 14:17:44.167  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.167  3796  3847 I jxcore-log: 
08-26 14:17:44.168  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.168  3796  3847 I jxcore-log: 
,08-26 14:17:44.169  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.169  3796  3847 I jxcore-log: 
08-26 14:17:44.170  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.170  3796  3847 I jxcore-log: 
08-26 14:17:44.172  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.172  3796  3847 I jxcore-log: 
08-26 14:17:44.173  1701  4225 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 14:17:44.173  1701  4225 W BaseAppContext: Using Auth Proxy for data requests.
08-26 14:17:44.174  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.174  3796  3847 I jxcore-log: 
08-26 14:17:44.175  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.175  3796  3847 I jxcore-log: 
08-26 14:17:44.175  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.175  3796  3847 I jxcore-log: 
08-26 14:17:44.177  1701  4225 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
08-26 14:17:44.177  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.177  3796  3847 I jxcore-log: 
08-26 14:17:44.178  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:44.178  3796  3847 I jxcore-log: 
08-26 14:17:44.179  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.179  3796  3847 I jxcore-log: 
08-26 14:17:44.180  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.180  3796  3847 I jxcore-log: 
08-26 14:17:44.180  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.180  3796  3847 I jxcore-log: 
08-26 14:17:44.181  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.181  3796  3847 I jxcore-log: 
08-26 14:17:44.182  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.182  3796  3847 I jxcore-log: 
,08-26 14:17:44.183  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.183  3796  3847 I jxcore-log: 
,08-26 14:17:44.184  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.184  3796  3847 I jxcore-log: 
,08-26 14:17:44.185  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.185  3796  3847 I jxcore-log: 
,08-26 14:17:44.186  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.186  3796  3847 I jxcore-log: 
08-26 14:17:44.187  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.187  3796  3847 I jxcore-log: 
08-26 14:17:44.188  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.188  3796  3847 I jxcore-log: 
08-26 14:17:44.188  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:44.188  3796  3847 I jxcore-log: 
08-26 14:17:44.189  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.189  3796  3847 I jxcore-log: 
08-26 14:17:44.190  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.190  3796  3847 I jxcore-log: 
08-26 14:17:44.190  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.190  3796  3847 I jxcore-log: 
08-26 14:17:44.191  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:44.191  3796  3847 I jxcore-log: 
08-26 14:17:44.192  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.192  3796  3847 I jxcore-log: 
,08-26 14:17:44.192  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.192  3796  3847 I jxcore-log: 
08-26 14:17:44.193  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.193  3796  3847 I jxcore-log: 
08-26 14:17:44.193  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:44.194  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:44.194  3796  3847 I jxcore-log: 
,08-26 14:17:44.195  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 14:17:44.189  1701  2408 I iu.UploadsManager: num queued entries: 0
,08-26 14:17:44.211  1701  2408 I iu.UploadsManager: num updated entries: 0
,08-26 14:17:44.217  1701  4222 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 14:17:44.219  1701  2408 I iu.SyncManager: NEXT; no task
,08-26 14:17:44.219  1701  4222 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-26 14:17:44.220  1701  4222 I SystemUpdateService: now status is 0 (complete)
08-26 14:17:44.220  1701  4222 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 14:17:44.220  1701  4222 I SystemUpdateService: file has been verified
08-26 14:17:44.220  1701  4222 I SystemUpdateService: OTA package size = 12249756
,08-26 14:17:44.224  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 14:17:44.224  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 14:17:44.224  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 14:17:44.224  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 14:17:44.226  1701  4222 I SystemUpdateService: showing system update notification
,08-26 14:17:44.237  1701  4225 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-26 14:17:44.240  1701  1701 D SystemUpdateService: onDestroy
,08-26 14:17:44.270   872  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:44 GMT], X-Android-Received-Millis=[1472213864269], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472213864204]}
,08-26 14:17:44.271   872  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 14:17:44.271   872  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 14:17:44.272   872  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 14:17:44.279   872  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 14:17:44.375  3082  4229 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 14:17:44.511  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:44.518  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:44.518  3796  3847 I jxcore-log: 
,08-26 14:17:44.570  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:44.574  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:44.574  3796  3847 I jxcore-log: 
,08-26 14:17:44.618  3796  3796 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:44.621  3796  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:44.621  3796  3847 I jxcore-log: 
,08-26 14:17:44.771  4234  4234 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 14:17:44.776  4234  4234 D AndroidRuntime: CheckJNI is OFF
,08-26 14:17:44.818  4234  4234 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 14:17:44.862  4234  4234 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 14:17:44.884  4234  4234 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 14:17:44.894   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 14:17:44.894   872   885 I ActivityManager: Killing 3796:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 14:17:45.014   872   895 W PackageSettings: Skipping PackageSetting{a9b1bf0 com.example.hello/10273} due to missing metadata
,08-26 14:17:45.037   872   882 D GraphicsStats: Buffer count: 2
,08-26 14:17:45.037   872  1397 I WindowState: WIN DEATH: Window{7b5130f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 14:17:45.038   872  1317 D WifiService: Client connection lost with reason: 4
,08-26 14:17:45.046   872   895 I art     : Starting a blocking GC Explicit
,08-26 14:17:45.065   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 14:17:45.067   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 14:17:45.067   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-26 14:17:45.067   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 14:17:45.067   872   885 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 14:17:45.067   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.067   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.067   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:45.067   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 14:17:45.068   872   885 I ActivityManager:   Force finishing activity ActivityRecord{217f3a4 u0 com.test.thalitest/.MainActivity t2}
,08-26 14:17:45.075   872  2016 W ActivityManager: Spurious death for ProcessRecord{a8991b2 0:com.test.thalitest/u0a0}, curProc for 3796: null
,08-26 14:17:45.104   872   895 I art     : Explicit concurrent mark sweep GC freed 44897(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 703us total 56.300ms
,08-26 14:17:45.126   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 14:17:45.128  4234  4234 I art     : System.exit called, status: 0
,08-26 14:17:45.128  4234  4234 I AndroidRuntime: VM exiting with result code 0.
08-26 14:17:45.131   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 14:17:45.159   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 14:17:45.166  4148  4148 D BluetoothMapAppObserver: onReceive
,08-26 14:17:45.166  4148  4148 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 14:17:45.169   872  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 14:17:45.174  1882  1882 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 14:17:45.174  3638  3638 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 14:17:45.178  1882  4251 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 14:17:45.182  1896  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:45.192  1882  4251 I Decoder : createOrResetDecoder
,08-26 14:17:45.221   872  2016 I ActivityManager: Start proc 4253:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 14:17:45.235  1969  1969 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 14:17:45.253  1504  1504 I ConfigService: onCreate
,08-26 14:17:45.256  1504  4265 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 14:17:45.256  1504  4265 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 14:17:45.257  1504  4265 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 14:17:45.258  1504  4265 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-26 14:17:45.269   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 14:17:45.280  1882  4251 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 14:17:45.283   872  2039 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3796 uid 10000
,08-26 14:17:45.285  1882  1882 I Keyboard.Facilitator: onFinishInput()
,08-26 14:17:45.293   872  1344 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-26 14:17:45.293   872  1344 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-26 14:17:45.293   872  1344 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-26 14:17:45.293   872  1344 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
,08-26 14:17:45.293   872  1344 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,08-26 14:17:45.293   872  1344 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-26 14:17:45.293   872  1344 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-26 14:17:45.293   872  1344 W System.err: ,	at libcore.io.Posix.writeBytes(Native Method)
08-26 14:17:45.293   872  1344 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,08-26 14:17:45.293   872  1344 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
,08-26 14:17:45.294   872  1344 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,08-26 14:17:45.294   872  1344 W System.err: 	... 4 more
,08-26 14:17:45.294   872  1344 D skia    : ------- write threw an exception
08-26 14:17:45.302  4253  4253 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-26 14:17:45.305   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 14:17:45.305   872   884 E PackageManager: Failed to write settings, restoring backup
08-26 14:17:45.305   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 14:17:45.305   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 14:17:45.305   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 14:17:45.305   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 14:17:45.305   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 14:17:45.305   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.305   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.305   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.309   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 14:17:45.309   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 14:17:45.309   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.309   872   885 E DropBoxManagerService: 	... 13 more
,08-26 14:17:45.317  1984  2087 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 14:17:45.330   872  2124 I ActivityManager: Start proc 4268:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-26 14:17:45.330  1882  4251 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,--------- beginning of crash
08-26 14:17:45.330  1984  2087 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 14:17:45.330  1984  2087 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1984
08-26 14:17:45.330  1984  2087 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.330  1984  2087 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.331  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 14:17:45.331  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 14:17:45.332   872  2016 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 14:17:45.332   872  4273 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.332   872  4273 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.332   872  4273 E DropBoxManagerService: 	... 5 more
,08-26 14:17:45.343  1984  2087 I Process : Sending signal. PID: 1984 SIG: 9
,08-26 14:17:45.355  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 14:17:45.355  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 14:17:45.356  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 14:17:45.356  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 14:17:45.356  1882  4251 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 14:17:45.356  1882  4251 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-26 14:17:45.356  1882  4251 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 14:17:45.357  1882  4251 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 14:17:45.357  1882  4251 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 14:17:45.357  1882  4251 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 14:17:45.381  4253  4253 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 14:17:45.397  4253  4285 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 14:17:45.404   872   883 I ActivityManager: Start proc 4286:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 14:17:45.421  4253  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.421  4253  4283 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694),
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.421  4253  4283 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.427   872  1408 D GraphicsStats: Buffer count: 1
08-26 14:17:45.427   872   882 I WindowState: WIN DEATH: Window{9da5730 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 14:17:45.438   872  2039 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1984) has died
,08-26 14:17:45.439   872  2039 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 14:17:45.442   872  2039 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 14:17:45.448  4286  4286 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 14:17:45.466   872   885 I ActivityManager: Start proc 4299:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 14:17:45.482  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 14:17:45.482  1504  1504 D AndroidRuntime: Shutting down VM
,08-26 14:17:45.483  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
08-26 14:17:45.483  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
08-26 14:17:45.483  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: ,	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 14:17:45.483  1504  1504 E AndroidRuntime: 	... 8 more
,08-26 14:17:45.495   872  4314 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.495   872  4314 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.495   872  4314 E DropBoxManagerService: 	... 5 more
,08-26 14:17:45.496  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
,08-26 14:17:45.521  4299  4299 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.521  4299  4299 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 14:17:45.521  4299  4299 D AndroidRuntime: Shutting down VM
08-26 14:17:45.529  4299  4299 E AndroidRuntime: FATAL EXCEPTION: main
08-26 14:17:45.529  4299  4299 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4299
08-26 14:17:45.529  4299  4299 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 14:17:45.529  4299  4299 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 14:17:45.529  4299  4299 E AndroidRuntime: 	... 10 more
08-26 14:17:45.531   872  1716 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 14:17:45.531  4299  4299 I Process : Sending signal. PID: 4299 SIG: 9
08-26 14:17:45.531   872  4317 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.531   872  4317 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.531   872  4317 E DropBoxManagerService: 	... 5 more
,08-26 14:17:45.538   872  1317 D WifiService: Client connection lost with reason: 4
,08-26 14:17:45.541  1701  4315 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8c26866
,08-26 14:17:45.543   872  2122 I ActivityManager: Process com.google.process.gapps (pid 1504) has died
,08-26 14:17:45.544   872  2122 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-26 14:17:45.544   872  2122 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,08-26 14:17:45.544   872  2122 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-26 14:17:45.544   872  2122 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-26 14:17:45.553  1701  1701 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 14:17:45.555  4253  4283 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 14:17:45.560  4253  4285 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.560  4253  4285 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.561  4253  4285 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 14:17:45.561  4253  4285 E AndroidRuntime: Process: android.process.acore, PID: 4253
08-26 14:17:45.561  4253  4285 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.561  4253  4285 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:45.563  4253  4283 I Process : Sending signal. PID: 4253 SIG: 9
,08-26 14:17:45.569   872  2005 I ActivityManager: Start proc 4320:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-26 14:17:45.570   872  2123 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4299) has died
,08-26 14:17:45.571   872  2123 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 14:17:45.576   872  4329 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.576   872  4329 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.576   872  4329 E DropBoxManagerService: 	... 5 more
,08-26 14:17:45.586   872   885 I ActivityManager: Start proc 4333:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 14:17:45.605  4320  4320 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-26 14:17:45.608  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 14:17:45.608  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 14:17:45.609   872  1716 I ActivityManager: Process android.process.acore (pid 4253) has died
08-26 14:17:45.609   872  1716 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-26 14:17:45.615  4320  4320 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 14:17:45.617  4320  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.617  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:45.618  4320  4320 D AndroidRuntime: Shutting down VM
08-26 14:17:45.618  4320  4320 E AndroidRuntime: FATAL EXCEPTION: main
08-26 14:17:45.618  4320  4320 E AndroidRuntime: Process: com.google.process.gapps, PID: 4320
08-26 14:17:45.61,8  4320  4320 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 14:17:45.618  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26, 14:17:45.618  4320  4320 E AndroidRuntime: 	... 10 more
08-26 14:17:45.615  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 14:17:45.622  4320  4320 I Process : Sending signal. PID: 4320 SIG: 9
08-26 14:17:45.623   872  4347 E DropBoxManagerService: Can't write: system_app_crash
08-26 14:17:45.623   872  4347 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 14:17:45.623   872  4347 E DropBoxManagerService: 	... 5 more
08-26 14:17:45.623  1701  1701 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-26 14:17:45.628  1701  4349 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 14:17:45.631  4333  4333 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 14:17:45.632  4333  4333 D AndroidRuntime: Shutting down VM
08-26 14:17:45.633   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
