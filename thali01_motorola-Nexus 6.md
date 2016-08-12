#### Test 7976383092ab77f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 17:39:44.678  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:44.690  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 17:39:44.693  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 17:39:44.752  1509  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 17:39:44.752  1509  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 17:39:44.753  1509  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:39:44.753  1509  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 17:39:44.812  3497  3497 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 17:39:44.814  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 17:39:44.815  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-12 17:39:45.409  3804  3804 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 17:39:45.413  3804  3804 D AndroidRuntime: CheckJNI is OFF
08-12 17:39:45.449  3804  3804 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 17:39:45.514  3804  3804 I Radio-JNI: register_android_hardware_Radio DONE
08-12 17:39:45.542  3804  3804 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 17:39:45.547   872  1924 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:39:45.589  1990  2009 W SearchService: Abort, client detached.
08-12 17:39:45.593  3804  3804 D AndroidRuntime: Shutting down VM
08-12 17:39:45.598  1990  1990 I HotwordDetector: Closing mic
08-12 17:39:45.598  1990  2338 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d619961
08-12 17:39:45.598  1990  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 17:39:45.613   872   882 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 17:39:45.650   376  2350 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 17:39:45.652   376  2350 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 17:39:45.659   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 17:39:45.661  1990  2346 I MicroRecognitionRnrImpl: Detection finished
08-12 17:39:45.661  1990  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 17:39:45.686  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 17:39:45.711  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 17:39:45.718  3815  3815 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9606-9609)
08-12 17:39:45.718  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:39:45.730  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c336d6}
08-12 17:39:45.731  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:39:45.731  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:39:45.735  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 17:39:45.737  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 17:39:45.748  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 17:39:45.757  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:39:45.757  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:39:45.757  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 17:39:45.757  3815  3815 I Adreno  : Build Date                       : 10/20/15
08-12 17:39:45.757  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 17:39:45.757  3815  3815 I Adreno  : Local Branch                     : M14
08-12 17:39:45.757  3815  3815 I Adreno  : Remote Branch                    : 
08-12 17:39:45.757  3815  3815 I Adreno  : Remote Branch                    : 
08-12 17:39:45.757  3815  3815 I Adreno  : Reconstruct Branch               : 
08-12 17:39:45.833   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bd72d03:true
,08-12 17:39:45.860  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 17:39:45.873  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 17:39:45.932  3815  3854 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 17:39:45.945  3815  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 17:39:45.985  3815  3854 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 17:39:46.041   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +445ms
,08-12 17:39:46.046  1852  1852 I Keyboard.Facilitator: onFinishInput()
,08-12 17:39:46.165  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,08-12 17:39:46.277  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:39:46.435   872  1363 I ActivityManager: Killing 3061:com.google.android.talk/u0a61 (adj 15): empty #17
,08-12 17:39:46.484   872  1363 I ActivityManager: Killing 2960:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-12 17:39:46.638  3815  3856 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681655504
,08-12 17:39:46.652  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:39:46.652  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:39:46.652  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:39:46.652  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:39:46.652  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 17:39:46.653  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9115a7a added. We now have 1 listener(s)
,08-12 17:39:46.658  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 17:39:46.659  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 17:39:46.660  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:39:46.660  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 17:39:46.664  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4cb821 added. We now have 1 listener(s)
08-12 17:39:46.664  3815  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 17:39:46.668   872  1308 D WifiService: New client listening to asynchronous messages
,08-12 17:39:46.668  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 17:39:46.668  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:39:46.669  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:39:46.669  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 17:39:46.669  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 17:39:46.676  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 17:39:46.676  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 17:39:46.684  3815  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:39:46.684  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:39:46.684  3815  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 17:39:46.684  3815  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 17:39:46.685  3815  3856 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 17:39:46.686  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 17:39:46.688  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 17:39:46.713  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:39:47.546   872  1866 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 17:39:47.745  3815  3864 W jxcore-log: Initializing JXcore engine,
08-12 17:39:47.745  3815  3864 W jxcore-log: JXcore engine is ready
,08-12 17:39:47.788  3864  3864 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8836 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-12 17:39:47.788  3864  3864 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10094]" dev="sockfs" ino=10094 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 17:39:47.788  3864  3864 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-12 17:39:47.788  3864  3864 W Thread-333: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23148]" dev="sockfs" ino=23148 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 17:39:47.804  3815  3864 W jxcore-log: Starting JXcore engine
,08-12 17:39:47.892  3815  3864 W jxcore-log: Platform android
08-12 17:39:47.892  3815  3864 W jxcore-log: 
,08-12 17:39:47.892  3815  3864 W jxcore-log: Process ARCH arm
08-12 17:39:47.892  3815  3864 W jxcore-log: 
,08-12 17:39:48.054  3815  3864 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:39:48.054  3815  3864 I jxcore-log: 
,08-12 17:39:48.055  3815  3864 W jxcore-log: JXcore engine is started
,08-12 17:39:48.066  3815  3856 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 17:39:48.070  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 17:39:48.796   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 17:39:53.637  3588  3871 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 17:39:53.677  3588  3872 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 17:39:53.689  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:53.691  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:53.718  1509  2208 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 17:39:53.718  1509  2208 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 17:39:53.718  1509  2208 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 17:39:53.718  1509  2208 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:39:53.748  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:53.751  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:53.781  1509  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 17:39:53.782  1509  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 17:39:53.782  1509  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:39:53.782  1509  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:39:53.800  3588  3872 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 17:39:53.802  3588  3871 E BooksSync: Soft error
08-12 17:39:53.802  3588  3871 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:39:53.802  3588  3871 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 17:39:53.802  3588  3871 E BooksSync: Sync error
08-12 17:39:53.802  3588  3871 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 17:39:53.802  3588  3871 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 17:39:53.803  3588  3871 I BooksSync: Finished books sync
,08-12 17:39:53.809   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127484, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:39:53.903  3613  3873 V KeepSync: Connecting to GoogleApiClient
,08-12 17:39:53.904   872  1365 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 17:39:53.987  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:53.990  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 17:39:54.054  1509  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 17:39:54.055  1509  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 17:39:54.055  1509  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:39:54.055  1509  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:39:54.106  1732  3874 V BaseAuthAsyncOperation: access token request failed
,08-12 17:39:54.111  3613  3873 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 17:39:54.169  1509  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 17:39:54.169  1509  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 17:39:54.169  1509  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 17:39:54.169  1509  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 17:39:54.187  3613  3873 E KeepSync: IOException
08-12 17:39:54.187  3613  3873 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 17:39:54.187  3613  3873 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 17:39:54.187  3613  3873 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 17:39:54.187  3613  3873 E KeepSync: 	... 10 more
08-12 17:39:54.187  3613  3873 W KeepSync: Sync result 2
,08-12 17:39:54.195   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127628, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 17:39:58.342  3815  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:39:58.342  3815  3864 I jxcore-log: 
,08-12 17:39:58.344  3815  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:39:58.344  3815  3864 I jxcore-log: 
,08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:39:58.352  3815  3864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 17:39:58.355  3815  3864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 17:39:58.357  3815  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:39:58.357  3815  3864 I jxcore-log: 
,08-12 17:39:58.359  3815  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:39:58.359  3815  3864 I jxcore-log: 
,08-12 17:39:58.693  3815  3864 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-12 17:39:58.693  3815  3864 I jxcore-log: Failed to execute UT.
08-12 17:39:58.693  3815  3864 I jxcore-log: 
08-12 17:39:58.694  3815  3864 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 17:39:58.694  3815  3864 I jxcore-log: 
,08-12 17:39:58.697  3815  3864 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:39:58.697  3815  3864 I jxcore-log: 
,08-12 17:39:58.716  3815  3815 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 17:39:59.368  3883  3883 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 17:39:59.373  3883  3883 D AndroidRuntime: CheckJNI is OFF
,08-12 17:39:59.416  3883  3883 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 17:39:59.465  3883  3883 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 17:39:59.487  3883  3883 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:39:59.498   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 17:39:59.498   872   885 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 17:39:59.610   872   896 W PackageSettings: Skipping PackageSetting{55bc13d com.example.hello/10273} due to missing metadata
,08-12 17:39:59.621   872  1365 D GraphicsStats: Buffer count: 2
,08-12 17:39:59.621   872  1930 I WindowState: WIN DEATH: Window{ded5cf3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:39:59.622   872  1308 D WifiService: Client connection lost with reason: 4
,08-12 17:39:59.642   872   885 W ActivityManager: Force removing ActivityRecord{d10a938 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-12 17:39:59.654   872   896 I art     : Starting a blocking GC Explicit
,08-12 17:39:59.661   872   883 W ActivityManager: Spurious death for ProcessRecord{9ffb25d 0:com.test.thalitest/u0a0}, curProc for 3815: null
,08-12 17:39:59.696   872   896 I art     : Explicit concurrent mark sweep GC freed 31138(1946KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 828us total 41.478ms
,08-12 17:39:59.704   872  1924 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
,08-12 17:39:59.706  1852  1852 I Keyboard.Facilitator: onFinishInput()
,08-12 17:39:59.721   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 17:39:59.725  3883  3883 I art     : System.exit called, status: 0
08-12 17:39:59.725  3883  3883 I AndroidRuntime: VM exiting with result code 0.
,08-12 17:39:59.739   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 17:39:59.777  2087  2269 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:39:59.777  2648  2648 D BluetoothMapAppObserver: onReceive
08-12 17:39:59.777  2648  2648 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-12 17:39:59.777   872  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 17:39:59.781  1367  1377 I art     : Background partial concurrent mark sweep GC freed 14170(751KB) AllocSpace objects, 5(560KB) LOS objects, 23% free, 52MB/68MB, paused 7.186ms total 21.788ms
,08-12 17:39:59.797  3681  3681 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 17:39:59.798  1852  1852 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 17:39:59.820  1990  3900 I MicroRecognitionRnrImpl: Starting detection.
,08-12 17:39:59.821  1852  3899 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 17:39:59.822  1990  3901 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@e42308b
,08-12 17:39:59.826  1852  3899 I Decoder : createOrResetDecoder
,08-12 17:39:59.829   376  3903 I AudioFlinger: AudioFlinger's thread 0xb3380000 ready to run
,08-12 17:39:59.832   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-12 17:39:59.833  1990  3901 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@e42308b
,08-12 17:39:59.843   376  3903 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-12 17:39:59.843   376  3903 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-12 17:39:59.843   376  3903 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-12 17:39:59.853  1911  1911 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 17:39:59.854   376  3903 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-12 17:39:59.878  3480  3904 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 17:39:59.881  1509  1509 I ConfigService: onCreate
,08-12 17:39:59.885   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 17:39:59.900  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-12 17:39:59.903  1509  1509 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-12 17:39:59.903  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
08-12 17:39:59.903  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
08-12 17:39:59.903  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 17:39:59.903  1509  1509 E AndroidRuntime: 	... 8 more
08-12 17:39:59.905  1852  3899 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-12 17:39:59.907  3480  3495 E SQLiteLog: (1034) os_unix.c:29052: (30) full_fsync(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj64318A907) - 
08-12 17:39:59.908   872  3909 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:39:59.908   872  3909 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:39:59.908   872  3909 E DropBox,ManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:39:59.908   872  3909 E DropBoxManagerService: 	... 5 more
08-12 17:39:59.923   872  3910 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 17:39:59.927  1926  2021 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-12 17:39:59.929   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 17:39:59.929   872   884 E PackageManager: Failed to write settings, restoring backup
08-12 17:39:59.929   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 17:39:59.929   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 17:39:59.929   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 17:39:59.929   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 17:39:59.929   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 17:39:59.929   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:39:59.929   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:39:59.929   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:39:59.907  3480  3495 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj64318A907) - 
08-12 17:39:59.933   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-12 17:39:59.933   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 17:39:59.933   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:39:59.933   872   885 E DropBoxManagerService: 	... 13 more
08-12 17:39:59.933  1990  1990 I HotwordWorkerImpl: onReady
08-12 17:39:59.940   872  1925 I ActivityManager: Start proc 3911:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 17:39:59.940  1926  2021 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 17:39:59.940  1926  2021 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1926
08-12 17:39:59.940  1926  2021 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:39:59.940  1926  2021 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 17:39:59.941   872  1930 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 17:39:59.943   872  3917 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:39:59.943   872  3917 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:39:59.943   872  3917 E DropBoxManagerService: 	... 5 more
,08-12 17:39:59.955   872  3910 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 17:39:59.955   872  3910 I Adreno  : Build Date                       : 10/20/15
08-12 17:39:59.955   872  3910 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 17:39:59.955   872  3910 I Adreno  : Local Branch                     : M14
08-12 17:39:59.955   872  3910 I Adreno  : Remote Branch                    : 
08-12 17:39:59.955   872  3910 I Adreno  : Remote Branch                    : 
08-12 17:39:59.955   872  3910 I Adreno  : Reconstruct Branch               : 
08-12 17:39:59.957  1990  2014 W SearchService: Abort, client detached.
08-12 17:39:59.959  1990  1990 I HotwordDetector: Closing mic
08-12 17:39:59.960  1990  2338 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e42308b
08-12 17:39:59.960  1990  3901 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 17:39:59.960   872  3910 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:39:59.965  1990  3925 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-12 17:40:00.004  1852  3899 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 17:40:00.015   376  3903 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-12 17:40:00.016   376  3903 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 17:40:00.018   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 17:40:00.019  1990  3900 I MicroRecognitionRnrImpl: Detection finished
08-12 17:40:00.020  1990  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-12 17:40:00.034  3480  3904 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 17:40:00.035  3480  3904 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-12 17:40:00.035  3480  3904 E AndroidRuntime: Process: android.process.acore, PID: 3480
08-12 17:40:00.035  3480  3904 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 17:40:00.035  3480  3904 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 17:40:00.036  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-12 17:40:00.036  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-12 17:40:00.036  3480  3495 I Process : Sending signal. PID: 3480 SIG: 9
08-12 17:40:00.040   872  3930 E DropBoxManagerService: Can't write: system_app_crash
08-12 17:40:00.040   872  3930 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186),
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 17:40:00.040   872  3930 E DropBoxManagerService: 	... 5 more
,08-12 17:40:00.048  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 17:40:00.048  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-12 17:40:00.049  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 17:40:00.049  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 17:40:00.050  1852  3899 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 17:40:00.050  1852  3899 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 17:40:00.050  1852  3899 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 17:40:00.050  1852  3899 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 17:40:00.050  1852  3899 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 17:40:00.051  1852  3899 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 17:40:00.073   872  1965 I ActivityManager: Process android.process.acore (pid 3480) has died
,08-12 17:40:00.074   872  1965 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-12 17:40:00.093  1732  3932 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-12 17:40:00.093  1732  3932 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-12 17:40:00.285   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
,08-12 17:40:00.285   281   281 E qdoverlay: MdpData failed to play
08-12 17:40:00.286   281   281 E qdoverlay: == Dump MdpData start ==
,08-12 17:40:00.286   281   281 E qdoverlay: == Dump OvFD fd=33 path=/dev/graphics/fb0 start/end ==
,08-12 17:40:00.286   281   281 E qdoverlay: mOvData msmfb_overlay_data id=8
,08-12 17:40:00.286   281   281 E qdoverlay: data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
,08-12 17:40:00.286   281   281 E qdoverlay: == Dump MdpData end ==
08-12 17:40:00.286   281   281 E qdhwcomposer: draw: queue failed for left of dpy = 0
,08-12 17:40:00.286   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
,08-12 17:40:00.287   281   281 E qdoverlay: MdpData failed to play
,08-12 17:40:00.287   281   281 E qdoverlay: == Dump MdpData start ==
08-12 17:40:00.287   281   281 E qdoverlay: == Dump OvFD fd=76 path=/dev/graphics/fb0 start/end ==,
08-12 17:40:00.288   281   281 E qdoverlay: mOvData msmfb_overlay_data id=16
,08-12 17:40:00.288   281   281 E qdoverlay: data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
08-12 17:40:00.289   281   281 E qdoverlay: == Dump MdpData end ==
08-12 17:40:00.289   281   281 E qdhwcomposer: draw: queue failed for right of dpy = 0
08-12 17:40:00.289   281   281 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
08-12 17:40:00.289   281   281 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
08-12 17:40:00.290   281   281 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
08-12 17:40:00.290   281   281 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
08-12 17:40:00.294   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-12 17:40:00.294   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-12 17:40:00.294   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 17:40:00.294   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 17:40:00.294   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-12 17:40:00.296   281   281 E qdoverlay: MdpCtrl close error in unset

```
