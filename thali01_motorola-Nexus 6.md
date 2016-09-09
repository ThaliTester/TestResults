#### Test 836273375fe617f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-09 13:41:16.434  1526  1526 I ConfigService: onDestroy
,09-09 13:41:17.090  3797  3797 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 13:41:17.107  3797  3797 D AndroidRuntime: CheckJNI is OFF
09-09 13:41:17.175  3797  3797 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 13:41:17.223  3797  3797 I Radio-JNI: register_android_hardware_Radio DONE
09-09 13:41:17.244  3797  3797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-09 13:41:17.250   874  1540 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 13:41:17.311  2022  2036 W SearchService: Abort, client detached.
09-09 13:41:17.321  2022  2358 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@b06e75f
09-09 13:41:17.321  2022  2370 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 13:41:17.321  2022  2022 I HotwordDetector: Closing mic
09-09 13:41:17.341  3797  3797 D AndroidRuntime: Shutting down VM
09-09 13:41:17.393   874  1991 I ActivityManager: Start proc 3806:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 13:41:17.402   377  2372 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 13:41:17.405   377  2372 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 13:41:17.420   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 13:41:17.422  2022  2369 I MicroRecognitionRnrImpl: Detection finished
09-09 13:41:17.423  2022  2362 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 13:41:17.493  3806  3806 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 13:41:17.528  3806  3806 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 13:41:17.540  3806  3806 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8732-8736)
09-09 13:41:17.540  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:17.569  3806  3806 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0ab56f}
09-09 13:41:17.571  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:17.572  3806  3806 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:41:17.589  3806  3806 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:41:17.592  3806  3806 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:41:17.614  3806  3806 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:41:17.632  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 13:41:17.633  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:17.633  3806  3806 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:41:17.633  3806  3806 I Adreno  : Build Date                       : 10/20/15
09-09 13:41:17.633  3806  3806 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:41:17.633  3806  3806 I Adreno  : Local Branch                     : M14
09-09 13:41:17.633  3806  3806 I Adreno  : Remote Branch                    : 
09-09 13:41:17.633  3806  3806 I Adreno  : Remote Branch                    : 
09-09 13:41:17.633  3806  3806 I Adreno  : Reconstruct Branch               : 
,09-09 13:41:17.737   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a99f02:true
,09-09 13:41:17.813  3806  3806 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:41:17.838  3806  3806 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 13:41:17.926  3806  3848 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 13:41:17.944  3806  3834 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 13:41:17.976  3806  3848 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:41:18.028   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +686ms
,09-09 13:41:18.036  1876  1876 I Keyboard.Facilitator: onFinishInput()
,09-09 13:41:18.137  3806  3806 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3806
,09-09 13:41:18.220   874   884 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #17
,09-09 13:41:18.265   874   884 I ActivityManager: Killing 3141:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-09 13:41:18.275  3806  3806 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:41:18.428  3806  3850 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1681917648
,09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 13:41:18.433  3806  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17a4272 added. We now have 1 listener(s)
,09-09 13:41:18.436  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 13:41:18.441  3806  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:18.446  3806  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:18.447  3806  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:41:18.461  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:41:18.462  3806  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceada79 added. We now have 1 listener(s)
09-09 13:41:18.462  3806  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:18.467   874  1319 D WifiService: New client listening to asynchronous messages
,09-09 13:41:18.468  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:18.468  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 13:41:18.468  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:41:18.468  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:41:18.469  3806  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:41:18.472  3806  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:18.472  3806  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 13:41:18.479  3806  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:18.479  3806  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:18.479  3806  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:41:18.479  3806  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:18.480  3806  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:41:18.481  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:18.485  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:18.511  3806  3806 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:41:19.073  3806  3816 I art     : Background sticky concurrent mark sweep GC freed 69265(6MB) AllocSpace objects, 18(1604KB) LOS objects, 30% free, 22MB/32MB, paused 769us total 132.358ms
,09-09 13:41:19.832  3806  3861 W jxcore-log: Initializing JXcore engine
,09-09 13:41:19.832  3806  3861 W jxcore-log: JXcore engine is ready
,09-09 13:41:19.871  3861  3861 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 13:41:19.871  3861  3861 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11014]" dev="sockfs" ino=11014 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 13:41:19.871  3861  3861 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:41:19.871  3861  3861 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27061]" dev="sockfs" ino=27061 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 13:41:19.884  3806  3861 W jxcore-log: Starting JXcore engine
,09-09 13:41:19.962  3806  3861 W jxcore-log: Platform android
09-09 13:41:19.962  3806  3861 W jxcore-log: 
,09-09 13:41:19.962  3806  3861 W jxcore-log: Process ARCH arm
09-09 13:41:19.962  3806  3861 W jxcore-log: 
,09-09 13:41:20.151  3806  3861 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:41:20.151  3806  3861 I jxcore-log: 
,09-09 13:41:20.151  3806  3861 W jxcore-log: JXcore engine is started
,09-09 13:41:20.166  3806  3850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 13:41:20.173  3806  3806 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:41:22.842   874  1318 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 13:41:23.243  1746  1755 W art     : Suspending all threads took: 6.552ms
,09-09 13:41:24.483   874   887 I ActivityManager: Waited long enough for: ServiceRecord{55a7dea u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-09 13:41:26.363  3052  3870 V KeepSync: Connecting to GoogleApiClient
,09-09 13:41:26.364   874  1992 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 13:41:26.411  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:26.414  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:26.461  1526  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 13:41:26.461  1526  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 13:41:26.462  1526  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:41:26.462  1526  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:26.502  1746  3871 V BaseAuthAsyncOperation: access token request failed
,09-09 13:41:26.505  3052  3870 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 13:41:26.610  1526  2333 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 13:41:26.610  1526  2333 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 13:41:26.610  1526  2333 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:26.610  1526  2333 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:26.652  3052  3870 E KeepSync: IOException
09-09 13:41:26.652  3052  3870 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 13:41:26.652  3052  3870 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 13:41:26.652  3052  3870 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 13:41:26.652  3052  3870 E KeepSync: 	... 10 more
,09-09 13:41:26.652  3052  3870 W KeepSync: Sync result 2
,09-09 13:41:26.665   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127486, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:41:28.485   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:41:29.860  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:29.887  1526  2333 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:41:29.887  1526  2333 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-09 13:41:29.887  1526  2333 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:29.887  1526  2333 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:29.913  3548  3548 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:41:29.914  3548  3548 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 13:41:29.914  3548  3548 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 13:41:30.032  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:41:30.032  3806  3861 I jxcore-log: 
,09-09 13:41:30.034  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:41:30.034  3806  3861 I jxcore-log: 
,09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:30.045  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:30.051  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:30.053  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:41:30.053  3806  3861 I jxcore-log: 
,09-09 13:41:30.054  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:41:30.054  3806  3861 I jxcore-log: 
,09-09 13:41:30.592  3806  3861 I jxcore-log: Unit Test app is loaded
09-09 13:41:30.592  3806  3861 I jxcore-log: 
,09-09 13:41:30.598  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:30.598  3806  3861 I jxcore-log: 
,09-09 13:41:30.603  3806  3861 D executeNativeTests: Running unit tests
09-09 13:41:30.603  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:30.603  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2610e0 added. We now have 2 listener(s)
,09-09 13:41:30.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:30.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:30.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:30.604  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:30.605  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c999f99 added. We now have 2 listener(s)
09-09 13:41:30.605  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:30.605  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:30.607  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:30.613  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:30.615  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:30.615  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:30.617  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.618  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:30.623  3806  3806 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:41:31.515   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 13:41:36.827   874  2084 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 13:41:40.709  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:40.709  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f added. We now have 3 listener(s)
,09-09 13:41:40.710  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:40.710  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:40.710  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:40.710  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:40.710  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c added. We now have 3 listener(s)
,09-09 13:41:40.711  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:40.711  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:40.714  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:40.731  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:40.733  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:40.734  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:40.736  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:40.768  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.768  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:40.769  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:40.769  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:40.769  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:40.770  3806  3861 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 13:41:40.770  3806  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:40.770  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 13:41:40.770  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:40.770  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:40.770  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:40.771  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:40.771  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:40.771  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:40.771  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:40.771  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f removed from the list
09-09 13:41:40.771  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:40.771  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c removed from the list
09-09 13:41:40.771  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:40.771  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:40.774  3806  3861 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:41:40.774  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:40.774  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:40.774  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:40.775  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:40.775  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:40.775  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:40.775  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:40.775  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:40.775  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 13:41:40.780  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 13:41:40.781  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:40.782  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:40.782  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:40.782  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 13:41:40.782  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:40.782  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
,09-09 13:41:40.782  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:40.783  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:40.783  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:40.783  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:40.783  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:40.784  3806  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:40.786  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:40.794  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:40.797  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:40.797  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:40.798  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:41:40.798  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-09 13:41:40.798  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:40.798  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:40.798  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:40.800  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:40.802  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:40.804  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:40.804  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:40.804  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:40.804  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:40.804  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:40.805  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:40.805  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:40.808  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:40.809  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:40.810  3806  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 13:41:40.810  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:40.811  3806  3877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:40.816  3806  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:40.817  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:40.820  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 13:41:40.821  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:40.825  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:40.826  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:40.827  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-09 13:41:40.830  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:40.831  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:40.831  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:40.833  3806  3861 D BluetoothAdapter: STATE_ON
,09-09 13:41:40.845  2724  2739 D BtGatt.GattService: registerClient() - UUID=91234465-6846-4666-a472-4b4cda4a5499
,09-09 13:41:40.847  2724  2777 D BtGatt.GattService: onClientRegistered() - UUID=91234465-6846-4666-a472-4b4cda4a5499, clientIf=5
,09-09 13:41:40.848  3806  3818 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:41:40.853  2724  2779 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:40.859  2724  2779 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:40.886  2724  2777 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:41:40.904  2724  2777 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:41:40.907  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:40.907  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:40.908  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:40.914  3806  3861 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:40.914  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:40.915  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:40.916  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:40.916  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:40.916  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:40.917  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:40.926  3806  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:40.927  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:41.424  3806  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 13:41:41.424  3806  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:41:41.425  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 13:41:41.425  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:41:41.426  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:41:41.426  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:41.426  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:41.427  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:41:41.427  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:41:41.428  3806  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:41.428  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:41:41.428  3806  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:41.428  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:41.428  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:41.429  3806  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:41.429  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:41.429  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:41.431  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:41.433  3806  3861 D BluetoothAdapter: STATE_ON
09-09 13:41:41.434  3806  3861 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:41.435  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:41.435  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:41.438  2724  2779 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:41.440  2724  2779 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:41:41.469  2724  2777 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:41:41.469  2724  2777 D BtGatt.GattService: Client app is not null!
,09-09 13:41:41.472  2724  2929 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:41:41.474  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:41.474  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:41.474  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:41.475  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:41.475  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:41.478  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:41.478  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:41.479  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:41.480  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:41.483  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:41:41.483  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:41.485  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:41.486  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:41.486  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:41.487  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:41.487  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:41.488  3806  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:41.488  3806  3861 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:41:41.488  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-09 13:41:41.488  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-09 13:41:41.488  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:41.488  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:41.488  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:41.488  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:41.489  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:41.490  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:41.491  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:41.491  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:41.491  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:41.491  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:41.491  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:41.491  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:41.500  3806  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:41.500  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:41.501  3806  3880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:41.505  3806  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:41.505  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:41.507  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:41:41.507  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:41.511  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:41.511  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:41:41.512  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-09 13:41:41.512  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:41.513  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:41.513  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:41.514  3806  3861 D BluetoothAdapter: STATE_ON
,09-09 13:41:41.520  2724  2929 D BtGatt.GattService: registerClient() - UUID=03020b71-4b8c-4649-9e78-6b156c678846
,09-09 13:41:41.521  2724  2777 D BtGatt.GattService: onClientRegistered() - UUID=03020b71-4b8c-4649-9e78-6b156c678846, clientIf=5
09-09 13:41:41.522  3806  3855 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 13:41:41.524  2724  2779 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:41.528  2724  2779 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:41.541  2724  2777 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:41:41.551  2724  2777 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:41:41.552  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:41.552  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:41.554  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:41.556  3806  3861 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:41.556  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:41.557  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:41.557  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:41.557  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:41.558  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:41.558  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:41.567  3806  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:41.567  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:42.063  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:42.063  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:42.064  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:42.064  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:41:42.065  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 13:41:42.065  3806  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:42.065  3806  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:42.065  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:42.065  3806  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
09-09 13:41:42.065  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.066  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:42.066  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:42.066  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:42.066  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:42.066  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:42.067  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:42.067  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:42.067  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:42.069  3806  3861 D BluetoothAdapter: STATE_ON
09-09 13:41:42.070  3806  3861 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:42.070  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:42.070  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:42.074  2724  2779 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:42.077  2724  2779 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:41:42.093  2724  2777 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:41:42.093  2724  2777 D BtGatt.GattService: Client app is not null!
09-09 13:41:42.095  2724  2734 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:41:42.096  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:42.097  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:42.097  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:42.097  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:42.098  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:42.102  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:42.102  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:42.102  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:42.104  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:42.108  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:42.108  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:42.109  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:42.110  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.110  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:42.110  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.113  3806  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:42.117  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.128  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:42.136  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:42.137  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:42.137  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-09 13:41:42.137  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-09 13:41:42.141  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:42.143  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:42.143  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:41:42.144  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.145  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.148  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:42.150  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:42.150  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:42.150  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:42.151  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:41:42.151  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.151  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:42.153  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.154  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:42.158  3806  3882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:42.161  3806  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:42.162  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:42.162  3806  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:42.175  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:42.176  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:41:42.176  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:42.183  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:42.184  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:41:42.184  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-09 13:41:42.184  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:42.185  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:42.185  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:41:42.187  3806  3861 D BluetoothAdapter: STATE_ON
,09-09 13:41:42.193  2724  2739 D BtGatt.GattService: registerClient() - UUID=c369af0b-2d5f-498a-89c8-305e53e2acef
,09-09 13:41:42.195  2724  2777 D BtGatt.GattService: onClientRegistered() - UUID=c369af0b-2d5f-498a-89c8-305e53e2acef, clientIf=5
,09-09 13:41:42.195  3806  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-09 13:41:42.197  2724  2779 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:42.204  2724  2779 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:42.236  2724  2777 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:41:42.258  2724  2777 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:41:42.260  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:42.261  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:42.267  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:42.271  3806  3861 I io.jxcore.node.ConnectionHelper: start: OK
09-09 13:41:42.271  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:42.272  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:42.272  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:42.272  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:42.272  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:42.273  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:42.280  3806  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:41:42.280  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:42.775  3806  3861 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:41:42.776  3806  3861 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:41:42.776  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:41:42.777  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:42.777  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:41:42.777  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:42.777  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:41:42.779  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:42.779  3806  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:42.780  3806  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:42.780  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:42.780  3806  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:42.780  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:42.781  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:41:42.785  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:42.788  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:41:42.789  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:42.789  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:42.792  3806  3861 D BluetoothAdapter: STATE_ON
,09-09 13:41:42.793  3806  3861 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:42.793  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:42.793  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:42.796  2724  2779 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:42.798  2724  2779 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:41:42.822  2724  2777 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:41:42.822  2724  2777 D BtGatt.GattService: Client app is not null!
,09-09 13:41:42.826  2724  2920 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 13:41:42.828  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:42.830  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:42.830  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:42.830  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:42.832  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:42.838  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:42.838  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:42.839  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:42.840  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:42.844  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:42.845  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:42.845  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:42.846  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:42.846  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:42.847  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:42.847  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:42.857  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.857  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.857  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:42.857  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.858  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:42.858  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.858  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.858  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.860  3806  3861 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 13:41:42.861  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.861  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.861  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.861  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
,09-09 13:41:42.861  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.861  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.861  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.861  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.861  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.862  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:42.862  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.863  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:42.863  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.863  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.863  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.863  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.863  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.863  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.863  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.864  3806  3861 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:41:42.864  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.864  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.864  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.864  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.864  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.864  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.865  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.865  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.865  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.865  3806  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 13:41:42.866  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:42.866  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.866  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.866  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.866  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.866  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.866  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.866  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.866  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.867  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:42.867  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:42.867  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:42.867  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:42.867  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:42.868  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:42.868  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:42.868  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:42.868  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:42.868  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:42.868  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.868  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.868  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.868  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.868  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.868  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:42.869  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.869  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.869  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:42.870  3806  3861 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 13:41:42.870  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:42.874  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:42.874  3806  3861 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:41:42.874  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:42.874  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:41:42.874  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:42.874  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:42.875  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:42.876  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:42.877  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:42.877  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:42.877  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:42.877  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:42.877  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:41:42.877  3806  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:42.878  3806  3861 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:41:42.878  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:42.878  3806  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:42.878  3806  3861 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:41:42.878  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:42.878  3806  3861 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:42.878  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 13:41:42.886  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:41:42.887  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:41:42.887  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:41:42.889  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:41:42.889  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:41:42.889  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:41:42.889  3806  3861 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:42.890  3806  3861 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:41:42.890  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.890  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.890  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.891  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:41:42.891  3806  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
09-09 13:41:42.892  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.892  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.892  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.892  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.892  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.892  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.892  3806  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
09-09 13:41:42.893  3806  3861 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:41:42.894  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.894  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.894  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.894  3806  3885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:42.894  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.894  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.895  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.895  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.895  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.895  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.896  3806  3861 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:41:42.896  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.896  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.896  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.896  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.897  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.897  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.897  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.897  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.897  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.898  3806  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:41:42.898  3806  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:41:42.898  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:42.898  3806  3861 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:41:42.898  3806  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:42.898  3806  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:41:42.898  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:42.898  3806  3861 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:41:42.898  3806  3861 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:42.900  3806  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:42.900  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:42.900  3806  3861 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:41:42.901  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:42.901  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.901  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.902  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:42.902  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:42.902  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:42.902  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.904  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.904  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:42.905  3806  3861 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:42.908  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.916  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:42.919  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:42.919  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:42.919  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:41:42.919  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:41:42.921  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:42.921  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:42.921  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:42.922  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.923  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.925  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:42.926  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:42.926  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:42.926  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:42.926  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:42.926  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:42.926  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:42.929  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.929  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:42.930  3806  3887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:42.932  3806  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:42.932  3806  3861 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 13:41:42.932  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:42.938  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:42.939  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 13:41:42.939  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:41:42.940  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:41:42.941  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:41:42.941  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-09 13:41:42.941  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:42.941  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:42.941  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:41:42.941  3806  3861 D BluetoothAdapter: STATE_ON
09-09 13:41:42.943  2724  2920 D BtGatt.GattService: registerClient() - UUID=f2ef6f66-e3d7-49b4-82bb-41f61a4d3ab4
09-09 13:41:42.944  2724  2777 D BtGatt.GattService: onClientRegistered() - UUID=f2ef6f66-e3d7-49b4-82bb-41f61a4d3ab4, clientIf=5
09-09 13:41:42.944  3806  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-09 13:41:42.945  2724  2779 D BtGatt.AdvertiseManager: message : 0
09-09 13:41:42.946  2724  2779 D BtGatt.AdvertiseManager: starting multi advertising
09-09 13:41:42.956  2724  2777 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 13:41:42.962  2724  2777 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 13:41:42.963  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:42.963  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:42.965  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:42.966  3806  3861 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:42.966  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:42.966  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:42.967  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:42.967  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:42.967  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:42.967  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:42.970  3806  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:42.970  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:43.471  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:43.472  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:43.472  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:43.472  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:41:43.472  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-09 13:41:43.473  3806  3887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:43.473  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:43.474  3806  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:43.474  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:43.474  3806  3887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:43.475  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:43.475  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:43.476  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:43.476  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.476  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:43.476  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:43.477  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:43.478  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:43.480  3806  3861 D BluetoothAdapter: STATE_ON
09-09 13:41:43.481  3806  3861 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:43.481  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:43.481  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:43.484  2724  2779 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:43.485  2724  2779 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 13:41:43.508  2724  2777 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 13:41:43.508  2724  2777 D BtGatt.GattService: Client app is not null!
,09-09 13:41:43.511  2724  2739 D BtGatt.GattService: unregisterClient() - clientIf=5
09-09 13:41:43.512  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:43.513  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:43.513  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:43.514  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:43.514  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:43.519  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:43.519  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-09 13:41:43.520  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:43.521  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:43.527  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:43.527  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:43.528  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:43.529  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
,09-09 13:41:43.529  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.530  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.538  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:43.538  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:43.539  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.539  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:43.539  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.540  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
,09-09 13:41:43.540  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.540  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.540  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.542  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:43.542  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:43.543  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:43.543  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:43.543  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:43.544  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:43.544  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:43.544  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:43.544  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:43.544  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:43.544  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:43.544  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:43.544  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.544  3806  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:43.544  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:43.545  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:43.545  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:43.545  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.545  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:43.545  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:41:43.545  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:43.545  3806  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:43.545  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.545  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.547  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:43.547  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:43.547  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:43.547  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:43.548  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:43.548  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:43.548  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.548  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.549  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.552  3806  3861 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-09 13:41:43.552  3806  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 13:41:43.553  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 13:41:43.553  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:41:43.553  3806  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:41:43.554  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:43.554  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.554  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.554  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
,09-09 13:41:43.554  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.554  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
09-09 13:41:43.554  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:43.554  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.554  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.558  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:43.558  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:43.558  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.558  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
09-09 13:41:43.558  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.558  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
,09-09 13:41:43.559  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.559  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.559  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.560  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:43.560  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:43.560  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.560  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1438d2f not in the list
,09-09 13:41:43.560  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.560  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@219f3c not in the list
,09-09 13:41:43.560  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.560  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:43.560  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.562  3806  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-09 13:41:43.562  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:43.562  3806  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:41:43.562  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 13:41:43.562  3806  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:41:43.562  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 13:41:43.565  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:43.566  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:41:43.566  3806  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:41:43.566  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:43.567  3806  3861 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-09 13:41:43.567  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 13:41:43.567  3806  3861 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:41:43.567  3806  3861 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:41:43.567  3806  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-09 13:41:43.567  3806  3861 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 13:41:43.568  3806  3861 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-09 13:41:43.568  3806  3861 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:41:43.568  3806  3861 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:41:43.568  3806  3861 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 13:41:43.571  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:43.571  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d1e935 added. We now have 3 listener(s)
09-09 13:41:43.572  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:43.572  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:43.573  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:43.573  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:43.573  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ca1ca added. We now have 3 listener(s)
09-09 13:41:43.573  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:43.573  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:43.576  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:43.580  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.582  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:43.582  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:43.584  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:43.584  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.584  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:43.584  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:43.584  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d1e935 removed from the list
09-09 13:41:43.585  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.585  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ca1ca removed from the list
09-09 13:41:43.585  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:43.585  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:43.586  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:43.587  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:43.587  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f91f658 added. We now have 3 listener(s)
,09-09 13:41:43.588  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:43.588  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:43.589  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:43.589  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:43.589  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a44e3b1 added. We now have 3 listener(s)
09-09 13:41:43.589  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:43.589  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:43.589  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.591  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:43.596  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.598  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:43.598  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:43.598  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:43.598  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:43.598  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:43.598  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:43.598  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f91f658 removed from the list
09-09 13:41:43.599  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:43.599  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a44e3b1 removed from the list
,09-09 13:41:43.600  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.601  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:43.601  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:43.602  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:43.602  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317f417 added. We now have 3 listener(s)
,09-09 13:41:43.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:43.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:43.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:43.604  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:43.604  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5c2004 added. We now have 3 listener(s)
09-09 13:41:43.604  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:43.604  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:43.605  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:43.607  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:43.611  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.614  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:43.614  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:43.615   874  1399 D WifiService: setWifiEnabled: false pid=3806, uid=10000
,09-09 13:41:43.616   874  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:41:43.617  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.621  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.648  1480  1480 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 13:41:43.653   874  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:43.654   874  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-09 13:41:43.654   874  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:41:43.655   874  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:43.669   874  2091 D DhcpClient: Clearing IP address
,09-09 13:41:43.670   373   873 D CommandListener: Setting iface cfg
,09-09 13:41:43.674   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:43.677   874  2096 D DhcpClient: Receive thread stopped
,09-09 13:41:43.684  1526  2549 V NativeCrypto: Read error: ssl=0x9b509a00: I/O error during system call, Connection timed out
,09-09 13:41:43.687  1526  2549 V NativeCrypto: SSL shutdown failed: ssl=0x9b509a00: I/O error during system call, Broken pipe
,09-09 13:41:43.690   874  1976 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-09 13:41:43.691   874  2074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-09 13:41:43.695   874  2074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-09 13:41:43.697   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-09 13:41:43.697   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-09 13:41:43.700   404   404 E Parcel  : Reading a NULL string not supported here.
,09-09 13:41:43.701   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 13:41:43.706   874  1318 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 13:41:43.707   874  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:41:43.709   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:43.711   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 13:41:43.712   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 13:41:43.715   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.720  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.723  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:43.726  2069  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.727  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.730  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.733  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:43.735  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:43.737   874  1991 I ActivityManager: Start proc 3894:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 13:41:43.738   874  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-09 13:41:43.743   874  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:41:43.768   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:43.774  3894  3894 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 13:41:43.790   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:43.792   874  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 13:41:43.792   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.802   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:43.810  3420  3420 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bfee441 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.813  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.816  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:43.819  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:43.830  3894  3894 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
09-09 13:41:43.845  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 13:41:43.849  1746  1746 D SystemUpdateService: onCreate,
09-09 13:41:43.850   373   873 E Netd    : netlink response contains error (No such file or directory)
09-09 13:41:43.851   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:41:43.853  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 13:41:43.861  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-09 13:41:43.865  1746  2525 I iu.UploadsManager: num queued entries: 0
09-09 13:41:43.865  1746  2525 I iu.UploadsManager: num updated entries: 0
09-09 13:41:43.865  1746  2525 I iu.SyncManager: NEXT; no task
09-09 13:41:43.866  1746  3927 I SystemUpdateService: active receiver: enabled
09-09 13:41:43.868  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-09 13:41:43.869  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-09 13:41:43.869  1746  3927 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-09 13:41:43.871  1746  3927 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 13:41:43.871  1746  3927 I SystemUpdateService: now status is 0 (complete)
09-09 13:41:43.871  1746  3927 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:41:43.871  1746  3927 I SystemUpdateService: file has been verified
09-09 13:41:43.871  1746  3927 I SystemUpdateService: OTA package size = 12249756
09-09 13:41:43.878  1746  3927 I SystemUpdateService: showing system update notification
,09-09 13:41:43.894   874  1992 I ActivityManager: Start proc 3929:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-09 13:41:43.921  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
09-09 13:41:43.924  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.929  3929  3929 D SprintDMHelper: simOperator: 
,09-09 13:41:43.930  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:41:43.946   874   884 I ActivityManager: Start proc 3941:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 13:41:43.947   874   884 I ActivityManager: Killing 2996:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 13:41:43.990  1746  1746 D SystemUpdateService: onDestroy
,09-09 13:41:44.007   874  1540 I ActivityManager: Killing 3420:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 13:41:44.048  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:44.089   874  1991 I ActivityManager: Start proc 3956:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 13:41:44.092  3094  3955 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
09-09 13:41:44.097   874  1976 I ActivityManager: Killing 3609:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-09 13:41:44.123   874   885 D WifiService: setWifiEnabled: true pid=3806, uid=10000
09-09 13:41:44.124   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:41:44.129  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:44.129  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:44.129  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:44.130  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:44.130  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@317f417 removed from the list
09-09 13:41:44.130  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:44.130  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5c2004 removed from the list
09-09 13:41:44.130  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:44.130  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:44.145   874  1318 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:41:44.146  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:44.146  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6fa022 added. We now have 3 listener(s)
,09-09 13:41:44.147  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:44.147  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:44.147  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:44.147  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:44.147  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79dbab3 added. We now have 3 listener(s)
09-09 13:41:44.149  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:44.153  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:44.156  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.160  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.162  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:44.165  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:44.167  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:44.167  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:44.167  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:44.168  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:44.168  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:44.168  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:44.168  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6fa022 removed from the list
09-09 13:41:44.168  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:44.168  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79dbab3 removed from the list
,09-09 13:41:44.168  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:44.168  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:44.169   874  1318 D WifiConfigStore: loaded 0 passpoint configs
09-09 13:41:44.169  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:44.169  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12357e9 added. We now have 3 listener(s)
,09-09 13:41:44.170   874  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 13:41:44.171   874  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:41:44.171  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:44.171  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:44.171  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:44.171   874  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 13:41:44.171  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:44.172  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80b9c6e added. We now have 3 listener(s)
09-09 13:41:44.172   874  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 13:41:44.172  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:44.172   874  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:41:44.172   874  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-09 13:41:44.172  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:44.175  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.175  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:44.177  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.180  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:44.181  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
09-09 13:41:44.182  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:44.182  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:44.184  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.184   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-09 13:41:44.186  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.186  2724  2773 D BluetoothAdapterState: Current state: ON, message: 23
09-09 13:41:44.186  2724  2773 D BluetoothAdapterProperties: Setting state to 13
09-09 13:41:44.186  2724  2773 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 13:41:44.187   373   873 D CommandListener: Setting iface cfg
09-09 13:41:44.187  2724  2773 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:41:44.187  2724  2773 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:41:44.188   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 13:41:44.188  2724  2724 D BluetoothMapService: onReceive
09-09 13:41:44.188   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 13:41:44.188  2724  2724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:44.188  2724  2724 D BluetoothMapService: STATE_TURNING_OFF
09-09 13:41:44.188  2724  2724 D BluetoothMapService: MAP Service closeService in
09-09 13:41:44.188  2724  2724 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 13:41:44.188  2724  2724 D ObexServerSockets0: shutdown(block = true)
09-09 13:41:44.189  2724  2777 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:44.189  2724  2724 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:41:44.189  2724  2724 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 13:41:44.189  2724  2773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 13:41:44.189  2724  2930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 13:41:44.190  2724  2910 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 13:41:44.190  2724  2931 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 13:41:44.191  2724  2724 I BtOppRfcommListener: stopping Accept Thread
09-09 13:41:44.191  2724  3470 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 13:41:44.191  2724  3470 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 13:41:44.192  2724  2724 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:41:44.192  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.192  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:44.193   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:41:44.193  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.194  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:44.196  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.196  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:44.196  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.196  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:44.196   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:41:44.198  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.198   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:44.198   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:44.198  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:44.198  1384  1396 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:44.199  1931  3541 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:44.199  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:44.199   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 13:41:44.199  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:44.199   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:44.199   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-09 13:41:44.200  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.202  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.202  2724  2773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-09 13:41:44.202  2724  2773 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-09 13:41:44.203  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.203  2724  2724 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:44.204  2724  2923 D A2dpStateMachine: Exit Disconnected: -1
09-09 13:41:44.205   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:44.205  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.206  2724  2724 D HidService: Received stop request...Stopping profile...
09-09 13:41:44.206  2724  2724 D HidService: Stopping Bluetooth HidService
09-09 13:41:44.207  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.207  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.208  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.208  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.209  2724  2724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 13:41:44.209  2724  2724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 13:41:44.210  2724  2777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 13:41:44.210  2724  2724 D HealthService: Received stop request...Stopping profile...
09-09 13:41:44.210  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.210  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.210  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.210  2724  2777 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 13:41:44.214  1384  1384 D HeadsetProfile: Bluetooth service disconnected
09-09 13:41:44.214  1384  1384 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:44.215  1384  1384 D BluetoothInputDevice: Proxy object disconnected
09-09 13:41:44.215  1384  1384 D HidProfile: Bluetooth service disconnected
09-09 13:41:44.217  2724  2724 D PanService: Received stop request...Stopping profile...
09-09 13:41:44.217  1384  1384 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 13:41:44.217  1384  1384 D PanProfile: Bluetooth service disconnected
09-09 13:41:44.218  2724  2724 D BluetoothMapService: Received stop request...Stopping profile...
09-09 13:41:44.218  2724  2724 D BluetoothMapService: stop()
09-09 13:41:44.218  2724  2724 D BluetoothMapAppObserver: deinitObservers()
09-09 13:41:44.218  2724  2724 D BluetoothMapAppObserver: removeReceiver()
09-09 13:41:44.219  1384  1384 D BluetoothMap: Proxy object disconnected
09-09 13:41:44.219  1384  1384 D MapProfile: Bluetooth service disconnected
09-09 13:41:44.220  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.220  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.220  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.220  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.221  2724  2724 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:41:44.221  2724  2724 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.221  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.222  2724  2724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 13:41:44.222  2724  2777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:41:44.222  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.222  2724  2777 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 13:41:44.222  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.222  2724  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:44.222  2724  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:44.222  2724  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:44.222  2724  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:44.222  2724  2777 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 13:41:44.222  2724  2724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:44.223  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.223  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.223  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.223  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.226  2724  2724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 13:41:44.226  2724  2724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 13:41:44.227  2724  2724 D BluetoothMapService: MAP Service closeService in
09-09 13:41:44.227  2724  2724 V BluetoothAdapterState: isTurningOff()=true
09-09 13:41:44.227  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.227  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
09-09 13:41:44.227  2724  2724 V BluetoothAdapterState: isBleTurningOff()=false
09-09 13:41:44.227  2724  2773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 13:41:44.227  2724  2724 D BluetoothMapService: cleanup()
09-09 13:41:44.227  2724  2724 D BluetoothMapService: MAP Service closeService in
09-09 13:41:44.227  2724  2773 D BluetoothAdapterProperties: Setting state to 15
09-09 13:41:44.227  2724  2773 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 13:41:44.228  2724  2773 I BluetoothAdapterState: Entering BleOnState
09-09 13:41:44.228  2724  2773 D BluetoothAdapterState: Current state: BLE ON, message: 0
09-09 13:41:44.228   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:44.228  1384  1398 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 13:41:44.228  1384  2060 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:44.229   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:44.229  1931  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:44.229   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 13:41:44.229  1384  1396 D BluetoothPan: onBluetoothStateChange on: false
09-09 13:41:44.230  1384  1398 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:44.230  1384  2060 D BluetoothMap: onBluetoothStateChange: up=false
09-09 13:41:44.230   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 13:41:44.231  1384  1396 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 13:41:44.232  2724  2773 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 13:41:44.232  2724  2773 D BluetoothAdapterProperties: Setting state to 16
09-09 13:41:44.232  2724  2773 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-09 13:41:44.232  2724  2773 D BluetoothAdapterProperties: onBleDisable
09-09 13:41:44.232  2724  2773 I BluetoothAdapterState: Entering PendingCommandState
09-09 13:41:44.233  2724  2774 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 13:41:44.233  2724  2777 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:44.233  2724  2901 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 13:41:44.233  2724  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 13:41:44.234  3806  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
09-09 13:41:44.236  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.237  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.238  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.241  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.243  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:44.244  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:44.276  3956  3956 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 13:41:44.276  3956  3956 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 13:41:44.276  3956  3956 I GAv4    :   adb logcat -s GAv4
09-09 13:41:44.287  3956  3956 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-09 13:41:44.293  3956  3956 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:44.317  3956  3978 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 13:41:44.416  3956  3956 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 13:41:44.435  2724  2777 I bt_hci  : shut_down
,09-09 13:41:44.436  2724  2781 D bt_hwcfg: hw_epilog_process
,09-09 13:41:44.437  2724  2781 I bt_vendor: low_power_mode_cb
,09-09 13:41:44.458  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 13:41:44.463  2724  2781 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 13:41:44.463  2724  2781 I bt_vendor: epilog_cb
09-09 13:41:44.463  2724  2781 I bt_hci  : epilog_finished_callback
,09-09 13:41:44.467  2724  2777 I bt_hci_h4: hal_close
,09-09 13:41:44.467  2724  2777 I bt_userial_vendor: device fd = 51 close
,09-09 13:41:44.483  3956  3956 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 5665-5680)
,09-09 13:41:44.493  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:44.502  3956  3956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60556b3}
09-09 13:41:44.503  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:41:44.503  3956  3956 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:41:44.512  3956  3956 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:41:44.514  3956  3956 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:41:44.530  3956  3956 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 13:41:44.543  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:44.543  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 13:41:44.543  3956  3956 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:41:44.543  3956  3956 I Adreno  : Build Date                       : 10/20/15
09-09 13:41:44.543  3956  3956 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:41:44.543  3956  3956 I Adreno  : Local Branch                     : M14
09-09 13:41:44.543  3956  3956 I Adreno  : Remote Branch                    : 
09-09 13:41:44.543  3956  3956 I Adreno  : Remote Branch                    : 
09-09 13:41:44.543  3956  3956 I Adreno  : Reconstruct Branch               : 
,09-09 13:41:44.584  2724  2774 D bt_stack_manager: event_shut_down_stack finished.
,09-09 13:41:44.586  2724  2773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 13:41:44.591  2724  2724 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 13:41:44.592  2724  2773 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-09 13:41:44.592  2724  2724 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 13:41:44.592  2724  2724 D BtGatt.GattService: stop()
09-09 13:41:44.592  2724  2724 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 13:41:44.596  2724  2724 V BluetoothAdapterState: isTurningOff()=false
,09-09 13:41:44.597  2724  2724 V BluetoothAdapterState: isTurningOn()=false
09-09 13:41:44.597  2724  2724 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 13:41:44.597  2724  2724 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 13:41:44.598  2724  2773 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-09 13:41:44.598  2724  2773 D BluetoothAdapterProperties: Setting state to 10
,09-09 13:41:44.599  2724  2773 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 13:41:44.600  2724  2773 I BluetoothAdapterState: Entering OffState
,09-09 13:41:44.605  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:44.609  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:44.612  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:44.620  3956  3956 I NSApplication: Starting up...
,09-09 13:41:44.624  3956  4007 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:41:44.658   874  1399 I ActivityManager: Start proc 4012:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 13:41:44.659   874  1399 I ActivityManager: Killing 3504:com.android.providers.calendar/u0a3 (adj 15): empty #17
09-09 13:41:44.660   279   279 E lowmemorykiller: Error writing /proc/3504/oom_score_adj; errno=22
,09-09 13:41:44.737  4012  4012 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 13:41:44.949   874   885 I ActivityManager: Killing 1692:android.process.acore/u0a5 (adj 15): empty #17
,09-09 13:41:45.056   874  1972 I ActivityManager: Start proc 4028:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 13:41:45.156  4028  4028 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-09 13:41:45.172  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:45.183   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7495deb:true
,09-09 13:41:45.186  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:45.228   874  1972 I ActivityManager: Start proc 4040:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-09 13:41:45.274  4028  4028 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 13:41:45.277  4028  4028 D BluetoothMap: Create BluetoothMap proxy object
,09-09 13:41:45.284  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 13:41:45.290  4028  4028 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 13:41:45.304  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:45.316   874   884 I ActivityManager: Killing 3696:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.482  4040  4040 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.482  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.485  4040  4040 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.485  4040  4040 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:45.485  4040  4040 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:45.497  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:45.516  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:45.517  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:45.521   874  1991 I ActivityManager: Killing 3712:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 13:41:45.579  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:45.591  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:45.613  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:45.798  4040  4061 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 13:41:45.824   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cad89a8:true
,09-09 13:41:49.226  3806  3972 E io.jxcore.node.ConnectivityMonitorTest: BT is not enabled after 5s!
,09-09 13:41:49.231  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:49.234  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:49.234  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:49.234  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:49.235  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:41:49.235  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12357e9 removed from the list
,09-09 13:41:49.235  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:49.235  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80b9c6e removed from the list
,09-09 13:41:49.236  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:49.236  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:49.239  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:49.239  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6556b9c added. We now have 3 listener(s)
,09-09 13:41:49.247  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 13:41:49.247  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:49.248  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:49.248  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:49.248  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd089a5 added. We now have 3 listener(s)
,09-09 13:41:49.248  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:49.249  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:49.255  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:49.260  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.260  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:49.262  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.262  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.262  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:49.263   874   884 D WifiService: setWifiEnabled: false pid=3806, uid=10000
,09-09 13:41:49.264   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:41:49.265  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:49.268  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:49.278  2069  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:49.282   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:41:49.284  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.284  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:49.285  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.286  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:49.292  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.292  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:49.294  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.294  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.297  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.298  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:49.298  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.299  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:49.781  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:49.784   874  1399 D WifiService: setWifiEnabled: true pid=3806, uid=10000
,09-09 13:41:49.784   874  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 13:41:49.802   874  1318 D WifiConfigStore: Loading config and enabling all networks 
,09-09 13:41:49.806  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.806  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:49.807  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:49.808  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:49.808  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.809  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.812  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.812  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:49.813  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:49.815  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
09-09 13:41:49.815  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:49.816  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:49.816  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:49.816  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:49.816  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:49.816  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 13:41:49.816  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6556b9c removed from the list
09-09 13:41:49.816  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:49.816  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd089a5 removed from the list
09-09 13:41:49.817  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:49.817  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:49.817  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:49.822  3806  4084 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 13:41:49.822  3806  4084 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:49.829   874  1318 D WifiConfigStore: loaded 0 passpoint configs
,09-09 13:41:49.830   874  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-09 13:41:49.831   874  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 13:41:49.832   874  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:49.832   874  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 13:41:49.832   874  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-09 13:41:49.832   874  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 13:41:49.844   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 13:41:49.845   373   873 D CommandListener: Setting iface cfg
09-09 13:41:49.845   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)',
09-09 13:41:49.845   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:41:49.848   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
09-09 13:41:49.848   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 13:41:49.868   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:41:49.916   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:41:50.340  3806  4087 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 13:41:50.340  3806  4084 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:41:50.341  3806  4087 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:50.341  3806  4084 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:50.341  3806  4087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.341  3806  4084 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.342  3806  4087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.342  3806  4087 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:41:50.343  3806  4084 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:50.345  3806  4090 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: IncomingSocketThread/Sender)
,09-09 13:41:50.346  3806  4084 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:50.347  3806  4092 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: OutgoingSocketThread/Sender)
,09-09 13:41:50.351  3806  4091 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: IncomingSocketThread/Receiver)
09-09 13:41:50.351  3806  4093 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: OutgoingSocketThread/Receiver)
,09-09 13:41:50.351  3806  4093 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 488, thread name: OutgoingSocketThread/Receiver)
,09-09 13:41:50.352  3806  4093 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:50.352  3806  4093 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:50.353  3806  4091 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 487, thread name: IncomingSocketThread/Receiver)
09-09 13:41:50.354  3806  4091 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:50.354  3806  4091 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:50.847  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 13:41:50.848  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:41:50.850  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c5851bd Bundle[{}]
,09-09 13:41:50.851  3806  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:41:50.851  3806  3861 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 13:41:50.852  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-09 13:41:50.852  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:41:50.853  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 13:41:50.854  3806  3861 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:50.864  3806  4094 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:41:50.865  3806  4094 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:51.336   874  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.12 rxSuccessRate=0.24 delta 1000 -> 1000
,09-09 13:41:51.340   874  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-09 13:41:51.341   874  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:51.363   874  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 13:41:51.374  3806  4096 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 13:41:51.374  3806  4094 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-09 13:41:51.375  3806  4096 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:51.375  3806  4094 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 13:41:51.375  3806  4094 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
,09-09 13:41:51.375  3806  4096 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:51.376  3806  4096 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:51.377  3806  4094 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:51.379  3806  4096 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 13:41:51.379  3806  4098 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: IncomingSocketThread/Sender),
,09-09 13:41:51.386  3806  4099 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: OutgoingSocketThread/Sender)
,09-09 13:41:51.388  3806  4094 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:51.392  3806  4100 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: IncomingSocketThread/Receiver)
,09-09 13:41:51.394  3806  4100 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: IncomingSocketThread/Receiver)
,09-09 13:41:51.394  3806  4101 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 502, name: OutgoingSocketThread/Receiver)
09-09 13:41:51.394  3806  4100 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-09 13:41:51.394  3806  4100 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:41:51.395  3806  4101 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 502, thread name: OutgoingSocketThread/Receiver)
,09-09 13:41:51.395  3806  4101 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 13:41:51.395  3806  4101 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 502, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:51.411   874  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 13:41:51.412  1480  1480 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 13:41:51.835  1480  1480 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 13:41:51.881  1480  1480 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 13:41:51.883  1480  1480 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 13:41:51.884  3806  3861 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 511)
,09-09 13:41:51.885  3806  3861 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 13:41:51.887  3806  3861 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 512)
,09-09 13:41:51.888   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:41:51.899  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:51.899  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b added. We now have 3 listener(s)
,09-09 13:41:51.905   874  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:41:51.906   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 13:41:51.906  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 13:41:51.906   874  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 13:41:51.906  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:51.906  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:51.907  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:51.907  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 added. We now have 3 listener(s)
09-09 13:41:51.908  3806  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:51.908  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:51.911  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:51.913  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:51.914  3806  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:51.915  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:51.915  3806  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:51.915  3806  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:51.916  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:51.917  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:51.917  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:51.917  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:51.917  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:51.917  3806  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b removed from the list
09-09 13:41:51.917  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:51.917  3806  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 removed from the list
,09-09 13:41:51.920   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 13:41:51.923  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:51.925   874  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:51.925  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:51.927  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:51.927  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:51.928   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 13:41:51.928   874   894 I Adreno  : Build Date                       : 10/20/15
09-09 13:41:51.928   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 13:41:51.928   874   894 I Adreno  : Local Branch                     : M14
09-09 13:41:51.928   874   894 I Adreno  : Remote Branch                    : 
09-09 13:41:51.928   874   894 I Adreno  : Remote Branch                    : 
09-09 13:41:51.928   874   894 I Adreno  : Reconstruct Branch               : 
,09-09 13:41:51.929  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-09 13:41:51.929  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-09 13:41:51.931  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:51.931  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:41:51.931  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:51.931  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:51.932  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-09 13:41:51.932  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-09 13:41:51.933  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED,
,09-09 13:41:51.933  1876  1876 I Keyboard.Facilitator: onFinishInput()
09-09 13:41:51.937   373   873 D CommandListener: Setting iface cfg
,09-09 13:41:51.938  3806  3861 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,09-09 13:41:51.938  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:51.940  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:51.939   874  1318 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:41:51.941  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:51.944  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:41:51.947  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:41:51.948  3806  3861 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-09 13:41:51.947   874  4104 D DhcpClient: Receive thread started
,09-09 13:41:51.950  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:51.951  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:51.951  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:41:51.952  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:51.953  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-09 13:41:51.954   874  1320 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-09 13:41:51.954  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:51.955  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b not in the list
09-09 13:41:51.956   874  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-09 13:41:51.956  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:51.956  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:41:51.958  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:51.960  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:51.960  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:51.961  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:51.962  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:51.963  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:51.964  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:51.964  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:51.965  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 not in the list
,09-09 13:41:51.965  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:51.966  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:51.966  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:51.967  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:51.970  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:51.970  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:51.970  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:51.970  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:51.970  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:51.972  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:41:51.972   281  1308 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
09-09 13:41:51.973  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:41:51.973  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-09 13:41:51.973  3806  3861 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 13:41:52.040   874  1318 E native  : do suspend false
,09-09 13:41:52.057   874  2091 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 13:41:52.070   874  4104 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172671, domain null
,09-09 13:41:52.070   874  2091 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172671 seconds
09-09 13:41:52.071   874  2091 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 13:41:52.083   874  4104 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 13:41:52.083   874  2091 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-09 13:41:52.084   373   873 D CommandListener: Setting iface cfg
,09-09 13:41:52.088   874  2091 D DhcpClient: Scheduling renewal in 86399s
,09-09 13:41:52.092   874  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 13:41:52.103   874  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 13:41:52.103   874  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 13:41:52.103   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:52.104   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 13:41:52.116   874  1320 D ConnectivityService: Adding iface wlan0 to network 101
09-09 13:41:52.124   874  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:52.152   874  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:52.152   874  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-09 13:41:52.153   874  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 13:41:52.154   874  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 13:41:52.155   874  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 13:41:52.162   874  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 13:41:52.167   874  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 13:41:52.167   874  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 13:41:52.167   874  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
09-09 13:41:52.167   874  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 13:41:52.167   874  1320 D ConnectivityService:    accepting network in place of null
,09-09 13:41:52.168   874  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-09 13:41:52.168   874  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 13:41:52.184   874  4103 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153381, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 13:41:52.193   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:52.217   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 13:41:52.225   874  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 13:41:52.225   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:52.232   874  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 13:41:52.233   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:52.244  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:52.244  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:52.245  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:52.245  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:52.250   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-09 13:41:52.251  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:52.251  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:52.252  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:52.253  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:52.261  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 13:41:52.265  1746  1746 D SystemUpdateService: onCreate
,09-09 13:41:52.271  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 13:41:52.289  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:52.297  1746  4116 I SystemUpdateService: active receiver: enabled
,09-09 13:41:52.303  1746  2525 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:52.303  1746  2525 I iu.UploadsManager: num updated entries: 0
09-09 13:41:52.304  1746  2525 I iu.SyncManager: NEXT; no task
,09-09 13:41:52.306  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 13:41:52.308  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 13:41:52.310  1746  4116 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 13:41:52.312  1746  4116 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 13:41:52.313  1746  4116 I SystemUpdateService: now status is 0 (complete)
,09-09 13:41:52.314   874   886 I ActivityManager: Start proc 4122:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-09 13:41:52.321   874  4102 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:52 GMT], X-Android-Received-Millis=[1473421312319], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473421312297]}
,09-09 13:41:52.324   874  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 13:41:52.324   874  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 13:41:52.324   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-09 13:41:52.325   874  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:52.321  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:52.335  1746  4119 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 13:41:52.335  1746  4119 W BaseAppContext: Using Auth Proxy for data requests.
09-09 13:41:52.337  3929  3929 D SprintDMHelper: simOperator: 
09-09 13:41:52.337  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 13:41:52.344  1746  4119 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 13:41:52.314  1746  4116 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 13:41:52.352  1746  4116 I SystemUpdateService: file has been verified
09-09 13:41:52.352  1746  4116 I SystemUpdateService: OTA package size = 12249756
,09-09 13:41:52.361  4122  4122 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-09 13:41:52.377  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:52.379  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:52.387  3012  3021 W art     : Suspending all threads took: 9.777ms
,09-09 13:41:52.403  1746  4116 I SystemUpdateService: showing system update notification
,09-09 13:41:52.431  1746  1746 D SystemUpdateService: onDestroy
,09-09 13:41:52.442  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 13:41:52.442  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 13:41:52.443  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:41:52.443  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:52.449  4122  4122 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-09 13:41:52.456  1746  4119 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-09 13:41:52.460  4122  4122 I BooksApp: Created application version: 3.6.9 (30609)
,09-09 13:41:52.473  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-09 13:41:52.474  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:52.485  3094  4136 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 13:41:52.501  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:52.501  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:41:52.523   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 13:41:52.527  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c5851bd Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@899234, 16908290=android.view.AbsSavedState$1@899234}, android:focusedViewId=100}]}]
09-09 13:41:52.527  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:41:52.527  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:41:52.527  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-09 13:41:52.527   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-09 13:41:52.532   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 13:41:52.534   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-09 13:41:52.534   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 13:41:52.564  1526  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:41:52.565  1526  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:41:52.565  1526  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 13:41:52.565  1526  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:52.577  3012  4138 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 13:41:52.577  3012  4138 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at blb.a(PG:3937)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at czp.a(PG:18188)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:41:52.577  3012  4138 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	... 12 more
09-09 13:41:52.577  3012  4138 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at fal.a(PG:38)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:41:52.577  3012  4138 E HttpOperation: 	... 14 more
,09-09 13:41:52.605  1526  2995 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 13:41:52.606  1526  2995 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 13:41:52.606  1526  2995 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:52.606  1526  2995 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:52.609  4122  4149 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 13:41:52.616  3012  4138 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 13:41:52.616  3012  4138 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jdm.a(PG:82)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jcs.o(PG:406)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jcn.a(PG:1379)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jcs.i(PG:143)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at hec.a(PG:42)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at hee.a(PG:102)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at czr.a(PG:65)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at kka.a(PG:108)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at czp.a(PG:19176)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at czp.a(PG:9081)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at czq.run(PG:1686)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:41:52.616  3012  4138 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jdj.a(PG:4091)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jdj.a(PG:1125)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jdm.a(PG:77)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	... 15 more
09-09 13:41:52.616  3012  4138 E HttpOperation: Caused by: faj: BadAuthentication
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at fal.a(PG:38)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	at jdj.a(PG:4089)
09-09 13:41:52.616  3012  4138 E HttpOperation: 	... 17 more
,09-09 13:41:52.616  3012  4138 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,09-09 13:41:52.616  3012  4138 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at hec.a(PG:42)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at hee.a(PG:102)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at czr.a(PG:65)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at kka.a(PG:108)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	... 15 more
09-09 13:41:52.616  3012  4138 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at fal.a(PG:38)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 13:41:52.616  3012  4138 E ExperimentLoader: 	... 17 more
,09-09 13:41:52.728   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131589, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:41:52.766   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 13:41:52.772  4122  4157 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 13:41:52.768   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-09 13:41:52.775   874  1341 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,09-09 13:41:52.778   874   894 I DreamManagerService: Entering dreamland.
,09-09 13:41:52.779   874   894 I PowerManagerService: Dozing...
,09-09 13:41:52.780   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 13:41:52.823  1526  2993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:41:52.823  1526  2993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 13:41:52.823  1526  2993 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:52.823  1526  2993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:52.832   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 13:41:52.832   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 13:41:52.849   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 13:41:52.853  1919  4159 D NfcService: Discovery configuration equal, not updating.
,09-09 13:41:52.858  1526  2333 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 13:41:52.858  1526  2333 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 13:41:52.858  1526  2333 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:52.858  1526  2333 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 13:41:52.860   874  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 13:41:52.862   874  1318 E native  : do suspend false
,09-09 13:41:52.870  4122  4157 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 13:41:52.872  4122  4149 E BooksSync: Soft error
09-09 13:41:52.872  4122  4149 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:41:52.872  4122  4149 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 13:41:52.872  4122  4149 E BooksSync: Sync error
09-09 13:41:52.872  4122  4149 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 13:41:52.872  4122  4149 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 13:41:52.872  4122  4149 I BooksSync: Finished books sync
,09-09 13:41:52.875   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128958, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 13:41:52.877   874  1318 D WifiConfigStore: No blacklist allowed without epno enabled
09-09 13:41:52.877   874   885 I ActivityManager: Killing 3485:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 13:41:52.890   874  1318 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 13:41:52.892   874  1318 E native  : do suspend true
,09-09 13:41:52.973   377  1469 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-09 13:41:52.973   377  1469 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 13:41:53.222   874  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 13:41:54.974  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:54.976  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:54.977  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:54.977  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:54.977  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b not in the list
09-09 13:41:54.978  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:54.978  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:41:54.978  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:41:54.979  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:54.980  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:54.981  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:54.985  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:54.985  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:54.986  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:54.986  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 not in the list
09-09 13:41:54.986  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:54.987  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:54.987  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:54.987  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:54.990  3806  3861 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-09 13:41:54.990  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-09 13:41:54.993  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:54.994  3806  3861 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:41:54.994  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:41:54.996  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:54.999  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-09 13:41:55.001  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-09 13:41:55.001  3806  3861 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
,09-09 13:41:55.001  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-09 13:41:55.002  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:41:55.002  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:55.002  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:55.012  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-09 13:41:55.015  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:41:55.016  3806  3861 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-09 13:41:55.018  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-09 13:41:55.019  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:55.019  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:55.020  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:55.020  3806  3861 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,09-09 13:41:55.021  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:55.021  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b not in the list
09-09 13:41:55.021  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:55.022  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:41:55.022  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:55.022  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:55.023  3806  3861 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:55.024  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:55.026  3806  3861 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:55.027  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 not in the list
,09-09 13:41:55.027  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:55.027  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 13:41:55.027  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:55.027  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:55.027  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:55.027  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:55.028  3806  3861 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:55.028  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:55.028  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:55.028  3806  3861 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79bcd2b not in the list
09-09 13:41:55.028  3806  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:55.028  3806  3861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba588 not in the list
09-09 13:41:55.028  3806  3861 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:55.028  3806  3861 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:55.029  3806  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:55.029  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:55.030  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:55.030  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:55.030  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:55.030  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:55.030  3806  3861 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:55.038  3806  4165 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 530, name: My test thread name)
,09-09 13:41:55.529  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:57.037  3806  3861 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 530
09-09 13:41:57.037  3806  3861 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 530, name: My test thread name)
,09-09 13:41:57.045  3806  4166 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 531, name: My test thread name)
,09-09 13:41:57.045  3806  4166 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 531, thread name: My test thread name)
09-09 13:41:57.046  3806  4166 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 531, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 13:41:57.051  3806  3861 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:57.060  3806  4167 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 535, name: My test thread name)
,09-09 13:41:57.061  3806  4167 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 535, thread name: My test thread name): Test exception.
,09-09 13:41:57.062  3806  4167 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 535, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-09 13:41:57.064  3806  3861 E com.test.thalitest.ThaliTestRunner: testStartStop(io.jxcore.node.ConnectivityMonitorTest)
09-09 13:41:57.064  3806  3861 E com.test.thalitest.ThaliTestRunner: Proper state of WIFI is set when switched on
09-09 13:41:57.064  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:57.064  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Proper state of WIFI is set when switched on
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testStartStop(ConnectivityMonitorTest.java:228)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.071  3806  3861 E com.test.thalit,est.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: testIsBluetoothEnabled(io.jxcore.node.ConnectivityMonitorTest)
,09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: Returns proper state of BT when switched on
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:57.071  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: Returns proper state of BT when switched on
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <false>
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectivityMonitorTest.testIsBluetoothEnabled(ConnectivityMonitorTest.java:325)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.076  3806  3861 E com.tes,t.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: testExecuteStopOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:41:57.076  3806  3861 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
,09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandler.executeCurrentOperation(StartStopOperationHandler.java:150)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandler.executeStartOperation(StartStopOperationHandler.java:62)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStopOperation(StartStopOperationHandlerTest.java:174)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.080  3806  3861 E com.test.thalite,st.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: testCheckCurrentOperationStatus(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: mCurrentOperation should be null
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-09 13:41:57.080  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should affect listening to advertisements only>
,09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: mCurrentOperation should be null
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: Expected: is null
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner:      but: was <Start operation: Should affect listening to advertisements only>
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testCheckCurrentOperationStatus(StartStopOperationHandlerTest.java:243)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:2,68)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: testExecuteStartOperation(io.jxcore.node.StartStopOperationHandlerTest)
09-09 13:41:57.082  3806  3861 E com.test.thalitest.ThaliTestRunner: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandler.executeCurrentOperation(StartStopOperationHandler.java:150)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandler.executeStartOperation(StartStopOperationHandler.java:62)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StartStopOperationHandlerTest.testExecuteStartOperation(StartStopOpera,tionHandlerTest.java:129)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:74)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$1.Receiver(RegisterExecuteUT.java:26)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.loopOnce(Native Method)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$6$1.run(jxcore.java:348)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:57.084  3806  3861 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
09-09 13:41:57.086  3806  3861 I jxcore-log: Total number of executed tests:  82
09-09 13:41:57.086  3806  3861 I jxcore-log: 
09-09 13:41:57.086  3806  3861 I jxcore-log: Number of passed tests:  77
09-09 13:41:57.086  3806  3861 I jxcore-log: 
09-09 13:41:57.087  3806  3861 I jxcore-log: Number of failed tests:  5
09-09 13:41:57.087  3806  3861 I jxcore-log: 
09-09 13:41:57.087  3806  3861 I jxcore-log: Number of ignored tests:  0
09-09 13:41:57.087  3806  3861 I jxcore-log: 
09-09 13:41:57.087  3806  3861 I jxcore-log: Total duration:  16356
09-09 13:41:57.087  3806  3861 I jxcore-log: 
09-09 13:41:57.089  3806  3861 I jxcore-log: Failed to execute UT.
09-09 13:41:57.089  3806  3861 I jxcore-log: 
09-09 13:41:57.090  3806  3861 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
09-09 13:41:57.090  3806  3861 I jxcore-log: 
09-09 13:41:57.093  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.093  3806  3861 I jxcore-log: 
09-09 13:41:57.095  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.095  3806  3861 I jxcore-log: 
09-09 13:41:57.096  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.096  3806  3861 I jxcore-log: 
09-09 13:41:57.097  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:57.097  3806  3861 I jxcore-log: 
09-09 13:41:57.099  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:57.099  3806  3861 I jxcore-log: 
09-09 13:41:57.101  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.101  3806  3861 I jxcore-log: 
09-09 13:41:57.103  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:57.103  3806  3861 I jxcore-log: 
09-09 13:41:57.104  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.104  3806  3861 I jxcore-log: 
09-09 13:41:57.105  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:57.105  3806  3861 I jxcore-log: 
09-09 13:41:57.106  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.106  3806  3861 I jxcore-log: 
09-09 13:41:57.107  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.107  3806  3861 I jxcore-log: 
09-09 13:41:57.108  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.108  3806  3861 I jxcore-log: 
09-09 13:41:57.108  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.108  3806  3861 I jxcore-log: 
09-09 13:41:57.110  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.110  3806  3861 I jxcore-log: 
09-09 13:41:57.111  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.111  3806  3861 I jxcore-log: 
,09-09 13:41:57.112  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:57.112  3806  3861 I jxcore-log: 
09-09 13:41:57.113  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.113  3806  3861 I jxcore-log: 
09-09 13:41:57.114  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.114  3806  3861 I jxcore-log: 
09-09 13:41:57.115  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.115  3806  3861 I jxcore-log: 
09-09 13:41:57.115  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.115  3806  3861 I jxcore-log: 
09-09 13:41:57.116  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.116  3806  3861 I jxcore-log: 
09-09 13:41:57.117  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.117  3806  3861 I jxcore-log: 
09-09 13:41:57.118  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.118  3806  3861 I jxcore-log: 
09-09 13:41:57.119  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.119  3806  3861 I jxcore-log: 
09-09 13:41:57.120  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.120  3806  3861 I jxcore-log: 
09-09 13:41:57.121  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.121  3806  3861 I jxcore-log: 
09-09 13:41:57.121  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 13:41:57.121  3806  3861 I jxcore-log: 
09-09 13:41:57.122  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.122  3806  3861 I jxcore-log: 
09-09 13:41:57.122  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.122  3806  3861 I jxcore-log: 
09-09 13:41:57.123  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.123  3806  3861 I jxcore-log: 
09-09 13:41:57.123  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 13:41:57.123  3806  3861 I jxcore-log: 
09-09 13:41:57.124  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.124  3806  3861 I jxcore-log: 
09-09 13:41:57.124  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:57.124  3806  3861 I jxcore-log: 
09-09 13:41:57.125  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:57.125  3806  3861 I jxcore-log: 
09-09 13:41:57.126  3806  3861 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:57.126  3806  3861 I jxcore-log: 
,09-09 13:41:57.218  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 13:41:57.225  3806  4165 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 530, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-09 13:41:57.270  1526  2993 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 13:41:57.270  1526  2993 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 13:41:57.270  1526  2993 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 13:41:57.271  1526  2993 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 13:41:57.294  3548  3548 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 13:41:57.294  3548  3548 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 13:41:57.294  3548  3548 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 13:41:57.448  4122  4145 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-09 13:41:57.811  4168  4168 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-09 13:41:57.816  4168  4168 D AndroidRuntime: CheckJNI is OFF
,09-09 13:41:57.857  2069  2663 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:41:57.860  4168  4168 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-09 13:41:57.908  4168  4168 I Radio-JNI: register_android_hardware_Radio DONE
,09-09 13:41:57.930  4168  4168 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:41:57.939   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 13:41:57.940   874   887 I ActivityManager: Killing 3806:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-09 13:41:58.055   874   897 W PackageSettings: Skipping PackageSetting{103382a com.example.hello/10273} due to missing metadata
,09-09 13:41:58.061   874  1399 I WindowState: WIN DEATH: Window{cbccb2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:41:58.062   874  1319 D WifiService: Client connection lost with reason: 4
,09-09 13:41:58.062   874  1976 D GraphicsStats: Buffer count: 2
,09-09 13:41:58.104   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 13:41:58.104   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-09 13:41:58.105   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-09 13:41:58.105   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 13:41:58.105   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.105   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.105   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:41:58.105   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-09 13:41:58.105   874   887 I ActivityManager:   Force finishing activity ActivityRecord{c2888fa u0 com.test.thalitest/.MainActivity t4}
,09-09 13:41:58.108   874   897 I art     : Starting a blocking GC Explicit
,09-09 13:41:58.118   874  1993 W ActivityManager: Spurious death for ProcessRecord{9e0b672 0:com.test.thalitest/u0a0}, curProc for 3806: null
,09-09 13:41:58.167   874   897 I art     : Explicit concurrent mark sweep GC freed 32932(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.125ms total 59.032ms
,09-09 13:41:58.188   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-09 13:41:58.191  4168  4168 I art     : System.exit called, status: 0
09-09 13:41:58.191  4168  4168 I AndroidRuntime: VM exiting with result code 0.
,09-09 13:41:58.198   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-09 13:41:58.214   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-09 13:41:58.218  2069  2285 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 13:41:58.223   874  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 13:41:58.224  1876  1876 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 13:41:58.219  3682  3682 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-09 13:41:58.239   874   884 I ActivityManager: Start proc 4184:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-09 13:41:58.246  1876  4182 I Keyboard.Facilitator.DecoderInitializer: run()
,09-09 13:41:58.252  1931  1931 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:58.260  1876  4182 I Decoder : createOrResetDecoder
,09-09 13:41:58.291  1526  1526 I ConfigService: onCreate
,09-09 13:41:58.300   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 13:41:58.309  1876  4182 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-09 13:41:58.313  4184  4184 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-09 13:41:58.323   874  1399 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3806 uid 10000
,09-09 13:41:58.324  1876  1876 I Keyboard.Facilitator: onFinishInput()
,09-09 13:41:58.334  1948  2043 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-09 13:41:58.335   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-09 13:41:58.335   874   886 E PackageManager: Failed to write settings, restoring backup
09-09 13:41:58.335   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 13:41:58.335   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 13:41:58.335   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 13:41:58.335   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 13:41:58.335   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 13:41:58.335   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.335   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.335   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:41:58.343   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-09 13:41:58.343   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 13:41:58.343   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.343   874   887 E DropBoxManagerService: 	... 13 more
,09-09 13:41:58.348   874  1993 I ActivityManager: Start proc 4198:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
,09-09 13:41:58.349  1948  2043 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 13:41:58.349  1948  2043 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1948
09-09 13:41:58.349  1948  2043 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.349  1948  2043 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:41:58.351   874  4205 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:41:58.351   874  4205 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.351   874  4205 E DropBoxManagerService: 	... 5 more
,09-09 13:41:58.351   874  1976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:41:58.354  1948  2043 I Process : Sending signal. PID: 1948 SIG: 9
,09-09 13:41:58.384  4184  4184 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-09 13:41:58.391  1876  4182 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-09 13:41:58.393  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 13:41:58.393  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-09 13:41:58.395  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 13:41:58.395  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-09 13:41:58.397  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-09 13:41:58.397  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-09 13:41:58.400  1876  4182 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-09 13:41:58.400  1876  4182 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 13:41:58.400  1876  4182 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-09 13:41:58.401  1876  4182 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 13:41:58.401  1876  4182 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 13:41:58.401  1876  4182 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-09 13:41:58.414   874  1955 I WindowState: WIN DEATH: Window{6779929 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-09 13:41:58.414   874  1399 D GraphicsStats: Buffer count: 1
,09-09 13:41:58.415   874  1947 I ActivityManager: Start proc 4215:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-09 13:41:58.438   874  1991 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1948) has died
,09-09 13:41:58.438  4184  4228 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-09 13:41:58.438   874  1991 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-09 13:41:58.439   874  1991 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 13:41:58.455  4184  4204 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.455  4184  4204 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.457  4184  4204 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:41:58.460   874   884 I ActivityManager: Start proc 4229:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:41:58.477  4215  4215 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-09 13:41:58.500  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 13:41:58.501  1526  1526 D AndroidRuntime: Shutting down VM
09-09 13:41:58.502  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:41:58.502  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
09-09 13:41:58.502  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 13:41:58.502  1526  1526 E AndroidRuntime: 	... 8 more
,09-09 13:41:58.510   874  4244 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:41:58.510   874  4244 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.510   874  4244 E DropBoxManagerService: 	... 5 more
,09-09 13:41:58.511  1526  1526 I Process : Sending signal. PID: 1526 SIG: 9
,09-09 13:41:58.515  4229  4229 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:58.515  4229  4229 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:41:58.515  4229  4229 D AndroidRuntime: Shutting down VM
,09-09 13:41:58.521  4229  4229 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:41:58.521  4229  4229 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4229
09-09 13:41:58.521  4229  4229 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:41:58.521  4229  4229 E AndroidRuntime: 	... 10 more
,09-09 13:41:58.522   874  1976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:41:58.523  4229  4229 I Process : Sending signal. PID: 4229 SIG: 9
09-09 13:41:58.524   874  4247 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:41:58.524   874  4247 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.524   874  4247 E DropBoxManagerService: 	... 5 more
,09-09 13:41:58.539   874  1987 I ActivityManager: Killing 3740:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-09 13:41:58.564  4184  4204 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-09 13:41:58.568  4184  4228 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.568  4184  4228 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-09 13:41:58.569  4184  4228 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 13:41:58.569  4184  4228 E AndroidRuntime: Process: android.process.acore, PID: 4184
09-09 13:41:58.569  4184  4228 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.569  4184  4228 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 13:41:58.570  4184  4204 I Process : Sending signal. PID: 4184 SIG: 9
,09-09 13:41:58.572   874  1319 D WifiService: Client connection lost with reason: 4
09-09 13:41:58.573  1746  4245 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@c262222
,09-09 13:41:58.586   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4229) has died
,09-09 13:41:58.587   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-09 13:41:58.594   874  1947 I ActivityManager: Process com.google.process.gapps (pid 1526) has died
,09-09 13:41:58.594   874  1947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-09 13:41:58.595   874  1947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 10999ms
09-09 13:41:58.595   874  1947 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,09-09 13:41:58.601  1746  1746 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-09 13:41:58.621   874  1993 I ActivityManager: Start proc 4249:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-09 13:41:58.639   874   887 I ActivityManager: Start proc 4260:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-09 13:41:58.640   874  1540 I ActivityManager: Process android.process.acore (pid 4184) has died
09-09 13:41:58.641   874  1540 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30953ms
,09-09 13:41:58.648   874  4268 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:41:58.648   874  4268 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.648   874  4268 E DropBoxManagerService: 	... 5 more
,09-09 13:41:58.656  3012  3012 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,09-09 13:41:58.663  4249  4249 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-09 13:41:58.669  4249  4249 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-09 13:41:58.671  4249  4249 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:58.671  4249  4249 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-09 13:41:58.672  4249  4249 D AndroidRuntime: Shutting down VM
,09-09 13:41:58.672  4249  4249 E AndroidRuntime: FATAL EXCEPTION: main
09-09 13:41:58.672  4249  4249 E AndroidRuntime: Process: com.google.process.gapps, PID: 4249
09-09 13:41:58.672  4249  4249 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 13:41:58.672  4249  4249 E AndroidRuntime: 	... 10 more
,09-09 13:41:58.676  4249  4249 I Process : Sending signal. PID: 4249 SIG: 9
,09-09 13:41:58.680   874  4275 E DropBoxManagerService: Can't write: system_app_crash
09-09 13:41:58.680   874  4275 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 13:41:58.680   874  4275 E DropBoxManagerService: 	... 5 more
,09-09 13:41:58.686  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-09 13:41:58.686  1746  1746 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-09 13:41:58.690  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-09 13:41:58.690  1746  1746 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-09 13:41:58.691   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
