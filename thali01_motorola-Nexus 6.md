#### Test 8180285668baf36_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-18 14:08:43.450  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 14:08:43.462  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 14:08:43.467  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-18 14:08:43.521  1507  2192 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-18 14:08:43.522  1507  2192 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-18 14:08:43.522  1507  2192 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 14:08:43.522  1507  2192 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-18 14:08:43.556  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-18 14:08:43.557  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 14:08:43.559  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-18 14:08:44.042  3789  3789 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-18 14:08:44.046  3789  3789 D AndroidRuntime: CheckJNI is OFF
08-18 14:08:44.082  3789  3789 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-18 14:08:44.125  3789  3789 I Radio-JNI: register_android_hardware_Radio DONE
08-18 14:08:44.146  3789  3789 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 14:08:44.150   871  1373 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 14:08:44.195  1992  2006 W SearchService: Abort, client detached.
08-18 14:08:44.199  3789  3789 D AndroidRuntime: Shutting down VM
08-18 14:08:44.201  1992  1992 I HotwordDetector: Closing mic
08-18 14:08:44.201  1992  2342 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@18efed6
08-18 14:08:44.202  1992  2349 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-18 14:08:44.218   871  1932 I ActivityManager: Start proc 3798:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-18 14:08:44.262   377  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-18 14:08:44.263   377  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-18 14:08:44.271   377  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-18 14:08:44.273  1992  2347 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-18 14:08:44.274  1992  2348 I MicroRecognitionRnrImpl: Detection finished
08-18 14:08:44.315  3798  3798 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-18 14:08:44.343  3798  3798 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-18 14:08:44.352  3798  3798 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1294-1297)
08-18 14:08:44.352  3798  3798 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 14:08:44.366  3798  3798 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3343b6b}
08-18 14:08:44.367  3798  3798 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 14:08:44.367  3798  3798 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 14:08:44.373  3798  3798 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 14:08:44.374  3798  3798 E SysUtils: ApplicationContext is null in ApplicationStatus
08-18 14:08:44.388  3798  3798 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-18 14:08:44.398  3798  3798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 14:08:44.398  3798  3798 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 14:08:44.398  3798  3798 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 14:08:44.398  3798  3798 I Adreno  : Build Date                       : 10/20/15
08-18 14:08:44.398  3798  3798 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 14:08:44.398  3798  3798 I Adreno  : Local Branch                     : M14
08-18 14:08:44.398  3798  3798 I Adreno  : Remote Branch                    : 
08-18 14:08:44.398  3798  3798 I Adreno  : Remote Branch                    : 
08-18 14:08:44.398  3798  3798 I Adreno  : Reconstruct Branch               : 
,08-18 14:08:44.454   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@73de27b:true
,08-18 14:08:44.522  3798  3798 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-18 14:08:44.538  3798  3798 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-18 14:08:44.631  3798  3836 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-18 14:08:44.643  3798  3823 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-18 14:08:44.677  3798  3836 I OpenGLRenderer: Initialized EGL, version 1.4
,08-18 14:08:44.786   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +585ms
,08-18 14:08:44.788  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-18 14:08:44.891  3798  3798 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3798
,08-18 14:08:45.025   871  1932 I ActivityManager: Killing 2965:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-18 14:08:45.073   871  1932 I ActivityManager: Killing 3201:com.google.android.gm/u0a78 (adj 15): empty #18
,08-18 14:08:45.125  3798  3798 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 14:08:45.308  3798  3838 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697973968
,08-18 14:08:45.338  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 14:08:45.338  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 14:08:45.338  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 14:08:45.338  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 14:08:45.338  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-18 14:08:45.339  3798  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c4b7ff added. We now have 1 listener(s),
,08-18 14:08:45.343  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-18 14:08:45.344  3798  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 14:08:45.345  3798  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:08:45.345  3798  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 14:08:45.350  3798  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bc832a added. We now have 1 listener(s)
08-18 14:08:45.351  3798  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:08:45.354   871  1306 D WifiService: New client listening to asynchronous messages
08-18 14:08:45.355  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:08:45.356  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-18 14:08:45.356  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 14:08:45.356  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-18 14:08:45.356  3798  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-18 14:08:45.364  3798  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:45.364  3798  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-18 14:08:45.371  3798  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:45.371  3798  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:08:45.371  3798  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 14:08:45.371  3798  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:08:45.372  3798  3838 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 14:08:45.487  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:45.490  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:45.494  3798  3798 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 14:08:45.940  3798  3807 I art     : Background sticky concurrent mark sweep GC freed 70132(6MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 782us total 161.086ms
,08-18 14:08:45.984   871  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-18 14:08:46.555  3798  3848 W jxcore-log: Initializing JXcore engine
,08-18 14:08:46.556  3798  3848 W jxcore-log: JXcore engine is ready
,08-18 14:08:46.591  3848  3848 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-18 14:08:46.591  3848  3848 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12951]" dev="sockfs" ino=12951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-18 14:08:46.591  3848  3848 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-18 14:08:46.591  3848  3848 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27058]" dev="sockfs" ino=27058 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-18 14:08:46.604  3798  3848 W jxcore-log: Starting JXcore engine
,08-18 14:08:46.680  3798  3848 W jxcore-log: Platform android
08-18 14:08:46.680  3798  3848 W jxcore-log: 
,08-18 14:08:46.680  3798  3848 W jxcore-log: Process ARCH arm
08-18 14:08:46.680  3798  3848 W jxcore-log: 
,08-18 14:08:46.911  3798  3848 I jxcore-log: JXcore Cordova bridge is ready!
08-18 14:08:46.911  3798  3848 I jxcore-log: 
,08-18 14:08:46.911  3798  3848 W jxcore-log: JXcore engine is started
,08-18 14:08:46.924  3798  3838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-18 14:08:46.929  3798  3798 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-18 14:08:49.321  3046  3856 V KeepSync: Connecting to GoogleApiClient
,08-18 14:08:49.321   871  1942 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-18 14:08:49.370  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:08:49.372  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:08:49.398  1507  2964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-18 14:08:49.398  1507  2964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-18 14:08:49.398  1507  2964 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 14:08:49.398  1507  2964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 14:08:49.421  1720  3857 V BaseAuthAsyncOperation: access token request failed
,08-18 14:08:49.422  3046  3856 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-18 14:08:49.475  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-18 14:08:49.475  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-18 14:08:49.475  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 14:08:49.476  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 14:08:49.503  3046  3856 E KeepSync: IOException
08-18 14:08:49.503  3046  3856 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-18 14:08:49.503  3046  3856 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-18 14:08:49.503  3046  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-18 14:08:49.503  3046  3856 E KeepSync: 	... 10 more
,08-18 14:08:49.503  3046  3856 W KeepSync: Sync result 2
,08-18 14:08:49.512   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 125673, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-18 14:08:56.425   871  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-18 14:08:56.689  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 14:08:56.689  3798  3848 I jxcore-log: 
,08-18 14:08:56.691  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 14:08:56.691  3798  3848 I jxcore-log: 
,08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:56.705  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:08:56.713  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:08:56.720  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 14:08:56.720  3798  3848 I jxcore-log: 
,08-18 14:08:56.727  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 14:08:56.727  3798  3848 I jxcore-log: 
,08-18 14:08:57.251  3798  3848 D ExecuteNativeTests: Running unit tests
,08-18 14:08:57.309  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:08:57.309  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f added. We now have 2 listener(s)
,08-18 14:08:57.310  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:08:57.310  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 14:08:57.310  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 14:08:57.310  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:08:57.310  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c added. We now have 2 listener(s)
,08-18 14:08:57.311  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:08:57.311  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:08:57.314  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.325  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:08:57.328  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.328  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 14:08:57.331  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-18 14:08:57.333  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.333  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:08:57.333  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-18 14:08:57.335  3798  3848 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-18 14:08:57.335  3798  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-18 14:08:57.335  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:08:57.335  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:08:57.335  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:08:57.336  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.336  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.336  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 14:08:57.336  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.336  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.336  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:08:57.336  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:08:57.337  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f removed from the list
,08-18 14:08:57.337  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:08:57.337  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c removed from the list
08-18 14:08:57.339  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.340  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.340  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.343  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.344  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.349  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.349  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.349  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.349  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.351  3798  3848 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-18 14:08:57.351  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:08:57.351  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.351  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 14:08:57.351  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.352  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.352  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.352  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.352  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.352  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.352  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.352  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.352  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.352  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.352  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.354  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.354  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:08:57.355  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.355  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.369  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-18 14:08:57.369  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-18 14:08:57.369  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-18 14:08:57.369  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-18 14:08:57.369  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-18 14:08:57.370  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-18 14:08:57.371  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 14:08:57.372  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 14:08:57.373  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-18 14:08:57.374  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-18 14:08:57.374  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 14:08:57.374  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:08:57.374  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.374  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.374  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:08:57.374  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.374  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.374  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
,08-18 14:08:57.374  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.375  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.375  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.375  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.375  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.375  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.375  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.376  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.376  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:08:57.376  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.376  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.376  3798  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:08:57.378  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.383  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:08:57.385  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.385  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 14:08:57.387  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 14:08:57.387  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 14:08:57.387  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.387  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:08:57.387  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:08:57.387  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:08:57.389  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.391  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 14:08:57.391  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 14:08:57.396  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 14:08:57.399  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 14:08:57.399  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 14:08:57.402  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-18 14:08:57.406  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-18 14:08:57.406  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 14:08:57.406  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 14:08:57.407  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 14:08:57.409  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:08:57.415  2654  2780 D BtGatt.GattService: registerClient() - UUID=070b93a4-4020-48c1-8568-458c2f107309
,08-18 14:08:57.416  2654  2677 D BtGatt.GattService: onClientRegistered() - UUID=070b93a4-4020-48c1-8568-458c2f107309, clientIf=5
08-18 14:08:57.416  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 14:08:57.417  2654  2666 D BtGatt.GattService: start scan with filters
,08-18 14:08:57.421  2654  2687 D BtGatt.ScanManager: handling starting scan
08-18 14:08:57.421  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 14:08:57.421  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 14:08:57.421  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 14:08:57.422  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 14:08:57.422  2654  2687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:08:57.424  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:08:57.425  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 14:08:57.425  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:08:57.428  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 14:08:57.432  2654  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 14:08:57.432  3798  3848 I io.jxcore.node.ConnectionHelper: start: OK
08-18 14:08:57.432  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.433  2654  2687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 14:08:57.437  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:08:57.437  3798  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-18 14:08:57.437  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.437  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-18 14:08:57.437  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.437  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 14:08:57.438  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-18 14:08:57.438  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 14:08:57.438  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:08:57.438  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:08:57.439  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 14:08:57.439  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:08:57.440  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 14:08:57.440  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:08:57.440  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.440  2654  2666 D BtGatt.GattService: stopScan() - queue size =1
08-18 14:08:57.440  2654  2687 D BtGatt.ScanManager: Starting BLE batch scan
08-18 14:08:57.441  2654  2757 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 14:08:57.441  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:08:57.440  2654  2687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:08:57.442  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 14:08:57.442  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 14:08:57.442  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 14:08:57.442  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 14:08:57.443  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.443  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 14:08:57.443  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:08:57.444  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:08:57.444  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:08:57.445  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.445  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.445  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.445  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:08:57.445  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.445  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:08:57.445  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.445  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:08:57.446  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.446  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.446  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.446  3798  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:08:57.447  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.451  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:08:57.453  2654  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 14:08:57.453  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.454  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:08:57.454  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:08:57.454  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:08:57.454  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:08:57.454  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 14:08:57.455  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:57.455  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:08:57.456  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.458  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 14:08:57.459  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:08:57.459  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.459  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 14:08:57.459  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.463  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 14:08:57.464  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 14:08:57.464  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 14:08:57.466  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 14:08:57.466  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.466  2654  2687 D BtGatt.ScanManager: stopping BLe Batch
,08-18 14:08:57.469  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 14:08:57.469  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 14:08:57.469  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 14:08:57.469  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:08:57.471  2654  2666 D BtGatt.GattService: registerClient() - UUID=784ab5ac-3c51-4b89-9623-b91fc09e937d
,08-18 14:08:57.471  2654  2677 D BtGatt.GattService: onClientRegistered() - UUID=784ab5ac-3c51-4b89-9623-b91fc09e937d, clientIf=5
08-18 14:08:57.472  3798  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
08-18 14:08:57.472  2654  2664 D BtGatt.GattService: start scan with filters
,08-18 14:08:57.473  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 14:08:57.473  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.473  2654  2687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 14:08:57.474  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 14:08:57.474  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-18 14:08:57.475  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-18 14:08:57.475  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 14:08:57.477  2654  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
08-18 14:08:57.477  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.478  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 14:08:57.479  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 14:08:57.479  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:08:57.479  2654  2687 D BtGatt.ScanManager: handling starting scan
08-18 14:08:57.481  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 14:08:57.483  2654  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 14:08:57.483  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.483  2654  2687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 14:08:57.484  3798  3848 I io.jxcore.node.ConnectionHelper: start: OK
08-18 14:08:57.485  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.486  3798  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 14:08:57.486  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:08:57.486  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 14:08:57.486  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.486  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 14:08:57.486  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-18 14:08:57.486  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 14:08:57.486  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 14:08:57.486  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:08:57.486  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 14:08:57.486  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:08:57.488  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 14:08:57.488  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.488  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:08:57.488  2654  2687 D BtGatt.ScanManager: Starting BLE batch scan
08-18 14:08:57.488  2654  2687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:08:57.488  2654  2666 D BtGatt.GattService: stopScan() - queue size =1
08-18 14:08:57.489  2654  2664 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 14:08:57.490  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:08:57.490  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-18 14:08:57.490  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 14:08:57.490  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 14:08:57.490  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 14:08:57.492  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 14:08:57.492  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 14:08:57.493  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:08:57.493  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:08:57.493  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:08:57.495  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 14:08:57.495  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.495  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.495  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 14:08:57.495  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.495  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:08:57.495  2654  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 14:08:57.495  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.495  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.496  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.496  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.496  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.496  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.496  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.496  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.498  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.498  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:08:57.498  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:08:57.498  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.500  3798  3848 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 14:08:57.500  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 14:08:57.500  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.501  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.504  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:08:57.506  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:08:57.506  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 14:08:57.506  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:08:57.506  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.506  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:08:57.506  2654  2687 D BtGatt.ScanManager: stopping BLe Batch
08-18 14:08:57.506  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:08:57.506  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 14:08:57.506  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:57.506  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:08:57.508  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:57.509  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 14:08:57.509  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:08:57.511  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:57.512  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 14:08:57.512  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 14:08:57.512  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 14:08:57.513  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 14:08:57.513  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.513  2654  2687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 14:08:57.515  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 14:08:57.515  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 14:08:57.516  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-18 14:08:57.516  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:08:57.517  2654  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 14:08:57.517  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.519  2654  2757 D BtGatt.GattService: registerClient() - UUID=45134f4e-c46d-40c9-b94c-e9527d1aa877
,08-18 14:08:57.519  2654  2677 D BtGatt.GattService: onClientRegistered() - UUID=45134f4e-c46d-40c9-b94c-e9527d1aa877, clientIf=5
08-18 14:08:57.519  3798  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 14:08:57.519  2654  2666 D BtGatt.GattService: start scan with filters
,08-18 14:08:57.521  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 14:08:57.521  2654  2687 D BtGatt.ScanManager: handling starting scan
08-18 14:08:57.522  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 14:08:57.522  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 14:08:57.522  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 14:08:57.525  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:08:57.525  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 14:08:57.525  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 14:08:57.526  2654  2677 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 14:08:57.526  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.526  2654  2687 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 14:08:57.527  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 14:08:57.529  3798  3848 I io.jxcore.node.ConnectionHelper: start: OK
,08-18 14:08:57.529  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.529  3798  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 14:08:57.529  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.529  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 14:08:57.529  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.529  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 14:08:57.529  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 14:08:57.529  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 14:08:57.529  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:08:57.529  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:08:57.529  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 14:08:57.529  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:08:57.530  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:08:57.530  2654  2666 D BtGatt.GattService: stopScan() - queue size =1
08-18 14:08:57.531  2654  2780 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-18 14:08:57.531  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:08:57.531  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 14:08:57.531  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.531  2654  2687 D BtGatt.ScanManager: Starting BLE batch scan
08-18 14:08:57.531  2654  2687 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:08:57.531  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 14:08:57.531  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 14:08:57.531  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 14:08:57.531  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 14:08:57.532  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.532  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 14:08:57.532  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:08:57.532  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 14:08:57.533  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:08:57.533  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:08:57.533  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.533  3798  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 14:08:57.533  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.533  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.533  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.534  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.534  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.534  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.534  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:08:57.534  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.534  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.534  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.534  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.534  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.534  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.534  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.535  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.535  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.535  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.535  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.535  3798  3848 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-18 14:08:57.536  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.536  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.536  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.536  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:08:57.536  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.536  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.536  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.536  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.536  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.536  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.536  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.536  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.536  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.536  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.537  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.537  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.537  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.537  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.538  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 14:08:57.538  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.538  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.538  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.538  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:08:57.538  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.538  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.538  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.538  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.538  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.538  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.539  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.539  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.539  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.539  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.539  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.539  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:08:57.539  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.539  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.540  3798  3848 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-18 14:08:57.540  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.540  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:08:57.540  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.540  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.540  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.540  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.540  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
,08-18 14:08:57.540  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.540  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.540  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.540  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.540  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.540  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.541  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.541  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.541  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.541  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.541  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.542  2654  2677 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 14:08:57.542  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.542  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-18 14:08:57.542  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.542  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.542  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.542  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.542  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.542  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.543  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
,08-18 14:08:57.543  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.543  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.543  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.543  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.543  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.543  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.543  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.543  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.543  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.544  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.544  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.544  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 14:08:57.545  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:08:57.545  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:08:57.545  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:08:57.545  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 14:08:57.545  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 14:08:57.545  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.546  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:08:57.546  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.546  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.546  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.546  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.546  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.546  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.546  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.546  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.546  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.546  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.547  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.547  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.549  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 14:08:57.549  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.549  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.549  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.549  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.550  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.551  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:08:57.552  3798  3848 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-18 14:08:57.552  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-18 14:08:57.556  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:08:57.556  3798  3848 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 14:08:57.557  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-18 14:08:57.558  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-18 14:08:57.559  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 14:08:57.559  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-18 14:08:57.559  3798  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 14:08:57.559  3798  3848 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-18 14:08:57.559  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:08:57.559  3798  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 14:08:57.559  3798  3848 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-18 14:08:57.559  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:08:57.559  3798  3848 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-18 14:08:57.560  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-18 14:08:57.560  2654  2677 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 14:08:57.561  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:08:57.561  2654  2687 D BtGatt.ScanManager: stopping BLe Batch
08-18 14:08:57.563  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-18 14:08:57.563  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-18 14:08:57.563  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-18 14:08:57.564  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-18 14:08:57.564  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-18 14:08:57.564  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-18 14:08:57.564  3798  3848 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 14:08:57.565  3798  3848 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-18 14:08:57.567  2654  2677 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 14:08:57.567  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.565  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.568  2654  2687 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 14:08:57.568  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:08:57.568  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 14:08:57.568  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-18 14:08:57.568  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:08:57.568  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.568  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-18 14:08:57.569  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list,
08-18 14:08:57.569  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.569  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.569  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 14:08:57.569  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.569  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.569  3798  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
,08-18 14:08:57.569  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.569  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.570  3798  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
,08-18 14:08:57.571  3798  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
,08-18 14:08:57.571  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.571  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:08:57.571  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.571  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
,08-18 14:08:57.572  3798  3848 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-18 14:08:57.573  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.573  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-18 14:08:57.573  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.573  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.573  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.573  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.573  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.573  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:08:57.573  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.573  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.573  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.573  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.574  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.574  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.574  2654  2677 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 14:08:57.574  2654  2677 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:08:57.575  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.575  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.575  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.575  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.576  3798  3848 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-18 14:08:57.576  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.576  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:08:57.576  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.576  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.576  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.576  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:08:57.576  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.577  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.577  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.577  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.577  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.577  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.577  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.577  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.578  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.578  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.578  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.578  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-18 14:08:57.579  3798  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-18 14:08:57.579  3798  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 14:08:57.579  3798  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:08:57.579  3798  3848 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 14:08:57.579  3798  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 14:08:57.579  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:08:57.579  3798  3848 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-18 14:08:57.580  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:08:57.580  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.580  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.580  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.580  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.580  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.580  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.580  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.580  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.580  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.580  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.581  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.581  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.581  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.581  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.581  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.581  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.582  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.582  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.582  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.582  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.582  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.582  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.582  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.582  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.582  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.583  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.583  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.583  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.583  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.583  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.583  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.583  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.583  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.583  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.583  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.583  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.583  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.583  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.583  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.583  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.584  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.584  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.584  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.584  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.584  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.584  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.585  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.585  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.585  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.585  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.586  3798  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-18 14:08:57.586  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:57.587  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-18 14:08:57.587  3798  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-18 14:08:57.587  3798  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 14:08:57.588  3798  3798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-18 14:08:57.588  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-18 14:08:57.588  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.588  3798  3848 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-18 14:08:57.588  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.588  3798  3798 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.588  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 14:08:57.588  3798  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-18 14:08:57.588  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:08:57.589  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:08:57.589  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.589  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.589  3798  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-18 14:08:57.589  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.590  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.590  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.590  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.590  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:08:57.590  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.590  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.590  3798  3798 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-18 14:08:57.590  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.590  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.590  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:08:57.590  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.590  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.590  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.590  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.590  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.590  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.590  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.590  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.590  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.591  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.591  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.591  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.591  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.592  3798  3848 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-18 14:08:57.592  3798  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-18 14:08:57.592  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 14:08:57.594  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 14:08:57.594  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.594  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.594  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.594  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.594  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.594  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.595  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.595  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.595  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.595  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.595  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.595  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.595  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.595  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.596  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.596  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.596  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.596  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.599  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.599  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.599  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.599  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.599  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.599  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.599  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.599  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.599  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.599  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.599  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.599  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.599  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.599  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.600  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:08:57.600  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.600  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.600  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.601  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:08:57.601  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:08:57.601  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:08:57.601  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:08:57.601  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.601  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.601  3798  3848 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c03110f not in the list
08-18 14:08:57.601  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.601  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.601  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:08:57.601  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.601  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.601  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:08:57.601  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:08:57.602  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-18 14:08:57.602  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:08:57.602  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:08:57.602  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1b059c not in the list
08-18 14:08:57.603  3798  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-18 14:08:57.603  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 14:08:57.603  3798  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-18 14:08:57.603  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 14:08:57.603  3798  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-18 14:08:57.603  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 14:08:57.604  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 14:08:57.604  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-18 14:08:57.605  3798  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-18 14:08:57.605  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 14:08:57.605  3798  3848 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-18 14:08:57.605  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 14:08:57.605  3798  3848 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-18 14:08:57.605  3798  3848 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-18 14:08:57.606  3798  3848 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-18 14:08:57.607  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:08:57.607  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9e6071e added. We now have 2 listener(s)
08-18 14:08:57.607  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:08:57.608  3798  3848 D BluetoothAdapter: enable(): BT is already enabled..!
08-18 14:08:57.608   871   882 D WifiService: setWifiEnabled: true pid=3798, uid=10000
08-18 14:08:57.608   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 14:08:57.609  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:08:57.609  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c505bff added. We now have 3 listener(s)
08-18 14:08:57.609  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:08:57.613  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:08:57.613  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@790dcc added. We now have 4 listener(s)
08-18 14:08:57.613  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:08:57.615  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:08:57.615  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d873815 added. We now have 5 listener(s)
08-18 14:08:57.615  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:08:57.616   871  2243 D WifiService: setWifiEnabled: false pid=3798, uid=10000
08-18 14:08:57.616   871  2243 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 14:08:57.619  2654  2668 D BluetoothAdapterState: Current state: ON, message: 23
08-18 14:08:57.619  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:08:57.619  2654  2668 D BluetoothAdapterProperties: Setting state to 13
08-18 14:08:57.619  2654  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-18 14:08:57.620  2654  2668 D BluetoothAdapterProperties: onBluetoothDisable()
,08-18 14:08:57.622  2654  2654 D BluetoothMapService: onReceive
,08-18 14:08:57.622  2654  2654 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:08:57.622  2654  2654 D BluetoothMapService: STATE_TURNING_OFF
08-18 14:08:57.622  2654  2654 D BluetoothMapService: MAP Service closeService in
08-18 14:08:57.622  2654  2654 D BluetoothMapMasInstance0: MAP Service shutdown
08-18 14:08:57.622  2654  2654 D ObexServerSockets0: shutdown(block = true)
,08-18 14:08:57.623  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.623  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:08:57.623  2654  2654 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 14:08:57.623  2654  2654 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 14:08:57.623  2654  2795 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-18 14:08:57.623  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.623  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.623  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:08:57.624  2654  2794 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-18 14:08:57.624  2654  2753 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-18 14:08:57.621  2654  2668 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:08:57.624  2654  2654 I BtOppRfcommListener: stopping Accept Thread
08-18 14:08:57.625  2654  3420 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-18 14:08:57.625  2654  3420 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 14:08:57.626  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.627  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.630  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:08:57.630  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:08:57.630  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:08:57.631  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:08:57.634  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.634  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 14:08:57.636   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 14:08:57.636   871   884 I ActivityManager: Start proc 3867:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-18 14:08:57.636   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-18 14:08:57.636   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 14:08:57.636   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 14:08:57.636  2654  2677 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:08:57.637  2654  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-18 14:08:57.639  2654  2654 D HeadsetService: Received stop request...Stopping profile...
08-18 14:08:57.643   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:08:57.644   871  1873 D DhcpClient: Clearing IP address
08-18 14:08:57.645   373   869 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:08:57.647  1920  2203 D BluetoothHeadset: Proxy object disconnected
08-18 14:08:57.647  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:57.649   373   869 D CommandListener: Setting iface cfg
08-18 14:08:57.650  1507  2470 V NativeCrypto: Read error: ssl=0x9b1e7a00: I/O error during system call, Connection timed out
08-18 14:08:57.652  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.652  1507  2470 V NativeCrypto: SSL shutdown failed: ssl=0x9b1e7a00: I/O error during system call, Broken pipe
08-18 14:08:57.652  1349  1980 D BluetoothHeadset: Proxy object disconnected
08-18 14:08:57.653   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:08:57.653   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:08:57.653  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-18 14:08:57.653  2654  2654 D A2dpService: Received stop request...Stopping profile...
08-18 14:08:57.654  2654  2763 D A2dpStateMachine: Exit Disconnected: -1
,08-18 14:08:57.655   871  1927 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-18 14:08:57.655   871  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-18 14:08:57.656   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-18 14:08:57.656   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 14:08:57.657   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-18 14:08:57.657   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-18 14:08:57.659   396   396 E Parcel  : Reading a NULL string not supported here.
08-18 14:08:57.661   871   871 D BluetoothA2dp: Proxy object disconnected
08-18 14:08:57.663  2654  2654 D HidService: Received stop request...Stopping profile...
,08-18 14:08:57.663  2654  2654 D HidService: Stopping Bluetooth HidService
08-18 14:08:57.664  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.664  2654  2654 V BluetoothAdapterState: isTurningOn()=false
08-18 14:08:57.664  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 14:08:57.664  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:08:57.665  2654  2654 D HealthService: Received stop request...Stopping profile...
08-18 14:08:57.666   373   869 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:08:57.667   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-18 14:08:57.667   871  1876 D DhcpClient: Receive thread stopped
08-18 14:08:57.667  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 14:08:57.668  2654  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-18 14:08:57.668  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 14:08:57.668  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:08:57.668  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:08:57.668  2654  2677 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-18 14:08:57.669  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-18 14:08:57.671  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-18 14:08:57.672  1349  1349 D HidProfile: Bluetooth service disconnected
08-18 14:08:57.672  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-18 14:08:57.674  2654  2654 D PanService: Received stop request...Stopping profile...
08-18 14:08:57.675   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:08:57.675  2654  2654 D BluetoothMapService: Received stop request...Stopping profile...
08-18 14:08:57.675  2654  2654 D BluetoothMapService: stop()
08-18 14:08:57.677  2654  2654 D BluetoothMapAppObserver: deinitObservers()
08-18 14:08:57.677  2654  2654 D BluetoothMapAppObserver: removeReceiver()
08-18 14:08:57.678  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:08:57.678  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:08:57.678  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:08:57.678  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:08:57.680   871  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-18 14:08:57.680  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.680  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:08:57.680  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:08:57.680  2654  2654 V BluetoothAdapterState: isTurningOn()=false
08-18 14:08:57.680  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:57.680  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:08:57.681  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:08:57.681  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:08:57.682  2103  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 14:08:57.684  2654  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-18 14:08:57.684  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:08:57.684  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:08:57.684  2654  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:08:57.685  2654  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:08:57.685  2654  2750 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:08:57.685  2654  2750 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isTurningOn()=false
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:08:57.685  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 14:08:57.685  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isTurningOn()=false
,08-18 14:08:57.685   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 14:08:57.685  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:57.686  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:08:57.686  2654  2677 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 14:08:57.686  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 14:08:57.686  2654  2677 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-18 14:08:57.686  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:08:57.686  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 14:08:57.686  1349  1349 D PanProfile: Bluetooth service disconnected
08-18 14:08:57.686  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.686  2654  2654 V BluetoothAdapterState: isTurningOn()=false
08-18 14:08:57.687  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:57.687  1349  1349 D BluetoothMap: Proxy object disconnected
08-18 14:08:57.687  1349  1349 D MapProfile: Bluetooth service disconnected
08-18 14:08:57.687  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:08:57.687  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 14:08:57.687  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 14:08:57.688  2654  2654 D BluetoothMapService: MAP Service closeService in
08-18 14:08:57.688  2654  2654 V BluetoothAdapterState: isTurningOff()=true
08-18 14:08:57.688  2654  2654 V BluetoothAdapterState: isTurningOn()=false
08-18 14:08:57.688  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:57.688  2654  2654 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:08:57.689  2654  2654 D BluetoothMapService: cleanup()
08-18 14:08:57.689  2654  2654 D BluetoothMapService: MAP Service closeService in
,08-18 14:08:57.689  2654  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-18 14:08:57.689  2654  2668 D BluetoothAdapterProperties: Setting state to 15
08-18 14:08:57.689  2654  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 14:08:57.690  1920  2204 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:08:57.690  2654  2668 I BluetoothAdapterState: Entering BleOnState
08-18 14:08:57.690  1349  1364 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:08:57.690  1349  1980 D BluetoothMap: onBluetoothStateChange: up=false
,08-18 14:08:57.691   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:08:57.691  1349  3881 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:08:57.692  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
08-18 14:08:57.692   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:08:57.692  1349  1364 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 14:08:57.693   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:08:57.693  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=false
,08-18 14:08:57.694   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:08:57.694  2654  2668 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-18 14:08:57.695  2654  2668 D BluetoothAdapterProperties: Setting state to 16
08-18 14:08:57.695  2654  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-18 14:08:57.695  2654  2668 D BluetoothAdapterProperties: onBleDisable
08-18 14:08:57.696  2654  2668 I BluetoothAdapterState: Entering PendingCommandState
08-18 14:08:57.696  2654  2669 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-18 14:08:57.696  2654  2677 D BluetoothAdapterProperties: Scan Mode:20
,08-18 14:08:57.698  2654  2750 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-18 14:08:57.698  2654  2750 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:08:57.698  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.699  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.700  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.701  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.718   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-18 14:08:57.719  3867  3867 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-18 14:08:57.730  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 14:08:57.734   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ff5c2a:true
,08-18 14:08:57.735  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:08:57.737   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:08:57.738   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-18 14:08:57.738   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:08:57.747   871   882 I ActivityManager: Start proc 3885:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-18 14:08:57.751   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-18 14:08:57.752  3405  3405 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1c4b7ff and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-18 14:08:57.753  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:08:57.753  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-18 14:08:57.754  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:08:57.777  3885  3885 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-18 14:08:57.779  3867  3867 D LocalBluetoothProfileManager: Adding local MAP profile
,08-18 14:08:57.781  3867  3867 D BluetoothMap: Create BluetoothMap proxy object
,08-18 14:08:57.789  3867  3867 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-18 14:08:57.793   373   869 E Netd    : netlink response contains error (No such file or directory)
,08-18 14:08:57.794   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 14:08:57.801  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:08:57.807   871  2244 I ActivityManager: Killing 3405:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-18 14:08:57.898  2654  2677 I bt_hci  : shut_down
,08-18 14:08:57.899  2654  2688 D bt_hwcfg: hw_epilog_process
,08-18 14:08:57.900  2654  2688 I bt_vendor: low_power_mode_cb
,08-18 14:08:57.926  2654  2688 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-18 14:08:57.926  2654  2688 I bt_vendor: epilog_cb
08-18 14:08:57.926  2654  2688 I bt_hci  : epilog_finished_callback
,08-18 14:08:57.933  2654  2677 I bt_hci_h4: hal_close
,08-18 14:08:57.934  2654  2677 I bt_userial_vendor: device fd = 51 close
,08-18 14:08:58.026  3885  3885 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.026  3885  3885 D StrictMode: 	,at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 14:08:58.026  3885  3885 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 14:08:58.026  3885  3885 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 14:08:58.026  3885  3885 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 14:08:58.026  3885  3885 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.k.d(PG:583)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.026  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:08:58.027  3885  3885 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at an,droid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:08:58.027  3885  3885 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.027  3885  3885 D StrictM,ode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:08:58.027  3885  3885 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:08:58.027  3885  3885 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:08:58.064   871  2244 I ActivityManager: Start proc 3919:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-18 14:08:58.065   871  2244 I ActivityManager: Killing 3556:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-18 14:08:58.090  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 14:08:58.137  2654  2669 D bt_stack_manager: event_shut_down_stack finished.
,08-18 14:08:58.138  2654  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-18 14:08:58.140  2654  2668 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-18 14:08:58.141  2654  2654 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 14:08:58.141  2654  2654 D BtGatt.GattService: Received stop request...Stopping profile...
,08-18 14:08:58.141  2654  2654 D BtGatt.GattService: stop()
08-18 14:08:58.142  2654  2654 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 14:08:58.144  2654  2654 V BluetoothAdapterState: isTurningOff()=false
08-18 14:08:58.144  2654  2654 V BluetoothAdapterState: isTurningOn()=false
,08-18 14:08:58.144  2654  2654 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:08:58.144  2654  2654 V BluetoothAdapterState: isBleTurningOff()=true
08-18 14:08:58.144  2654  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-18 14:08:58.145  2654  2668 D BluetoothAdapterProperties: Setting state to 10
08-18 14:08:58.145  2654  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-18 14:08:58.145  2654  2668 I BluetoothAdapterState: Entering OffState
,08-18 14:08:58.147   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-18 14:08:58.154  2654  2654 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-18 14:08:58.154  2654  2654 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-18 14:08:58.154  2654  2654 I BluetoothServiceJni: cleanupNative: return from cleanup
08-18 14:08:58.155  2654  2669 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 14:08:58.157  2654  2669 D bt_stack_manager: event_clean_up_stack finished.
,08-18 14:08:58.161  3919  3919 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-18 14:08:58.167  2654  2654 I art     : System.exit called, status: 0
,08-18 14:08:58.167  2654  2654 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 14:08:58.190  3885  3916 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-18 14:08:58.242   871   881 I ActivityManager: Process com.android.bluetooth (pid 2654) has died
,08-18 14:08:58.251   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@769817e:true
,08-18 14:08:58.263  3919  3919 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-18 14:08:58.282  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 14:08:58.300   871  1939 I ActivityManager: Start proc 3947:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-18 14:08:58.306  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:08:58.364  3947  3947 D AdapterServiceConfig: Adding HeadsetService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding A2dpService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding HidService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding HealthService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding PanService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding GattService
08-18 14:08:58.365  3947  3947 D AdapterServiceConfig: Adding BluetoothMapService
08-18 14:08:58.367   871  1939 I ActivityManager: Killing 3456:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-18 14:08:58.421  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:08:58.458  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 14:08:58.461  1720  2438 I iu.UploadsManager: num queued entries: 0
,08-18 14:08:58.461  1720  2438 I iu.UploadsManager: num updated entries: 0
08-18 14:08:58.462  1720  2438 I iu.SyncManager: NEXT; no task
,08-18 14:08:58.467  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 14:08:58.472  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 14:08:58.512   871   882 I ActivityManager: Start proc 3960:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-18 14:08:58.575  3960  3960 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-18 14:08:58.579  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:08:58.589  3960  3960 D SprintDMHelper: simOperator: 
08-18 14:08:58.589  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 14:08:58.627   871   882 I ActivityManager: Start proc 3972:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-18 14:08:58.629   871   882 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-18 14:08:58.785  2398  3986 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-18 14:08:58.789   871  1932 I ActivityManager: Start proc 3987:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-18 14:08:58.795   871  1942 I ActivityManager: Killing 3651:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-18 14:08:58.874  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-18 14:08:58.938  3987  3987 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-18 14:08:58.938  3987  3987 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-18 14:08:58.938  3987  3987 I GAv4    :   adb logcat -s GAv4
,08-18 14:08:58.954  3987  3987 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-18 14:08:58.963  3987  3987 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-18 14:08:58.996  3987  4004 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-18 14:08:59.122  3987  3987 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-18 14:08:59.163  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-18 14:08:59.173  3987  3987 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6116-6119)
08-18 14:08:59.173  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 14:08:59.190  3987  3987 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e019eef}
,08-18 14:08:59.190  3987  3987 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 14:08:59.191  3987  3987 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-18 14:08:59.201  3987  3987 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-18 14:08:59.202  3987  3987 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-18 14:08:59.218  3987  3987 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-18 14:08:59.234  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 14:08:59.234  3987  3987 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 14:08:59.234  3987  3987 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 14:08:59.234  3987  3987 I Adreno  : Build Date                       : 10/20/15
08-18 14:08:59.234  3987  3987 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 14:08:59.234  3987  3987 I Adreno  : Local Branch                     : M14
08-18 14:08:59.234  3987  3987 I Adreno  : Remote Branch                    : 
08-18 14:08:59.234  3987  3987 I Adreno  : Remote Branch                    : 
08-18 14:08:59.234  3987  3987 I Adreno  : Reconstruct Branch               : 
,08-18 14:08:59.305  3987  3987 I NSApplication: Starting up...
,08-18 14:08:59.314  3987  4033 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-18 14:08:59.328   871  1942 I ActivityManager: Start proc 4038:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-18 14:08:59.329   871  1942 I ActivityManager: Killing 3666:com.android.musicfx/u0a18 (adj 15): empty #17
,08-18 14:08:59.434  4038  4038 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-18 14:08:59.659   871  1373 I ActivityManager: Killing 2218:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-18 14:09:00.628   871   881 D WifiService: setWifiEnabled: true pid=3798, uid=10000
,08-18 14:09:00.628   871   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:09:00.645   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-18 14:09:00.652  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:00.652  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:00.652  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:00.653  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:00.656  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:00.656  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:00.657  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:00.657  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:00.677   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-18 14:09:00.678   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-18 14:09:00.680   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-18 14:09:00.681   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-18 14:09:00.681   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-18 14:09:00.681   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-18 14:09:00.681   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 14:09:00.698   373   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 14:09:00.698   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.75 rxSuccessRate=17.62 delta 1000 -> 994
,08-18 14:09:00.700   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:00.701   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-18 14:09:00.701   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-18 14:09:00.708   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-18 14:09:00.708   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:00.710   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
08-18 14:09:00.711   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-18 14:09:00.719   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 14:09:00.779   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-18 14:09:00.781  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 14:09:01.203  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 14:09:01.251  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-18 14:09:01.254  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-18 14:09:01.261   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:09:01.271   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 14:09:01.272   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-18 14:09:01.273   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:01.297   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:01.316   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:01.317   871  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-18 14:09:01.333   871  4061 D DhcpClient: Receive thread started
,08-18 14:09:01.337   871  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-18 14:09:01.340   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 14:09:01.432   871  1305 E native  : do suspend false
,08-18 14:09:01.453   871  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 14:09:01.468   871  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-18 14:09:01.469   871  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-18 14:09:01.474   871  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 14:09:01.487   871  4061 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 14:09:01.488   871  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-18 14:09:01.493   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:01.505   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 14:09:01.506   871  1873 D DhcpClient: Scheduling renewal in 86399s
,08-18 14:09:01.514   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 14:09:01.518   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 14:09:01.518   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 14:09:01.519   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-18 14:09:01.521   871  1307 D ConnectivityService: Adding iface wlan0 to network 101
08-18 14:09:01.532   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-18 14:09:01.581   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-18 14:09:01.581   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-18 14:09:01.584   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-18 14:09:01.585   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-18 14:09:01.586   871  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-18 14:09:01.591   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 14:09:01.596   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-18 14:09:01.597   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-18 14:09:01.598   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-18 14:09:01.598   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-18 14:09:01.598   871  1307 D ConnectivityService:    accepting network in place of null
,08-18 14:09:01.598   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 14:09:01.599   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 14:09:01.626   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:01.642   871  4060 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138588, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 14:09:01.660   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:01.667   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-18 14:09:01.667   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:01.670   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-18 14:09:01.671   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-18 14:09:01.683  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:01.683  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:09:01.684  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:01.684  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:01.688  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:01.688  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:09:01.688  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:01.689  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:01.696  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-18 14:09:01.707   871  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:815::200e
,08-18 14:09:01.716  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 14:09:01.720  1720  2438 I iu.UploadsManager: num queued entries: 0
,08-18 14:09:01.720  1720  2438 I iu.UploadsManager: num updated entries: 0
,08-18 14:09:01.723  1720  2438 I iu.SyncManager: NEXT; no task
,08-18 14:09:01.725  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 14:09:01.727  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 14:09:01.729  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:01.731  1720  4073 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 14:09:01.731  1720  4073 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 14:09:01.732  1720  4073 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 14:09:01.735  3960  3960 D SprintDMHelper: simOperator: 
08-18 14:09:01.735  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 14:09:01.737  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:09:01.739  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:09:01.772   871  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 12:09:01 GMT], X-Android-Received-Millis=[1471522141771], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471522141742]}
,08-18 14:09:01.772  1507  2964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-18 14:09:01.772  1507  2964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.,
08-18 14:09:01.772  1507  2964 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 14:09:01.772  1507  2964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 14:09:01.773   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-18 14:09:01.773   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-18 14:09:01.774   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-18 14:09:01.775   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-18 14:09:01.797  1720  4073 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-18 14:09:01.851  2398  4076 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 14:09:02.668   871  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-18 14:09:03.362   871  2052 I ActivityManager: Killing 3689:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-18 14:09:03.637   871  1373 D WifiService: setWifiEnabled: false pid=3798, uid=10000
,08-18 14:09:03.638   871  1373 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:09:03.655  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-18 14:09:03.656   871  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 14:09:03.657   871  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-18 14:09:03.657   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 14:09:03.657   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:03.671   871  1873 D DhcpClient: Clearing IP address
,08-18 14:09:03.672   373   869 D CommandListener: Clearing all IP addresses on wlan0
,08-18 14:09:03.675   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:03.677   871  4061 D DhcpClient: Receive thread stopped
,08-18 14:09:03.679  1507  4081 V NativeCrypto: Read error: ssl=0x9a8b7400: I/O error during system call, Connection timed out
,08-18 14:09:03.681  1507  4081 V NativeCrypto: SSL shutdown failed: ssl=0x9a8b7400: I/O error during system call, Broken pipe
,08-18 14:09:03.683   871  2243 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-18 14:09:03.683   871  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-18 14:09:03.684   871  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:815::200e
,08-18 14:09:03.693   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-18 14:09:03.694   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-18 14:09:03.696   871  4059 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:815::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-18 14:09:03.700   396   396 E Parcel  : Reading a NULL string not supported here.
,08-18 14:09:03.702   871  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-18 14:09:03.702   871  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-18 14:09:03.705   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 14:09:03.731   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:03.762   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:03.763   871  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-18 14:09:03.763   373   869 D CommandListener: Clearing all IP addresses on wlan0
08-18 14:09:03.764   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:03.768   871   888 D Tethering: MasterInitialState.processMessage what=3
08-18 14:09:03.772  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-18 14:09:03.772  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:03.772  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:03.772  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.772  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:03.773  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:03.773  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:03.773  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:03.773  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:03.784   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:09:03.787  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:03.787  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:03.787  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.787  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:03.788  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:03.788  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:03.788  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:03.788  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:03.788   871  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-18 14:09:03.790  2103  2330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 14:09:03.795  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 14:09:03.803  1720  2438 I iu.UploadsManager: num queued entries: 0
,08-18 14:09:03.803  1720  2438 I iu.UploadsManager: num updated entries: 0
,08-18 14:09:03.806  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 14:09:03.808  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 14:09:03.810  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:03.815  3960  3960 D SprintDMHelper: simOperator: 
,08-18 14:09:03.815  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 14:09:03.841   373   869 E Netd    : netlink response contains error (No such file or directory)
,08-18 14:09:03.842   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 14:09:03.848  1720  2438 I iu.SyncManager: NEXT; no task
,08-18 14:09:03.853  2398  4093 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-18 14:09:03.946  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:09:03.985  1507  2192 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-18 14:09:03.985  1507  2192 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-18 14:09:03.985  1507  2192 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 14:09:03.985  1507  2192 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 14:09:04.023  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-18 14:09:04.024  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 14:09:04.024  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-18 14:09:06.687   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8a9e9aa:true
,08-18 14:09:06.688  3947  3947 D BluetoothAdapterState: make() - Creating AdapterState
,08-18 14:09:06.693  3947  3947 I bt_bluedroid: init
,08-18 14:09:06.694  3947  4097 I BluetoothAdapterState: Entering OffState
,08-18 14:09:06.699  3947  4098 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-18 14:09:06.700  3947  4098 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 14:09:06.700  3947  4098 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-18 14:09:06.700  3947  4098 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 14:09:06.702  3947  3947 I bt_bluedroid: get_profile_interface socket
,08-18 14:09:06.706  3947  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 14:09:06.707  3947  3947 I bt_bluedroid: get_profile_interface sdp
,08-18 14:09:06.711  3947  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 14:09:06.736  3947  3958 I bt_bluedroid: config_hci_snoop_log
,08-18 14:09:06.740   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-18 14:09:06.750  3947  4097 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 14:09:06.750  3947  4097 D BluetoothAdapterProperties: Setting state to 14
,08-18 14:09:06.750  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 14:09:06.752  3947  4097 D BluetoothBondStateMachine: make
,08-18 14:09:06.755  3947  4102 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 14:09:06.758  3947  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:09:06.759  3947  3947 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 14:09:06.762  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:06.763  3947  3947 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 14:09:06.764  3947  3947 D BtGatt.GattService: Received start request. Starting profile...
,08-18 14:09:06.764  3947  3947 D BtGatt.GattService: start()
,08-18 14:09:06.764  3947  3947 I bt_bluedroid: get_profile_interface gatt
,08-18 14:09:06.765  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:06.765  3947  3947 D BtGatt.AdvertiseManager: advertise manager created
,08-18 14:09:06.772  3947  3947 V BluetoothAdapterState: isTurningOff()=false,
08-18 14:09:06.772  3947  3947 V BluetoothAdapterState: isTurningOn()=false
,08-18 14:09:06.772  3947  3947 V BluetoothAdapterState: isBleTurningOn()=true
,08-18 14:09:06.772  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:06.772  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-18 14:09:06.772  3947  4097 I bt_bluedroid: enable
08-18 14:09:06.773  3947  4098 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
08-18 14:09:06.773  3947  4098 I bt_hci  : start_up
,08-18 14:09:06.780  3947  4098 I bt_vendor: alloc value 0xb3939189
,08-18 14:09:06.780  3947  4098 I bt_vendor: init
08-18 14:09:06.780  3947  4098 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf,
08-18 14:09:06.780  3947  4098 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 14:09:06.888  3947  4098 D bt_hci  : start_up starting async portion
,08-18 14:09:06.888  3947  4105 I bt_hci  : event_finish_startup
,08-18 14:09:06.888  3947  4105 I bt_hci_h4: hal_open
,08-18 14:09:06.888  3947  4105 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 14:09:06.894  3947  4105 I bt_userial_vendor: device fd = 51 open
,08-18 14:09:06.931  3947  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 14:09:06.963  3947  4105 D bt_hwcfg: Chipset BCM4354A2,
08-18 14:09:06.963  3947  4105 D bt_hwcfg: Target name = [BCM4354A2]
08-18 14:09:06.963  3947  4105 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 14:09:07.651  3947  4105 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-18 14:09:07.653  3947  4105 D bt_hwcfg: Settlement delay -- 100 ms
,08-18 14:09:07.653  3947  4105 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 14:09:07.770  3947  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 14:09:07.771  3947  4105 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 14:09:07.800  3947  4105 I bt_hwcfg: vendor lib fwcfg completed
,08-18 14:09:07.800  3947  4105 I bt_vendor: firmware callback
08-18 14:09:07.801  3947  4105 I bt_hci  : firmware_config_callback
,08-18 14:09:07.812  3947  4109 I bt_btu  : btu_task pending for preload complete event
,08-18 14:09:07.812  3947  4109 I bt_btu_task: Bluetooth chip preload is complete
,08-18 14:09:07.813  3947  4109 I bt_btu  : btu_task received preload complete event
,08-18 14:09:07.822  3947  4109 I         : BTE_InitTraceLevels -- TRC_HCI
,08-18 14:09:07.822  3947  4109 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-18 14:09:07.823  3947  4109 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-18 14:09:07.823  3947  4109 I         : BTE_InitTraceLevels -- TRC_AVDT
08-18 14:09:07.823  3947  4109 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-18 14:09:07.824  3947  4109 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 14:09:07.824  3947  4109 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 14:09:07.824  3947  4109 I         : BTE_InitTraceLevels -- TRC_BTM
,08-18 14:09:07.825  3947  4109 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 14:09:07.825  3947  4109 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 14:09:07.825  3947  4109 I         : BTE_InitTraceLevels -- TRC_SDP
,08-18 14:09:07.825  3947  4109 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 14:09:07.826  3947  4109 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 14:09:07.826  3947  4109 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 14:09:07.827  3947  4109 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 14:09:07.960  3947  4109 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-18 14:09:07.961  3947  4109 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-18 14:09:07.976  3947  4101 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-18 14:09:07.979  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 14:09:07.980  3947  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-18 14:09:07.984  3947  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 14:09:07.987  3947  4101 D BluetoothAdapterProperties: Scan Mode:20
,08-18 14:09:07.987  3947  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 14:09:07.988  3947  4101 D bt_hci  : do_postload posting postload work item
08-18 14:09:07.988  3947  4105 I bt_hci  : event_postload
08-18 14:09:07.988  3947  4105 I bt_vendor: sco_config_cb
08-18 14:09:07.988  3947  4105 I bt_hci  : sco_config_callback postload finished.
08-18 14:09:07.991  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:07.992  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:07.993  3947  4101 D bt_bte_conf: Device ID record 1 : primary
,08-18 14:09:07.993  3947  4101 D bt_bte_conf:   vendorId            = 000f
,08-18 14:09:07.993  3947  4101 D bt_bte_conf:   vendorIdSource      = 0001
,08-18 14:09:07.993  3947  4101 D bt_bte_conf:   product             = 1200
,08-18 14:09:07.994  3947  4101 D bt_bte_conf:   version             = 1436
,08-18 14:09:07.994  3947  4101 D bt_bte_conf:   clientExecutableURL = 
,08-18 14:09:07.994  3947  4101 D bt_bte_conf:   serviceDescription  = 
,08-18 14:09:07.994  3947  4101 D bt_bte_conf:   documentationURL    = 
,08-18 14:09:07.995  3947  4101 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-18 14:09:07.995  3947  4098 D bt_stack_manager: event_start_up_stack finished
08-18 14:09:07.996  3947  4105 I bt_vendor: low_power_mode_cb
08-18 14:09:07.997  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-18 14:09:07.997  3947  4097 D BluetoothAdapterProperties: Setting state to 15
,08-18 14:09:07.998  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-18 14:09:08.004  3947  4097 I BluetoothAdapterState: Entering BleOnState
08-18 14:09:08.005  3947  4097 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-18 14:09:08.005  3947  4097 D BluetoothAdapterProperties: Setting state to 11
08-18 14:09:08.005  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-18 14:09:08.009  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:08.010  3947  3947 D HeadsetService: Received start request. Starting profile...
08-18 14:09:08.013  3947  3947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 14:09:08.013  3947  3947 D HeadsetStateMachine: make
08-18 14:09:08.025  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:08.026  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:08.037  3947  3947 D HeadsetStateMachine: max_hf_connections = 1
08-18 14:09:08.037  3947  3947 I bt_bluedroid: get_profile_interface handsfree
08-18 14:09:08.039  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 14:09:08.039  3947  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 14:09:08.040  3947  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:09:08.042  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:08.043  3947  3947 D A2dpService: Received start request. Starting profile...
,08-18 14:09:08.044  3947  3947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-18 14:09:08.044  3947  3947 I bt_bluedroid: get_profile_interface avrcp
,08-18 14:09:08.052  3947  3947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-18 14:09:08.052  3947  3947 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:09:08.052  3947  3947 D A2dpStateMachine: make
,08-18 14:09:08.054  3947  3947 I bt_bluedroid: get_profile_interface a2dp
,08-18 14:09:08.055  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-18 14:09:08.056  3947  4118 D A2dpStateMachine: Enter Disconnected: -2
,08-18 14:09:08.056  3947  3947 I BluetoothHidServiceJni: classInitNative: succeeds
08-18 14:09:08.057  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:08.058  3947  3947 D HidService: Received start request. Starting profile...
,08-18 14:09:08.058  3947  3947 I bt_bluedroid: get_profile_interface hidhost
08-18 14:09:08.058  3947  4101 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-18 14:09:08.059  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-18 14:09:08.059  3947  3947 D HidService: setHidService(): set to: null
,08-18 14:09:08.062  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:09:08.063  3947  3947 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-18 14:09:08.064  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:08.064  3947  3947 D HealthService: Received start request. Starting profile...
,08-18 14:09:08.066  3947  3947 I bt_bluedroid: get_profile_interface health
,08-18 14:09:08.067  3867  3867 D BluetoothInputDevice: Proxy object connected
,08-18 14:09:08.068  3867  3867 D HidProfile: Bluetooth service connected
08-18 14:09:08.067  3947  3947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-18 14:09:08.069  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:08.070  3947  3947 D PanService: Received start request. Starting profile...
08-18 14:09:08.070  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
,08-18 14:09:08.071  3947  3947 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 14:09:08.071  3947  3947 I bt_bluedroid: get_profile_interface pan
,08-18 14:09:08.072  3867  3867 D PanProfile: Bluetooth service connected
08-18 14:09:08.072  3947  4101 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-18 14:09:08.074  3947  3947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:08.074  3947  3947 D BluetoothMapService: Received start request. Starting profile...
,08-18 14:09:08.075  3947  3947 D BluetoothMapService: start()
08-18 14:09:08.075  3867  3867 D BluetoothMap: Proxy object connected
08-18 14:09:08.075  3867  3867 D MapProfile: Bluetooth service connected
,08-18 14:09:08.075  3867  3867 D BluetoothMap: getConnectedDevices()
,08-18 14:09:08.076  3867  3867 D BluetoothMap: Bluetooth is Not enabled
08-18 14:09:08.076  3947  3947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-18 14:09:08.077  3947  3947 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-18 14:09:08.077  3947  3947 D BluetoothMapAppObserver: createReceiver()
,08-18 14:09:08.078  3947  3947 D BluetoothMapAppObserver: initObservers()
08-18 14:09:08.078  3947  3947 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 14:09:08.083  3947  4115 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-18 14:09:08.084  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-18 14:09:08.084  3947  3947 V BluetoothAdapterState: isTurningOn()=true
,08-18 14:09:08.084  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.084  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:08.085  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-18 14:09:08.085  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:08.085  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.085  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:08.086  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:08.086  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:08.086  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.086  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:08.088  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:08.089  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:08.090  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 14:09:08.090  3947  4097 D BluetoothAdapterProperties: ScanMode =  20
08-18 14:09:08.090  3947  4097 D BluetoothAdapterProperties: State =  11
,08-18 14:09:08.092  3947  4101 D BluetoothAdapterProperties: Scan Mode:21
,08-18 14:09:08.092  3947  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:09:08.092  3947  4097 D BluetoothAdapterProperties: Setting state to 12
08-18 14:09:08.092  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 14:09:08.093  1920  2082 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:08.093  3947  4097 I BluetoothAdapterState: Entering OnState
,08-18 14:09:08.094  1349  1980 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:08.095  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:08.095  3867  3879 D BluetoothPbap: onBluetoothStateChange: up=true
,08-18 14:09:08.096  1349  3881 D BluetoothMap: onBluetoothStateChange: up=true
,08-18 14:09:08.096  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:08.099   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:08.099  1349  1349 D BluetoothMap: Proxy object connected
08-18 14:09:08.099  1349  1364 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 14:09:08.099  1349  1349 D MapProfile: Bluetooth service connected
,08-18 14:09:08.099  1349  1349 D BluetoothMap: getConnectedDevices()
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:08.099  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:08.101  1349  1980 D BluetoothPan: onBluetoothStateChange on: true
08-18 14:09:08.102  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:08.102  1349  1349 D BluetoothA2dp: Proxy object connected
08-18 14:09:08.103  3867  3877 D BluetoothPan: onBluetoothStateChange on: true
08-18 14:09:08.103   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:08.103  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 14:09:08.103  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 14:09:08.103  1349  1349 D PanProfile: Bluetooth service connected
,08-18 14:09:08.104  3947  3947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 14:09:08.104   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:08.104  3947  3947 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-18 14:09:08.105  1349  1364 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 14:09:08.105  1349  1349 D BluetoothInputDevice: Proxy object connected
08-18 14:09:08.106  1349  1349 D HidProfile: Bluetooth service connected
08-18 14:09:08.106   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 14:09:08.106  3947  3947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:09:08.106   871   871 D BluetoothA2dp: Proxy object connected
08-18 14:09:08.106  3867  3879 D BluetoothMap: onBluetoothStateChange: up=true
08-18 14:09:08.107  3867  3877 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 14:09:08.111  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:08.112   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-18 14:09:08.112  3867  3867 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-18 14:09:08.112  3947  3947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:09:08.112  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:08.113  3947  3947 D ObexServerSockets: Succeed to create listening sockets 
08-18 14:09:08.113  3947  3947 D ObexServerSockets0: startAccept()
08-18 14:09:08.113  3947  3947 D ObexServerSockets0: prepareForNewConnect()
08-18 14:09:08.115  3947  3947 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-18 14:09:08.115  3947  3947 D BluetoothSdpJni: SDP Create record success - handle: 0
08-18 14:09:08.116  3947  3947 D BluetoothMapService: onReceive
08-18 14:09:08.116  3947  3947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:09:08.116  3947  3947 D BluetoothMapService: STATE_ON
08-18 14:09:08.118  3867  3867 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-18 14:09:08.119  3947  4126 D ObexServerSockets0: Accepting socket connection...
,08-18 14:09:08.120  3947  4125 D ObexServerSockets0: Accepting socket connection...
,08-18 14:09:08.128  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 14:09:08.131  3867  3867 D BluetoothA2dp: Proxy object connected
,08-18 14:09:08.136  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:09:08.136  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:09:08.145  3947  3947 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-18 14:09:08.145  3867  3867 D BluetoothPbap: Proxy object connected
,08-18 14:09:08.145  1349  1349 D BluetoothPbap: Proxy object connected
08-18 14:09:08.145  3947  3947 D ObexServerSockets0: prepareForNewConnect()
08-18 14:09:08.145  3867  3867 D PbapServerProfile: Bluetooth service connected
08-18 14:09:08.145  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-18 14:09:08.159  3947  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:09:08.194   871   871 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.195  1349  3881 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.195  3947  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:09:08.195  1349  1349 D HeadsetProfile: Bluetooth service connected
08-18 14:09:08.195  1920  2203 D BluetoothHeadset: Proxy object connected
08-18 14:09:08.197  3947  4134 I BtOppRfcommListener: Accept thread started.
08-18 14:09:08.197  1349  1364 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.197   871   871 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.197   871   871 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.197  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-18 14:09:08.199   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.203   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.205   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.224  3867  3879 D BluetoothHeadset: Proxy object connected
,08-18 14:09:08.225  3867  3867 D HeadsetProfile: Bluetooth service connected
,08-18 14:09:09.602   871  1307 D ConnectivityService: handlePromptUnvalidated 101
,08-18 14:09:09.653  3947  4097 D BluetoothAdapterState: Current state: ON, message: 23
,08-18 14:09:09.654  3947  4097 D BluetoothAdapterProperties: Setting state to 13
,08-18 14:09:09.654  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 14:09:09.657  3947  4097 D BluetoothAdapterProperties: onBluetoothDisable()
,08-18 14:09:09.661  3947  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:09:09.670  3947  3947 D BluetoothMapService: onReceive
,08-18 14:09:09.670  3947  3947 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-18 14:09:09.671  3947  3947 D BluetoothMapService: STATE_TURNING_OFF
,08-18 14:09:09.671  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:09.671  3947  3947 D BluetoothMapService: MAP Service closeService in
,08-18 14:09:09.672  3947  3947 D BluetoothMapMasInstance0: MAP Service shutdown
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:09.672  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:09.672  3947  3947 D ObexServerSockets0: shutdown(block = true)
,08-18 14:09:09.673  3947  4125 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-18 14:09:09.674  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:09.674  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:09.679  3947  4101 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:09:09.681  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-18 14:09:09.680  3947  3947 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-18 14:09:09.682  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 14:09:09.682  3947  4126 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:09.682  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 14:09:09.682  3947  4112 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-18 14:09:09.683  3947  3947 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 14:09:09.683  3947  3947 I BtOppRfcommListener: stopping Accept Thread
08-18 14:09:09.683  3947  4134 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-18 14:09:09.683  3798  3798 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 14:09:09.684  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 14:09:09.684  3947  4134 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 14:09:09.686  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:09.687  3947  3947 D HeadsetService: Received stop request...Stopping profile...
,08-18 14:09:09.689  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:09.690  3867  3877 D BluetoothHeadset: Proxy object disconnected
08-18 14:09:09.690   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:09:09.689  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 14:09:09.691  1920  2204 D BluetoothHeadset: Proxy object disconnected
,08-18 14:09:09.691  1349  1364 D BluetoothHeadset: Proxy object disconnected
08-18 14:09:09.691   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:09:09.692   871   871 D BluetoothHeadset: Proxy object disconnected
08-18 14:09:09.692  3947  3947 D A2dpService: Received stop request...Stopping profile...
08-18 14:09:09.692  3947  4118 D A2dpStateMachine: Exit Disconnected: -1
,08-18 14:09:09.696   871   871 D BluetoothA2dp: Proxy object disconnected
,08-18 14:09:09.697  3867  3867 D HeadsetProfile: Bluetooth service disconnected
,08-18 14:09:09.697  3947  3947 D HidService: Received stop request...Stopping profile...
08-18 14:09:09.697  3947  3947 D HidService: Stopping Bluetooth HidService
,08-18 14:09:09.699  3947  3947 D HealthService: Received stop request...Stopping profile...
,08-18 14:09:09.700  3947  3947 V BluetoothAdapterState: isTurningOff()=true
,08-18 14:09:09.700  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:09.701  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:09.701  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:09.701  3947  3947 D PanService: Received stop request...Stopping profile...
,08-18 14:09:09.704  3947  3947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-18 14:09:09.704  3947  3947 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-18 14:09:09.704  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:09:09.704  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:09:09.704  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:09:09.704  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-18 14:09:09.705  3947  3947 D BluetoothMapService: Received stop request...Stopping profile...
08-18 14:09:09.705  3947  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-18 14:09:09.705  3947  3947 D BluetoothMapService: stop()
,08-18 14:09:09.706  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-18 14:09:09.706  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-18 14:09:09.706  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-18 14:09:09.706  1349  1349 D HidProfile: Bluetooth service disconnected
,08-18 14:09:09.707  3947  3947 D BluetoothMapAppObserver: deinitObservers()
08-18 14:09:09.707  3947  3947 D BluetoothMapAppObserver: removeReceiver()
08-18 14:09:09.707  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-18 14:09:09.707  1349  1349 D PanProfile: Bluetooth service disconnected
,08-18 14:09:09.708  1349  1349 D BluetoothMap: Proxy object disconnected
,08-18 14:09:09.708  1349  1349 D MapProfile: Bluetooth service disconnected,
08-18 14:09:09.708  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-18 14:09:09.708  3947  3947 V BluetoothAdapterState: isTurningOn()=false
,08-18 14:09:09.709  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:09.709  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:09.710  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 14:09:09.710  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 14:09:09.710  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-18 14:09:09.710  3947  4109 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:09:09.710  3947  4109 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:09:09.710  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:09.710  3947  4109 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 14:09:09.710  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 14:09:09.711  3947  4109 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 14:09:09.711  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:09.711  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-18 14:09:09.712  3867  3867 D DockEventReceiver: finishStartingService: stopping service
08-18 14:09:09.713  3867  3867 D BluetoothA2dp: Proxy object disconnected
08-18 14:09:09.714  3867  3867 D BluetoothInputDevice: Proxy object disconnected
08-18 14:09:09.714  3867  3867 D HidProfile: Bluetooth service disconnected
08-18 14:09:09.714  3867  3867 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-18 14:09:09.714  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 14:09:09.714  3867  3867 D PanProfile: Bluetooth service disconnected
08-18 14:09:09.715  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-18 14:09:09.715  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:09.715  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:09.715  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:09.715  3947  3947 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 14:09:09.715  3947  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 14:09:09.715  3947  3947 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-18 14:09:09.716  3867  3867 D BluetoothMap: Proxy object disconnected
08-18 14:09:09.716  3947  3947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 14:09:09.716  3947  4101 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-18 14:09:09.716  3867  3867 D MapProfile: Bluetooth service disconnected
08-18 14:09:09.716  3947  3947 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-18 14:09:09.717  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-18 14:09:09.717  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:09.717  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:09.717  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:09.717  3947  3947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 14:09:09.717  3947  3947 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-18 14:09:09.718  3947  3947 D BluetoothMapService: MAP Service closeService in
08-18 14:09:09.718  3947  3947 V BluetoothAdapterState: isTurningOff()=true
08-18 14:09:09.718  3947  3947 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:09.718  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:09.718  3947  3947 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:09.719  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-18 14:09:09.719  3947  3947 D BluetoothMapService: cleanup()
08-18 14:09:09.719  3947  3947 D BluetoothMapService: MAP Service closeService in
,08-18 14:09:09.719  3947  4097 D BluetoothAdapterProperties: Setting state to 15
08-18 14:09:09.719  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 14:09:09.719  3947  4097 I BluetoothAdapterState: Entering BleOnState
08-18 14:09:09.720  3867  3877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:09:09.721  1349  1349 D BluetoothPbap: Proxy object disconnected
08-18 14:09:09.721  1349  1349 D PbapServerProfile: Bluetooth service disconnected
,08-18 14:09:09.721  1920  1935 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 14:09:09.721  1349  3881 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:09:09.725  3867  3879 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 14:09:09.725  1349  1980 D BluetoothMap: onBluetoothStateChange: up=false
08-18 14:09:09.721  3867  3867 D BluetoothPbap: Proxy object disconnected
08-18 14:09:09.727  3867  3867 D PbapServerProfile: Bluetooth service disconnected
,08-18 14:09:09.727   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:09:09.728  1349  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:09:09.728  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
08-18 14:09:09.729  3867  3877 D BluetoothPan: onBluetoothStateChange on: false
,08-18 14:09:09.729   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:09:09.729  1349  3881 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 14:09:09.730   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 14:09:09.730  3867  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:09:09.731  1349  1364 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 14:09:09.732   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 14:09:09.732  3867  3877 D BluetoothMap: onBluetoothStateChange: up=false
08-18 14:09:09.733  3867  3879 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 14:09:09.733  3947  4097 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-18 14:09:09.733  3947  4097 D BluetoothAdapterProperties: Setting state to 16
08-18 14:09:09.733  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-18 14:09:09.734  3947  4097 D BluetoothAdapterProperties: onBleDisable
,08-18 14:09:09.735  3947  4097 I BluetoothAdapterState: Entering PendingCommandState
08-18 14:09:09.735  3947  4098 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-18 14:09:09.736  3947  4109 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-18 14:09:09.736  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:09.736  3947  4109 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 14:09:09.737  3947  4101 D BluetoothAdapterProperties: Scan Mode:20
08-18 14:09:09.737  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:09.738  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 14:09:09.739  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:09.740  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:09.744  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:09:09.748  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:09:09.936  3947  4101 I bt_hci  : shut_down
,08-18 14:09:09.937  3947  4105 D bt_hwcfg: hw_epilog_process
08-18 14:09:09.938  3947  4105 I bt_vendor: low_power_mode_cb
,08-18 14:09:09.968  3947  4105 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-18 14:09:09.969  3947  4105 I bt_vendor: epilog_cb
08-18 14:09:09.969  3947  4105 I bt_hci  : epilog_finished_callback
,08-18 14:09:09.979  3947  4101 I bt_hci_h4: hal_close
,08-18 14:09:09.981  3947  4101 I bt_userial_vendor: device fd = 51 close
,08-18 14:09:10.103  3947  4098 D bt_stack_manager: event_shut_down_stack finished.
,08-18 14:09:10.105  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-18 14:09:10.111  3947  4097 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-18 14:09:10.111  3947  3947 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 14:09:10.112  3947  3947 D BtGatt.GattService: Received stop request...Stopping profile...
,08-18 14:09:10.113  3947  3947 D BtGatt.GattService: stop()
08-18 14:09:10.113  3947  3947 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 14:09:10.120  3947  3947 V BluetoothAdapterState: isTurningOff()=false
,08-18 14:09:10.120  3947  3947 V BluetoothAdapterState: isTurningOn()=false
,08-18 14:09:10.121  3947  3947 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:10.121  3947  3947 V BluetoothAdapterState: isBleTurningOff()=true
08-18 14:09:10.123  3947  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-18 14:09:10.123  3947  4097 D BluetoothAdapterProperties: Setting state to 10
,08-18 14:09:10.124  3947  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-18 14:09:10.128  3947  4097 I BluetoothAdapterState: Entering OffState
,08-18 14:09:10.130   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-18 14:09:10.149  3947  3947 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-18 14:09:10.149  3947  3947 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-18 14:09:10.149  3947  3947 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-18 14:09:10.150  3947  4098 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 14:09:10.153  3947  4098 D bt_stack_manager: event_clean_up_stack finished.
,08-18 14:09:10.155  3947  3947 I art     : System.exit called, status: 0
,08-18 14:09:10.155  3947  3947 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 14:09:10.209   871  1932 I ActivityManager: Process com.android.bluetooth (pid 3947) has died
,08-18 14:09:12.650  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:09:12.651  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:13.201   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-18 14:09:13.213   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 14:09:13.213   871   891 I Adreno  : Build Date                       : 10/20/15
08-18 14:09:13.213   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 14:09:13.213   871   891 I Adreno  : Local Branch                     : M14
08-18 14:09:13.213   871   891 I Adreno  : Remote Branch                    : 
08-18 14:09:13.213   871   891 I Adreno  : Remote Branch                    : 
08-18 14:09:13.213   871   891 I Adreno  : Reconstruct Branch               : 
,08-18 14:09:13.212  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-18 14:09:13.262   282   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (359 us)
,08-18 14:09:13.883  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 14:09:13.883  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-18 14:09:13.939   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-18 14:09:13.942  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a538d99 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f58b91b, 16908290=android.view.AbsSavedState$1@f58b91b}, android:focusedViewId=100}]}]
08-18 14:09:13.942  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-18 14:09:13.942  3798  3798 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-18 14:09:13.943  3798  3798 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-18 14:09:13.951   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-18 14:09:13.956   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-18 14:09:13.956   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-18 14:09:13.956   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-18 14:09:14.192   282   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-18 14:09:14.203   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-18 14:09:14.210   871  1330 D SurfaceControl: Excessive delay in setPowerMode(): 254ms
08-18 14:09:14.212   871   891 I DreamManagerService: Entering dreamland.
,08-18 14:09:14.213   871   891 I PowerManagerService: Dozing...
,08-18 14:09:14.214   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-18 14:09:14.266   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-18 14:09:14.266   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-18 14:09:14.278   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:09:14.286   871  1305 E native  : do suspend false
,08-18 14:09:14.291  1905  4145 D NfcService: Discovery configuration equal, not updating.
,08-18 14:09:14.323   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:09:14.329   871  1305 E native  : do suspend true
,08-18 14:09:14.408   377  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-18 14:09:14.408   377  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-18 14:09:15.658  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:15.659  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@70f3ab8 added. We now have 6 listener(s)
08-18 14:09:15.659  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:15.664  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:15.664  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b04091 added. We now have 7 listener(s)
08-18 14:09:15.665  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:15.666  3798  3848 I System.out: IsBluetoothEnabled
,08-18 14:09:15.678  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:15.730   871   888 I ActivityManager: Start proc 4153:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-18 14:09:15.862  4153  4153 D AdapterServiceConfig: Adding HeadsetService
,08-18 14:09:15.862  4153  4153 D AdapterServiceConfig: Adding A2dpService
08-18 14:09:15.863  4153  4153 D AdapterServiceConfig: Adding HidService
08-18 14:09:15.863  4153  4153 D AdapterServiceConfig: Adding HealthService
,08-18 14:09:15.863  4153  4153 D AdapterServiceConfig: Adding PanService
08-18 14:09:15.863  4153  4153 D AdapterServiceConfig: Adding GattService
08-18 14:09:15.863  4153  4153 D AdapterServiceConfig: Adding BluetoothMapService
,08-18 14:09:15.880  4153  4153 D BluetoothAdapterState: make() - Creating AdapterState
,08-18 14:09:15.880   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42c82c2:true
,08-18 14:09:15.885  4153  4153 I bt_bluedroid: init
,08-18 14:09:15.887  4153  4165 I BluetoothAdapterState: Entering OffState
,08-18 14:09:15.894  4153  4166 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-18 14:09:15.894  4153  4166 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 14:09:15.895  4153  4166 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-18 14:09:15.895  4153  4166 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 14:09:15.897  4153  4153 I bt_bluedroid: get_profile_interface socket
08-18 14:09:15.899  4153  4153 I bt_bluedroid: get_profile_interface sdp
,08-18 14:09:15.904  4153  4169 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 14:09:15.905  4153  4164 I bt_bluedroid: config_hci_snoop_log
08-18 14:09:15.908  4153  4169 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 14:09:15.910   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-18 14:09:15.921  4153  4165 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 14:09:15.921  4153  4165 D BluetoothAdapterProperties: Setting state to 14
,08-18 14:09:15.922  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 14:09:15.926  4153  4165 D BluetoothBondStateMachine: make
,08-18 14:09:15.932  4153  4170 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 14:09:15.940  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:09:15.943  4153  4153 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 14:09:15.951  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:15.953  4153  4153 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 14:09:15.954  4153  4153 D BtGatt.GattService: Received start request. Starting profile...
,08-18 14:09:15.955  4153  4153 D BtGatt.GattService: start()
08-18 14:09:15.955  4153  4153 I bt_bluedroid: get_profile_interface gatt
,08-18 14:09:15.957  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:15.957  4153  4153 D BtGatt.AdvertiseManager: advertise manager created
,08-18 14:09:15.971  4153  4153 V BluetoothAdapterState: isTurningOff()=false
,08-18 14:09:15.972  4153  4153 V BluetoothAdapterState: isTurningOn()=false
08-18 14:09:15.972  4153  4153 V BluetoothAdapterState: isBleTurningOn()=true
,08-18 14:09:15.972  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:15.973  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-18 14:09:15.974  4153  4165 I bt_bluedroid: enable
08-18 14:09:15.974  4153  4166 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-18 14:09:15.975  4153  4166 I bt_hci  : start_up
,08-18 14:09:15.992  4153  4166 I bt_vendor: alloc value 0xb39aa189
,08-18 14:09:15.992  4153  4166 I bt_vendor: init
08-18 14:09:15.992  4153  4166 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-18 14:09:15.992  4153  4166 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 14:09:16.100  4153  4166 D bt_hci  : start_up starting async portion
,08-18 14:09:16.101  4153  4173 I bt_hci  : event_finish_startup
,08-18 14:09:16.101  4153  4173 I bt_hci_h4: hal_open
08-18 14:09:16.101  4153  4173 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 14:09:16.113  4153  4173 I bt_userial_vendor: device fd = 51 open
08-18 14:09:16.141  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-18 14:09:16.173  4153  4173 D bt_hwcfg: Chipset BCM4354A2
08-18 14:09:16.174  4153  4173 D bt_hwcfg: Target name = [BCM4354A2]
08-18 14:09:16.175  4153  4173 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 14:09:16.833  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 115200,
08-18 14:09:16.834  4153  4173 D bt_hwcfg: Settlement delay -- 100 ms
,08-18 14:09:16.836  4153  4173 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 14:09:16.952  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-18 14:09:16.953  4153  4173 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 14:09:16.982  4153  4173 I bt_hwcfg: vendor lib fwcfg completed
08-18 14:09:16.982  4153  4173 I bt_vendor: firmware callback
08-18 14:09:16.982  4153  4173 I bt_hci  : firmware_config_callback
,08-18 14:09:16.991  4153  4175 I bt_btu  : btu_task pending for preload complete event
08-18 14:09:16.991  4153  4175 I bt_btu_task: Bluetooth chip preload is complete
08-18 14:09:16.991  4153  4175 I bt_btu  : btu_task received preload complete event
,08-18 14:09:17.000  4153  4175 I         : BTE_InitTraceLevels -- TRC_HCI
08-18 14:09:17.000  4153  4175 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-18 14:09:17.000  4153  4175 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-18 14:09:17.000  4153  4175 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-18 14:09:17.001  4153  4175 I         : BTE_InitTraceLevels -- TRC_AVRC
08-18 14:09:17.001  4153  4175 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 14:09:17.001  4153  4175 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 14:09:17.001  4153  4175 I         : BTE_InitTraceLevels -- TRC_BTM
08-18 14:09:17.001  4153  4175 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 14:09:17.002  4153  4175 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 14:09:17.002  4153  4175 I         : BTE_InitTraceLevels -- TRC_SDP
,08-18 14:09:17.002  4153  4175 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 14:09:17.002  4153  4175 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 14:09:17.002  4153  4175 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 14:09:17.003  4153  4175 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 14:09:17.137  4153  4175 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3927d9d
,08-18 14:09:17.137  4153  4175 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3927d9d 
,08-18 14:09:17.145  4153  4169 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-18 14:09:17.146  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 14:09:17.147  4153  4169 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-18 14:09:17.149  4153  4169 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 14:09:17.152  4153  4169 D BluetoothAdapterProperties: Scan Mode:20
,08-18 14:09:17.152  4153  4169 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 14:09:17.153  4153  4169 D bt_hci  : do_postload posting postload work item
,08-18 14:09:17.154  4153  4173 I bt_hci  : event_postload
,08-18 14:09:17.155  4153  4173 I bt_vendor: sco_config_cb
,08-18 14:09:17.155  4153  4173 I bt_hci  : sco_config_callback postload finished.
,08-18 14:09:17.157  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:17.159  4153  4169 D bt_bte_conf: Device ID record 1 : primary
,08-18 14:09:17.160  4153  4169 D bt_bte_conf:   vendorId            = 000f
,08-18 14:09:17.160  4153  4169 D bt_bte_conf:   vendorIdSource      = 0001
08-18 14:09:17.160  4153  4169 D bt_bte_conf:   product             = 1200
08-18 14:09:17.160  4153  4169 D bt_bte_conf:   version             = 1436
08-18 14:09:17.161  4153  4169 D bt_bte_conf:   clientExecutableURL = 
08-18 14:09:17.161  4153  4169 D bt_bte_conf:   serviceDescription  = 
08-18 14:09:17.161  4153  4169 D bt_bte_conf:   documentationURL    = 
08-18 14:09:17.161  4153  4169 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-18 14:09:17.162  4153  4166 D bt_stack_manager: event_start_up_stack finished
,08-18 14:09:17.163  4153  4173 I bt_vendor: low_power_mode_cb
,08-18 14:09:17.164  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-18 14:09:17.165  4153  4165 D BluetoothAdapterProperties: Setting state to 15
,08-18 14:09:17.165  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-18 14:09:17.166  4153  4165 I BluetoothAdapterState: Entering BleOnState
,08-18 14:09:17.170  4153  4165 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-18 14:09:17.171  4153  4165 D BluetoothAdapterProperties: Setting state to 11
08-18 14:09:17.171  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-18 14:09:17.179  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:17.184  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:17.186  4153  4153 D HeadsetService: Received start request. Starting profile...
,08-18 14:09:17.193  4153  4153 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-18 14:09:17.194  4153  4153 D HeadsetStateMachine: make
,08-18 14:09:17.200  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
,08-18 14:09:17.204  4153  4153 D HeadsetStateMachine: max_hf_connections = 1
,08-18 14:09:17.204  4153  4153 I bt_bluedroid: get_profile_interface handsfree
08-18 14:09:17.204  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 14:09:17.204  4153  4169 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 14:09:17.210  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
,08-18 14:09:17.211  4153  4153 D A2dpService: Received start request. Starting profile...
08-18 14:09:17.212  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:09:17.212  4153  4153 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-18 14:09:17.212  4153  4153 I bt_bluedroid: get_profile_interface avrcp
,08-18 14:09:17.218  4153  4153 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 14:09:17.218  4153  4153 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 14:09:17.219  4153  4153 D A2dpStateMachine: make
,08-18 14:09:17.220  4153  4153 I bt_bluedroid: get_profile_interface a2dp
,08-18 14:09:17.221  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-18 14:09:17.222  4153  4184 D A2dpStateMachine: Enter Disconnected: -2
,08-18 14:09:17.223  4153  4153 I BluetoothHidServiceJni: classInitNative: succeeds
,08-18 14:09:17.224  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:17.224  4153  4153 D HidService: Received start request. Starting profile...
,08-18 14:09:17.225  4153  4153 I bt_bluedroid: get_profile_interface hidhost
,08-18 14:09:17.225  4153  4169 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39093e5
08-18 14:09:17.225  4153  4153 D HidService: setHidService(): set to: null
08-18 14:09:17.225  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-18 14:09:17.226  4153  4153 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 14:09:17.227  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:17.228  4153  4153 D HealthService: Received start request. Starting profile...
,08-18 14:09:17.230  4153  4153 I bt_bluedroid: get_profile_interface health
,08-18 14:09:17.231  4153  4153 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 14:09:17.232  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:17.232  4153  4153 D PanService: Received start request. Starting profile...
08-18 14:09:17.232  4153  4153 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 14:09:17.233  4153  4153 I bt_bluedroid: get_profile_interface pan
08-18 14:09:17.233  4153  4169 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-18 14:09:17.235  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:17.236  4153  4153 D BluetoothMapService: Received start request. Starting profile...
08-18 14:09:17.236  4153  4153 D BluetoothMapService: start()
,08-18 14:09:17.239  4153  4153 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-18 14:09:17.240  4153  4153 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-18 14:09:17.240  4153  4153 D BluetoothMapAppObserver: createReceiver()
,08-18 14:09:17.244  4153  4153 D BluetoothMapAppObserver: initObservers()
,08-18 14:09:17.244  4153  4153 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 14:09:17.254  4153  4153 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:17.254  4153  4153 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:17.254  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 14:09:17.254  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:17.257  4153  4182 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-18 14:09:17.257  4153  4153 V BluetoothAdapterState: isTurningOff()=false
,08-18 14:09:17.257  4153  4153 V BluetoothAdapterState: isTurningOn()=true
,08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isTurningOn()=true
,08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:17.258  4153  4153 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:17.259  4153  4153 V BluetoothAdapterState: isTurningOn()=true
,08-18 14:09:17.259  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:17.259  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 14:09:17.260  4153  4153 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:17.260  4153  4153 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:17.260  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 14:09:17.261  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:17.261  4153  4153 V BluetoothAdapterState: isTurningOff()=false
08-18 14:09:17.261  4153  4153 V BluetoothAdapterState: isTurningOn()=true
08-18 14:09:17.261  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
08-18 14:09:17.261  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
08-18 14:09:17.262  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 14:09:17.262  4153  4165 D BluetoothAdapterProperties: ScanMode =  20
08-18 14:09:17.262  4153  4165 D BluetoothAdapterProperties: State =  11
,08-18 14:09:17.263  4153  4165 D BluetoothAdapterProperties: Setting state to 12
08-18 14:09:17.263  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-18 14:09:17.264  4153  4165 I BluetoothAdapterState: Entering OnState
,08-18 14:09:17.264  3867  4143 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 14:09:17.266  4153  4169 D BluetoothAdapterProperties: Scan Mode:21
,08-18 14:09:17.266  4153  4169 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 14:09:17.266  1920  2082 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 14:09:17.267  1349  1364 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 14:09:17.270  3867  3877 D BluetoothPbap: onBluetoothStateChange: up=true
,08-18 14:09:17.272  1349  1361 D BluetoothMap: onBluetoothStateChange: up=true
,08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:17.272  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:17.273  4153  4153 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 14:09:17.273   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 14:09:17.274  1349  1980 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 14:09:17.274  4153  4153 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2),
,08-18 14:09:17.275  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:17.276  1349  3881 D BluetoothPan: onBluetoothStateChange on: true
,08-18 14:09:17.276  4153  4153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:09:17.278  3867  3879 D BluetoothPan: onBluetoothStateChange on: true
,08-18 14:09:17.280   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 14:09:17.280  4153  4153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 14:09:17.280  1349  1364 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 14:09:17.282  4153  4153 D ObexServerSockets: Succeed to create listening sockets 
08-18 14:09:17.282   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 14:09:17.282  4153  4153 D ObexServerSockets0: startAccept()
08-18 14:09:17.282  4153  4153 D ObexServerSockets0: prepareForNewConnect()
,08-18 14:09:17.282  3867  4143 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 14:09:17.284  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 14:09:17.285   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 14:09:17.285  4153  4153 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-18 14:09:17.286  4153  4153 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-18 14:09:17.286  3867  3877 D BluetoothMap: onBluetoothStateChange: up=true
08-18 14:09:17.286  4153  4189 D ObexServerSockets0: Accepting socket connection...
08-18 14:09:17.288  4153  4190 D ObexServerSockets0: Accepting socket connection...
08-18 14:09:17.288  1349  1349 D BluetoothMap: Proxy object connected
08-18 14:09:17.288  1349  1349 D MapProfile: Bluetooth service connected
,08-18 14:09:17.288  1349  1349 D BluetoothMap: getConnectedDevices()
08-18 14:09:17.290   871   871 D BluetoothA2dp: Proxy object connected
,08-18 14:09:17.290  3867  3867 D BluetoothMap: Proxy object connected
,08-18 14:09:17.291  3867  3877 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 14:09:17.292  1349  1349 D BluetoothA2dp: Proxy object connected
,08-18 14:09:17.294   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-18 14:09:17.295  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 14:09:17.295  1349  1349 D PanProfile: Bluetooth service connected
,08-18 14:09:17.297  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:17.291  3867  3867 D MapProfile: Bluetooth service connected
,08-18 14:09:17.299  4153  4153 D BluetoothMapService: onReceive
08-18 14:09:17.298  3867  3867 D BluetoothMap: getConnectedDevices()
08-18 14:09:17.299  4153  4153 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 14:09:17.299  4153  4153 D BluetoothMapService: STATE_ON
08-18 14:09:17.299  1349  1349 D BluetoothInputDevice: Proxy object connected
08-18 14:09:17.299  1349  1349 D HidProfile: Bluetooth service connected
,08-18 14:09:17.301  3867  3867 D BluetoothA2dp: Proxy object connected
,08-18 14:09:17.302  3867  3867 D BluetoothPan: BluetoothPAN Proxy object connected
,08-18 14:09:17.302  3867  3867 D PanProfile: Bluetooth service connected
,08-18 14:09:17.306  3867  3867 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 14:09:17.308  3867  3867 D BluetoothInputDevice: Proxy object connected
,08-18 14:09:17.308  3867  3867 D HidProfile: Bluetooth service connected
,08-18 14:09:17.312  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 14:09:17.313  3867  3867 D DockEventReceiver: finishStartingService: stopping service
,08-18 14:09:17.320  3867  3867 D BluetoothPbap: Proxy object connected
,08-18 14:09:17.320  3867  3867 D PbapServerProfile: Bluetooth service connected
,08-18 14:09:17.322  1349  1349 D BluetoothPbap: Proxy object connected
,08-18 14:09:17.322  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-18 14:09:17.326  4153  4153 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 14:09:17.326  4153  4153 D ObexServerSockets0: prepareForNewConnect()
,08-18 14:09:17.330  4153  4195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:09:17.345  4153  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 14:09:17.347  4153  4199 I BtOppRfcommListener: Accept thread started.
,08-18 14:09:17.368  3867  3877 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.368  1920  2203 D BluetoothHeadset: Proxy object connected
08-18 14:09:17.368   871   871 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.369  3867  3867 D HeadsetProfile: Bluetooth service connected
,08-18 14:09:17.369  1920  2204 D BluetoothHeadset: Proxy object connected
08-18 14:09:17.369  1349  1361 D BluetoothHeadset: Proxy object connected
08-18 14:09:17.369  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-18 14:09:17.369  1349  1361 D BluetoothHeadset: Proxy object connected
08-18 14:09:17.370   871   871 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.370   871   871 D BluetoothHeadset: Proxy object connected
08-18 14:09:17.372  1349  1349 D HeadsetProfile: Bluetooth service connected
08-18 14:09:17.373   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.380   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.382   871   888 D BluetoothHeadset: Proxy object connected
,08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:17.702  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:17.709  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:17.714  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:09:17.715  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@adddbf6 added. We now have 8 listener(s)
08-18 14:09:17.715  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:17.722   871  1927 D WifiService: setWifiEnabled: false pid=3798, uid=10000
,08-18 14:09:17.722   871  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:09:17.735  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:17.736   871  2243 D WifiService: setWifiEnabled: true pid=3798, uid=10000
,08-18 14:09:17.736   871  2243 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 14:09:17.754   871  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:17.769  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:17.777  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:17.786   871  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-18 14:09:17.788   871  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-18 14:09:17.789   871  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-18 14:09:17.790   871  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-18 14:09:17.791   871  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-18 14:09:17.791   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-18 14:09:17.791   871  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 14:09:17.809   373   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 14:09:17.809   871  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.08 delta 1000 -> 1000
,08-18 14:09:17.809   871  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-18 14:09:17.811   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:17.818   871  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-18 14:09:17.818   871  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-18 14:09:17.819   871  1305 E native  : do suspend true
,08-18 14:09:17.827   871  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-18 14:09:17.833   871  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-18 14:09:17.835   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-18 14:09:17.835   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:17.847   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 14:09:17.907   871  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-18 14:09:17.931  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 14:09:18.356  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 14:09:18.400  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-18 14:09:18.403  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-18 14:09:18.409   871  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 14:09:18.425   871  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-18 14:09:18.425   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:18.425   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-18 14:09:18.446   871  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 14:09:18.461   373   869 D CommandListener: Setting iface cfg
08-18 14:09:18.462   871  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-18 14:09:18.468   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 14:09:18.519   871  4207 D DhcpClient: Receive thread started
,08-18 14:09:18.611   871  1305 E native  : do suspend false
,08-18 14:09:18.631   871  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 14:09:18.646   871  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-18 14:09:18.647   871  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-18 14:09:18.650   871  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 14:09:18.663   871  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 14:09:18.664   871  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-18 14:09:18.669   373   869 D CommandListener: Setting iface cfg
,08-18 14:09:18.680   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 14:09:18.681   871  1873 D DhcpClient: Scheduling renewal in 86399s
,08-18 14:09:18.684   871  1305 E native  : do suspend true
,08-18 14:09:18.710   871  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 14:09:18.714   871  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 14:09:18.716   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-18 14:09:18.719   871  1307 D ConnectivityService: Adding iface wlan0 to network 102
,08-18 14:09:18.731   871  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 14:09:18.758  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 14:09:18.763  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 14:09:18.771  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-18 14:09:18.772  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-18 14:09:18.776  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a538d99 Bundle[{}]
,08-18 14:09:18.778  3798  3848 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 14:09:18.778  3798  3848 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-18 14:09:18.780  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-18 14:09:18.782  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-18 14:09:18.783  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-18 14:09:18.785  3798  3848 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 14:09:18.785   871  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-18 14:09:18.785   871  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-18 14:09:18.787   871  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-18 14:09:18.789   871  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-18 14:09:18.791  3798  3848 I System.out: Running OutgoingSocketThread
08-18 14:09:18.792   871  1307 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-18 14:09:18.793  3798  4211 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
08-18 14:09:18.794  3798  4211 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38398
08-18 14:09:18.794  3798  4211 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-18 14:09:18.804   871  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-18 14:09:18.809   871  1307 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-18 14:09:18.809   871  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-18 14:09:18.809   871  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-18 14:09:18.809   871  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-18 14:09:18.809   871  1307 D ConnectivityService:    accepting network in place of null
,08-18 14:09:18.810   871  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 14:09:18.810   871  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 14:09:18.821   871  4206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155767, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 14:09:18.852   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:18.887   373   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 14:09:18.892   871  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:4001:80a::200e
,08-18 14:09:18.892   871  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-18 14:09:18.892   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:18.893   871  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-18 14:09:18.898   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:18.910  3798  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:09:18.912  3798  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:18.923  1992  1992 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-18 14:09:18.951  1720  1720 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 14:09:18.955  1720  2438 I iu.UploadsManager: num queued entries: 0
,08-18 14:09:18.955  1720  2438 I iu.UploadsManager: num updated entries: 0
,08-18 14:09:18.962  1720  2438 I iu.SyncManager: NEXT; no task
,08-18 14:09:18.964  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 14:09:18.965  1720  1720 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 14:09:18.967  3960  3960 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 14:09:18.970   871  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 12:09:18 GMT], X-Android-Received-Millis=[1471522158970], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471522158945]}
,08-18 14:09:18.972   871  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 14:09:18.972   871  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-18 14:09:18.972   871  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-18 14:09:18.973   871  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-18 14:09:18.972  1720  4220 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 14:09:18.976  1720  4220 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 14:09:18.979  3960  3960 D SprintDMHelper: simOperator: 
,08-18 14:09:18.979  3960  3960 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 14:09:18.983  1720  4220 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 14:09:18.994  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:09:19.000  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 14:09:19.073  1507  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-18 14:09:19.073  1507  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-18 14:09:19.073  1507  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 14:09:19.073  1507  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 14:09:19.105  1720  4220 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-18 14:09:19.127  2398  4223 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 14:09:19.411  2103  2634 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-18 14:09:19.794  3798  3848 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-18 14:09:19.795  3798  3848 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-18 14:09:19.805  3798  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-18 14:09:19.808  3798  3848 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-18 14:09:19.808  3798  3848 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-18 14:09:19.813  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:19.813  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbfcbf7 added. We now have 2 listener(s)
08-18 14:09:19.815  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:19.815  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:19.815  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:19.816  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:19.816  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd94a64 added. We now have 9 listener(s)
08-18 14:09:19.816  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:19.817  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:09:19.820  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:19.829  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:09:19.833  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:19.833  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:09:19.834  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:09:19.834  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03c182 added. We now have 3 listener(s)
08-18 14:09:19.836  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:19.836  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:19.837  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:19.837  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:19.837  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b3093 added. We now have 10 listener(s)
08-18 14:09:19.837  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:19.837  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:09:19.837  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:09:19.837  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:09:19.837  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:19.837  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.838  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:09:19.838  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:19.838  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:19.838  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fbfcbf7 removed from the list
08-18 14:09:19.838  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:19.838  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd94a64 removed from the list
,08-18 14:09:19.845  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:19.845  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:09:19.845  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:19.846  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.846  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:19.849  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 14:09:19.849  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:19.849  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:19.850  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd94a64 not in the list
08-18 14:09:19.850  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.850  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:19.852  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:09:19.853  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:19.853  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:19.853  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b3093 removed from the list
08-18 14:09:19.853  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:19.854  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:09:19.854  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:19.854  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:19.854  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b03c182 removed from the list
,08-18 14:09:19.856  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:19.857  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@312a8d0 added. We now have 2 listener(s)
,08-18 14:09:19.862  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 14:09:19.863  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:19.863  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:19.863  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:09:19.864  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4170c9 added. We now have 9 listener(s)
08-18 14:09:19.864  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:19.865  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:09:19.871  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:19.883  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:09:19.888  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:19.889  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:09:19.889  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:19.889  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4be42ef added. We now have 3 listener(s)
,08-18 14:09:19.892   871  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-18 14:09:19.893  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 14:09:19.893  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:19.893  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:19.894  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:09:19.894  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14181fc added. We now have 10 listener(s)
,08-18 14:09:19.894  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:19.895  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:09:19.895  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 14:09:19.895  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:19.895  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:09:19.896  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:09:19.896  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 14:09:19.900  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:19.902  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 14:09:19.903  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 14:09:19.912  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 14:09:19.913  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 14:09:19.913  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 14:09:19.919  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 14:09:19.920  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 14:09:19.920  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 14:09:19.921  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:09:19.924  4153  4181 D BtGatt.GattService: registerClient() - UUID=d46e80bb-707b-4820-b179-44fb17a4e584
,08-18 14:09:19.926  4153  4169 D BtGatt.GattService: onClientRegistered() - UUID=d46e80bb-707b-4820-b179-44fb17a4e584, clientIf=5
,08-18 14:09:19.927  3798  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 14:09:19.928  4153  4164 D BtGatt.GattService: start scan with filters
,08-18 14:09:19.932  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 14:09:19.933  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 14:09:19.933  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 14:09:19.933  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 14:09:19.933  4153  4172 D BtGatt.ScanManager: handling starting scan
,08-18 14:09:19.936  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:09:19.936  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 14:09:19.936  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:09:19.937  4153  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@112449d
08-18 14:09:19.938  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 14:09:19.941  3798  3848 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-18 14:09:19.941  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:09:19.941  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 14:09:19.941  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.941  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 14:09:19.941  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 14:09:19.942  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 14:09:19.942  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:09:19.942  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:09:19.942  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 14:09:19.942  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:09:19.943  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:09:19.945  4153  4163 D BtGatt.GattService: stopScan() - queue size =1
,08-18 14:09:19.946  4153  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 14:09:19.946  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:09:19.947  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 14:09:19.947  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 14:09:19.947  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 14:09:19.946  4153  4169 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 14:09:19.947  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 14:09:19.947  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:19.948  4153  4172 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-18 14:09:19.949  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:09:19.949  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 14:09:19.949  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-18 14:09:19.949  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:09:19.950  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:09:19.953  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 14:09:19.953  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:09:19.953  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 14:09:19.956  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:09:19.957  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:09:19.957  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:09:19.957  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:19.957  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.957  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:09:19.957  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:19.957  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@312a8d0 removed from the list
08-18 14:09:19.957  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:09:19.957  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4170c9 removed from the list
08-18 14:09:19.958  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:09:19.958  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:19.958  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:09:19.958  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:19.960  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:19.960  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:19.960  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:09:19.960  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4170c9 not in the list
,08-18 14:09:19.960  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.960  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-18 14:09:19.961  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:09:19.961  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:19.961  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:19.961  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14181fc removed from the list
08-18 14:09:19.961  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:19.961  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:19.961  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:19.962  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-18 14:09:19.962  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4be42ef removed from the list
08-18 14:09:19.962  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:19.963  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c1e8 added. We now have 2 listener(s)
08-18 14:09:19.965  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:19.965  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:19.965  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 14:09:19.965  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:19.965  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 14:09:19.965  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a517001 added. We now have 9 listener(s)
08-18 14:09:19.965  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:19.965  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:19.966  4153  4172 D BtGatt.ScanManager: Starting BLE batch scan
08-18 14:09:19.966  4153  4172 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:09:19.967  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:09:19.969  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:19.978  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 14:09:19.982  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:19.983  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 14:09:19.983  4153  4169 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 14:09:19.983  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:19.983  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:19.984  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f45a0e7 added. We now have 3 listener(s)
,08-18 14:09:19.987  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:19.989  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 14:09:19.989  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:09:19.990  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 14:09:19.991  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 14:09:19.991  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:19.991  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:19.991  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1561494 added. We now have 10 listener(s)
,08-18 14:09:19.991  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:19.992  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 14:09:19.992  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 14:09:19.992  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 14:09:19.992  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:09:19.993  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 14:09:19.993  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 14:09:19.993  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 14:09:19.996  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 14:09:19.996  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:09:19.999  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 14:09:19.999  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.000  4153  4172 D BtGatt.ScanManager: stopping BLe Batch
,08-18 14:09:20.002  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 14:09:20.003  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 14:09:20.003  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 14:09:20.006  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 14:09:20.006  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.006  4153  4172 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 14:09:20.008  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 14:09:20.008  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-18 14:09:20.008  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 14:09:20.009  3798  3848 D BluetoothAdapter: STATE_ON
,08-18 14:09:20.011  4153  4164 D BtGatt.GattService: registerClient() - UUID=a6623e2f-09de-4d69-b04f-575fc8820294
,08-18 14:09:20.012  4153  4169 D BtGatt.GattService: onClientRegistered() - UUID=a6623e2f-09de-4d69-b04f-575fc8820294, clientIf=5
,08-18 14:09:20.012  3798  3810 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 14:09:20.012  4153  4163 D BtGatt.GattService: start scan with filters
08-18 14:09:20.013  4153  4169 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 14:09:20.013  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:09:20.027  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 14:09:20.027  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-18 14:09:20.027  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-18 14:09:20.030  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 14:09:20.027  4153  4172 D BtGatt.ScanManager: handling starting scan
,08-18 14:09:20.039  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:09:20.039  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 14:09:20.039  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 14:09:20.040  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 14:09:20.043  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:09:20.043  4153  4169 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 14:09:20.043  3798  3848 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-18 14:09:20.043  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:09:20.043  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 14:09:20.043  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 14:09:20.043  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 14:09:20.043  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:09:20.043  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:09:20.043  4153  4172 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 14:09:20.043  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 14:09:20.043  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-18 14:09:20.043  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f22c1e8 removed from the list
,08-18 14:09:20.044  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:09:20.044  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a517001 removed from the list
,08-18 14:09:20.044  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 14:09:20.044  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:09:20.044  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.044  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-18 14:09:20.044  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 14:09:20.045  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 14:09:20.045  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 14:09:20.045  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 14:09:20.046  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:09:20.046  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a517001 not in the list,
,08-18 14:09:20.046  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 14:09:20.046  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 14:09:20.046  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:09:20.046  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-18 14:09:20.046  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:09:20.047  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:09:20.047  4153  4181 D BtGatt.GattService: stopScan() - queue size =1,
08-18 14:09:20.048  4153  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 14:09:20.048  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-18 14:09:20.048  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 14:09:20.048  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 14:09:20.049  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-18 14:09:20.049  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 14:09:20.049  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-18 14:09:20.049  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.049  4153  4172 D BtGatt.ScanManager: Starting BLE batch scan
,08-18 14:09:20.050  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:09:20.050  4153  4172 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:09:20.050  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-18 14:09:20.050  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:09:20.050  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 14:09:20.050  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.052  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 14:09:20.052  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:09:20.052  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 14:09:20.052  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:20.052  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:20.052  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 14:09:20.052  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1561494 removed from the list
08-18 14:09:20.052  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 14:09:20.052  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.052  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:20.053  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:20.053  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f45a0e7 removed from the list
08-18 14:09:20.053  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:20.054  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c9e600 added. We now have 2 listener(s)
08-18 14:09:20.055  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 14:09:20.055  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 14:09:20.056  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:20.056  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:20.056  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b1e39 added. We now have 9 listener(s)
,08-18 14:09:20.056  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:20.057  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 14:09:20.059  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:09:20.061  4153  4169 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 14:09:20.061  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:20.064  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:09:20.066  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 14:09:20.066  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:09:20.066  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 14:09:20.066  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cabc5df added. We now have 3 listener(s)
08-18 14:09:20.066  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 14:09:20.067  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.068  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:20.068  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-18 14:09:20.068  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:20.068  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 14:09:20.068  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7622c added. We now have 10 listener(s)
08-18 14:09:20.068  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 14:09:20.068  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:09:20.068  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:20.068  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-18 14:09:20.068  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 14:09:20.069  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:09:20.069  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 14:09:20.071  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:20.073  3798  3848 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 14:09:20.073  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 14:09:20.075  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 14:09:20.075  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.075  4153  4172 D BtGatt.ScanManager: stopping BLe Batch
08-18 14:09:20.076  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 14:09:20.077  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 14:09:20.077  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 14:09:20.080  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 14:09:20.080  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 14:09:20.080  3798  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-18 14:09:20.080  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:09:20.081  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 14:09:20.081  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.081  4153  4172 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-18 14:09:20.082  4153  4181 D BtGatt.GattService: registerClient() - UUID=dd374c03-4384-4d78-ac53-6462f40a3084
08-18 14:09:20.082  4153  4169 D BtGatt.GattService: onClientRegistered() - UUID=dd374c03-4384-4d78-ac53-6462f40a3084, clientIf=5
08-18 14:09:20.083  3798  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 14:09:20.083  4153  4191 D BtGatt.GattService: start scan with filters
08-18 14:09:20.085  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 14:09:20.085  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 14:09:20.085  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 14:09:20.085  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 14:09:20.086  4153  4169 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 14:09:20.086  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.087  4153  4172 D BtGatt.ScanManager: handling starting scan
08-18 14:09:20.088  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 14:09:20.089  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 14:09:20.089  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 14:09:20.090  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-18 14:09:20.093  4153  4169 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 14:09:20.093  4153  4169 D BtGatt.ScanManager: callback done for, clientIf - 5 status - 0
08-18 14:09:20.093  4153  4172 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-18 14:09:20.095  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:09:20.095  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:09:20.095  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:09:20.095  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:20.095  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.095  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 14:09:20.095  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:20.095  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c9e600 removed from the list
08-18 14:09:20.095  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.096  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b1e39 removed from the list
08-18 14:09:20.096  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:09:20.096  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:09:20.096  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.096  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-18 14:09:20.096  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.096  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:09:20.098  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 14:09:20.098  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:20.098  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.098  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:20.098  4153  4172 D BtGatt.ScanManager: Starting BLE batch scan
08-18 14:09:20.098  4153  4172 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 14:09:20.098  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.098  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b1e39 not in the list
08-18 14:09:20.098  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 14:09:20.098  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 14:09:20.098  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 14:09:20.098  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 14:09:20.099  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 14:09:20.099  3798  3848 D BluetoothAdapter: STATE_ON
08-18 14:09:20.099  4153  4191 D BtGatt.GattService: stopScan() - queue size =1
08-18 14:09:20.100  4153  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 14:09:20.100  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 14:09:20.100  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 14:09:20.100  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 14:09:20.101  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 14:09:20.101  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 14:09:20.101  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:09:20.101  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 14:09:20.102  3798  3848 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 14:09:20.102  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 14:09:20.102  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.103  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:20.103  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:20.103  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.103  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:09:20.103  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7622c removed from the list
08-18 14:09:20.103  3798  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 14:09:20.103  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:20.103  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.103  3798  3798 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 14:09:20.103  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.103  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:20.103  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cabc5df removed from the list
08-18 14:09:20.104  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:09:20.104  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e7518 added. We now have 2 listener(s)
08-18 14:09:20.106  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:20.106  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:20.106  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:20.106  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:20.106  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e155b71 added. We now have 9 listener(s)
08-18 14:09:20.106  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:20.107  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 14:09:20.107  4153  4169 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 14:09:20.107  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.109  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 14:09:20.112  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 14:09:20.113  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 14:09:20.113  3798  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 14:09:20.114  3798  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 14:09:20.114  3798  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 14:09:20.115  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 14:09:20.115  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32291d7 added. We now have 3 listener(s)
08-18 14:09:20.116  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:20.117  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 14:09:20.117  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 14:09:20.118  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 14:09:20.118  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 14:09:20.118  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171cac4 added. We now have 10 listener(s)
08-18 14:09:20.118  3798  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 14:09:20.118  3798  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 14:09:20.118  3798  3848 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 14:09:20.118  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 14:09:20.118  3798  3848 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 14:09:20.118  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:20.118  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.118  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 14:09:20.119  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:20.119  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87e7518 removed from the list
08-18 14:09:20.119  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.119  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e155b71 removed from the list
08-18 14:09:20.119  3798  3848 D io.jxcore.node.ConnectivityMonitor: stop
08-18 14:09:20.119  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.120  4153  4169 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 14:09:20.120  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.121  4153  4172 D BtGatt.ScanManager: stopping BLe Batch
08-18 14:09:20.122  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.122  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.123  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:20.123  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:20.123  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.123  3798  3848 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e155b71 not in the list
08-18 14:09:20.123  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.123  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 14:09:20.124  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 14:09:20.124  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 14:09:20.124  3798  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 14:09:20.124  3798  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171cac4 removed from the list
08-18 14:09:20.124  3798  3848 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 14:09:20.125  3798  3848 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 14:09:20.125  3798  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 14:09:20.125  3798  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 14:09:20.125  3798  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32291d7 removed from the list
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-18 14:09:20.126  3798  3848 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 14:09:20.129  4153  4169 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 14:09:20.129  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.129  4153  4172 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-18 14:09:20.133  3798  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-18 14:09:20.133  3798  4229 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-18 14:09:20.133  3798  4229 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 14:09:20.135  4153  4169 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 14:09:20.135  4153  4169 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 14:09:20.135  3798  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
08-18 14:09:20.135  3798  4230 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-18 14:09:20.135  3798  4230 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 14:09:20.138  3798  3848 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-18 14:09:20.138  3798  3848 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-18 14:09:20.138  3798  3848 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-18 14:09:20.138  3798  3848 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-18 14:09:20.138  3798  3848 D com.test.thalitest.ThaliTestRunner: Total duration: 22831 ms
08-18 14:09:20.140  3798  3848 I jxcore-log: Total number of executed tests:  80
08-18 14:09:20.140  3798  3848 I jxcore-log: 
08-18 14:09:20.140  3798  3848 I jxcore-log: Number of passed tests:  80
08-18 14:09:20.140  3798  3848 I jxcore-log: 
08-18 14:09:20.140  3798  3848 I jxcore-log: Number of failed tests:  0
08-18 14:09:20.140  3798  3848 I jxcore-log: 
08-18 14:09:20.141  3798  3848 I jxcore-log: Number of ignored tests:  0
08-18 14:09:20.141  3798  3848 I jxcore-log: 
08-18 14:09:20.141  3798  3848 I jxcore-log: Total duration:  22831
08-18 14:09:20.141  3798  3848 I jxcore-log: 
08-18 14:09:20.141  3798  3848 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-18 14:09:20.141  3798  3848 I jxcore-log: 
08-18 14:09:20.147  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.147  3798  3848 I jxcore-log: 
08-18 14:09:20.149  3798  3798 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-18 14:09:20.151  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.151  3798  3848 I jxcore-log: 
08-18 14:09:20.152  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.152  3798  3848 I jxcore-log: 
08-18 14:09:20.152  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.152  3798  3848 I jxcore-log: 
08-18 14:09:20.153  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.153  3798  3848 I jxcore-log: 
08-18 14:09:20.154  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.154  3798  3848 I jxcore-log: 
08-18 14:09:20.157  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.157  3798  3848 I jxcore-log: 
08-18 14:09:20.158  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.158  3798  3848 I jxcore-log: 
08-18 14:09:20.159  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.159  3798  3848 I jxcore-log: 
08-18 14:09:20.160  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 14:09:20.160  3798  3848 I jxcore-log: 
08-18 14:09:20.161  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.161  3798  3848 I jxcore-log: 
08-18 14:09:20.162  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.162  3798  3848 I jxcore-log: 
08-18 14:09:20.163  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.163  3798  3848 I jxcore-log: 
08-18 14:09:20.163  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.163  3798  3848 I jxcore-log: 
08-18 14:09:20.164  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.164  3798  3848 I jxcore-log: 
08-18 14:09:20.165  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.165  3798  3848 I jxcore-log: 
08-18 14:09:20.166  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.166  3798  3848 I jxcore-log: 
08-18 14:09:20.166  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.166  3798  3848 I jxcore-log: 
08-18 14:09:20.167  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.167  3798  3848 I jxcore-log: 
08-18 14:09:20.168  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.168  3798  3848 I jxcore-log: 
08-18 14:09:20.169  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.169  3798  3848 I jxcore-log: 
08-18 14:09:20.169  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.169  3798  3848 I jxcore-log: 
08-18 14:09:20.173  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.173  3798  3848 I jxcore-log: 
08-18 14:09:20.173  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 14:09:20.173  3798  3848 I jxcore-log: 
08-18 14:09:20.174  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.174  3798  3848 I jxcore-log: 
08-18 14:09:20.175  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 14:09:20.175  3798  3848 I jxcore-log: 
08-18 14:09:20.176  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.176  3798  3848 I jxcore-log: 
08-18 14:09:20.177  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.177  3798  3848 I jxcore-log: 
08-18 14:09:20.178  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.178  3798  3848 I jxcore-log: 
08-18 14:09:20.178  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.178  3798  3848 I jxcore-log: 
08-18 14:09:20.179  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.179  3798  3848 I jxcore-log: 
08-18 14:09:20.179  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 14:09:20.179  3798  3848 I jxcore-log: 
,08-18 14:09:20.455  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 14:09:20.458  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 14:09:20.458  3798  3848 I jxcore-log: 
,08-18 14:09:20.553  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 14:09:20.556  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 14:09:20.556  3798  3848 I jxcore-log: 
,08-18 14:09:20.603  3798  3798 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 14:09:20.606  3798  3848 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 14:09:20.606  3798  3848 I jxcore-log: 
,08-18 14:09:20.834  4232  4232 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-18 14:09:20.839  4232  4232 D AndroidRuntime: CheckJNI is OFF
,08-18 14:09:20.882  4232  4232 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-18 14:09:20.930  4232  4232 I Radio-JNI: register_android_hardware_Radio DONE
,08-18 14:09:20.954  4232  4232 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-18 14:09:20.968   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-18 14:09:20.969   871   884 I ActivityManager: Killing 3798:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-18 14:09:21.070   871   882 I WindowState: WIN DEATH: Window{37de786 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-18 14:09:21.071   871  1392 D GraphicsStats: Buffer count: 2
08-18 14:09:21.072   871  1306 D WifiService: Client connection lost with reason: 4
,08-18 14:09:21.118   871   894 W PackageSettings: Skipping PackageSetting{a522856 com.example.hello/10273} due to missing metadata
,08-18 14:09:21.144   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-18 14:09:21.144   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-18 14:09:21.145   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-18 14:09:21.145   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
,08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-18 14:09:21.145   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.145   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.145   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 14:09:21.145   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-18 14:09:21.146   871   884 I ActivityManager:   Force finishing activity ActivityRecord{800cc6f u0 com.test.thalitest/.MainActivity t2}
,08-18 14:09:21.149   871  2052 W ActivityManager: Spurious death for ProcessRecord{d836063 0:com.test.thalitest/u0a0}, curProc for 3798: null
,08-18 14:09:21.154   871   894 I art     : Starting a blocking GC Explicit
,08-18 14:09:21.220   871   894 I art     : Explicit concurrent mark sweep GC freed 13714(957KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.084ms total 65.975ms
,08-18 14:09:21.278   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-18 14:09:21.285  4232  4232 I art     : System.exit called, status: 0
08-18 14:09:21.286  4232  4232 I AndroidRuntime: VM exiting with result code 0.
08-18 14:09:21.287   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-18 14:09:21.311   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-18 14:09:21.326  4153  4153 D BluetoothMapAppObserver: onReceive
,08-18 14:09:21.326  4153  4153 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-18 14:09:21.327  2103  2287 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-18 14:09:21.331   871  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 14:09:21.361  3637  3637 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-18 14:09:21.373  1856  1856 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-18 14:09:21.378  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-18 14:09:21.397   871  1373 I ActivityManager: Start proc 4245:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-18 14:09:21.402  1856  4254 I Keyboard.Facilitator.DecoderInitializer: run()
,08-18 14:09:21.410  1856  4254 I Decoder : createOrResetDecoder
08-18 14:09:21.412   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-18 14:09:21.429  4245  4245 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-18 14:09:21.432  1507  1507 I ConfigService: onCreate
,08-18 14:09:21.435  1507  4258 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 14:09:21.435  1507  4258 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 14:09:21.435  1507  4258 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-18 14:09:21.436  1507  4258 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-18 14:09:21.445  1856  4254 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-18 14:09:21.457   871  1932 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3798 uid 10000
08-18 14:09:21.458  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-18 14:09:21.474  4245  4245 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-18 14:09:21.481   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-18 14:09:21.482   871   883 E PackageManager: Failed to write settings, restoring backup
08-18 14:09:21.482   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-18 14:09:21.482   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-18 14:09:21.482   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-18 14:09:21.482   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-18 14:09:21.482   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-18 14:09:21.482   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.482   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.482   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 14:09:21.487   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-18 14:09:21.487   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-18 14:09:21.487   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.487   871   884 E DropBoxManagerService: 	... 13 more
,08-18 14:09:21.489  4245  4262 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-18 14:09:21.491  1856  4254 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-18 14:09:21.494  1943  2022 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-18 14:09:21.494  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-18 14:09:21.494  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-18 14:09:21.497  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-18 14:09:21.497  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-18 14:09:21.498   871  2243 I ActivityManager: Start proc 4264:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-18 14:09:21.501  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-18 14:09:21.502  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-18 14:09:21.503  1856  4254 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-18 14:09:21.503  1856  4254 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-18 14:09:21.503  1856  4254 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-18 14:09:21.510   871   882 I ActivityManager: Start proc 4275:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-18 14:09:21.510  1943  2022 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-18 14:09:21.510  1943  2022 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1943
08-18 14:09:21.510  1943  2022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.510  1943  2022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 14:09:21.511  1856  4254 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-18 14:09:21.511  1856  4254 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-18 14:09:21.511  1856  4254 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-18 14:09:21.512   871  1927 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-18 14:09:21.514   871  4281 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.514   871  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.514   871  4281 E DropBoxManagerService: 	... 5 more
,08-18 14:09:21.525  1943  2022 I Process : Sending signal. PID: 1943 SIG: 9
,08-18 14:09:21.534  4245  4262 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.534  4245  4262 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 14:09:21.534  4245  4262 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-18 14:09:21.534  4245  4262 E AndroidRuntime: Process: android.process.acore, PID: 4245
08-18 14:09:21.534  4245  4262 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.534  4245  4262 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.536   871  4290 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerServ,ice.java:211)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.536   871  4290 E DropBoxManagerService: 	... 5 more
,08-18 14:09:21.541  4264  4264 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-18 14:09:21.542  4245  4262 I Process : Sending signal. PID: 4245 SIG: 9
,08-18 14:09:21.561  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-18 14:09:21.562  1507  1507 D AndroidRuntime: Shutting down VM
08-18 14:09:21.563  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
08-18 14:09:21.563  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
08-18 14:09:21.563  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-18 14:09:21.563  1507  1507 E AndroidRuntime: 	... 8 more
,08-18 14:09:21.567   871  4293 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.567   871  4293 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.567   871  4293 E DropBoxManagerService: 	... 5 more
08-18 14:09:21.570  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
,08-18 14:09:21.582   280   280 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
,08-18 14:09:21.584   871  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-18 14:09:21.605   280   280 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
,08-18 14:09:21.616  1720  4297 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,08-18 14:09:21.616  1720  4297 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@dd0b92a
08-18 14:09:21.616   871   881 I ActivityManager: Process com.google.process.gapps (pid 1507) early provider death
,08-18 14:09:21.618   871  1306 D WifiService: Client connection lost with reason: 4
,08-18 14:09:21.622   871   881 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
,08-18 14:09:21.622   871  1927 D GraphicsStats: Buffer count: 1
08-18 14:09:21.622   871  1927 I WindowState: WIN DEATH: Window{12850f8 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-18 14:09:21.622   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,08-18 14:09:21.622   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-18 14:09:21.622   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
08-18 14:09:21.623   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,08-18 14:09:21.624   871  1942 W ActivityManager: Spurious death for ProcessRecord{b2a0b77 0:com.google.process.gapps/u0a11}, curProc for 1507: null
,08-18 14:09:21.667   871  1392 I ActivityManager: Start proc 4300:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-18 14:09:21.667   871  2052 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1943) has died
,08-18 14:09:21.667   871  2052 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40955ms
,08-18 14:09:21.668   871  2052 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-18 14:09:21.672   871  1942 I ActivityManager: Process android.process.acore (pid 4245) has died,
08-18 14:09:21.672   871  1942 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40950ms
08-18 14:09:21.675  1720  1720 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-18 14:09:21.685   871   884 I ActivityManager: Start proc 4312:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 14:09:21.711  4300  4300 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-18 14:09:21.715  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-18 14:09:21.715  1720  1720 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-18 14:09:21.717  4300  4300 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-18 14:09:21.719  4300  4300 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:09:21.719  4300  4300 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:09:21.720  4300  4300 D AndroidRuntime: Shutting down VM
08-18 14:09:21.720  4300  4300 E AndroidRuntime: FATAL EXCEPTION: main
08-18 14:09:21.720  4300  4300 E AndroidRuntime: Process: com.google.process.gapps, PID: 4300
08-18 14:09:21.72,0  4300  4300 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 14:09:21.720  4300  4300 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18, 14:09:21.720  4300  4300 E AndroidRuntime: 	... 10 more
08-18 14:09:21.723  4300  4300 I Process : Sending signal. PID: 4300 SIG: 9
08-18 14:09:21.725   871  4326 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.725   871  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.725   871  4326 E DropBoxManagerService: 	... 5 more
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:09:21.733  4312  4312 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:09:21.733  1720  1720 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-18 14:09:21.733  1720  1720 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-18 14:09:21.733  4312  4312 D AndroidRuntime: Shutting down VM
08-18 14:09:21.738  1720  4327 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-18 14:09:21.748   871  1394 I ActivityManager: Process com.google.process.gapps (pid 4300) has died
08-18 14:09:21.749   871  1394 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{b41a823 u0 com.google.android.gms/.config.ConfigService}
08-18 14:09:21.749   871  1394 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{690aac2 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-18 14:09:21.749   871  1394 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6338f32 u0 com.google.android.gms/.auth.GetToken}
08-18 14:09:21.749   871  1394 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{416b64f u0 com.google.android.gms/.gcm.GcmService}
08-18 14:09:21.753  1720  4327 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-18 14:09:21.753  1720  4327 E AndroidRuntime: Process: com.google.android.gms, PID: 1720
08-18 14:09:21.753  1720  4327 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 14:09:21.753  1720  4327 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-18 14:09:21.761   871  1394 I ActivityManager: Start proc 4329:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-18 14:09:21.773  4312  4312 E AndroidRuntime: FATAL EXCEPTION: main
08-18 14:09:21.773  4312  4312 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4312
08-18 14:09:21.773  4312  4312 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 14:09:21.773  4312  4312 E AndroidRuntime: 	... 10 more
08-18 14:09:21.774  1720  4327 I Process : Sending signal. PID: 1720 SIG: 9
08-18 14:09:21.775   871  1373 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-18 14:09:21.775  4312  4312 I Process : Sending signal. PID: 4312 SIG: 9
08-18 14:09:21.775   280   280 E lowmemorykiller: Error writing /proc/1720/oom_score_adj; errno=22
08-18 14:09:21.776   871  4340 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.776   871  4340 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.776   871  4340 E DropBoxManagerService: 	... 5 more
08-18 14:09:21.777   871  4342 E DropBoxManagerService: Can't write: system_app_crash
08-18 14:09:21.777   871  4342 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 14:09:21.777   871  4342 E DropBoxManagerService: 	... 5 more
08-18 14:09:21.787   871  2243 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
08-18 14:09:21.788   871  2243 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-18 14:09:21.788   871  2243 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-18 14:09:21.788   871  2243 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
08-18 14:09:21.789  1992  4343 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-18 14:09:21.810  4329  4329 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-18 14:09:21.826   871  2243 I ActivityManager: Start proc 4344:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-18 14:09:21.827  1992  4343 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-18 14:09:21.827   871   882 W ActivityManager: Spurious death for ProcessRecord{6afe07b 4344:com.google.android.googlequicksearchbox/u0a28}, curProc for 4312: null
08-18 14:09:21.829   871  2053 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@96a3e98)
08-18 14:09:21.830   871  1307 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-18 14:09:21.830   871  1307 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
