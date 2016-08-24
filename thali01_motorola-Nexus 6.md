#### Test 825189961ca4444_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 16:54:34.960   873  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 16:54:35.679  3835  3835 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 16:54:35.685  3835  3835 D AndroidRuntime: CheckJNI is OFF
08-24 16:54:35.736  3835  3835 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 16:54:35.790  3835  3835 I Radio-JNI: register_android_hardware_Radio DONE
08-24 16:54:35.811  3835  3835 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 16:54:35.814   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 16:54:35.842  2040  3750 W SearchService: Abort, client detached.
08-24 16:54:35.854  2040  2040 I HotwordDetector: Closing mic
08-24 16:54:35.855  2040  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@38434
08-24 16:54:35.855  2040  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 16:54:35.866  3835  3835 D AndroidRuntime: Shutting down VM
08-24 16:54:35.893   873  1602 I ActivityManager: Start proc 3844:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 16:54:35.910   376  2355 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 16:54:35.912   376  2355 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 16:54:35.922   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 16:54:35.925  2040  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 16:54:35.926  2040  2351 I MicroRecognitionRnrImpl: Detection finished
08-24 16:54:35.981  3844  3844 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 16:54:36.002  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 16:54:36.009  3844  3844 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4693-4695)
08-24 16:54:36.009  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:54:36.027  3844  3844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c4ff17}
08-24 16:54:36.027  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 16:54:36.028  3844  3844 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 16:54:36.034  3844  3844 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 16:54:36.035  3844  3844 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 16:54:36.048  3844  3844 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 16:54:36.057  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 16:54:36.057  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 16:54:36.057  3844  3844 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 16:54:36.057  3844  3844 I Adreno  : Build Date                       : 10/20/15
08-24 16:54:36.057  3844  3844 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 16:54:36.057  3844  3844 I Adreno  : Local Branch                     : M14
08-24 16:54:36.057  3844  3844 I Adreno  : Remote Branch                    : 
08-24 16:54:36.057  3844  3844 I Adreno  : Remote Branch                    : 
08-24 16:54:36.057  3844  3844 I Adreno  : Reconstruct Branch               : 
,08-24 16:54:36.114   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c00b46:true
,08-24 16:54:36.151  3844  3844 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 16:54:36.167  3844  3844 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 16:54:36.238  3844  3883 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 16:54:36.246  3844  3870 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 16:54:36.283  3844  3883 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 16:54:36.334   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +468ms
,08-24 16:54:36.336  1888  1888 I Keyboard.Facilitator: onFinishInput()
,08-24 16:54:36.401  3844  3844 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3844
,08-24 16:54:36.528  3844  3844 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 16:54:36.706   873  1708 I ActivityManager: Killing 3414:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 16:54:36.744   873  1708 I ActivityManager: Killing 3214:com.google.android.gm/u0a78 (adj 15): empty #18
,08-24 16:54:36.756  3844  3886 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1696138960
,08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 16:54:36.765  3844  3886 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d976f3a added. We now have 1 listener(s)
,08-24 16:54:36.770  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 16:54:36.774  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:54:36.774  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:54:36.775  3844  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 16:54:36.780  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 16:54:36.781  3844  3886 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81663e1 added. We now have 1 listener(s)
08-24 16:54:36.782  3844  3886 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:54:36.789   873  1312 D WifiService: New client listening to asynchronous messages
,08-24 16:54:36.792  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:54:36.792  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 16:54:36.793  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 16:54:36.793  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 16:54:36.793  3844  3886 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 16:54:36.798  3844  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:54:36.798  3844  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 16:54:36.812  3844  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:36.812  3844  3886 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:36.813  3844  3886 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 16:54:36.813  3844  3886 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:54:36.814  3844  3886 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 16:54:36.815  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:36.817  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:36.998  3844  3844 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 16:54:38.213  3844  3896 W jxcore-log: Initializing JXcore engine
,08-24 16:54:38.213  3844  3896 W jxcore-log: JXcore engine is ready
,08-24 16:54:38.250  3896  3896 W Thread-334: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 16:54:38.250  3896  3896 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12643]" dev="sockfs" ino=12643 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 16:54:38.250  3896  3896 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 16:54:38.250  3896  3896 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26912]" dev="sockfs" ino=26912 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 16:54:38.265  3844  3896 W jxcore-log: Starting JXcore engine
,08-24 16:54:38.342  3844  3896 W jxcore-log: Platform android
08-24 16:54:38.342  3844  3896 W jxcore-log: 
,08-24 16:54:38.343  3844  3896 W jxcore-log: Process ARCH arm
08-24 16:54:38.343  3844  3896 W jxcore-log: 
,08-24 16:54:38.522  3844  3896 I jxcore-log: JXcore Cordova bridge is ready!
08-24 16:54:38.522  3844  3896 I jxcore-log: 
08-24 16:54:38.523  3844  3896 W jxcore-log: JXcore engine is started
,08-24 16:54:38.537  3844  3886 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 16:54:38.545  3844  3844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 16:54:38.617   873  2106 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 16:54:39.412  3042  3898 V KeepSync: Connecting to GoogleApiClient
,08-24 16:54:39.413   873  1375 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 16:54:39.471  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:54:39.473  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:54:39.512  1497  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 16:54:39.512  1497  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 16:54:39.512  1497  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:54:39.513  1497  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:54:39.544  1709  3899 V BaseAuthAsyncOperation: access token request failed
,08-24 16:54:39.544  3042  3898 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 16:54:39.608  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 16:54:39.608  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 16:54:39.608  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 16:54:39.609  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:54:39.653  3042  3898 E KeepSync: IOException
08-24 16:54:39.653  3042  3898 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 16:54:39.653  3042  3898 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 16:54:39.653  3042  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 16:54:39.653  3042  3898 E KeepSync: 	... 10 more
,08-24 16:54:39.653  3042  3898 W KeepSync: Sync result 2
,08-24 16:54:39.679   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127602, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 16:54:41.108  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:54:41.134  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 16:54:41.134  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 16:54:41.134  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 16:54:41.134  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:54:41.157  3537  3537 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 16:54:41.157  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 16:54:41.157  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-24 16:54:48.490  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 16:54:48.490  3844  3896 I jxcore-log: 
,08-24 16:54:48.492  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 16:54:48.492  3844  3896 I jxcore-log: 
,08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:48.501  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:48.504  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:54:48.505  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 16:54:48.505  3844  3896 I jxcore-log: 
,08-24 16:54:48.507  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 16:54:48.507  3844  3896 I jxcore-log: 
,08-24 16:54:49.033  3844  3896 D executeNativeTests: Running unit tests
,08-24 16:54:49.069  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:54:49.070  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:54:49.082  3786  3908 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 16:54:49.116  1497  2523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 16:54:49.117  1497  2523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 16:54:49.117  1497  2523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 16:54:49.117  1497  2523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 16:54:49.117  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:54:49.118  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb added. We now have 2 listener(s)
08-24 16:54:49.119  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:54:49.119  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:54:49.119  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:54:49.119  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:54:49.119  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 added. We now have 2 listener(s)
08-24 16:54:49.119  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:54:49.119  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:54:49.121  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:49.124  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:49.126  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.126  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:54:49.128  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 16:54:49.128  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:54:49.128  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:54:49.128  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.131  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.131  3844  3896 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-24 16:54:49.131  3844  3896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 16:54:49.131  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 16:54:49.131  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 16:54:49.131  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 16:54:49.133  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.133  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.133  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.134  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.134  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.134  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.134  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:54:49.134  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb removed from the list
08-24 16:54:49.134  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.134  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 removed from the list
,08-24 16:54:49.134  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 16:54:49.134  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.135  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.135  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.139  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.139  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.139  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.139  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.141  3786  3908 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 16:54:49.142  3844  3896 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-24 16:54:49.142  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.142  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.142  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.142  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.142  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 16:54:49.142  3786  3908 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
08-24 16:54:49.142  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.142  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.142  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.142  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.142  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.142  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.142  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.143  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.143  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.143  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.144  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.144  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.144  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 16:54:49.148  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-24 16:54:49.149  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 16:54:49.150  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 16:54:49.150  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.150  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.150  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.150  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.150  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.150  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.150  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.150  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.150  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.151  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.151  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.151  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.151  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.151  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.151  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-24 16:54:49.151  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 16:54:49.151  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.151  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.152  3844  3896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 16:54:49.153  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:49.156  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:54:49.158  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.158  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:54:49.158  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 16:54:49.158  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:54:49.158  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:54:49.158  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:54:49.158  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:54:49.160  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.161  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 16:54:49.161  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 16:54:49.162  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.165  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:54:49.166  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 16:54:49.166  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:54:49.168  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-24 16:54:49.169  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-24 16:54:49.169  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 16:54:49.169  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 16:54:49.170  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 16:54:49.171  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:54:49.174  2711  2726 D BtGatt.GattService: registerClient() - UUID=4aa2fa82-c592-4cf1-8ba6-95f91bccf478
,08-24 16:54:49.174  2711  2763 D BtGatt.GattService: onClientRegistered() - UUID=4aa2fa82-c592-4cf1-8ba6-95f91bccf478, clientIf=5
,08-24 16:54:49.175  3844  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 16:54:49.175  2711  2911 D BtGatt.GattService: start scan with filters
,08-24 16:54:49.179  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 16:54:49.179  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 16:54:49.179  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 16:54:49.179  2711  2767 D BtGatt.ScanManager: handling starting scan,
08-24 16:54:49.179  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 16:54:49.180  2711  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:49.181  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 16:54:49.181  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 16:54:49.181  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:54:49.182  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:54:49.184  3844  3896 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 16:54:49.185  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.185  3844  3896 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 16:54:49.185  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.186  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 16:54:49.186  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.186  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 16:54:49.186  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 16:54:49.186  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:54:49.186  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 16:54:49.186  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 16:54:49.186  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:54:49.186  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 16:54:49.187  2711  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 16:54:49.187  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.187  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:54:49.187  2711  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 16:54:49.187  2711  2724 D BtGatt.GattService: stopScan() - queue size =1
,08-24 16:54:49.187  2711  2911 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 16:54:49.188  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:54:49.188  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 16:54:49.188  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 16:54:49.188  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 16:54:49.188  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 16:54:49.188  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.189  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 16:54:49.189  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 16:54:49.189  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:54:49.189  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.190  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.190  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.190  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.190  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.190  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.190  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.190  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.190  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.190  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.190  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop,
08-24 16:54:49.190  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.190  3844  3896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 16:54:49.191  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 16:54:49.191  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.191  2711  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-24 16:54:49.191  2711  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 16:54:49.192  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:49.195  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:49.196  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.196  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 16:54:49.196  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:54:49.196  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:54:49.196  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:54:49.196  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:54:49.196  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 16:54:49.198  2711  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 16:54:49.198  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.198  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.199  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 16:54:49.199  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 16:54:49.200  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.202  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:54:49.202  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 16:54:49.202  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:54:49.203  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 16:54:49.203  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:54:49.206  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 16:54:49.206  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 16:54:49.206  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 16:54:49.207  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:54:49.208  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 16:54:49.208  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.208  2711  2767 D BtGatt.ScanManager: stopping BLe Batch
08-24 16:54:49.209  2711  2724 D BtGatt.GattService: registerClient() - UUID=0b0dea69-2ee8-4b5e-98e2-dd0fa9fd7e0f
,08-24 16:54:49.209  2711  2763 D BtGatt.GattService: onClientRegistered() - UUID=0b0dea69-2ee8-4b5e-98e2-dd0fa9fd7e0f, clientIf=5
08-24 16:54:49.210  3844  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 16:54:49.210  2711  2911 D BtGatt.GattService: start scan with filters
,08-24 16:54:49.212  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 16:54:49.212  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 16:54:49.212  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 16:54:49.212  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 16:54:49.214  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 16:54:49.214  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.215  2711  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 16:54:49.215  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:54:49.215  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:54:49.215  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 16:54:49.216  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:54:49.217  3844  3896 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 16:54:49.219  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.219  3844  3896 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 16:54:49.219  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.219  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 16:54:49.219  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.219  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 16:54:49.219  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 16:54:49.219  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:54:49.219  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 16:54:49.219  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 16:54:49.220  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:54:49.220  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 16:54:49.220  2711  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 16:54:49.220  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.220  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:54:49.221  2711  2724 D BtGatt.GattService: stopScan() - queue size =0
,08-24 16:54:49.221  2711  2911 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 16:54:49.221  2711  2767 D BtGatt.ScanManager: handling starting scan
,08-24 16:54:49.221  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:54:49.222  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 16:54:49.222  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 16:54:49.222  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 16:54:49.222  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 16:54:49.223  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.223  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 16:54:49.223  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 16:54:49.223  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 16:54:49.223  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.224  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.224  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.224  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.224  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.224  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.225  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.225  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.225  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.225  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.225  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 16:54:49.225  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.225  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.225  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.226  2711  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 16:54:49.226  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.226  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.226  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.226  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.226  2711  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 16:54:49.226  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.226  3844  3896 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 16:54:49.227  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:54:49.230  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 16:54:49.230  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:54:49.230  2711  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-24 16:54:49.230  2711  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:49.231  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:49.233  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.233  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:54:49.234  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:54:49.234  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 16:54:49.234  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:54:49.234  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:54:49.234  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:54:49.235  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.237  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.237  2711  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 16:54:49.237  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:54:49.238  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 16:54:49.238  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 16:54:49.240  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 16:54:49.241  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 16:54:49.241  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 16:54:49.241  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 16:54:49.241  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:54:49.244  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 16:54:49.244  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 16:54:49.244  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 16:54:49.244  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:54:49.246  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 16:54:49.246  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.246  2711  2724 D BtGatt.GattService: registerClient() - UUID=a0dcfee0-5e1d-4074-ac4b-ac65b42ea265
,08-24 16:54:49.247  2711  2763 D BtGatt.GattService: onClientRegistered() - UUID=a0dcfee0-5e1d-4074-ac4b-ac65b42ea265, clientIf=5
08-24 16:54:49.247  3844  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 16:54:49.247  2711  2767 D BtGatt.ScanManager: stopping BLe Batch
08-24 16:54:49.247  2711  2911 D BtGatt.GattService: start scan with filters
,08-24 16:54:49.249  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 16:54:49.249  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 16:54:49.249  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 16:54:49.249  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 16:54:49.251  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:54:49.251  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:54:49.251  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 16:54:49.252  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 16:54:49.252  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.252  2711  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 16:54:49.252  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:54:49.254  3844  3896 I io.jxcore.node.ConnectionHelper: start: OK
08-24 16:54:49.254  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.254  3844  3896 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 16:54:49.254  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.254  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 16:54:49.254  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.254  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 16:54:49.254  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 16:54:49.254  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:54:49.254  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 16:54:49.254  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 16:54:49.254  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:54:49.255  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 16:54:49.255  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:54:49.255  2711  2911 D BtGatt.GattService: stopScan() - queue size =0
08-24 16:54:49.256  2711  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 16:54:49.256  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:54:49.256  2711  2920 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 16:54:49.256  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 16:54:49.256  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 16:54:49.256  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 16:54:49.257  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 16:54:49.257  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 16:54:49.257  2711  2767 D BtGatt.ScanManager: handling starting scan
08-24 16:54:49.257  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.257  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 16:54:49.257  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 16:54:49.257  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:54:49.258  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.259  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.259  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.259  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 16:54:49.259  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.259  3844  3896 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 16:54:49.259  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.259  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.259  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.259  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.260  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:54:49.260  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
,08-24 16:54:49.260  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.260  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.260  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.260  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.260  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.260  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.261  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.261  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.261  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.261  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.261  2711  2763 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 16:54:49.261  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.261  2711  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 16:54:49.261  3844  3896 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 16:54:49.262  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.262  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 16:54:49.262  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.262  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.262  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.262  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.262  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.262  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.262  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.262  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.262  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.262  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.262  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 16:54:49.262  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.263  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:54:49.263  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.263  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.263  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.264  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 16:54:49.264  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.264  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.264  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.264  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.264  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.264  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.264  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.264  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.265  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.265  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.265  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.265  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.265  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.265  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.265  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 16:54:49.265  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.265  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.265  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 16:54:49.265  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.265  2711  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-24 16:54:49.265  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.265  2711  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 16:54:49.266  3844  3896 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-24 16:54:49.266  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.266  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.266  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.266  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.266  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.266  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.266  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
,08-24 16:54:49.266  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.266  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.266  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 16:54:49.266  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.267  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.267  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.267  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.267  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:54:49.267  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.267  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.267  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.268  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-24 16:54:49.268  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.268  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.268  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.268  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.268  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.268  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.268  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.268  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.268  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.268  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop,
08-24 16:54:49.269  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.269  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.269  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.269  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.269  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.269  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.269  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.270  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.270  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 16:54:49.271  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:54:49.271  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 16:54:49.271  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 16:54:49.271  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 16:54:49.271  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 16:54:49.273  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.273  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.273  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.273  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.273  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.273  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.274  2711  2763 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 16:54:49.274  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.274  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.274  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.274  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.275  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.275  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.275  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.275  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.276  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.277  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:54:49.277  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.277  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.277  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.278  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:54:49.278  3844  3896 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 16:54:49.278  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 16:54:49.278  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 16:54:49.278  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.280  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:54:49.280  3844  3896 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 16:54:49.280  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-24 16:54:49.281  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-24 16:54:49.282  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 16:54:49.282  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 16:54:49.282  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 16:54:49.282  3844  3896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:54:49.282  3844  3896 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 16:54:49.282  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:54:49.282  3844  3896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:54:49.282  3844  3896 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 16:54:49.282  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 16:54:49.282  3844  3896 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 16:54:49.282  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 16:54:49.284  2711  2763 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 16:54:49.284  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.284  2711  2767 D BtGatt.ScanManager: stopping BLe Batch
08-24 16:54:49.286  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 16:54:49.286  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 16:54:49.286  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 16:54:49.287  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-24 16:54:49.287  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 16:54:49.287  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 16:54:49.287  3844  3896 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 16:54:49.287  3844  3896 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 16:54:49.288  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:54:49.288  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.288  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.288  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.288  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.288  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.288  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 16:54:49.288  3844  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-24 16:54:49.289  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.289  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.289  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.289  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.289  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.289  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.289  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.289  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.289  2711  2763 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 16:54:49.289  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.289  2711  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 16:54:49.289  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.289  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.290  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.290  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.290  3844  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
,08-24 16:54:49.290  3844  3896 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 16:54:49.290  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.290  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.290  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.291  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.291  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.291  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.291  3844  3910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:54:49.291  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
,08-24 16:54:49.291  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.291  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.291  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.291  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.291  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.291  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.291  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.292  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.292  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.292  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.292  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.293  3844  3896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 16:54:49.293  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.293  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 16:54:49.293  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.293  2711  2763 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 16:54:49.293  2711  2763 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:54:49.293  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.293  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.293  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.294  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.294  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.294  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.294  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.294  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.294  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.294  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.294  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.295  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.295  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.295  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.295  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.295  3844  3896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 16:54:49.295  3844  3896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 16:54:49.295  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:54:49.295  3844  3896 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-24 16:54:49.296  3844  3896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 16:54:49.296  3844  3896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 16:54:49.296  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 16:54:49.296  3844  3896 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 16:54:49.296  3844  3896 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 16:54:49.296  3844  3896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 16:54:49.296  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 16:54:49.296  3844  3896 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 16:54:49.296  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.296  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 16:54:49.296  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.297  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.297  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.297  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.297  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.297  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.297  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.297  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.297  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.297  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.297  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.297  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.298  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:54:49.298  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.298  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.298  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.298  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.298  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.298  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.298  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.298  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.298  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.299  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.299  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.299  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.299  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.299  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.299  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.299  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.299  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.299  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.299  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.299  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.299  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:54:49.299  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.299  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.299  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.299  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list,
08-24 16:54:49.300  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.300  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.300  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.300  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 16:54:49.300  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.300  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.300  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-24 16:54:49.301  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.301  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.301  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.301  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.302  3844  3896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 16:54:49.302  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:54:49.303  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-24 16:54:49.303  3844  3896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 16:54:49.303  3844  3896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 16:54:49.304  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 16:54:49.304  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-24 16:54:49.304  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 16:54:49.304  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.304  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 16:54:49.304  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-24 16:54:49.304  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 16:54:49.304  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.304  3844  3896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-24 16:54:49.304  3844  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:54:49.304  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 16:54:49.304  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
,08-24 16:54:49.305  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.305  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:54:49.305  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 16:54:49.305  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 16:54:49.305  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.305  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.306  3844  3912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-24 16:54:49.306  3844  3912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 16:54:49.306  3844  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 16:54:49.306  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 16:54:49.306  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.306  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:54:49.306  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:54:49.306  3844  3844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 16:54:49.306  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.307  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.307  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.307  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.307  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:54:49.307  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.307  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.307  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.307  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.307  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.307  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.307  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.307  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.307  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.307  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.308  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.309  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.309  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.309  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.309  3844  3896 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 16:54:49.310  3844  3896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 16:54:49.310  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 16:54:49.311  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 16:54:49.311  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.311  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.311  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.313  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-24 16:54:49.313  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.313  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.313  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
,08-24 16:54:49.313  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.313  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.313  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.313  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.313  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.313  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.313  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.315  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:54:49.315  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.315  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.315  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.318  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.318  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.318  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.319  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.319  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.319  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.319  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.319  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.319  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.319  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.319  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.319  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.319  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.319  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.320  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.321  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.321  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:54:49.321  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.321  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:54:49.321  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:54:49.321  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:54:49.321  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:54:49.321  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.322  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.322  3844  3896 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b96bdfb not in the list
08-24 16:54:49.322  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.322  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
,08-24 16:54:49.322  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:54:49.322  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:54:49.322  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:54:49.322  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:54:49.322  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:54:49.323  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:54:49.323  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:54:49.323  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:54:49.323  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8338e18 not in the list
08-24 16:54:49.324  3844  3896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-24 16:54:49.324  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:54:49.324  3844  3896 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 16:54:49.324  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 16:54:49.324  3844  3896 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 16:54:49.324  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-24 16:54:49.325  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 16:54:49.325  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 16:54:49.326  3844  3896 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 16:54:49.326  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 16:54:49.326  3844  3896 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 16:54:49.326  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 16:54:49.326  3844  3896 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 16:54:49.326  3844  3896 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-24 16:54:49.326  3844  3896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 16:54:49.327  3844  3896 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 16:54:49.327  3844  3896 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 16:54:49.327  3844  3896 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 16:54:49.327  3844  3896 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 16:54:49.327  3844  3896 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 16:54:49.328  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:54:49.328  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b61633a added. We now have 2 listener(s)
08-24 16:54:49.328  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:54:49.329  3844  3896 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 16:54:49.330   873  1708 D WifiService: setWifiEnabled: true pid=3844, uid=10000
08-24 16:54:49.330   873  1708 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 16:54:49.330  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:54:49.330  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8f1beb added. We now have 3 listener(s)
,08-24 16:54:49.330  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:54:49.336  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:54:49.337  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@332ad48 added. We now have 4 listener(s)
08-24 16:54:49.337  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:54:49.338  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:54:49.338  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0fe7e1 added. We now have 5 listener(s)
08-24 16:54:49.338  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:54:49.340   873  1707 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,08-24 16:54:49.340   873  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:54:49.344  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:54:49.344  2711  2759 D BluetoothAdapterState: Current state: ON, message: 23
08-24 16:54:49.344  2711  2759 D BluetoothAdapterProperties: Setting state to 13
08-24 16:54:49.344  2711  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 16:54:49.345  2711  2759 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 16:54:49.345  2711  2759 I BluetoothAdapterState: Entering PendingCommandState
,08-24 16:54:49.346  2711  2763 D BluetoothAdapterProperties: Scan Mode:20
,08-24 16:54:49.347  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-24 16:54:49.347  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:49.347  2711  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 16:54:49.347  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:49.347  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:54:49.347  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:54:49.348  2711  2711 D HeadsetService: Received stop request...Stopping profile...
,08-24 16:54:49.349   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 16:54:49.349  1369  2105 D BluetoothHeadset: Proxy object disconnected
08-24 16:54:49.350  1954  1965 D BluetoothHeadset: Proxy object disconnected
,08-24 16:54:49.350   873   873 D BluetoothHeadset: Proxy object disconnected
08-24 16:54:49.350  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.350   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 16:54:49.350  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.351  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:49.350  1369  1369 D HeadsetProfile: Bluetooth service disconnected
,08-24 16:54:49.351  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:49.351  2711  2711 D A2dpService: Received stop request...Stopping profile...
,08-24 16:54:49.352  2711  2915 D A2dpStateMachine: Exit Disconnected: -1
,08-24 16:54:49.354  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:49.356   873   873 D BluetoothA2dp: Proxy object disconnected
,08-24 16:54:49.356  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 16:54:49.356  2711  2711 D HidService: Received stop request...Stopping profile...
,08-24 16:54:49.356  2711  2711 D HidService: Stopping Bluetooth HidService
08-24 16:54:49.357  1369  1369 D BluetoothA2dp: Proxy object disconnected
,08-24 16:54:49.357  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.357   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 16:54:49.357   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 16:54:49.357   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 16:54:49.357   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:54:49.357  1369  1369 D BluetoothInputDevice: Proxy object disconnected
,08-24 16:54:49.358  1369  1369 D HidProfile: Bluetooth service disconnected
,08-24 16:54:49.359  2711  2711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 16:54:49.359  2711  2711 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:54:49.359  2711  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-24 16:54:49.359  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:54:49.359  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 16:54:49.359  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 16:54:49.360  2711  2711 D HealthService: Received stop request...Stopping profile...
,08-24 16:54:49.360  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:49.360  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:49.361  2711  2763 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 16:54:49.361  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.361  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:54:49.363  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.363  2711  2711 D PanService: Received stop request...Stopping profile...
,08-24 16:54:49.364  2711  2711 D BluetoothMapService: Received stop request...Stopping profile...
08-24 16:54:49.364  2711  2711 D BluetoothMapService: stop()
,08-24 16:54:49.364  2711  2711 D BluetoothMapAppObserver: deinitObservers()
08-24 16:54:49.364  2711  2711 D BluetoothMapAppObserver: removeReceiver()
,08-24 16:54:49.364  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 16:54:49.365  1369  1369 D PanProfile: Bluetooth service disconnected
08-24 16:54:49.366  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.366  1369  1369 D BluetoothMap: Proxy object disconnected
08-24 16:54:49.366  1369  1369 D MapProfile: Bluetooth service disconnected
08-24 16:54:49.366  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.366  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:49.366  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:49.366   873  2111 D DhcpClient: Clearing IP address
,08-24 16:54:49.366   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:54:49.367  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.367  2711  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 16:54:49.367  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.367  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:54:49.367  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:49.367  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:49.367  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:54:49.367  2711  2896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 16:54:49.367  2711  2711 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 16:54:49.368  2711  2711 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 16:54:49.368  2711  2763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 16:54:49.368  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.368  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.368  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:49.368  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:49.367  2711  2896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:54:49.368  2711  2896 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 16:54:49.368  2711  2896 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:54:49.368  2711  2711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 16:54:49.369  2711  2763 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 16:54:49.369  2711  2711 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 16:54:49.369  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.369  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.369  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:54:49.369  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:49.370  2711  2711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-24 16:54:49.370  2711  2711 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 16:54:49.370  2711  2711 D BluetoothMapService: MAP Service closeService in
08-24 16:54:49.370  2711  2711 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 16:54:49.370  2711  2711 D ObexServerSockets0: shutdown(block = true)
08-24 16:54:49.371  2711  2711 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 16:54:49.371  2711  2908 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 16:54:49.371  2711  2711 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 16:54:49.371  2711  2921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-24 16:54:49.371  1497  3460 V NativeCrypto: Read error: ssl=0x9b21a400: I/O error during system call, Connection timed out
08-24 16:54:49.372   372   871 D CommandListener: Setting iface cfg
08-24 16:54:49.372  2711  2922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 16:54:49.372  1497  3460 V NativeCrypto: SSL shutdown failed: ssl=0x9b21a400: I/O error during system call, Broken pipe
08-24 16:54:49.374   873  2287 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-24 16:54:49.374   873  2096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-24 16:54:49.375  2711  2711 V BluetoothAdapterState: isTurningOff()=true
08-24 16:54:49.375  2711  2711 V BluetoothAdapterState: isTurningOn()=false
08-24 16:54:49.376   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 16:54:49.376  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:49.376   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-24 16:54:49.376  2711  2711 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:49.377  2711  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 16:54:49.377  2711  2759 D BluetoothAdapterProperties: Setting state to 15
08-24 16:54:49.377  2711  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 16:54:49.378   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
08-24 16:54:49.378  2711  2759 I BluetoothAdapterState: Entering BleOnState
08-24 16:54:49.378  2711  2711 D BluetoothMapService: cleanup()
08-24 16:54:49.378  2711  2711 D BluetoothMapService: MAP Service closeService in
08-24 16:54:49.378   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 16:54:49.379   395   395 E Parcel  : Reading a NULL string not supported here.
08-24 16:54:49.380   873  2096 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-24 16:54:49.382   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:54:49.385   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 16:54:49.387   873  2117 D DhcpClient: Receive thread stopped
08-24 16:54:49.389  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:49.389  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:54:49.390  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.390  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:49.392  1855  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:54:49.395  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:49.395  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:54:49.396  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.396  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:54:49.396  2711  2711 I BtOppRfcommListener: stopping Accept Thread
08-24 16:54:49.396  2711  3425 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 16:54:49.397  2711  3425 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 16:54:49.397   873  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 16:54:49.398   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 16:54:49.402  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.404  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:49.404  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:49.414   873  1602 I ActivityManager: Start proc 3917:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-24 16:54:49.415  1369  2099 D BluetoothMap: onBluetoothStateChange: up=false
08-24 16:54:49.416   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:54:49.416  1369  2105 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:54:49.417  1369  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 16:54:49.418  1369  1381 D BluetoothPan: onBluetoothStateChange on: false
08-24 16:54:49.418  1369  2099 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 16:54:49.419  1369  2105 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:54:49.419   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:54:49.419  1954  1966 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:54:49.420   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:54:49.420   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:54:49.420  2711  2759 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 16:54:49.420  2711  2759 D BluetoothAdapterProperties: Setting state to 16
08-24 16:54:49.420  2711  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 16:54:49.421  2711  2759 D BluetoothAdapterProperties: onBleDisable
08-24 16:54:49.421  2711  2759 I BluetoothAdapterState: Entering PendingCommandState
08-24 16:54:49.421  2711  2760 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 16:54:49.422  3844  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-24 16:54:49.422  2711  2896 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 16:54:49.422  2711  2896 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:54:49.422  2711  2763 D BluetoothAdapterProperties: Scan Mode:20
08-24 16:54:49.427  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:49.428  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:49.429  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.430  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.431  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.436   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-24 16:54:49.455   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-24 16:54:49.456   873  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-24 16:54:49.457   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 16:54:49.458   873   890 D Tethering: MasterInitialState.processMessage what=3
08-24 16:54:49.461  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.462  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:49.475  3917  3917 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-24 16:54:49.487  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 16:54:49.493  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:54:49.493   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@640dda2:true
08-24 16:54:49.505   873  1686 I ActivityManager: Start proc 3937:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-24 16:54:49.508   372   871 E Netd    : netlink response contains error (No such file or directory)
08-24 16:54:49.509   873  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-24 16:54:49.509   873  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 16:54:49.515  3917  3917 D LocalBluetoothProfileManager: Adding local MAP profile
08-24 16:54:49.517  3917  3917 D BluetoothMap: Create BluetoothMap proxy object
08-24 16:54:49.522  3917  3917 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-24 16:54:49.534  3917  3917 D DockEventReceiver: finishStartingService: stopping service
08-24 16:54:49.540  3937  3937 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-24 16:54:49.542   873  1969 I ActivityManager: Killing 3580:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 16:54:49.623  2711  2763 I bt_hci  : shut_down
,08-24 16:54:49.629  2711  2768 I bt_vendor: low_power_mode_cb
,08-24 16:54:49.638  2711  2768 D bt_hwcfg: hw_epilog_process
,08-24 16:54:49.658  2711  2768 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 16:54:49.658  2711  2768 I bt_vendor: epilog_cb
08-24 16:54:49.658  2711  2768 I bt_hci  : epilog_finished_callback
,08-24 16:54:49.660  2711  2763 I bt_hci_h4: hal_close
08-24 16:54:49.661  2711  2763 I bt_userial_vendor: device fd = 51 close
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=46 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.734  3937  3937 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:54:49.734  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 16:54:49.738  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 16:54:49.750  3917  3917 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:54:49.750  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:54:49.758   873  2287 I ActivityManager: Killing 2791:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 16:54:49.807  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 16:54:49.839  2711  2760 D bt_stack_manager: event_shut_down_stack finished.
,08-24 16:54:49.840  2711  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-24 16:54:49.847  2711  2759 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 16:54:49.847  2711  2711 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:54:49.848  2711  2711 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 16:54:49.848  2711  2711 D BtGatt.GattService: stop()
08-24 16:54:49.849  2711  2711 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 16:54:49.850  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 16:54:49.857  2711  2711 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:49.858  2711  2711 V BluetoothAdapterState: isTurningOn()=false
,08-24 16:54:49.858  2711  2711 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:54:49.858  2711  2711 V BluetoothAdapterState: isBleTurningOff()=true
08-24 16:54:49.859  2711  2759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 16:54:49.859  2711  2759 D BluetoothAdapterProperties: Setting state to 10
08-24 16:54:49.860  2711  2759 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 16:54:49.861  2711  2759 I BluetoothAdapterState: Entering OffState
,08-24 16:54:49.864   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 16:54:49.865  1709  1709 D SystemUpdateService: onCreate
,08-24 16:54:49.883  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 16:54:49.891  2711  2711 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 16:54:49.891  2711  2711 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 16:54:49.891  2711  2760 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 16:54:49.894  2711  2760 D bt_stack_manager: event_clean_up_stack finished.
,08-24 16:54:49.894  2711  2711 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 16:54:49.900  1709  3968 I SystemUpdateService: active receiver: enabled
,08-24 16:54:49.902  2711  2711 I art     : System.exit called, status: 0
,08-24 16:54:49.902  2711  2711 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 16:54:49.904  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 16:54:49.905  1709  2519 I iu.UploadsManager: num queued entries: 0
,08-24 16:54:49.921  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 16:54:49.915  1709  2519 I iu.UploadsManager: num updated entries: 0
08-24 16:54:49.922  1709  2519 I iu.SyncManager: NEXT; no task
,08-24 16:54:49.926  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 16:54:49.938  1709  3968 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 16:54:49.943  1709  3968 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 16:54:49.944  1709  3968 I SystemUpdateService: now status is 0 (complete)
,08-24 16:54:49.944  1709  3968 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 16:54:49.945  1709  3968 I SystemUpdateService: file has been verified
,08-24 16:54:49.946  1709  3968 I SystemUpdateService: OTA package size = 12249756
,08-24 16:54:49.956   873  1980 I ActivityManager: Start proc 3972:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-24 16:54:49.970  1709  3968 I SystemUpdateService: showing system update notification
,08-24 16:54:49.972   873  1375 I ActivityManager: Process com.android.bluetooth (pid 2711) has died
,08-24 16:54:50.014  1709  1709 D SystemUpdateService: onDestroy
,08-24 16:54:50.021  3972  3972 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 16:54:50.023  3972  3972 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:54:50.031  3972  3972 D SprintDMHelper: simOperator: 
,08-24 16:54:50.031  3972  3972 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 16:54:50.045   873  1602 I ActivityManager: Start proc 3985:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 16:54:50.064  3937  3955 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 16:54:50.132   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff2e86f:true
,08-24 16:54:50.145  2216  3999 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 16:54:50.147   873   883 I ActivityManager: Start proc 4000:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 16:54:50.151   873   883 I ActivityManager: Killing 3520:android.process.acore/u0a5 (adj 15): empty #17
,08-24 16:54:50.238  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 16:54:50.304  4000  4000 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 16:54:50.304  4000  4000 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 16:54:50.304  4000  4000 I GAv4    :   adb logcat -s GAv4
,08-24 16:54:50.327  4000  4000 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:54:50.332  4000  4000 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:54:50.360  4000  4018 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 16:54:50.470  4000  4000 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 16:54:50.512  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 16:54:50.525  4000  4000 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9208-9212)
08-24 16:54:50.525  4000  4000 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 16:54:50.543  4000  4000 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dbcf1db}
,08-24 16:54:50.543  4000  4000 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 16:54:50.545  4000  4000 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 16:54:50.553  4000  4000 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-24 16:54:50.556  4000  4000 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 16:54:50.570  4000  4000 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 16:54:50.587  4000  4000 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 16:54:50.587  4000  4000 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 16:54:50.587  4000  4000 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 16:54:50.587  4000  4000 I Adreno  : Build Date                       : 10/20/15
08-24 16:54:50.587  4000  4000 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 16:54:50.587  4000  4000 I Adreno  : Local Branch                     : M14
08-24 16:54:50.587  4000  4000 I Adreno  : Remote Branch                    : 
08-24 16:54:50.587  4000  4000 I Adreno  : Remote Branch                    : 
08-24 16:54:50.587  4000  4000 I Adreno  : Reconstruct Branch               : 
,08-24 16:54:50.653  4000  4000 I NSApplication: Starting up...
,08-24 16:54:50.664  4000  4048 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 16:54:50.692   873  2288 I ActivityManager: Start proc 4053:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 16:54:50.693   873  2288 I ActivityManager: Killing 3654:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 16:54:50.779  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 16:54:50.964   873  2020 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 16:54:52.355   873  1686 D WifiService: setWifiEnabled: true pid=3844, uid=10000
,08-24 16:54:52.355   873  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:54:52.369   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-24 16:54:52.378  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:52.378  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:52.379  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:52.379  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:52.382  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:52.383  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:54:52.383  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:52.383  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:52.398   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-24 16:54:52.399   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 16:54:52.400   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 16:54:52.401   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 16:54:52.401   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 16:54:52.402   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-24 16:54:52.402   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 16:54:52.417   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 16:54:52.418   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.88 rxSuccessRate=15.25 delta 1000 -> 994
,08-24 16:54:52.418   372   871 D CommandListener: Setting iface cfg
,08-24 16:54:52.419   873  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-24 16:54:52.419   873  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,08-24 16:54:52.422   873  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 16:54:52.423   873  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 16:54:52.429   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 16:54:52.429   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:54:52.450   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 16:54:52.506   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 16:54:52.507  1445  1445 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 16:54:52.928  1445  1445 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 16:54:52.963  1445  1445 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 16:54:52.963  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 16:54:52.970   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 16:54:52.978   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 16:54:52.978   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 16:54:52.978   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 16:54:52.995   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:54:53.009   372   871 D CommandListener: Setting iface cfg
,08-24 16:54:53.011   873  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 16:54:53.023   873  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-24 16:54:53.024   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 16:54:53.051   873  4076 D DhcpClient: Receive thread started
,08-24 16:54:53.134   873  1311 E native  : do suspend false
,08-24 16:54:53.154   873  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 16:54:53.168   873  4076 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-24 16:54:53.169   873  2111 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-24 16:54:53.175   873  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 16:54:53.187   873  4076 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 16:54:53.189   873  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 16:54:53.194   372   871 D CommandListener: Setting iface cfg
,08-24 16:54:53.205   873  2111 D DhcpClient: Scheduling renewal in 86399s
,08-24 16:54:53.208   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 16:54:53.227   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 16:54:53.230   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 16:54:53.231   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 16:54:53.232   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 16:54:53.234   873  1313 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 16:54:53.254   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 16:54:53.285   873  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 16:54:53.285   873  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 16:54:53.287   873  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-24 16:54:53.290   873  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-24 16:54:53.292   873  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 16:54:53.301   873  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 16:54:53.308   873  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 16:54:53.308   873  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-24 16:54:53.308   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-24 16:54:53.309   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 16:54:53.309   873  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-24 16:54:53.309   873  1313 D ConnectivityService:    accepting network in place of null
,08-24 16:54:53.310   873  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 16:54:53.322   873  4075 D NetlinkSocketObserver: NeighborEvent{elapsedMs=142008, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 16:54:53.356   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:54:53.407   873  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.238,2a00:1450:4001:817::200e
,08-24 16:54:53.417   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:54:53.426   873  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 16:54:53.427   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:54:53.430   873  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-24 16:54:53.433   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 16:54:53.447  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:53.447  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:54:53.447  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:53.447  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:53.449  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:54:53.449  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:54:53.449  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:53.449  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:54:53.454  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-24 16:54:53.457  1709  1709 D SystemUpdateService: onCreate
,08-24 16:54:53.461  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 16:54:53.473  1709  4086 I SystemUpdateService: active receiver: enabled
,08-24 16:54:53.477  1709  4086 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 16:54:53.481  1709  4086 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 16:54:53.482  1709  4086 I SystemUpdateService: now status is 0 (complete),
08-24 16:54:53.482  1709  4086 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 16:54:53.482  1709  4086 I SystemUpdateService: file has been verified
,08-24 16:54:53.482  1709  4086 I SystemUpdateService: OTA package size = 12249756
,08-24 16:54:53.485  1709  4086 I SystemUpdateService: showing system update notification
,08-24 16:54:53.492  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 16:54:53.495  1709  2519 I iu.UploadsManager: num queued entries: 0
,08-24 16:54:53.495  1709  2519 I iu.UploadsManager: num updated entries: 0
08-24 16:54:53.496  1709  2519 I iu.SyncManager: NEXT; no task
,08-24 16:54:53.499  1709  4091 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 16:54:53.499  1709  4091 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 16:54:53.500  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-24 16:54:53.500  1709  4091 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 16:54:53.501  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 16:54:53.505  3972  3972 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-24 16:54:53.505   873  4074 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 14:54:53 GMT], X-Android-Received-Millis=[1472050493504], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472050493467]}
,08-24 16:54:53.505  1709  1709 D SystemUpdateService: onDestroy
,08-24 16:54:53.507   873  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 16:54:53.508   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 16:54:53.508   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 16:54:53.509   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 16:54:53.516  3972  3972 D SprintDMHelper: simOperator: 
08-24 16:54:53.516  3972  3972 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 16:54:53.550  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 16:54:53.550  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 16:54:53.550  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:54:53.550  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:54:53.564  1709  4091 E MDM     : [178] SitrepService.a: Error sending sitrep.,
,08-24 16:54:53.631  2216  4094 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 16:54:54.424   873  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 16:54:54.962   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-24 16:54:55.124   873  1708 I ActivityManager: Killing 3462:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-24 16:54:55.361   873  2020 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,08-24 16:54:55.361   873  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:54:55.392  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 16:54:55.400   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 16:54:55.400   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 16:54:55.401   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 16:54:55.401   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:54:55.428   873  2111 D DhcpClient: Clearing IP address
,08-24 16:54:55.430   372   871 D CommandListener: Setting iface cfg
,08-24 16:54:55.434   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-24 16:54:55.436   873  4076 D DhcpClient: Receive thread stopped
,08-24 16:54:55.440  1497  4098 V NativeCrypto: Read error: ssl=0x9b19ae00: I/O error during system call, Connection timed out
,08-24 16:54:55.445  1497  4098 V NativeCrypto: SSL shutdown failed: ssl=0x9b19ae00: I/O error during system call, Broken pipe
,08-24 16:54:55.452   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 16:54:55.452   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-24 16:54:55.458   395   395 E Parcel  : Reading a NULL string not supported here.
,08-24 16:54:55.462   873  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-24 16:54:55.465   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
08-24 16:54:55.466   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 16:54:55.500   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:54:55.529   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:54:55.529   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-24 16:54:55.530   873  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 16:54:55.530   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:54:55.534   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-24 16:54:55.547  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:55.547  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:55.547  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.547  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:54:55.548  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:55.548  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:55.548  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.548  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:55.550   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 16:54:55.553  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:55.554  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:55.554  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.554  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:55.554  1855  2305 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 16:54:55.555  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:55.555  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:55.555  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:54:55.555  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:54:55.558   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 16:54:55.571  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 16:54:55.576  1709  1709 D SystemUpdateService: onCreate
,08-24 16:54:55.580  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 16:54:55.585  1709  4108 I SystemUpdateService: active receiver: enabled
,08-24 16:54:55.593  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 16:54:55.598  1709  2519 I iu.UploadsManager: num queued entries: 0
,08-24 16:54:55.602  1709  4108 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 16:54:55.603  1709  2519 I iu.UploadsManager: num updated entries: 0
,08-24 16:54:55.606  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 16:54:55.608  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 16:54:55.611  3972  3972 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:54:55.616  3972  3972 D SprintDMHelper: simOperator: 
,08-24 16:54:55.616  3972  3972 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 16:54:55.624   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-24 16:54:55.624   873  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-24 16:54:55.629  1709  4108 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 16:54:55.631  1709  4108 I SystemUpdateService: now status is 0 (complete)
,08-24 16:54:55.631  1709  4108 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 16:54:55.631  1709  4108 I SystemUpdateService: file has been verified
,08-24 16:54:55.636  1709  2519 I iu.SyncManager: NEXT; no task,
,08-24 16:54:55.645  2216  4112 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 16:54:55.647  1709  4108 I SystemUpdateService: OTA package size = 12249756
,08-24 16:54:55.667  1709  4108 I SystemUpdateService: showing system update notification
,08-24 16:54:55.677  1709  1709 D SystemUpdateService: onDestroy
,08-24 16:54:58.406   873   890 I ActivityManager: Start proc 4115:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 16:54:58.534  4115  4115 D AdapterServiceConfig: Adding HeadsetService
,08-24 16:54:58.534  4115  4115 D AdapterServiceConfig: Adding A2dpService
08-24 16:54:58.534  4115  4115 D AdapterServiceConfig: Adding HidService
08-24 16:54:58.534  4115  4115 D AdapterServiceConfig: Adding HealthService
08-24 16:54:58.535  4115  4115 D AdapterServiceConfig: Adding PanService
,08-24 16:54:58.535  4115  4115 D AdapterServiceConfig: Adding GattService
08-24 16:54:58.536  4115  4115 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 16:54:58.551   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ef2317:true
,08-24 16:54:58.552  4115  4115 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 16:54:58.560  4115  4127 I BluetoothAdapterState: Entering OffState
,08-24 16:54:58.560  4115  4115 I bt_bluedroid: init
,08-24 16:54:58.563  4115  4128 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 16:54:58.563  4115  4128 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 16:54:58.563  4115  4128 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 16:54:58.563  4115  4128 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 16:54:58.564  4115  4115 I bt_bluedroid: get_profile_interface socket
,08-24 16:54:58.568  4115  4115 I bt_bluedroid: get_profile_interface sdp
,08-24 16:54:58.569  4115  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 16:54:58.573  4115  4131 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 16:54:58.574  4115  4126 I bt_bluedroid: config_hci_snoop_log
,08-24 16:54:58.577   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 16:54:58.584  4115  4127 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 16:54:58.584  4115  4127 D BluetoothAdapterProperties: Setting state to 14
08-24 16:54:58.584  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 16:54:58.586  4115  4127 D BluetoothBondStateMachine: make
,08-24 16:54:58.590  4115  4132 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 16:54:58.596  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
08-24 16:54:58.597  4115  4115 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 16:54:58.601  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:58.603  4115  4115 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 16:54:58.604  4115  4115 D BtGatt.GattService: Received start request. Starting profile...
,08-24 16:54:58.604  4115  4115 D BtGatt.GattService: start()
,08-24 16:54:58.604  4115  4115 I bt_bluedroid: get_profile_interface gatt
,08-24 16:54:58.606  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:58.606  4115  4115 D BtGatt.AdvertiseManager: advertise manager created
,08-24 16:54:58.619  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:58.619  4115  4115 V BluetoothAdapterState: isTurningOn()=false
,08-24 16:54:58.620  4115  4115 V BluetoothAdapterState: isBleTurningOn()=true
08-24 16:54:58.620  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:58.621  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-24 16:54:58.622  4115  4127 I bt_bluedroid: enable
,08-24 16:54:58.622  4115  4128 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-24 16:54:58.623  4115  4128 I bt_hci  : start_up
,08-24 16:54:58.628  4115  4128 I bt_vendor: alloc value 0xb39ba189
,08-24 16:54:58.629  4115  4128 I bt_vendor: init
08-24 16:54:58.629  4115  4128 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-24 16:54:58.629  4115  4128 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 16:54:58.735  4115  4128 D bt_hci  : start_up starting async portion
,08-24 16:54:58.736  4115  4135 I bt_hci  : event_finish_startup
08-24 16:54:58.736  4115  4135 I bt_hci_h4: hal_open
,08-24 16:54:58.736  4115  4135 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 16:54:58.751  4115  4135 I bt_userial_vendor: device fd = 51 open
,08-24 16:54:58.777  4115  4135 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 16:54:58.809  4115  4135 D bt_hwcfg: Chipset BCM4354A2
08-24 16:54:58.809  4115  4135 D bt_hwcfg: Target name = [BCM4354A2]
,08-24 16:54:58.810  4115  4135 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 16:54:59.518  4115  4135 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 16:54:59.520  4115  4135 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 16:54:59.521  4115  4135 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 16:54:59.638  4115  4135 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 16:54:59.640  4115  4135 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 16:54:59.668  4115  4135 I bt_hwcfg: vendor lib fwcfg completed
,08-24 16:54:59.668  4115  4135 I bt_vendor: firmware callback
,08-24 16:54:59.668  4115  4135 I bt_hci  : firmware_config_callback
,08-24 16:54:59.680  4115  4138 I bt_btu  : btu_task pending for preload complete event
,08-24 16:54:59.680  4115  4138 I bt_btu_task: Bluetooth chip preload is complete
08-24 16:54:59.681  4115  4138 I bt_btu  : btu_task received preload complete event
,08-24 16:54:59.693  4115  4138 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 16:54:59.693  4115  4138 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 16:54:59.693  4115  4138 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 16:54:59.694  4115  4138 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 16:54:59.694  4115  4138 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 16:54:59.694  4115  4138 I         : BTE_InitTraceLevels -- TRC_A2D
,08-24 16:54:59.695  4115  4138 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-24 16:54:59.696  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 16:54:59.696  4115  4138 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 16:54:59.696  4115  4138 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 16:54:59.697  4115  4138 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 16:54:59.697  4115  4138 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 16:54:59.697  4115  4138 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 16:54:59.697  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 16:54:59.698  4115  4138 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 16:54:59.830  4115  4138 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,08-24 16:54:59.830  4115  4138 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,08-24 16:54:59.843  4115  4131 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 16:54:59.846  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 16:54:59.847  4115  4131 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 16:54:59.850  4115  4131 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 16:54:59.853  4115  4131 D BluetoothAdapterProperties: Scan Mode:20
,08-24 16:54:59.853  4115  4131 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 16:54:59.854  4115  4131 D bt_hci  : do_postload posting postload work item
,08-24 16:54:59.854  4115  4135 I bt_hci  : event_postload
,08-24 16:54:59.854  4115  4135 I bt_vendor: sco_config_cb
08-24 16:54:59.854  4115  4135 I bt_hci  : sco_config_callback postload finished.
,08-24 16:54:59.857  4115  4131 D bt_bte_conf: Device ID record 1 : primary
,08-24 16:54:59.857  4115  4131 D bt_bte_conf:   vendorId            = 000f
08-24 16:54:59.857  4115  4131 D bt_bte_conf:   vendorIdSource      = 0001
,08-24 16:54:59.858  4115  4131 D bt_bte_conf:   product             = 1200
,08-24 16:54:59.858  4115  4131 D bt_bte_conf:   version             = 1436
08-24 16:54:59.858  4115  4131 D bt_bte_conf:   clientExecutableURL = 
,08-24 16:54:59.858  4115  4131 D bt_bte_conf:   serviceDescription  = 
08-24 16:54:59.858  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:59.858  4115  4131 D bt_bte_conf:   documentationURL    = 
08-24 16:54:59.859  4115  4131 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-24 16:54:59.859  4115  4128 D bt_stack_manager: event_start_up_stack finished
08-24 16:54:59.861  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 16:54:59.862  4115  4127 D BluetoothAdapterProperties: Setting state to 15,
08-24 16:54:59.862  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 16:54:59.862  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:59.862  4115  4135 I bt_vendor: low_power_mode_cb
,08-24 16:54:59.863  4115  4127 I BluetoothAdapterState: Entering BleOnState
08-24 16:54:59.869  4115  4127 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 16:54:59.869  4115  4127 D BluetoothAdapterProperties: Setting state to 11
08-24 16:54:59.869  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11,
,08-24 16:54:59.883  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:59.886  4115  4115 D HeadsetService: Received start request. Starting profile...
,08-24 16:54:59.893  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:59.893  4115  4115 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 16:54:59.894  4115  4115 D HeadsetStateMachine: make
08-24 16:54:59.894  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:54:59.900  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-24 16:54:59.901  4115  4115 D HeadsetStateMachine: max_hf_connections = 1
,08-24 16:54:59.903  4115  4115 I bt_bluedroid: get_profile_interface handsfree
08-24 16:54:59.903  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-24 16:54:59.903  4115  4131 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-24 16:54:59.908  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:59.909  4115  4115 D A2dpService: Received start request. Starting profile...
08-24 16:54:59.909  4115  4115 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 16:54:59.910  4115  4115 I bt_bluedroid: get_profile_interface avrcp
,08-24 16:54:59.915  4115  4115 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 16:54:59.915  4115  4115 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 16:54:59.915  4115  4115 D A2dpStateMachine: make
,08-24 16:54:59.916  4115  4115 I bt_bluedroid: get_profile_interface a2dp
,08-24 16:54:59.917  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 16:54:59.921  4115  4147 D A2dpStateMachine: Enter Disconnected: -2
,08-24 16:54:59.921  4115  4115 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 16:54:59.922  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:59.923  4115  4115 D HidService: Received start request. Starting profile...
08-24 16:54:59.923  4115  4115 I bt_bluedroid: get_profile_interface hidhost
08-24 16:54:59.924  4115  4115 D HidService: setHidService(): set to: null
08-24 16:54:59.924  4115  4131 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
08-24 16:54:59.924  3917  3917 D BluetoothInputDevice: Proxy object connected
,08-24 16:54:59.924  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 16:54:59.924  4115  4115 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 16:54:59.925  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:59.925  4115  4115 D HealthService: Received start request. Starting profile...
08-24 16:54:59.926  3917  3917 D HidProfile: Bluetooth service connected
,08-24 16:54:59.927  4115  4115 I bt_bluedroid: get_profile_interface health
,08-24 16:54:59.927  4115  4115 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 16:54:59.928  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:54:59.929  4115  4115 D PanService: Received start request. Starting profile...
,08-24 16:54:59.929  3917  3917 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:54:59.929  4115  4115 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-24 16:54:59.929  4115  4115 I bt_bluedroid: get_profile_interface pan
08-24 16:54:59.930  4115  4131 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 16:54:59.932  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
08-24 16:54:59.934  4115  4115 D BluetoothMapService: Received start request. Starting profile...
08-24 16:54:59.934  4115  4115 D BluetoothMapService: start()
,08-24 16:54:59.936  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 16:54:59.937  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 16:54:59.937  4115  4115 D BluetoothMapAppObserver: createReceiver()
,08-24 16:54:59.938  4115  4115 D BluetoothMapAppObserver: initObservers()
,08-24 16:54:59.938  4115  4115 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 16:54:59.943  3917  3917 D PanProfile: Bluetooth service connected
,08-24 16:54:59.943  3917  3917 D BluetoothMap: Proxy object connected
08-24 16:54:59.944  3917  3917 D MapProfile: Bluetooth service connected
,08-24 16:54:59.944  3917  3917 D BluetoothMap: getConnectedDevices()
08-24 16:54:59.945  3917  3917 D BluetoothMap: Bluetooth is Not enabled
,08-24 16:54:59.948  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:54:59.948  4115  4145 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-24 16:54:59.948  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:59.948  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.949  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:59.949  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:59.951  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:59.951  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.951  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:59.952  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:59.952  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:59.952  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.952  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:59.953  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:54:59.953  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:54:59.953  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.953  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:59.953  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:59.954  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-24 16:54:59.954  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:54:59.955  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:54:59.956  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 16:54:59.956  4115  4127 D BluetoothAdapterProperties: ScanMode =  20
08-24 16:54:59.956  4115  4127 D BluetoothAdapterProperties: State =  11
08-24 16:54:59.957  4115  4127 D BluetoothAdapterProperties: Setting state to 12
08-24 16:54:59.957  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 16:54:59.958  1369  2099 D BluetoothMap: onBluetoothStateChange: up=true
08-24 16:54:59.958  4115  4131 D BluetoothAdapterProperties: Scan Mode:21
08-24 16:54:59.958  4115  4131 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 16:54:59.959  4115  4127 I BluetoothAdapterState: Entering OnState
08-24 16:54:59.960   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:54:59.960  1369  1369 D BluetoothMap: Proxy object connected
08-24 16:54:59.960  1369  2105 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:54:59.960  1369  1369 D MapProfile: Bluetooth service connected
08-24 16:54:59.960  1369  1369 D BluetoothMap: getConnectedDevices()
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:59.962  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:59.962  3917  3930 D BluetoothMap: onBluetoothStateChange: up=true
08-24 16:54:59.962  1369  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 16:54:59.963  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 16:54:59.964  4115  4115 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-24 16:54:59.964  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:54:59.964  1369  1369 D BluetoothInputDevice: Proxy object connected
08-24 16:54:59.964  1369  1369 D HidProfile: Bluetooth service connected
08-24 16:54:59.964  1369  1385 D BluetoothPan: onBluetoothStateChange on: true
08-24 16:54:59.965  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:54:59.966  1369  1381 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 16:54:59.966  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:54:59.966  1369  1369 D PanProfile: Bluetooth service connected
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:54:59.967  3844  3,844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:54:59.967  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:54:59.967  1369  2105 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:54:59.968  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 16:54:59.968  3917  3929 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 16:54:59.968   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:54:59.968  1954  2114 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:54:59.969  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:54:59.969   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:54:59.969  4115  4115 D ObexServerSockets: Succeed to create listening sockets 
08-24 16:54:59.969  3917  3930 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 16:54:59.969  4115  4115 D ObexServerSockets0: startAccept()
08-24 16:54:59.969  4115  4115 D ObexServerSockets0: prepareForNewConnect()
08-24 16:54:59.970   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:54:59.971  3917  3929 D BluetoothPan: onBluetoothStateChange on: true
08-24 16:54:59.971  4115  4115 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 16:54:59.971  4115  4115 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 16:54:59.972  4115  4153 D ObexServerSockets0: Accepting socket connection...
08-24 16:54:59.973  4115  4154 D ObexServerSockets0: Accepting socket connection...
08-24 16:54:59.973   873   873 D BluetoothA2dp: Proxy object connected
08-24 16:54:59.974  4115  4115 D BluetoothMapService: onReceive
08-24 16:54:59.974  4115  4115 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:54:59.975  4115  4115 D BluetoothMapService: STATE_ON
08-24 16:54:59.975  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:59.976  1369  1369 D BluetoothA2dp: Proxy object connected
08-24 16:54:59.976  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:54:59.977   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 16:54:59.978  3917  3917 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-24 16:54:59.981  3917  3917 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 16:54:59.986  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 16:54:59.988  3917  3917 D BluetoothA2dp: Proxy object connected
,08-24 16:54:59.993  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:54:59.999  1369  1369 D BluetoothPbap: Proxy object connected
,08-24 16:54:59.999  1369  1369 D PbapServerProfile: Bluetooth service connected
,08-24 16:54:59.999  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 16:54:59.999  4115  4115 D ObexServerSockets0: prepareForNewConnect()
,08-24 16:55:00.000  3917  3917 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:55:00.001  3917  3917 D BluetoothPbap: Proxy object connected
,08-24 16:55:00.002  3917  3917 D PbapServerProfile: Bluetooth service connected
,08-24 16:55:00.014  4115  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:00.028  4115  4164 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:00.030  4115  4164 I BtOppRfcommListener: Accept thread started.
,08-24 16:55:00.062   873   873 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.062  1369  1385 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.062  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-24 16:55:00.063  1954  1966 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.063   873   873 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.063   873   873 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.068  1369  1381 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.068   873   890 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.068  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-24 16:55:00.069  1954  2120 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.069   873   890 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.084  3917  3930 D BluetoothHeadset: Proxy object connected
,08-24 16:55:00.084  3917  3917 D HeadsetProfile: Bluetooth service connected
,08-24 16:55:01.314   873  1313 D ConnectivityService: handlePromptUnvalidated 101
,08-24 16:55:01.377  4115  4127 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 16:55:01.377  4115  4127 D BluetoothAdapterProperties: Setting state to 13
,08-24 16:55:01.377  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-24 16:55:01.380  4115  4127 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 16:55:01.387  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
,08-24 16:55:01.392  4115  4115 D BluetoothMapService: onReceive
,08-24 16:55:01.392  4115  4115 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 16:55:01.392  4115  4115 D BluetoothMapService: STATE_TURNING_OFF
,08-24 16:55:01.393  4115  4115 D BluetoothMapService: MAP Service closeService in
08-24 16:55:01.394  4115  4115 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 16:55:01.394  4115  4115 D ObexServerSockets0: shutdown(block = true)
,08-24 16:55:01.397  4115  4153 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-24 16:55:01.398  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:01.398  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:55:01.400  4115  4131 D BluetoothAdapterProperties: Scan Mode:20
,08-24 16:55:01.400  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 16:55:01.401  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:55:01.401  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:55:01.404  4115  4115 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 16:55:01.405  4115  4154 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 16:55:01.407  4115  4141 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 16:55:01.407  4115  4115 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 16:55:01.408  4115  4115 D HeadsetService: Received stop request...Stopping profile...
08-24 16:55:01.408  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:01.409  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 16:55:01.410   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 16:55:01.410  1369  1381 D BluetoothHeadset: Proxy object disconnected
08-24 16:55:01.410  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 16:55:01.410  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:55:01.410  1954  1965 D BluetoothHeadset: Proxy object disconnected
08-24 16:55:01.411  4115  4115 D A2dpService: Received stop request...Stopping profile...
,08-24 16:55:01.411   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 16:55:01.411   873   873 D BluetoothHeadset: Proxy object disconnected
,08-24 16:55:01.411  4115  4147 D A2dpStateMachine: Exit Disconnected: -1
08-24 16:55:01.412  3917  3929 D BluetoothHeadset: Proxy object disconnected
08-24 16:55:01.413   873   873 D BluetoothA2dp: Proxy object disconnected
,08-24 16:55:01.414  4115  4115 I BtOppRfcommListener: stopping Accept Thread
08-24 16:55:01.414  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:01.415  4115  4164 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 16:55:01.415  4115  4164 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 16:55:01.415  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:01.416  1369  1369 D HeadsetProfile: Bluetooth service disconnected
08-24 16:55:01.416  1369  1369 D BluetoothA2dp: Proxy object disconnected
,08-24 16:55:01.416  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 16:55:01.417  4115  4115 D HidService: Received stop request...Stopping profile...
08-24 16:55:01.417  4115  4115 D HidService: Stopping Bluetooth HidService
08-24 16:55:01.419  4115  4115 V BluetoothAdapterState: isTurningOff()=true
08-24 16:55:01.419  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.419  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:01.420  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.420  1369  1369 D BluetoothInputDevice: Proxy object disconnected
08-24 16:55:01.420  1369  1369 D HidProfile: Bluetooth service disconnected
08-24 16:55:01.421  3917  3917 D HeadsetProfile: Bluetooth service disconnected
08-24 16:55:01.421  4115  4115 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 16:55:01.421  3917  3917 D BluetoothA2dp: Proxy object disconnected
08-24 16:55:01.421  4115  4115 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 16:55:01.421  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 16:55:01.421  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:55:01.421  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:55:01.421  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 16:55:01.422  4115  4131 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-24 16:55:01.422  4115  4115 D HealthService: Received stop request...Stopping profile...
,08-24 16:55:01.424  4115  4115 V BluetoothAdapterState: isTurningOff()=true
08-24 16:55:01.424  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.425  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:55:01.425  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.425  4115  4115 D PanService: Received stop request...Stopping profile...,
08-24 16:55:01.425  3917  3917 D DockEventReceiver: finishStartingService: stopping service
08-24 16:55:01.427  3917  3917 D BluetoothInputDevice: Proxy object disconnected
,08-24 16:55:01.426  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 16:55:01.427  3917  3917 D HidProfile: Bluetooth service disconnected
08-24 16:55:01.427  1369  1369 D PanProfile: Bluetooth service disconnected
,08-24 16:55:01.427  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 16:55:01.427  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 16:55:01.427  4115  4138 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 16:55:01.427  4115  4138 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 16:55:01.428  4115  4138 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 16:55:01.428  4115  4138 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 16:55:01.428  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-24 16:55:01.428  4115  4115 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 16:55:01.428  4115  4115 D BluetoothMapService: stop()
08-24 16:55:01.430  4115  4115 D BluetoothMapAppObserver: deinitObservers()
08-24 16:55:01.430  4115  4115 D BluetoothMapAppObserver: removeReceiver()
,08-24 16:55:01.430  3917  3917 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 16:55:01.431  3917  3917 D PanProfile: Bluetooth service disconnected
08-24 16:55:01.431  3917  3917 D BluetoothMap: Proxy object disconnected
,08-24 16:55:01.431  3917  3917 D MapProfile: Bluetooth service disconnected
,08-24 16:55:01.431  1369  1369 D BluetoothMap: Proxy object disconnected
,08-24 16:55:01.432  1369  1369 D MapProfile: Bluetooth service disconnected
08-24 16:55:01.433  4115  4115 V BluetoothAdapterState: isTurningOff()=true
08-24 16:55:01.433  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.433  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:01.433  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.433  4115  4115 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 16:55:01.433  4115  4131 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 16:55:01.434  4115  4115 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 16:55:01.438  4115  4115 V BluetoothAdapterState: isTurningOff()=true
,08-24 16:55:01.438  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.438  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:01.438  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.438  4115  4115 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 16:55:01.439  4115  4131 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 16:55:01.439  4115  4115 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-24 16:55:01.439  4115  4115 V BluetoothAdapterState: isTurningOff()=true
08-24 16:55:01.439  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.439  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:55:01.439  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.440  4115  4115 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 16:55:01.440  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 16:55:01.440  4115  4115 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 16:55:01.442  4115  4115 D BluetoothMapService: MAP Service closeService in
08-24 16:55:01.442  4115  4115 V BluetoothAdapterState: isTurningOff()=true
08-24 16:55:01.442  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:01.442  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:01.442  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:01.443  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 16:55:01.443  4115  4127 D BluetoothAdapterProperties: Setting state to 15
08-24 16:55:01.444  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 16:55:01.444  4115  4127 I BluetoothAdapterState: Entering BleOnState
08-24 16:55:01.444  3917  3930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.444  4115  4115 D BluetoothMapService: cleanup()
08-24 16:55:01.445  4115  4115 D BluetoothMapService: MAP Service closeService in
08-24 16:55:01.445  1369  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-24 16:55:01.445   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.446  1369  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:55:01.447  3917  3929 D BluetoothMap: onBluetoothStateChange: up=false
08-24 16:55:01.448  3917  3917 D BluetoothPbap: Proxy object disconnected
08-24 16:55:01.448  3917  3917 D PbapServerProfile: Bluetooth service disconnected
08-24 16:55:01.448  1369  1369 D BluetoothPbap: Proxy object disconnected
08-24 16:55:01.448  1369  1369 D PbapServerProfile: Bluetooth service disconnected
08-24 16:55:01.448  1369  2099 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 16:55:01.448  1369  2105 D BluetoothPan: onBluetoothStateChange on: false
08-24 16:55:01.449  1369  1381 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 16:55:01.451  3917  3930 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:55:01.452  1369  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.452  3917  3929 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 16:55:01.452   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.453  1954  2114 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.453   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 16:55:01.453  3917  4169 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 16:55:01.455   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 16:55:01.455  3917  3930 D BluetoothPan: onBluetoothStateChange on: false
08-24 16:55:01.455  4115  4127 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 16:55:01.455  4115  4127 D BluetoothAdapterProperties: Setting state to 16
,08-24 16:55:01.455  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 16:55:01.456  4115  4127 D BluetoothAdapterProperties: onBleDisable
08-24 16:55:01.456  4115  4127 I BluetoothAdapterState: Entering PendingCommandState
08-24 16:55:01.456  4115  4128 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-24 16:55:01.457  4115  4138 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 16:55:01.457  4115  4138 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 16:55:01.461  4115  4131 D BluetoothAdapterProperties: Scan Mode:20
,08-24 16:55:01.462  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:01.463  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:01.463  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 16:55:01.464  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:01.465  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:01.467  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:55:01.472  3917  3917 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:55:01.657  4115  4131 I bt_hci  : shut_down
,08-24 16:55:01.658  4115  4135 D bt_hwcfg: hw_epilog_process
,08-24 16:55:01.659  4115  4135 I bt_vendor: low_power_mode_cb
,08-24 16:55:01.685  4115  4135 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 16:55:01.686  4115  4135 I bt_vendor: epilog_cb
08-24 16:55:01.686  4115  4135 I bt_hci  : epilog_finished_callback
,08-24 16:55:01.690  4115  4131 I bt_hci_h4: hal_close
,08-24 16:55:01.690  4115  4131 I bt_userial_vendor: device fd = 51 close
,08-24 16:55:01.739  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:55:01.750  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:55:01.756  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:55:01.808  4115  4128 D bt_stack_manager: event_shut_down_stack finished.
,08-24 16:55:01.809  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-24 16:55:01.811  1497  4017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 16:55:01.811  1497  4017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 16:55:01.811  1497  4017 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:55:01.811  1497  4017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 16:55:01.812  4115  4115 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 16:55:01.813  4115  4115 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 16:55:01.813  4115  4115 D BtGatt.GattService: stop()
08-24 16:55:01.813  4115  4115 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 16:55:01.813  4115  4127 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 16:55:01.819  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-24 16:55:01.819  4115  4115 V BluetoothAdapterState: isTurningOn()=false
,08-24 16:55:01.819  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:01.819  4115  4115 V BluetoothAdapterState: isBleTurningOff()=true
08-24 16:55:01.820  4115  4127 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 16:55:01.820  4115  4127 D BluetoothAdapterProperties: Setting state to 10
08-24 16:55:01.820  4115  4127 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-24 16:55:01.820  4115  4127 I BluetoothAdapterState: Entering OffState
08-24 16:55:01.821   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 16:55:01.838  4115  4115 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 16:55:01.838  4115  4115 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-24 16:55:01.839  4115  4128 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 16:55:01.843  4115  4128 D bt_stack_manager: event_clean_up_stack finished.
08-24 16:55:01.843  4115  4115 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 16:55:01.844  4115  4115 I art     : System.exit called, status: 0
,08-24 16:55:01.845  4115  4115 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 16:55:01.847  3537  3537 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 16:55:01.847  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 16:55:01.849  3537  3537 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-24 16:55:01.872   873   882 I art     : Background partial concurrent mark sweep GC freed 60884(3MB) AllocSpace objects, 11(300KB) LOS objects, 33% free, 29MB/43MB, paused 2.726ms total 107.859ms
,08-24 16:55:01.944   873  2279 I ActivityManager: Process com.android.bluetooth (pid 4115) has died
,08-24 16:55:04.330   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 16:55:04.340  1888  1888 I Keyboard.Facilitator: onFinishInput()
,08-24 16:55:04.345   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 16:55:04.345   873   893 I Adreno  : Build Date                       : 10/20/15
08-24 16:55:04.345   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 16:55:04.345   873   893 I Adreno  : Local Branch                     : M14
08-24 16:55:04.345   873   893 I Adreno  : Remote Branch                    : 
08-24 16:55:04.345   873   893 I Adreno  : Remote Branch                    : 
08-24 16:55:04.345   873   893 I Adreno  : Reconstruct Branch               : 
,08-24 16:55:04.374  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:55:04.376  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:04.378   280   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
,08-24 16:55:05.033  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 16:55:05.034  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 16:55:05.069   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-24 16:55:05.076   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 16:55:05.075  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8756ca5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d418bc7, 16908290=android.view.AbsSavedState$1@d418bc7}, android:focusedViewId=100}]}]
,08-24 16:55:05.076  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 16:55:05.079  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 16:55:05.079  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 16:55:05.081   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 16:55:05.093   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-24 16:55:05.093   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 16:55:05.345   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 16:55:05.350   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
,08-24 16:55:05.351   873  1337 D SurfaceControl: Excessive delay in setPowerMode(): 270ms
08-24 16:55:05.355   873   893 I DreamManagerService: Entering dreamland.
08-24 16:55:05.356   873   893 I PowerManagerService: Dozing...
,08-24 16:55:05.357   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 16:55:05.425   376  1319 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-24 16:55:05.425   376  1319 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 16:55:05.434   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 16:55:05.438   873  1311 E native  : do suspend false
,08-24 16:55:05.455  1942  4177 D NfcService: Discovery configuration equal, not updating.
,08-24 16:55:05.480   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 16:55:05.483   873  1311 E native  : do suspend true
,08-24 16:55:05.562   376  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-24 16:55:05.562   376  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-24 16:55:07.382  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:07.383  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6955f4 added. We now have 6 listener(s)
08-24 16:55:07.383  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:07.387  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:07.388  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c2211d added. We now have 7 listener(s)
,08-24 16:55:07.388  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:55:07.389  3844  3896 I System.out: IsBluetoothEnabled
,08-24 16:55:07.401  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:07.449   873   890 I ActivityManager: Start proc 4184:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 16:55:07.563  4184  4184 D AdapterServiceConfig: Adding HeadsetService
,08-24 16:55:07.564  4184  4184 D AdapterServiceConfig: Adding A2dpService
08-24 16:55:07.564  4184  4184 D AdapterServiceConfig: Adding HidService
,08-24 16:55:07.564  4184  4184 D AdapterServiceConfig: Adding HealthService
08-24 16:55:07.564  4184  4184 D AdapterServiceConfig: Adding PanService
08-24 16:55:07.565  4184  4184 D AdapterServiceConfig: Adding GattService
,08-24 16:55:07.565  4184  4184 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 16:55:07.583   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@164b219:true
,08-24 16:55:07.585  4184  4184 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 16:55:07.593  4184  4196 I BluetoothAdapterState: Entering OffState
,08-24 16:55:07.593  4184  4184 I bt_bluedroid: init
,08-24 16:55:07.598  4184  4197 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 16:55:07.599  4184  4197 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 16:55:07.600  4184  4197 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 16:55:07.601  4184  4197 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 16:55:07.603  4184  4184 I bt_bluedroid: get_profile_interface socket
,08-24 16:55:07.606  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 16:55:07.608  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6,
,08-24 16:55:07.609  4184  4184 I bt_bluedroid: get_profile_interface sdp
,08-24 16:55:07.615  4184  4195 I bt_bluedroid: config_hci_snoop_log
,08-24 16:55:07.618   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 16:55:07.626  4184  4196 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 16:55:07.627  4184  4196 D BluetoothAdapterProperties: Setting state to 14
08-24 16:55:07.627  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 16:55:07.629  4184  4196 D BluetoothBondStateMachine: make
,08-24 16:55:07.633  4184  4201 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 16:55:07.637  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-24 16:55:07.639  4184  4184 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 16:55:07.643  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:55:07.644  4184  4184 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 16:55:07.645  4184  4184 D BtGatt.GattService: Received start request. Starting profile...
08-24 16:55:07.645  4184  4184 D BtGatt.GattService: start()
08-24 16:55:07.645  4184  4184 I bt_bluedroid: get_profile_interface gatt
,08-24 16:55:07.646  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
08-24 16:55:07.647  4184  4184 D BtGatt.AdvertiseManager: advertise manager created
,08-24 16:55:07.659  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:55:07.659  4184  4184 V BluetoothAdapterState: isTurningOn()=false
08-24 16:55:07.659  4184  4184 V BluetoothAdapterState: isBleTurningOn()=true
08-24 16:55:07.659  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:07.660  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-24 16:55:07.661  4184  4196 I bt_bluedroid: enable
08-24 16:55:07.661  4184  4197 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 16:55:07.662  4184  4197 I bt_hci  : start_up
,08-24 16:55:07.684  4184  4197 I bt_vendor: alloc value 0xb39ba189
,08-24 16:55:07.684  4184  4197 I bt_vendor: init
08-24 16:55:07.684  4184  4197 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 16:55:07.685  4184  4197 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 16:55:07.792  4184  4197 D bt_hci  : start_up starting async portion
,08-24 16:55:07.792  4184  4204 I bt_hci  : event_finish_startup
08-24 16:55:07.793  4184  4204 I bt_hci_h4: hal_open
08-24 16:55:07.793  4184  4204 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 16:55:07.802  4184  4204 I bt_userial_vendor: device fd = 51 open
,08-24 16:55:07.834  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 16:55:07.865  4184  4204 D bt_hwcfg: Chipset BCM4354A2
08-24 16:55:07.866  4184  4204 D bt_hwcfg: Target name = [BCM4354A2]
,08-24 16:55:07.866  4184  4204 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 16:55:08.507  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 16:55:08.508  4184  4204 D bt_hwcfg: Settlement delay -- 100 ms
,08-24 16:55:08.508  4184  4204 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 16:55:08.626  4184  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 16:55:08.627  4184  4204 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 16:55:08.656  4184  4204 I bt_hwcfg: vendor lib fwcfg completed
,08-24 16:55:08.656  4184  4204 I bt_vendor: firmware callback
08-24 16:55:08.656  4184  4204 I bt_hci  : firmware_config_callback
,08-24 16:55:08.669  4184  4206 I bt_btu  : btu_task pending for preload complete event
,08-24 16:55:08.669  4184  4206 I bt_btu_task: Bluetooth chip preload is complete
08-24 16:55:08.669  4184  4206 I bt_btu  : btu_task received preload complete event
,08-24 16:55:08.679  4184  4206 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 16:55:08.679  4184  4206 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 16:55:08.680  4184  4206 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 16:55:08.681  4184  4206 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 16:55:08.681  4184  4206 I         : BTE_InitTraceLevels -- TRC_AVRC
08-24 16:55:08.681  4184  4206 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 16:55:08.681  4184  4206 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-24 16:55:08.682  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 16:55:08.682  4184  4206 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 16:55:08.682  4184  4206 I         : BTE_InitTraceLevels -- TRC_PAN
,08-24 16:55:08.682  4184  4206 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 16:55:08.683  4184  4206 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 16:55:08.683  4184  4206 I         : BTE_InitTraceLevels -- TRC_SMP
,08-24 16:55:08.683  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 16:55:08.684  4184  4206 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 16:55:08.819  4184  4206 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3937d9d
,08-24 16:55:08.820  4184  4206 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3937d9d 
,08-24 16:55:08.839  4184  4200 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 16:55:08.841  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 16:55:08.842  4184  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 16:55:08.844  4184  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 16:55:08.848  4184  4200 D BluetoothAdapterProperties: Scan Mode:20
,08-24 16:55:08.848  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 16:55:08.849  4184  4200 D bt_hci  : do_postload posting postload work item
,08-24 16:55:08.850  4184  4204 I bt_hci  : event_postload
,08-24 16:55:08.850  4184  4204 I bt_vendor: sco_config_cb
,08-24 16:55:08.850  4184  4204 I bt_hci  : sco_config_callback postload finished.
08-24 16:55:08.851  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:08.853  4184  4200 D bt_bte_conf: Device ID record 1 : primary
08-24 16:55:08.853  4184  4204 I bt_vendor: low_power_mode_cb
,08-24 16:55:08.853  4184  4200 D bt_bte_conf:   vendorId            = 000f
08-24 16:55:08.853  4184  4200 D bt_bte_conf:   vendorIdSource      = 0001
,08-24 16:55:08.853  4184  4200 D bt_bte_conf:   product             = 1200
08-24 16:55:08.853  4184  4200 D bt_bte_conf:   version             = 1436
,08-24 16:55:08.854  4184  4200 D bt_bte_conf:   clientExecutableURL = 
08-24 16:55:08.854  4184  4200 D bt_bte_conf:   serviceDescription  = 
08-24 16:55:08.854  4184  4200 D bt_bte_conf:   documentationURL    = ,
08-24 16:55:08.854  4184  4200 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 16:55:08.855  4184  4197 D bt_stack_manager: event_start_up_stack finished,
08-24 16:55:08.857  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 16:55:08.857  4184  4196 D BluetoothAdapterProperties: Setting state to 15
,08-24 16:55:08.858  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 16:55:08.859  4184  4196 I BluetoothAdapterState: Entering BleOnState
,08-24 16:55:08.863  4184  4196 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 16:55:08.863  4184  4196 D BluetoothAdapterProperties: Setting state to 11
08-24 16:55:08.863  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 16:55:08.871  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:08.880  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:55:08.881  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:55:08.881  4184  4184 D HeadsetService: Received start request. Starting profile...
08-24 16:55:08.885  4184  4184 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 16:55:08.885  4184  4184 D HeadsetStateMachine: make
,08-24 16:55:08.891  4184  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-24 16:55:08.893  4184  4184 D HeadsetStateMachine: max_hf_connections = 1
,08-24 16:55:08.893  4184  4184 I bt_bluedroid: get_profile_interface handsfree
,08-24 16:55:08.893  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-24 16:55:08.893  4184  4200 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 16:55:08.897  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:55:08.898  4184  4184 D A2dpService: Received start request. Starting profile...
,08-24 16:55:08.898  4184  4184 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 16:55:08.899  4184  4184 I bt_bluedroid: get_profile_interface avrcp
,08-24 16:55:08.905  4184  4184 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 16:55:08.905  4184  4184 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-24 16:55:08.905  4184  4184 D A2dpStateMachine: make
,08-24 16:55:08.906  4184  4184 I bt_bluedroid: get_profile_interface a2dp
,08-24 16:55:08.907  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 16:55:08.908  4184  4215 D A2dpStateMachine: Enter Disconnected: -2
,08-24 16:55:08.909  4184  4184 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 16:55:08.910  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
08-24 16:55:08.911  4184  4184 D HidService: Received start request. Starting profile...
,08-24 16:55:08.911  4184  4184 I bt_bluedroid: get_profile_interface hidhost
08-24 16:55:08.911  4184  4200 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39193e5
,08-24 16:55:08.911  4184  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 16:55:08.911  4184  4184 D HidService: setHidService(): set to: null
,08-24 16:55:08.912  4184  4184 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 16:55:08.913  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:55:08.913  4184  4184 D HealthService: Received start request. Starting profile...
,08-24 16:55:08.915  4184  4184 I bt_bluedroid: get_profile_interface health
08-24 16:55:08.915  4184  4184 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-24 16:55:08.916  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
08-24 16:55:08.917  4184  4184 D PanService: Received start request. Starting profile...
08-24 16:55:08.917  4184  4184 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-24 16:55:08.917  4184  4184 I bt_bluedroid: get_profile_interface pan
08-24 16:55:08.918  4184  4200 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 16:55:08.921  4184  4184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
,08-24 16:55:08.922  4184  4184 D BluetoothMapService: Received start request. Starting profile...
08-24 16:55:08.922  4184  4184 D BluetoothMapService: start()
,08-24 16:55:08.925  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 16:55:08.926  4184  4184 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 16:55:08.926  4184  4184 D BluetoothMapAppObserver: createReceiver()
,08-24 16:55:08.927  4184  4184 D BluetoothMapAppObserver: initObservers()
08-24 16:55:08.927  4184  4184 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 16:55:08.936  4184  4212 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-24 16:55:08.937  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-24 16:55:08.937  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.937  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 16:55:08.937  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:55:08.939  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:55:08.939  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.939  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:08.939  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isTurningOff()=false
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:08.940  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isTurningOff()=false
,08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isTurningOn()=true
08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isBleTurningOn()=false
08-24 16:55:08.941  4184  4184 V BluetoothAdapterState: isBleTurningOff()=false
08-24 16:55:08.941  4184  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 16:55:08.942  4184  4196 D BluetoothAdapterProperties: ScanMode =  20
08-24 16:55:08.942  4184  4196 D BluetoothAdapterProperties: State =  11
,08-24 16:55:08.942  4184  4196 D BluetoothAdapterProperties: Setting state to 12
08-24 16:55:08.942  4184  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 16:55:08.943  4184  4196 I BluetoothAdapterState: Entering OnState
08-24 16:55:08.944  3917  4169 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:55:08.945  4184  4200 D BluetoothAdapterProperties: Scan Mode:21
08-24 16:55:08.945  4184  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 16:55:08.945  1369  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-24 16:55:08.947   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:55:08.948  1369  2105 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 16:55:08.949  3917  3930 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 16:55:08.950  1369  1369 D BluetoothMap: Proxy object connected
08-24 16:55:08.950  1369  1369 D MapProfile: Bluetooth service connected
,08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:08.950  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:55:08.950  1369  1369 D BluetoothMap: getConnectedDevices()
,08-24 16:55:08.952  3917  3917 D BluetoothMap: Proxy object connected
08-24 16:55:08.952  3917  3917 D MapProfile: Bluetooth service connected
,08-24 16:55:08.953  1369  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 16:55:08.953  1369  1369 D BluetoothA2dp: Proxy object connected,
,08-24 16:55:08.955  1369  1385 D BluetoothPan: onBluetoothStateChange on: true
,08-24 16:55:08.955  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 16:55:08.956  1369  1369 D BluetoothInputDevice: Proxy object connected
08-24 16:55:08.956  1369  1369 D HidProfile: Bluetooth service connected
,08-24 16:55:08.956  1369  2105 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 16:55:08.958  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 16:55:08.958  3917  4169 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 16:55:08.958  4184  4184 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 16:55:08.960  3917  3917 D BluetoothMap: getConnectedDevices()
08-24 16:55:08.960  1369  2099 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 16:55:08.961  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:08.961  3917  3930 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 16:55:08.963   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 16:55:08.963  4184  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:08.963  1954  1966 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 16:55:08.964   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 16:55:08.964  3917  4169 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 16:55:08.964  4184  4184 D ObexServerSockets: Succeed to create listening sockets 
,08-24 16:55:08.964  4184  4184 D ObexServerSockets0: startAccept()
,08-24 16:55:08.964  4184  4184 D ObexServerSockets0: prepareForNewConnect()
,08-24 16:55:08.965   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 16:55:08.966   873   873 D BluetoothA2dp: Proxy object connected,
,08-24 16:55:08.966  4184  4184 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 16:55:08.966  3917  3929 D BluetoothPan: onBluetoothStateChange on: true
,08-24 16:55:08.966  4184  4184 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 16:55:08.969  4184  4222 D ObexServerSockets0: Accepting socket connection...
08-24 16:55:08.969  4184  4221 D ObexServerSockets0: Accepting socket connection...
,08-24 16:55:08.970   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 16:55:08.970  4184  4184 D BluetoothMapService: onReceive
08-24 16:55:08.970  4184  4184 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 16:55:08.971  4184  4184 D BluetoothMapService: STATE_ON
,08-24 16:55:08.971  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:08.972  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:55:08.972  1369  1369 D PanProfile: Bluetooth service connected
,08-24 16:55:08.973  3917  3917 D BluetoothA2dp: Proxy object connected
08-24 16:55:08.974  3917  3917 D BluetoothInputDevice: Proxy object connected
08-24 16:55:08.974  3917  3917 D HidProfile: Bluetooth service connected
,08-24 16:55:08.975  3917  3917 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 16:55:08.975  3917  3917 D PanProfile: Bluetooth service connected
,08-24 16:55:08.980  3917  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 16:55:08.984  3917  3917 D DockEventReceiver: finishStartingService: stopping service
,08-24 16:55:08.985  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 16:55:08.994  3917  3917 D BluetoothPbap: Proxy object connected
,08-24 16:55:08.994  3917  3917 D PbapServerProfile: Bluetooth service connected
,08-24 16:55:08.996  1369  1369 D BluetoothPbap: Proxy object connected
,08-24 16:55:08.996  1369  1369 D PbapServerProfile: Bluetooth service connected
,08-24 16:55:09.001  4184  4184 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 16:55:09.001  4184  4184 D ObexServerSockets0: prepareForNewConnect()
08-24 16:55:09.003  4184  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:09.019  4184  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 16:55:09.020  4184  4231 I BtOppRfcommListener: Accept thread started.
,08-24 16:55:09.046   873   873 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.046  1369  1385 D BluetoothHeadset: Proxy object connected
08-24 16:55:09.046  1369  1369 D HeadsetProfile: Bluetooth service connected
08-24 16:55:09.047  1954  2120 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.047   873   873 D BluetoothHeadset: Proxy object connected
08-24 16:55:09.047   873   873 D BluetoothHeadset: Proxy object connected
08-24 16:55:09.048   873   890 D BluetoothHeadset: Proxy object connected
08-24 16:55:09.048  3917  3930 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.048  3917  3917 D HeadsetProfile: Bluetooth service connected
,08-24 16:55:09.060  1369  1381 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.061  1369  1369 D HeadsetProfile: Bluetooth service connected
,08-24 16:55:09.064   873   890 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.065  1954  1965 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.066   873   890 D BluetoothHeadset: Proxy object connected
,08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:09.423  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:55:09.430  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:55:09.434  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:09.435  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92d1f92 added. We now have 8 listener(s)
,08-24 16:55:09.435  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:09.440   873  1978 D WifiService: setWifiEnabled: false pid=3844, uid=10000
08-24 16:55:09.441   873  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:55:09.453  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:09.454   873  2287 D WifiService: setWifiEnabled: true pid=3844, uid=10000
08-24 16:55:09.454   873  2287 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 16:55:09.471   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:09.489  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:55:09.495  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:55:09.505   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-24 16:55:09.506   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 16:55:09.507   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 16:55:09.508   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 16:55:09.508   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 16:55:09.508   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 16:55:09.508   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 16:55:09.523   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 16:55:09.524   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.24 rxSuccessRate=0.28 delta 1000 -> 1000
08-24 16:55:09.524   372   871 D CommandListener: Setting iface cfg
08-24 16:55:09.524   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-24 16:55:09.525   873  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-24 16:55:09.525   873  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 16:55:09.537   873  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 16:55:09.537   873  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 16:55:09.540   873  1311 E native  : do suspend true
,08-24 16:55:09.568   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-24 16:55:09.568   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:55:09.575   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 16:55:09.628   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 16:55:09.631  1445  1445 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 16:55:09.657  1855  2647 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 16:55:10.062  1445  1445 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 16:55:10.102  1445  1445 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 16:55:10.103  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 16:55:10.108   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 16:55:10.122   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 16:55:10.123   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 16:55:10.123   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:55:10.150   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 16:55:10.169   372   871 D CommandListener: Setting iface cfg
,08-24 16:55:10.170   873  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,08-24 16:55:10.179   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 16:55:10.208   873  4239 D DhcpClient: Receive thread started
,08-24 16:55:10.295   873  1311 E native  : do suspend false
,08-24 16:55:10.314   873  2111 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 16:55:10.327   873  4239 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-24 16:55:10.328   873  2111 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-24 16:55:10.331   873  2111 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 16:55:10.346   873  4239 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 16:55:10.347   873  2111 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 16:55:10.352   372   871 D CommandListener: Setting iface cfg
,08-24 16:55:10.363   873  2111 D DhcpClient: Scheduling renewal in 86399s
,08-24 16:55:10.367   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 16:55:10.370   873  1311 E native  : do suspend true
,08-24 16:55:10.400   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 16:55:10.404   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 16:55:10.406   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 16:55:10.409   873  1313 D ConnectivityService: Adding iface wlan0 to network 102
,08-24 16:55:10.418   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 16:55:10.457   873  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 16:55:10.458   873  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 16:55:10.459   873  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 16:55:10.460   873  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 16:55:10.462   873  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 16:55:10.471  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 16:55:10.474   873  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 16:55:10.476  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 16:55:10.481   873  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 16:55:10.481   873  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-24 16:55:10.481  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 16:55:10.481   873  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102],
,08-24 16:55:10.481   873  1313 D ConnectivityService:    accepting network in place of null
,08-24 16:55:10.482   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-24 16:55:10.482  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 16:55:10.483   873  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 16:55:10.484   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 16:55:10.484  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8756ca5 Bundle[{}],
08-24 16:55:10.485  3844  3896 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 16:55:10.485  3844  3896 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 16:55:10.486  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 16:55:10.486  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 16:55:10.487  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 16:55:10.488  3844  3896 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 16:55:10.493  3844  3896 I System.out: Running OutgoingSocketThread
,08-24 16:55:10.494   873  4238 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159181, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 16:55:10.494  3844  4244 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-24 16:55:10.495  3844  4244 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44633
,08-24 16:55:10.495  3844  4244 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 16:55:10.517   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:55:10.546   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 16:55:10.554   873  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 16:55:10.555   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:55:10.561   873  4237 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.238,2a00:1450:4001:815::200e
,08-24 16:55:10.563   873   890 D Tethering: MasterInitialState.processMessage what=3
08-24 16:55:10.569   873  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:10.585  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 16:55:10.587  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:10.590  1709  1709 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 16:55:10.600  1709  1709 D SystemUpdateService: onCreate
,08-24 16:55:10.603  1709  1709 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 16:55:10.618  1709  4249 I SystemUpdateService: active receiver: enabled
,08-24 16:55:10.623  1709  4249 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 16:55:10.627  1709  1709 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 16:55:10.630  1709  4249 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 16:55:10.632  1709  4249 I SystemUpdateService: now status is 0 (complete)
08-24 16:55:10.632  1709  4249 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 16:55:10.632  1709  4249 I SystemUpdateService: file has been verified
08-24 16:55:10.632  1709  4249 I SystemUpdateService: OTA package size = 12249756
08-24 16:55:10.635   873  4237 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 14:55:10 GMT], X-Android-Received-Millis=[1472050510635], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472050510610]}
,08-24 16:55:10.636   873  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 16:55:10.637   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-24 16:55:10.637   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 16:55:10.638   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 16:55:10.641  1709  2519 I iu.UploadsManager: num queued entries: 0
,08-24 16:55:10.642  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 16:55:10.644  1709  1709 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 16:55:10.645  3972  3972 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 16:55:10.650  3972  3972 D SprintDMHelper: simOperator: 
,08-24 16:55:10.651  3972  3972 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,08-24 16:55:10.654  1709  4252 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 16:55:10.655  1709  4252 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 16:55:10.670  1709  4252 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 16:55:10.696  1709  2519 I iu.UploadsManager: num updated entries: 0
,08-24 16:55:10.697  1709  2519 I iu.SyncManager: NEXT; no task
,08-24 16:55:10.699  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:55:10.703  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 16:55:10.712  1709  4249 I SystemUpdateService: showing system update notification
,08-24 16:55:10.730  1709  1709 D SystemUpdateService: onDestroy
,08-24 16:55:10.746  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 16:55:10.746  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-24 16:55:10.746  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 16:55:10.746  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 16:55:10.763  1709  4252 E MDM     : [183] SitrepService.a: Error sending sitrep.,
,08-24 16:55:10.828  2216  4255 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 16:55:11.496  3844  3896 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-24 16:55:11.496  3844  3896 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-24 16:55:11.506  3844  3896 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-24 16:55:11.508  3844  3896 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-24 16:55:11.508  3844  3896 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-24 16:55:11.515  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.515  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c11d63 added. We now have 2 listener(s)
,08-24 16:55:11.517  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.517  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.517  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.517  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:11.517  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abfdd60 added. We now have 9 listener(s)
,08-24 16:55:11.517  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:55:11.518  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 16:55:11.521  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:11.528  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:55:11.532  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:55:11.532  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:11.533  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.533  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e79a2de added. We now have 3 listener(s)
,08-24 16:55:11.538  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:11.539  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.540  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.540  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:55:11.540  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:11.541  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1e2cbf added. We now have 10 listener(s)
,08-24 16:55:11.541  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:55:11.541  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:55:11.542  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:55:11.542  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:55:11.542  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:55:11.542  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.542  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:55:11.543  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.543  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c11d63 removed from the list
,08-24 16:55:11.544  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.544  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:11.544  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abfdd60 removed from the list
08-24 16:55:11.544  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 16:55:11.545  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.546  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.546  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.548  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.548  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 16:55:11.548  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.549  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abfdd60 not in the list
,08-24 16:55:11.549  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.549  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.550  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 16:55:11.551  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:55:11.551  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.551  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1e2cbf removed from the list
,08-24 16:55:11.551  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.551  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.552  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.552  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 16:55:11.552  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e79a2de removed from the list,
,08-24 16:55:11.553   873  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-24 16:55:11.554  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.554  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c356f8c added. We now have 2 listener(s)
,08-24 16:55:11.558  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.558  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.558  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:55:11.558  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:11.558  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0556d5 added. We now have 9 listener(s)
,08-24 16:55:11.558  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-24 16:55:11.559  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:55:11.562  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:11.568  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:55:11.571  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:55:11.571  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:11.572  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.572  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e12d5db added. We now have 3 listener(s)
,08-24 16:55:11.574  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:11.575  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:55:11.575  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.575  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.575  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:55:11.576  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8ff878 added. We now have 10 listener(s)
08-24 16:55:11.576  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.576  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:55:11.576  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:55:11.577  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:55:11.577  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.577  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:55:11.579  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:11.581  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 16:55:11.581  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 16:55:11.585  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 16:55:11.586  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 16:55:11.586  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:55:11.589  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 16:55:11.590  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 16:55:11.590  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 16:55:11.590  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:55:11.594  4184  4220 D BtGatt.GattService: registerClient() - UUID=bbcfacb0-2305-4536-ac07-6bb81f68259b
,08-24 16:55:11.595  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=bbcfacb0-2305-4536-ac07-6bb81f68259b, clientIf=5
08-24 16:55:11.596  3844  3854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 16:55:11.597  4184  4223 D BtGatt.GattService: start scan with filters
,08-24 16:55:11.601  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 16:55:11.601  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 16:55:11.601  4184  4203 D BtGatt.ScanManager: handling starting scan
08-24 16:55:11.601  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 16:55:11.601  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 16:55:11.603  4184  4203 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a300ae9
08-24 16:55:11.604  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:55:11.604  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 16:55:11.604  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:55:11.606  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:55:11.609  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 16:55:11.609  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.610  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 16:55:11.612  3844  3896 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 16:55:11.612  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 16:55:11.613  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 16:55:11.613  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.613  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 16:55:11.613  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 16:55:11.613  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 16:55:11.613  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 16:55:11.613  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 16:55:11.614  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 16:55:11.614  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 16:55:11.616  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:55:11.617  4184  4220 D BtGatt.GattService: stopScan() - queue size =1
,08-24 16:55:11.618  4184  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 16:55:11.618  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 16:55:11.618  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.619  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 16:55:11.619  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 16:55:11.620  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 16:55:11.620  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 16:55:11.620  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 16:55:11.620  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
,08-24 16:55:11.620  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 16:55:11.623  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 16:55:11.623  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 16:55:11.624  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 16:55:11.624  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 16:55:11.625  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:55:11.626  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,08-24 16:55:11.626  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:55:11.626  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-24 16:55:11.630  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 16:55:11.630  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:55:11.630  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:55:11.630  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:55:11.630  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.630  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:55:11.631  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.631  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c356f8c removed from the list
,08-24 16:55:11.631  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.631  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0556d5 removed from the list
08-24 16:55:11.631  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 16:55:11.631  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.631  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.631  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.633  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:55:11.633  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.633  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.634  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0556d5 not in the list
,08-24 16:55:11.634  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.634  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.638  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 16:55:11.638  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 16:55:11.638  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.638  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:55:11.638  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.639  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8ff878 removed from the list
,08-24 16:55:11.639  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:55:11.639  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.639  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.640  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 16:55:11.640  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e12d5db removed from the list
,08-24 16:55:11.642  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.642  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c082424 added. We now have 2 listener(s)
,08-24 16:55:11.644  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 16:55:11.644  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-24 16:55:11.648  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.649  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.649  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 16:55:11.650  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:11.650  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2528b8d added. We now have 9 listener(s),
,08-24 16:55:11.650  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.651  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:55:11.652  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 16:55:11.652  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.652  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
,08-24 16:55:11.654  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:11.661  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:55:11.662  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 16:55:11.663  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.663  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.663  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:11.663  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 16:55:11.665  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.665  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:11.665  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e42553 added. We now have 3 listener(s)
,08-24 16:55:11.666  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.667  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.667  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.667  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:11.667  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:55:11.667  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db55e90 added. We now have 10 listener(s)
08-24 16:55:11.667  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.667  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:55:11.668  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 16:55:11.668  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:55:11.668  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:55:11.668  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.668  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 16:55:11.669  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 16:55:11.669  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.671  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 16:55:11.671  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 16:55:11.674  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 16:55:11.674  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 16:55:11.674  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:55:11.677  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 16:55:11.677  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 16:55:11.677  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 16:55:11.677  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:55:11.679  4184  4220 D BtGatt.GattService: registerClient() - UUID=ceceebeb-cbd7-4a2c-b30f-ea08ab874ed6
,08-24 16:55:11.679  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=ceceebeb-cbd7-4a2c-b30f-ea08ab874ed6, clientIf=5
08-24 16:55:11.679  3844  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 16:55:11.680  4184  4195 D BtGatt.GattService: start scan with filters
,08-24 16:55:11.682  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 16:55:11.682  4184  4203 D BtGatt.ScanManager: handling starting scan
08-24 16:55:11.682  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 16:55:11.682  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 16:55:11.682  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 16:55:11.684  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 16:55:11.685  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:55:11.685  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 16:55:11.686  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:55:11.687  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 16:55:11.687  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.687  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 16:55:11.689  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 16:55:11.689  3844  3896 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 16:55:11.689  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:55:11.689  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:55:11.689  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 16:55:11.690  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.690  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.690  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 16:55:11.690  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.690  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c082424 removed from the list
08-24 16:55:11.690  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.690  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2528b8d removed from the list
08-24 16:55:11.690  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:55:11.690  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:55:11.690  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.691  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 16:55:11.691  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.691  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 16:55:11.691  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.691  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.691  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.692  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2528b8d not in the list
,08-24 16:55:11.692  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:55:11.692  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 16:55:11.692  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 16:55:11.692  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:55:11.692  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 16:55:11.692  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 16:55:11.692  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.692  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
08-24 16:55:11.693  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 16:55:11.693  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:55:11.693  4184  4195 D BtGatt.GattService: stopScan() - queue size =1
,08-24 16:55:11.694  4184  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 16:55:11.695  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 16:55:11.695  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 16:55:11.695  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 16:55:11.695  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 16:55:11.695  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 16:55:11.696  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:55:11.696  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 16:55:11.696  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 16:55:11.696  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:55:11.697  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.698  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 16:55:11.698  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:55:11.698  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:55:11.698  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.698  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.698  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.699  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db55e90 removed from the list
08-24 16:55:11.699  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.699  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.699  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.699  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.699  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e42553 removed from the list
08-24 16:55:11.700  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 16:55:11.700  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d3bc added. We now have 2 listener(s)
,08-24 16:55:11.701  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.701  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:55:11.701  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.702  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:55:11.702  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0a9f45 added. We now have 9 listener(s)
,08-24 16:55:11.702  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.702  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:55:11.702  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 16:55:11.702  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.705  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.707  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 16:55:11.708  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:11.709  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:55:11.710  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 16:55:11.711  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:11.712  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.712  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b0ebcb added. We now have 3 listener(s)
,08-24 16:55:11.713  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:11.713  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 16:55:11.714  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.714  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 16:55:11.714  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 16:55:11.714  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
08-24 16:55:11.714  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-24 16:55:11.714  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:55:11.714  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e6fa8 added. We now have 10 listener(s)
08-24 16:55:11.714  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.714  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:55:11.714  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 16:55:11.715  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:11.715  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 16:55:11.715  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.715  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 16:55:11.717  3844  3896 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 16:55:11.718  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 16:55:11.721  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 16:55:11.721  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 16:55:11.721  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.722  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 16:55:11.722  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 16:55:11.722  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 16:55:11.726  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 16:55:11.726  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 16:55:11.726  3844  3896 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 16:55:11.726  3844  3896 D BluetoothAdapter: STATE_ON
,08-24 16:55:11.727  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 16:55:11.728  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.729  4184  4195 D BtGatt.GattService: registerClient() - UUID=6c4a0aa3-8bf9-41ae-a8c9-b2c63a47ac56
,08-24 16:55:11.729  4184  4200 D BtGatt.GattService: onClientRegistered() - UUID=6c4a0aa3-8bf9-41ae-a8c9-b2c63a47ac56, clientIf=5
08-24 16:55:11.729  3844  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 16:55:11.729  4184  4223 D BtGatt.GattService: start scan with filters
,08-24 16:55:11.731  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 16:55:11.731  4184  4203 D BtGatt.ScanManager: handling starting scan
,08-24 16:55:11.731  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 16:55:11.732  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 16:55:11.732  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 16:55:11.734  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 16:55:11.734  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 16:55:11.734  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 16:55:11.736  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 16:55:11.738  4184  4200 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 16:55:11.738  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.738  4184  4203 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 16:55:11.740  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:55:11.740  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 16:55:11.740  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:55:11.740  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.740  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.740  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 16:55:11.740  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.740  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9d3bc removed from the list
,08-24 16:55:11.740  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.740  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0a9f45 removed from the list
08-24 16:55:11.740  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:55:11.740  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:55:11.741  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-24 16:55:11.741  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 16:55:11.741  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.741  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.742  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0a9f45 not in the list
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 16:55:11.742  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 16:55:11.742  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 16:55:11.742  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 16:55:11.743  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 16:55:11.743  3844  3896 D BluetoothAdapter: STATE_ON
08-24 16:55:11.743  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.743  4184  4203 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 16:55:11.743  4184  4203 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 16:55:11.743  4184  4220 D BtGatt.GattService: stopScan() - queue size =1
08-24 16:55:11.744  4184  4195 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 16:55:11.744  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 16:55:11.744  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 16:55:11.744  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 16:55:11.744  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 16:55:11.744  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 16:55:11.745  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:55:11.745  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 16:55:11.745  3844  3896 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 16:55:11.745  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 16:55:11.746  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.746  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 16:55:11.747  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 16:55:11.747  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 16:55:11.747  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.747  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.747  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 16:55:11.747  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e6fa8 removed from the list
08-24 16:55:11.747  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.747  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.747  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.747  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.747  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b0ebcb removed from the list
08-24 16:55:11.748  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.748  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cede54 added. We now have 2 listener(s)
08-24 16:55:11.750  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:55:11.750  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:55:11.750  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.750  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 16:55:11.750  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca71fd added. We now have 9 listener(s)
,08-24 16:55:11.750  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 16:55:11.755  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 16:55:11.757  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 16:55:11.761  3844  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 16:55:11.762  4184  4200 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 16:55:11.762  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.763  3844  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 16:55:11.763  3844  3896 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 16:55:11.764  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 16:55:11.764  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8910943 added. We now have 3 listener(s)
08-24 16:55:11.765  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 16:55:11.767  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 16:55:11.767  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 16:55:11.767  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 16:55:11.767  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 16:55:11.767  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 16:55:11.767  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3658bc0 added. We now have 10 listener(s)
08-24 16:55:11.767  3844  3896 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 16:55:11.767  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 16:55:11.767  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.767  3844  3896 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 16:55:11.768  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 16:55:11.768  3844  3896 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 16:55:11.768  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 16:55:11.768  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.768  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 16:55:11.768  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.768  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cede54 removed from the list
08-24 16:55:11.768  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.768  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca71fd removed from the list
,08-24 16:55:11.768  3844  3896 D io.jxcore.node.ConnectivityMonitor: stop
08-24 16:55:11.768  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 16:55:11.769  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.769  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.770  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 16:55:11.770  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.770  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.770  3844  3896 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ca71fd not in the list
08-24 16:55:11.770  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.770  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.771  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 16:55:11.771  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 16:55:11.771  3844  3896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 16:55:11.771  3844  3896 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3658bc0 removed from the list
08-24 16:55:11.771  3844  3896 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 16:55:11.771  3844  3896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 16:55:11.771  3844  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 16:55:11.771  3844  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 16:55:11.772  3844  3896 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8910943 removed from the list
08-24 16:55:11.772  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 16:55:11.772  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-24 16:55:11.773  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 16:55:11.773  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 16:55:11.773  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-24 16:55:11.773  3844  3896 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 16:55:11.774  4184  4200 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 16:55:11.774  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.774  4184  4203 D BtGatt.ScanManager: stopping BLe Batch
,08-24 16:55:11.778  3844  4261 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-24 16:55:11.778  3844  4261 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-24 16:55:11.778  3844  4261 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 16:55:11.780  4184  4200 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 16:55:11.780  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 16:55:11.780  4184  4203 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 16:55:11.780  3844  4262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
08-24 16:55:11.781  3844  4262 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
,08-24 16:55:11.781  3844  4262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 16:55:11.783  3844  3896 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 16:55:11.783  3844  3896 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 16:55:11.783  3844  3896 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 16:55:11.783  3844  3896 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 16:55:11.783  3844  3896 D com.test.thalitest.ThaliTestRunner: Total duration: 22668 ms
,08-24 16:55:11.785  3844  3896 I jxcore-log: Total number of executed tests:  80
08-24 16:55:11.785  3844  3896 I jxcore-log: 
,08-24 16:55:11.785  3844  3896 I jxcore-log: Number of passed tests:  80
08-24 16:55:11.785  3844  3896 I jxcore-log: 
,08-24 16:55:11.785  3844  3896 I jxcore-log: Number of failed tests:  0
08-24 16:55:11.785  3844  3896 I jxcore-log: 
08-24 16:55:11.785  3844  3896 I jxcore-log: Number of ignored tests:  0
08-24 16:55:11.785  3844  3896 I jxcore-log: 
08-24 16:55:11.785  4184  4200 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 16:55:11.786  4184  4200 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 16:55:11.786  3844  3896 I jxcore-log: Total duration:  22668
08-24 16:55:11.786  3844  3896 I jxcore-log: 
08-24 16:55:11.786  3844  3896 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 16:55:11.786  3844  3896 I jxcore-log: 
,08-24 16:55:11.793  3844  3844 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 16:55:11.794  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.794  3844  3896 I jxcore-log: 
,08-24 16:55:11.795  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.795  3844  3896 I jxcore-log: 
08-24 16:55:11.796  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.796  3844  3896 I jxcore-log: 
08-24 16:55:11.797  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.797  3844  3896 I jxcore-log: 
08-24 16:55:11.797  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.797  3844  3896 I jxcore-log: 
08-24 16:55:11.798  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.798  3844  3896 I jxcore-log: 
08-24 16:55:11.800  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.800  3844  3896 I jxcore-log: 
08-24 16:55:11.801  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.801  3844  3896 I jxcore-log: 
08-24 16:55:11.801  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.801  3844  3896 I jxcore-log: 
08-24 16:55:11.802  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 16:55:11.802  3844  3896 I jxcore-log: 
08-24 16:55:11.803  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.803  3844  3896 I jxcore-log: 
08-24 16:55:11.803  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.803  3844  3896 I jxcore-log: 
,08-24 16:55:11.804  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.804  3844  3896 I jxcore-log: 
,08-24 16:55:11.804  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.804  3844  3896 I jxcore-log: 
08-24 16:55:11.805  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.805  3844  3896 I jxcore-log: 
08-24 16:55:11.805  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.805  3844  3896 I jxcore-log: 
08-24 16:55:11.806  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.806  3844  3896 I jxcore-log: 
08-24 16:55:11.808  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.808  3844  3896 I jxcore-log: 
08-24 16:55:11.809  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.809  3844  3896 I jxcore-log: 
,08-24 16:55:11.809  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.809  3844  3896 I jxcore-log: 
08-24 16:55:11.809  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.809  3844  3896 I jxcore-log: 
08-24 16:55:11.810  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.810  3844  3896 I jxcore-log: 
,08-24 16:55:11.811  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.811  3844  3896 I jxcore-log: 
08-24 16:55:11.811  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 16:55:11.811  3844  3896 I jxcore-log: 
,08-24 16:55:11.812  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.812  3844  3896 I jxcore-log: 
08-24 16:55:11.812  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 16:55:11.812  3844  3896 I jxcore-log: 
08-24 16:55:11.812  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.812  3844  3896 I jxcore-log: 
,08-24 16:55:11.813  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.813  3844  3896 I jxcore-log: 
08-24 16:55:11.813  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.813  3844  3896 I jxcore-log: 
,08-24 16:55:11.814  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.814  3844  3896 I jxcore-log: 
,08-24 16:55:11.814  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.814  3844  3896 I jxcore-log: 
,08-24 16:55:11.815  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 16:55:11.815  3844  3896 I jxcore-log: 
,08-24 16:55:12.128  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 16:55:12.131  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 16:55:12.131  3844  3896 I jxcore-log: 
,08-24 16:55:12.199  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 16:55:12.203  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 16:55:12.203  3844  3896 I jxcore-log: 
,08-24 16:55:12.248  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 16:55:12.251  3844  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 16:55:12.251  3844  3896 I jxcore-log: 
,08-24 16:55:12.416  4263  4263 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 16:55:12.421  4263  4263 D AndroidRuntime: CheckJNI is OFF
,08-24 16:55:12.463  4263  4263 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 16:55:12.508  4263  4263 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 16:55:12.532  4263  4263 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 16:55:12.541   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-24 16:55:12.542   873   886 I ActivityManager: Killing 3844:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-24 16:55:12.659   873   897 W PackageSettings: Skipping PackageSetting{ca059f2 com.example.hello/10273} due to missing metadata
,08-24 16:55:12.662   873  1978 D GraphicsStats: Buffer count: 2
,08-24 16:55:12.662   873  2020 I WindowState: WIN DEATH: Window{447d1f6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 16:55:12.663   873  1312 D WifiService: Client connection lost with reason: 4
,08-24 16:55:12.704   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-24 16:55:12.705   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-24 16:55:12.705   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-24 16:55:12.705   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 16:55:12.705   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:12.705   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:12.705   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 16:55:12.705   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-24 16:55:12.706   873   886 I ActivityManager:   Force finishing activity ActivityRecord{eb0601f u0 com.test.thalitest/.MainActivity t2}
,08-24 16:55:12.710   873  1978 W ActivityManager: Spurious death for ProcessRecord{1e710ba 0:com.test.thalitest/u0a0}, curProc for 3844: null
,08-24 16:55:12.716   873   897 I art     : Starting a blocking GC Explicit
,08-24 16:55:12.758   873   897 I art     : Explicit concurrent mark sweep GC freed 13719(958KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 664us total 42.138ms
,08-24 16:55:12.785   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 16:55:12.790  4263  4263 I art     : System.exit called, status: 0
,08-24 16:55:12.790  4263  4263 I AndroidRuntime: VM exiting with result code 0.
,08-24 16:55:12.796   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 16:55:12.816   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-24 16:55:12.819  4184  4184 D BluetoothMapAppObserver: onReceive
08-24 16:55:12.820  4184  4184 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 16:55:12.823  1888  1888 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 16:55:12.824  1855  2243 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 16:55:12.827   873  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 16:55:12.830  3640  3640 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-24 16:55:12.840  1888  4274 I Keyboard.Facilitator.DecoderInitializer: run()
,08-24 16:55:12.859  1888  4274 I Decoder : createOrResetDecoder
,08-24 16:55:12.863   873  1980 I ActivityManager: Start proc 4277:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-24 16:55:12.867  1954  1954 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-24 16:55:12.909  1497  1497 I ConfigService: onCreate
,08-24 16:55:12.916  4277  4277 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-24 16:55:12.921   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 16:55:12.927   873  1686 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3844 uid 10000
,08-24 16:55:12.929  1888  1888 I Keyboard.Facilitator: onFinishInput()
,08-24 16:55:12.932  1888  4274 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 16:55:12.935  1972  2115 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-24 16:55:12.938   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-24 16:55:12.939   873   885 E PackageManager: Failed to write settings, restoring backup
08-24 16:55:12.939   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 16:55:12.939   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 16:55:12.939   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 16:55:12.939   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 16:55:12.939   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 16:55:12.939   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:12.939   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:12.939   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:55:12.944   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-24 16:55:12.944   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 16:55:12.944   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:12.944   873   886 E DropBoxManagerService: 	... 13 more
,08-24 16:55:12.954   873  1708 I ActivityManager: Start proc 4290:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-24 16:55:12.954  1972  2115 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 16:55:12.954  1972  2115 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1972
08-24 16:55:12.954  1972  2115 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:12.954  1972  2115 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:55:12.956   873  4295 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:55:12.956   873  4295 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:12.956   873  4295 E DropBoxManagerService: 	... 5 more
,08-24 16:55:12.957   873  1978 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 16:55:12.960  1972  2115 I Process : Sending signal. PID: 1972 SIG: 9
,08-24 16:55:12.992  1888  4274 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-24 16:55:12.993  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-24 16:55:12.993  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-24 16:55:12.995  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-24 16:55:12.995  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-24 16:55:12.997  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-24 16:55:12.997  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-24 16:55:12.999  1888  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-24 16:55:12.999  1888  4274 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-24 16:55:12.999  1888  4274 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 16:55:12.999  1888  4274 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-24 16:55:12.999  1888  4274 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 16:55:13.000  1888  4274 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 16:55:13.017   873  2288 I WindowState: WIN DEATH: Window{b6db5de u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-24 16:55:13.017   873  1980 D GraphicsStats: Buffer count: 1
,08-24 16:55:13.028   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1972) has died
,08-24 16:55:13.029   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-24 16:55:13.031   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 16:55:13.048   873   886 I ActivityManager: Start proc 4308:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 16:55:13.055  4277  4277 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-24 16:55:13.059  4277  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.059  4277  4305 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:55:13.067  4277  4320 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-24 16:55:13.073   873  1969 I ActivityManager: Start proc 4322:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.104  4277  4305 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.104  4308  4308 E SQLiteData,base: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:55:13.104  4308  4308 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:55:13.104  4308  4308 D AndroidRuntime: Shutting down VM
08-24 16:55:13.111  4308  4308 E AndroidRuntime: FATAL EXCEPTION: main
08-24 16:55:13.111  4308  4308 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4308
08-24 16:55:13.111  4308  4308 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.os.Loop,er.loop(Looper.java:148)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 16:55:13.111  4308  4308 E AndroidRuntime: 	... 10 more
08-24 16:55:13.112   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 16:55:13.113   873  4335 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:55:13.113   873  4335 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:13.113   873  4335 E DropBoxManagerService: 	... 5 more
08-24 16:55:13.113  4308  4308 I Process : Sending signal. PID: 4308 SIG: 9
08-24 16:55:13.123  1709  4334 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 16:55:13.124  1709  4334 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 16:55:13.129  1709  4334 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 16:55:13.130  1709  4334 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 16:55:13.137   873  1978 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4308) has died
08-24 16:55:13.138   873  1978 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 16:55:13.143  4322  4322 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-24 16:55:13.151   873   886 I ActivityManager: Start proc 4336:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 16:55:13.166  1497  1497 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 16:55:13.167  1497  1497 D AndroidRuntime: Shutting down VM
08-24 16:55:13.168  1497  1497 E AndroidRuntime: FATAL EXCEPTION: main
08-24 16:55:13.168  1497  1497 E AndroidRuntime: Process: com.google.process.gapps, PID: 1497
08-24 16:55:13.168  1497  1497 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 16:55:13.168  1497  1497 E AndroidRuntime: 	... 8 more
,08-24 16:55:13.172  1497  1497 I Process : Sending signal. PID: 1497 SIG: 9
08-24 16:55:13.173   873  4351 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:55:13.173   873  4351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:13.173   873  4351 E DropBoxManagerService: 	... 5 more
08-24 16:55:13.183   873  2279 I ActivityManager: Killing 3693:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:55:13.196  4336  4336 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:55:13.196  4336  4336 D AndroidRuntime: Shutting down VM
08-24 16:55:13.208  4277  4305 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-24 16:55:13.213  4277  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.213  4277  4320 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:55:13.213  4277  4320 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 16:55:13.213  4277  4320 E AndroidRuntime: Process: android.process.acore, PID: 4277
08-24 16:55:13.213  4277  4320 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.213  4277  4320 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 16:55:13.215  4277  4305 I Process : Sending signal. PID: 4277 SIG: 9,
,08-24 16:55:13.235   873  1312 D WifiService: Client connection lost with reason: 4
,08-24 16:55:13.243   873  1980 I ActivityManager: Process com.google.process.gapps (pid 1497) has died
,08-24 16:55:13.243   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,08-24 16:55:13.244   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,08-24 16:55:13.244   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-24 16:55:13.244   873  1980 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,08-24 16:55:13.249  1709  1709 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-24 16:55:13.249  4336  4336 E AndroidRuntime: FATAL EXCEPTION: main
08-24 16:55:13.249  4336  4336 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4336
08-24 16:55:13.249  4336  4336 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 16:55:13.249  4336  4336 E AndroidRuntime: 	... 10 more
08-24 16:55:13.252   873  4352 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:55:13.252   873  4352 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:13.252   873  4352 E DropBoxManagerService: 	... 5 more
08-24 16:55:13.254   873  1978 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 16:55:13.255   873  4353 E DropBoxManagerService: Can't write: system_app_crash
08-24 16:55:13.255   873  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 16:55:13.255   873  4353 E DropBoxManagerService: 	... 5 more
,08-24 16:55:13.255  4336  4336 I Process : Sending signal. PID: 4336 SIG: 9
,08-24 16:55:13.267  1709  4334 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 16:55:13.268  1709  4334 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-24 16:55:13.276   873  2287 I ActivityManager: Start proc 4354:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-24 16:55:13.283   873  1978 I ActivityManager: Process android.process.acore (pid 4277) has died
,08-24 16:55:13.284   873  1978 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30959ms
,08-24 16:55:13.285   873  2020 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4336) has died
08-24 16:55:13.286   873  2020 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 16:55:13.286   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-24 16:55:13.300   873   886 I ActivityManager: Start proc 4368:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 16:55:13.319   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
