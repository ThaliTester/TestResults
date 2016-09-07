#### Test 829120309a78d5a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 16:09:03.480  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:03.492  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 16:09:03.495  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 16:09:03.533  1526  3206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 16:09:03.533  1526  3206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 16:09:03.533  1526  3206 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:03.533  1526  3206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 16:09:03.564  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 16:09:03.565  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 16:09:03.565  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-07 16:09:04.164  3798  3798 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 16:09:04.169  3798  3798 D AndroidRuntime: CheckJNI is OFF
09-07 16:09:04.212  3798  3798 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 16:09:04.263  3798  3798 I Radio-JNI: register_android_hardware_Radio DONE
09-07 16:09:04.284  3798  3798 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 16:09:04.288   873  1636 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 16:09:04.312  2010  2022 W SearchService: Abort, client detached.
09-07 16:09:04.319  2010  2010 I HotwordDetector: Closing mic
09-07 16:09:04.319  2010  2342 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@19fbf35
09-07 16:09:04.320  2010  2359 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 16:09:04.331  3798  3798 D AndroidRuntime: Shutting down VM
09-07 16:09:04.356   873   884 I ActivityManager: Start proc 3807:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 16:09:04.375   376  2362 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 16:09:04.377   376  2362 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 16:09:04.384   376  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 16:09:04.388  2010  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 16:09:04.389  2010  2358 I MicroRecognitionRnrImpl: Detection finished
09-07 16:09:04.448  3807  3807 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 16:09:04.479  3807  3807 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 16:09:04.487  3807  3807 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 44-47)
09-07 16:09:04.487  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 16:09:04.503  3807  3807 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c7ea3c}
09-07 16:09:04.503  3807  3807 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 16:09:04.503  3807  3807 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 16:09:04.528  3807  3807 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 16:09:04.531  3807  3807 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 16:09:04.554  3807  3807 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 16:09:04.565  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 16:09:04.565  3807  3807 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 16:09:04.565  3807  3807 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 16:09:04.565  3807  3807 I Adreno  : Build Date                       : 10/20/15
09-07 16:09:04.565  3807  3807 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 16:09:04.565  3807  3807 I Adreno  : Local Branch                     : M14
09-07 16:09:04.565  3807  3807 I Adreno  : Remote Branch                    : 
09-07 16:09:04.565  3807  3807 I Adreno  : Remote Branch                    : 
09-07 16:09:04.565  3807  3807 I Adreno  : Reconstruct Branch               : 
,09-07 16:09:04.610   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cef34d1:true
,09-07 16:09:04.660  3807  3807 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 16:09:04.675  3807  3807 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 16:09:04.742  3807  3846 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 16:09:04.753  3807  3832 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 16:09:04.790  3807  3846 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 16:09:04.876   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms
,09-07 16:09:04.881  1864  1864 I Keyboard.Facilitator: onFinishInput()
,09-07 16:09:04.951  3807  3807 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3807
,09-07 16:09:05.048  3807  3807 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 16:09:05.155   873  1917 I ActivityManager: Killing 3057:com.google.android.talk/u0a61 (adj 15): empty #17
,09-07 16:09:05.208   873  1917 I ActivityManager: Killing 2977:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-07 16:09:05.341  3807  3849 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1717044944
,09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 16:09:05.349  3807  3849 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@189c700 added. We now have 1 listener(s)
,09-07 16:09:05.357  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 16:09:05.360  3807  3849 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 16:09:05.360  3807  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 16:09:05.360  3807  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 16:09:05.363  3807  3849 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@691dadf added. We now have 1 listener(s)
,09-07 16:09:05.364  3807  3849 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:09:05.378   873  1304 D WifiService: New client listening to asynchronous messages
,09-07 16:09:05.379  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:09:05.379  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 16:09:05.380  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 16:09:05.380  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-07 16:09:05.380  3807  3849 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 16:09:05.384  3807  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:09:05.384  3807  3849 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 16:09:05.389  3807  3849 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:05.389  3807  3849 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:05.389  3807  3849 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 16:09:05.389  3807  3849 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:09:05.390  3807  3849 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 16:09:05.392  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:05.395  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:05.415  3807  3807 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 16:09:06.391  3807  3858 W jxcore-log: Initializing JXcore engine
09-07 16:09:06.391  3807  3858 W jxcore-log: JXcore engine is ready
,09-07 16:09:06.468  3858  3858 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 16:09:06.468  3858  3858 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9538]" dev="sockfs" ino=9538 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 16:09:06.468  3858  3858 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 16:09:06.468  3858  3858 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25980]" dev="sockfs" ino=25980 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 16:09:06.483  3807  3858 W jxcore-log: Starting JXcore engine
,09-07 16:09:06.599  3807  3858 W jxcore-log: Platform android
09-07 16:09:06.599  3807  3858 W jxcore-log: 
,09-07 16:09:06.599  3807  3858 W jxcore-log: Process ARCH arm
09-07 16:09:06.599  3807  3858 W jxcore-log: 
,09-07 16:09:06.810  3807  3858 I jxcore-log: JXcore Cordova bridge is ready!
09-07 16:09:06.810  3807  3858 I jxcore-log: 
,09-07 16:09:06.811  3807  3858 W jxcore-log: JXcore engine is started
,09-07 16:09:06.823  3807  3849 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 16:09:06.827  3807  3807 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 16:09:06.956   873  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 16:09:09.183   873  1878 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:09:10.411  3039  3865 V KeepSync: Connecting to GoogleApiClient
,09-07 16:09:10.419   873  1917 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:09:10.486  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:10.497  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:10.530  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:09:10.530  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 16:09:10.530  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:10.530  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:10.549  1746  3866 V BaseAuthAsyncOperation: access token request failed
,09-07 16:09:10.550  3039  3865 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:09:10.599  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 16:09:10.599  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 16:09:10.599  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:10.599  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:10.634  3039  3865 E KeepSync: IOException
09-07 16:09:10.634  3039  3865 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:09:10.634  3039  3865 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:09:10.634  3039  3865 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:09:10.634  3039  3865 E KeepSync: 	... 10 more
09-07 16:09:10.634  3039  3865 W KeepSync: Sync result 2
,09-07 16:09:10.640   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125873, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:09:15.689   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 16:09:18.712   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 16:09:21.136  3807  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 16:09:21.136  3807  3858 I jxcore-log: 
,09-07 16:09:21.138  3807  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 16:09:21.138  3807  3858 I jxcore-log: 
,09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:21.148  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:21.159  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:09:21.165  3807  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 16:09:21.165  3807  3858 I jxcore-log: 
,09-07 16:09:21.172  3807  3858 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 16:09:21.172  3807  3858 I jxcore-log: 
,09-07 16:09:21.544  3807  3858 I jxcore-log: Running unit tests
09-07 16:09:21.544  3807  3858 I jxcore-log: 
,09-07 16:09:21.545  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 16:09:21.545  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81f287b added. We now have 2 listener(s)
09-07 16:09:21.546  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:09:21.547  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:09:21.547  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:09:21.547  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:09:21.547  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbbe698 added. We now have 2 listener(s)
09-07 16:09:21.547  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:09:21.547  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:09:21.550  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:21.563  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:21.566  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:09:21.567  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:09:21.567  3807  3858 D executeNativeTests: Running unit tests
,09-07 16:09:21.574  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:21.581  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:21.630  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:09:21.630  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 added. We now have 3 listener(s)
,09-07 16:09:21.631  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:09:21.631  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:09:21.631  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:09:21.632  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:09:21.632  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 added. We now have 3 listener(s)
09-07 16:09:21.632  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:09:21.632  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:09:21.636  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:21.661  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:21.662  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.663  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:09:21.665  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 16:09:21.666  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:21.667  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:09:21.667  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:09:21.667  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:09:21.668  3807  3858 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 16:09:21.668  3807  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 16:09:21.668  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 16:09:21.669  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 16:09:21.669  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:09:21.669  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:09:21.669  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:21.670  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:21.670  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:21.670  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:21.670  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.670  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:09:21.670  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:21.670  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:09:21.670  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 removed from the list
09-07 16:09:21.670  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.670  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 removed from the list
09-07 16:09:21.670  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:21.670  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.671  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.671  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.672  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:21.672  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:21.672  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.672  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:21.674  3807  3858 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 16:09:21.674  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:21.674  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:21.674  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:21.675  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:21.675  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.675  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.B,luetoothManager: release: 2 listener(s) left
09-07 16:09:21.675  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:21.675  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.675  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:21.675  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:21.675  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.675  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.675  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.675  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.677  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:21.677  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:21.677  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.677  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 16:09:21.683  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 16:09:21.684  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 16:09:21.684  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:21.684  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:21.684  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:21.685  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:21.685  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.685  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.685  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:21.685  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.685  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:21.685  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:21.685  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.685  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.685  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:21.685  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:21.686  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:21.687  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:21.687  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:21.687  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:21.687  3807  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 16:09:21.689  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:21.694  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:21.696  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:21.696  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:09:21.697  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:09:21.697  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:09:21.697  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:09:21.697  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:09:21.698  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 16:09:21.698  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:21.701  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 16:09:21.701  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 16:09:21.701  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:21.706  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 16:09:21.707  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:09:21.708  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 16:09:21.711  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 16:09:21.715  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 16:09:21.715  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 16:09:21.716  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 16:09:21.716  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 16:09:21.717  3807  3858 D BluetoothAdapter: STATE_ON
09-07 16:09:21.721  2668  2799 D BtGatt.GattService: registerClient() - UUID=1aebeaf6-e33c-4b68-bd49-f63ce5fd833d
09-07 16:09:21.722  2668  2702 D BtGatt.GattService: onClientRegistered() - UUID=1aebeaf6-e33c-4b68-bd49-f63ce5fd833d, clientIf=5
09-07 16:09:21.724  3807  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:09:21.725  2668  2821 D BtGatt.GattService: start scan with filters
09-07 16:09:21.727  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 16:09:21.727  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:09:21.727  2668  2705 D BtGatt.ScanManager: handling starting scan
09-07 16:09:21.727  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 16:09:21.728  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 16:09:21.730  2668  2705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:09:21.730  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:21.730  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 16:09:21.730  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:21.731  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 16:09:21.734  3807  3858 I io.jxcore.node.ConnectionHelper: start: OK
09-07 16:09:21.738  2668  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 16:09:21.739  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:21.739  2668  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 16:09:21.745  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:09:21.745  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:21.746  2668  2705 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:09:21.746  2668  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 16:09:21.759  2668  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 16:09:21.759  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:21.766  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 16:09:21.766  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:22.232  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 16:09:22.233  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:09:22.233  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:09:23.274  2668  2668 D BtGatt.ScanManager: awakened up at time 138834
,09-07 16:09:23.276  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:23.317  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-07 16:09:23.317  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:23.318  2668  2702 D BtGatt.GattService: current time is 138878961030
09-07 16:09:23.320  2668  2702 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, 4, -101, 14, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:09:23.323  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:09:23.325  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-07 16:09:23.327  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:09:23.327  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:09:23.328  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 16:09:23.329  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:09:24.765   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 16:09:24.832  2668  2668 D BtGatt.ScanManager: awakened up at time 140392
,09-07 16:09:24.836  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:24.906  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-07 16:09:24.906  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:24.906  2668  2702 D BtGatt.GattService: current time is 140466850667
,09-07 16:09:24.906  2668  2702 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -97, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 85, -113, -37, 31, -33, 8, 0, 4, -87, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-07 16:09:24.907  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:09:24.907  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:09:24.907  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 16:09:24.907  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-07 16:09:25.079  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:25.091  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:25.097  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:25.142  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 16:09:25.143  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 16:09:25.143  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:25.143  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:25.182  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 16:09:25.183  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 16:09:25.183  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 16:09:26.412  2668  2668 D BtGatt.ScanManager: awakened up at time 141973
,09-07 16:09:26.415  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:26.459  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-07 16:09:26.460  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:26.460  2668  2702 D BtGatt.GattService: current time is 142021209259
,09-07 16:09:26.461  2668  2702 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -78, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -86, 21, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -86, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -86, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:09:26.462  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 16:09:26.463  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 16:09:26.464  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
09-07 16:09:26.465  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-07 16:09:26.466  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:09:26.743  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:26.744  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:09:26.744  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:09:26.745  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:26.745  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:09:26.745  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 16:09:26.746  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:09:26.746  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:09:26.747  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 16:09:26.749  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:09:26.749  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:09:26.752  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:09:26.754  2668  2821 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:09:26.756  2668  2679 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:09:26.758  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 16:09:26.759  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 16:09:26.759  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 16:09:26.760  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:09:26.760  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 16:09:26.764  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:09:26.765  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:09:26.766  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 16:09:26.767  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 16:09:26.768  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:09:26.771  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:09:26.772  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:26.772  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:09:26.772  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:09:26.772  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 16:09:26.772  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:26.772  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:26.773  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:09:26.773  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:26.773  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:26.773  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:26.773  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:26.773  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:26.774  2668  2705 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:09:26.783  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 16:09:26.783  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:26.783  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:26.791  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 16:09:26.791  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:27.273  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:09:27.781   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 16:09:31.774  3807  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 16:09:31.780  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:31.794  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:31.800  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:09:31.801  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:09:31.802  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 16:09:31.802  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:09:31.802  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:09:31.803  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:09:31.803  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:09:31.809  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:31.814  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:09:31.815  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 16:09:31.817  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 16:09:31.823  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:09:31.824  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 16:09:31.825  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:09:31.832  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 16:09:31.832  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 16:09:31.833  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 16:09:31.834  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:09:31.838  2668  2680 D BtGatt.GattService: registerClient() - UUID=4b4a2fbf-8c5e-47fa-a9fc-2a3eba6ae534
,09-07 16:09:31.839  2668  2702 D BtGatt.GattService: onClientRegistered() - UUID=4b4a2fbf-8c5e-47fa-a9fc-2a3eba6ae534, clientIf=5
,09-07 16:09:31.840  3807  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:09:31.841  2668  2822 D BtGatt.GattService: start scan with filters,
,09-07 16:09:31.847  2668  2705 D BtGatt.ScanManager: handling starting scan
,09-07 16:09:31.847  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 16:09:31.847  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 16:09:31.848  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 16:09:31.848  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 16:09:31.857  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:31.857  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:31.858  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 16:09:31.859  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:09:31.860  2668  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 16:09:31.861  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:31.861  2668  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:09:31.864  3807  3858 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 16:09:31.869  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:31.869  3807  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 16:09:31.869  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:31.869  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:09:31.869  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:31.870  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-07 16:09:31.870  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:09:31.870  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:09:31.870  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:09:31.870  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:09:31.870  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 16:09:31.870  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:09:31.872  3807  3858 D BluetoothAdapter: STATE_ON
09-07 16:09:31.874  2668  2821 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:09:31.875  2668  2679 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 16:09:31.876  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:09:31.876  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-07 16:09:31.876  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 16:09:31.877  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 16:09:31.877  2668  2705 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:09:31.877  2668  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:09:31.877  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 16:09:31.887  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:09:31.887  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 16:09:31.890  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:09:31.890  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:09:31.890  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:09:31.891  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:09:31.892  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:09:31.895  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:09:31.895  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:09:31.895  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:31.895  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:09:31.895  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:31.895  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:09:31.896  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:31.896  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:31.896  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:31.896  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:09:31.896  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:31.897  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:31.897  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:31.898  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:31.898  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:09:31.898  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:31.899  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:31.900  3807  3858 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 16:09:31.902  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:09:31.905  2668  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 16:09:31.905  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:31.911  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:31.914  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 16:09:31.914  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.915  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-07 16:09:31.916  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:09:31.918  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:09:31.918  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:09:31.918  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:09:31.918  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-07 16:09:31.918  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:09:31.924  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 16:09:31.924  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.925  2668  2705 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:09:31.925  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:31.927  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:09:31.927  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 16:09:31.933  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 16:09:31.933  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:31.933  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:31.934  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:31.934  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:09:31.935  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:09:31.935  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:09:31.941  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 16:09:31.941  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 16:09:31.941  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.941  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 16:09:31.942  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 16:09:31.944  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:09:31.948  2668  2822 D BtGatt.GattService: registerClient() - UUID=0dd7bc8c-ea1b-4403-bf2b-b95db94c2a47
,09-07 16:09:31.948  2668  2702 D BtGatt.GattService: onClientRegistered() - UUID=0dd7bc8c-ea1b-4403-bf2b-b95db94c2a47, clientIf=5
09-07 16:09:31.949  3807  3819 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:09:31.949  2668  2679 D BtGatt.GattService: start scan with filters
,09-07 16:09:31.953  2668  2705 D BtGatt.ScanManager: handling starting scan
,09-07 16:09:31.953  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 16:09:31.953  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:09:31.953  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 16:09:31.953  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 16:09:31.959  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:31.960  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:09:31.960  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 16:09:31.961  2668  2702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
09-07 16:09:31.961  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:31.961  2668  2705 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:09:31.964  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:09:31.967  3807  3858 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 16:09:31.970  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:09:31.970  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.970  2668  2705 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:09:31.970  2668  2705 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:09:31.983  2668  2702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 16:09:31.983  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:31.990  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 16:09:31.990  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:32.461  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 16:09:32.461  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 16:09:32.462  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:09:33.496  2668  2668 D BtGatt.ScanManager: awakened up at time 149057
,09-07 16:09:33.498  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:33.544  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-07 16:09:33.544  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:33.544  2668  2702 D BtGatt.GattService: current time is 149105317257
09-07 16:09:33.545  2668  2702 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -95, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, -128, -99, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 0, 35, 97, 126, -92, 22, -56, 1, -128, -92, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -65, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
09-07 16:09:33.546  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 16:09:33.547  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:09:33.547  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-07 16:09:33.547  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25]
09-07 16:09:33.547  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-07 16:09:33.548  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:09:33.548  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-07 16:09:34.433   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 16:09:34.455  1864  1864 I Keyboard.Facilitator: onFinishInput()
,09-07 16:09:34.463   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 16:09:34.463   873   893 I Adreno  : Build Date                       : 10/20/15
09-07 16:09:34.463   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 16:09:34.463   873   893 I Adreno  : Local Branch                     : M14
09-07 16:09:34.463   873   893 I Adreno  : Remote Branch                    : 
09-07 16:09:34.463   873   893 I Adreno  : Remote Branch                    : 
09-07 16:09:34.463   873   893 I Adreno  : Reconstruct Branch               : 
,09-07 16:09:34.505   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (310 us)
,09-07 16:09:35.047  2668  2668 D BtGatt.ScanManager: awakened up at time 150608
,09-07 16:09:35.051  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:35.141  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 16:09:35.141  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 16:09:35.181   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 16:09:35.184  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@868d972 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@52e90f8, 16908290=android.view.AbsSavedState$1@52e90f8}, android:focusedViewId=100}]}]
09-07 16:09:35.184  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 16:09:35.184  3807  3807 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 16:09:35.184  3807  3807 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 16:09:35.206   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 16:09:35.212   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 16:09:35.213   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-07 16:09:35.213   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 16:09:35.220  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-07 16:09:35.220  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:35.220  2668  2702 D BtGatt.GattService: current time is 150781140237
09-07 16:09:35.220  2668  2702 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 16:09:35.221  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-07 16:09:35.221  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:09:35.221  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 16:09:35.221  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-07 16:09:35.221  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:09:35.440   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 16:09:35.445   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 16:09:35.451   873  1329 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-07 16:09:35.455   873   893 I DreamManagerService: Entering dreamland.
,09-07 16:09:35.456   873   893 I PowerManagerService: Dozing...
,09-07 16:09:35.459   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 16:09:35.534   376  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-07 16:09:35.535   376  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 16:09:35.550   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:09:35.560  1907  3876 D NfcService: Discovery configuration equal, not updating.
,09-07 16:09:35.567   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-07 16:09:35.571   873  1303 E native  : do suspend false
,09-07 16:09:35.593   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 16:09:35.612   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:09:35.616   873  1303 E native  : do suspend true
,09-07 16:09:35.665   376  1311 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 16:09:35.666   376  1311 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 16:09:35.724  2668  2668 D BtGatt.ScanManager: awakened up at time 151284
,09-07 16:09:35.726  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:35.752  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-07 16:09:35.753  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:09:35.753  2668  2702 D BtGatt.GattService: current time is 151313963571
,09-07 16:09:35.754  2668  2702 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -86, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:09:35.754  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-07 16:09:35.755  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 16:09:35.756  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:09:36.056   873  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-07 16:09:36.967  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:36.968  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:36.968  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:09:36.968  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:36.969  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-07 16:09:36.969  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:09:36.969  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:09:36.970  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 16:09:36.970  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:09:36.970  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:09:36.971  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 16:09:36.973  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:09:36.976  2668  2821 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:09:36.981  2668  2679 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:09:36.982  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 16:09:36.982  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 16:09:36.983  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 16:09:36.984  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:09:36.984  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 16:09:36.989  2668  2668 D BtGatt.ScanManager: awakened up at time 152549
,09-07 16:09:36.990  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:09:36.991  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 16:09:36.991  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:09:36.991  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 16:09:36.993  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:09:36.996  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:09:36.996  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:09:36.996  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:09:36.996  2668  2702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 16:09:36.996  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:36.997  2668  2705 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:09:37.007  2668  2702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 16:09:37.007  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:37.008  2668  2705 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:09:37.025  2668  2702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-07 16:09:37.026  2668  2702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:09:37.026  2668  2702 D BtGatt.GattService: current time is 152586903393
09-07 16:09:37.026  2668  2702 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -92, 24, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-07 16:09:37.027  2668  2702 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,09-07 16:09:37.497  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:09:37.498  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:37.498  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:09:40.742  3617  3881 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:09:40.780  3617  3884 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:09:40.795  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:40.799  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:40.827  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:09:40.827  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 16:09:40.827  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:40.827  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:40.857  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:40.860  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:40.910  1526  2328 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:09:40.910  1526  2328 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:09:40.910  1526  2328 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:40.910  1526  2328 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:40.933  3617  3884 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:09:40.934  3617  3881 E BooksSync: Soft error
09-07 16:09:40.934  3617  3881 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:09:40.934  3617  3881 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:09:40.935  3617  3881 E BooksSync: Sync error
09-07 16:09:40.935  3617  3881 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:09:40.935  3617  3881 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:09:40.935  3617  3881 I BooksSync: Finished books sync
,09-07 16:09:40.944   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128564, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:09:40.958  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:09:40.958  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:09:40.959  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:40.959  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:40.976  3555  3883 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:09:40.976  3555  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:09:40.976  3555  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	... 12 more
09-07 16:09:40.976  3555  3883 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at fal.a(PG:38)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:09:40.976  3555  3883 E HttpOperation: 	... 14 more
,09-07 16:09:41.036  1526  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:09:41.036  1526  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 16:09:41.036  1526  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:41.037  1526  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:41.057  3555  3883 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:09:41.057  3555  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at hec.a(PG:42)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at hee.a(PG:102)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at czr.a(PG:65)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at kka.a(PG:108)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:09:41.057  3555  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	... 15 more
09-07 16:09:41.057  3555  3883 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at fal.a(PG:38)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:09:41.057  3555  3883 E HttpOperation: 	... 17 more
,09-07 16:09:41.057  3555  3883 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:09:41.057  3555  3883 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	... 15 more
09-07 16:09:41.057  3555  3883 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:09:41.057  3555  3883 E ExperimentLoader: 	... 17 more
,09-07 16:09:41.133  2206  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 16:09:41.219   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130519, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:09:41.998  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:41.998  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:09:41.999  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:42.000  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.000  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.000  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:09:42.000  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.001  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.001  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.001  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.002  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.003  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.004  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.007  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:09:42.007  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.008  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.008  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.010  3807  3858 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 16:09:42.013  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:42.013  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.013  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:42.014  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.014  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.014  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.015  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.015  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.015  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.015  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.016  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.016  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.016  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.017  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.019  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.020  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.020  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.020  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:42.023  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 16:09:42.023  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:42.024  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-07 16:09:42.024  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:42.024  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:42.024  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:42.025  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-07 16:09:42.025  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:42.025  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:42.025  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.026  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.026  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.026  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.027  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.027  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.029  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.030  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.030  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.030  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.032  3807  3858 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 16:09:42.033  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:42.033  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.033  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:42.033  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.034  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.034  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.034  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.034  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.035  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.035  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.035  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:42.035  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.036  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.036  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.038  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.039  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.039  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.039  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:42.041  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 16:09:42.041  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:42.042  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.042  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:42.042  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:42.042  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.043  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.043  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:42.043  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.044  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.044  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.044  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:42.044  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.044  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.045  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.047  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:09:42.047  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.047  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.047  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:42.049  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 16:09:42.053  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:09:42.053  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 16:09:42.053  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 16:09:42.054  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 16:09:42.054  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:09:42.055  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 16:09:42.055  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 16:09:42.056  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 16:09:42.056  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:42.056  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.057  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:42.057  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:42.057  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.057  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.058  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.058  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.058  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.059  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.059  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.059  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.060  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.060  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.065  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:09:42.065  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:09:42.065  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.065  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list,
,09-07 16:09:42.067  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 16:09:42.068  3807  3858 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 16:09:42.068  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,09-07 16:09:42.078  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 16:09:42.078  3807  3858 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 16:09:42.079  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-07 16:09:42.079  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-07 16:09:42.079  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-07 16:09:42.080  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 16:09:42.080  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 16:09:42.080  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 16:09:42.080  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 16:09:42.081  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 16:09:42.082  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 16:09:42.082  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 16:09:42.082  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 16:09:42.082  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 16:09:42.082  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
09-07 16:09:42.083  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 16:09:42.083  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
,09-07 16:09:42.083  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-07 16:09:42.083  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 16:09:42.084  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-07 16:09:42.084  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 16:09:42.084  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-07 16:09:42.084  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 16:09:42.084  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 16:09:42.085  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-07 16:09:42.085  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 16:09:42.085  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-07 16:09:42.085  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-07 16:09:42.086  3807  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 16:09:42.086  3807  3858 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 16:09:42.086  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 16:09:42.087  3807  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 16:09:42.087  3807  3858 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 16:09:42.087  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 16:09:42.087  3807  3858 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 16:09:42.087  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 16:09:42.091  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 16:09:42.093  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 16:09:42.093  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 16:09:42.094  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 16:09:42.094  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 16:09:42.095  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-07 16:09:42.095  3807  3858 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 16:09:42.095  3807  3858 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-07 16:09:42.096  3807  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-07 16:09:42.097  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:42.097  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:09:42.098  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:42.098  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:42.098  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.098  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:42.098  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 16:09:42.099  3807  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:09:42.099  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:42.100  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.100  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.100  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:09:42.100  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:42.100  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.101  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.101  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.101  3807  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-07 16:09:42.101  3807  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
09-07 16:09:42.101  3807  3887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
,09-07 16:09:42.102  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.103  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.103  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.103  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.104  3807  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
09-07 16:09:42.105  3807  3858 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 16:09:42.106  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:42.106  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.106  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:42.106  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.106  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.106  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.107  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.107  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:42.107  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.107  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.107  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.107  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.107  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.107  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.109  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:09:42.109  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.109  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.110  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.111  3807  3858 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 16:09:42.111  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:42.111  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:42.111  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:42.112  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.112  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.112  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.112  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.112  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.112  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.112  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.113  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:42.113  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.113  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.113  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.114  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.114  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:42.114  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.115  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:42.116  3807  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 16:09:42.116  3807  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 16:09:42.116  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 16:09:42.116  3807  3858 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 16:09:42.117  3807  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 16:09:42.117  3807  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 16:09:42.117  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 16:09:42.117  3807  3858 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 16:09:42.117  3807  3858 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 16:09:42.117  3807  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 16:09:42.117  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 16:09:42.117  3807  3858 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 16:09:42.117  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:42.118  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:09:42.118  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:42.118  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.118  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.118  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.118  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.118  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.118  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:42.118  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.118  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.118  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.118  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.119  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.120  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:42.120  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:09:42.120  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:42.120  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.120  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:42.120  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.121  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:42.121  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:42.121  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:42.121  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:42.121  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:42.121  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:42.121  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:45.327  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:45.518  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:45.527  1526  3889 I VacuumService: Vacuum at: now=1473257385527 tag=VacuumService
,09-07 16:09:45.568  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 16:09:45.568  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 16:09:45.569  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:45.569  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:45.585  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 16:09:45.585  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 16:09:45.586  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 16:09:45.626  1526  3890 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 16:09:45.628  1526  3890 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 16:09:46.971   873  1303 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-07 16:09:47.122  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:47.122  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:47.123  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:47.123  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.123  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.124  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:47.124  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:47.124  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:09:47.124  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:47.125  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:47.125  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.125  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.126  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:47.126  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:47.126  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:47.127  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:47.127  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:47.127  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.127  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.128  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.131  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:09:47.131  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:09:47.132  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:47.133  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:47.138  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 16:09:47.139  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-07 16:09:47.141  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 16:09:47.143  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 16:09:47.144  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 16:09:47.144  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 16:09:47.145  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 16:09:47.145  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:09:47.146  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:47.146  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 16:09:47.146  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 16:09:47.147  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 16:09:47.147  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.147  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 16:09:47.148  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:47.148  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 16:09:47.148  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:47.148  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:09:47.148  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:09:47.148  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 16:09:47.149  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.149  3807  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:09:47.149  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.153  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:09:47.153  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:47.153  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:09:47.153  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:09:47.153  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:09:47.154  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:09:47.154  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:47.154  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:47.156  3807  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 16:09:47.156  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:47.156  3807  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 16:09:47.157  3807  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 16:09:47.157  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:47.157  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.157  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
,09-07 16:09:47.157  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.157  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
,09-07 16:09:47.157  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:09:47.158  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:47.158  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.158  3807  3807 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 16:09:47.158  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.158  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:47.159  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:47.159  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:47.159  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.160  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.161  3807  3858 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 16:09:47.161  3807  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 16:09:47.161  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 16:09:47.162  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:09:47.162  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:09:47.162  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:47.162  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:47.162  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:09:47.162  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:47.162  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.162  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.162  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:47.162  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.163  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.163  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:47.163  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.163  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.163  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.163  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.164  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:47.164  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:47.164  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.164  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.168  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:47.168  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:47.168  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:47.169  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:09:47.169  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.169  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.169  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:47.169  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.169  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.169  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:47.169  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.169  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.169  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: rele,ase: The given listener does not exist in the list - probably already removed
09-07 16:09:47.170  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.171  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:47.171  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:09:47.171  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.171  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.172  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:09:47.172  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:09:47.172  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:09:47.173  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:09:47.173  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.173  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.173  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc7e586 not in the list
09-07 16:09:47.173  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.173  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.173  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:47.173  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:47.173  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.173  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:47.173  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:09:47.175  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:09:47.175  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:09:47.175  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:47.175  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bafbe47 not in the list
09-07 16:09:47.176  3807  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 16:09:47.176  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 16:09:47.176  3807  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-07 16:09:47.176  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 16:09:47.176  3807  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 16:09:47.177  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 16:09:47.181  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 16:09:47.181  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 16:09:47.181  3807  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 16:09:47.182  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 16:09:47.182  3807  3858 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 16:09:47.182  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 16:09:47.182  3807  3858 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 16:09:47.182  3807  3858 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 16:09:47.183  3807  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 16:09:47.183  3807  3858 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 16:09:47.183  3807  3858 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-07 16:09:47.183  3807  3858 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 16:09:47.183  3807  3858 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 16:09:47.184  3807  3858 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 16:09:47.185  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:09:47.185  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@41abc36 added. We now have 3 listener(s)
09-07 16:09:47.185  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:09:47.187  3807  3858 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 16:09:47.187   873  1636 D WifiService: setWifiEnabled: true pid=3807, uid=10000
09-07 16:09:47.187   873  1636 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:09:47.232  2668  2766 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-07 16:09:47.232  2668  2796 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-07 16:09:47.570  1526  3890 W Uploader:  no longer exists, so no auth token.
,09-07 16:09:47.655  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:09:48.497  1526  3890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 16:09:48.497  1526  3890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 16:09:48.497  1526  3890 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:48.497  1526  3890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:48.517  1526  3890 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 16:09:48.517  1526  3890 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 16:09:48.517  1526  3890 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 16:09:48.880  1526  3890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 16:09:48.880  1526  3890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 16:09:48.880  1526  3890 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:09:48.880  1526  3890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:48.903  1526  3890 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 16:09:48.903  1526  3890 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 16:09:48.903  1526  3890 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 16:09:49.550  1526  3890 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 16:09:49.551  1526  3890 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-07 16:09:49.551  1526  3890 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:49.551  1526  3890 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:49.571  1526  3890 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 16:09:49.571  1526  3890 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 16:09:49.571  1526  3890 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 16:09:50.703   873  1878 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:09:52.195  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-07 16:09:52.195  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7ec737 added. We now have 4 listener(s)
09-07 16:09:52.195  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:09:52.212  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:09:52.212  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7ec737 removed from the list
09-07 16:09:52.213  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:52.213  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:09:52.213  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:52.215  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:09:52.216  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e37c4a4 added. We now have 4 listener(s)
,09-07 16:09:52.216  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:09:52.220  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:09:52.220  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e37c4a4 removed from the list
,09-07 16:09:52.221  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:09:52.221  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:09:52.221  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:09:52.224  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:09:52.224  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@680e20d added. We now have 4 listener(s)
,09-07 16:09:52.224  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:09:52.231   873  1944 D WifiService: setWifiEnabled: false pid=3807, uid=10000
09-07 16:09:52.232   873  1944 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:09:52.245  2668  2698 D BluetoothAdapterState: Current state: ON, message: 23,
09-07 16:09:52.245  2668  2698 D BluetoothAdapterProperties: Setting state to 13
09-07 16:09:52.246  2668  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 16:09:52.247  2668  2698 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 16:09:52.247  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:09:52.249  2668  2698 I BluetoothAdapterState: Entering PendingCommandState
09-07 16:09:52.250  2668  2702 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:09:52.250  2668  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 16:09:52.253  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.253  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:52.253  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.254  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:52.254  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:09:52.257  2668  2668 D HeadsetService: Received stop request...Stopping profile...
09-07 16:09:52.258  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.259  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 16:09:52.263  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.265   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 16:09:52.265   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 16:09:52.265   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:09:52.266   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 16:09:52.267   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 16:09:52.268  1916  2113 D BluetoothHeadset: Proxy object disconnected
09-07 16:09:52.269  1349  1968 D BluetoothHeadset: Proxy object disconnected
09-07 16:09:52.269  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.269  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:52.269   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 16:09:52.269  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-07 16:09:52.269   873   873 D BluetoothHeadset: Proxy object disconnected
,09-07 16:09:52.270  2668  2668 D A2dpService: Received stop request...Stopping profile...
09-07 16:09:52.270  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.270  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:09:52.270  2668  2802 D A2dpStateMachine: Exit Disconnected: -1
09-07 16:09:52.272   873   873 D BluetoothA2dp: Proxy object disconnected
09-07 16:09:52.273  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.273  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:52.273  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-07 16:09:52.274  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.274  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:52.274  2668  2668 D HidService: Received stop request...Stopping profile...
,09-07 16:09:52.274  2668  2668 D HidService: Stopping Bluetooth HidService
09-07 16:09:52.275  1349  1349 D BluetoothInputDevice: Proxy object disconnected
09-07 16:09:52.276  1349  1349 D HidProfile: Bluetooth service disconnected
09-07 16:09:52.276   873  1303 E native  : do suspend true
09-07 16:09:52.277  2668  2668 V BluetoothAdapterState: isTurningOff()=true
09-07 16:09:52.277  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.277  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:09:52.277  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:09:52.277  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.278  2668  2668 D HealthService: Received stop request...Stopping profile...
09-07 16:09:52.279  2668  2668 D PanService: Received stop request...Stopping profile...
,09-07 16:09:52.279  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 16:09:52.279  1349  1349 D PanProfile: Bluetooth service disconnected
09-07 16:09:52.281  2668  2668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 16:09:52.281  2668  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 16:09:52.282  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:09:52.282  2668  2668 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 16:09:52.282  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:09:52.282  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:09:52.282  2668  2702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 16:09:52.282  2668  2668 V BluetoothAdapterState: isTurningOff()=true
,09-07 16:09:52.282  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.282  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:09:52.283  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:09:52.284  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:09:52.284  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:09:52.284  2668  2766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 16:09:52.284  2668  2766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:09:52.284  2668  2766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 16:09:52.284  2668  2766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:09:52.284  2668  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 16:09:52.285  2668  2668 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 16:09:52.285  2668  2668 D BluetoothMapService: stop()
09-07 16:09:52.286  2668  2668 D BluetoothMapAppObserver: deinitObservers()
09-07 16:09:52.286  2668  2668 D BluetoothMapAppObserver: removeReceiver()
,09-07 16:09:52.287  1349  1349 D BluetoothMap: Proxy object disconnected
,09-07 16:09:52.288  1349  1349 D MapProfile: Bluetooth service disconnected
09-07 16:09:52.288  2668  2668 V BluetoothAdapterState: isTurningOff()=true
09-07 16:09:52.288  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.288  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:09:52.288  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:09:52.288  2668  2668 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 16:09:52.289  2668  2702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 16:09:52.289  2668  2668 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 16:09:52.290  2668  2668 V BluetoothAdapterState: isTurningOff()=true
09-07 16:09:52.290  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.290  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:09:52.290  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:09:52.290  2668  2668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 16:09:52.290  2668  2702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 16:09:52.291  2668  2668 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 16:09:52.291  2668  2668 V BluetoothAdapterState: isTurningOff()=true
09-07 16:09:52.291  2668  2668 V BluetoothAdapterState: isTurningOn()=false
,09-07 16:09:52.291  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:09:52.291  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:09:52.292  2668  2668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 16:09:52.292  2668  2668 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 16:09:52.292   873  1880 D DhcpClient: Clearing IP address
,09-07 16:09:52.293   372   871 D CommandListener: Setting iface cfg
09-07 16:09:52.293  2668  2668 D BluetoothMapService: MAP Service closeService in
09-07 16:09:52.293  2668  2668 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 16:09:52.293  2668  2668 D ObexServerSockets0: shutdown(block = true)
09-07 16:09:52.293  2668  2823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 16:09:52.295  2668  2668 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 16:09:52.295  2668  2824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 16:09:52.296  2668  2796 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 16:09:52.296  2668  2668 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 16:09:52.296  2668  2668 V BluetoothAdapterState: isTurningOff()=true
09-07 16:09:52.296  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.296   873  1887 D DhcpClient: Receive thread stopped
,09-07 16:09:52.296  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:09:52.297   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-07 16:09:52.297  2668  2668 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:09:52.297  2668  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 16:09:52.297  2668  2698 D BluetoothAdapterProperties: Setting state to 15
09-07 16:09:52.297  2668  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 16:09:52.297  2668  2698 I BluetoothAdapterState: Entering BleOnState
09-07 16:09:52.298  2668  2668 D BluetoothMapService: cleanup()
09-07 16:09:52.298  2668  2668 D BluetoothMapService: MAP Service closeService in
,09-07 16:09:52.301  2668  2668 I BtOppRfcommListener: stopping Accept Thread
09-07 16:09:52.302  2668  3426 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 16:09:52.302  1349  1367 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 16:09:52.302  2668  3426 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 16:09:52.306  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.306  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:52.307  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.307  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:09:52.309  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.309  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:52.310  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.310  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:09:52.312  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:52.312  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:52.312  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.313  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:09:52.316  1526  2190 V NativeCrypto: Read error: ssl=0xaeb6ae00: I/O error during system call, Connection timed out
,09-07 16:09:52.318  1526  2190 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6ae00: I/O error during system call, Broken pipe
,09-07 16:09:52.319   873   886 I ActivityManager: Start proc 3908:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 16:09:52.321   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 16:09:52.321   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 16:09:52.322   402   402 E Parcel  : Reading a NULL string not supported here.
,09-07 16:09:52.324  1349  2026 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:09:52.326   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 16:09:52.326   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 16:09:52.327   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:09:52.327   873  1303 E native  : do suspend true
09-07 16:09:52.328  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:09:52.332  1349  1968 D BluetoothMap: onBluetoothStateChange: up=false
09-07 16:09:52.332  1349  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:09:52.332  1349  2026 D BluetoothPan: onBluetoothStateChange on: false
09-07 16:09:52.333   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 16:09:52.333   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:09:52.333   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:09:52.333  1916  2281 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:09:52.333   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:09:52.334  2668  2698 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 16:09:52.334  2668  2698 D BluetoothAdapterProperties: Setting state to 16
09-07 16:09:52.334  2668  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 16:09:52.334  2668  2698 D BluetoothAdapterProperties: onBleDisable
09-07 16:09:52.334  2668  2698 I BluetoothAdapterState: Entering PendingCommandState
09-07 16:09:52.335  2668  2699 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 16:09:52.336  2668  2766 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 16:09:52.336  2668  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:09:52.336  2668  2702 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:09:52.339  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.339  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:09:52.341  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.341  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:09:52.342  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.342  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:09:52.343  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.344  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.348  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:52.366   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:09:52.371  3908  3908 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 16:09:52.381  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:09:52.384   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:09:52.385   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-07 16:09:52.386   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 16:09:52.386   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:09:52.388   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:09:52.389  3413  3413 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@189c700 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-07 16:09:52.392   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:09:52.407  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:52.407  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:09:52.409  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:09:52.411  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:09:52.420   873  1914 I ActivityManager: Start proc 3927:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 16:09:52.422   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:09:52.424  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.424  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:09:52.425  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.425  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:09:52.426   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 16:09:52.426  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.426  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:09:52.427  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:52.427  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:09:52.428  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:52.428  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:09:52.429  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:52.429  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:09:52.438  2206  2354 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 16:09:52.441   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9129eb2:true
,09-07 16:09:52.456   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-07 16:09:52.456   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 16:09:52.465  3927  3927 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 16:09:52.467  3908  3908 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 16:09:52.473  3908  3908 D BluetoothMap: Create BluetoothMap proxy object
,09-07 16:09:52.480  3908  3908 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 16:09:52.494  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:09:52.498   873   883 I ActivityManager: Killing 3246:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-07 16:09:52.537  2668  2702 I bt_hci  : shut_down
,09-07 16:09:52.560  2668  2706 D bt_hwcfg: hw_epilog_process
,09-07 16:09:52.560  2668  2706 I bt_vendor: low_power_mode_cb
,09-07 16:09:52.588  2668  2706 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 16:09:52.588  2668  2706 I bt_vendor: epilog_cb
,09-07 16:09:52.589  2668  2706 I bt_hci  : epilog_finished_callback
09-07 16:09:52.591  2668  2702 I bt_hci_h4: hal_close
,09-07 16:09:52.591  2668  2702 I bt_userial_vendor: device fd = 51 close
,09-07 16:09:52.684  3927  3927 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.684  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:09:52.685  3927  3927 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:09:52.685  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:09:52.691  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 16:09:52.707  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:09:52.711  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:09:52.745   873  1944 I ActivityManager: Start proc 3959:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-07 16:09:52.746   873  1944 I ActivityManager: Killing 3413:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 16:09:52.798  2668  2699 D bt_stack_manager: event_shut_down_stack finished.
,09-07 16:09:52.799  2668  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 16:09:52.811  2668  2668 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:09:52.811  2668  2698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 16:09:52.812  2668  2668 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 16:09:52.813  2668  2668 D BtGatt.GattService: stop()
09-07 16:09:52.813  2668  2668 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 16:09:52.817  2668  2668 V BluetoothAdapterState: isTurningOff()=false
09-07 16:09:52.818  2668  2668 V BluetoothAdapterState: isTurningOn()=false
09-07 16:09:52.818  2668  2668 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:09:52.818  2668  2668 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 16:09:52.818  2668  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 16:09:52.819  2668  2698 D BluetoothAdapterProperties: Setting state to 10
09-07 16:09:52.819  2668  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 16:09:52.820  2668  2698 I BluetoothAdapterState: Entering OffState
,09-07 16:09:52.821   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 16:09:52.830  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-07 16:09:52.832  2668  2668 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 16:09:52.833  2668  2668 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 16:09:52.833  2668  2668 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 16:09:52.833  2668  2699 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 16:09:52.835  2668  2699 D bt_stack_manager: event_clean_up_stack finished.
,09-07 16:09:52.847  2668  2668 I art     : System.exit called, status: 0
09-07 16:09:52.847  2668  2668 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 16:09:52.907   873  2002 I ActivityManager: Process com.android.bluetooth (pid 2668) has died
,09-07 16:09:53.012  3927  3952 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 16:09:53.076  3959  3979 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-07 16:09:53.076  3959  3979 I Babel_SMS: MmsConfig.loadMmsSettings
,09-07 16:09:53.083  3959  3979 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-07 16:09:53.083  3959  3979 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 16:09:53.118  3959  3979 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 16:09:53.118  3959  3979 I Babel_SMS: MmsConfig.loadFromResources
,09-07 16:09:53.121  3959  3979 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 16:09:53.121  3959  3979 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-07 16:09:53.156  3959  3959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 16:09:53.159  3959  3959 I Babel_Crash: startup - clean
,09-07 16:09:53.184  3959  3959 I Babel_telephony: TeleModule.launchCompleted
,09-07 16:09:53.194   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 16:09:53.204  3959  3959 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-07 16:09:53.211  3959  3959 W Babel   : BAM#gBA: invalid account id: -1
,09-07 16:09:53.212  3959  3959 W Babel   : BAM#gBA: invalid account id: -1
,09-07 16:09:53.212  3959  3959 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-07 16:09:53.224  3959  3984 I Babel   : deleted: false for 0
,09-07 16:09:53.227   873  1917 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 16:09:53.242  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:09:53.245  1746  1746 D SystemUpdateService: onCreate
,09-07 16:09:53.260  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 16:09:53.269  1746  3986 I SystemUpdateService: active receiver: enabled
,09-07 16:09:53.291  1746  3986 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:09:53.292  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 16:09:53.293  1746  3986 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 16:09:53.293  1746  3986 I SystemUpdateService: now status is 0 (complete)
09-07 16:09:53.293  1746  3986 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 16:09:53.293  1746  3986 I SystemUpdateService: file has been verified
09-07 16:09:53.293  1746  3986 I SystemUpdateService: OTA package size = 12249756
,09-07 16:09:53.295  1746  2433 I iu.UploadsManager: num queued entries: 0
,09-07 16:09:53.297  1746  2433 I iu.UploadsManager: num updated entries: 0
,09-07 16:09:53.298  1746  3986 I SystemUpdateService: showing system update notification
09-07 16:09:53.298  1746  2433 I iu.SyncManager: NEXT; no task
,09-07 16:09:53.309  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 16:09:53.310  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:09:53.320  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:09:53.324   873  2976 I ActivityManager: Start proc 3988:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 16:09:53.326  1746  1746 D SystemUpdateService: onDestroy
,09-07 16:09:53.373  3988  3988 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 16:09:53.376  3959  3959 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 16:09:53.384  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:09:53.390  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:09:53.397  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:09:53.405  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:09:53.410  3988  3988 D SprintDMHelper: simOperator: 
09-07 16:09:53.410  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:09:53.414  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:09:53.451   873  1369 I ActivityManager: Start proc 4000:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 16:09:53.454   873  1917 I ActivityManager: Killing 3576:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-07 16:09:53.493   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab72636:true
,09-07 16:09:53.521  3959  3959 I vclib   : onServiceConnected
,09-07 16:09:53.604   873  1917 I ActivityManager: Start proc 4016:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider,
,09-07 16:09:53.607  3959  4015 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 16:09:53.610   873  2003 I ActivityManager: Killing 3465:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 16:09:53.685  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 16:09:53.744  4016  4016 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 16:09:53.744  4016  4016 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 16:09:53.744  4016  4016 I GAv4    :   adb logcat -s GAv4
,09-07 16:09:53.759  4016  4016 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:09:53.765  4016  4016 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:09:53.801  4016  4033 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:09:53.909  4016  4016 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 16:09:53.950  4016  4016 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 16:09:53.964  4016  4016 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9517-9524)
,09-07 16:09:53.964  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 16:09:53.978  4016  4016 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c1cf030}
09-07 16:09:53.978  4016  4016 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 16:09:53.978  4016  4016 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 16:09:53.987  4016  4016 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 16:09:53.989  4016  4016 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 16:09:54.009  4016  4016 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 16:09:54.021  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 16:09:54.021  4016  4016 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 16:09:54.021  4016  4016 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 16:09:54.021  4016  4016 I Adreno  : Build Date                       : 10/20/15
09-07 16:09:54.021  4016  4016 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 16:09:54.021  4016  4016 I Adreno  : Local Branch                     : M14
09-07 16:09:54.021  4016  4016 I Adreno  : Remote Branch                    : 
09-07 16:09:54.021  4016  4016 I Adreno  : Remote Branch                    : 
09-07 16:09:54.021  4016  4016 I Adreno  : Reconstruct Branch               : 
,09-07 16:09:54.086  4016  4016 I NSApplication: Starting up...
,09-07 16:09:54.094  4016  4062 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 16:09:54.132   873  1369 I ActivityManager: Start proc 4067:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 16:09:54.133   873  1369 I ActivityManager: Killing 3501:android.process.acore/u0a5 (adj 15): empty #17
,09-07 16:09:54.219  4067  4067 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 16:09:54.430   873   884 I ActivityManager: Killing 3690:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 16:09:54.500   873  1944 I ActivityManager: Start proc 4081:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 16:09:54.589  4081  4081 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 16:09:54.647  4081  4081 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 16:09:54.661   873  2003 I ActivityManager: Killing 3707:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 16:09:57.257   873  1636 D WifiService: setWifiEnabled: true pid=3807, uid=10000
,09-07 16:09:57.257   873  1636 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:09:57.275   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 16:09:57.283  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:57.285  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:09:57.285  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:09:57.285  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:09:57.291  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:57.292  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:09:57.292  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:57.292  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:09:57.295  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:09:57.295  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:09:57.296  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:57.297  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:09:57.319   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 16:09:57.320   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 16:09:57.321   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 16:09:57.322   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 16:09:57.322   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 16:09:57.322   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 16:09:57.322   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 16:09:57.342   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 16:09:57.342   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:09:57.343   372   871 D CommandListener: Setting iface cfg
,09-07 16:09:57.352   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-07 16:09:57.352   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 16:09:57.354   873  1303 E native  : do suspend true
,09-07 16:09:57.361   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 16:09:57.361   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 16:09:57.369   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.,
,09-07 16:09:58.080   873  2003 I ActivityManager: Killing 2254:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 16:09:58.633   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:09:58.705   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.94 rxSuccessRate=6.62 delta 1000 -> 994
,09-07 16:09:58.707   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 16:09:58.707   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:09:58.724   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 16:09:58.774   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 16:09:58.775  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 16:09:59.198  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 16:09:59.278  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 16:09:59.279  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-07 16:09:59.282   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:09:59.297   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 16:09:59.298   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 16:09:59.298   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:09:59.319   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:09:59.328   372   871 D CommandListener: Setting iface cfg
,09-07 16:09:59.328   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 16:09:59.334   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 16:09:59.386   873  4116 D DhcpClient: Receive thread started
,09-07 16:09:59.474   873  1303 E native  : do suspend false
,09-07 16:09:59.494   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 16:09:59.514   873  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,09-07 16:09:59.515   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,09-07 16:09:59.519   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 16:09:59.534   873  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 16:09:59.536   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 16:09:59.543   372   871 D CommandListener: Setting iface cfg
,09-07 16:09:59.554   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 16:09:59.555   873  1303 E native  : do suspend true
09-07 16:09:59.555   873  1880 D DhcpClient: Scheduling renewal in 86399s
,09-07 16:09:59.568   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-07 16:09:59.568   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 16:09:59.570   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 16:09:59.572   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
09-07 16:09:59.576   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 16:09:59.651   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 16:09:59.651   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 16:09:59.653   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 16:09:59.654   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 16:09:59.655   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 16:09:59.663   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 16:09:59.671   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 16:09:59.671   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 16:09:59.672   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 16:09:59.672   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 16:09:59.672   873  1305 D ConnectivityService:    accepting network in place of null
09-07 16:09:59.672   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:09:59.673   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 16:09:59.680   873  4115 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175240, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:09:59.702   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:09:59.750   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:09:59.759   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 16:09:59.759   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:09:59.770   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:09:59.775   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-07 16:09:59.784   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 16:09:59.785  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:59.785  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:59.785  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.785  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:59.787  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:59.788  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:09:59.788  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.788  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:59.790  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:09:59.790  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:09:59.790  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:09:59.790  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:09:59.809  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:09:59.813  1746  1746 D SystemUpdateService: onCreate
,09-07 16:09:59.816  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 16:09:59.838  1746  4126 I SystemUpdateService: active receiver: enabled
,09-07 16:09:59.845  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 16:09:59.846   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 14:09:59 GMT], X-Android-Received-Millis=[1473257399845], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473257399820]}
,09-07 16:09:59.848  1746  2433 I iu.UploadsManager: num queued entries: 0
,09-07 16:09:59.848   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 16:09:59.848  1746  2433 I iu.UploadsManager: num updated entries: 0
09-07 16:09:59.848   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 16:09:59.848   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 16:09:59.849  1746  2433 I iu.SyncManager: NEXT; no task
,09-07 16:09:59.852   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 16:09:59.860  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 16:09:59.861  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:09:59.863  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:09:59.868  1746  4130 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 16:09:59.868  1746  4130 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 16:09:59.870  1746  4130 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:09:59.870  3988  3988 D SprintDMHelper: simOperator: 
09-07 16:09:59.870  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:09:59.877  1746  4126 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:09:59.879  1746  4126 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 16:09:59.879  1746  4126 I SystemUpdateService: now status is 0 (complete)
09-07 16:09:59.879  1746  4126 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 16:09:59.879  1746  4126 I SystemUpdateService: file has been verified
09-07 16:09:59.882  1746  4126 I SystemUpdateService: OTA package size = 12249756
,09-07 16:09:59.885  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:59.890  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:09:59.927  1746  4126 I SystemUpdateService: showing system update notification
,09-07 16:09:59.962  1746  1746 D SystemUpdateService: onDestroy
,09-07 16:09:59.975  1526  2328 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 16:09:59.976  1526  2328 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 16:09:59.976  1526  2328 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:09:59.976  1526  2328 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:09:59.996  1746  4130 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-07 16:10:00.074  3959  4134 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 16:10:00.759   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 16:10:02.269   873  1890 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,09-07 16:10:02.269   873  1890 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:10:02.301  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 16:10:02.305   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 16:10:02.306   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 16:10:02.306   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:10:02.306   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:10:02.324   873  1303 E native  : do suspend true
,09-07 16:10:02.340   873  1880 D DhcpClient: Clearing IP address
09-07 16:10:02.341   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-07 16:10:02.350  1526  4138 V NativeCrypto: Read error: ssl=0x9ae55a00: I/O error during system call, Connection timed out
,09-07 16:10:02.351   372   871 D CommandListener: Setting iface cfg
09-07 16:10:02.353   873  4116 D DhcpClient: Receive thread stopped
,09-07 16:10:02.352  1526  4138 V NativeCrypto: SSL shutdown failed: ssl=0x9ae55a00: I/O error during system call, Broken pipe
,09-07 16:10:02.360   873  2003 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-07 16:10:02.360   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-07 16:10:02.364   873  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 16:10:02.365   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 16:10:02.367   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-07 16:10:02.367   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 16:10:02.371   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 16:10:02.372   402   402 E Parcel  : Reading a NULL string not supported here.
09-07 16:10:02.375   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 16:10:02.377   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 16:10:02.382   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:10:02.382   873  1303 E native  : do suspend true
,09-07 16:10:02.391   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 16:10:02.419   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:10:02.443   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:10:02.444   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-07 16:10:02.444   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 16:10:02.445   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:10:02.448   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:10:02.456   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:10:02.461  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.461  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:02.461  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.461  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.462  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.462  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:02.462  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.462  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.463  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.463  3807  3807 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-07 16:10:02.463  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.463  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.473   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 16:10:02.476  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.476  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:02.476  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.476  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.477  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.477  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:02.477  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.477  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.478  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:02.478  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:02.478  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:02.478  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:02.478   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 16:10:02.480  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 16:10:02.482  2206  2354 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 16:10:02.484  1746  1746 D SystemUpdateService: onCreate
09-07 16:10:02.488  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-07 16:10:02.498  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-07 16:10:02.500  1746  2433 I iu.UploadsManager: num queued entries: 0
09-07 16:10:02.501  1746  2433 I iu.UploadsManager: num updated entries: 0
09-07 16:10:02.501  1746  2433 I iu.SyncManager: NEXT; no task
,09-07 16:10:02.505  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 16:10:02.506  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 16:10:02.510  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 16:10:02.517  1746  4151 I SystemUpdateService: active receiver: enabled
09-07 16:10:02.519  3988  3988 D SprintDMHelper: simOperator: 
09-07 16:10:02.519  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 16:10:02.526   372   871 E Netd    : netlink response contains error (No such file or directory)
09-07 16:10:02.528   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 16:10:02.528   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 16:10:02.547  3959  4154 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 16:10:02.549  1746  4151 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-07 16:10:02.551  1746  4151 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 16:10:02.551  1746  4151 I SystemUpdateService: now status is 0 (complete)
09-07 16:10:02.551  1746  4151 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 16:10:02.551  1746  4151 I SystemUpdateService: file has been verified
,09-07 16:10:02.551  1746  4151 I SystemUpdateService: OTA package size = 12249756
,09-07 16:10:02.559  1746  4151 I SystemUpdateService: showing system update notification
,09-07 16:10:02.581  1746  1746 D SystemUpdateService: onDestroy
,09-07 16:10:07.329   873   890 I ActivityManager: Start proc 4157:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 16:10:07.441  4157  4157 D AdapterServiceConfig: Adding HeadsetService
,09-07 16:10:07.441  4157  4157 D AdapterServiceConfig: Adding A2dpService
09-07 16:10:07.441  4157  4157 D AdapterServiceConfig: Adding HidService
,09-07 16:10:07.442  4157  4157 D AdapterServiceConfig: Adding HealthService
09-07 16:10:07.442  4157  4157 D AdapterServiceConfig: Adding PanService
,09-07 16:10:07.442  4157  4157 D AdapterServiceConfig: Adding GattService
09-07 16:10:07.443  4157  4157 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 16:10:07.466   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b729fb:true
,09-07 16:10:07.466  4157  4157 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 16:10:07.471  4157  4157 I bt_bluedroid: init
,09-07 16:10:07.472  4157  4169 I BluetoothAdapterState: Entering OffState
,09-07 16:10:07.479  4157  4170 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 16:10:07.479  4157  4170 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 16:10:07.480  4157  4170 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 16:10:07.481  4157  4170 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 16:10:07.484  4157  4157 I bt_bluedroid: get_profile_interface socket
,09-07 16:10:07.488  4157  4157 I bt_bluedroid: get_profile_interface sdp
,09-07 16:10:07.492  4157  4173 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:10:07.494  4157  4173 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:10:07.495  4157  4168 I bt_bluedroid: config_hci_snoop_log
,09-07 16:10:07.496   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 16:10:07.503  4157  4169 D BluetoothAdapterState: Current state: OFF, message: 0
09-07 16:10:07.504  4157  4169 D BluetoothAdapterProperties: Setting state to 14
09-07 16:10:07.504  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 16:10:07.508  4157  4169 D BluetoothBondStateMachine: make
,09-07 16:10:07.512  4157  4174 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 16:10:07.520  4157  4169 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:10:07.520  4157  4157 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 16:10:07.526  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:07.527  4157  4157 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:10:07.527  4157  4157 D BtGatt.GattService: Received start request. Starting profile...
09-07 16:10:07.528  4157  4157 D BtGatt.GattService: start()
,09-07 16:10:07.528  4157  4157 I bt_bluedroid: get_profile_interface gatt
,09-07 16:10:07.530  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:07.530  4157  4157 D BtGatt.AdvertiseManager: advertise manager created
,09-07 16:10:07.540  4157  4157 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:07.540  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:07.541  4157  4157 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 16:10:07.541  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:07.541  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 16:10:07.542  4157  4169 I bt_bluedroid: enable
,09-07 16:10:07.542  4157  4170 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 16:10:07.543  4157  4170 I bt_hci  : start_up
,09-07 16:10:07.554  4157  4170 I bt_vendor: alloc value 0xb39e9189
,09-07 16:10:07.554  4157  4170 I bt_vendor: init
09-07 16:10:07.555  4157  4170 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 16:10:07.555  4157  4170 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 16:10:07.663  4157  4170 D bt_hci  : start_up starting async portion
,09-07 16:10:07.664  4157  4177 I bt_hci  : event_finish_startup
09-07 16:10:07.664  4157  4177 I bt_hci_h4: hal_open
09-07 16:10:07.665  4157  4177 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 16:10:07.676   873  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-07 16:10:07.678  4157  4177 I bt_userial_vendor: device fd = 51 open
,09-07 16:10:07.703  4157  4177 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:10:07.735  4157  4177 D bt_hwcfg: Chipset BCM4354A2
,09-07 16:10:07.736  4157  4177 D bt_hwcfg: Target name = [BCM4354A2]
09-07 16:10:07.736  4157  4177 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 16:10:08.406  4157  4177 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 16:10:08.407  4157  4177 D bt_hwcfg: Settlement delay -- 100 ms
09-07 16:10:08.408  4157  4177 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 16:10:08.524  4157  4177 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:10:08.525  4157  4177 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 16:10:08.554  4157  4177 I bt_hwcfg: vendor lib fwcfg completed
,09-07 16:10:08.555  4157  4177 I bt_vendor: firmware callback
09-07 16:10:08.555  4157  4177 I bt_hci  : firmware_config_callback
,09-07 16:10:08.567  4157  4179 I bt_btu  : btu_task pending for preload complete event
,09-07 16:10:08.567  4157  4179 I bt_btu_task: Bluetooth chip preload is complete
09-07 16:10:08.567  4157  4179 I bt_btu  : btu_task received preload complete event
,09-07 16:10:08.577  4157  4179 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 16:10:08.577  4157  4179 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 16:10:08.578  4157  4179 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 16:10:08.578  4157  4179 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 16:10:08.578  4157  4179 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 16:10:08.578  4157  4179 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 16:10:08.579  4157  4179 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 16:10:08.579  4157  4179 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 16:10:08.579  4157  4179 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 16:10:08.580  4157  4179 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 16:10:08.580  4157  4179 I         : BTE_InitTraceLevels -- TRC_SDP
,09-07 16:10:08.580  4157  4179 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 16:10:08.580  4157  4179 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 16:10:08.581  4157  4179 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-07 16:10:08.581  4157  4179 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 16:10:08.716  4157  4179 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,09-07 16:10:08.717  4157  4179 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,09-07 16:10:08.739  4157  4173 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 16:10:08.741  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 16:10:08.742  4157  4173 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:10:08.745  4157  4173 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:10:08.750  4157  4173 D BluetoothAdapterProperties: Scan Mode:20
,09-07 16:10:08.750  4157  4173 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 16:10:08.752  4157  4173 D bt_hci  : do_postload posting postload work item
,09-07 16:10:08.752  4157  4177 I bt_hci  : event_postload
09-07 16:10:08.752  4157  4177 I bt_vendor: sco_config_cb
09-07 16:10:08.753  4157  4177 I bt_hci  : sco_config_callback postload finished.
,09-07 16:10:08.755  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.758  4157  4173 D bt_bte_conf: Device ID record 1 : primary
,09-07 16:10:08.758  4157  4173 D bt_bte_conf:   vendorId            = 000f
,09-07 16:10:08.758  4157  4173 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 16:10:08.758  4157  4173 D bt_bte_conf:   product             = 1200
09-07 16:10:08.758  4157  4173 D bt_bte_conf:   version             = 1436
09-07 16:10:08.758  4157  4173 D bt_bte_conf:   clientExecutableURL = 
,09-07 16:10:08.758  4157  4173 D bt_bte_conf:   serviceDescription  = 
09-07 16:10:08.758  4157  4173 D bt_bte_conf:   documentationURL    = 
09-07 16:10:08.759  4157  4173 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 16:10:08.759  4157  4170 D bt_stack_manager: event_start_up_stack finished
09-07 16:10:08.759  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 16:10:08.760  4157  4169 D BluetoothAdapterProperties: Setting state to 15
09-07 16:10:08.760  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 16:10:08.761  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.763  4157  4177 I bt_vendor: low_power_mode_cb
,09-07 16:10:08.763  4157  4169 I BluetoothAdapterState: Entering BleOnState
09-07 16:10:08.765  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:08.769  4157  4169 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 16:10:08.770  4157  4169 D BluetoothAdapterProperties: Setting state to 11
,09-07 16:10:08.770  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 16:10:08.784  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:08.785  4157  4157 D HeadsetService: Received start request. Starting profile...
,09-07 16:10:08.789  4157  4157 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 16:10:08.789  4157  4157 D HeadsetStateMachine: make
,09-07 16:10:08.792  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.794  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:08.797  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.798  4157  4169 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:10:08.800  4157  4157 D HeadsetStateMachine: max_hf_connections = 1
,09-07 16:10:08.801  4157  4157 I bt_bluedroid: get_profile_interface handsfree
09-07 16:10:08.801  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 16:10:08.801  4157  4173 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-07 16:10:08.806  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:08.807  4157  4157 D A2dpService: Received start request. Starting profile...
,09-07 16:10:08.807  4157  4157 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 16:10:08.808  4157  4157 I bt_bluedroid: get_profile_interface avrcp
,09-07 16:10:08.814  4157  4157 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 16:10:08.814  4157  4157 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 16:10:08.814  4157  4157 D A2dpStateMachine: make
,09-07 16:10:08.815  4157  4157 I bt_bluedroid: get_profile_interface a2dp
,09-07 16:10:08.816  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 16:10:08.817  4157  4189 D A2dpStateMachine: Enter Disconnected: -2
,09-07 16:10:08.818  4157  4157 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 16:10:08.819  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:08.820  4157  4157 D HidService: Received start request. Starting profile...
,09-07 16:10:08.820  3908  3908 D BluetoothInputDevice: Proxy object connected
09-07 16:10:08.821  4157  4157 I bt_bluedroid: get_profile_interface hidhost
09-07 16:10:08.821  4157  4157 D HidService: setHidService(): set to: null
,09-07 16:10:08.821  4157  4173 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
,09-07 16:10:08.821  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 16:10:08.821  3908  3908 D HidProfile: Bluetooth service connected
09-07 16:10:08.822  4157  4157 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 16:10:08.822  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:08.823  4157  4157 D HealthService: Received start request. Starting profile...
09-07 16:10:08.824  4157  4157 I bt_bluedroid: get_profile_interface health
09-07 16:10:08.825  4157  4157 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 16:10:08.825  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:08.826  4157  4157 D PanService: Received start request. Starting profile...
09-07 16:10:08.827  4157  4157 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 16:10:08.827  4157  4157 I bt_bluedroid: get_profile_interface pan
09-07 16:10:08.827  4157  4173 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 16:10:08.832  4157  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:08.833  4157  4157 D BluetoothMapService: Received start request. Starting profile...
09-07 16:10:08.833  4157  4157 D BluetoothMapService: start()
09-07 16:10:08.835  4157  4157 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 16:10:08.836  4157  4157 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 16:10:08.836  4157  4157 D BluetoothMapAppObserver: createReceiver()
09-07 16:10:08.836  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 16:10:08.836  3908  3908 D PanProfile: Bluetooth service connected
09-07 16:10:08.836  3908  3908 D BluetoothMap: Proxy object connected
09-07 16:10:08.837  4157  4157 D BluetoothMapAppObserver: initObservers()
,09-07 16:10:08.837  3908  3908 D MapProfile: Bluetooth service connected
09-07 16:10:08.837  4157  4157 D BluetoothMapAppObserver: getEnabledAccountItems()
09-07 16:10:08.837  3908  3908 D BluetoothMap: getConnectedDevices()
09-07 16:10:08.838  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:10:08.839  3908  3908 D BluetoothMap: Bluetooth is Not enabled
,09-07 16:10:08.843  4157  4157 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:08.843  4157  4157 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:08.843  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.843  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:08.843  4157  4187 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 16:10:08.844  4157  4157 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:08.844  4157  4157 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:08.844  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.844  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOn()=true
,09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.845  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:08.846  4157  4157 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:08.846  4157  4157 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:08.846  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:08.846  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:08.846  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-07 16:10:08.847  4157  4169 D BluetoothAdapterProperties: ScanMode =  20
,09-07 16:10:08.847  4157  4169 D BluetoothAdapterProperties: State =  11
09-07 16:10:08.849  4157  4173 D BluetoothAdapterProperties: Scan Mode:21
09-07 16:10:08.849  4157  4173 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 16:10:08.849  4157  4169 D BluetoothAdapterProperties: Setting state to 12
,09-07 16:10:08.849  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.849  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 16:10:08.850  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:10:08.852  4157  4169 I BluetoothAdapterState: Entering OnState
09-07 16:10:08.852  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 16:10:08.852  1349  2026 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:08.852  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:10:08.856  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:08.857  1349  1349 D BluetoothInputDevice: Proxy object connected
,09-07 16:10:08.857  1349  1349 D HidProfile: Bluetooth service connected
,09-07 16:10:08.858  1349  1367 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:08.859  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:08.859  1349  1361 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 16:10:08.861  1349  1968 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:10:08.861  1349  1349 D BluetoothMap: Proxy object connected
09-07 16:10:08.861  1349  1349 D MapProfile: Bluetooth service connected
09-07 16:10:08.861  1349  1349 D BluetoothMap: getConnectedDevices()
09-07 16:10:08.861  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:08.861  1349  1361 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:10:08.862  4157  4157 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 16:10:08.862  4157  4157 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 16:10:08.862  1349  1349 D BluetoothA2dp: Proxy object connected
09-07 16:10:08.863  3908  3918 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 16:10:08.863  4157  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:10:08.864   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:08.864   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:10:08.864  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 16:10:08.864  1349  1349 D PanProfile: Bluetooth service connected
09-07 16:10:08.864   873   873 D BluetoothA2dp: Proxy object connected
,09-07 16:10:08.865   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:08.865  1916  2282 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:08.865  3908  3920 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:10:08.866  4157  4157 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:10:08.866   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:08.866  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:10:08.866  4157  4157 D ObexServerSockets: Succeed to create listening sockets 
,09-07 16:10:08.867  4157  4157 D ObexServerSockets0: startAccept()
09-07 16:10:08.867  4157  4157 D ObexServerSockets0: prepareForNewConnect()
09-07 16:10:08.868   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 16:10:08.868  4157  4157 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 16:10:08.868  4157  4157 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 16:10:08.869  4157  4157 D BluetoothMapService: onReceive
09-07 16:10:08.869  4157  4157 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 16:10:08.869  4157  4157 D BluetoothMapService: STATE_ON
09-07 16:10:08.870  4157  4195 D ObexServerSockets0: Accepting socket connection...
09-07 16:10:08.871  4157  4194 D ObexServerSockets0: Accepting socket connection...
09-07 16:10:08.871  3908  3908 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:08.872  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:08.874  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:08.875  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:08.875  3908  3908 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 16:10:08.876  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:08.883  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:10:08.885  3908  3908 D BluetoothA2dp: Proxy object connected
,09-07 16:10:08.889  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:10:08.893  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:10:08.893  4157  4157 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 16:10:08.893  4157  4157 D ObexServerSockets0: prepareForNewConnect()
09-07 16:10:08.894  3908  3908 D BluetoothPbap: Proxy object connected
,09-07 16:10:08.895  3908  3908 D PbapServerProfile: Bluetooth service connected
,09-07 16:10:08.896  1349  1349 D BluetoothPbap: Proxy object connected
,09-07 16:10:08.896  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-07 16:10:08.900  4157  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:08.909  4157  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:08.911  4157  4204 I BtOppRfcommListener: Accept thread started.
,09-07 16:10:08.964   873   873 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.964  1916  1936 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.965   873   890 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.965  1349  1361 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.966  1349  1349 D HeadsetProfile: Bluetooth service connected
09-07 16:10:08.966   873   873 D BluetoothHeadset: Proxy object connected
09-07 16:10:08.966   873   873 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.967  1916  2281 D BluetoothHeadset: Proxy object connected,
09-07 16:10:08.967   873   890 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.979  3908  3918 D BluetoothHeadset: Proxy object connected
,09-07 16:10:08.980  3908  3908 D HeadsetProfile: Bluetooth service connected
,09-07 16:10:10.725  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:10:10.739  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:10:10.745  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:10:10.813  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 16:10:10.814  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 16:10:10.814  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:10:10.815  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:10:10.879  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 16:10:10.880  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 16:10:10.881  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 16:10:12.289  4157  4169 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 16:10:12.289  4157  4169 D BluetoothAdapterProperties: Setting state to 13
,09-07 16:10:12.289  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 16:10:12.291  4157  4169 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 16:10:12.297  4157  4169 I BluetoothAdapterState: Entering PendingCommandState
09-07 16:10:12.305  4157  4157 D BluetoothMapService: onReceive
09-07 16:10:12.305  4157  4157 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 16:10:12.305  4157  4157 D BluetoothMapService: STATE_TURNING_OFF
,09-07 16:10:12.306  4157  4157 D BluetoothMapService: MAP Service closeService in
09-07 16:10:12.306  4157  4157 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 16:10:12.307  4157  4157 D ObexServerSockets0: shutdown(block = true)
,09-07 16:10:12.307  4157  4194 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 16:10:12.310  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:10:12.310  4157  4157 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:12.310  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:10:12.310  4157  4157 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 16:10:12.310  4157  4195 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 16:10:12.312  4157  4181 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 16:10:12.312  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:12.313  4157  4157 I BtOppRfcommListener: stopping Accept Thread
09-07 16:10:12.313  4157  4204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 16:10:12.314  4157  4204 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 16:10:12.313  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:12.317  4157  4173 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:10:12.318  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 16:10:12.320  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:12.320  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:12.321  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:12.321  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:12.324  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:12.324  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:12.324  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 16:10:12.325  3807  3807 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:10:12.325  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:12.327  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.323  4157  4157 D HeadsetService: Received stop request...Stopping profile...
09-07 16:10:12.328  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.330  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.331  3908  3918 D BluetoothHeadset: Proxy object disconnected
09-07 16:10:12.332  4157  4157 D A2dpService: Received stop request...Stopping profile...
09-07 16:10:12.332   873   873 D BluetoothHeadset: Proxy object disconnected
,09-07 16:10:12.332  4157  4189 D A2dpStateMachine: Exit Disconnected: -1
09-07 16:10:12.332  1916  2282 D BluetoothHeadset: Proxy object disconnected
09-07 16:10:12.333  1349  1367 D BluetoothHeadset: Proxy object disconnected
09-07 16:10:12.333  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-07 16:10:12.334   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 16:10:12.334   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 16:10:12.335  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-07 16:10:12.335   873   873 D BluetoothA2dp: Proxy object disconnected
09-07 16:10:12.336  4157  4157 D HidService: Received stop request...Stopping profile...
09-07 16:10:12.336  4157  4157 D HidService: Stopping Bluetooth HidService
,09-07 16:10:12.337  1349  1349 D BluetoothInputDevice: Proxy object disconnected
,09-07 16:10:12.338  1349  1349 D HidProfile: Bluetooth service disconnected
09-07 16:10:12.338  4157  4157 D HealthService: Received stop request...Stopping profile...
09-07 16:10:12.340  4157  4157 D PanService: Received stop request...Stopping profile...
,09-07 16:10:12.340  3908  3908 D DockEventReceiver: finishStartingService: stopping service
09-07 16:10:12.340  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 16:10:12.340  1349  1349 D PanProfile: Bluetooth service disconnected
,09-07 16:10:12.341  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.341  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.341  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:12.341  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:12.342  4157  4157 D BluetoothMapService: Received stop request...Stopping profile...
09-07 16:10:12.342  4157  4157 D BluetoothMapService: stop()
09-07 16:10:12.342  4157  4157 D BluetoothMapAppObserver: deinitObservers()
09-07 16:10:12.342  4157  4157 D BluetoothMapAppObserver: removeReceiver()
,09-07 16:10:12.343  1349  1349 D BluetoothMap: Proxy object disconnected
09-07 16:10:12.344  1349  1349 D MapProfile: Bluetooth service disconnected
09-07 16:10:12.344  3908  3908 D HeadsetProfile: Bluetooth service disconnected
,09-07 16:10:12.344  3908  3908 D BluetoothA2dp: Proxy object disconnected
09-07 16:10:12.345  3908  3908 D BluetoothInputDevice: Proxy object disconnected
09-07 16:10:12.345  3908  3908 D HidProfile: Bluetooth service disconnected
,09-07 16:10:12.345  4157  4157 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 16:10:12.345  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 16:10:12.345  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:10:12.345  4157  4157 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 16:10:12.345  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:10:12.345  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:10:12.345  4157  4173 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 16:10:12.346  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.346  4157  4157 V BluetoothAdapterState: isTurningOn()=false
,09-07 16:10:12.346  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:10:12.346  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:12.348  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-07 16:10:12.348  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:10:12.348  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:10:12.348  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.348  4157  4179 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 16:10:12.348  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.348  4157  4179 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:10:12.348  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:10:12.348  4157  4179 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 16:10:12.348  4157  4179 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 16:10:12.348  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:12.349  4157  4157 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 16:10:12.349  4157  4173 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 16:10:12.349  4157  4157 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 16:10:12.349  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.349  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.349  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:12.350  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:12.350  4157  4157 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 16:10:12.350  4157  4173 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 16:10:12.350  4157  4157 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 16:10:12.351  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.351  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.351  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:10:12.351  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:12.351  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:12.352  4157  4157 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 16:10:12.352  4157  4157 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 16:10:12.353  4157  4157 D BluetoothMapService: MAP Service closeService in
09-07 16:10:12.353  4157  4157 V BluetoothAdapterState: isTurningOff()=true
09-07 16:10:12.353  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.353  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:12.353  4157  4157 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:12.354  3908  3908 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 16:10:12.354  3908  3908 D PanProfile: Bluetooth service disconnected
09-07 16:10:12.354  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 16:10:12.354  4157  4169 D BluetoothAdapterProperties: Setting state to 15
09-07 16:10:12.354  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 16:10:12.354  3908  3908 D BluetoothMap: Proxy object disconnected
09-07 16:10:12.354  3908  3908 D MapProfile: Bluetooth service disconnected
09-07 16:10:12.354  4157  4157 D BluetoothMapService: cleanup()
09-07 16:10:12.354  4157  4157 D BluetoothMapService: MAP Service closeService in
09-07 16:10:12.354  1349  1968 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 16:10:12.355  4157  4169 I BluetoothAdapterState: Entering BleOnState
09-07 16:10:12.355  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:10:12.356  1349  2026 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:10:12.357  3908  3908 D BluetoothPbap: Proxy object disconnected
09-07 16:10:12.357  3908  3908 D PbapServerProfile: Bluetooth service disconnected
09-07 16:10:12.357  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:10:12.357  1349  1367 D BluetoothMap: onBluetoothStateChange: up=false
09-07 16:10:12.359  1349  1968 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.362  3908  3918 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.362  1349  2026 D BluetoothPan: onBluetoothStateChange on: false
09-07 16:10:12.362  3908  3920 D BluetoothMap: onBluetoothStateChange: up=false
09-07 16:10:12.363   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.367   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:10:12.367   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.368  1916  1936 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.368  3908  3918 D BluetoothPan: onBluetoothStateChange on: false
,09-07 16:10:12.370   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:10:12.370  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:10:12.370  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 16:10:12.371  4157  4169 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 16:10:12.371  4157  4169 D BluetoothAdapterProperties: Setting state to 16
09-07 16:10:12.371  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 16:10:12.373  4157  4169 D BluetoothAdapterProperties: onBleDisable
,09-07 16:10:12.374  4157  4169 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:10:12.374  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:12.374  4157  4170 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-07 16:10:12.375  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 16:10:12.375  4157  4179 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 16:10:12.375  4157  4179 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:10:12.375  4157  4173 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:10:12.375  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.377  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.378  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:12.380  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.381  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:10:12.381  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:12.384  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:10:12.577  4157  4173 I bt_hci  : shut_down
,09-07 16:10:12.578  4157  4177 D bt_hwcfg: hw_epilog_process
,09-07 16:10:12.593  4157  4177 I bt_vendor: low_power_mode_cb
,09-07 16:10:12.623  4157  4177 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 16:10:12.623  4157  4177 I bt_vendor: epilog_cb
09-07 16:10:12.623  4157  4177 I bt_hci  : epilog_finished_callback
,09-07 16:10:12.632  4157  4173 I bt_hci_h4: hal_close
,09-07 16:10:12.633  4157  4173 I bt_userial_vendor: device fd = 51 close
,09-07 16:10:12.766  4157  4170 D bt_stack_manager: event_shut_down_stack finished.
,09-07 16:10:12.768  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 16:10:12.773  4157  4169 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 16:10:12.774  4157  4157 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 16:10:12.775  4157  4157 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 16:10:12.775  4157  4157 D BtGatt.GattService: stop()
09-07 16:10:12.776  4157  4157 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 16:10:12.781  4157  4157 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:12.782  4157  4157 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:12.782  4157  4157 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:10:12.782  4157  4157 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 16:10:12.783  4157  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 16:10:12.784  4157  4169 D BluetoothAdapterProperties: Setting state to 10
09-07 16:10:12.784  4157  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 16:10:12.786  4157  4169 I BluetoothAdapterState: Entering OffState
09-07 16:10:12.787   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 16:10:12.821  4157  4157 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 16:10:12.822  4157  4157 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 16:10:12.824  4157  4170 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 16:10:12.827  4157  4170 D bt_stack_manager: event_clean_up_stack finished.
,09-07 16:10:12.827  4157  4157 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 16:10:12.829  4157  4157 I art     : System.exit called, status: 0
,09-07 16:10:12.829  4157  4157 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 16:10:12.870   873  3132 I ActivityManager: Process com.android.bluetooth (pid 4157) has died
,09-07 16:10:17.285  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:10:17.286  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:17.290  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:10:17.291  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@680e20d removed from the list
09-07 16:10:17.291  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:17.291  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:17.292  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:17.295  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:10:17.295  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cee9fd3 added. We now have 4 listener(s)
09-07 16:10:17.295  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:10:17.297  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:17.297  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cee9fd3 removed from the list
,09-07 16:10:17.298  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:17.298  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:17.298  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:17.301  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:17.301  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67e8710 added. We now have 4 listener(s)
,09-07 16:10:17.301  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:10:22.315  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:22.360   873   890 I ActivityManager: Start proc 4215:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 16:10:22.491  4215  4215 D AdapterServiceConfig: Adding HeadsetService
,09-07 16:10:22.492  4215  4215 D AdapterServiceConfig: Adding A2dpService
09-07 16:10:22.492  4215  4215 D AdapterServiceConfig: Adding HidService
09-07 16:10:22.492  4215  4215 D AdapterServiceConfig: Adding HealthService
,09-07 16:10:22.492  4215  4215 D AdapterServiceConfig: Adding PanService
09-07 16:10:22.494  4215  4215 D AdapterServiceConfig: Adding GattService
09-07 16:10:22.494  4215  4215 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 16:10:22.511   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50b8ee:true
09-07 16:10:22.512  4215  4215 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 16:10:22.517  4215  4215 I bt_bluedroid: init
,09-07 16:10:22.518  4215  4227 I BluetoothAdapterState: Entering OffState
,09-07 16:10:22.524  4215  4228 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 16:10:22.524  4215  4228 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 16:10:22.525  4215  4228 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 16:10:22.525  4215  4228 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 16:10:22.527  4215  4215 I bt_bluedroid: get_profile_interface socket
,09-07 16:10:22.530  4215  4215 I bt_bluedroid: get_profile_interface sdp
,09-07 16:10:22.533  4215  4231 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:10:22.537  4215  4226 I bt_bluedroid: config_hci_snoop_log
,09-07 16:10:22.540  4215  4231 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:10:22.541   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 16:10:22.557  4215  4227 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 16:10:22.557  4215  4227 D BluetoothAdapterProperties: Setting state to 14
09-07 16:10:22.558  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 16:10:22.563  4215  4227 D BluetoothBondStateMachine: make
,09-07 16:10:22.569  4215  4232 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 16:10:22.580  4215  4227 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:10:22.581  4215  4215 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 16:10:22.591  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:22.592  4215  4215 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:10:22.594  4215  4215 D BtGatt.GattService: Received start request. Starting profile...
,09-07 16:10:22.594  4215  4215 D BtGatt.GattService: start()
,09-07 16:10:22.594  4215  4215 I bt_bluedroid: get_profile_interface gatt
09-07 16:10:22.596  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:22.596  4215  4215 D BtGatt.AdvertiseManager: advertise manager created
,09-07 16:10:22.611  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:22.611  4215  4215 V BluetoothAdapterState: isTurningOn()=false
09-07 16:10:22.611  4215  4215 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 16:10:22.612  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:22.612  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 16:10:22.612  4215  4227 I bt_bluedroid: enable
09-07 16:10:22.613  4215  4228 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
09-07 16:10:22.614  4215  4228 I bt_hci  : start_up
,09-07 16:10:22.634  4215  4228 I bt_vendor: alloc value 0xb39e9189
,09-07 16:10:22.634  4215  4228 I bt_vendor: init
09-07 16:10:22.634  4215  4228 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 16:10:22.634  4215  4228 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 16:10:22.742  4215  4228 D bt_hci  : start_up starting async portion
,09-07 16:10:22.742  4215  4235 I bt_hci  : event_finish_startup
,09-07 16:10:22.743  4215  4235 I bt_hci_h4: hal_open
09-07 16:10:22.743  4215  4235 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 16:10:22.756  4215  4235 I bt_userial_vendor: device fd = 51 open
,09-07 16:10:22.785  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:10:22.816  4215  4235 D bt_hwcfg: Chipset BCM4354A2
09-07 16:10:22.817  4215  4235 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 16:10:22.817  4215  4235 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 16:10:23.655  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 16:10:23.657  4215  4235 D bt_hwcfg: Settlement delay -- 100 ms
09-07 16:10:23.657  4215  4235 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 16:10:23.775  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:10:23.776  4215  4235 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 16:10:23.805  4215  4235 I bt_hwcfg: vendor lib fwcfg completed
09-07 16:10:23.805  4215  4235 I bt_vendor: firmware callback
,09-07 16:10:23.805  4215  4235 I bt_hci  : firmware_config_callback
,09-07 16:10:23.819  4215  4237 I bt_btu  : btu_task pending for preload complete event
,09-07 16:10:23.820  4215  4237 I bt_btu_task: Bluetooth chip preload is complete
09-07 16:10:23.820  4215  4237 I bt_btu  : btu_task received preload complete event
,09-07 16:10:23.832  4215  4237 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 16:10:23.832  4215  4237 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 16:10:23.833  4215  4237 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 16:10:23.833  4215  4237 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 16:10:23.833  4215  4237 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 16:10:23.833  4215  4237 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 16:10:23.833  4215  4237 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-07 16:10:23.834  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 16:10:23.834  4215  4237 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 16:10:23.834  4215  4237 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 16:10:23.834  4215  4237 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 16:10:23.835  4215  4237 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 16:10:23.835  4215  4237 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 16:10:23.835  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 16:10:23.835  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 16:10:23.985  4215  4237 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,09-07 16:10:23.986  4215  4237 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,09-07 16:10:23.999  4215  4231 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 16:10:24.001  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 16:10:24.002  4215  4231 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 16:10:24.005  4215  4231 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:10:24.009  4215  4231 D BluetoothAdapterProperties: Scan Mode:20
,09-07 16:10:24.009  4215  4231 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 16:10:24.010  4215  4231 D bt_hci  : do_postload posting postload work item
,09-07 16:10:24.010  4215  4235 I bt_hci  : event_postload
,09-07 16:10:24.010  4215  4235 I bt_vendor: sco_config_cb
,09-07 16:10:24.011  4215  4235 I bt_hci  : sco_config_callback postload finished.
,09-07 16:10:24.013  4215  4231 D bt_bte_conf: Device ID record 1 : primary
09-07 16:10:24.013  4215  4231 D bt_bte_conf:   vendorId            = 000f
09-07 16:10:24.014  4215  4231 D bt_bte_conf:   vendorIdSource      = 0001
09-07 16:10:24.014  4215  4231 D bt_bte_conf:   product             = 1200
,09-07 16:10:24.014  4215  4231 D bt_bte_conf:   version             = 1436
09-07 16:10:24.014  4215  4231 D bt_bte_conf:   clientExecutableURL = 
09-07 16:10:24.015  4215  4231 D bt_bte_conf:   serviceDescription  = 
09-07 16:10:24.015  4215  4231 D bt_bte_conf:   documentationURL    = 
,09-07 16:10:24.015  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:24.016  4215  4231 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 16:10:24.016  4215  4228 D bt_stack_manager: event_start_up_stack finished
09-07 16:10:24.019  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 16:10:24.020  4215  4227 D BluetoothAdapterProperties: Setting state to 15
09-07 16:10:24.020  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:24.020  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 16:10:24.023  4215  4227 I BluetoothAdapterState: Entering BleOnState
09-07 16:10:24.025  4215  4235 I bt_vendor: low_power_mode_cb
09-07 16:10:24.026  4215  4227 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 16:10:24.026  4215  4227 D BluetoothAdapterProperties: Setting state to 11
09-07 16:10:24.027  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 16:10:24.035  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:24.040  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:24.036  4215  4215 D HeadsetService: Received start request. Starting profile...
,09-07 16:10:24.042  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:24.049  4215  4215 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 16:10:24.049  4215  4215 D HeadsetStateMachine: make
,09-07 16:10:24.053  4215  4227 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:10:24.061  4215  4215 D HeadsetStateMachine: max_hf_connections = 1
,09-07 16:10:24.061  4215  4215 I bt_bluedroid: get_profile_interface handsfree
09-07 16:10:24.061  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 16:10:24.062  4215  4231 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-07 16:10:24.066  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:24.066  4215  4215 D A2dpService: Received start request. Starting profile...
,09-07 16:10:24.067  4215  4215 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 16:10:24.067  4215  4215 I bt_bluedroid: get_profile_interface avrcp
,09-07 16:10:24.074  4215  4215 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 16:10:24.074  4215  4215 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-07 16:10:24.075  4215  4215 D A2dpStateMachine: make
09-07 16:10:24.076  4215  4215 I bt_bluedroid: get_profile_interface a2dp
09-07 16:10:24.077  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 16:10:24.079  4215  4246 D A2dpStateMachine: Enter Disconnected: -2
,09-07 16:10:24.080  4215  4215 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 16:10:24.081  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
09-07 16:10:24.081  4215  4215 D HidService: Received start request. Starting profile...
09-07 16:10:24.082  4215  4215 I bt_bluedroid: get_profile_interface hidhost
,09-07 16:10:24.082  4215  4231 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
09-07 16:10:24.082  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 16:10:24.082  4215  4215 D HidService: setHidService(): set to: null
,09-07 16:10:24.085  4215  4215 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 16:10:24.085  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:24.086  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:10:24.086  4215  4215 D HealthService: Received start request. Starting profile...
,09-07 16:10:24.088  4215  4215 I bt_bluedroid: get_profile_interface health
09-07 16:10:24.088  4215  4215 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 16:10:24.089  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:24.090  4215  4215 D PanService: Received start request. Starting profile...
09-07 16:10:24.090  4215  4215 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 16:10:24.090  4215  4215 I bt_bluedroid: get_profile_interface pan
09-07 16:10:24.090  4215  4231 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 16:10:24.093  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:24.094  4215  4215 D BluetoothMapService: Received start request. Starting profile...
09-07 16:10:24.094  4215  4215 D BluetoothMapService: start()
,09-07 16:10:24.096  4215  4215 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 16:10:24.097  4215  4215 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 16:10:24.097  4215  4215 D BluetoothMapAppObserver: createReceiver()
09-07 16:10:24.098  4215  4215 D BluetoothMapAppObserver: initObservers()
09-07 16:10:24.098  4215  4215 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 16:10:24.105  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:24.105  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.105  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:24.105  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:24.107  4215  4244 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 16:10:24.107  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:24.107  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:24.108  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:10:24.110  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:24.110  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:10:24.111  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:10:24.112  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 16:10:24.112  4215  4227 D BluetoothAdapterProperties: ScanMode =  20
09-07 16:10:24.112  4215  4227 D BluetoothAdapterProperties: State =  11
,09-07 16:10:24.112  4215  4227 D BluetoothAdapterProperties: Setting state to 12
,09-07 16:10:24.112  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 16:10:24.113  4215  4227 I BluetoothAdapterState: Entering OnState
09-07 16:10:24.113  1349  1367 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:10:24.115  4215  4231 D BluetoothAdapterProperties: Scan Mode:21
09-07 16:10:24.115  4215  4231 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 16:10:24.118  3908  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:24.120  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:24.122  1349  1968 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:10:24.123  4215  4215 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 16:10:24.123  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:24.123  4215  4215 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 16:10:24.124  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:10:24.124  1349  1349 D BluetoothInputDevice: Proxy object connected
09-07 16:10:24.124  1349  1349 D HidProfile: Bluetooth service connected
09-07 16:10:24.126  1349  1367 D BluetoothMap: onBluetoothStateChange: up=true
09-07 16:10:24.126  4215  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:24.126  3908  3908 D BluetoothInputDevice: Proxy object connected
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:24.126  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:10:24.127  3908  3908 D HidProfile: Bluetooth service connected
09-07 16:10:24.128  4215  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:24.128  1349  2026 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:24.129  3908  3920 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:24.129  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:10:24.129  1349  1968 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:10:24.129  4215  4215 D ObexServerSockets: Succeed to create listening sockets 
09-07 16:10:24.129  4215  4215 D ObexServerSockets0: startAccept()
09-07 16:10:24.129  4215  4215 D ObexServerSockets0: prepareForNewConnect()
09-07 16:10:24.131  3908  3918 D BluetoothMap: onBluetoothStateChange: up=true
09-07 16:10:24.131  4215  4215 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 16:10:24.131  4215  4215 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 16:10:24.132   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:24.132   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 16:10:24.132  4215  4253 D ObexServerSockets0: Accepting socket connection...
09-07 16:10:24.132  1349  1349 D BluetoothA2dp: Proxy object connected
09-07 16:10:24.133  4215  4252 D ObexServerSockets0: Accepting socket connection...
09-07 16:10:24.133   873   873 D BluetoothA2dp: Proxy object connected
09-07 16:10:24.133   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:10:24.134  1916  2281 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:10:24.134  1349  1349 D BluetoothMap: Proxy object connected
09-07 16:10:24.134  1349  1349 D MapProfile: Bluetooth service connected
09-07 16:10:24.134  1349  1349 D BluetoothMap: getConnectedDevices()
09-07 16:10:24.134  3908  3918 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:10:24.135  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 16:10:24.136  1349  1349 D PanProfile: Bluetooth service connected
09-07 16:10:24.137   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:10:24.137  3908  3920 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 16:10:24.139  3908  3918 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:10:24.137  3908  3908 D BluetoothMap: Proxy object connected
,09-07 16:10:24.141   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 16:10:24.142  4215  4215 D BluetoothMapService: onReceive
09-07 16:10:24.142  4215  4215 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 16:10:24.142  4215  4215 D BluetoothMapService: STATE_ON
09-07 16:10:24.142  3908  3908 D MapProfile: Bluetooth service connected
09-07 16:10:24.143  3908  3908 D BluetoothMap: getConnectedDevices()
09-07 16:10:24.144  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:24.145  3908  3908 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 16:10:24.145  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:24.145  3908  3908 D PanProfile: Bluetooth service connected
09-07 16:10:24.147  3908  3908 D BluetoothA2dp: Proxy object connected
,09-07 16:10:24.152  3908  3908 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:10:24.158  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:10:24.159  3908  3908 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:10:24.163  4215  4215 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 16:10:24.163  3908  3908 D BluetoothPbap: Proxy object connected
09-07 16:10:24.163  4215  4215 D ObexServerSockets0: prepareForNewConnect()
09-07 16:10:24.163  3908  3908 D PbapServerProfile: Bluetooth service connected
,09-07 16:10:24.166  1349  1349 D BluetoothPbap: Proxy object connected
09-07 16:10:24.166  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-07 16:10:24.167  4215  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:24.192  4215  4264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:10:24.193  4215  4264 I BtOppRfcommListener: Accept thread started.
,09-07 16:10:24.232   873   890 D BluetoothHeadset: Proxy object connected
,09-07 16:10:24.232  3908  3918 D BluetoothHeadset: Proxy object connected
09-07 16:10:24.232   873   873 D BluetoothHeadset: Proxy object connected
09-07 16:10:24.232  3908  3908 D HeadsetProfile: Bluetooth service connected
09-07 16:10:24.233  1916  1939 D BluetoothHeadset: Proxy object connected
,09-07 16:10:24.233  1349  1968 D BluetoothHeadset: Proxy object connected
,09-07 16:10:24.233  1349  1349 D HeadsetProfile: Bluetooth service connected
09-07 16:10:24.233   873   890 D BluetoothHeadset: Proxy object connected
,09-07 16:10:24.233   873   873 D BluetoothHeadset: Proxy object connected
09-07 16:10:24.234   873   873 D BluetoothHeadset: Proxy object connected
09-07 16:10:24.235  1916  2113 D BluetoothHeadset: Proxy object connected
,09-07 16:10:24.236   873   890 D BluetoothHeadset: Proxy object connected
,09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:27.335  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:10:27.343  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:27.343  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:27.344  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67e8710 removed from the list
,09-07 16:10:27.344  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:27.344  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:27.345  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:10:27.347  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:27.348  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7669209 added. We now have 4 listener(s)
09-07 16:10:27.348  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:10:27.352   873  2976 D WifiService: setWifiEnabled: false pid=3807, uid=10000
,09-07 16:10:27.352   873  2976 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:10:32.366  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:32.368   873  2002 D WifiService: setWifiEnabled: true pid=3807, uid=10000
09-07 16:10:32.368   873  2002 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:10:32.387   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:32.407  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:10:32.409  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:10:32.415  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:10:32.418  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:10:32.424   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 16:10:32.425   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 16:10:32.426   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 16:10:32.427   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 16:10:32.427   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 16:10:32.427   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 16:10:32.427   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 16:10:32.443   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 16:10:32.445   372   871 D CommandListener: Setting iface cfg
,09-07 16:10:32.445   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:10:32.445   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-07 16:10:32.445   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 16:10:32.501   873  1303 E native  : do suspend true
,09-07 16:10:32.506   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 16:10:32.521   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 16:10:32.538   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:10:33.809   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:10:33.958   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=8.12 delta 1000 -> 994
,09-07 16:10:33.961   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 16:10:33.961   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:10:33.979   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 16:10:34.053   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 16:10:34.059  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 16:10:34.497  1864  1967 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-07 16:10:34.498  1864  1967 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 16:10:34.506  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 16:10:34.534  1526  1526 I ConfigService: onCreate
,09-07 16:10:34.555  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 16:10:34.556  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 16:10:34.560   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:10:34.575   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 16:10:34.575   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:10:34.575   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 16:10:34.608   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:10:34.620   372   871 D CommandListener: Setting iface cfg
09-07 16:10:34.620   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 16:10:34.629   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 16:10:34.645   873  4275 D DhcpClient: Receive thread started
,09-07 16:10:34.738   873  1303 E native  : do suspend false
,09-07 16:10:34.762   873  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 16:10:34.777   873  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-07 16:10:34.779   873  1880 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-07 16:10:34.782   873  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 16:10:34.798   873  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-07 16:10:34.800   873  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 16:10:34.804   372   871 D CommandListener: Setting iface cfg
,09-07 16:10:34.809   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 16:10:34.813   873  1303 E native  : do suspend true
,09-07 16:10:34.814   873  1880 D DhcpClient: Scheduling renewal in 86399s
,09-07 16:10:34.828   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-07 16:10:34.828   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 16:10:34.829   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 16:10:34.830   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 16:10:34.834   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 16:10:34.893   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 16:10:34.893   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 16:10:34.894   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 16:10:34.896   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 16:10:34.898   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 16:10:34.911   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 16:10:34.920   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 16:10:34.920   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 16:10:34.920   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 16:10:34.920   873  1305 D ConnectivityService:    accepting network in place of null
09-07 16:10:34.920   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 16:10:34.922   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:10:34.923   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 16:10:34.931   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:10:34.960   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:10:35.012   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:10:35.022   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 16:10:35.023   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:10:35.033   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:10:35.036   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:35.048  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:35.050  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:35.057   873  4273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:35.058  3807  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:35.063  3807  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:35.069  1746  1746 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:10:35.074  1746  1746 D SystemUpdateService: onCreate
,09-07 16:10:35.079  1746  1746 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 16:10:35.100  1746  4284 I SystemUpdateService: active receiver: enabled
,09-07 16:10:35.106  1746  1746 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 16:10:35.109  1746  2433 I iu.UploadsManager: num queued entries: 0
,09-07 16:10:35.118  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 16:10:35.120  1746  1746 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:10:35.122  3988  3988 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:10:35.124   873  4273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 14:10:35 GMT], X-Android-Received-Millis=[1473257435124], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473257435099]}
,09-07 16:10:35.125   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 16:10:35.126   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-07 16:10:35.126   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 16:10:35.129  1746  4286 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 16:10:35.129  1746  4286 W BaseAppContext: Using Auth Proxy for data requests.
09-07 16:10:35.129   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 16:10:35.132  3988  3988 D SprintDMHelper: simOperator: 
09-07 16:10:35.132  3988  3988 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:10:35.135  1746  4286 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:10:35.146  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:10:35.119  1746  4284 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:10:35.109  1746  2433 I iu.UploadsManager: num updated entries: 0
,09-07 16:10:35.163  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:10:35.175  1746  2433 I iu.SyncManager: NEXT; no task
,09-07 16:10:35.177  1746  4284 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 16:10:35.177  1746  4284 I SystemUpdateService: now status is 0 (complete)
09-07 16:10:35.177  1746  4284 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 16:10:35.177  1746  4284 I SystemUpdateService: file has been verified
09-07 16:10:35.177  1746  4284 I SystemUpdateService: OTA package size = 12249756
,09-07 16:10:35.207  1746  4284 I SystemUpdateService: showing system update notification
,09-07 16:10:35.266  1746  1746 D SystemUpdateService: onDestroy
,09-07 16:10:35.284  1526  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 16:10:35.284  1526  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 16:10:35.284  1526  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:10:35.284  1526  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:10:35.312  1746  4286 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-07 16:10:35.315  3959  4290 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 16:10:36.022   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:37.399  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:37.406  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:37.407  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:37.408  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7669209 removed from the list
,09-07 16:10:37.408  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:10:37.408  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:37.409  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:37.420  3807  4296 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-07 16:10:37.421  3807  4296 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 16:10:39.604  1526  1526 I ConfigService: onDestroy
,09-07 16:10:40.428  3807  4298 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-07 16:10:40.428  3807  4296 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-07 16:10:40.429  3807  4298 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 16:10:40.430  3807  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:10:40.430  3807  4296 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 16:10:40.431  3807  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:10:40.431  3807  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:10:40.435  3807  4300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
09-07 16:10:40.435  3807  4298 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 16:10:40.439  3807  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:10:40.441  3807  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
09-07 16:10:40.443  3807  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
,09-07 16:10:40.444  3807  4296 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 16:10:40.445  3807  4301 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
,09-07 16:10:40.445  3807  4301 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-07 16:10:40.446  3807  4301 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-07 16:10:40.446  3807  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Receiver)
09-07 16:10:40.448  3807  4303 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: OutgoingSocketThread/Receiver)
09-07 16:10:40.449  3807  4303 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 16:10:40.449  3807  4303 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 16:10:42.927   873  1305 D ConnectivityService: handlePromptUnvalidated 102
,09-07 16:10:43.428  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 16:10:43.430  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 16:10:43.438  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@868d972 Bundle[{}]
,09-07 16:10:43.439  3807  3858 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 16:10:43.439  3807  3858 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-07 16:10:43.439  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 16:10:43.440  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 16:10:43.440  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 16:10:43.441  3807  3858 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 16:10:43.445  3807  3858 I System.out: Running OutgoingSocketThread
,09-07 16:10:43.448  3807  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 16:10:43.449  3807  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 16:10:46.458  3807  4305 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 16:10:46.458  3807  4305 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 16:10:46.458  3807  4304 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-07 16:10:46.458  3807  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:10:46.459  3807  4304 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 16:10:46.460  3807  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:10:46.461  3807  4305 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:10:46.462  3807  4304 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:10:46.465  3807  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
,09-07 16:10:46.467  3807  4304 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 16:10:46.467  3807  4305 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 16:10:46.471  3807  4308 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
,09-07 16:10:46.474  3807  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
,09-07 16:10:46.477  3807  4310 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
,09-07 16:10:46.478  3807  4310 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 16:10:46.478  3807  4310 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 16:10:46.480  3807  4309 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,09-07 16:10:46.482  3807  4309 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
,09-07 16:10:46.483  3807  4309 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 16:10:46.483  3807  4309 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 16:10:49.460  3807  3858 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,09-07 16:10:49.463  3807  3858 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 16:10:49.463  3807  3858 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-07 16:10:49.469  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 16:10:49.469  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3211c0e added. We now have 3 listener(s)
,09-07 16:10:49.471  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:10:49.471  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:10:49.471  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:10:49.471  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:49.471  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c79662f added. We now have 4 listener(s)
,09-07 16:10:49.472  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:10:49.472  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 16:10:49.476  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:49.488  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:49.494  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:49.495  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:10:49.496  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:10:49.497  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:10:49.497  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:10:49.497  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:10:49.497  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:49.498  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:10:49.498  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:10:49.498  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3211c0e removed from the list
09-07 16:10:49.498  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:49.499  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c79662f removed from the list
,09-07 16:10:49.502  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:49.511  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:49.511  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:49.511  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:49.513  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:49.513  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:49.515  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:10:49.515  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:49.515  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:10:49.515  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c79662f not in the list
09-07 16:10:49.516  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:49.516  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:49.516  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:49.517  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:10:49.517  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:49.517  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c79662f not in the list
09-07 16:10:49.517  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:10:49.517  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:49.517  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:10:49.517  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3211c0e not in the list
09-07 16:10:49.518  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:10:49.518  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd45c5 added. We now have 3 listener(s)
09-07 16:10:49.520  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:10:49.520  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 16:10:49.520  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:10:49.520  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:49.520  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d6eb1a added. We now have 4 listener(s)
09-07 16:10:49.520  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:10:49.521  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 16:10:49.525  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:49.534  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:49.538  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:49.538  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:10:49.540  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:10:49.540  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 16:10:49.540  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:10:49.541  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:49.541  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:10:49.541  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:10:49.547  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:49.552  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 16:10:49.552  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 16:10:49.562  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:10:49.564  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:10:49.564  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:10:49.576  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 16:10:49.577  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 16:10:49.577  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 16:10:49.579  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:10:49.589  4215  4256 D BtGatt.GattService: registerClient() - UUID=13c6fdd6-9dcd-49df-909d-2df195fa30cf
,09-07 16:10:49.591  4215  4231 D BtGatt.GattService: onClientRegistered() - UUID=13c6fdd6-9dcd-49df-909d-2df195fa30cf, clientIf=5
,09-07 16:10:49.593  3807  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:10:49.597  4215  4251 D BtGatt.GattService: start scan with filters
,09-07 16:10:49.610  4215  4234 D BtGatt.ScanManager: handling starting scan
09-07 16:10:49.610  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 16:10:49.610  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:10:49.611  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 16:10:49.611  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 16:10:49.616  4215  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6bc54e6
,09-07 16:10:49.620  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:10:49.621  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:10:49.621  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:10:49.626  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:10:49.632  3807  3858 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 16:10:49.632  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 16:10:49.632  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 16:10:49.632  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:49.632  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-07 16:10:49.632  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:10:49.632  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:10:49.632  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:10:49.633  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:10:49.633  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:10:49.633  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:10:49.633  4215  4231 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 16:10:49.633  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:10:49.634  3807  3858 D BluetoothAdapter: STATE_ON
09-07 16:10:49.635  4215  4256 D BtGatt.GattService: stopScan() - queue size =1
09-07 16:10:49.635  4215  4234 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:10:49.635  4215  4251 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 16:10:49.636  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 16:10:49.636  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 16:10:49.636  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 16:10:49.636  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:10:49.636  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 16:10:49.637  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:10:49.637  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 16:10:49.637  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 16:10:49.637  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:10:49.638  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:10:49.640  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:10:49.640  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:10:49.640  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:10:49.647  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:10:49.648  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:10:49.649  4215  4234 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:10:49.649  4215  4234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:10:49.664  4215  4231 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 16:10:49.664  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:10:49.671  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 16:10:49.671  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:10:49.682  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 16:10:49.682  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:10:49.682  4215  4234 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:10:49.691  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 16:10:49.692  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:10:49.692  4215  4234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:10:49.699  4215  4231 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 16:10:49.699  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:10:50.142  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-07 16:10:50.142  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:10:50.142  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:10:52.641  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:10:52.642  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:10:52.642  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:10:52.643  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:10:52.643  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:52.644  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:10:52.644  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:10:52.645  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd45c5 removed from the list
,09-07 16:10:52.645  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:10:52.645  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d6eb1a removed from the list
,09-07 16:10:52.645  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:52.646  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:10:52.647  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:52.648  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:52.651  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:10:52.651  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:52.651  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:52.652  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d6eb1a not in the list
09-07 16:10:52.652  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:52.653  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:52.656  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:52.656  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:10:52.657  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:10:52.657  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d6eb1a not in the list
09-07 16:10:52.657  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:10:52.657  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:52.658  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:52.658  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd45c5 not in the list
09-07 16:10:52.661  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:10:52.661  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ec27 added. We now have 3 listener(s)
,09-07 16:10:52.667  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 16:10:52.668  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:10:52.668  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 16:10:52.669  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:52.669  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9679ed4 added. We now have 4 listener(s)
,09-07 16:10:52.669  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:10:52.670  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:10:52.678  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:10:52.688  3807  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:10:52.691  3807  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:10:52.692  3807  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:10:52.692  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 16:10:52.694  3807  3858 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-07 16:10:52.694  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-07 16:10:52.695  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 16:10:52.695  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 16:10:52.695  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 16:10:52.695  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:10:52.697  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 16:10:52.697  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 16:10:52.697  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 16:10:52.698  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 16:10:52.698  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 16:10:52.698  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:10:52.698  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 16:10:52.699  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:10:52.704  3807  3858 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:10:52.705  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 16:10:52.705  3807  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:10:52.704  3807  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:10:52.705  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 16:10:52.710  3807  4311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 16:10:52.713  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 16:10:52.714  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:10:52.714  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:10:52.717  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 16:10:52.717  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 16:10:52.718  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-07 16:10:52.719  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 16:10:52.719  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 16:10:52.719  3807  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 16:10:52.720  3807  3858 D BluetoothAdapter: STATE_ON
,09-07 16:10:52.724  4215  4225 D BtGatt.GattService: registerClient() - UUID=89c002a7-0519-4e09-808e-523e112a0f4a
,09-07 16:10:52.725  4215  4231 D BtGatt.GattService: onClientRegistered() - UUID=89c002a7-0519-4e09-808e-523e112a0f4a, clientIf=5
,09-07 16:10:52.726  3807  3818 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 16:10:52.728  4215  4233 D BtGatt.AdvertiseManager: message : 0
,09-07 16:10:52.731  4215  4233 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 16:10:52.746  4215  4231 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 16:10:52.759  4215  4231 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 16:10:52.761  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 16:10:52.762  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:10:52.765  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:10:52.767  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 16:10:52.767  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 16:10:52.768  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 16:10:52.768  3807  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 16:10:52.768  3807  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 16:10:52.768  3807  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 16:10:52.771  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-07 16:10:52.775  3807  3807 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 16:10:52.775  3807  3807 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 16:10:52.833   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228393, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:10:53.276  3807  3807 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 16:10:53.277  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 16:10:53.277  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:10:55.773  3807  3858 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:10:55.773  3807  3858 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 16:10:55.774  3807  3858 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:10:55.774  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 16:10:55.774  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 16:10:55.774  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 16:10:55.775  3807  4311 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 16:10:55.775  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:10:55.775  3807  4311 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 16:10:55.776  3807  3858 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 16:10:55.776  3807  4311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 16:10:55.776  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:10:55.777  3807  3807 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 16:10:55.777  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 16:10:55.777  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:10:55.777  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:10:55.778  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:10:55.780  3807  3858 D BluetoothAdapter: STATE_ON
09-07 16:10:55.780  3807  3858 D BluetoothLeScanner: could not find callback wrapper
09-07 16:10:55.781  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 16:10:55.781  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 16:10:55.783  4215  4233 D BtGatt.AdvertiseManager: message : 1
09-07 16:10:55.785  4215  4233 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 16:10:55.794  4215  4231 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 16:10:55.795  4215  4231 D BtGatt.GattService: Client app is not null!
,09-07 16:10:55.797  4215  4255 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:10:55.798  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 16:10:55.798  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 16:10:55.798  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 16:10:55.799  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 16:10:55.799  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 16:10:55.801  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:10:55.801  3807  3858 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 16:10:55.802  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:10:55.803  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:10:55.806  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:10:55.806  3807  3807 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:10:55.806  3807  3807 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 16:10:55.806  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:10:55.807  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:10:55.807  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 16:10:55.807  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ec27 removed from the list
09-07 16:10:55.807  3807  3807 D AndroidRuntime: Shutting down VM
09-07 16:10:55.807  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:10:55.808  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9679ed4 removed from the list
,09-07 16:10:55.808  3807  3858 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:10:55.808  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,--------- beginning of crash
09-07 16:10:55.809  3807  3807 E AndroidRuntime: FATAL EXCEPTION: main
09-07 16:10:55.809  3807  3807 E AndroidRuntime: Process: com.test.thalitest, PID: 3807
09-07 16:10:55.809  3807  3807 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:10:55.809  3807  3807 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:10:55.810  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:55.810  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:10:55.814  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:10:55.815  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:55.815  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:55.815  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9679ed4 not in the list
09-07 16:10:55.815  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:55.816  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:55.817   873  1369 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
09-07 16:10:55.818  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:10:55.819  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:10:55.819  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:10:55.820  3807  3858 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9679ed4 not in the list
09-07 16:10:55.820  3807  3858 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:10:55.820  3807  3858 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:10:55.821  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:10:55.821  3807  3858 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ec27 not in the list
09-07 16:10:55.823  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:10:55.823  3807  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5b0f79 added. We now have 3 listener(s)
,09-07 16:10:55.830  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 16:10:55.830  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:10:55.830  3807  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:10:55.830  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:10:55.830  3807  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@912a4be added. We now have 4 listener(s)
,09-07 16:10:55.830  3807  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:10:55.831  3807  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:10:55.834   873  1369 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 16:10:55.897  3807  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:10:55.905  3807  3807 I Process : Sending signal. PID: 3807 SIG: 9
,09-07 16:10:55.905   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{d43916c u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{7abb9be 3807 com.test.thalitest/10000/u0 remote:5075879}: process crashing
09-07 16:10:55.906   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{19c0335 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{7abb9be 3807 com.test.thalitest/10000/u0 remote:5075879}: process crashing
,09-07 16:10:56.002   873  1636 I WindowState: WIN DEATH: Window{455f441 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 16:10:56.003   873   884 D GraphicsStats: Buffer count: 2
09-07 16:10:56.005   873  1304 D WifiService: Client connection lost with reason: 4
,09-07 16:10:56.037   873  1944 I ActivityManager: Process com.test.thalitest (pid 3807) has died
,09-07 16:10:56.090   873  2976 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3807 uid 10000
,09-07 16:10:56.093  1864  1864 I Keyboard.Facilitator: onFinishInput()
,09-07 16:11:11.744  3039  4315 V KeepSync: Connecting to GoogleApiClient
,09-07 16:11:11.744   873  1369 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:11:11.815  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:11.816  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:11.841  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-07 16:11:11.841  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 16:11:11.841  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:11:11.841  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:11.869  1746  4316 V BaseAuthAsyncOperation: access token request failed
,09-07 16:11:11.871  3039  4315 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:11:11.931  1526  3206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-07 16:11:11.931  1526  3206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 16:11:11.931  1526  3206 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:11:11.931  1526  3206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:11.952  3039  4315 E KeepSync: IOException
09-07 16:11:11.952  3039  4315 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:11:11.952  3039  4315 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:11:11.952  3039  4315 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:11:11.952  3039  4315 E KeepSync: 	... 10 more
,09-07 16:11:11.952  3039  4315 W KeepSync: Sync result 2
,09-07 16:11:11.967   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 247125, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:11:32.397   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:11:40.883  1526  2186 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 16:11:44.443  3617  4318 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:11:44.493  3617  4319 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:11:44.533  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:44.539  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:44.610  1526  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:11:44.611  1526  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:11:44.611  1526  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:11:44.611  1526  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:44.669  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:44.672  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:44.716  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:11:44.716  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:11:44.716  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:11:44.716  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:44.742  3617  4319 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:11:44.745  3617  4318 E BooksSync: Soft error
09-07 16:11:44.745  3617  4318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:11:44.745  3617  4318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:11:44.746  3617  4318 E BooksSync: Sync error
09-07 16:11:44.746  3617  4318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:11:44.746  3617  4318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:11:44.746  3617  4318 I BooksSync: Finished books sync
,09-07 16:11:44.758   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279956, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:11:44.965  3039  4320 V KeepSync: Connecting to GoogleApiClient
,09-07 16:11:44.965   873  1944 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:11:45.034  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:45.037  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:11:45.085  1526  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:11:45.086  1526  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 16:11:45.086  1526  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:11:45.086  1526  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:45.121  1746  4321 V BaseAuthAsyncOperation: access token request failed
09-07 16:11:45.123  3039  4320 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:11:45.210  1526  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 16:11:45.211  1526  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 16:11:45.211  1526  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:11:45.211  1526  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:11:45.259  3039  4320 E KeepSync: IOException
09-07 16:11:45.259  3039  4320 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:11:45.259  3039  4320 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:11:45.259  3039  4320 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:11:45.259  3039  4320 E KeepSync: 	... 10 more
,09-07 16:11:45.267  3039  4320 W KeepSync: Sync result 2
,09-07 16:11:45.294   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 280202, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:11:49.290   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:11:56.133  1864  1967 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 16:11:56.134  1864  1967 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 16:11:56.173  1526  1526 I ConfigService: onCreate
,09-07 16:12:01.247  1526  1526 I ConfigService: onDestroy
,09-07 16:12:15.529  3617  4332 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:12:15.641  3617  4333 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:12:15.652  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:12:15.653  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:12:15.689  1526  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:12:15.689  1526  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 16:12:15.689  1526  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:12:15.690  1526  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:15.701  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:12:15.701  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 16:12:15.702  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:12:15.702  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:15.732  3555  4331 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:12:15.732  3555  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:15.732  3555  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	... 12 more
09-07 16:12:15.732  3555  4331 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at fal.a(PG:38)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:12:15.732  3555  4331 E HttpOperation: 	... 14 more
,09-07 16:12:15.814  1526  2328 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:12:15.814  1526  2328 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 16:12:15.814  1526  2328 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:12:15.814  1526  2328 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:15.815  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 16:12:15.815  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:12:15.815  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:12:15.815  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:15.840  3617  4333 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:12:15.841  3617  4332 E BooksSync: Soft error
09-07 16:12:15.841  3617  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:12:15.841  3617  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:12:15.841  3617  4332 E BooksSync: Sync error
09-07 16:12:15.841  3617  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:12:15.841  3617  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:12:15.841  3617  4332 I BooksSync: Finished books sync
,09-07 16:12:15.863   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 310754, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-07 16:12:15.865  3555  4331 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:12:15.865  3555  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at hec.a(PG:42)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at hee.a(PG:102)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at czr.a(PG:65)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at kka.a(PG:108)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:15.865  3555  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	... 15 more
09-07 16:12:15.865  3555  4331 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:12:15.865  3555  4331 E HttpOperation: 	at fal.a(PG:38)
09-07 16:1,2:15.865  3555  4331 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:12:15.865  3555  4331 E HttpOperation: 	... 17 more
,09-07 16:12:15.866  3555  4331 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:12:15.866  3555  4331 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	... 15 more
09-07 16:12:15.866  3555  4331 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:12:15.866  3555  4331 E ExperimentLoader: 	... 17 more
,09-07 16:12:16.012   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 285672, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:12:28.411   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:12:45.293   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340853, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:12:46.874  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:12:46.890  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:12:46.897  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:12:46.960  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:12:46.960  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 16:12:46.960  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:12:46.961  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:46.972  1526  4334 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 16:12:46.972  1526  4334 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 16:12:46.973  1526  4334 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:12:46.973  1526  4334 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:46.999  3555  4339 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:12:46.999  3555  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:46.999  3555  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	... 12 more
09-07 16:12:46.999  3555  4339 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at fal.a(PG:38)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:12:46.999  3555  4339 E HttpOperation: 	... 14 more
,09-07 16:12:47.007  1526  4334 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 16:12:47.007  1526  4334 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 16:12:47.023  3518  3547 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 16:12:47.023  3518  3547 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 16:12:47.023  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 16:12:47.023  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 16:12:47.023  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 16:12:47.023  3518  3547 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 16:12:47.023  3518  3547 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 16:12:47.097  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:12:47.097  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:12:47.097  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:12:47.097  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:12:47.113  3555  4339 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:12:47.113  3555  4339 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at hec.a(PG:42)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at hee.a(PG:102)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at czr.a(PG:65)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at kka.a(PG:108)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:47.113  3555  4339 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	... 15 more
09-07 16:12:47.113  3555  4339 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at fal.a(PG:38)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:12:47.113  3555  4339 E HttpOperation: 	... 17 more
,09-07 16:12:47.114  3555  4339 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:12:47.114  3555  4339 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	... 15 more
09-07 16:12:47.114  3555  4339 E ExperimentLoader: Caused by: faj: BadAuthentication,
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:12:47.114  3555  4339 E ExperimentLoader: 	... 17 more
,09-07 16:12:47.289   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 342252, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:12:52.170   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:13:04.279   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=359839, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:13:17.581  3617  4347 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:13:17.633  3617  4348 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:13:17.653  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:17.656  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:17.660  3039  4346 V KeepSync: Connecting to GoogleApiClient
,09-07 16:13:17.661   873   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:13:17.726  1526  2328 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:13:17.726  1526  2328 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:13:17.726  1526  2328 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:17.726  1526  2328 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:17.822  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:17.827  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:17.879  1526  4334 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:13:17.879  1526  4334 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:13:17.879  1526  4334 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:17.879  1526  4334 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:17.887  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:13:17.887  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 16:13:17.887  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:17.887  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:17.916  3617  4348 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:13:17.918  3617  4347 E BooksSync: Soft error
09-07 16:13:17.918  3617  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:13:17.918  3617  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:13:17.918  3617  4347 E BooksSync: Sync error
09-07 16:13:17.918  3617  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:13:17.918  3617  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:13:17.918  3617  4347 I BooksSync: Finished books sync
,09-07 16:13:17.921  1746  4349 V BaseAuthAsyncOperation: access token request failed
09-07 16:13:17.922  3039  4346 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:13:17.942   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 372294, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:13:17.992  1526  2328 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-07 16:13:17.992  1526  2328 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 16:13:17.992  1526  2328 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:17.992  1526  2328 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:18.008  3039  4346 E KeepSync: IOException
09-07 16:13:18.008  3039  4346 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:13:18.008  3039  4346 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:13:18.008  3039  4346 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:13:18.008  3039  4346 E KeepSync: 	... 10 more
,09-07 16:13:18.008  3039  4346 W KeepSync: Sync result 2
,09-07 16:13:18.020   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 346203, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:13:45.287  1526  2186 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 16:13:48.990  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:48.994  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:13:49.033  1526  3206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 16:13:49.033  1526  3206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:13:49.033  1526  3206 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:49.033  1526  3206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:49.054  3555  4352 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:13:49.054  3555  4352 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:13:49.054  3555  4352 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	... 12 more
09-07 16:13:49.054  3555  4352 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at fal.a(PG:38)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:13:49.054  3555  4352 E HttpOperation: 	... 14 more
,09-07 16:13:49.094  1526  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:13:49.094  1526  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:13:49.094  1526  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:13:49.095  1526  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:13:49.112  3555  4352 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:13:49.112  3555  4352 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at hec.a(PG:42)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at hee.a(PG:102)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at czr.a(PG:65)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at kka.a(PG:108)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:13:49.112  3555  4352 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	... 15 more
09-07 16:13:49.112  3555  4352 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at fal.a(PG:38)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:13:49.112  3555  4352 E HttpOperation: 	... 17 more
,09-07 16:13:49.113  3555  4352 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:13:49.113  3555  4352 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	... 15 more
09-07 16:13:49.113  3555  4352 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:13:49.113  3555  4352 E ExperimentLoader: 	... 17 more
,09-07 16:13:49.274   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 404208, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:13:54.837   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:14:11.747   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=427307, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:14:40.506   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=456066, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:14:57.345   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=472905, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:15:19.743  3617  4359 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:15:19.789  3617  4360 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:15:19.802  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:19.806  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:19.843  1526  1544 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:15:19.843  1526  1544 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:15:19.843  1526  1544 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:15:19.843  1526  1544 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:15:19.885  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:19.888  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:19.932  1526  3206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:15:19.932  1526  3206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:15:19.932  1526  3206 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:15:19.933  1526  3206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:15:19.959  3617  4360 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:15:19.960  3617  4359 E BooksSync: Soft error
09-07 16:15:19.960  3617  4359 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:15:19.960  3617  4359 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:15:19.960  3617  4359 E BooksSync: Sync error
09-07 16:15:19.960  3617  4359 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:15:19.960  3617  4359 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:15:19.961  3617  4359 I BooksSync: Finished books sync
,09-07 16:15:19.973   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 495243, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:15:40.130   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=515690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:15:50.196  3039  4362 V KeepSync: Connecting to GoogleApiClient
,09-07 16:15:50.197   873  2976 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:15:50.266  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:50.271  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:15:50.315  1526  2110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:15:50.316  1526  2110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 16:15:50.316  1526  2110 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:15:50.316  1526  2110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:15:50.338  1746  4363 V BaseAuthAsyncOperation: access token request failed
,09-07 16:15:50.339  3039  4362 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:15:50.407  1526  2371 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 16:15:50.407  1526  2371 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 16:15:50.407  1526  2371 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:15:50.407  1526  2371 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:15:50.431  3039  4362 E KeepSync: IOException
09-07 16:15:50.431  3039  4362 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:15:50.431  3039  4362 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:15:50.431  3039  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:15:50.431  3039  4362 E KeepSync: 	... 10 more
,09-07 16:15:50.431  3039  4362 W KeepSync: Sync result 2
,09-07 16:15:50.450   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 504277, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:15:57.077   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=532637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:16:10.092   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=545652, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:16:20.870  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:16:20.872  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:16:20.927  1526  4334 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 16:16:20.927  1526  4334 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:16:20.928  1526  4334 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:16:20.928  1526  4334 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:16:20.948  3555  4366 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:16:20.948  3555  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:16:20.948  3555  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	... 12 more
09-07 16:16:20.948  3555  4366 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at fal.a(PG:38)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:16:20.948  3555  4366 E HttpOperation: 	... 14 more
,09-07 16:16:21.080  1526  3206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 16:16:21.080  1526  3206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:16:21.080  1526  3206 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:16:21.080  1526  3206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:16:21.103  3555  4366 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:16:21.103  3555  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at hec.a(PG:42)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at hee.a(PG:102)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at czr.a(PG:65)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at kka.a(PG:108)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:16:21.103  3555  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	... 15 more
09-07 16:16:21.103  3555  4366 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at fal.a(PG:38)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:16:21.103  3555  4366 E HttpOperation: 	... 17 more
09-07 16:16:21.104  3555  4366 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:16:21.104  3555  4366 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	... 15 more
09-07 16:16:21.104  3555  4366 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:16:21.104  3555  4366 E ExperimentLoader: 	... 17 more
,09-07 16:16:21.276   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 527551, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:16:26.997   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=562557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:16:40.065   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=575625, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:16:56.918   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=592478, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:17:52.464   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=648024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:18:09.344   873  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=664904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:27:22.988   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-07 16:32:35.225  4415  4415 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 16:32:35.229  4415  4415 D AndroidRuntime: CheckJNI is OFF
09-07 16:32:35.265  4415  4415 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 16:32:35.304  4415  4415 I Radio-JNI: register_android_hardware_Radio DONE
09-07 16:32:35.325  4415  4415 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 16:32:35.336   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-07 16:32:35.472   873   896 W PackageSettings: Skipping PackageSetting{6f5d0db com.example.hello/10273} due to missing metadata
09-07 16:32:35.517   873   896 I art     : Starting a blocking GC Explicit
09-07 16:32:35.600   873   896 I art     : Explicit concurrent mark sweep GC freed 38117(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 764us total 81.842ms
09-07 16:32:35.643   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-07 16:32:35.646  4415  4415 I art     : System.exit called, status: 0
09-07 16:32:35.646  4415  4415 I AndroidRuntime: VM exiting with result code 0.
09-07 16:32:35.650   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 16:32:35.677  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 16:32:35.677  4215  4215 D BluetoothMapAppObserver: onReceive
09-07 16:32:35.677  4215  4215 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-07 16:32:35.683   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 16:32:35.684  2206  2317 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 16:32:35.688  3676  3676 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 16:32:35.694  1864  4429 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 16:32:35.698  1864  4429 I Decoder : createOrResetDecoder
09-07 16:32:35.728   873  3132 I ActivityManager: Start proc 4432:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-07 16:32:35.733  1916  1916 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 16:32:35.747  1526  1526 I ConfigService: onCreate
09-07 16:32:35.769   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 16:32:35.772  1864  4429 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-07 16:32:35.792  4432  4432 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-07 16:32:35.795  1937  2025 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 16:32:35.798   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 16:32:35.798   873   885 E PackageManager: Failed to write settings, restoring backup
09-07 16:32:35.798   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 16:32:35.798   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 16:32:35.798   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 16:32:35.798   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 16:32:35.798   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 16:32:35.798   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:35.798   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.798   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 16:32:35.802   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-07 16:32:35.802   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 16:32:35.802   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:32:35.802   873   886 E DropBoxManagerService: 	... 13 more
09-07 16:32:35.804  1864  4429 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 16:32:35.805  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 16:32:35.805  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 16:32:35.807  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 16:32:35.807  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 16:32:35.808  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 16:32:35.808  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 16:32:35.809   873  1944 I ActivityManager: Start proc 4446:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-07 16:32:35.809  1864  4429 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 16:32:35.810  1864  4429 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 16:32:35.810  1864  4429 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 16:32:35.810  1864  4429 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 16:32:35.810  1864  4429 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 16:32:35.810  1864  4429 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 16:32:35.810  1937  2025 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 16:32:35.810  1937  2025 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1937
09-07 16:32:35.810  1937  2025 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.810  1937  2025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 16:32:35.811   873  2976 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 16:32:35.813   873  4452 E DropBoxManagerService: Can't write: system_app_crash
09-07 16:32:35.813   873  4452 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:32:35.813   873  4452 E DropBoxManagerService: 	... 5 more
09-07 16:32:35.815  1937  2025 I Process : Sending signal. PID: 1937 SIG: 9
09-07 16:32:35.851  4432  4432 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-07 16:32:35.868   873  3132 I ActivityManager: Start proc 4463:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 16:32:35.870  4432  4467 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 16:32:35.882   873  1944 I WindowState: WIN DEATH: Window{801c058 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-07 16:32:35.882   873   883 D GraphicsStats: Buffer count: 1
09-07 16:32:35.892   873  1997 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1937) has died
09-07 16:32:35.894   873  1997 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-07 16:32:35.895   873  1997 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 16:32:35.913   873  2976 I ActivityManager: Start proc 4477:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 16:32:35.934  4463  4463 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:32:35.959  4477  4477 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:32:35.960  4477  4477 D AndroidRuntime: Shutting down VM
09-07 16:32:35.967  4477  4477 E AndroidRuntime: FATAL EXCEPTION: main
09-07 16:32:35.967  4477  4477 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4477
09-07 16:32:35.967  4477  4477 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 16:32:35.967  4477  4477 E AndroidRuntime: 	... 10 more
09-07 16:32:35.968  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 16:32:35.969  1526  1526 D AndroidRuntime: Shutting down VM
09-07 16:32:35.973   873  1997 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 16:32:35.974  4477  4477 I Process : Sending signal. PID: 4477 SIG: 9
09-07 16:32:35.974   873  4493 E DropBoxManagerService: Can't write: system_app_crash
09-07 16:32:35.974   873  4493 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:32:35.974   873  4493 E DropBoxManagerService: 	... 5 more
09-07 16:32:35.981  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
09-07 16:32:35.981  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
09-07 16:32:35.981  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 16:32:35.981  1526  1526 E AndroidRuntime: 	... 8 more
09-07 16:32:35.985   873  4494 E DropBoxManagerService: Can't write: system_app_crash
09-07 16:32:35.985   873  4494 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:32:35.985   873  4494 E DropBoxManagerService: 	... 5 more
09-07 16:32:35.986  1526  1526 I Process : Sending signal. PID: 1526 SIG: 9
09-07 16:32:35.993  1746  4490 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 16:32:35.995  1746  4490 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 16:32:35.997   873  2976 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4477) has died
09-07 16:32:35.998   873  2976 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:36.003  4432  4461 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:36.004  4432  4461 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 16:32:36.012   873   886 I ActivityManager: Start proc 4495:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 16:32:36.015  1746  4490 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 16:32:36.016  1746  4490 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 16:32:36.035   873  1304 D WifiService: Client connection lost with reason: 4
09-07 16:32:36.039   873   883 I ActivityManager: Process com.google.process.gapps (pid 1526) has died
09-07 16:32:36.039   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-07 16:32:36.039   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-07 16:32:36.039   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-07 16:32:36.049  1746  1746 W RocketImpressions: ClearcutLogger connection suspended: 1
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:32:36.058  4495  4495 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:32:36.058   873   883 I ActivityManager: Start proc 4508:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-07 16:32:36.058  4495  4495 D AndroidRuntime: Shutting down VM
09-07 16:32:36.073  4495  4495 E AndroidRuntime: FATAL EXCEPTION: main
09-07 16:32:36.073  4495  4495 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4495
09-07 16:32:36.073  4495  4495 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 16:32:36.073  4495  4495 E AndroidRuntime: 	... 10 more
09-07 16:32:36.075   873  1636 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 16:32:36.076  4495  4495 I Process : Sending signal. PID: 4495 SIG: 9
09-07 16:32:36.076   873  4521 E DropBoxManagerService: Can't write: system_app_crash
09-07 16:32:36.076   873  4521 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:32:36.076   873  4521 E DropBoxManagerService: 	... 5 more
09-07 16:32:36.094  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 16:32:36.094  1746  1746 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 16:32:36.102  1746  1746 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 16:32:36.102  1746  1746 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 16:32:36.104  1746  4490 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 16:32:36.106  1746  4490 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 16:32:36.113   873   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4495) has died
09-07 16:32:36.115   873   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 16:32:36.120  1746  4524 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-07 16:32:36.125  4432  4461 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-07 16:32:36.129   873  2976 I ActivityManager: Start proc 4526:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
09-07 16:32:36.131  2010  4523 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-07 16:32:36.137   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
