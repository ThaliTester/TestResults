#### Test 797638305c870dd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 16:00:24.363  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:00:24.373  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:00:24.377  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:00:24.413  1509  2999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 16:00:24.413  1509  2999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:00:24.413  1509  2999 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:00:24.413  1509  2999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 16:00:24.440  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:00:24.440  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:00:24.441  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-30 16:00:25.324  3761  3761 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 16:00:25.329  3761  3761 D AndroidRuntime: CheckJNI is OFF
08-30 16:00:25.373  3761  3761 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 16:00:25.424  3761  3761 I Radio-JNI: register_android_hardware_Radio DONE
08-30 16:00:25.447  3761  3761 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 16:00:25.452   874  1380 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 16:00:25.487  2027  2044 W SearchService: Abort, client detached.
08-30 16:00:25.492  3761  3761 D AndroidRuntime: Shutting down VM
08-30 16:00:25.502  2027  2027 I HotwordDetector: Closing mic
08-30 16:00:25.502  2027  2337 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cec47e9
08-30 16:00:25.502  2027  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 16:00:25.508   874  1687 I ActivityManager: Start proc 3770:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 16:00:25.549   377  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 16:00:25.550   377  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 16:00:25.556   377  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 16:00:25.558  2027  2348 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 16:00:25.558  2027  2353 I MicroRecognitionRnrImpl: Detection finished
08-30 16:00:25.590  3770  3770 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 16:00:25.618  3770  3770 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 16:00:25.628  3770  3770 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 626-631)
08-30 16:00:25.629  3770  3770 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:00:25.650  3770  3770 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c9146d4}
08-30 16:00:25.650  3770  3770 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:00:25.651  3770  3770 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:00:25.658  3770  3770 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 16:00:25.660  3770  3770 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 16:00:25.687  3770  3770 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 16:00:25.700  3770  3770 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:00:25.700  3770  3770 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:00:25.700  3770  3770 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:00:25.700  3770  3770 I Adreno  : Build Date                       : 10/20/15
08-30 16:00:25.700  3770  3770 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:00:25.700  3770  3770 I Adreno  : Local Branch                     : M14
08-30 16:00:25.700  3770  3770 I Adreno  : Remote Branch                    : 
08-30 16:00:25.700  3770  3770 I Adreno  : Remote Branch                    : 
08-30 16:00:25.700  3770  3770 I Adreno  : Reconstruct Branch               : 
,08-30 16:00:25.806   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7fd010:true
,08-30 16:00:25.862  3770  3770 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 16:00:25.880  3770  3770 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 16:00:25.947  3770  3809 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 16:00:25.960  3770  3795 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 16:00:26.012  3770  3809 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 16:00:26.098   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +605ms
,08-30 16:00:26.101  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-30 16:00:26.247  3770  3770 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3770
,08-30 16:00:26.328   874  1976 I ActivityManager: Killing 2987:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 16:00:26.376   874  1976 I ActivityManager: Killing 3042:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,08-30 16:00:26.445  3770  3770 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:00:26.593  3770  3812 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696659152
,08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 16:00:26.612  3770  3812 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323d818 added. We now have 1 listener(s)
,08-30 16:00:26.625  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 16:00:26.628  3770  3812 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:00:26.628  3770  3812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:26.629  3770  3812 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 16:00:26.634  3770  3812 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c590d7 added. We now have 1 listener(s)
08-30 16:00:26.635  3770  3812 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:26.638   874  1309 D WifiService: New client listening to asynchronous messages
,08-30 16:00:26.639  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:26.640  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 16:00:26.640  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:00:26.640  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 16:00:26.640  3770  3812 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,08-30 16:00:26.644  3770  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:26.644  3770  3812 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 16:00:26.650  3770  3812 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:26.651  3770  3812 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:26.651  3770  3812 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 16:00:26.651  3770  3812 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:26.652  3770  3812 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 16:00:26.705  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:26.708  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:26.709  3770  3770 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:00:27.999  3770  3821 W jxcore-log: Initializing JXcore engine
08-30 16:00:27.999  3770  3821 W jxcore-log: JXcore engine is ready
,08-30 16:00:28.037  3821  3821 W Thread-318: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 16:00:28.037  3821  3821 W Thread-318: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12667]" dev="sockfs" ino=12667 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 16:00:28.037  3821  3821 W Thread-318: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 16:00:28.047  3770  3821 W jxcore-log: Starting JXcore engine
,08-30 16:00:28.037  3821  3821 W Thread-318: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25401]" dev="sockfs" ino=25401 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 16:00:28.126  3770  3821 W jxcore-log: Platform android
08-30 16:00:28.126  3770  3821 W jxcore-log: 
,08-30 16:00:28.127  3770  3821 W jxcore-log: Process ARCH arm
08-30 16:00:28.127  3770  3821 W jxcore-log: 
,08-30 16:00:28.318  3770  3821 I jxcore-log: JXcore Cordova bridge is ready!
08-30 16:00:28.318  3770  3821 I jxcore-log: 
08-30 16:00:28.319  3770  3821 W jxcore-log: JXcore engine is started
,08-30 16:00:28.333  3770  3812 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 16:00:28.340  3770  3770 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 16:00:28.611   874  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 16:00:32.696  3061  3829 V KeepSync: Connecting to GoogleApiClient
,08-30 16:00:32.696   874  1395 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 16:00:32.758  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:00:32.762  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:00:32.807  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 16:00:32.808  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 16:00:32.808  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:00:32.808  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 16:00:32.842  1717  3830 V BaseAuthAsyncOperation: access token request failed
,08-30 16:00:32.844  3061  3829 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 16:00:32.924  1509  2900 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 16:00:32.924  1509  2900 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-30 16:00:32.924  1509  2900 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:00:32.925  1509  2900 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:00:32.959  3061  3829 E KeepSync: IOException
08-30 16:00:32.959  3061  3829 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 16:00:32.959  3061  3829 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 16:00:32.959  3061  3829 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 16:00:32.959  3061  3829 E KeepSync: 	... 10 more
,08-30 16:00:32.959  3061  3829 W KeepSync: Sync result 2
,08-30 16:00:32.971   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127554, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:00:38.228  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 16:00:38.228  3770  3821 I jxcore-log: ,
08-30 16:00:38.231  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:00:38.231  3770  3821 I jxcore-log: 
,08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:38.247  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:38.253  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:38.255  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:00:38.255  3770  3821 I jxcore-log: 
,08-30 16:00:38.257  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:00:38.257  3770  3821 I jxcore-log: 
,08-30 16:00:38.764  3770  3821 D executeNativeTests: Running unit tests
,08-30 16:00:38.822  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:00:38.822  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 added. We now have 2 listener(s)
,08-30 16:00:38.823  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:00:38.823  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:00:38.823  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:00:38.824  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:38.824  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 added. We now have 2 listener(s)
08-30 16:00:38.824  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:38.824  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:00:38.832  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:38.843  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:38.847  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:38.848  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:38.853  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:38.857  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:00:38.864  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:38.857  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:38.866  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 16:00:38.871  3770  3821 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 16:00:38.872  3770  3821 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:00:38.872  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:00:38.872  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:38.873  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 16:00:38.874  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:38.875  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:38.876  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:38.877  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:38.877  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.878  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:38.878  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:00:38.879  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 removed from the list
,08-30 16:00:38.879  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:38.879  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 removed from the list
,08-30 16:00:38.879  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:38.880  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:38.881  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:38.881  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.882  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:38.883  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:38.883  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:38.883  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:38.885  3770  3821 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 16:00:38.886  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:38.886  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:38.886  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:38.887  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:38.887  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.887  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.887  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:38.887  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:38.887  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:38.887  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:38.887  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.888  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.888  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.888  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.889  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:38.890  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:38.890  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:38.890  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:00:38.895  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:00:38.896  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-30 16:00:38.896  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:38.896  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:38.896  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:38.897  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:38.897  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.897  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.897  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:38.897  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:38.897  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:38.897  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:38.897  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.897  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.897  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:38.897  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:38.899  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:38.899  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:38.899  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:38.899  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:38.900  3770  3821 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:00:38.904  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:38.913  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:38.919  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:38.919  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:38.920  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:00:38.920  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:00:38.920  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:00:38.921  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:38.921  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:38.922  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:38.934  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:38.937  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:00:38.938  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:38.950  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:38.954  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:00:38.955  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:38.961  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 16:00:38.970  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 16:00:38.971  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:38.974  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:00:38.977  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:00:38.978  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:00:38.987  2632  2643 D BtGatt.GattService: registerClient() - UUID=369b133c-f5f4-472a-af28-64d6b1ac40af
,08-30 16:00:38.989  2632  2652 D BtGatt.GattService: onClientRegistered() - UUID=369b133c-f5f4-472a-af28-64d6b1ac40af, clientIf=5
,08-30 16:00:38.990  3770  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:00:38.991  2632  2739 D BtGatt.GattService: start scan with filters
,08-30 16:00:38.994  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:38.995  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:00:38.995  2632  2655 D BtGatt.ScanManager: handling starting scan
08-30 16:00:38.996  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:00:38.996  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:00:39.007  2632  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:39.019  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:39.020  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:39.020  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:00:39.025  2632  2652 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 16:00:39.025  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:39.025  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.026  2632  2655 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:00:39.029  3770  3821 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:00:39.031  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 16:00:39.032  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.032  2632  2655 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:39.032  2632  2655 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:00:39.036  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.036  3770  3821 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:39.036  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.036  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:00:39.037  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.037  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:39.037  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:39.037  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:00:39.037  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:39.037  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:39.037  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:39.038  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:00:39.038  3770  3821 D BluetoothAdapter: STATE_ON
08-30 16:00:39.039  2632  2739 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:39.041  2632  2643 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:00:39.041  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:39.042  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 16:00:39.042  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:39.042  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:39.042  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:39.042  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:39.043  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:00:39.043  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:39.043  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:00:39.044  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:39.045  2632  2652 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:00:39.045  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.045  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.046  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.046  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:39.046  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.046  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.046  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:39.046  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.046  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.046  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.046  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.046  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.047  3770  3821 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:00:39.048  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:39.056  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:00:39.056  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:39.056  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:39.059  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:39.059  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:39.059  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:00:39.060  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:00:39.060  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:00:39.060  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:39.060  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:00:39.061  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.063  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.065  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:00:39.065  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:00:39.066  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:00:39.066  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.066  2632  2655 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:00:39.072  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:39.073  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:00:39.073  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:00:39.073  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:00:39.073  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.074  2632  2655 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:00:39.078  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:00:39.078  2632  2652 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:00:39.079  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:39.079  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.079  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:00:39.080  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:00:39.082  2632  2738 D BtGatt.GattService: registerClient() - UUID=e315131b-284d-4fc1-a82f-0c4f634cb59d
08-30 16:00:39.082  2632  2652 D BtGatt.GattService: onClientRegistered() - UUID=e315131b-284d-4fc1-a82f-0c4f634cb59d, clientIf=5
,08-30 16:00:39.083  3770  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:00:39.083  2632  2644 D BtGatt.GattService: start scan with filters
,08-30 16:00:39.086  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:39.086  2632  2655 D BtGatt.ScanManager: handling starting scan
08-30 16:00:39.086  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:00:39.086  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:00:39.086  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:00:39.089  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:39.089  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:00:39.089  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:00:39.091  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 16:00:39.093  3770  3821 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:00:39.094  2632  2652 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 16:00:39.095  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.095  2632  2655 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:00:39.097  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.097  3770  3821 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:39.098  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:39.098  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:00:39.098  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.098  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:39.099  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:39.099  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:39.099  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:39.099  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-30 16:00:39.100  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:39.100  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:00:39.101  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:00:39.101  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:00:39.101  2632  2655 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:00:39.101  2632  2655 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:00:39.101  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:00:39.102  2632  2644 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:00:39.104  2632  2643 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:00:39.105  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:39.105  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:39.105  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 16:00:39.106  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:39.106  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:00:39.108  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:39.108  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:00:39.108  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:39.108  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:00:39.109  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:39.109  2632  2652 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:00:39.110  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.110  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.110  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.110  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:00:39.110  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.110  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.110  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.110  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.110  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.110  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.111  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.111  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:39.111  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.111  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.112  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.112  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.112  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.112  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.113  3770  3821 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:00:39.114  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:00:39.114  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:00:39.114  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:39.121  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:39.123  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:00:39.124  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.124  2632  2655 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:00:39.125  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:39.125  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:00:39.125  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:00:39.125  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:00:39.125  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:00:39.125  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:00:39.125  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:00:39.129  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.131  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 16:00:39.131  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:00:39.131  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:00:39.131  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.132  2632  2655 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:00:39.132  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.135  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:00:39.137  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:00:39.137  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:00:39.139  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:00:39.139  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:00:39.139  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:00:39.139  3770  3821 D BluetoothAdapter: STATE_ON
08-30 16:00:39.140  2632  2652 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:00:39.140  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:00:39.144  2632  2739 D BtGatt.GattService: registerClient() - UUID=903c6a47-786d-4c33-8d68-45f3a0cdce72
,08-30 16:00:39.145  2632  2652 D BtGatt.GattService: onClientRegistered() - UUID=903c6a47-786d-4c33-8d68-45f3a0cdce72, clientIf=5
,08-30 16:00:39.145  3770  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:00:39.146  2632  2643 D BtGatt.GattService: start scan with filters
,08-30 16:00:39.149  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:00:39.149  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:00:39.149  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:00:39.149  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:00:39.149  2632  2655 D BtGatt.ScanManager: handling starting scan
,08-30 16:00:39.151  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:39.151  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:00:39.151  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:00:39.152  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:00:39.154  3770  3821 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:00:39.154  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.154  3770  3821 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:39.154  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.154  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:00:39.154  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.154  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:00:39.154  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:39.154  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:00:39.154  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:00:39.155  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:39.155  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:00:39.155  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:00:39.155  3770  3821 D BluetoothAdapter: STATE_ON
08-30 16:00:39.156  2632  2652 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 16:00:39.156  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:00:39.156  2632  2738 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:00:39.156  2632  2655 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 16:00:39.157  2632  2644 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:00:39.157  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:00:39.157  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:00:39.157  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:00:39.157  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:00:39.157  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:00:39.158  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:39.158  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:00:39.158  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:00:39.158  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:00:39.159  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:39.161  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.161  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.161  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:00:39.161  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.161  3770  3821 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:00:39.161  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.161  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.162  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.162  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.162  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:00:39.162  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.162  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.162  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.162  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.162  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.162  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.162  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.163  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.163  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:39.163  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.163  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.163  3770  3821 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 16:00:39.164  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.164  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:39.164  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.164  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.164  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.164  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.164  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.164  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.164  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.164  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.164  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.165  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.165  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.165  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.165  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.165  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.165  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.165  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.166  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:00:39.166  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.166  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.166  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.166  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.166  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.167  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.167  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.167  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.167  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.167  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.167  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.167  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.167  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.167  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.169  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.169  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.169  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.169  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.169  3770  3821 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 16:00:39.169  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.169  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.169  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.169  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 16:00:39.170  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.170  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.170  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.170  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.171  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.171  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.171  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.171  2632  2655 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 16:00:39.171  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.171  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.171  2632  2655 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:00:39.171  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.171  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.171  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.171  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.171  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.172  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.172  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.172  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:00:39.172  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.172  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.172  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.172  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.172  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.172  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.172  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.173  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.173  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.173  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.173  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.173  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.173  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.173  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.173  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.173  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.173  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.173  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.174  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:00:39.175  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:39.175  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:00:39.175  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:39.175  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:00:39.175  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:00:39.175  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.176  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.176  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.176  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.176  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.176  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.176  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.176  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.176  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.176  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:39.176  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.176  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.177  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.177  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.178  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.178  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.178  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.178  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.178  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:39.178  3770  3821 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:00:39.178  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 16:00:39.182  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:39.182  3770  3821 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:00:39.183  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:00:39.184  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 16:00:39.185  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-30 16:00:39.185  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:00:39.185  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:00:39.185  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:00:39.185  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:00:39.185  3770  3821 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:39.186  3770  3821 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:00:39.186  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:39.186  3770  3821 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:39.186  3770  3821 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 16:00:39.186  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:39.186  3770  3821 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:00:39.186  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:00:39.189  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 16:00:39.190  2632  2652 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:00:39.190  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.190  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 16:00:39.190  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 16:00:39.192  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:00:39.192  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 16:00:39.192  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 16:00:39.192  3770  3821 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:00:39.192  3770  3821 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:00:39.193  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.193  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.193  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.193  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.193  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.193  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.193  3770  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 382)
08-30 16:00:39.193  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:00:39.194  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.194  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.194  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.194  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.194  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.194  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.195  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:00:39.195  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.196  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.196  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.196  3770  3835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:39.197  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.198  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.198  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.198  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.198  3770  3821 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 16:00:39.198  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.199  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.199  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.199  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.199  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.199  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.199  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.199  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.199  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.199  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:39.199  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.199  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.199  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.199  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.197  3770  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 382
08-30 16:00:39.200  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.200  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.200  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.200  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.201  3770  3821 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-30 16:00:39.201  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.201  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.201  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.201  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.201  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.201  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.201  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.201  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.201  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.201  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.201  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.201  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.201  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.201  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.202  3770  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 382)
,08-30 16:00:39.202  3770  3835 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 382)
08-30 16:00:39.202  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.203  2632  2724 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-30 16:00:39.203  3770  3836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 382)
08-30 16:00:39.203  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.203  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.203  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.205  3770  3821 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-30 16:00:39.205  2632  2652 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:00:39.205  3770  3821 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:00:39.205  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.205  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 16:00:39.205  2632  2655 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:00:39.206  3770  3821 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:00:39.206  3770  3821 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:00:39.206  3770  3821 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:00:39.206  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:39.206  3770  3821 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:00:39.207  3770  3821 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:00:39.207  3770  3821 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:00:39.207  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:39.207  3770  3821 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-30 16:00:39.207  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.208  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.208  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.208  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.208  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.208  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.209  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.209  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.209  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.209  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:39.209  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.209  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.210  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.210  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.212  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.212  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.212  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.213  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.214  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.215  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.215  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.215  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.215  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.215  2632  2652 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:00:39.215  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.216  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:00:39.216  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.216  2632  2655 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:00:39.216  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.216  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.216  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.217  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.217  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.217  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.217  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.218  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.218  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.218  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:00:39.218  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.219  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.219  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.219  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 16:00:39.219  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
,08-30 16:00:39.219  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.219  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.219  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:39.220  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.220  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.220  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.220  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.221  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:00:39.221  2632  2652 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:00:39.221  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.221  2632  2652 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:00:39.221  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.221  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.222  3770  3821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-30 16:00:39.222  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:39.225  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:00:39.226  3770  3821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:00:39.226  3770  3821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 16:00:39.226  3770  3770 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:00:39.226  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 16:00:39.226  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:00:39.227  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.227  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 16:00:39.227  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:00:39.227  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 16:00:39.227  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.227  3770  3821 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:00:39.227  3770  3770 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:00:39.227  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
,08-30 16:00:39.227  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.227  3770  3837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:39.227  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:00:39.227  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:00:39.227  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:00:39.227  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.228  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.228  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:00:39.229  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.229  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.229  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:00:39.229  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:00:39.229  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 16:00:39.229  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.229  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:00:39.229  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.229  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.229  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.229  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.229  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.229  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.229  3770  3837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 16:00:39.229  3770  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:00:39.229  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.230  3770  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:00:39.230  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.230  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.230  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.230  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.230  3770  3770 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 16:00:39.231  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.231  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.231  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.231  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.232  3770  3821 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 16:00:39.232  3770  3821 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:00:39.232  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 16:00:39.232  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:00:39.232  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.233  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.233  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.233  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:00:39.233  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.233  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.233  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.233  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.233  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.233  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.233  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.233  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.233  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:00:39.234  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.235  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.235  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:00:39.235  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:00:39.235  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.239  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.239  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.240  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.240  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.240  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.240  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.240  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.240  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.240  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.240  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:39.240  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.240  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.240  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.240  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:00:39.241  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.241  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:39.241  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.241  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.242  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:00:39.242  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:00:39.242  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:00:39.242  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:00:39.242  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.242  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.242  3770  3821 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfc78e8 not in the list
08-30 16:00:39.242  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.242  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
,08-30 16:00:39.242  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:00:39.242  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.242  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.242  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:00:39.242  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:39.244  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:00:39.244  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:00:39.244  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:00:39.244  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc65b01 not in the list
08-30 16:00:39.245  3770  3821 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 16:00:39.245  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 16:00:39.245  3770  3821 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:00:39.245  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:00:39.245  3770  3821 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 16:00:39.245  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:00:39.246  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:00:39.246  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 16:00:39.247  3770  3821 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 16:00:39.247  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:00:39.247  3770  3821 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:00:39.247  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 16:00:39.247  3770  3821 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 16:00:39.247  3770  3821 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-30 16:00:39.248  3770  3821 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 16:00:39.249  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:39.249  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d85d3fb added. We now have 2 listener(s)
08-30 16:00:39.249  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:39.251  3770  3821 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 16:00:39.251   874  2199 D WifiService: setWifiEnabled: true pid=3770, uid=10000
08-30 16:00:39.251   874  2199 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:00:39.252  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:39.252  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b3ec18 added. We now have 3 listener(s)
08-30 16:00:39.252  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:39.256  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:39.256  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1b0671 added. We now have 4 listener(s)
08-30 16:00:39.256  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:39.258  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:39.258  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fde5c56 added. We now have 5 listener(s)
08-30 16:00:39.258  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:39.261   874   885 D WifiService: setWifiEnabled: false pid=3770, uid=10000
08-30 16:00:39.261   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 16:00:39.263  2632  2648 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:00:39.263  2632  2648 D BluetoothAdapterProperties: Setting state to 13
08-30 16:00:39.263  2632  2648 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 16:00:39.264  2632  2648 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:00:39.265  2632  2648 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:00:39.265  2632  2632 D BluetoothMapService: onReceive
08-30 16:00:39.265  2632  2632 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:39.266  2632  2632 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:00:39.266  2632  2632 D BluetoothMapService: MAP Service closeService in
08-30 16:00:39.266  2632  2632 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 16:00:39.266  2632  2632 D ObexServerSockets0: shutdown(block = true)
,08-30 16:00:39.266  2632  2632 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:00:39.266  2632  2632 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:00:39.267  2632  2740 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 16:00:39.267  2632  2724 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 16:00:39.267  2632  2741 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 16:00:39.268  2632  2632 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:00:39.268  2632  3424 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:00:39.268  2632  3424 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 16:00:39.272  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:39.272  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:39.273  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:39.273  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:39.277  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:00:39.277   874   887 I ActivityManager: Start proc 3840:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 16:00:39.278  2632  2652 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:00:39.278  2632  2648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 16:00:39.279  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:00:39.281  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.283  2632  2632 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:00:39.284   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 16:00:39.284   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 16:00:39.285   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-30 16:00:39.285   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:39.290   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:39.290   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:39.290  1957  2101 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:39.290   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 16:00:39.290  1352  2080 D BluetoothHeadset: Proxy object disconnected
08-30 16:00:39.290  1352  1352 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:00:39.290  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:39.291  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:39.291  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:39.292  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:39.292  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:00:39.292  2632  2632 D A2dpService: Received stop request...Stopping profile...
,08-30 16:00:39.292   874  2079 D DhcpClient: Clearing IP address
,08-30 16:00:39.292  2632  2729 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:00:39.293   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:00:39.294   874   874 D BluetoothA2dp: Proxy object disconnected
,08-30 16:00:39.294  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:39.294  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.294  2632  2632 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:00:39.294  2632  2632 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:39.294  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.294  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:39.295  2632  2632 D HidService: Received stop request...Stopping profile...
,08-30 16:00:39.295  2632  2632 D HidService: Stopping Bluetooth HidService
,08-30 16:00:39.295   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:39.295  1352  1352 D BluetoothInputDevice: Proxy object disconnected
,08-30 16:00:39.295  1352  1352 D HidProfile: Bluetooth service disconnected
08-30 16:00:39.296  1509  2539 V NativeCrypto: Read error: ssl=0x9b082800: I/O error during system call, Connection timed out
08-30 16:00:39.296  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:39.297  1509  2539 V NativeCrypto: SSL shutdown failed: ssl=0x9b082800: I/O error during system call, Broken pipe
08-30 16:00:39.298   874  1686 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-30 16:00:39.298   874  2075 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-30 16:00:39.300   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:00:39.300   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 16:00:39.300   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 16:00:39.300   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:00:39.303   402   402 E Parcel  : Reading a NULL string not supported here.
,08-30 16:00:39.304   373   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:00:39.305  2632  2632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:00:39.305   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 16:00:39.305  2632  2652 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-30 16:00:39.305  2632  2632 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 16:00:39.305  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.305  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.305  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.305  2632  2652 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 16:00:39.306   874  2075 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-30 16:00:39.306  2632  2632 D HealthService: Received stop request...Stopping profile...
08-30 16:00:39.308  2632  2632 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:00:39.309  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:39.309  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.309  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:39.309  2632  2632 D PanService: Received stop request...Stopping profile...
08-30 16:00:39.310  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:00:39.310  1352  1352 D PanProfile: Bluetooth service disconnected
08-30 16:00:39.312   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 16:00:39.315  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:39.315  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:39.316  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:39.316  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:39.317  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:39.318  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:39.318  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:39.318  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:39.319  2632  2652 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 16:00:39.319  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.319  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.319  2632  2714 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:00:39.319  2632  2714 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:39.319  2632  2714 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:00:39.319  2632  2714 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:39.321  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:39.321  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:39.321  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.321  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:39.321  2632  2632 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:00:39.321  2632  2652 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:00:39.321  2632  2632 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:00:39.322  2632  2632 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:00:39.322  2632  2632 D BluetoothMapService: stop()
08-30 16:00:39.323  2632  2632 D BluetoothMapAppObserver: deinitObservers()
08-30 16:00:39.323  2632  2632 D BluetoothMapAppObserver: removeReceiver()
08-30 16:00:39.324  1352  1352 D BluetoothMap: Proxy object disconnected
08-30 16:00:39.324  1352  1352 D MapProfile: Bluetooth service disconnected
08-30 16:00:39.324  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:39.324  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:39.325  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.325  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:39.325  2632  2632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:00:39.325  2632  2652 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:00:39.325   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:00:39.322  1863  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:00:39.326  2632  2632 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:00:39.332  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:39.332  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:39.332  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.332  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:39.333  2632  2632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:00:39.334  2632  2632 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:00:39.336  2632  2632 D BluetoothMapService: MAP Service closeService in
08-30 16:00:39.336  2632  2632 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:39.336  2632  2632 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:39.336  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:39.336  2632  2632 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:39.336  2632  2648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 16:00:39.336  2632  2648 D BluetoothAdapterProperties: Setting state to 15
08-30 16:00:39.336  2632  2648 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 16:00:39.337  1352  1375 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:00:39.337  2632  2648 I BluetoothAdapterState: Entering BleOnState
08-30 16:00:39.338  1352  2080 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:00:39.338  2632  2632 D BluetoothMapService: cleanup()
08-30 16:00:39.338  1352  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:00:39.338  2632  2632 D BluetoothMapService: MAP Service closeService in
08-30 16:00:39.339   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:39.339   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:00:39.339   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:39.339   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:39.339  1352  1709 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:39.340  1352  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:00:39.340  1957  2101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:39.340  1352  2080 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:00:39.341  2632  2648 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 16:00:39.341  2632  2648 D BluetoothAdapterProperties: Setting state to 16
08-30 16:00:39.341  2632  2648 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:00:39.341  2632  2648 D BluetoothAdapterProperties: onBleDisable
08-30 16:00:39.342  2632  2648 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:00:39.342  2632  2649 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:00:39.343  2632  2714 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 16:00:39.343  2632  2714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:39.343  2632  2652 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:00:39.344  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.346  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.350  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.351   874  2102 D DhcpClient: Receive thread stopped
08-30 16:00:39.351  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.364   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 16:00:39.369  3840  3840 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-30 16:00:39.381  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:39.383   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 16:00:39.384   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:00:39.384   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:00:39.386  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:00:39.387   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 16:00:39.387   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3eeec4:true
08-30 16:00:39.389  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.390  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:39.393  3427  3427 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@323d818 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-30 16:00:39.395  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-30 16:00:39.403   874   885 I ActivityManager: Start proc 3858:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-30 16:00:39.413  3840  3840 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 16:00:39.416  3840  3840 D BluetoothMap: Create BluetoothMap proxy object
08-30 16:00:39.420  3840  3840 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 16:00:39.433  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:39.438  3858  3858 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 16:00:39.440   874  1955 I ActivityManager: Killing 3219:com.google.android.gm/u0a78 (adj 15): empty #17
,08-30 16:00:39.442   373   872 E Netd    : netlink response contains error (No such file or directory)
,08-30 16:00:39.443   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 16:00:39.554  2632  2652 I bt_hci  : shut_down
,08-30 16:00:39.562  2632  2656 I bt_vendor: low_power_mode_cb
,08-30 16:00:39.562  2632  2656 D bt_hwcfg: hw_epilog_process
,08-30 16:00:39.583  2632  2656 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:00:39.583  2632  2656 I bt_vendor: epilog_cb
,08-30 16:00:39.583  2632  2656 I bt_hci  : epilog_finished_callback
,08-30 16:00:39.585  2632  2652 I bt_hci_h4: hal_close
08-30 16:00:39.585  2632  2652 I bt_userial_vendor: device fd = 51 close
,08-30 16:00:39.627  3858  3858 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.627  3858  3858 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.627  3858  3858 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.627  3858  3858 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.627  3858  3858 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:00:39.627  3858  3858 D StrictMode: 	,at com.google.r.e.b(PG:15188)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.627  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.628  3858  3858 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.628  3858  3858 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.628  3858  3858 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:00:39.628  3858  3858 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:00:39.650   874  2198 I ActivityManager: Start proc 3890:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 16:00:39.651   874  2198 I ActivityManager: Killing 3427:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 16:00:39.730  3770  3770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:00:39.796  2632  2649 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:00:39.796  2632  2648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:00:39.800  2632  2648 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 16:00:39.801  2632  2632 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:00:39.802  2632  2632 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 16:00:39.802  3890  3890 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-30 16:00:39.802  2632  2632 D BtGatt.GattService: stop()
,08-30 16:00:39.802  2632  2632 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:00:39.805  2632  2632 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:39.806  2632  2632 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:39.806  2632  2632 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:39.806  2632  2632 V BluetoothAdapterState: isBleTurningOff()=true
08-30 16:00:39.806  2632  2648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 16:00:39.807  2632  2648 D BluetoothAdapterProperties: Setting state to 10
,08-30 16:00:39.807  2632  2648 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 16:00:39.808  2632  2648 I BluetoothAdapterState: Entering OffState
,08-30 16:00:39.808   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 16:00:39.829  2632  2632 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 16:00:39.829  2632  2632 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 16:00:39.830  2632  2649 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:00:39.830  2632  2632 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:00:39.834  2632  2649 D bt_stack_manager: event_clean_up_stack finished.
,08-30 16:00:39.842  2632  2632 I art     : System.exit called, status: 0
,08-30 16:00:39.842  2632  2632 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:00:39.946  3890  3890 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 16:00:39.965  3858  3878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 16:00:39.974  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:39.981   874   884 I ActivityManager: Process com.android.bluetooth (pid 2632) has died
,08-30 16:00:40.003   874  1955 I ActivityManager: Start proc 3919:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-30 16:00:40.005  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:40.020   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cc11f24:true
,08-30 16:00:40.067  3919  3919 D AdapterServiceConfig: Adding HeadsetService
08-30 16:00:40.067  3919  3919 D AdapterServiceConfig: Adding A2dpService
08-30 16:00:40.067  3919  3919 D AdapterServiceConfig: Adding HidService
08-30 16:00:40.068  3919  3919 D AdapterServiceConfig: Adding HealthService
,08-30 16:00:40.068  3919  3919 D AdapterServiceConfig: Adding PanService
,08-30 16:00:40.069  3919  3919 D AdapterServiceConfig: Adding GattService
08-30 16:00:40.069  3919  3919 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:00:40.074   874  1975 I ActivityManager: Killing 2800:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 16:00:40.131  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:40.151  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:00:40.156  1717  1717 D SystemUpdateService: onCreate
,08-30 16:00:40.159  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:00:40.163  1717  3931 I SystemUpdateService: active receiver: enabled
,08-30 16:00:40.167  1717  3931 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:00:40.177  1717  3931 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 16:00:40.178  1717  3931 I SystemUpdateService: now status is 0 (complete)
,08-30 16:00:40.178  1717  3931 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:00:40.178  1717  3931 I SystemUpdateService: file has been verified
,08-30 16:00:40.178  1717  3931 I SystemUpdateService: OTA package size = 12249756
,08-30 16:00:40.183  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:00:40.186  1717  3931 I SystemUpdateService: showing system update notification
,08-30 16:00:40.188  1717  2517 I iu.UploadsManager: num queued entries: 0
08-30 16:00:40.188  1717  2517 I iu.UploadsManager: num updated entries: 0
,08-30 16:00:40.192  1717  2517 I iu.SyncManager: NEXT; no task
,08-30 16:00:40.203  1717  1717 D SystemUpdateService: onDestroy
,08-30 16:00:40.211  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:00:40.216  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:00:40.238   874  2184 I ActivityManager: Start proc 3933:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 16:00:40.299  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 16:00:40.302  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:40.309  3933  3933 D SprintDMHelper: simOperator: 
08-30 16:00:40.309  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:00:40.335   874  1956 I ActivityManager: Start proc 3945:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 16:00:40.339   874  1956 I ActivityManager: Killing 1693:android.process.acore/u0a5 (adj 15): empty #17
,08-30 16:00:40.458  2179  3959 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 16:00:40.477   874   884 I ActivityManager: Start proc 3960:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 16:00:40.481   874  2198 I ActivityManager: Killing 3622:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 16:00:40.541  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 16:00:40.598  3960  3960 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 16:00:40.598  3960  3960 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 16:00:40.598  3960  3960 I GAv4    :   adb logcat -s GAv4
,08-30 16:00:40.613  3960  3960 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:40.620  3960  3960 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:40.651  3960  3977 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:00:40.767  3960  3960 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 16:00:40.808  3960  3960 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 16:00:40.816  3960  3960 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5816-5819)
,08-30 16:00:40.816  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 16:00:40.835  3960  3960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c97748}
,08-30 16:00:40.836  3960  3960 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 16:00:40.836  3960  3960 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:00:40.845  3960  3960 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 16:00:40.847  3960  3960 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 16:00:40.862  3960  3960 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 16:00:40.878  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:00:40.878  3960  3960 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:00:40.878  3960  3960 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:00:40.878  3960  3960 I Adreno  : Build Date                       : 10/20/15
08-30 16:00:40.878  3960  3960 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:00:40.878  3960  3960 I Adreno  : Local Branch                     : M14
08-30 16:00:40.878  3960  3960 I Adreno  : Remote Branch                    : 
08-30 16:00:40.878  3960  3960 I Adreno  : Remote Branch                    : 
08-30 16:00:40.878  3960  3960 I Adreno  : Reconstruct Branch               : 
,08-30 16:00:40.941  3960  3960 I NSApplication: Starting up...
,08-30 16:00:40.954  3960  4006 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 16:00:40.990   874  1687 I ActivityManager: Start proc 4011:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 16:00:40.992   874  1687 I ActivityManager: Killing 3637:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 16:00:41.077  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 16:00:41.268   874  1976 I ActivityManager: Killing 3449:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 16:00:42.294   874  1687 D WifiService: setWifiEnabled: true pid=3770, uid=10000
,08-30 16:00:42.295   874  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:00:42.311   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:00:42.316  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:42.316  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:42.316  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:42.317  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:42.319  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:42.320  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:42.320  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:42.320  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:42.341   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:00:42.342   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 16:00:42.343   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:00:42.344   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 16:00:42.344   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-30 16:00:42.344   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 16:00:42.345   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,08-30 16:00:42.362   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:00:42.364   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.62 rxSuccessRate=17.12 delta 1000 -> 994
,08-30 16:00:42.364   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:42.366   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
,08-30 16:00:42.366   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 16:00:42.369   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-30 16:00:42.369   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:00:42.392   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 16:00:42.392   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:42.400   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:00:42.452   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:00:42.455  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:00:42.876  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:00:42.918  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:00:42.919  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 16:00:42.924   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:00:42.932   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:00:42.932   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:42.933   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 16:00:42.955   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:42.968   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:42.969   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 16:00:42.987   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-30 16:00:42.992   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 16:00:43.001   874  4034 D DhcpClient: Receive thread started
,08-30 16:00:43.082   874  1308 E native  : do suspend false
,08-30 16:00:43.101   874  2079 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:00:43.115   874  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-30 16:00:43.117   874  2079 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-30 16:00:43.120   874  2079 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:00:43.135   874  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:00:43.136   874  2079 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:00:43.140   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:43.151   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:00:43.151   874  2079 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:00:43.168   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:00:43.171   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:00:43.171   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:00:43.173   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:00:43.178   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 16:00:43.190   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:00:43.246   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:00:43.246   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 16:00:43.249   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 16:00:43.250   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 16:00:43.252   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 16:00:43.266   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:00:43.275   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-30 16:00:43.275   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 16:00:43.275   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 16:00:43.275   874  1310 D ConnectivityService:    accepting network in place of null
,08-30 16:00:43.276   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 16:00:43.276   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 16:00:43.277   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:00:43.319   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:00:43.368   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:00:43.377   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 16:00:43.378   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-30 16:00:43.387   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 16:00:43.395   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 16:00:43.400  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:43.400  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:00:43.400  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:43.400  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:43.403  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:00:43.404  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:00:43.404  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:43.404  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:00:43.411  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 16:00:43.414  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:00:43.417  1717  1717 D SystemUpdateService: onCreate
,08-30 16:00:43.421  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:00:43.423  1717  4045 I SystemUpdateService: active receiver: enabled
,08-30 16:00:43.429  1717  4045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:00:43.432  1717  4045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 16:00:43.432  1717  4045 I SystemUpdateService: now status is 0 (complete)
08-30 16:00:43.432  1717  4045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:00:43.432  1717  4045 I SystemUpdateService: file has been verified
,08-30 16:00:43.432  1717  4045 I SystemUpdateService: OTA package size = 12249756
,08-30 16:00:43.437  1717  4045 I SystemUpdateService: showing system update notification
,08-30 16:00:43.443  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 16:00:43.445  1717  2517 I iu.UploadsManager: num queued entries: 0
,08-30 16:00:43.447  1717  4049 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 16:00:43.447  1717  4049 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 16:00:43.448  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:00:43.449  1717  4049 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:00:43.449  1717  2517 I iu.UploadsManager: num updated entries: 0
,08-30 16:00:43.449  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:00:43.452  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:43.455  1717  1717 D SystemUpdateService: onDestroy
,08-30 16:00:43.456  1717  2517 I iu.SyncManager: NEXT; no task
,08-30 16:00:43.456  3933  3933 D SprintDMHelper: simOperator: 
,08-30 16:00:43.456  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:00:43.465  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:00:43.467  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:00:43.494  1509  2999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-30 16:00:43.494  1509  2999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 16:00:43.494  1509  2999 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:00:43.494  1509  2999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:00:43.506  1717  4049 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-30 16:00:43.989   874  4033 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138991, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:00:44.378   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 16:00:45.302   874  1687 D WifiService: setWifiEnabled: false pid=3770, uid=10000
,08-30 16:00:45.302   874  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:00:45.337  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 16:00:45.344   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 16:00:45.345   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 16:00:45.345   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:00:45.345   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:45.369   874  2079 D DhcpClient: Clearing IP address
,08-30 16:00:45.369   373   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:00:45.372   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:45.385   874  4034 D DhcpClient: Receive thread stopped
,08-30 16:00:45.387   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-30 16:00:45.388   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-30 16:00:45.391   402   402 E Parcel  : Reading a NULL string not supported here.
,08-30 16:00:45.398   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-30 16:00:45.401   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:00:45.403   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-30 16:00:45.404   373   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:00:45.412  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:45.412  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:45.412  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:45.413   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:00:45.412  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:45.415   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 16:00:45.417  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:45.418  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:45.418  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:45.418  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:45.424  1863  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:00:45.438   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:00:45.465   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:00:45.467   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 16:00:45.467   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:45.469   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:00:45.477  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:45.477  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-30 16:00:45.478  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:45.485  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:00:45.487  1717  1717 D SystemUpdateService: onCreate
,08-30 16:00:45.493  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:00:45.501  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:00:45.503  1717  2517 I iu.UploadsManager: num queued entries: 0
,08-30 16:00:45.503  1717  2517 I iu.UploadsManager: num updated entries: 0
,08-30 16:00:45.505  1717  4064 I SystemUpdateService: active receiver: enabled
,08-30 16:00:45.508  1717  2517 I iu.SyncManager: NEXT; no task
,08-30 16:00:45.509  1717  4064 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:00:45.510  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:00:45.512  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:00:45.513  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:00:45.515  1717  4064 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 16:00:45.515  1717  4064 I SystemUpdateService: now status is 0 (complete)
,08-30 16:00:45.515  1717  4064 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 16:00:45.515  1717  4064 I SystemUpdateService: file has been verified
08-30 16:00:45.516  1717  4064 I SystemUpdateService: OTA package size = 12249756
,08-30 16:00:45.518  3933  3933 D SprintDMHelper: simOperator: 
08-30 16:00:45.518  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:00:45.533  1717  4064 I SystemUpdateService: showing system update notification
,08-30 16:00:45.560   373   872 E Netd    : netlink response contains error (No such file or directory)
,08-30 16:00:45.560  1717  1717 D SystemUpdateService: onDestroy
08-30 16:00:45.561   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 16:00:46.135  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:00:46.181  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:00:46.182  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-30 16:00:46.182  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:00:46.182  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:00:46.199  3520  3520 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:00:46.200  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:00:46.200  3520  3520 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-30 16:00:48.290   874  4032 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-30 16:00:48.292   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 16:00:48.360   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53fe3ba:true
,08-30 16:00:48.360  3919  3919 D BluetoothAdapterState: make() - Creating AdapterState,
,08-30 16:00:48.365  3919  3919 I bt_bluedroid: init
,08-30 16:00:48.366  3919  4072 I BluetoothAdapterState: Entering OffState
,08-30 16:00:48.368  3919  4073 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 16:00:48.368  3919  4073 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 16:00:48.368  3919  4073 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 16:00:48.368  3919  4073 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:00:48.369  3919  3919 I bt_bluedroid: get_profile_interface socket
,08-30 16:00:48.371  3919  3919 I bt_bluedroid: get_profile_interface sdp
,08-30 16:00:48.375  3919  4076 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 16:00:48.377  3919  3930 I bt_bluedroid: config_hci_snoop_log
08-30 16:00:48.377  3919  4076 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 16:00:48.379   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 16:00:48.390  3919  4072 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:00:48.390  3919  4072 D BluetoothAdapterProperties: Setting state to 14
08-30 16:00:48.391  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 16:00:48.395  3919  4072 D BluetoothBondStateMachine: make
,08-30 16:00:48.404  3919  4078 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:00:48.405  3919  4072 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:00:48.407  3919  3919 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:00:48.411  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:48.413  3919  3919 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:00:48.413  3919  3919 D BtGatt.GattService: Received start request. Starting profile...
,08-30 16:00:48.414  3919  3919 D BtGatt.GattService: start()
08-30 16:00:48.414  3919  3919 I bt_bluedroid: get_profile_interface gatt
,08-30 16:00:48.415  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:48.415  3919  3919 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:00:48.423  3919  3919 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:48.423  3919  3919 V BluetoothAdapterState: isTurningOn()=false,
08-30 16:00:48.423  3919  3919 V BluetoothAdapterState: isBleTurningOn()=true
08-30 16:00:48.423  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:48.424  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 16:00:48.425  3919  4072 I bt_bluedroid: enable
08-30 16:00:48.425  3919  4073 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 16:00:48.425  3919  4073 I bt_hci  : start_up
,08-30 16:00:48.431  3919  4073 I bt_vendor: alloc value 0xb3979189
08-30 16:00:48.431  3919  4073 I bt_vendor: init
08-30 16:00:48.431  3919  4073 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 16:00:48.431  3919  4073 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:00:48.492  2179  4051 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-30 16:00:48.492  2179  4051 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:00:48.494  2179  4051 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 16:00:48.537  3919  4073 D bt_hci  : start_up starting async portion
,08-30 16:00:48.538  3919  4081 I bt_hci  : event_finish_startup
08-30 16:00:48.538  3919  4081 I bt_hci_h4: hal_open
08-30 16:00:48.538  3919  4081 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 16:00:48.545  3919  4081 I bt_userial_vendor: device fd = 51 open
,08-30 16:00:48.581  3919  4081 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:00:48.613  3919  4081 D bt_hwcfg: Chipset BCM4354A2
08-30 16:00:48.613  3919  4081 D bt_hwcfg: Target name = [BCM4354A2]
08-30 16:00:48.614  3919  4081 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:00:49.284  3919  4081 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 16:00:49.286  3919  4081 D bt_hwcfg: Settlement delay -- 100 ms
08-30 16:00:49.286  3919  4081 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:00:49.403  3919  4081 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:00:49.404  3919  4081 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:00:49.434  3919  4081 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:00:49.434  3919  4081 I bt_vendor: firmware callback
,08-30 16:00:49.434  3919  4081 I bt_hci  : firmware_config_callback
,08-30 16:00:49.446  3919  4083 I bt_btu  : btu_task pending for preload complete event
,08-30 16:00:49.446  3919  4083 I bt_btu_task: Bluetooth chip preload is complete
08-30 16:00:49.446  3919  4083 I bt_btu  : btu_task received preload complete event
,08-30 16:00:49.456  3919  4083 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:00:49.456  3919  4083 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:00:49.456  3919  4083 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:00:49.457  3919  4083 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:00:49.457  3919  4083 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:00:49.457  3919  4083 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:00:49.458  3919  4083 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:00:49.458  3919  4083 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:00:49.458  3919  4083 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:00:49.459  3919  4083 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 16:00:49.459  3919  4083 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 16:00:49.459  3919  4083 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:00:49.459  3919  4083 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:00:49.460  3919  4083 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 16:00:49.460  3919  4083 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:00:49.595  3919  4083 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-30 16:00:49.596  3919  4083 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-30 16:00:49.608  3919  4076 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:00:49.610  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:00:49.611  3919  4076 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:00:49.615  3919  4076 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:00:49.619  3919  4076 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:00:49.619  3919  4076 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:00:49.621  3919  4076 D bt_hci  : do_postload posting postload work item
,08-30 16:00:49.621  3919  4081 I bt_hci  : event_postload
,08-30 16:00:49.621  3919  4081 I bt_vendor: sco_config_cb
,08-30 16:00:49.621  3919  4081 I bt_hci  : sco_config_callback postload finished.
08-30 16:00:49.624  3919  4076 D bt_bte_conf: Device ID record 1 : primary
08-30 16:00:49.624  3919  4076 D bt_bte_conf:   vendorId            = 000f
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   product             = 1200
08-30 16:00:49.625  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   version             = 1436
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   clientExecutableURL = 
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   serviceDescription  = 
08-30 16:00:49.625  3919  4076 D bt_bte_conf:   documentationURL    = 
08-30 16:00:49.626  3919  4076 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:00:49.626  3919  4073 D bt_stack_manager: event_start_up_stack finished
08-30 16:00:49.629  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:49.630  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 16:00:49.631  3919  4072 D BluetoothAdapterProperties: Setting state to 15
08-30 16:00:49.631  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:00:49.632  3919  4081 I bt_vendor: low_power_mode_cb
08-30 16:00:49.633  3919  4072 I BluetoothAdapterState: Entering BleOnState
,08-30 16:00:49.641  3919  4072 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 16:00:49.641  3919  4072 D BluetoothAdapterProperties: Setting state to 11
,08-30 16:00:49.641  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-30 16:00:49.647  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.648  3919  3919 D HeadsetService: Received start request. Starting profile...
08-30 16:00:49.651  3919  3919 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:00:49.652  3919  3919 D HeadsetStateMachine: make
08-30 16:00:49.656  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:49.658  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:49.666  3919  4072 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:00:49.667  3919  3919 D HeadsetStateMachine: max_hf_connections = 1
,08-30 16:00:49.667  3919  3919 I bt_bluedroid: get_profile_interface handsfree
,08-30 16:00:49.668  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:00:49.668  3919  4076 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 16:00:49.679  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.681  3919  3919 D A2dpService: Received start request. Starting profile...
,08-30 16:00:49.682  3919  3919 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 16:00:49.683  3919  3919 I bt_bluedroid: get_profile_interface avrcp
,08-30 16:00:49.697  3919  3919 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 16:00:49.697  3919  3919 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-30 16:00:49.698  3919  3919 D A2dpStateMachine: make
,08-30 16:00:49.701  3919  3919 I bt_bluedroid: get_profile_interface a2dp
,08-30 16:00:49.703  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 16:00:49.706  3919  3919 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 16:00:49.706  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.707  3919  4092 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:00:49.708  3919  3919 D HidService: Received start request. Starting profile...
08-30 16:00:49.708  3840  3840 D BluetoothInputDevice: Proxy object connected
08-30 16:00:49.708  3919  3919 I bt_bluedroid: get_profile_interface hidhost
,08-30 16:00:49.708  3919  3919 D HidService: setHidService(): set to: null
08-30 16:00:49.708  3919  4076 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-30 16:00:49.708  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 16:00:49.709  3840  3840 D HidProfile: Bluetooth service connected
08-30 16:00:49.709  3919  3919 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:00:49.709  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.710  3919  3919 D HealthService: Received start request. Starting profile...
,08-30 16:00:49.713  3919  3919 I bt_bluedroid: get_profile_interface health
08-30 16:00:49.714  3919  3919 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:00:49.714  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.716  3840  3840 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:00:49.716  3919  3919 D PanService: Received start request. Starting profile...
08-30 16:00:49.717  3919  3919 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 16:00:49.717  3840  3840 D PanProfile: Bluetooth service connected
,08-30 16:00:49.717  3919  3919 I bt_bluedroid: get_profile_interface pan
08-30 16:00:49.717  3919  4076 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 16:00:49.722  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:49.722  3919  3919 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:49.725  3840  3840 D BluetoothMap: Proxy object connected
08-30 16:00:49.725  3919  3919 D BluetoothMapService: Received start request. Starting profile...
,08-30 16:00:49.726  3919  3919 D BluetoothMapService: start()
08-30 16:00:49.726  3840  3840 D MapProfile: Bluetooth service connected
08-30 16:00:49.726  3840  3840 D BluetoothMap: getConnectedDevices()
08-30 16:00:49.727  3840  3840 D BluetoothMap: Bluetooth is Not enabled
,08-30 16:00:49.728  3919  3919 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 16:00:49.729  3919  3919 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 16:00:49.729  3919  3919 D BluetoothMapAppObserver: createReceiver()
,08-30 16:00:49.731  3919  3919 D BluetoothMapAppObserver: initObservers()
,08-30 16:00:49.731  3919  3919 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 16:00:49.737  3919  3919 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:49.737  3919  3919 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:00:49.737  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:49.738  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:49.739  3919  3919 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:49.739  3919  3919 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:49.740  3919  4090 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:49.740  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:49.741  3919  3919 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:49.741  3919  3919 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:00:49.741  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:49.741  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:49.743  3919  3919 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:49.743  3919  3919 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:49.743  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:49.743  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:49.743  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 16:00:49.743  3919  4072 D BluetoothAdapterProperties: ScanMode =  20
,08-30 16:00:49.743  3919  4072 D BluetoothAdapterProperties: State =  11
,08-30 16:00:49.744  3919  4072 D BluetoothAdapterProperties: Setting state to 12
,08-30 16:00:49.744  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:00:49.744  3919  4072 I BluetoothAdapterState: Entering OnState
,08-30 16:00:49.745  1352  1375 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:00:49.746  3919  4076 D BluetoothAdapterProperties: Scan Mode:21
,08-30 16:00:49.746  3919  4076 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 16:00:49.750  1352  2080 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:49.751  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:49.753  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:49.753  1352  1352 D BluetoothInputDevice: Proxy object connected
,08-30 16:00:49.753  1352  1352 D HidProfile: Bluetooth service connected
08-30 16:00:49.754  3840  3853 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:00:49.756  1352  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:49.758  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:49.758   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:49.758   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:49.759   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:00:49.759  3840  3852 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:00:49.759  3919  3919 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 16:00:49.759   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:49.760  3840  3853 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:00:49.760  3919  3919 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-30 16:00:49.760  1352  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:00:49.761  3840  3852 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:00:49.761  1352  2080 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:00:49.761  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:49.763  1957  2101 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:49.764  1352  1352 D BluetoothMap: Proxy object connected
08-30 16:00:49.764  1352  1352 D MapProfile: Bluetooth service connected
,08-30 16:00:49.764  1352  1365 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:00:49.764  1352  1352 D BluetoothMap: getConnectedDevices()
08-30 16:00:49.767  3919  3919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:49.768  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:00:49.768  1352  1352 D PanProfile: Bluetooth service connected
08-30 16:00:49.769   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 16:00:49.774  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:49.774  3919  3919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:49.776  3840  3840 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-30 16:00:49.776  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:49.776  3919  3919 D ObexServerSockets: Succeed to create listening sockets 
08-30 16:00:49.776  3919  3919 D ObexServerSockets0: startAccept()
08-30 16:00:49.777  3919  3919 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:00:49.780  3840  3840 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 16:00:49.784  3919  4098 D ObexServerSockets0: Accepting socket connection...
08-30 16:00:49.785  3919  3919 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 16:00:49.785  3919  3919 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 16:00:49.787   874   874 D BluetoothA2dp: Proxy object connected
08-30 16:00:49.787  3919  3919 D BluetoothMapService: onReceive
,08-30 16:00:49.787  3919  3919 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:00:49.787  3919  3919 D BluetoothMapService: STATE_ON
08-30 16:00:49.788  3919  4099 D ObexServerSockets0: Accepting socket connection...
,08-30 16:00:49.788  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:49.789  1352  1352 D BluetoothA2dp: Proxy object connected
08-30 16:00:49.793  3840  3840 D BluetoothA2dp: Proxy object connected
08-30 16:00:49.795  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:49.802  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:49.811  3840  3840 D BluetoothPbap: Proxy object connected
,08-30 16:00:49.814  1352  1352 D BluetoothPbap: Proxy object connected
08-30 16:00:49.814  1352  1352 D PbapServerProfile: Bluetooth service connected
,08-30 16:00:49.816  3840  3840 D PbapServerProfile: Bluetooth service connected
,08-30 16:00:49.822  3919  3919 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:00:49.822  3919  3919 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:00:49.825  3919  4103 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:49.843  3919  4107 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:49.845  3919  4107 I BtOppRfcommListener: Accept thread started.
,08-30 16:00:49.862   874   874 D BluetoothHeadset: Proxy object connected
,08-30 16:00:49.862   874   874 D BluetoothHeadset: Proxy object connected
08-30 16:00:49.863  1957  2191 D BluetoothHeadset: Proxy object connected
08-30 16:00:49.863   874   874 D BluetoothHeadset: Proxy object connected
,08-30 16:00:49.864  1352  2080 D BluetoothHeadset: Proxy object connected
08-30 16:00:49.864  1352  1352 D HeadsetProfile: Bluetooth service connected
08-30 16:00:49.864  1957  1977 D BluetoothHeadset: Proxy object connected
,08-30 16:00:49.884  3840  3852 D BluetoothHeadset: Proxy object connected
,08-30 16:00:49.885  3840  3840 D HeadsetProfile: Bluetooth service connected
,08-30 16:00:51.278   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-30 16:00:51.321  3919  4072 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:00:51.322  3919  4072 D BluetoothAdapterProperties: Setting state to 13
,08-30 16:00:51.322  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 16:00:51.325  3919  4072 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:00:51.328  3919  4072 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:00:51.333  3919  4076 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:00:51.334  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 16:00:51.339  3919  3919 D BluetoothMapService: onReceive
,08-30 16:00:51.339  3919  3919 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:51.340  3919  3919 D BluetoothMapService: STATE_TURNING_OFF
,08-30 16:00:51.340  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:51.341  3919  3919 D BluetoothMapService: MAP Service closeService in
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:51.341  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:51.341  3919  3919 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 16:00:51.341  3919  3919 D ObexServerSockets0: shutdown(block = true)
08-30 16:00:51.342  3919  4098 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 16:00:51.343  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:51.343  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:51.345  3919  3919 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:00:51.345  3919  4099 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 16:00:51.347  3919  4086 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 16:00:51.349  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:51.349  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:00:51.351  3770  3770 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:00:51.351  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:00:51.352  3919  3919 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 16:00:51.352  3919  3919 I BtOppRfcommListener: stopping Accept Thread
08-30 16:00:51.352  3919  4107 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:00:51.353  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:51.353  3919  4107 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:00:51.354  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:51.355  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:51.358  3919  3919 D HeadsetService: Received stop request...Stopping profile...
08-30 16:00:51.361   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 16:00:51.361   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:51.361  1957  1983 D BluetoothHeadset: Proxy object disconnected
08-30 16:00:51.361   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 16:00:51.362  1352  2080 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:51.362  3840  3852 D BluetoothHeadset: Proxy object disconnected
,08-30 16:00:51.363  1352  1352 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:00:51.363  3919  3919 D A2dpService: Received stop request...Stopping profile...
08-30 16:00:51.363  3919  4092 D A2dpStateMachine: Exit Disconnected: -1
08-30 16:00:51.364  3840  3840 D DockEventReceiver: finishStartingService: stopping service
08-30 16:00:51.365   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:51.365  1352  1352 D BluetoothA2dp: Proxy object disconnected
08-30 16:00:51.366  3840  3840 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:00:51.366  3840  3840 D BluetoothA2dp: Proxy object disconnected
,08-30 16:00:51.368  3919  3919 D HidService: Received stop request...Stopping profile...
,08-30 16:00:51.368  3919  3919 D HidService: Stopping Bluetooth HidService
08-30 16:00:51.370  3840  3840 D BluetoothInputDevice: Proxy object disconnected
08-30 16:00:51.370  3840  3840 D HidProfile: Bluetooth service disconnected
,08-30 16:00:51.371  1352  1352 D BluetoothInputDevice: Proxy object disconnected
08-30 16:00:51.371  1352  1352 D HidProfile: Bluetooth service disconnected
,08-30 16:00:51.371  3919  3919 D HealthService: Received stop request...Stopping profile...
,08-30 16:00:51.373  3919  3919 D PanService: Received stop request...Stopping profile...
,08-30 16:00:51.373  1352  1352 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 16:00:51.373  1352  1352 D PanProfile: Bluetooth service disconnected
08-30 16:00:51.374  3840  3840 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:00:51.374  3840  3840 D PanProfile: Bluetooth service disconnected
08-30 16:00:51.374  3919  3919 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:00:51.374  3919  3919 D BluetoothMapService: stop()
08-30 16:00:51.375  3919  3919 D BluetoothMapAppObserver: deinitObservers()
,08-30 16:00:51.375  3919  3919 D BluetoothMapAppObserver: removeReceiver()
,08-30 16:00:51.376  1352  1352 D BluetoothMap: Proxy object disconnected
,08-30 16:00:51.376  1352  1352 D MapProfile: Bluetooth service disconnected
08-30 16:00:51.376  3840  3840 D BluetoothMap: Proxy object disconnected
08-30 16:00:51.377  3840  3840 D MapProfile: Bluetooth service disconnected
,08-30 16:00:51.379  3919  3919 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:00:51.379  3919  3919 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:51.380  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:51.380  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:51.380  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:51.384  3919  3919 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 16:00:51.384  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 16:00:51.384  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:51.384  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:51.384  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:51.384  3919  3919 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 16:00:51.384  3919  4076 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-30 16:00:51.385  3919  3919 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:51.385  3919  3919 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:51.385  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:51.385  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:51.387  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 16:00:51.387  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:51.387  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:00:51.388  3919  4083 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:00:51.388  3919  4083 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:51.388  3919  4083 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 16:00:51.388  3919  4083 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:00:51.388  3919  3919 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:00:51.388  3919  3919 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:51.388  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:51.388  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:51.388  3919  3919 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:00:51.388  3919  3919 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:00:51.389  3919  3919 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:51.389  3919  3919 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:51.389  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:51.389  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:51.389  3919  3919 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 16:00:51.390  3919  4076 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:00:51.390  3919  4076 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:00:51.390  3919  3919 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:00:51.390  3919  3919 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:51.390  3919  3919 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:51.391  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:51.391  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:51.391  3919  3919 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:00:51.391  3919  3919 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:00:51.392  3919  3919 D BluetoothMapService: MAP Service closeService in
08-30 16:00:51.392  3919  3919 V BluetoothAdapterState: isTurningOff()=true
08-30 16:00:51.392  3919  3919 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:51.392  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:51.392  3919  3919 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:51.393  3919  3919 D BluetoothMapService: cleanup()
08-30 16:00:51.393  3919  3919 D BluetoothMapService: MAP Service closeService in
08-30 16:00:51.393  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-30 16:00:51.393  3919  4072 D BluetoothAdapterProperties: Setting state to 15
08-30 16:00:51.393  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 16:00:51.394  3840  3853 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:51.395  3919  4072 I BluetoothAdapterState: Entering BleOnState
08-30 16:00:51.395  1352  1365 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:00:51.395  1352  1352 D BluetoothPbap: Proxy object disconnected
,08-30 16:00:51.395  1352  1352 D PbapServerProfile: Bluetooth service disconnected
08-30 16:00:51.396  3840  3840 D BluetoothPbap: Proxy object disconnected
08-30 16:00:51.396  1352  2080 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:00:51.396  3840  3852 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:00:51.396  3840  3840 D PbapServerProfile: Bluetooth service disconnected
08-30 16:00:51.399  1352  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:00:51.401   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:00:51.401   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:00:51.401   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:51.402  3840  3853 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:00:51.402   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:51.402  3840  3852 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:00:51.403  1352  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:51.403  3840  3853 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 16:00:51.404  1352  1709 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:00:51.405  1957  2101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:00:51.405  3840  3852 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:00:51.406  1352  2080 D BluetoothPan: onBluetoothStateChange on: false
,08-30 16:00:51.407  3919  4072 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 16:00:51.407  3919  4072 D BluetoothAdapterProperties: Setting state to 16
08-30 16:00:51.407  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:00:51.407  3919  4072 D BluetoothAdapterProperties: onBleDisable
08-30 16:00:51.408  3919  4072 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:00:51.408  3919  4073 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:00:51.409  3919  4083 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 16:00:51.409  3919  4083 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 16:00:51.411  3919  4076 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:00:51.411  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:51.413  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:00:51.414  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:51.415  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:51.417  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:51.419  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:51.421  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:51.612  3919  4076 I bt_hci  : shut_down
,08-30 16:00:51.619  3919  4081 I bt_vendor: low_power_mode_cb
,08-30 16:00:51.621  3919  4081 D bt_hwcfg: hw_epilog_process
,08-30 16:00:51.639  3919  4081 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:00:51.639  3919  4081 I bt_vendor: epilog_cb
08-30 16:00:51.640  3919  4081 I bt_hci  : epilog_finished_callback
,08-30 16:00:51.644  3919  4076 I bt_hci_h4: hal_close
,08-30 16:00:51.645  3919  4076 I bt_userial_vendor: device fd = 51 close
,08-30 16:00:51.761  3919  4073 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:00:51.762  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:00:51.767  3919  3919 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:00:51.768  3919  4072 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 16:00:51.769  3919  3919 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 16:00:51.770  3919  3919 D BtGatt.GattService: stop()
,08-30 16:00:51.771  3919  3919 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:00:51.777  3919  3919 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:51.777  3919  3919 V BluetoothAdapterState: isTurningOn()=false
08-30 16:00:51.778  3919  3919 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:51.778  3919  3919 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 16:00:51.779  3919  4072 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 16:00:51.780  3919  4072 D BluetoothAdapterProperties: Setting state to 10
,08-30 16:00:51.780  3919  4072 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 16:00:51.782  3919  4072 I BluetoothAdapterState: Entering OffState
08-30 16:00:51.785   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 16:00:51.816  3919  3919 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 16:00:51.817  3919  3919 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 16:00:51.817  3919  4073 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:00:51.823  3919  4073 D bt_stack_manager: event_clean_up_stack finished.
,08-30 16:00:51.823  3919  3919 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:00:51.828  3919  3919 I art     : System.exit called, status: 0
,08-30 16:00:51.828  3919  3919 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:00:51.895   874   885 I ActivityManager: Process com.android.bluetooth (pid 3919) has died
,08-30 16:00:54.319  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:00:54.319  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:00:54.908   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 16:00:54.919  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-30 16:00:54.925   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:00:54.925   874   894 I Adreno  : Build Date                       : 10/20/15
08-30 16:00:54.925   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:00:54.925   874   894 I Adreno  : Local Branch                     : M14
08-30 16:00:54.925   874   894 I Adreno  : Remote Branch                    : 
08-30 16:00:54.925   874   894 I Adreno  : Remote Branch                    : 
08-30 16:00:54.925   874   894 I Adreno  : Reconstruct Branch               : 
,08-30 16:00:54.972   281   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (192 us)
,08-30 16:00:55.598  3770  3770 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:00:55.599  3770  3770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 16:00:55.632   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 16:00:55.635  3770  3770 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dcb36ca Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@407b1c4, 16908290=android.view.AbsSavedState$1@407b1c4}, android:focusedViewId=100}]}]
,08-30 16:00:55.635  3770  3770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-30 16:00:55.636  3770  3770 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 16:00:55.636  3770  3770 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 16:00:55.644   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 16:00:55.652   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 16:00:55.652   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-30 16:00:55.653   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 16:00:55.699   874   883 I art     : Background partial concurrent mark sweep GC freed 15535(1290KB) AllocSpace objects, 11(316KB) LOS objects, 33% free, 28MB/43MB, paused 1.088ms total 111.702ms
,08-30 16:00:55.908   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 16:00:55.912   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-30 16:00:55.912   874  1336 D SurfaceControl: Excessive delay in setPowerMode(): 261ms,
08-30 16:00:55.916   874   894 I DreamManagerService: Entering dreamland.
,08-30 16:00:55.921   874   894 I PowerManagerService: Dozing...
,08-30 16:00:55.921   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 16:00:56.000   377  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 16:00:56.001   377  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 16:00:56.011   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:00:56.025  1946  4119 D NfcService: Discovery configuration equal, not updating.
,08-30 16:00:56.028   874  1308 E native  : do suspend false
,08-30 16:00:56.057   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:00:56.061   874  1308 E native  : do suspend true
,08-30 16:00:56.132   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-30 16:00:56.132   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 16:00:57.327  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:00:57.328  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10898ad added. We now have 6 listener(s)
08-30 16:00:57.328  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:57.332  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:57.332  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fbe7e2 added. We now have 7 listener(s)
08-30 16:00:57.332  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:00:57.334  3770  3821 I System.out: IsBluetoothEnabled
,08-30 16:00:57.346  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 16:00:57.398   874   891 I ActivityManager: Start proc 4125:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 16:00:57.511  4125  4125 D AdapterServiceConfig: Adding HeadsetService
,08-30 16:00:57.511  4125  4125 D AdapterServiceConfig: Adding A2dpService
,08-30 16:00:57.512  4125  4125 D AdapterServiceConfig: Adding HidService
08-30 16:00:57.513  4125  4125 D AdapterServiceConfig: Adding HealthService
08-30 16:00:57.515  4125  4125 D AdapterServiceConfig: Adding PanService
,08-30 16:00:57.517  4125  4125 D AdapterServiceConfig: Adding GattService
,08-30 16:00:57.518  4125  4125 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:00:57.534   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b383ed2:true
,08-30 16:00:57.534  4125  4125 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 16:00:57.540  4125  4125 I bt_bluedroid: init
,08-30 16:00:57.541  4125  4137 I BluetoothAdapterState: Entering OffState
,08-30 16:00:57.544  4125  4138 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 16:00:57.544  4125  4138 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:00:57.544  4125  4138 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:00:57.544  4125  4138 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:00:57.545  4125  4125 I bt_bluedroid: get_profile_interface socket
,08-30 16:00:57.548  4125  4125 I bt_bluedroid: get_profile_interface sdp
08-30 16:00:57.549  4125  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:00:57.551  4125  4141 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:00:57.554  4125  4136 I bt_bluedroid: config_hci_snoop_log
,08-30 16:00:57.557   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 16:00:57.566  4125  4137 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:00:57.566  4125  4137 D BluetoothAdapterProperties: Setting state to 14
08-30 16:00:57.566  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-30 16:00:57.568  4125  4137 D BluetoothBondStateMachine: make
,08-30 16:00:57.572  4125  4142 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:00:57.576  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:00:57.579  4125  4125 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:00:57.586  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:57.588  4125  4125 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:00:57.589  4125  4125 D BtGatt.GattService: Received start request. Starting profile...
,08-30 16:00:57.589  4125  4125 D BtGatt.GattService: start()
08-30 16:00:57.590  4125  4125 I bt_bluedroid: get_profile_interface gatt
,08-30 16:00:57.591  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
08-30 16:00:57.591  4125  4125 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:00:57.601  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:57.601  4125  4125 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:00:57.602  4125  4125 V BluetoothAdapterState: isBleTurningOn()=true
08-30 16:00:57.602  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:57.603  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 16:00:57.603  4125  4137 I bt_bluedroid: enable
08-30 16:00:57.603  4125  4138 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 16:00:57.604  4125  4138 I bt_hci  : start_up
,08-30 16:00:57.618  4125  4138 I bt_vendor: alloc value 0xb39ee189
,08-30 16:00:57.618  4125  4138 I bt_vendor: init
08-30 16:00:57.618  4125  4138 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 16:00:57.618  4125  4138 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:00:57.727  4125  4138 D bt_hci  : start_up starting async portion
,08-30 16:00:57.728  4125  4145 I bt_hci  : event_finish_startup
,08-30 16:00:57.728  4125  4145 I bt_hci_h4: hal_open
,08-30 16:00:57.728  4125  4145 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-30 16:00:57.738  4125  4145 I bt_userial_vendor: device fd = 51 open
,08-30 16:00:57.768  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:00:57.800  4125  4145 D bt_hwcfg: Chipset BCM4354A2
,08-30 16:00:57.802  4125  4145 D bt_hwcfg: Target name = [BCM4354A2]
08-30 16:00:57.803  4125  4145 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:00:58.462  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 16:00:58.463  4125  4145 D bt_hwcfg: Settlement delay -- 100 ms
08-30 16:00:58.464  4125  4145 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:00:58.581  4125  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:00:58.582  4125  4145 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:00:58.611  4125  4145 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:00:58.612  4125  4145 I bt_vendor: firmware callback
08-30 16:00:58.612  4125  4145 I bt_hci  : firmware_config_callback
,08-30 16:00:58.624  4125  4147 I bt_btu  : btu_task pending for preload complete event
,08-30 16:00:58.624  4125  4147 I bt_btu_task: Bluetooth chip preload is complete
08-30 16:00:58.625  4125  4147 I bt_btu  : btu_task received preload complete event
,08-30 16:00:58.635  4125  4147 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 16:00:58.635  4125  4147 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:00:58.635  4125  4147 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:00:58.636  4125  4147 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 16:00:58.636  4125  4147 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:00:58.636  4125  4147 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:00:58.636  4125  4147 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 16:00:58.637  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:00:58.637  4125  4147 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:00:58.637  4125  4147 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 16:00:58.638  4125  4147 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:00:58.638  4125  4147 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:00:58.638  4125  4147 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 16:00:58.638  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:00:58.638  4125  4147 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:00:58.771  4125  4147 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396bd9d
08-30 16:00:58.771  4125  4147 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396bd9d 
,08-30 16:00:58.799  4125  4141 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:00:58.800  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:00:58.801  4125  4141 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:00:58.802  4125  4141 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 16:00:58.803  4125  4141 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:00:58.803  4125  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:00:58.803  4125  4141 D bt_hci  : do_postload posting postload work item
08-30 16:00:58.804  4125  4145 I bt_hci  : event_postload
08-30 16:00:58.804  4125  4145 I bt_vendor: sco_config_cb
08-30 16:00:58.804  4125  4145 I bt_hci  : sco_config_callback postload finished.
08-30 16:00:58.805  4125  4141 D bt_bte_conf: Device ID record 1 : primary
,08-30 16:00:58.805  4125  4141 D bt_bte_conf:   vendorId            = 000f
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   product             = 1200
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   version             = 1436
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   clientExecutableURL = 
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   serviceDescription  = 
08-30 16:00:58.805  4125  4141 D bt_bte_conf:   documentationURL    = 
08-30 16:00:58.805  4125  4141 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:00:58.805  4125  4138 D bt_stack_manager: event_start_up_stack finished
08-30 16:00:58.806  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 16:00:58.806  4125  4137 D BluetoothAdapterProperties: Setting state to 15
08-30 16:00:58.806  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:00:58.806  4125  4137 I BluetoothAdapterState: Entering BleOnState
,08-30 16:00:58.810  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:58.814  4125  4145 I bt_vendor: low_power_mode_cb
,08-30 16:00:58.814  4125  4137 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 16:00:58.814  4125  4137 D BluetoothAdapterProperties: Setting state to 11
,08-30 16:00:58.815  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 16:00:58.835  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:58.838  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
08-30 16:00:58.840  4125  4125 D HeadsetService: Received start request. Starting profile...
08-30 16:00:58.841  4125  4137 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:00:58.842  4125  4125 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:00:58.842  4125  4125 D HeadsetStateMachine: make
,08-30 16:00:58.850  4125  4125 D HeadsetStateMachine: max_hf_connections = 1
,08-30 16:00:58.850  4125  4125 I bt_bluedroid: get_profile_interface handsfree
,08-30 16:00:58.851  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:00:58.851  4125  4141 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 16:00:58.857  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:58.857  4125  4125 D A2dpService: Received start request. Starting profile...
,08-30 16:00:58.858  4125  4125 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:00:58.858  4125  4125 I bt_bluedroid: get_profile_interface avrcp
,08-30 16:00:58.864  4125  4125 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 16:00:58.864  4125  4125 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:00:58.864  4125  4125 D A2dpStateMachine: make
,08-30 16:00:58.865  4125  4125 I bt_bluedroid: get_profile_interface a2dp
,08-30 16:00:58.866  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 16:00:58.867  4125  4157 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:00:58.868  4125  4125 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 16:00:58.869  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:58.870  4125  4125 D HidService: Received start request. Starting profile...
,08-30 16:00:58.870  4125  4125 I bt_bluedroid: get_profile_interface hidhost
08-30 16:00:58.870  4125  4141 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394d3e5
08-30 16:00:58.871  4125  4141 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 16:00:58.871  4125  4125 D HidService: setHidService(): set to: null
,08-30 16:00:58.872  4125  4125 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 16:00:58.873  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:58.873  4125  4125 D HealthService: Received start request. Starting profile...
,08-30 16:00:58.875  4125  4125 I bt_bluedroid: get_profile_interface health
,08-30 16:00:58.875  4125  4125 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:00:58.876  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:58.876  4125  4125 D PanService: Received start request. Starting profile...
,08-30 16:00:58.876  4125  4125 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:00:58.876  4125  4125 I bt_bluedroid: get_profile_interface pan
,08-30 16:00:58.877  4125  4141 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:00:58.879  4125  4125 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:00:58.880  4125  4125 D BluetoothMapService: Received start request. Starting profile...
08-30 16:00:58.880  4125  4125 D BluetoothMapService: start()
08-30 16:00:58.882  4125  4125 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 16:00:58.882  4125  4125 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 16:00:58.882  4125  4125 D BluetoothMapAppObserver: createReceiver()
,08-30 16:00:58.883  4125  4125 D BluetoothMapAppObserver: initObservers()
,08-30 16:00:58.883  4125  4125 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 16:00:58.892  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:58.892  4125  4155 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:00:58.893  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:58.893  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:58.893  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:58.893  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:58.896  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isTurningOff()=false
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:58.897  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:58.898  4125  4125 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:00:58.898  4125  4125 V BluetoothAdapterState: isTurningOn()=true
08-30 16:00:58.898  4125  4125 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:00:58.898  4125  4125 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:00:58.898  4125  4137 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 16:00:58.898  4125  4137 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:00:58.898  4125  4137 D BluetoothAdapterProperties: State =  11
08-30 16:00:58.899  4125  4137 D BluetoothAdapterProperties: Setting state to 12
08-30 16:00:58.899  4125  4137 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:00:58.899  4125  4137 I BluetoothAdapterState: Entering OnState
08-30 16:00:58.900  3840  3853 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:58.900  4125  4141 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:00:58.901  4125  4141 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:00:58.901  1352  1365 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:58.903  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:58.904  1352  1709 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:00:58.905  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:58.908  3840  3852 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:00:58.908  1352  1352 D BluetoothInputDevice: Proxy object connected
08-30 16:00:58.908  1352  1352 D HidProfile: Bluetooth service connected
,08-30 16:00:58.909  4125  4125 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:00:58.910  1352  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:00:58.910  4125  4125 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 16:00:58.911   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:58.911   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:58.911   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:58.911  4125  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:58.912  3840  3853 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:00:58.913   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:58.913  4125  4125 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:00:58.913  3840  3852 D BluetoothPan: onBluetoothStateChange on: true
,08-30 16:00:58.915  4125  4125 D ObexServerSockets: Succeed to create listening sockets 
,08-30 16:00:58.915  4125  4125 D ObexServerSockets0: startAccept()
08-30 16:00:58.915  4125  4125 D ObexServerSockets0: prepareForNewConnect()
08-30 16:00:58.915  1352  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:00:58.916  3840  3853 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:00:58.917  4125  4125 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 16:00:58.917  4125  4125 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 16:00:58.919  3840  3840 D BluetoothInputDevice: Proxy object connected
08-30 16:00:58.919  4125  4162 D ObexServerSockets0: Accepting socket connection...
,08-30 16:00:58.919  3840  3840 D HidProfile: Bluetooth service connected
08-30 16:00:58.919  1352  2080 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:00:58.919  1352  1352 D BluetoothA2dp: Proxy object connected
08-30 16:00:58.920   874   874 D BluetoothA2dp: Proxy object connected
,08-30 16:00:58.921  3840  3840 D BluetoothMap: Proxy object connected
,08-30 16:00:58.921  3840  3840 D MapProfile: Bluetooth service connected
08-30 16:00:58.922  3840  3840 D BluetoothMap: getConnectedDevices()
,08-30 16:00:58.922  1352  1352 D BluetoothMap: Proxy object connected
,08-30 16:00:58.922  1352  1352 D MapProfile: Bluetooth service connected
08-30 16:00:58.922  1352  1352 D BluetoothMap: getConnectedDevices()
,08-30 16:00:58.923  1957  1983 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:00:58.923  3840  3840 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:00:58.923  3840  3840 D PanProfile: Bluetooth service connected
08-30 16:00:58.924  3840  3853 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:00:58.924  4125  4163 D ObexServerSockets0: Accepting socket connection...
08-30 16:00:58.925  3840  3840 D BluetoothA2dp: Proxy object connected
08-30 16:00:58.925  1352  1375 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:00:58.926  1352  1352 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:00:58.926  1352  1352 D PanProfile: Bluetooth service connected
,08-30 16:00:58.927   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 16:00:58.929  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:00:58.929  4125  4125 D BluetoothMapService: onReceive
08-30 16:00:58.930  4125  4125 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:00:58.930  4125  4125 D BluetoothMapService: STATE_ON
,08-30 16:00:58.933  3840  3840 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:00:58.937  3840  3840 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:00:58.939  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:00:58.952  1352  1352 D BluetoothPbap: Proxy object connected
,08-30 16:00:58.952  1352  1352 D PbapServerProfile: Bluetooth service connected
08-30 16:00:58.952  3840  3840 D BluetoothPbap: Proxy object connected
08-30 16:00:58.952  3840  3840 D PbapServerProfile: Bluetooth service connected
,08-30 16:00:58.958  4125  4125 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:00:58.958  4125  4125 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:00:58.960  4125  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:58.975  4125  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:00:58.976  4125  4172 I BtOppRfcommListener: Accept thread started.
,08-30 16:00:59.002   874   874 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.002   874   874 D BluetoothHeadset: Proxy object connected
08-30 16:00:59.002  1957  2101 D BluetoothHeadset: Proxy object connected
08-30 16:00:59.003   874   874 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.003  1352  1709 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.003  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-30 16:00:59.004  3840  4164 D BluetoothHeadset: Proxy object connected
08-30 16:00:59.005  3840  3840 D HeadsetProfile: Bluetooth service connected
,08-30 16:00:59.011   874   891 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.012   874   891 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.013   874   891 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.016  1352  2080 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.016  1352  1352 D HeadsetProfile: Bluetooth service connected
,08-30 16:00:59.024  1957  2191 D BluetoothHeadset: Proxy object connected
,08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:59.370  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:59.377  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:59.380  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:00:59.380  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b4c773 added. We now have 8 listener(s)
,08-30 16:00:59.381  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:00:59.386   874  1686 D WifiService: setWifiEnabled: false pid=3770, uid=10000
08-30 16:00:59.386   874  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:00:59.398  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:00:59.399   874  1395 D WifiService: setWifiEnabled: true pid=3770, uid=10000
08-30 16:00:59.399   874  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:00:59.417   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:00:59.428  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:00:59.436  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:00:59.447   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:00:59.449   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 16:00:59.450   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:00:59.451   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 16:00:59.452   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 16:00:59.452   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 16:00:59.452   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 16:00:59.462   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.07 delta 1000 -> 1000
,08-30 16:00:59.463   874  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 16:00:59.463   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:00:59.465   373   872 D CommandListener: Setting iface cfg
,08-30 16:00:59.474   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 16:00:59.474   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 16:00:59.474   874  1308 E native  : do suspend true
,08-30 16:00:59.490   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 16:00:59.490   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:00:59.501   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:00:59.540   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 16:00:59.540   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:00:59.576   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:00:59.578  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:01:00.052  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:01:00.104  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:01:00.105  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 16:01:00.109   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:01:00.129   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:01:00.131   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:01:00.131   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 16:01:00.149   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:01:00.167   373   872 D CommandListener: Setting iface cfg
,08-30 16:01:00.168   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 16:01:00.178   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 16:01:00.213   874  4180 D DhcpClient: Receive thread started
,08-30 16:01:00.302   874  1308 E native  : do suspend false
,08-30 16:01:00.323   874  2079 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:01:00.345   874  4180 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-30 16:01:00.346   874  2079 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-30 16:01:00.349   874  2079 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:01:00.366   874  4180 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:01:00.367   874  2079 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:01:00.372   373   872 D CommandListener: Setting iface cfg
,08-30 16:01:00.382   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:01:00.383   874  2079 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:01:00.388   874  1308 E native  : do suspend true
,08-30 16:01:00.407   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:01:00.410   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:01:00.412   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:01:00.413   874  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:01:00.416  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:01:00.419  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:01:00.424  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 16:01:00.424   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 16:01:00.424  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 16:01:00.427  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dcb36ca Bundle[{}]
,08-30 16:01:00.428  3770  3821 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:01:00.428  3770  3821 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:01:00.428  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:01:00.429  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 16:01:00.430  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 16:01:00.430  3770  3821 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 16:01:00.434  3770  3821 I System.out: Running OutgoingSocketThread
08-30 16:01:00.435  3770  4182 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 412)
,08-30 16:01:00.436  3770  4182 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42292
08-30 16:01:00.436  3770  4182 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 16:01:00.464   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:01:00.464   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 16:01:00.466   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 16:01:00.468   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 16:01:00.469   874  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 16:01:00.479   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 16:01:00.483   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 16:01:00.483   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 16:01:00.483   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 16:01:00.483   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 16:01:00.484   874  1310 D ConnectivityService:    accepting network in place of null
08-30 16:01:00.484   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:01:00.485   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:01:00.498   874  4179 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155501, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:01:00.517   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:01:00.572   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:01:00.584   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 16:01:00.585   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:01:00.594   874  4178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 16:01:00.598   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:01:00.599   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102],
,08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:00.614  3770  3770 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:00.618  3770  3770 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:01:00.625  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-30 16:01:00.631  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:01:00.639  1717  1717 D SystemUpdateService: onCreate
,08-30 16:01:00.643  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:01:00.660  1717  4190 I SystemUpdateService: active receiver: enabled
,08-30 16:01:00.663   874  4178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:01:00 GMT], X-Android-Received-Millis=[1472565660662], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472565660635]}
,08-30 16:01:00.664   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 16:01:00.664   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 16:01:00.664   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 16:01:00.665   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:01:00.669  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 16:01:00.678  1717  2517 I iu.UploadsManager: num queued entries: 0
,08-30 16:01:00.678  1717  2517 I iu.UploadsManager: num updated entries: 0
08-30 16:01:00.679  1717  2517 I iu.SyncManager: NEXT; no task
,08-30 16:01:00.681  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:01:00.682  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:01:00.684  3933  3933 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:01:00.689  3933  3933 D SprintDMHelper: simOperator: 
,08-30 16:01:00.689  3933  3933 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:01:00.691  1717  4194 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 16:01:00.691  1717  4194 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 16:01:00.692  1717  4194 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:01:00.695  1717  4190 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:01:00.703  1717  4190 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 16:01:00.703  1717  4190 I SystemUpdateService: now status is 0 (complete)
08-30 16:01:00.703  1717  4190 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:01:00.703  1717  4190 I SystemUpdateService: file has been verified
08-30 16:01:00.703  1717  4190 I SystemUpdateService: OTA package size = 12249756
,08-30 16:01:00.708  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-30 16:01:00.713  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:01:00.728  1717  4190 I SystemUpdateService: showing system update notification
,08-30 16:01:00.763  1717  1717 D SystemUpdateService: onDestroy
,08-30 16:01:00.766  1509  2999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 16:01:00.767  1509  2999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 16:01:00.767  1509  2999 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:01:00.767  1509  2999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:01:00.791  1717  4194 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-30 16:01:00.823  2179  4197 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:01:01.438  3770  3821 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 413)
,08-30 16:01:01.438  3770  3821 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 413)
,08-30 16:01:01.447  3770  3821 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,08-30 16:01:01.450  3770  3821 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-30 16:01:01.450  3770  3821 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 419)
,08-30 16:01:01.456  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:01:01.456  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb02630 added. We now have 2 listener(s)
,08-30 16:01:01.458  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.458  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.458  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:01:01.458  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.458  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c312a9 added. We now have 9 listener(s)
08-30 16:01:01.458  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:01:01.459  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:01:01.463  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:01.471  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:01.475  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.475  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:01:01.475  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.475  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0a67cf added. We now have 3 listener(s)
08-30 16:01:01.477  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:01:01.477  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.478  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.478  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.478  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@829755c added. We now have 10 listener(s)
08-30 16:01:01.478  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.478  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:01.478  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:01.478  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:01:01.478  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.478  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.479  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.479  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.479  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb02630 removed from the list
08-30 16:01:01.479  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.479  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c312a9 removed from the list
08-30 16:01:01.481  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.481  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:01.481  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:01.484  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.484  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:01.486  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:01.486  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.486  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.486  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c312a9 not in the list
,08-30 16:01:01.486  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.486  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.489  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:01.490  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.490  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:01.490  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.491  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@829755c removed from the list
08-30 16:01:01.492  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:01:01.492  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.493  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:01.493  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.494  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0a67cf removed from the list
,08-30 16:01:01.498  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:01:01.498  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c913065 added. We now have 2 listener(s)
,08-30 16:01:01.503  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.503  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.504  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.504  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:01:01.505  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae913a added. We now have 9 listener(s)
08-30 16:01:01.505  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:01:01.506  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:01:01.512  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:01.524  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:01.530  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:01:01.530  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:01:01.531  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.531  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a868b48 added. We now have 3 listener(s)
,08-30 16:01:01.538  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.538  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:01:01.538  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:01.538  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:01:01.539  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.539  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b696de1 added. We now have 10 listener(s)
,08-30 16:01:01.540  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.540  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:01:01.541  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:01:01.541  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:01:01.541  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:01.542  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:01:01.546  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:01.550  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:01:01.551  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:01:01.559  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:01:01.560  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:01:01.560  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:01:01.564  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:01:01.564  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:01:01.564  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:01:01.565  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.569  4125  4152 D BtGatt.GattService: registerClient() - UUID=58139f35-f563-4ac2-88e9-7020beafd7c7
,08-30 16:01:01.570  4125  4141 D BtGatt.GattService: onClientRegistered() - UUID=58139f35-f563-4ac2-88e9-7020beafd7c7, clientIf=5
,08-30 16:01:01.571  3770  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:01:01.572  4125  4154 D BtGatt.GattService: start scan with filters
,08-30 16:01:01.576  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:01:01.577  4125  4144 D BtGatt.ScanManager: handling starting scan
08-30 16:01:01.577  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:01:01.577  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:01:01.577  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:01:01.581  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:01:01.581  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:01:01.581  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:01:01.581  4125  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4af0cbe
,08-30 16:01:01.583  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 16:01:01.583   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 16:01:01.585  3770  3821 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:01:01.586  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:01:01.586  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:01:01.586  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.586  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:01:01.586  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 16:01:01.586  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:01:01.586  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:01:01.586  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 16:01:01.586  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:01:01.586  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:01:01.587  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.588  4125  4136 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:01:01.589  4125  4141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:01:01.590  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.590  4125  4135 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:01:01.590  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:01:01.590  4125  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:01:01.591  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:01:01.591  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 16:01:01.592  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:01:01.592  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:01:01.596  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:01:01.596  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:01:01.597  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:01:01.597  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:01:01.597  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:01:01.597  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.598  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.598  4125  4144 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:01:01.599  4125  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:01:01.601  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:01:01.601  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:01:01.601  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:01:01.608  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:01:01.608  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:01.609  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:01:01.610  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.610  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:01.610  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.611  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.611  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c913065 removed from the list
08-30 16:01:01.611  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.612  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae913a removed from the list
08-30 16:01:01.612  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:01.612  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:01.613  4125  4141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:01:01.613  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.613  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:01.614  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:01:01.615  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:01.615  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.615  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.616  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae913a not in the list
08-30 16:01:01.616  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:01.616  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.617  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:01:01.617  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:01.617  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:01:01.617  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b696de1 removed from the list
08-30 16:01:01.617  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.617  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.617  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.617  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.617  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a868b48 removed from the list
08-30 16:01:01.618  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.618  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72e071d added. We now have 2 listener(s)
,08-30 16:01:01.620  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.621  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.621  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.621  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.621  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2320d92 added. We now have 9 listener(s)
08-30 16:01:01.621  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:01:01.621  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:01:01.621  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.622  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:01:01.625  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:01.629  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:01.631  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:01:01.631  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.631  4125  4144 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:01:01.632  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.632  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:01:01.633  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:01:01.633  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f17b60 added. We now have 3 listener(s)
08-30 16:01:01.634  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.635  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:01:01.635  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.635  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.636  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.636  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a8f819 added. We now have 10 listener(s)
08-30 16:01:01.636  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.636  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:01.637  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.637  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:01.637  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:01:01.637  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:01:01.637  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.637  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:01:01.637  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:01.637  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:01:01.638  4125  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:01:01.640  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 16:01:01.640  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:01:01.644  4125  4141 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 16:01:01.644  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.645  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:01:01.646  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:01:01.646  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:01:01.649  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:01:01.649  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:01:01.649  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:01:01.650  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.652  4125  4154 D BtGatt.GattService: registerClient() - UUID=d4fd0a13-39a5-4af5-914e-82e4b4abffba
,08-30 16:01:01.652  4125  4141 D BtGatt.GattService: onClientRegistered() - UUID=d4fd0a13-39a5-4af5-914e-82e4b4abffba, clientIf=5
08-30 16:01:01.653  3770  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:01:01.653  4125  4152 D BtGatt.GattService: start scan with filters
,08-30 16:01:01.656  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:01:01.656  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:01:01.656  4125  4144 D BtGatt.ScanManager: handling starting scan
08-30 16:01:01.656  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:01:01.656  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:01:01.659  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:01:01.659  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:01:01.659  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:01:01.661  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:01:01.664  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:01.664  3770  3821 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 16:01:01.664  4125  4141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:01:01.664  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:01.664  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.664  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:01.665  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:01.665  4125  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 16:01:01.665  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.665  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:01.665  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:01:01.665  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.665  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72e071d removed from the list
,08-30 16:01:01.665  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:01:01.665  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2320d92 removed from the list
,08-30 16:01:01.665  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:01.665  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.666  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.666  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:01:01.666  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:01:01.666  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.667  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:01.667  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.668  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:01:01.668  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2320d92 not in the list
,08-30 16:01:01.668  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:01:01.668  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:01:01.668  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:01:01.668  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:01:01.668  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:01:01.669  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.669  4125  4135 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:01:01.670  4125  4136 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:01:01.671  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:01:01.671  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:01:01.671  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 16:01:01.671  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:01:01.671  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:01:01.672  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:01:01.672  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:01:01.672  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:01:01.673  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:01:01.673  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:01:01.673  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.673  4125  4144 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:01:01.673  4125  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:01:01.674  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.675  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.675  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:01.675  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:01:01.675  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a8f819 removed from the list
08-30 16:01:01.675  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.675  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.675  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.675  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.675  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f17b60 removed from the list
08-30 16:01:01.676  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.676  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@947fcd5 added. We now have 2 listener(s)
08-30 16:01:01.677  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:01:01.677  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:01:01.677  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:01:01.679  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.679  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.679  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.680  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:01:01.680  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46dbcea added. We now have 9 listener(s)
08-30 16:01:01.680  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.681  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:01:01.684  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:01.688  4125  4141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:01:01.688  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:01.689  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:01.691  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.691  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:01.692  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.692  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8975678 added. We now have 3 listener(s)
08-30 16:01:01.694  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.694  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:01:01.694  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.694  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.694  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.695  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d989151 added. We now have 10 listener(s)
,08-30 16:01:01.695  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.695  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:01.695  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:01:01.695  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:01:01.696  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:01:01.696  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:01:01.696  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:01:01.696  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.696  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.699  3770  3821 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 16:01:01.699  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:01:01.704  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:01:01.704  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.704  4125  4144 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:01:01.708  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:01:01.709  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:01:01.709  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:01:01.711  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:01:01.711  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.711  4125  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:01:01.713  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:01:01.713  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:01:01.713  3770  3821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:01:01.714  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.718  4125  4154 D BtGatt.GattService: registerClient() - UUID=c8f19a34-8ebf-4bc2-9c93-95126bb6a633
,08-30 16:01:01.718  4125  4141 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:01:01.718  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.718  4125  4141 D BtGatt.GattService: onClientRegistered() - UUID=c8f19a34-8ebf-4bc2-9c93-95126bb6a633, clientIf=5
08-30 16:01:01.719  3770  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:01:01.719  4125  4152 D BtGatt.GattService: start scan with filters
,08-30 16:01:01.722  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:01:01.722  4125  4144 D BtGatt.ScanManager: handling starting scan
08-30 16:01:01.722  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:01:01.722  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:01:01.723  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 16:01:01.727  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:01:01.728  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:01:01.729  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:01:01.730  4125  4141 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:01:01.730  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.730  4125  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:01:01.734  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:01:01.737  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 16:01:01.737  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.737  4125  4144 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:01:01.737  4125  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:01:01.742  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:01:01.742  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:01:01.742  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:01.742  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.743  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.743  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:01:01.743  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:01:01.743  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@947fcd5 removed from the list
08-30 16:01:01.743  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.743  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46dbcea removed from the list
08-30 16:01:01.743  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:01:01.744  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:01:01.749  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.749  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:01:01.750  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.750  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:01:01.751  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:01.751  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.751  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.752  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46dbcea not in the list
,08-30 16:01:01.752  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:01:01.752  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:01:01.752  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:01:01.752  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:01:01.753  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:01:01.754  3770  3821 D BluetoothAdapter: STATE_ON
,08-30 16:01:01.754  4125  4152 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:01:01.755  4125  4135 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:01:01.757  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:01:01.757  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:01:01.758  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:01:01.758  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 16:01:01.758  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:01:01.760  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:01:01.760  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:01:01.760  3770  3821 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:01:01.761  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 16:01:01.761  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.762  4125  4141 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:01:01.762  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.763  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:01:01.763  3770  3770 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:01:01.764  3770  3770 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:01:01.764  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:01:01.764  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:01.764  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:01:01.764  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d989151 removed from the list
08-30 16:01:01.764  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.765  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.765  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.765  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:01:01.765  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8975678 removed from the list
08-30 16:01:01.766  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.766  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@383f18d added. We now have 2 listener(s)
,08-30 16:01:01.770  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:01:01.770  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.770  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:01:01.770  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:01:01.770  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ff42 added. We now have 9 listener(s)
08-30 16:01:01.771  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.771  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:01:01.775  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:01:01.776  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:01:01.776  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:01:01.779  3770  3821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:01:01.781  3770  3821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:01:01.782  3770  3821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:01:01.783  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:01:01.784  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8a7c90 added. We now have 3 listener(s)
,08-30 16:01:01.784  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:01:01.785  4125  4141 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:01:01.786  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.786  4125  4144 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:01:01.787  3770  3770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:01:01.787  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:01:01.787  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:01:01.787  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:01:01.788  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:01:01.788  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64b1989 added. We now have 10 listener(s)
08-30 16:01:01.788  3770  3821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:01:01.788  3770  3821 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:01:01.788  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:01:01.788  3770  3821 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:01:01.788  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.788  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.788  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:01:01.789  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.789  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@383f18d removed from the list
08-30 16:01:01.789  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.789  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ff42 removed from the list
,08-30 16:01:01.789  3770  3821 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:01:01.789  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.789  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.790  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.791  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:01:01.791  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:01:01.791  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.791  3770  3821 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d4ff42 not in the list
08-30 16:01:01.791  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.791  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.792  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:01:01.792  4125  4141 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:01:01.792  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:01:01.792  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.792  3770  3821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:01:01.792  3770  3821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64b1989 removed from the list
,08-30 16:01:01.792  3770  3821 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:01:01.792  4125  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:01:01.792  3770  3821 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:01:01.792  3770  3821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:01:01.792  3770  3821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:01:01.792  3770  3821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8a7c90 removed from the list
08-30 16:01:01.793  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 16:01:01.794  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:01:01.794  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 16:01:01.794  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:01:01.794  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 16:01:01.794  3770  3821 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:01:01.799  4125  4141 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:01:01.799  4125  4141 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:01:01.802  3770  4203 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: My test thread name)
08-30 16:01:01.802  3770  4203 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: My test thread name)
08-30 16:01:01.802  3770  4203 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 16:01:01.804  3770  4204 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: My test thread name)
,08-30 16:01:01.804  3770  4204 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: My test thread name)
08-30 16:01:01.804  3770  4204 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 16:01:01.806  3770  3821 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 16:01:01.806  3770  3821 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-30 16:01:01.806  3770  3821 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 16:01:01.806  3770  3821 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 16:01:01.806  3770  3821 D com.test.thalitest.ThaliTestRunner: Total duration: 22986 ms
,08-30 16:01:01.808  3770  3821 I jxcore-log: *Native tests were executed*
08-30 16:01:01.808  3770  3821 I jxcore-log: 
,08-30 16:01:01.808  3770  3821 I jxcore-log: Total number of executed tests:  80
08-30 16:01:01.808  3770  3821 I jxcore-log: 
08-30 16:01:01.808  3770  3821 I jxcore-log: Number of passed tests:  80
08-30 16:01:01.808  3770  3821 I jxcore-log: 
08-30 16:01:01.808  3770  3821 I jxcore-log: Number of failed tests:  0
08-30 16:01:01.808  3770  3821 I jxcore-log: 
08-30 16:01:01.808  3770  3821 I jxcore-log: Number of ignored tests:  0
08-30 16:01:01.808  3770  3821 I jxcore-log: 
,08-30 16:01:01.809  3770  3821 I jxcore-log: Total duration:  22986
08-30 16:01:01.809  3770  3821 I jxcore-log: 
08-30 16:01:01.809  3770  3821 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 16:01:01.809  3770  3821 I jxcore-log: 
,08-30 16:01:01.816  3770  3770 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 16:01:01.817  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.817  3770  3821 I jxcore-log: 
08-30 16:01:01.820  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.820  3770  3821 I jxcore-log: 
08-30 16:01:01.821  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.821  3770  3821 I jxcore-log: 
08-30 16:01:01.823  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.823  3770  3821 I jxcore-log: 
08-30 16:01:01.828  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.828  3770  3821 I jxcore-log: 
,08-30 16:01:01.830  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.830  3770  3821 I jxcore-log: 
,08-30 16:01:01.832  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.832  3770  3821 I jxcore-log: 
,08-30 16:01:01.834  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.834  3770  3821 I jxcore-log: 
,08-30 16:01:01.835  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.835  3770  3821 I jxcore-log: 
08-30 16:01:01.836  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:01:01.836  3770  3821 I jxcore-log: 
,08-30 16:01:01.838  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:01:01.838  3770  3821 I jxcore-log: 
,08-30 16:01:01.839  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:01:01.839  3770  3821 I jxcore-log: 
,08-30 16:01:01.840  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.840  3770  3821 I jxcore-log: 
,08-30 16:01:01.841  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.841  3770  3821 I jxcore-log: 
,08-30 16:01:01.842  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.842  3770  3821 I jxcore-log: 
,08-30 16:01:01.842  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.842  3770  3821 I jxcore-log: 
,08-30 16:01:01.844  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.844  3770  3821 I jxcore-log: 
,08-30 16:01:01.844  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.844  3770  3821 I jxcore-log: 
,08-30 16:01:01.845  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.845  3770  3821 I jxcore-log: 
,08-30 16:01:01.846  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.846  3770  3821 I jxcore-log: 
,08-30 16:01:01.847  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.847  3770  3821 I jxcore-log: 
,08-30 16:01:01.848  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:01:01.848  3770  3821 I jxcore-log: 
,08-30 16:01:01.849  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:01:01.849  3770  3821 I jxcore-log: 
,08-30 16:01:01.850  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:01:01.850  3770  3821 I jxcore-log: 
,08-30 16:01:01.851  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.851  3770  3821 I jxcore-log: 
,08-30 16:01:01.851  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.851  3770  3821 I jxcore-log: 
,08-30 16:01:01.852  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.852  3770  3821 I jxcore-log: 
,08-30 16:01:01.853  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.853  3770  3821 I jxcore-log: 
,08-30 16:01:01.854  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.854  3770  3821 I jxcore-log: 
,08-30 16:01:01.855  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:01:01.855  3770  3821 I jxcore-log: 
,08-30 16:01:01.937  1863  2675 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 16:01:02.101  3770  3770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:01:02.104  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:01:02.104  3770  3821 I jxcore-log: 
,08-30 16:01:02.178  3770  3770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:01:02.181  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:01:02.181  3770  3821 I jxcore-log: 
,08-30 16:01:02.264  3770  3770 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:01:02.268  3770  3821 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:01:02.268  3770  3821 I jxcore-log: 
,08-30 16:01:02.462  4205  4205 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 16:01:02.467  4205  4205 D AndroidRuntime: CheckJNI is OFF
,08-30 16:01:02.509  4205  4205 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 16:01:02.558  4205  4205 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 16:01:02.581  4205  4205 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 16:01:02.594   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 16:01:02.595   874   887 I ActivityManager: Killing 3770:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 16:01:02.720   874  1395 I WindowState: WIN DEATH: Window{46f5d40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 16:01:02.720   874  1309 D WifiService: Client connection lost with reason: 4
,08-30 16:01:02.721   874   885 D GraphicsStats: Buffer count: 2
,08-30 16:01:02.747   874   898 W PackageSettings: Skipping PackageSetting{32a6a53 com.example.hello/10273} due to missing metadata
,08-30 16:01:02.776   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 16:01:02.777   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 16:01:02.777   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-30 16:01:02.777   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 16:01:02.777   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:02.777   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:02.777   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:01:02.777   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:01:02.778   874   887 I ActivityManager:   Force finishing activity ActivityRecord{c766b61 u0 com.test.thalitest/.MainActivity t2}
,08-30 16:01:02.781   874  2184 W ActivityManager: Spurious death for ProcessRecord{2d3fb8f 0:com.test.thalitest/u0a0}, curProc for 3770: null
,08-30 16:01:02.782   874   898 I art     : Starting a blocking GC Explicit
,08-30 16:01:02.818   874   898 I art     : Explicit concurrent mark sweep GC freed 13568(951KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 681us total 35.512ms
,08-30 16:01:02.848   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 16:01:02.852   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 16:01:02.852  4205  4205 I art     : System.exit called, status: 0
08-30 16:01:02.852  4205  4205 I AndroidRuntime: VM exiting with result code 0.
,08-30 16:01:02.883   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 16:01:02.886  4125  4125 D BluetoothMapAppObserver: onReceive
08-30 16:01:02.887  4125  4125 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 16:01:02.892  3608  3608 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-30 16:01:02.892  1894  1894 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 16:01:02.895  1863  2234 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 16:01:02.897   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 16:01:02.899  1894  4216 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 16:01:02.936   874  2199 I ActivityManager: Start proc 4219:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 16:01:02.941  1957  1957 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 16:01:02.948  1894  4216 I Decoder : createOrResetDecoder
,08-30 16:01:02.960  1509  1509 I ConfigService: onCreate
,08-30 16:01:02.978  4219  4219 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 16:01:02.981  1894  4216 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 16:01:03.004   874  2184 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3770 uid 10000
,08-30 16:01:03.005  1894  1894 I Keyboard.Facilitator: onFinishInput()
,08-30 16:01:03.013  1894  4216 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111,
,08-30 16:01:03.016  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 16:01:03.016  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 16:01:03.018  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-30 16:01:03.019  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 16:01:03.021  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 16:01:03.021  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 16:01:03.022  1894  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 16:01:03.022  1894  4216 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 16:01:03.022  1894  4216 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 16:01:03.022  1894  4216 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 16:01:03.022  1894  4216 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 16:01:03.022  1894  4216 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 16:01:03.024   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 16:01:03.041  1978  2070 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-30 16:01:03.042   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 16:01:03.043   874   886 E PackageManager: Failed to write settings, restoring backup
08-30 16:01:03.043   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 16:01:03.043   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 16:01:03.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 16:01:03.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 16:01:03.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 16:01:03.043   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.043   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.043   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:01:03.048   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 16:01:03.048   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:01:03.048   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:01:03.048   874   887 E DropBoxManagerService: 	... 13 more
,08-30 16:01:03.054   874  1975 I ActivityManager: Start proc 4236:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 16:01:03.055  1978  2070 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 16:01:03.055  1978  2070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1978
08-30 16:01:03.055  1978  2070 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.055  1978  2070 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:01:03.058   874  4241 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:01:03.058   874  4241 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:01:03.058   874  4241 E DropBoxManagerService: 	... 5 more
,08-30 16:01:03.059   874  1956 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 16:01:03.064  1978  2070 I Process : Sending signal. PID: 1978 SIG: 9
,08-30 16:01:03.074  4219  4219 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 16:01:03.104   874  1686 I ActivityManager: Start proc 4251:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 16:01:03.111  4219  4250 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 16:01:03.139  4219  4250 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.139  4219  4250 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:01:03.141  4219  4250 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 16:01:03.141  4219  4250 E AndroidRuntime: Process: android.process.acore, PID: 4219
08-30 16:01:03.141  4219  4250 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.141  4219  4250 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:01:03.143   874  4264 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:01:03.143   874  4264 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:01:03.143   874  4264 E DropBoxManagerService: 	... 5 more
,08-30 16:01:03.144  4219  4250 I Process : Sending signal. PID: 4219 SIG: 9
,08-30 16:01:03.149  4251  4251 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 16:01:03.167  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 16:01:03.168  1509  1509 D AndroidRuntime: Shutting down VM
,08-30 16:01:03.169   279   279 E lowmemorykiller: Error writing /proc/4219/oom_score_adj; errno=22
,08-30 16:01:03.170  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:01:03.170  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
08-30 16:01:03.170  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 16:01:03.170  1509  1509 E AndroidRuntime: 	... 8 more
,08-30 16:01:03.173   874   884 D GraphicsStats: Buffer count: 1
,08-30 16:01:03.173   874  1975 I WindowState: WIN DEATH: Window{6fe1fdf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 16:01:03.176   874  4267 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:01:03.176   874  4267 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:01:03.176   874  4267 E DropBoxManagerService: 	... 5 more
,08-30 16:01:03.179   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1978) has died
,08-30 16:01:03.180   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 16:01:03.181   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 16:01:03.183   279   279 E lowmemorykiller: Error writing /proc/4219/oom_score_adj; errno=22
,08-30 16:01:03.202   874   887 I ActivityManager: Start proc 4270:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 16:01:03.203  1509  1509 I Process : Sending signal. PID: 1509 SIG: 9
08-30 16:01:03.203   279   279 E lowmemorykiller: Error writing /proc/4219/oom_score_adj; errno=22
08-30 16:01:03.216   279   279 E lowmemorykiller: Error writing /proc/4219/oom_score_adj; errno=22
,08-30 16:01:03.229   874  1380 I ActivityManager: Killing 3661:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 16:01:03.245   874  1309 D WifiService: Client connection lost with reason: 4
,08-30 16:01:03.248   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-30 16:01:03.296   874   885 I ActivityManager: Process com.google.process.gapps (pid 1509) has died
,08-30 16:01:03.297   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-30 16:01:03.297   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-30 16:01:03.297   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
08-30 16:01:03.297   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
08-30 16:01:03.304   874  2199 I ActivityManager: Process android.process.acore (pid 4219) has died
08-30 16:01:03.304   874  2199 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40992ms
08-30 16:01:03.321  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-30 16:01:03.329  4270  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:01:03.329  4270  4270 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:01:03.329  4270  4270 D AndroidRuntime: Shutting down VM
08-30 16:01:03.329   874  2199 I ActivityManager: Start proc 4283:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-30 16:01:03.342  4270  4270 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:01:03.342  4270  4270 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4270
08-30 16:01:03.342  4270  4270 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:01:03.342  4270  4270 E AndroidRuntime: 	... 10 more
08-30 16:01:03.345   874   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:01:03.348  4270  4270 I Process : Sending signal. PID: 4270 SIG: 9
08-30 16:01:03.349   874  4295 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:01:03.349   874  4295 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:01:03.349   874  4295 E DropBoxManagerService: 	... 5 more
08-30 16:01:03.357   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
