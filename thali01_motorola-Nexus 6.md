#### Test 79751015f24a8ad_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 17:14:30.378   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 17:14:31.061  3815  3815 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 17:14:31.066  3815  3815 D AndroidRuntime: CheckJNI is OFF
08-12 17:14:31.109  3815  3815 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 17:14:31.159  3815  3815 I Radio-JNI: register_android_hardware_Radio DONE
08-12 17:14:31.181  3815  3815 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 17:14:31.187   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:14:31.209  2027  2379 W SearchService: Abort, client detached.
08-12 17:14:31.221  3815  3815 D AndroidRuntime: Shutting down VM
08-12 17:14:31.223  2027  2298 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fd3f6f0
08-12 17:14:31.223  2027  2311 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 17:14:31.226  2027  2027 I HotwordDetector: Closing mic
08-12 17:14:31.240   873  1375 I ActivityManager: Start proc 3824:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 17:14:31.277   376  2319 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 17:14:31.278   376  2319 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 17:14:31.288   376  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 17:14:31.290  2027  2302 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 17:14:31.291  2027  2310 I MicroRecognitionRnrImpl: Detection finished
08-12 17:14:31.328  3824  3824 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 17:14:31.351  3824  3824 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 17:14:31.358  3824  3824 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9215-9217)
08-12 17:14:31.358  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:14:31.369  3824  3824 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {55185b4}
08-12 17:14:31.370  3824  3824 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:14:31.371  3824  3824 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:14:31.377  3824  3824 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 17:14:31.378  3824  3824 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 17:14:31.406  3824  3824 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 17:14:31.416  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:14:31.416  3824  3824 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:14:31.416  3824  3824 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 17:14:31.416  3824  3824 I Adreno  : Build Date                       : 10/20/15
08-12 17:14:31.416  3824  3824 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 17:14:31.416  3824  3824 I Adreno  : Local Branch                     : M14
08-12 17:14:31.416  3824  3824 I Adreno  : Remote Branch                    : 
08-12 17:14:31.416  3824  3824 I Adreno  : Remote Branch                    : 
08-12 17:14:31.416  3824  3824 I Adreno  : Reconstruct Branch               : 
,08-12 17:14:31.455   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f3596d5:true
08-12 17:14:31.494  3824  3824 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 17:14:31.505  3824  3824 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-12 17:14:31.565  3824  3863 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 17:14:31.572  3824  3850 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 17:14:31.604  3824  3863 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:14:31.682   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +457ms
08-12 17:14:31.688  1872  1872 I Keyboard.Facilitator: onFinishInput()
08-12 17:14:31.755  3824  3824 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3824
08-12 17:14:31.889  3824  3824 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-12 17:14:32.029   873  2016 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #17
08-12 17:14:32.071   873  2016 I ActivityManager: Killing 3209:com.google.android.gm/u0a78 (adj 15): empty #18
08-12 17:14:32.091  3824  3866 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700005584
08-12 17:14:32.097  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:14:32.097  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:14:32.097  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:14:32.097  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:14:32.097  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 17:14:32.098  3824  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af0705b added. We now have 1 listener(s)
08-12 17:14:32.101  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-12 17:14:32.102  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 17:14:32.102  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:14:32.102  3824  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 17:14:32.105  3824  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43bb737 added. We now have 1 listener(s)
08-12 17:14:32.106  3824  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 17:14:32.112   873  1302 D WifiService: New client listening to asynchronous messages
08-12 17:14:32.114  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 17:14:32.114  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:14:32.114  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:14:32.114  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 17:14:32.115  3824  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 17:14:32.118  3824  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 17:14:32.118  3824  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-12 17:14:32.123  3824  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:14:32.123  3824  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:14:32.123  3824  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:14:32.123  3824  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 17:14:32.125  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:14:32.127  3824  3866 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 17:14:32.304  3824  3824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:14:32.311  3824  3824 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:14:33.184  3824  3875 W jxcore-log: Initializing JXcore engine
08-12 17:14:33.184  3824  3875 W jxcore-log: JXcore engine is ready
,08-12 17:14:33.244  3875  3875 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 17:14:33.244  3875  3875 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11741]" dev="sockfs" ino=11741 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 17:14:33.244  3875  3875 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 17:14:33.244  3875  3875 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25991]" dev="sockfs" ino=25991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 17:14:33.266  3824  3875 W jxcore-log: Starting JXcore engine
,08-12 17:14:33.364  3824  3875 W jxcore-log: Platform android
08-12 17:14:33.364  3824  3875 W jxcore-log: 
,08-12 17:14:33.364  3824  3875 W jxcore-log: Process ARCH arm
08-12 17:14:33.364  3824  3875 W jxcore-log: 
,08-12 17:14:33.588  3824  3875 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:14:33.588  3824  3875 I jxcore-log: 
,08-12 17:14:33.588  3824  3875 W jxcore-log: JXcore engine is started
,08-12 17:14:33.592  3824  3866 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 17:14:33.596  3824  3824 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 17:14:35.020   873  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 17:14:40.043  3602  3882 V KeepSync: Connecting to GoogleApiClient
,08-12 17:14:40.044   873  1992 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 17:14:40.084  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:14:40.087  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:14:40.111  1524  2191 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 17:14:40.112  1524  2191 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 17:14:40.112  1524  2191 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:14:40.112  1524  2191 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:14:40.129  1750  3883 V BaseAuthAsyncOperation: access token request failed
,08-12 17:14:40.130  3602  3882 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 17:14:40.186  1524  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 17:14:40.186  1524  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 17:14:40.187  1524  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:14:40.187  1524  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-12 17:14:40.224  3602  3882 E KeepSync: IOException
08-12 17:14:40.224  3602  3882 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 17:14:40.224  3602  3882 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:14:40.224  3602  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 17:14:40.224  3602  3882 E KeepSync: 	... 10 more
,08-12 17:14:40.224  3602  3882 W KeepSync: Sync result 2
,08-12 17:14:40.230   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127728, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:14:41.481  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:14:41.508  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 17:14:41.508  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 17:14:41.508  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:14:41.508  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:14:41.525  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 17:14:41.525  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 17:14:41.525  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-12 17:14:49.651  3824  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:14:49.651  3824  3875 I jxcore-log: 
,08-12 17:14:49.653  3824  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:14:49.653  3824  3875 I jxcore-log: 
,08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:14:49.658  3824  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:14:49.660  3824  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 17:14:49.662  3824  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:14:49.662  3824  3875 I jxcore-log: 
,08-12 17:14:49.664  3824  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:14:49.664  3824  3875 I jxcore-log: 
,08-12 17:14:50.006  3824  3875 I jxcore-log: Unit Test app is loaded
08-12 17:14:50.006  3824  3875 I jxcore-log: 
,08-12 17:14:50.013  3824  3875 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:14:50.013  3824  3875 I jxcore-log: 
,08-12 17:14:50.023  3824  3875 I jxcore-log: My device name is: motorola-Nexus 6
08-12 17:14:50.023  3824  3875 I jxcore-log: 
08-12 17:14:50.023  3824  3824 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 17:14:50.031  3824  3875 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 17:14:50.031  3824  3875 I jxcore-log: 
,08-12 17:14:52.306  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 17:14:52.306  3824  3875 I jxcore-log: 
,08-12 17:14:52.899  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 17:14:52.899  3824  3875 I jxcore-log: 
,08-12 17:14:52.923  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 17:14:52.923  3824  3875 I jxcore-log: 
,08-12 17:14:54.264  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 17:14:54.264  3824  3875 I jxcore-log: 
,08-12 17:14:54.490  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 17:14:54.490  3824  3875 I jxcore-log: 
,08-12 17:14:54.495  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 17:14:54.495  3824  3875 I jxcore-log: 
,08-12 17:14:54.501  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 17:14:54.501  3824  3875 I jxcore-log: 
,08-12 17:14:54.518  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 17:14:54.518  3824  3875 I jxcore-log: 
,08-12 17:14:54.523  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 17:14:54.523  3824  3875 I jxcore-log: 
,08-12 17:14:55.206  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 17:14:55.206  3824  3875 I jxcore-log: 
,08-12 17:14:55.228  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 17:14:55.228  3824  3875 I jxcore-log: 
,08-12 17:14:55.245  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 17:14:55.245  3824  3875 I jxcore-log: 
,08-12 17:14:55.256  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 17:14:55.256  3824  3875 I jxcore-log: 
,08-12 17:14:55.313  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 17:14:55.313  3824  3875 I jxcore-log: 
,08-12 17:14:55.369  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 17:14:55.369  3824  3875 I jxcore-log: 
,08-12 17:14:55.378  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 17:14:55.378  3824  3875 I jxcore-log: 
,08-12 17:14:55.542  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 17:14:55.542  3824  3875 I jxcore-log: 
,08-12 17:14:55.570  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 17:14:55.570  3824  3875 I jxcore-log: 
,08-12 17:14:55.576  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 17:14:55.576  3824  3875 I jxcore-log: 
,08-12 17:14:55.583  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 17:14:55.583  3824  3875 I jxcore-log: 
,08-12 17:14:55.601  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 17:14:55.601  3824  3875 I jxcore-log: 
,08-12 17:14:55.685  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 17:14:55.685  3824  3875 I jxcore-log: 
,08-12 17:14:55.698  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 17:14:55.698  3824  3875 I jxcore-log: 
,08-12 17:14:55.726  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 17:14:55.726  3824  3875 I jxcore-log: 
,08-12 17:14:55.739  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 17:14:55.739  3824  3875 I jxcore-log: 
,08-12 17:14:55.758  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 17:14:55.758  3824  3875 I jxcore-log: 
,08-12 17:14:55.795  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 17:14:55.795  3824  3875 I jxcore-log: 
,08-12 17:14:55.801  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 17:14:55.801  3824  3875 I jxcore-log: 
,08-12 17:14:56.009  3824  3875 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 17:14:56.009  3824  3875 I jxcore-log: 
,08-12 17:14:56.022  3824  3875 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 17:14:56.023  3824  3875 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 17:14:56.023  3824  3875 I jxcore-log: 
,08-12 17:14:56.695  1474  1474 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,08-12 17:15:01.071   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 17:15:02.100   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 17:15:02.118  1872  1872 I Keyboard.Facilitator: onFinishInput()
,08-12 17:15:02.124   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 17:15:02.124   873   893 I Adreno  : Build Date                       : 10/20/15
08-12 17:15:02.124   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 17:15:02.124   873   893 I Adreno  : Local Branch                     : M14
08-12 17:15:02.124   873   893 I Adreno  : Remote Branch                    : 
08-12 17:15:02.124   873   893 I Adreno  : Remote Branch                    : 
08-12 17:15:02.124   873   893 I Adreno  : Reconstruct Branch               : 
,08-12 17:15:02.162   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (461 us)
,08-12 17:15:02.840  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 17:15:02.840  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 17:15:02.873   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 17:15:02.874  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4431caa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@da5321, 16908290=android.view.AbsSavedState$1@da5321}, android:focusedViewId=100}]}]
,08-12 17:15:02.874  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-12 17:15:02.874  3824  3824 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 17:15:02.874  3824  3824 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 17:15:02.882   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 17:15:02.887   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 17:15:02.893   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-12 17:15:02.893   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 17:15:02.932   873   882 I art     : Background partial concurrent mark sweep GC freed 38224(2MB) AllocSpace objects, 15(336KB) LOS objects, 33% free, 29MB/43MB, paused 1.185ms total 117.305ms
,08-12 17:15:03.119   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 17:15:03.124   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 17:15:03.130   873  1330 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-12 17:15:03.133   873   893 I DreamManagerService: Entering dreamland.
,08-12 17:15:03.134   873   893 I PowerManagerService: Dozing...
,08-12 17:15:03.136   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 17:15:03.237   376  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 17:15:03.237   376  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 17:15:03.255   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 17:15:03.266  1932  3892 D NfcService: Discovery configuration equal, not updating.
,08-12 17:15:03.278   873  1301 E native  : do suspend false
,08-12 17:15:03.307   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 17:15:03.330   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 17:15:03.342   873  1301 E native  : do suspend true
,08-12 17:15:03.361   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-12 17:15:03.361   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 17:15:03.762   873  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 17:15:04.913  1524  2204 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 17:15:07.442  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:07.452  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:07.455  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:07.498  1524  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 17:15:07.498  1524  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 17:15:07.498  1524  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:15:07.498  1524  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:07.535  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 17:15:07.536  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 17:15:07.537  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 17:15:09.901  2192  2659 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 17:15:12.381  3772  3897 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 17:15:12.399  3772  3898 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 17:15:12.431  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 17:15:12.431  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 17:15:12.431  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:15:12.431  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:12.475  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 17:15:12.475  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 17:15:12.475  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:15:12.476  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:12.495  3772  3898 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 17:15:12.496  3772  3897 E BooksSync: Soft error
08-12 17:15:12.496  3772  3897 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:15:12.496  3772  3897 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 17:15:12.496  3772  3897 E BooksSync: Sync error
08-12 17:15:12.496  3772  3897 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:15:12.496  3772  3897 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 17:15:12.496  3772  3897 I BooksSync: Finished books sync
,08-12 17:15:12.500   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160056, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:15:15.037   873  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 17:15:33.588  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:33.770  1524  3900 I VacuumService: Vacuum at: now=1471014933770 tag=VacuumService
,08-12 17:15:33.855  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:33.891  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:33.895  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:34.034  1524  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 17:15:34.034  1524  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 17:15:34.034  1524  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:15:34.034  1524  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:34.060  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 17:15:34.060  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 17:15:34.062  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 17:15:34.162  1524  3901 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 17:15:34.166  1524  3901 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 17:15:34.204  1524  3901 W Uploader:  no longer exists, so no auth token.
,08-12 17:15:35.043  1524  3901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 17:15:35.043  1524  3901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 17:15:35.043  1524  3901 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:15:35.043  1524  3901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:35.058  1524  3901 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 17:15:35.058  1524  3901 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 17:15:35.058  1524  3901 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 17:15:35.416  1524  3901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-12 17:15:35.416  1524  3901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 17:15:35.416  1524  3901 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:15:35.416  1524  3901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:35.436  1524  3901 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 17:15:35.436  1524  3901 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 17:15:35.436  1524  3901 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 17:15:36.017  1524  3901 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-12 17:15:36.017  1524  3901 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 17:15:36.017  1524  3901 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:15:36.019  1524  3901 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:36.039  1524  3901 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 17:15:36.039  1524  3901 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 17:15:36.039  1524  3901 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 17:15:42.727  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:42.729  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:42.772  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 17:15:42.772  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 17:15:42.772  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:15:42.773  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:42.794  3544  3914 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 17:15:42.794  3544  3914 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jdm.a(PG:82)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jcs.o(PG:406)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jcn.a(PG:1379)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jcs.i(PG:143)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at blb.a(PG:3937)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at czp.a(PG:18188)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at czp.a(PG:9081)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at czq.run(PG:1686)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:15:42.794  3544  3914 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jdj.a(PG:4091)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jdj.a(PG:1125)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jdm.a(PG:77)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	... 12 more
08-12 17:15:42.794  3544  3914 E HttpOperation: Caused by: faj: BadAuthentication
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at fal.a(PG:38)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	at jdj.a(PG:4089)
08-12 17:15:42.794  3544  3914 E HttpOperation: 	... 14 more
,08-12 17:15:42.851  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 17:15:42.852  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 17:15:42.852  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:15:42.852  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:42.877  3544  3914 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 17:15:42.877  3544  3914 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jdm.a(PG:82)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jcs.o(PG:406)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jcn.a(PG:1379)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jcs.i(PG:143)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at hec.a(PG:42)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at hee.a(PG:102)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at czr.a(PG:65)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at kka.a(PG:108)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at czp.a(PG:19176)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at czp.a(PG:9081)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at czq.run(PG:1686)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:15:42.877  3544  3914 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jdj.a(PG:4091)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jdj.a(PG:1125)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jdm.a(PG:77)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	... 15 more
08-12 17:15:42.877  3544  3914 E HttpOperation: Caused by: faj: BadAuthentication
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at fal.a(PG:38)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	at jdj.a(PG:4089)
08-12 17:15:42.877  3544  3914 E HttpOperation: 	... 17 more
08-12 17:15:42.878  3544  3914 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 17:15:42.878  3544  3914 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at hec.a(PG:42)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at hee.a(PG:102)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at czr.a(PG:65)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at kka.a(PG:108)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	... 15 more
08-12 17:15:42.878  3544  3914 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at fal.a(PG:38)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 17:15:42.878  3544  3914 E ExperimentLoader: 	... 17 more
,08-12 17:15:43.073   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 162730, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:15:54.431  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:54.445  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:54.454  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:15:54.540  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 17:15:54.540  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 17:15:54.541  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:15:54.541  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:15:54.612  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 17:15:54.613  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 17:15:54.616  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 17:16:02.141  1872  1980 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 17:16:02.141  1872  1980 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 17:16:02.179  1524  1524 I ConfigService: onCreate
,08-12 17:16:07.254  1524  1524 I ConfigService: onDestroy
,08-12 17:16:10.792   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 17:16:16.591   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=224450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 17:16:43.583  3602  3920 V KeepSync: Connecting to GoogleApiClient
,08-12 17:16:43.585   873  1964 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 17:16:43.673  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:16:43.677  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:16:43.707  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 17:16:43.707  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 17:16:43.707  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:16:43.707  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:16:43.722  1750  3921 V BaseAuthAsyncOperation: access token request failed
,08-12 17:16:43.722  3602  3920 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 17:16:43.769  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 17:16:43.769  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 17:16:43.769  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:16:43.769  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:16:43.782  3602  3920 E KeepSync: IOException
08-12 17:16:43.782  3602  3920 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 17:16:43.782  3602  3920 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:16:43.782  3602  3920 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 17:16:43.782  3602  3920 E KeepSync: 	... 10 more
08-12 17:16:43.782  3602  3920 W KeepSync: Sync result 2
,08-12 17:16:43.794   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 251198, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:16:50.751   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 17:16:57.044   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 17:17:18.319  3772  3925 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 17:17:18.347  3772  3928 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 17:17:18.361  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:18.364  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:18.409  1524  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 17:17:18.410  1524  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 17:17:18.410  1524  2081 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-12 17:17:18.411  1524  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:17:18.447  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:18.449  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:18.480  1524  2884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 17:17:18.480  1524  2884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 17:17:18.480  1524  2884 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:17:18.480  1524  2884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:17:18.502  3772  3928 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 17:17:18.503  3772  3925 E BooksSync: Soft error
08-12 17:17:18.503  3772  3925 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:17:18.503  3772  3925 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 17:17:18.505  3772  3925 E BooksSync: Sync error
08-12 17:17:18.505  3772  3925 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:17:18.505  3772  3925 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 17:17:18.505  3772  3925 I BooksSync: Finished books sync
,08-12 17:17:18.513   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:17:31.285   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=299144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 17:17:37.552   873  1910 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 17:17:54.660  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:54.661  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:17:54.692  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 17:17:54.692  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 17:17:54.692  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:17:54.692  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:17:54.713  3544  3939 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 17:17:54.713  3544  3939 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jdm.a(PG:82)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jcs.o(PG:406)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jcn.a(PG:1379)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jcs.i(PG:143)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at blb.a(PG:3937)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at czp.a(PG:18188)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at czp.a(PG:9081)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at czq.run(PG:1686)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:17:54.713  3544  3939 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jdj.a(PG:4091)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jdj.a(PG:1125)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jdm.a(PG:77)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	... 12 more
08-12 17:17:54.713  3544  3939 E HttpOperation: Caused by: faj: BadAuthentication
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at fal.a(PG:38)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	at jdj.a(PG:4089)
08-12 17:17:54.713  3544  3939 E HttpOperation: 	... 14 more
,08-12 17:17:54.800  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 17:17:54.800  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 17:17:54.800  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:17:54.800  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:17:54.827  3544  3939 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 17:17:54.827  3544  3939 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jdm.a(PG:82)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jcs.o(PG:406)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jcn.a(PG:1379)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jcs.i(PG:143)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at hec.a(PG:42)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at hee.a(PG:102)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at czr.a(PG:65)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at kka.a(PG:108)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at czp.a(PG:19176)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at czp.a(PG:9081)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at czq.run(PG:1686)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:17:54.827  3544  3939 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jdj.a(PG:4091)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jdj.a(PG:1125)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jdm.a(PG:77)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	... 15 more
08-12 17:17:54.827  3544  3939 E HttpOperation: Caused by: faj: BadAuthentication
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at fal.a(PG:38)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	at jdj.a(PG:4089)
08-12 17:17:54.827  3544  3939 E HttpOperation: 	... 17 more
08-12 17:17:54.828  3544  3939 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 17:17:54.828  3544  3939 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at hec.a(PG:42)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at hee.a(PG:102)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at czr.a(PG:65)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at kka.a(PG:108)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	... 15 more
08-12 17:17:54.828  3544  3939 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at fal.a(PG:38)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 17:17:54.828  3544  3939 E ExperimentLoader: 	... 17 more
,08-12 17:17:54.955   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 322257, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,08-12 17:18:15.317  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:18:15.327  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:18:15.331  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:18:15.376  1524  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 17:18:15.377  1524  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 17:18:15.377  1524  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:18:15.378  1524  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:18:15.415  1524  1536 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 17:18:15.415  1524  1536 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 17:18:15.424  3506  3535 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 17:18:15.424  3506  3535 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 17:18:15.424  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 17:18:15.424  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 17:18:15.424  3506  3535 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 17:18:15.424  3506  3535 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 17:18:15.424  3506  3535 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 17:18:23.178  3824  3875 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 17:18:23.178  3824  3875 I jxcore-log: 
,08-12 17:18:23.794  3945  3945 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 17:18:23.800  3945  3945 D AndroidRuntime: CheckJNI is OFF
,08-12 17:18:23.827  3824  3875 I jxcore-log: TAP version 13
08-12 17:18:23.827  3824  3875 I jxcore-log: 
,08-12 17:18:23.833  3824  3875 I jxcore-log: # setup
08-12 17:18:23.833  3824  3875 I jxcore-log: 
,08-12 17:18:23.848  3945  3945 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 17:18:23.892  3945  3945 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 17:18:23.913  3945  3945 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:18:23.922   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-12 17:18:23.923   873   886 I ActivityManager: Killing 3824:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 17:18:24.004   873   896 W PackageSettings: Skipping PackageSetting{789c6b3 com.example.hello/10273} due to missing metadata
,08-12 17:18:24.038   873   896 I art     : Starting a blocking GC Explicit
,08-12 17:18:24.049   873  1992 I WindowState: WIN DEATH: Window{bcadf45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:18:24.050   873   884 D GraphicsStats: Buffer count: 2
08-12 17:18:24.050   873  1302 D WifiService: Client connection lost with reason: 4
,08-12 17:18:24.093   873   896 I art     : Explicit concurrent mark sweep GC freed 29893(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 28MB/43MB, paused 1.230ms total 53.009ms
,08-12 17:18:24.101   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 17:18:24.101   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 17:18:24.101   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-12 17:18:24.101   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 17:18:24.101   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.101   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.101   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:18:24.101   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 17:18:24.102   873   886 I ActivityManager:   Force finishing activity ActivityRecord{bc1b9e2 u0 com.test.thalitest/.MainActivity t2}
,08-12 17:18:24.106   873  1964 W ActivityManager: Spurious death for ProcessRecord{31c7ee 0:com.test.thalitest/u0a0}, curProc for 3824: null
,08-12 17:18:24.117   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 17:18:24.119  3945  3945 I art     : System.exit called, status: 0
08-12 17:18:24.120  3945  3945 I AndroidRuntime: VM exiting with result code 0.
,08-12 17:18:24.122   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 17:18:24.129   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 17:18:24.134   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 17:18:24.135  2589  2589 D BluetoothMapAppObserver: onReceive
08-12 17:18:24.135  2589  2589 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-12 17:18:24.143  3659  3659 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-12 17:18:24.132  1872  1872 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 17:18:24.152  2192  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:18:24.168  1945  1945 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED,
,08-12 17:18:24.204  1872  3957 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 17:18:24.213   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 17:18:24.221  3488  3959 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 17:18:24.223  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-12 17:18:24.223  1524  1524 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-12 17:18:24.225  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
08-12 17:18:24.225  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
08-12 17:18:24.225  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 17:18:24.225  1524  1524 E AndroidRuntime: 	... 8 more
,08-12 17:18:24.228   873  3963 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.228   873  3963 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.228   873  3963 E DropBoxManagerService: 	... 5 more
,08-12 17:18:24.230  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
,08-12 17:18:24.235  1959  2049 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 17:18:24.237  1872  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-12 17:18:24.237  1872  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-12 17:18:24.237  1872  3957 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-12 17:18:24.247   873  1997 I ActivityManager: Start proc 3964:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-12 17:18:24.248  1959  2049 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 17:18:24.248  1959  2049 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1959
08-12 17:18:24.248  1959  2049 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.248  1959  2049 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 17:18:24.249  1872  3957 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-12 17:18:24.249   873  3136 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 17:18:24.250   873  3970 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.250   873  3970 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.250   873  3970 E DropBoxManagerService: 	... 5 more
,08-12 17:18:24.256  1959  2049 I Process : Sending signal. PID: 1959 SIG: 9
,08-12 17:18:24.268  1872  3957 I Decoder : createOrResetDecoder
,08-12 17:18:24.275   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 17:18:24.276   873   885 E PackageManager: Failed to write settings, restoring backup
08-12 17:18:24.276   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 17:18:24.276   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 17:18:24.276   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 17:18:24.276   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 17:18:24.276   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 17:18:24.276   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.276   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.276   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 17:18:24.272  3488  3503 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj4B056B92B) - 
,08-12 17:18:24.279   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-12 17:18:24.279   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 17:18:24.279   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.279   873   886 E DropBoxManagerService: 	... 13 more
,08-12 17:18:24.294  3488  3959 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 17:18:24.295  3488  3959 I Process : Sending signal. PID: 3488 SIG: 9
,08-12 17:18:24.309   278   278 E lowmemorykiller: Error writing /proc/3488/oom_score_adj; errno=22
,08-12 17:18:24.318   873  1302 D WifiService: Client connection lost with reason: 4
,08-12 17:18:24.323   873  1375 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
,08-12 17:18:24.324   873  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-12 17:18:24.324   873  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
08-12 17:18:24.324   873  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 20999ms
08-12 17:18:24.324   873  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,08-12 17:18:24.326   278   278 E lowmemorykiller: Error writing /proc/3488/oom_score_adj; errno=22
,08-12 17:18:24.328   873  1997 D GraphicsStats: Buffer count: 1
,08-12 17:18:24.337  1750  1750 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-12 17:18:24.347   873  2015 I ActivityManager: Start proc 3980:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
,08-12 17:18:24.348   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1959) has died
08-12 17:18:24.348   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40976ms
,08-12 17:18:24.394   873   883 I ActivityManager: Process android.process.acore (pid 3488) has died
,08-12 17:18:24.394   873   883 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-12 17:18:24.404  3980  3980 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 17:18:24.418  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 17:18:24.418  1750  1750 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 17:18:24.416  3980  3980 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 17:18:24.419  3980  3980 I MultiDex: install
08-12 17:18:24.420  3980  3980 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 17:18:24.426  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 17:18:24.426  1750  1750 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 17:18:24.431  3980  3980 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-12 17:18:24.437  1750  3996 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 17:18:24.441  3980  3980 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-12 17:18:24.443  3980  3980 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:18:24.443  3980  3980 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 17:18:24.444  3980  3980 D AndroidRuntime: Shutting down VM
08-12 17:18:24.444  3980  3980 E AndroidRuntime: FATAL EXCEPTION: main
08-12 17:18:24.444  3980  3980 E AndroidRuntime: Process: com.google.process.gapps, PID: 3980
08-12 17:18:24.444  3980  3980 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 17,:18:24.444  3980  3980 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 17:18:24.444  3980  3980 E AndroidRuntime: 	... 10 more
08-12 17:18:24.448   873  2015 I ActivityManager: Start proc 3998:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-12 17:18:24.451   873  4003 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.451   873  4003 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.451   873  4003 E DropBoxManagerService: 	... 5 more
08-12 17:18:24.452  2027  3995 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 17:18:24.454  3980  3980 I Process : Sending signal. PID: 3980 SIG: 9
08-12 17:18:24.465  1750  3996 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 17:18:24.465  1750  3996 E AndroidRuntime: Process: com.google.android.gms, PID: 1750
08-12 17:18:24.465  1750  3996 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 17:18:24.465  1750  3996 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-12 17:18:24.466   873  3136 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-12 17:18:24.467   873  3136 I ActivityManager: Killing 1750:com.google.android.gms/u0a11 (adj 5): crash
08-12 17:18:24.469   873  4009 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.469   873  4009 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.469   873  4009 E DropBoxManagerService: 	... 5 more
,08-12 17:18:24.493  2027  3995 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 17:18:24.530   873  1375 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@fe8f1a)
,08-12 17:18:24.531   873  3136 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-12 17:18:24.533   873  1303 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:18:24.540   873  1303 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 17:18:24.542   873  1992 I ActivityManager: Process com.google.process.gapps (pid 3980) has died
,08-12 17:18:24.544   873  1992 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{da89ab7 u0 com.google.android.gms/.gcm.GcmService}
,08-12 17:18:24.545   873  1992 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b7e81dd u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,08-12 17:18:24.554   873  1992 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a28db42 u0 com.google.android.gms/.gcm.http.GoogleHttpService}
,08-12 17:18:24.554   873  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-12 17:18:24.555   873  3135 W ActivityManager: Unable to launch app com.google.android.gsf/10011 for provider com.google.android.gsf.gservices: launching app became null
,08-12 17:18:24.557   873  1696 W ActivityManager: Spurious death for ProcessRecord{d52a4c6 0:com.google.android.gms/u0a11}, curProc for 1750: null
,08-12 17:18:24.577  2027  3995 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-12 17:18:24.578  2027  3995 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 17:18:24.578  2027  3995 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2027
08-12 17:18:24.578  2027  3995 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.578  2027  3995 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:18:24.579   873  3135 I ActivityManager: Start proc 4013:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
08-12 17:18:24.581  2027  3995 I Process : Sending signal. PID: 2027 SIG: 9
08-12 17:18:24.588   873  4019 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.588   873  4019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS ,(Read-only file system)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.588   873  4019 E DropBoxManagerService: 	... 5 more
,08-12 17:18:24.602  3998  3998 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:18:24.602  3998  3998 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 17:18:24.603  3998  3998 D AndroidRuntime: Shutting down VM
,08-12 17:18:24.609  3998  3998 E AndroidRuntime: FATAL EXCEPTION: main
08-12 17:18:24.609  3998  3998 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3998
08-12 17:18:24.609  3998  3998 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 17:18:24.609  3998  3998 E AndroidRuntime: 	... 10 more
,08-12 17:18:24.610   873  2015 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 17:18:24.610   873  2015 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 17:18:24.611   873  2015 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-12 17:18:24.612   873  4026 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:18:24.612   873  4026 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:18:24.612   873  4026 E DropBoxManagerService: 	... 5 more
08-12 17:18:24.614   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-12 17:18:24.614   873  2015 I ActivityManager: Killing 3998:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
08-12 17:18:24.620  4013  4013 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm

```
