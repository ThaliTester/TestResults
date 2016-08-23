#### Test 82337235c858ce8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 15:43:18.685   873  1879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=111437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 15:43:19.406  3812  3812 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 15:43:19.411  3812  3812 D AndroidRuntime: CheckJNI is OFF
08-23 15:43:19.453  3812  3812 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 15:43:19.502  3812  3812 I Radio-JNI: register_android_hardware_Radio DONE
08-23 15:43:19.524  3812  3812 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 15:43:19.528   873  2019 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 15:43:19.568  2002  2014 W SearchService: Abort, client detached.
08-23 15:43:19.583  2002  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@98fa71e
08-23 15:43:19.584  2002  2352 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 15:43:19.585  2002  2002 I HotwordDetector: Closing mic
08-23 15:43:19.589  3812  3812 D AndroidRuntime: Shutting down VM
08-23 15:43:19.608   873  2272 I ActivityManager: Start proc 3821:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 15:43:19.653   375  2355 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 15:43:19.654   375  2355 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 15:43:19.658   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 15:43:19.659  2002  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 15:43:19.662  2002  2351 I MicroRecognitionRnrImpl: Detection finished
08-23 15:43:19.699  3821  3821 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 15:43:19.723  3821  3821 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 15:43:19.730  3821  3821 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2480-2482)
08-23 15:43:19.730  3821  3821 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:43:19.762  3821  3821 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ba2620f}
08-23 15:43:19.763  3821  3821 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:43:19.764  3821  3821 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 15:43:19.771  3821  3821 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 15:43:19.773  3821  3821 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 15:43:19.788  3821  3821 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 15:43:19.804  3821  3821 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 15:43:19.804  3821  3821 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 15:43:19.804  3821  3821 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 15:43:19.804  3821  3821 I Adreno  : Build Date                       : 10/20/15
08-23 15:43:19.804  3821  3821 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 15:43:19.804  3821  3821 I Adreno  : Local Branch                     : M14
08-23 15:43:19.804  3821  3821 I Adreno  : Remote Branch                    : 
08-23 15:43:19.804  3821  3821 I Adreno  : Remote Branch                    : 
08-23 15:43:19.804  3821  3821 I Adreno  : Reconstruct Branch               : 
,08-23 15:43:19.860   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fac740:true
,08-23 15:43:19.904  3821  3821 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 15:43:19.921  3821  3821 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 15:43:20.000  3821  3859 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 15:43:20.017  3821  3846 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 15:43:20.065  3821  3859 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 15:43:20.175   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms
,08-23 15:43:20.188  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-23 15:43:20.259  3821  3821 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3821
,08-23 15:43:20.433   873   883 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-23 15:43:20.457  3821  3821 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:43:20.496   873   883 I ActivityManager: Killing 3227:com.google.android.gm/u0a78 (adj 15): empty #18
,08-23 15:43:20.629  3821  3862 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680934608
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 15:43:20.635  3821  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e837392 added. We now have 1 listener(s)
08-23 15:43:20.639  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-23 15:43:20.640  3821  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 15:43:20.641  3821  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 15:43:20.641  3821  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 15:43:20.647  3821  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e1619 added. We now have 1 listener(s)
08-23 15:43:20.647  3821  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 15:43:20.650   873  1316 D WifiService: New client listening to asynchronous messages
,08-23 15:43:20.651  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 15:43:20.651  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:43:20.651  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:43:20.651  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 15:43:20.652  3821  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 15:43:20.656  3821  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 15:43:20.656  3821  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 15:43:20.662  3821  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:20.662  3821  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:43:20.662  3821  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:43:20.662  3821  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 15:43:20.663  3821  3862 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 15:43:20.665  3821  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:20.669  3821  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:20.689  3821  3821 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:43:21.446  3821  3871 W jxcore-log: Initializing JXcore engine
,08-23 15:43:21.446  3821  3871 W jxcore-log: JXcore engine is ready
,08-23 15:43:21.483  3871  3871 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 15:43:21.483  3871  3871 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11026]" dev="sockfs" ino=11026 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 15:43:21.483  3871  3871 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 15:43:21.483  3871  3871 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26659]" dev="sockfs" ino=26659 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 15:43:21.495  3821  3871 W jxcore-log: Starting JXcore engine
,08-23 15:43:21.575  3821  3871 W jxcore-log: Platform android
08-23 15:43:21.575  3821  3871 W jxcore-log: 
,08-23 15:43:21.575  3821  3871 W jxcore-log: Process ARCH arm
08-23 15:43:21.575  3821  3871 W jxcore-log: 
,08-23 15:43:21.825  3821  3871 I jxcore-log: JXcore Cordova bridge is ready!
08-23 15:43:21.825  3821  3871 I jxcore-log: 
,08-23 15:43:21.825  3821  3871 W jxcore-log: JXcore engine is started
,08-23 15:43:21.834  3821  3862 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 15:43:21.837  3821  3821 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:43:29.804   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 15:43:29.863  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 15:43:29.868  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 15:43:29.870  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 15:43:29.897  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 15:43:29.898  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 15:43:29.898  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 15:43:29.898  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 15:43:29.918  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 15:43:29.918  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 15:43:29.918  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-23 15:43:32.908  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 15:43:32.908  3821  3871 I jxcore-log: 
,08-23 15:43:33.583  3052  3882 V KeepSync: Connecting to GoogleApiClient
,08-23 15:43:33.584   873  2016 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 15:43:33.692  1522  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 15:43:33.692  1522  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-23 15:43:33.693  1522  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 15:43:33.693  1522  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 15:43:33.711  1728  3883 V BaseAuthAsyncOperation: access token request failed
,08-23 15:43:33.713  3052  3882 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 15:43:33.779  1522  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 15:43:33.779  1522  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 15:43:33.779  1522  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 15:43:33.779  1522  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 15:43:33.807  3052  3882 E KeepSync: IOException
08-23 15:43:33.807  3052  3882 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 15:43:33.807  3052  3882 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 15:43:33.807  3052  3882 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 15:43:33.807  3052  3882 E KeepSync: 	... 10 more
,08-23 15:43:33.807  3052  3882 W KeepSync: Sync result 2
,08-23 15:43:33.819   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 125652, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,08-23 15:43:34.774  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 15:43:34.774  3821  3871 I jxcore-log: 
,08-23 15:43:34.804  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 15:43:34.804  3821  3871 I jxcore-log: 
,08-23 15:43:34.821  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 15:43:34.821  3821  3871 I jxcore-log: 
,08-23 15:43:34.846  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 15:43:34.846  3821  3871 I jxcore-log: 
,08-23 15:43:34.851  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 15:43:34.851  3821  3871 I jxcore-log: 
,08-23 15:43:37.671  3821  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 15:43:37.671  3821  3871 I jxcore-log: 
,08-23 15:43:37.674  3821  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 15:43:37.674  3821  3871 I jxcore-log: 
,08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:37.683  3821  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 15:43:37.687  3821  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 15:43:37.690  3821  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 15:43:37.690  3821  3871 I jxcore-log: 
,08-23 15:43:37.692  3821  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 15:43:37.692  3821  3871 I jxcore-log: 
,08-23 15:43:41.371  3821  3871 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 15:43:41.371  3821  3871 I jxcore-log: 
,08-23 15:43:41.502  3821  3871 I jxcore-log: ERROR runTests: 
08-23 15:43:41.502  3821  3871 I jxcore-log: 
,08-23 15:43:41.504  3821  3871 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'
08-23 15:43:41.504  3821  3871 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:43:41.509  3821  3871 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:43:41.509  3821  3871 I jxcore-log: 
,08-23 15:43:41.526  3821  3821 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 15:43:41.527  3821  3821 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 15:43:41.533   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (599 us)
,08-23 15:43:41.575  3821  3821 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 15:43:41.575  3821  3821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 15:43:41.575  3821  3862 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 15:43:41.609   873   886 I ActivityManager: Killing 2469:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 15:43:41.678  3821  3821 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 15:43:41.678  3821  3821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 15:43:41.678  3821  3821 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 15:43:41.678  3821  3821 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-23 15:43:41.678  3821  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 15:43:41.678  3821  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 15:43:41.678  3821  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 15:43:41.678  3821  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:43:41.678  3821  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e837392 removed from the list
08-23 15:43:41.679  3821  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:43:41.679  3821  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e1619 removed from the list
08-23 15:43:41.679  3821  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:43:41.681  3821  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 15:43:41.685  3821  3821 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 15:43:41.716  1867  1867 I Keyboard.Facilitator: onFinishInput()
,08-23 15:43:41.735  2002  2002 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-23 15:43:41.775  2002  3891 I MicroRecognitionRnrImpl: Starting detection.
,08-23 15:43:41.776  2002  3892 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@829f539
,08-23 15:43:41.788   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 15:43:41.788   375  3894 I AudioFlinger: AudioFlinger's thread 0xb1c40000 ready to run
,08-23 15:43:41.789  2002  3892 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@829f539
,08-23 15:43:41.799   375  3894 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-23 15:43:41.799   375  3894 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-23 15:43:41.799   375  3894 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-23 15:43:41.805   375  3894 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record,
,08-23 15:43:41.880  2002  2002 I HotwordWorkerImpl: onReady
,08-23 15:43:42.231  3885  3885 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 15:43:42.232  1944  2197 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-23 15:43:42.235  3885  3885 D AndroidRuntime: CheckJNI is OFF
,08-23 15:43:42.267  3885  3885 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 15:43:42.302  3885  3885 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 15:43:42.357  3885  3885 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 15:43:42.383   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 15:43:42.384   873   886 I ActivityManager: Killing 3821:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-23 15:43:42.474   873  1316 D WifiService: Client connection lost with reason: 4
,08-23 15:43:42.476   873   897 W PackageSettings: Skipping PackageSetting{4acfd4a com.example.hello/10273} due to missing metadata
,08-23 15:43:42.478   873   883 D GraphicsStats: Buffer count: 2
,08-23 15:43:42.495   873  2017 W ActivityManager: Spurious death for ProcessRecord{a8f9c8e 0:com.test.thalitest/u0a0}, curProc for 3821: null
,08-23 15:43:42.516   873   897 I art     : Starting a blocking GC Explicit
,08-23 15:43:42.562   873   897 I art     : Explicit concurrent mark sweep GC freed 19779(1234KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 664us total 45.749ms
,08-23 15:43:42.584   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-23 15:43:42.588  3885  3885 I art     : System.exit called, status: 0
08-23 15:43:42.588  3885  3885 I AndroidRuntime: VM exiting with result code 0.
,08-23 15:43:42.591   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-23 15:43:42.610  1944  1953 I art     : Background partial concurrent mark sweep GC freed 4403(286KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 28MB/44MB, paused 8.601ms total 16.103ms
,08-23 15:43:42.631  2671  2671 D BluetoothMapAppObserver: onReceive
08-23 15:43:42.631  2671  2671 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 15:43:42.635  2106  2307 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:42.636   873  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 15:43:42.642  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
08-23 15:43:42.649  3657  3657 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 15:43:42.656  1867  3908 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 15:43:42.666  1867  3908 I Decoder : createOrResetDecoder
,08-23 15:43:42.694  1927  1927 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 15:43:42.726   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 15:43:42.742  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-23 15:43:42.743  1522  1522 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-23 15:43:42.744  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-23 15:43:42.744  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-23 15:43:42.744  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
,08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 15:43:42.744  1522  1522 E AndroidRuntime: 	... 8 more
,08-23 15:43:42.746   873  1342 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-23 15:43:42.746   873  1342 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-23 15:43:42.746   873  1342 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-23 15:43:42.746   873  1342 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-23 15:43:42.746   873  1342 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-23 15:43:42.747   873  1342 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-23 15:43:42.747   873  1342 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-23 15:43:42.748  3516  3530 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj2C565E965) - 
08-23 15:43:42.748   873  3912 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:43:42.748   873  3912 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 15:43:42.748   873  3912 E DropBoxManagerService: 	... 5 more
08-23 15:43:42.749   873  1342 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
,08-23 15:43:42.749   873  1342 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-23 15:43:42.749   873  1342 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-23 15:43:42.749   873  1342 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-23 15:43:42.749   873  1342 W System.err: 	... 4 more
08-23 15:43:42.749   873  1342 D skia    : ------- write threw an exception
08-23 15:43:42.750  3516  3909 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 15:43:42.755  3516  3530 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-23 15:43:42.755  3516  3530 E AndroidRuntime: Process: android.process.acore, PID: 3516
08-23 15:43:42.755  3516  3530 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 15:43:42.755  3516  3530 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:43:42.763   873  3913 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-23 15:43:42.766  3516  3909 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-23 15:43:42.767  1944  2030 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-23 15:43:42.767  3516  3909 I Process : Sending signal. PID: 3516 SIG: 9
08-23 15:43:42.768   873  3914 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:43:42.768   873  3914 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 15:43:42.768   873  3914 E DropBoxManagerService: 	... 5 more
08-23 15:43:42.771   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-23 15:43:42.771   873   885 E PackageManager: Failed to write settings, restoring backup
08-23 15:43:42.771   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 15:43:42.771   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 15:43:42.771   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 15:43:42.771   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 15:43:42.771   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 15:43:42.771   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:42.771   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 15:43:42.771   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:43:42.773   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-23 15:43:42.773   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 15:43:42.773   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 15:43:42.773   873   886 E DropBoxManagerService: 	... 13 more
08-23 15:43:42.787   873  2271 I ActivityManager: Start proc 3915:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-23 15:43:42.787  1944  2030 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 15:43:42.787  1944  2030 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1944
08-23 15:43:42.787  1944  2030 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 15:43:42.787  1944  2030 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:43:42.789   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 15:43:42.790   873  3921 E DropBoxManagerService: Can't write: system_app_crash
08-23 15:43:42.790   873  3921 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 15:43:42.790   873  3921 E DropBoxManagerService: 	... 5 more
08-23 15:43:42.792  2002  3767 W SearchService: Abort, client detached.
,08-23 15:43:42.795  2002  2002 I HotwordDetector: Closing mic
08-23 15:43:42.796  2002  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@829f539
08-23 15:43:42.796  2002  3892 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 15:43:42.797   873  3913 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 15:43:42.797   873  3913 I Adreno  : Build Date                       : 10/20/15
08-23 15:43:42.797   873  3913 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 15:43:42.797   873  3913 I Adreno  : Local Branch                     : M14
08-23 15:43:42.797   873  3913 I Adreno  : Remote Branch                    : 
08-23 15:43:42.797   873  3913 I Adreno  : Remote Branch                    : 
08-23 15:43:42.797   873  3913 I Adreno  : Reconstruct Branch               : 
08-23 15:43:42.802   873  3913 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 15:43:42.802   278   278 E lowmemorykiller: Error writing /proc/3516/oom_score_adj; errno=22
08-23 15:43:42.820   873  1380 I ActivityManager: Process android.process.acore (pid 3516) has died
08-23 15:43:42.821   873  1380 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-23 15:43:42.843   375  3894 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-23 15:43:42.844   375  3894 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 15:43:42.847   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-23 15:43:42.849  2002  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-23 15:43:42.852  2002  3891 I MicroRecognitionRnrImpl: Detection finished
,08-23 15:43:42.854   873  2019 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-23 15:43:42.869  1944  1944 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@bf2a46 new=com.google.android.velvet.VelvetApplication@bf2a46
,08-23 15:43:42.915  1944  1944 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-23 15:43:42.954  1728  3936 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-23 15:43:42.955  1728  3936 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-23 15:43:42.973   873   891 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +112ms
,08-23 15:43:43.149   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-23 15:43:43.150   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,08-23 15:43:43.150   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 15:43:43.150   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-23 15:43:43.150   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-23 15:43:43.150   280   280 E qdoverlay: MdpCtrl close error in unset
,08-23 15:43:43.431   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
