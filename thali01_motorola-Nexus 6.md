#### Test 80761374bf0e3f7_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 13:40:16.354  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:16.365  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 13:40:16.371  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 13:40:16.409   873  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-16 13:40:16.416  1522  2075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 13:40:16.417  1522  2075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:40:16.417  1522  2075 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:16.417  1522  2075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 13:40:16.455  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 13:40:16.455  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 13:40:16.455  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-16 13:40:16.987   873  1865 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-16 13:40:17.029  3917  3917 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 13:40:17.035  3917  3917 D AndroidRuntime: CheckJNI is OFF
08-16 13:40:17.078  3917  3917 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 13:40:17.130  3917  3917 I Radio-JNI: register_android_hardware_Radio DONE
08-16 13:40:17.152  3917  3917 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 13:40:17.158   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 13:40:17.201  1993  2005 W SearchService: Abort, client detached.
08-16 13:40:17.205  3917  3917 D AndroidRuntime: Shutting down VM
08-16 13:40:17.207  1993  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@61617cc
08-16 13:40:17.208  1993  1993 I HotwordDetector: Closing mic
08-16 13:40:17.208  1993  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 13:40:17.225   873  3223 I ActivityManager: Start proc 3926:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 13:40:17.272   376  2341 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 13:40:17.273   376  2341 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 13:40:17.280   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 13:40:17.282  1993  2337 I MicroRecognitionRnrImpl: Detection finished
08-16 13:40:17.283  1993  2333 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 13:40:17.328  3926  3926 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 13:40:17.363  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 13:40:17.370  3926  3926 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2991-2993)
08-16 13:40:17.370  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:40:17.387  3926  3926 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a1a082}
08-16 13:40:17.388  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 13:40:17.388  3926  3926 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 13:40:17.396  3926  3926 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 13:40:17.397  3926  3926 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 13:40:17.411  3926  3926 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 13:40:17.425  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:40:17.425  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:40:17.425  3926  3926 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:40:17.425  3926  3926 I Adreno  : Build Date                       : 10/20/15
08-16 13:40:17.425  3926  3926 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:40:17.425  3926  3926 I Adreno  : Local Branch                     : M14
08-16 13:40:17.425  3926  3926 I Adreno  : Remote Branch                    : 
08-16 13:40:17.425  3926  3926 I Adreno  : Remote Branch                    : ,
08-16 13:40:17.425  3926  3926 I Adreno  : Reconstruct Branch               : 
,08-16 13:40:17.493   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d5559de:true
,08-16 13:40:17.570  3926  3926 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 13:40:17.592  3926  3926 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 13:40:17.676  3926  3966 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 13:40:17.689  3926  3951 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 13:40:17.738  3926  3966 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 13:40:17.802   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +597ms
,08-16 13:40:17.813  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-16 13:40:17.875  3926  3926 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3926
,08-16 13:40:18.012  3926  3926 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 13:40:18.068   873  1702 I ActivityManager: Killing 3125:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 13:40:18.183   873  1702 I ActivityManager: Killing 3017:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-16 13:40:18.302  3926  3968 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1714226896
,08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 13:40:18.315  3926  3968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5b9a066 added. We now have 1 listener(s)
,08-16 13:40:18.328  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 13:40:18.335  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:40:18.337  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:40:18.338  3926  3968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 13:40:18.345  3926  3968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6db77fd added. We now have 1 listener(s)
08-16 13:40:18.346  3926  3968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:40:18.361   873  1308 D WifiService: New client listening to asynchronous messages
,08-16 13:40:18.364  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:40:18.364  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 13:40:18.364  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 13:40:18.365  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 13:40:18.365  3926  3968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 13:40:18.369  3926  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:18.369  3926  3968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 13:40:18.375  3926  3968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:18.375  3926  3968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:40:18.376  3926  3968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 13:40:18.376  3926  3968 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:40:18.377  3926  3968 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 13:40:18.377  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:18.379  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:18.405  3926  3926 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 13:40:19.520  3926  3976 W jxcore-log: Initializing JXcore engine
,08-16 13:40:19.520  3926  3976 W jxcore-log: JXcore engine is ready
,08-16 13:40:19.560  3976  3976 W Thread-349: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8800 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 13:40:19.560  3976  3976 W Thread-349: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10558]" dev="sockfs" ino=10558 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 13:40:19.560  3976  3976 W Thread-349: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 13:40:19.560  3976  3976 W Thread-349: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26249]" dev="sockfs" ino=26249 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 13:40:19.576  3926  3976 W jxcore-log: Starting JXcore engine
,08-16 13:40:19.660  3926  3976 W jxcore-log: Platform android
08-16 13:40:19.660  3926  3976 W jxcore-log: 
,08-16 13:40:19.660  3926  3976 W jxcore-log: Process ARCH arm
08-16 13:40:19.660  3926  3976 W jxcore-log: 
,08-16 13:40:19.876  3926  3976 I jxcore-log: JXcore Cordova bridge is ready!
08-16 13:40:19.876  3926  3976 I jxcore-log: 
,08-16 13:40:19.877  3926  3976 W jxcore-log: JXcore engine is started
,08-16 13:40:19.888  3926  3968 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 13:40:19.894  3926  3926 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 13:40:21.705  3677  3978 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 13:40:21.726  3677  3979 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 13:40:21.741  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:21.744  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:21.771  1522  2075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:40:21.771  1522  2075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 13:40:21.771  1522  2075 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:21.771  1522  2075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:21.810  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:21.813  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:21.845  1522  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:40:21.846  1522  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 13:40:21.846  1522  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:21.846  1522  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:21.871  3677  3979 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 13:40:21.874  3677  3978 E BooksSync: Soft error
08-16 13:40:21.874  3677  3978 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:40:21.874  3677  3978 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:40:21.874  3677  3978 E BooksSync: Sync error
08-16 13:40:21.874  3677  3978 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:40:21.874  3677  3978 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:40:21.874  3677  3978 I BooksSync: Finished books sync
,08-16 13:40:21.885   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127288, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:40:35.710  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 13:40:35.710  3926  3976 I jxcore-log: 
,08-16 13:40:35.712  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 13:40:35.712  3926  3976 I jxcore-log: 
,08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:35.721  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:40:35.726  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:40:35.728  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 13:40:35.728  3926  3976 I jxcore-log: 
,08-16 13:40:35.730  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 13:40:35.730  3926  3976 I jxcore-log: 
,08-16 13:40:36.064  3926  3976 I jxcore-log: Running unit tests
08-16 13:40:36.064  3926  3976 I jxcore-log: 
,08-16 13:40:36.065  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:40:36.065  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@514ac50 added. We now have 2 listener(s)
08-16 13:40:36.066  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:40:36.066  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:40:36.066  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:40:36.066  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:40:36.066  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2dee49 added. We now have 2 listener(s)
08-16 13:40:36.066  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:40:36.067  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:40:36.070  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:36.096  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:40:36.105  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:40:36.106  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:40:36.107  3926  3976 D ExecuteNativeTests: Running unit tests
,08-16 13:40:36.113  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:36.130  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:37.290  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:37.293  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:37.308  3868  3991 V GoogleAuthProtoRequest: [335] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:40:37.357  1522  2075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 13:40:37.357  1522  2075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 13:40:37.357  1522  2075 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:37.357  1522  2075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 13:40:37.385  3868  3991 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 13:40:37.483  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:37.520  1522  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 13:40:37.520  1522  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:40:37.520  1522  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:37.520  1522  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:37.543  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 13:40:37.543  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 13:40:37.543  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 13:40:37.589  1522  3992 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 13:40:37.596  1522  3992 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 13:40:37.640  1522  3992 W Uploader:  no longer exists, so no auth token.
,08-16 13:40:38.971  1522  3992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 13:40:38.971  1522  3992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 13:40:38.971  1522  3992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:38.971  1522  3992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:38.990  1522  3992 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 13:40:38.990  1522  3992 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 13:40:38.990  1522  3992 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 13:40:39.173  1522  3992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 13:40:39.174  1522  3992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 13:40:39.175  1522  3992 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:39.175  1522  3992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:39.221  1522  3992 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 13:40:39.221  1522  3992 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 13:40:39.221  1522  3992 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 13:40:39.600  1522  3992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 13:40:39.600  1522  3992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 13:40:39.601  1522  3992 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:39.601  1522  3992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:39.657  1522  3992 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 13:40:39.657  1522  3992 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 13:40:39.657  1522  3992 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 13:40:41.179  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:40:41.179  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f added. We now have 3 listener(s)
,08-16 13:40:41.186  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:40:41.187  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:40:41.187  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:40:41.188  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:40:41.188  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac added. We now have 3 listener(s)
,08-16 13:40:41.188  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:40:41.190  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:40:41.198  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:41.212  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:40:41.219  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:40:41.220  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:40:41.229  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:41.230  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 13:40:41.234  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:40:41.235  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:40:41.235  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:40:41.238  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:41.243  3926  3976 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 13:40:41.244  3926  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 13:40:41.244  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 13:40:41.245  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:40:41.245  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:40:41.245  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:40:41.248  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:40:41.250  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:41.250  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:40:41.251  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:40:41.252  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.252  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:40:41.253  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 13:40:41.253  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f removed from the list
,08-16 13:40:41.254  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:41.254  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac removed from the list
,08-16 13:40:41.254  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:40:41.255  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.256  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.256  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.257  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:40:41.257  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:40:41.257  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:40:41.257  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:40:41.260  3926  3976 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 13:40:41.260  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:40:41.260  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:41.260  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:40:41.261  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:40:41.261  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.261  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.261  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:40:41.261  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:41.261  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:41.261  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:40:41.261  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.261  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.261  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.261  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.262  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:40:41.263  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:40:41.263  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:41.263  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:40:41.269  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:40:41.269  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:40:41.270  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:40:41.271  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 13:40:41.272  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 13:40:41.272  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:40:41.272  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:41.272  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:40:41.273  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:40:41.273  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.273  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.273  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:40:41.273  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:41.273  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:41.273  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:40:41.273  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.273  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.274  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:41.274  3926  3976 D org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:41.275  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:40:41.275  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:40:41.275  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:41.275  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:41.276  3926  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 13:40:41.277  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:41.283  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:40:41.284  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:41.284  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:40:41.285  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:40:41.285  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:40:41.285  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:40:41.285  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:40:41.285  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:40:41.288  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:40:41.289  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:40:41.289  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:40:41.290  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:40:41.293  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:40:41.295  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 13:40:41.296  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 13:40:41.298  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 13:40:41.300  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 13:40:41.300  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 13:40:41.300  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:40:41.301  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:40:41.302  3926  3976 D BluetoothAdapter: STATE_ON
08-16 13:40:41.306  2734  2745 D BtGatt.GattService: registerClient() - UUID=2fcb4928-1806-4980-92d8-e2af0bfd8e5a
08-16 13:40:41.308  2734  2759 D BtGatt.GattService: onClientRegistered() - UUID=2fcb4928-1806-4980-92d8-e2af0bfd8e5a, clientIf=5
08-16 13:40:41.309  3926  3938 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 13:40:41.310  2734  2747 D BtGatt.GattService: start scan with filters
,08-16 13:40:41.314  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 13:40:41.314  2734  2762 D BtGatt.ScanManager: handling starting scan
08-16 13:40:41.315  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:40:41.315  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:40:41.315  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 13:40:41.315  2734  2762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:40:41.318  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:40:41.318  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:40:41.319  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:40:41.321  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 13:40:41.325  2734  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:40:41.325  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:41.326  3926  3976 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:40:41.326  2734  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 13:40:41.334  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:40:41.334  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:41.335  2734  2762 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:40:41.335  2734  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 13:40:41.347  2734  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 13:40:41.348  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:41.354  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 13:40:41.354  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:41.820  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 13:40:41.821  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 13:40:41.821  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:40:42.694   873  1865 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 13:40:42.861  2734  2734 D BtGatt.ScanManager: awakened up at time 148485
,08-16 13:40:42.865  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:42.900  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-16 13:40:42.900  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:42.901  2734  2759 D BtGatt.GattService: current time is 148524954188
,08-16 13:40:42.902  2734  2759 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -89, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 13:40:42.907  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 13:40:42.909  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 13:40:42.910  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:40:42.911  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:40:42.911  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
08-16 13:40:42.912  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 13:40:44.406  2734  2734 D BtGatt.ScanManager: awakened up at time 150029
,08-16 13:40:44.408  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:44.420  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:40:44.420  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:44.550   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 13:40:44.562  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-16 13:40:44.582   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:40:44.582   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 13:40:44.582   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:40:44.582   873   893 I Adreno  : Local Branch                     : M14
08-16 13:40:44.582   873   893 I Adreno  : Remote Branch                    : 
08-16 13:40:44.582   873   893 I Adreno  : Remote Branch                    : 
08-16 13:40:44.582   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 13:40:44.628   279   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (210 us)
,08-16 13:40:45.230  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 13:40:45.230  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 13:40:45.266   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 13:40:45.269  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78118e8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@72a68f1, 16908290=android.view.AbsSavedState$1@72a68f1}, android:focusedViewId=100}]}]
,08-16 13:40:45.269  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 13:40:45.269  3926  3926 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:40:45.269  3926  3926 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 13:40:45.278   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 13:40:45.281   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 13:40:45.281   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-16 13:40:45.281   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 13:40:45.312   873   882 I art     : Background partial concurrent mark sweep GC freed 33959(2MB) AllocSpace objects, 7(148KB) LOS objects, 33% free, 29MB/43MB, paused 888us total 115.189ms
,08-16 13:40:45.518   279   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 13:40:45.522   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 13:40:45.528   873  1330 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,08-16 13:40:45.533   873   893 I DreamManagerService: Entering dreamland.
,08-16 13:40:45.534   873   893 I PowerManagerService: Dozing...
,08-16 13:40:45.536   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 13:40:45.597   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 13:40:45.597   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-16 13:40:45.604  2734  2734 D BtGatt.ScanManager: awakened up at time 151227
,08-16 13:40:45.607  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:45.616  1898  4010 D NfcService: Discovery configuration equal, not updating.
,08-16 13:40:45.620   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:40:45.637  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 13:40:45.637  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:45.637  2734  2759 D BtGatt.GattService: current time is 151261546378
08-16 13:40:45.638  2734  2759 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -90, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -96, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -96, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 13:40:45.638  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 13:40:45.638  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 13:40:45.639  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 13:40:45.639  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 13:40:45.639  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:40:45.639   873  1307 E native  : do suspend false
08-16 13:40:45.639  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 13:40:45.654   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 13:40:45.663   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:40:45.666   873  1307 E native  : do suspend true
,08-16 13:40:45.734   376  1474 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 13:40:45.735   376  1474 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 13:40:46.128   873  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 13:40:46.336  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:40:46.336  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:40:46.337  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:40:46.337  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:46.337  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 13:40:46.338  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:40:46.338  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:40:46.338  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:40:46.338  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:40:46.341  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:40:46.341  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:40:46.344  3926  3976 D BluetoothAdapter: STATE_ON
08-16 13:40:46.346  2734  2745 D BtGatt.GattService: stopScan() - queue size =1
,08-16 13:40:46.348  2734  2747 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:40:46.350  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 13:40:46.350  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:40:46.351  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:40:46.351  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 13:40:46.351  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:40:46.356  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:40:46.360  2734  2734 D BtGatt.ScanManager: awakened up at time 151983
08-16 13:40:46.361  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:40:46.361  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 13:40:46.362  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:40:46.364  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:40:46.366  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:40:46.366  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:40:46.366  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:40:46.366  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:40:46.366  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:40:46.367  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:40:46.367  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:46.367  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:40:46.367  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:40:46.367  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:46.367  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:40:46.372  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 13:40:46.373  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:46.374  2734  2762 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:40:46.383  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 13:40:46.383  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:46.383  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:46.397  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 13:40:46.397  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:46.397  2734  2759 D BtGatt.GattService: current time is 152020909058
08-16 13:40:46.397  2734  2759 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -94, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:40:46.397  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-16 13:40:46.398  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 13:40:46.398  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 13:40:46.398  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:46.868  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:40:51.092  2151  2659 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 13:40:51.368  3926  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:40:51.374  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:51.389  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:40:51.396  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:40:51.397  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:40:51.397  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:40:51.398  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:40:51.400  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:40:51.400  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:51.401  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 13:40:51.408  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:51.414  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:40:51.414  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:40:51.416  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:51.428  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:40:51.431  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:40:51.431  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:40:51.443  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:40:51.443  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 13:40:51.444  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 13:40:51.448  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:40:51.456  2734  2881 D BtGatt.GattService: registerClient() - UUID=551f4517-1f58-4730-9881-a4bb6abe1fe4
,08-16 13:40:51.457  2734  2759 D BtGatt.GattService: onClientRegistered() - UUID=551f4517-1f58-4730-9881-a4bb6abe1fe4, clientIf=5
08-16 13:40:51.458  3926  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:40:51.459  2734  2880 D BtGatt.GattService: start scan with filters
,08-16 13:40:51.472  2734  2762 D BtGatt.ScanManager: handling starting scan
,08-16 13:40:51.472  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:40:51.473  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 13:40:51.473  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:40:51.473  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:40:51.484  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:40:51.485  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:40:51.486  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:40:51.490  2734  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 13:40:51.490  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.491  2734  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:40:51.495  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:40:51.507  3926  3976 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 13:40:51.512  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 13:40:51.512  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.512  2734  2762 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:40:51.513  2734  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 13:40:51.516  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:40:51.516  3926  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 13:40:51.516  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:51.517  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 13:40:51.517  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:40:51.517  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:40:51.517  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:40:51.517  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:40:51.518  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:40:51.518  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:40:51.518  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:40:51.518  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 13:40:51.520  3926  3976 D BluetoothAdapter: STATE_ON
08-16 13:40:51.522  2734  2747 D BtGatt.GattService: stopScan() - queue size =1
,08-16 13:40:51.524  2734  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:40:51.525  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:40:51.526  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:40:51.527  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:40:51.527  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:40:51.527  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:40:51.530  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:40:51.530  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:40:51.531  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:40:51.531  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:40:51.532  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:40:51.534  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:40:51.534  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:40:51.535  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:40:51.535  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:40:51.535  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:40:51.535  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:40:51.535  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:40:51.535  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:40:51.536  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:51.536  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:40:51.536  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:40:51.538  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:40:51.539  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:40:51.544  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:40:51.544  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:40:51.544  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:40:51.545  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:40:51.546  3926  3976 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 13:40:51.549  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:40:51.551  2734  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:40:51.551  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:40:51.556  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:40:51.559  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 13:40:51.559  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.560  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:40:51.561  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:40:51.561  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:40:51.561  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:40:51.561  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:40:51.561  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:40:51.561  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 13:40:51.565  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:51.568  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:40:51.569  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:40:51.570  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:40:51.574  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:40:51.574  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:51.574  2734  2762 D BtGatt.ScanManager: stopping BLe Batch
08-16 13:40:51.574  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 13:40:51.575  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:40:51.575  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:40:51.579  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:40:51.579  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:40:51.579  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:40:51.579  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:40:51.582  2734  2872 D BtGatt.GattService: registerClient() - UUID=927fc013-1aac-4eb4-98aa-a39ba54ec866
08-16 13:40:51.582  2734  2759 D BtGatt.GattService: onClientRegistered() - UUID=927fc013-1aac-4eb4-98aa-a39ba54ec866, clientIf=5
08-16 13:40:51.583  3926  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:40:51.583  2734  2881 D BtGatt.GattService: start scan with filters
,08-16 13:40:51.585  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 13:40:51.585  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.585  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:51.586  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 13:40:51.586  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:40:51.586  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:40:51.586  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:40:51.589  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:40:51.590  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:40:51.590  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:40:51.592  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:40:51.594  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 13:40:51.594  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.595  3926  3976 I io.jxcore.node.ConnectionHelper: start: OK
08-16 13:40:51.596  2734  2762 D BtGatt.ScanManager: handling starting scan
,08-16 13:40:51.603  2734  2759 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 13:40:51.603  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:51.604  2734  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:40:51.610  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 13:40:51.610  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:51.611  2734  2762 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:40:51.611  2734  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 13:40:51.623  2734  2759 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:40:51.623  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:51.630  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:40:51.630  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:52.090  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-16 13:40:52.090  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:40:52.090  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:40:52.100  3704  4017 V KeepSync: Connecting to GoogleApiClient
08-16 13:40:52.101   873  1915 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 13:40:52.134  2734  2734 D BtGatt.ScanManager: awakened up at time 157758
,08-16 13:40:52.135  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:52.156  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-16 13:40:52.156  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:52.156  2734  2759 D BtGatt.GattService: current time is 157780258277
08-16 13:40:52.157  2734  2759 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -90, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:52.157  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-16 13:40:52.158  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-16 13:40:52.158  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:40:52.159  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:52.184  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:52.187  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:52.241  1522  4008 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 13:40:52.241  1522  4008 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 13:40:52.241  1522  4008 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:52.241  1522  4008 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:52.246  1522  2075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 13:40:52.246  1522  2075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 13:40:52.247  1522  2075 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:52.248  1522  2075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:52.260  1739  4018 V BaseAuthAsyncOperation: access token request failed
08-16 13:40:52.261  3704  4017 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 13:40:52.285  3621  4016 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 13:40:52.285  3621  4016 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at blb.a(PG:3937)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at czp.a(PG:18188)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:40:52.285  3621  4016 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	... 12 more
08-16 13:40:52.285  3621  4016 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at fal.a(PG:38)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:40:52.285  3621  4016 E HttpOperation: 	... 14 more
,08-16 13:40:52.347  1522  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-16 13:40:52.347  1522  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 13:40:52.347  1522  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:52.348  1522  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:52.348  1522  2390 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 13:40:52.348  1522  2390 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 13:40:52.348  1522  2390 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:40:52.348  1522  2390 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:52.366  3621  4016 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 13:40:52.366  3621  4016 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:40:52.366  3621  4016 E HttpOperation: ,	at hec.a(PG:42)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at hee.a(PG:102)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at czr.a(PG:65)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at kka.a(PG:108)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at czp.a(PG:19176)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:40:52.366  3621  4016 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	... 15 more
08-16 13:40:52.366  3621  4016 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at fal.a(PG:38)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:40:52.366  3621  4016 E HttpOperation: 	... 17 more
08-16 13:40:52.366  3621  4016 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 13:40:52.366  3621  4016 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at hec.a(PG:42)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at hee.a(PG:102)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at czr.a(PG:65)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at kka.a(PG:108)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	... 15 more
08-16 13:40:52.366  3621  4016 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at fal.a(PG:38)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 13:40:52.366  3621  4016 E ExperimentLoader: 	... 17 more
,08-16 13:40:52.389  3704  4017 E KeepSync: IOException
08-16 13:40:52.389  3704  4017 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 13:40:52.389  3704  4017 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 13:40:52.389  3704  4017 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 13:40:52.389  3704  4017 E KeepSync: 	... 10 more
,08-16 13:40:52.390  3704  4017 W KeepSync: Sync result 2
,08-16 13:40:52.398   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130390, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:40:52.473   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127886, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:40:52.660  2734  2734 D BtGatt.ScanManager: awakened up at time 158284
08-16 13:40:52.662  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:52.703  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-16 13:40:52.704  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:40:52.704  2734  2759 D BtGatt.GattService: current time is 158328324842
,08-16 13:40:52.705  2734  2759 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 13:40:52.706  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 13:40:52.707  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 13:40:54.208  2734  2734 D BtGatt.ScanManager: awakened up at time 159831
,08-16 13:40:54.210  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:54.259  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 13:40:54.259  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:54.260  2734  2759 D BtGatt.GattService: current time is 159883649923
,08-16 13:40:54.260  2734  2759 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:54.262  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 13:40:54.263  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 13:40:54.265  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:40:54.266  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:55.761  2734  2734 D BtGatt.ScanManager: awakened up at time 161385
,08-16 13:40:55.764  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:55.814  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-16 13:40:55.815  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:55.815  2734  2759 D BtGatt.GattService: current time is 161439185456
,08-16 13:40:55.817  2734  2759 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -93, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-16 13:40:55.818  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 13:40:55.819  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:40:55.820  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:40:55.821  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 13:40:55.822  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-16 13:40:56.424   873  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 13:40:56.596  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:40:56.597  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:56.597  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:40:56.597  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:40:56.598  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:40:56.598  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:40:56.598  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:40:56.598  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:40:56.599  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 13:40:56.599  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:40:56.600  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:40:56.602  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:40:56.605  2734  2872 D BtGatt.GattService: stopScan() - queue size =1
,08-16 13:40:56.607  2734  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:40:56.610  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 13:40:56.610  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 13:40:56.611  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 13:40:56.611  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 13:40:56.611  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 13:40:56.615  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:40:56.615  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:40:56.616  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:40:56.617  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:40:56.620  2734  2734 D BtGatt.ScanManager: awakened up at time 162243
08-16 13:40:56.621  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:40:56.625  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:40:56.625  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:40:56.625  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:40:56.632  2734  2759 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 13:40:56.632  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:56.632  2734  2762 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:40:56.644  2734  2759 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 13:40:56.644  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:56.645  2734  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:40:56.663  2734  2759 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-16 13:40:56.664  2734  2759 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:40:56.664  2734  2759 D BtGatt.GattService: current time is 162288190868
,08-16 13:40:56.665  2734  2759 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:40:56.665  2734  2759 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 13:40:57.127  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:40:57.127  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:40:57.127  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:40:57.795  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:57.807  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:57.813  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:40:57.871  1522  2390 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 13:40:57.871  1522  2390 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:40:57.872  1522  2390 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:40:57.872  1522  2390 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:40:57.927  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 13:40:57.927  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 13:40:57.927  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 13:41:01.627  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.628  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:01.628  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.630  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:01.631  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.631  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:41:01.632  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.632  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.632  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.633  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:01.633  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.635  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.636  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.639  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.640  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.640  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.640  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.642  3926  3976 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 13:41:01.644  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.645  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:01.645  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.645  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.646  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.646  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.647  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.647  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.648  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.648  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.648  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.648  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.649  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.649  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.652  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:01.652  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.652  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.653  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.656  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 13:41:01.656  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.656  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:01.657  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.657  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.658  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.658  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.658  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.659  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.659  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.659  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.659  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.660  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.660  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.660  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.662  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.662  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.663  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.663  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.665  3926  3976 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 13:41:01.665  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.666  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:01.666  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.667  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.667  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.667  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.667  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:01.668  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.668  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.668  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.668  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.668  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.669  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.669  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.671  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.671  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.671  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.671  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.672  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 13:41:01.672  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:41:01.672  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:01.672  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:41:01.672  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.672  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.672  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.673  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.673  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.673  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.673  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:01.673  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.673  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.673  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.673  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.674  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.674  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.674  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.674  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.675  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 13:41:01.675  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:41:01.675  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:41:01.675  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:41:01.675  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:41:01.676  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:41:01.676  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 13:41:01.676  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 13:41:01.676  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 13:41:01.676  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.676  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:01.676  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:41:01.676  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:01.677  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.677  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.677  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.677  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.677  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.677  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.677  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.677  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.677  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.677  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.679  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.679  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.679  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.679  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.680  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 13:41:01.680  3926  3976 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 13:41:01.680  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 13:41:01.684  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 13:41:01.684  3926  3976 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 13:41:01.684  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 13:41:01.685  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 13:41:01.686  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 13:41:01.687  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 13:41:01.692  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 13:41:01.692  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 13:41:01.692  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 13:41:01.692  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 13:41:01.693  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 13:41:01.693  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 13:41:01.693  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-16 13:41:01.694  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 13:41:01.694  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-16 13:41:01.695  3926  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 13:41:01.695  3926  3976 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 13:41:01.695  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 13:41:01.696  3926  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 13:41:01.696  3926  3976 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-16 13:41:01.696  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 13:41:01.697  3926  3976 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 13:41:01.698  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 13:41:01.703  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-16 13:41:01.706  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-16 13:41:01.707  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-16 13:41:01.709  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-16 13:41:01.710  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 13:41:01.710  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 13:41:01.710  3926  3976 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 13:41:01.711  3926  3976 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 13:41:01.711  3926  4020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 413)
,08-16 13:41:01.712  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.713  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:01.714  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:41:01.714  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:01.714  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.714  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.721  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 13:41:01.721  3926  4020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:01.722  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:01.722  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.723  3926  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 413
08-16 13:41:01.722  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.723  3926  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 413)
08-16 13:41:01.723  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.723  3926  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 413)
08-16 13:41:01.723  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.723  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.723  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.723  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.725  3926  4020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 413)
,08-16 13:41:01.727  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:01.727  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.727  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.727  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.730  3926  3976 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-16 13:41:01.731  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:01.731  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:01.731  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.731  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.731  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.731  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.732  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.732  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.732  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.732  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:01.732  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.732  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.732  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.732  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.734  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.734  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:41:01.734  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:01.735  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.736  3926  3976 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-16 13:41:01.737  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-16 13:41:01.737  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:01.737  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.737  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:01.738  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.738  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 13:41:01.738  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:01.738  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.738  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.739  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:01.739  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.739  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.739  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.739  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.741  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:01.741  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.741  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.742  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:01.743  3926  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 13:41:01.743  3926  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 13:41:01.743  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:41:01.744  3926  3976 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-16 13:41:01.744  3926  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:41:01.744  3926  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-16 13:41:01.744  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 13:41:01.745  3926  3976 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 13:41:01.745  3926  3976 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 13:41:01.745  3926  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 13:41:01.745  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 13:41:01.745  3926  3976 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 13:41:01.746  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:41:01.746  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:01.746  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:01.747  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:01.747  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.747  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.747  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:01.747  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.747  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.747  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:01.747  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.747  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:01.748  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:01.748  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.749  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:01.750  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:01.750  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.750  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.752  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:01.752  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.752  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:01.753  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:01.753  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:01.754  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:01.754  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:01.754  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:01.755  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.757  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:06.757  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:06.757  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:06.758  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.758  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.763  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:06.764  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:06.764  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:06.766  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:41:06.767  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:06.767  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.768  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.768  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:06.769  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:06.769  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:06.769  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:06.770  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.770  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.770  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.771  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.775  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:06.775  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:41:06.775  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.776  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.780  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 13:41:06.781  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:41:06.782  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 13:41:06.784  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 13:41:06.785  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 13:41:06.786  3926  4022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:41:06.786  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 13:41:06.787  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:41:06.787  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 13:41:06.788  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:06.788  3926  4022 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 13:41:06.788  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 13:41:06.789  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 13:41:06.789  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 13:41:06.789  3926  4022 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 13:41:06.790  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.790  3926  4022 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 13:41:06.790  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-16 13:41:06.790  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:06.790  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 13:41:06.790  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:06.790  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:41:06.790  3926  4022 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 13:41:06.790  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 13:41:06.791  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:41:06.791  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.791  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.793  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:41:06.794  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.794  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:41:06.794  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:06.794  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:41:06.794  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:41:06.794  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:41:06.794  3926  3926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 13:41:06.794  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:06.795  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.795  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:41:06.795  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.795  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
08-16 13:41:06.795  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:06.795  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
08-16 13:41:06.796  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:06.796  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.796  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.796  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.796  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.798  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:06.798  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:41:06.798  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.799  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.801  3926  3976 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 13:41:06.801  3926  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 13:41:06.802  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 13:41:06.802  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 13:41:06.802  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 13:41:06.803  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:06.803  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:06.803  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:06.803  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:06.803  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.804  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.804  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:06.804  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.804  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.804  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:06.805  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.805  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.805  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.805  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.808  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:06.808  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:06.808  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.809  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.818  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:06.818  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:06.819  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:06.820  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:41:06.820  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.820  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.820  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:06.821  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.821  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.821  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:06.821  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.822  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.822  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:06.822  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:06.824  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:41:06.824  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:41:06.824  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:06.825  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.827  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:41:06.827  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:41:06.827  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:41:06.827  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:41:06.827  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.827  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.827  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7b9f5f not in the list
,08-16 13:41:06.827  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.828  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.828  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:06.828  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.828  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.828  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:41:06.828  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:06.829  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:41:06.829  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:41:06.829  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:06.829  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4abfdac not in the list
,08-16 13:41:06.853  2734  2853 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 13:41:06.853  2734  2868 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 13:41:07.296  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:41:11.832  3926  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 13:41:11.833  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 13:41:11.834  3926  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-16 13:41:11.834  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 13:41:11.835  3926  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 13:41:11.835  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 13:41:11.844  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 13:41:11.844  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 13:41:11.847  3926  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-16 13:41:11.847  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:41:11.848  3926  3976 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-16 13:41:11.848  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 13:41:11.848  3926  3976 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 13:41:11.849  3926  3976 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 13:41:11.852  3926  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 13:41:11.852  3926  3976 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 13:41:11.852  3926  3976 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 13:41:11.852  3926  3976 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 13:41:11.852  3926  3976 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-16 13:41:11.853  3926  3976 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 13:41:11.854  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:11.854  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2711e4f added. We now have 3 listener(s)
08-16 13:41:11.854  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:41:11.856  3926  3976 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 13:41:11.857   873  1954 D WifiService: setWifiEnabled: true pid=3926, uid=10000
08-16 13:41:11.857   873  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:16.866  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:16.867  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18029dc added. We now have 4 listener(s)
,08-16 13:41:16.867  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:41:16.889  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:16.889  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18029dc removed from the list
08-16 13:41:16.890  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:16.890  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:16.890  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:16.893  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 13:41:16.893  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7b0ae5 added. We now have 4 listener(s)
08-16 13:41:16.893  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:41:16.898  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:16.898  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7b0ae5 removed from the list
08-16 13:41:16.898  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:16.899  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:16.899  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:16.901  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:16.902  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd399ba added. We now have 4 listener(s)
08-16 13:41:16.902  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:41:16.910   873  1913 D WifiService: setWifiEnabled: false pid=3926, uid=10000
,08-16 13:41:16.910   873  1913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:16.924  2734  2755 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 13:41:16.925  2734  2755 D BluetoothAdapterProperties: Setting state to 13
,08-16 13:41:16.925  2734  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 13:41:16.927  2734  2755 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 13:41:16.923  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:41:16.931  2734  2755 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:41:16.941  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-16 13:41:16.942  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:16.945  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:16.946  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:16.948  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:41:16.948  2734  2734 D BluetoothMapService: onReceive
08-16 13:41:16.949  2734  2734 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:41:16.949  2734  2734 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:41:16.949  2734  2734 D BluetoothMapService: MAP Service closeService in
08-16 13:41:16.950  2734  2734 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 13:41:16.950  2734  2734 D ObexServerSockets0: shutdown(block = true)
08-16 13:41:16.950  2734  2734 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 13:41:16.951  2734  2734 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:41:16.951  2734  2868 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 13:41:16.951  2734  2882 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 13:41:16.951  2734  2883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 13:41:16.953  2734  2734 I BtOppRfcommListener: stopping Accept Thread
08-16 13:41:16.953  2734  3510 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 13:41:16.955  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:16.955  2734  3510 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 13:41:16.956  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 13:41:16.958   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 13:41:16.958   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 13:41:16.959   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:41:16.959   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:16.962  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:16.967  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:16.967  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:41:16.968  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:16.968  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:16.970   873  1307 E native  : do suspend true
,08-16 13:41:16.971  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:16.971  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:16.972  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:16.972  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:16.973   873   886 I ActivityManager: Start proc 4026:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 13:41:16.973  2734  2759 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:41:16.974  2734  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 13:41:16.977  2734  2734 D HeadsetService: Received stop request...Stopping profile...
,08-16 13:41:16.979  1918  1931 D BluetoothHeadset: Proxy object disconnected
,08-16 13:41:16.980  1361  2208 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:16.980   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:16.980   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:16.980   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:16.981  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:16.982  2734  2734 D A2dpService: Received stop request...Stopping profile...
08-16 13:41:16.984  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:16.984   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 13:41:16.985   873  1866 D DhcpClient: Clearing IP address
,08-16 13:41:16.986  2734  2875 D A2dpStateMachine: Exit Disconnected: -1
,08-16 13:41:16.985  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,08-16 13:41:16.985   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:41:16.987  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:16.987  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 13:41:16.988  2734  2734 D HidService: Received stop request...Stopping profile...
,08-16 13:41:16.988  2734  2734 D HidService: Stopping Bluetooth HidService
,08-16 13:41:16.989  2734  2734 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:16.989  2734  2734 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:41:16.989  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:16.989  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:16.989  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:16.989  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 13:41:16.990  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 13:41:16.993   372   871 D CommandListener: Setting iface cfg
08-16 13:41:16.994  2734  2734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:41:16.994  2734  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 13:41:16.994  2734  2734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 13:41:16.995  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:16.995  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:41:16.995  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:41:16.995  2734  2759 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 13:41:16.995  2734  2734 D HealthService: Received stop request...Stopping profile...
08-16 13:41:16.998   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 13:41:16.998   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 13:41:16.998   873  1867 D DhcpClient: Receive thread stopped
08-16 13:41:17.000   448   448 E Parcel  : Reading a NULL string not supported here.
08-16 13:41:17.001  2734  2734 D PanService: Received stop request...Stopping profile...
,08-16 13:41:17.002  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:41:17.002  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 13:41:17.002   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 13:41:17.003   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:41:17.003   873  1307 E native  : do suspend true
08-16 13:41:17.003  2734  2734 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 13:41:17.004  2734  2734 D BluetoothMapService: stop()
08-16 13:41:17.004  2734  2734 D BluetoothMapAppObserver: deinitObservers()
,08-16 13:41:17.008   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 13:41:17.009  2734  2734 D BluetoothMapAppObserver: removeReceiver()
08-16 13:41:17.013  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 13:41:17.013  2734  2734 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:17.014  1361  1361 D MapProfile: Bluetooth service disconnected
08-16 13:41:17.014  2734  2734 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:17.014  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:17.014  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:17.015  2734  2734 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:17.015  1522  2111 V NativeCrypto: Read error: ssl=0xaebeae00: I/O error during system call, Connection timed out
08-16 13:41:17.015  2734  2734 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:17.015  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:17.015  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:17.015  2734  2734 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 13:41:17.015  2734  2734 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 13:41:17.016  2734  2734 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:17.016  2734  2734 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:41:17.016  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:41:17.016  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:17.016  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:17.016  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:17.016  2734  2853 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 13:41:17.016  2734  2853 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:41:17.016  2734  2853 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 13:41:17.016  2734  2853 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:41:17.017  2734  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 13:41:17.017  2734  2759 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 13:41:17.016  2734  2734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 13:41:17.017  2734  2759 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 13:41:17.017  2734  2734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 13:41:17.018  2734  2734 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:41:17.018  2734  2734 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:17.018  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:17.018  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:17.018  2734  2734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 13:41:17.019  2734  2734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:41:17.019  2734  2734 D BluetoothMapService: MAP Service closeService in
08-16 13:41:17.019  2734  2734 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:41:17.019  2734  2734 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:17.019  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:17.020  2734  2734 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:17.020  2734  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 13:41:17.020  2734  2755 D BluetoothAdapterProperties: Setting state to 15
08-16 13:41:17.020  2734  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-16 13:41:17.020  2734  2734 D BluetoothMapService: cleanup()
08-16 13:41:17.020  2734  2734 D BluetoothMapService: MAP Service closeService in
08-16 13:41:17.020  2734  2755 I BluetoothAdapterState: Entering BleOnState
08-16 13:41:17.022  1522  2111 V NativeCrypto: SSL shutdown failed: ssl=0xaebeae00: I/O error during system call, Broken pipe
,08-16 13:41:17.025  1361  2019 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:41:17.025   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:17.026  1361  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:41:17.027  1361  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:41:17.027   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 13:41:17.027  1361  2208 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:41:17.028   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 13:41:17.028  1361  2019 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 13:41:17.028  1918  1930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:17.029   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:17.029  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:17.029  2734  2755 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 13:41:17.029  2734  2755 D BluetoothAdapterProperties: Setting state to 16
08-16 13:41:17.029  2734  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-16 13:41:17.030  2734  2755 D BluetoothAdapterProperties: onBleDisable
08-16 13:41:17.031  2734  2755 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:41:17.031  2734  2756 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 13:41:17.032  2734  2759 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:41:17.032  2734  2853 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 13:41:17.032  2734  2853 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:17.034  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.034  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:17.038  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.038  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:17.041   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:17.041  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.041  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:17.041  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.041  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:17.043  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.043  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:17.043  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.043  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:17.045  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:17.045  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:17.046  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:17.063   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 13:41:17.063   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 13:41:17.064   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-16 13:41:17.064   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 13:41:17.065   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 13:41:17.069   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 13:41:17.070  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:17.071  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:17.072  3459  3459 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5b9a066 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 13:41:17.072  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-16 13:41:17.072  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:17.082   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:41:17.085   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 13:41:17.085  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.085  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:17.086  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:17.086  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:17.087  2151  2324 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:41:17.088  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.088  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:17.089  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.089  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:17.091  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:17.091  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:17.094  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:17.094  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:17.097  4026  4026 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 13:41:17.106  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:41:17.112  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:41:17.112   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fe42ce8:true
,08-16 13:41:17.125   873  1387 I ActivityManager: Start proc 4047:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 13:41:17.132   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 13:41:17.133   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 13:41:17.152  4047  4047 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 13:41:17.157  4026  4026 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 13:41:17.159  4026  4026 D BluetoothMap: Create BluetoothMap proxy object
,08-16 13:41:17.168  4026  4026 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 13:41:17.180  4026  4026 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:41:17.194   873  1915 I ActivityManager: Killing 3634:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 13:41:17.239  2734  2759 I bt_hci  : shut_down
,08-16 13:41:17.261  2734  2764 I bt_vendor: low_power_mode_cb
,08-16 13:41:17.262  2734  2764 D bt_hwcfg: hw_epilog_process
,08-16 13:41:17.281  2734  2764 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 13:41:17.281  2734  2764 I bt_vendor: epilog_cb
,08-16 13:41:17.281  2734  2764 I bt_hci  : epilog_finished_callback
,08-16 13:41:17.287  2734  2759 I bt_hci_h4: hal_close
,08-16 13:41:17.288  2734  2759 I bt_userial_vendor: device fd = 51 close
,08-16 13:41:17.360  4047  4047 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.360  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.361  4047  4047 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:41:17.361  4047  4047 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:41:17.369  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 13:41:17.382  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:41:17.391  4026  4026 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:41:17.424   873  2705 I ActivityManager: Start proc 4078:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-16 13:41:17.428   873  2705 I ActivityManager: Killing 3459:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 13:41:17.516  2734  2756 D bt_stack_manager: event_shut_down_stack finished.
,08-16 13:41:17.517  2734  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-16 13:41:17.518  2734  2755 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 13:41:17.518  2734  2734 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 13:41:17.518  2734  2734 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:41:17.519  2734  2734 D BtGatt.GattService: stop()
08-16 13:41:17.519  2734  2734 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 13:41:17.520  2734  2734 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:17.520  2734  2734 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:17.520  2734  2734 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:17.520  2734  2734 V BluetoothAdapterState: isBleTurningOff()=true
08-16 13:41:17.520  2734  2755 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 13:41:17.521  2734  2755 D BluetoothAdapterProperties: Setting state to 10
08-16 13:41:17.521  2734  2755 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 13:41:17.521  2734  2755 I BluetoothAdapterState: Entering OffState
08-16 13:41:17.522   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 13:41:17.528  2734  2734 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 13:41:17.528  2734  2734 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 13:41:17.528  2734  2734 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 13:41:17.529  2734  2756 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 13:41:17.531  2734  2756 D bt_stack_manager: event_clean_up_stack finished.
,08-16 13:41:17.535  4078  4078 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 13:41:17.546  2734  2734 I art     : System.exit called, status: 0
,08-16 13:41:17.546  2734  2734 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 13:41:17.583  4047  4071 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 13:41:17.603   873  1915 I ActivityManager: Process com.android.bluetooth (pid 2734) has died
,08-16 13:41:17.682   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b67b5eb:true
,08-16 13:41:17.747  4078  4099 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 13:41:17.747  4078  4099 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 13:41:17.748  4078  4099 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-16 13:41:17.748  4078  4099 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 13:41:17.800  4078  4099 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 13:41:17.800  4078  4099 I Babel_SMS: MmsConfig.loadFromResources
08-16 13:41:17.801  4078  4099 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 13:41:17.813  4078  4099 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 13:41:17.882  4078  4078 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 13:41:17.885  4078  4078 I Babel_Crash: startup - clean
,08-16 13:41:17.924  4078  4078 I Babel_telephony: TeleModule.launchCompleted
,08-16 13:41:17.957   873  1702 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 13:41:17.971  4078  4078 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 13:41:17.977  4078  4078 W Babel   : BAM#gBA: invalid account id: -1
,08-16 13:41:17.978  4078  4078 W Babel   : BAM#gBA: invalid account id: -1
08-16 13:41:17.978  4078  4078 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 13:41:17.982  4078  4104 I Babel   : deleted: false for 0
,08-16 13:41:17.988   873  1915 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 13:41:18.012  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:41:18.020  1739  1739 D SystemUpdateService: onCreate
,08-16 13:41:18.028  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:41:18.047  1739  4106 I SystemUpdateService: active receiver: enabled
,08-16 13:41:18.078  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 13:41:18.083  1739  4106 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:41:18.086  1739  2415 I iu.UploadsManager: num queued entries: 0
,08-16 13:41:18.087  1739  2415 I iu.UploadsManager: num updated entries: 0
08-16 13:41:18.091  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:41:18.093  1739  2415 I iu.SyncManager: NEXT; no task
,08-16 13:41:18.095  1739  4106 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 13:41:18.095  1739  4106 I SystemUpdateService: now status is 0 (complete)
08-16 13:41:18.096  1739  4106 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 13:41:18.096  1739  4106 I SystemUpdateService: file has been verified
08-16 13:41:18.096  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 13:41:18.096  1739  4106 I SystemUpdateService: OTA package size = 12249756
,08-16 13:41:18.098  4078  4078 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:41:18.104  1739  4106 I SystemUpdateService: showing system update notification
,08-16 13:41:18.112   873   883 I ActivityManager: Start proc 4108:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 13:41:18.141  1739  1739 D SystemUpdateService: onDestroy
,08-16 13:41:18.165  4108  4108 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 13:41:18.175  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:18.181  4078  4078 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 13:41:18.187  4108  4108 D SprintDMHelper: simOperator: 
,08-16 13:41:18.187  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:41:18.191  4078  4078 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:41:18.193  4078  4078 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 13:41:18.196  4078  4078 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 13:41:18.205  4078  4078 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 13:41:18.217   873  3223 I ActivityManager: Start proc 4120:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 13:41:18.221   873  3223 I ActivityManager: Killing 3528:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 13:41:18.270  4078  4078 I vclib   : onServiceConnected
,08-16 13:41:18.375   873  1702 I ActivityManager: Start proc 4135:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 13:41:18.380  4078  4134 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-16 13:41:18.382   873  1953 I ActivityManager: Killing 3566:android.process.acore/u0a5 (adj 15): empty #17
,08-16 13:41:18.456  4135  4135 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 13:41:18.521  4135  4135 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 13:41:18.521  4135  4135 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 13:41:18.521  4135  4135 I GAv4    :   adb logcat -s GAv4
,08-16 13:41:18.538  4135  4135 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:41:18.545  4135  4135 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:41:18.564  4135  4152 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 13:41:18.687  4135  4135 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 13:41:18.729  4135  4135 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 13:41:18.738  4135  4135 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4359-4362)
08-16 13:41:18.738  4135  4135 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:41:18.752  4135  4135 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e0ef16}
,08-16 13:41:18.752  4135  4135 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 13:41:18.754  4135  4135 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 13:41:18.762  4135  4135 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 13:41:18.765  4135  4135 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 13:41:18.782  4135  4135 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 13:41:18.800  4135  4135 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 13:41:18.800  4135  4135 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 13:41:18.800  4135  4135 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 13:41:18.800  4135  4135 I Adreno  : Build Date                       : 10/20/15
08-16 13:41:18.800  4135  4135 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 13:41:18.800  4135  4135 I Adreno  : Local Branch                     : M14
08-16 13:41:18.800  4135  4135 I Adreno  : Remote Branch                    : 
08-16 13:41:18.800  4135  4135 I Adreno  : Remote Branch                    : 
08-16 13:41:18.800  4135  4135 I Adreno  : Reconstruct Branch               : 
,08-16 13:41:18.869  4135  4135 I NSApplication: Starting up...
,08-16 13:41:18.879  4135  4181 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 13:41:18.910   873  1947 I ActivityManager: Start proc 4186:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 13:41:18.911   873  1947 I ActivityManager: Killing 3778:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 13:41:19.008  4186  4186 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 13:41:19.226   873  1916 I ActivityManager: Killing 3795:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 13:41:19.930  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:41:19.945  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:41:19.949  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:41:20.010  1522  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 13:41:20.011  1522  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 13:41:20.011  1522  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:41:20.012  1522  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:41:20.059  3583  3583 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 13:41:20.060  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 13:41:20.061  3583  3583 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 13:41:21.951   873  1913 D WifiService: setWifiEnabled: true pid=3926, uid=10000
,08-16 13:41:21.951   873  1913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:21.968   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 13:41:21.977  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:21.978  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:21.979  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:21.979  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:21.984  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:21.984  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:21.985  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:21.988  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:21.989  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:21.989  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:21.989  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:21.989  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:22.007   873  1307 D WifiConfigStore: loaded 0 passpoint configs
08-16 13:41:22.008   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 13:41:22.009   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 13:41:22.010   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 13:41:22.010   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 13:41:22.010   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 13:41:22.010   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 13:41:22.031   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 13:41:22.032   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:41:22.032   372   871 D CommandListener: Setting iface cfg
08-16 13:41:22.032   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 13:41:22.032   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 13:41:22.041   873  1307 E native  : do suspend true
,08-16 13:41:22.041   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
08-16 13:41:22.042   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 13:41:22.065   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:41:22.646   873  1947 I ActivityManager: Killing 2217:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 13:41:23.429   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:41:23.467   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=8.88 delta 1000 -> 994
,08-16 13:41:23.472   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 13:41:23.472   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:23.495   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 13:41:23.576   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 13:41:23.579  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 13:41:23.995  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 13:41:24.035  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 13:41:24.037  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 13:41:24.045   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:41:24.062   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:41:24.063   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 13:41:24.063   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:24.086   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:24.102   372   871 D CommandListener: Setting iface cfg
,08-16 13:41:24.105   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 13:41:24.110   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 13:41:24.136   873  4213 D DhcpClient: Receive thread started
,08-16 13:41:24.220   873  1307 E native  : do suspend false
,08-16 13:41:24.240   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 13:41:24.253   873  4213 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172632, domain null
,08-16 13:41:24.255   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172632 seconds
,08-16 13:41:24.260   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 13:41:24.274   873  4213 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 13:41:24.275   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 13:41:24.281   372   871 D CommandListener: Setting iface cfg
,08-16 13:41:24.293   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 13:41:24.293   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-16 13:41:24.297   873  1307 E native  : do suspend true
,08-16 13:41:24.328   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 13:41:24.331   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 13:41:24.333   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 13:41:24.337   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 13:41:24.348   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 13:41:24.433   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 13:41:24.434   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 13:41:24.437   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 13:41:24.440   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 13:41:24.444   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 13:41:24.465   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 13:41:24.480   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 13:41:24.480   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 13:41:24.482   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 13:41:24.483   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 13:41:24.483   873  1309 D ConnectivityService:    accepting network in place of null
08-16 13:41:24.485   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 13:41:24.487   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:41:24.496   873  4212 D NetlinkSocketObserver: NeighborEvent{elapsedMs=190119, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 13:41:24.531   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:24.561   873  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.238,2a00:1450:4001:801::200e
,08-16 13:41:24.592   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:24.601   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 13:41:24.601   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:24.612   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:41:24.619  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:24.620  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:24.620  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:24.620  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.620   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 13:41:24.626  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:24.626  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 13:41:24.627  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:24.627  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.630  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:24.630  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:24.630  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:24.630  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:24.633   873  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:41:24 GMT], X-Android-Received-Millis=[1471347684632], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471347684606]}
,08-16 13:41:24.634   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 13:41:24.635   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 13:41:24.635   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 13:41:24.637   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 13:41:24.648  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 13:41:24.654  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:41:24.660  1739  1739 D SystemUpdateService: onCreate
,08-16 13:41:24.665  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:41:24.683  1739  4224 I SystemUpdateService: active receiver: enabled
,08-16 13:41:24.689  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 13:41:24.692  1739  2415 I iu.UploadsManager: num queued entries: 0
,08-16 13:41:24.692  1739  2415 I iu.UploadsManager: num updated entries: 0
,08-16 13:41:24.696  1739  4224 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:41:24.702  1739  4224 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 13:41:24.702  1739  4224 I SystemUpdateService: now status is 0 (complete)
08-16 13:41:24.702  1739  4224 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:41:24.702  1739  4224 I SystemUpdateService: file has been verified
08-16 13:41:24.703  1739  4224 I SystemUpdateService: OTA package size = 12249756
08-16 13:41:24.704  1739  2415 I iu.SyncManager: NEXT; no task
,08-16 13:41:24.706  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:41:24.707  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 13:41:24.709  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:24.711  1739  4227 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 13:41:24.712  1739  4227 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 13:41:24.717  1739  4227 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:41:24.721  4108  4108 D SprintDMHelper: simOperator: 
08-16 13:41:24.722  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:41:24.733  1739  4224 I SystemUpdateService: showing system update notification
,08-16 13:41:24.805  1522  4008 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 13:41:24.805  1522  4008 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 13:41:24.805  1522  4008 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:41:24.805  1522  4008 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:41:24.831  1739  1739 D SystemUpdateService: onDestroy
,08-16 13:41:24.841  1739  4227 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-16 13:41:24.854  4078  4231 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 13:41:25.601   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 13:41:26.964   873  1954 D WifiService: setWifiEnabled: false pid=3926, uid=10000
,08-16 13:41:26.964   873  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:26.996  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 13:41:27.000   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 13:41:27.001   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 13:41:27.001   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:41:27.001   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:27.027   873  1307 E native  : do suspend true
,08-16 13:41:27.038   873  1866 D DhcpClient: Clearing IP address
,08-16 13:41:27.039   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 13:41:27.044   372   871 D CommandListener: Setting iface cfg
,08-16 13:41:27.048  1522  4236 V NativeCrypto: Read error: ssl=0xaa1fc200: I/O error during system call, Connection timed out
,08-16 13:41:27.050   873  4213 D DhcpClient: Receive thread stopped
,08-16 13:41:27.050  1522  4236 V NativeCrypto: SSL shutdown failed: ssl=0xaa1fc200: I/O error during system call, Broken pipe
,08-16 13:41:27.054   873  1913 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-16 13:41:27.055   873  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-16 13:41:27.055   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 13:41:27.056   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 13:41:27.059   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 13:41:27.060   448   448 E Parcel  : Reading a NULL string not supported here.
,08-16 13:41:27.060   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 13:41:27.060   873  1307 E native  : do suspend true
,08-16 13:41:27.064   873  4211 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-16 13:41:27.075   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 13:41:27.077   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 13:41:27.079   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:41:27.096   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:41:27.099  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:27.099  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:27.100  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:27.100  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:27.100  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:27.101  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:27.101  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:27.101  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:27.101  2151  2324 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 13:41:27.101   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 13:41:27.102  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:27.102  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:27.102  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:27.102  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:27.117   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:27.151   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:27.152   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 13:41:27.152   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:27.154   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:41:27.158  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:27.159  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:27.160  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 13:41:27.169  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 13:41:27.176  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:41:27.182  1739  1739 D SystemUpdateService: onCreate
,08-16 13:41:27.187  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:41:27.200  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 13:41:27.209  1739  2415 I iu.UploadsManager: num queued entries: 0
,08-16 13:41:27.211  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 13:41:27.212  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 13:41:27.215  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:27.220  1739  4247 I SystemUpdateService: active receiver: enabled
08-16 13:41:27.221  4108  4108 D SprintDMHelper: simOperator: 
,08-16 13:41:27.221  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:41:27.230  1739  2415 I iu.UploadsManager: num updated entries: 0
,08-16 13:41:27.241  4078  4251 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 13:41:27.248  1739  2415 I iu.SyncManager: NEXT; no task
,08-16 13:41:27.250   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 13:41:27.251   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 13:41:27.251   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 13:41:27.250  1739  4247 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 13:41:27.256  1739  4247 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 13:41:27.256  1739  4247 I SystemUpdateService: now status is 0 (complete)
08-16 13:41:27.256  1739  4247 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:41:27.256  1739  4247 I SystemUpdateService: file has been verified
08-16 13:41:27.256  1739  4247 I SystemUpdateService: OTA package size = 12249756
,08-16 13:41:27.260  1739  4247 I SystemUpdateService: showing system update notification
,08-16 13:41:27.269  1739  1739 D SystemUpdateService: onDestroy
,08-16 13:41:32.020   873   890 I ActivityManager: Start proc 4253:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 13:41:32.148  4253  4253 D AdapterServiceConfig: Adding HeadsetService
,08-16 13:41:32.149  4253  4253 D AdapterServiceConfig: Adding A2dpService
,08-16 13:41:32.150  4253  4253 D AdapterServiceConfig: Adding HidService
,08-16 13:41:32.151  4253  4253 D AdapterServiceConfig: Adding HealthService
,08-16 13:41:32.151  4253  4253 D AdapterServiceConfig: Adding PanService
,08-16 13:41:32.152  4253  4253 D AdapterServiceConfig: Adding GattService
,08-16 13:41:32.152  4253  4253 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 13:41:32.170   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51a7962:true
,08-16 13:41:32.170  4253  4253 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 13:41:32.173  4253  4253 I bt_bluedroid: init
08-16 13:41:32.173  4253  4265 I BluetoothAdapterState: Entering OffState
,08-16 13:41:32.175  4253  4266 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 13:41:32.175  4253  4266 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:41:32.175  4253  4266 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 13:41:32.175  4253  4266 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 13:41:32.175  4253  4253 I bt_bluedroid: get_profile_interface socket
,08-16 13:41:32.177  4253  4253 I bt_bluedroid: get_profile_interface sdp
,08-16 13:41:32.177  4253  4269 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:41:32.178  4253  4269 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 13:41:32.180  4253  4264 I bt_bluedroid: config_hci_snoop_log
,08-16 13:41:32.183   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 13:41:32.194  4253  4265 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 13:41:32.194  4253  4265 D BluetoothAdapterProperties: Setting state to 14
,08-16 13:41:32.194  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-16 13:41:32.195  4253  4265 D BluetoothBondStateMachine: make
,08-16 13:41:32.197  4253  4270 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 13:41:32.199  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:41:32.199  4253  4253 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 13:41:32.204  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:32.205  4253  4253 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:41:32.206  4253  4253 D BtGatt.GattService: Received start request. Starting profile...
,08-16 13:41:32.206  4253  4253 D BtGatt.GattService: start()
,08-16 13:41:32.206  4253  4253 I bt_bluedroid: get_profile_interface gatt
08-16 13:41:32.207  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:32.207  4253  4253 D BtGatt.AdvertiseManager: advertise manager created
,08-16 13:41:32.212  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:32.212  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:32.212  4253  4253 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 13:41:32.212  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:32.212  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 13:41:32.213  4253  4265 I bt_bluedroid: enable
,08-16 13:41:32.213  4253  4266 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 13:41:32.213  4253  4266 I bt_hci  : start_up
,08-16 13:41:32.217  4253  4266 I bt_vendor: alloc value 0xb3a40189
,08-16 13:41:32.218  4253  4266 I bt_vendor: init
08-16 13:41:32.218  4253  4266 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 13:41:32.218  4253  4266 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 13:41:32.325  4253  4266 D bt_hci  : start_up starting async portion
,08-16 13:41:32.326  4253  4273 I bt_hci  : event_finish_startup
,08-16 13:41:32.326  4253  4273 I bt_hci_h4: hal_open
,08-16 13:41:32.327  4253  4273 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 13:41:32.337  4253  4273 I bt_userial_vendor: device fd = 51 open
,08-16 13:41:32.367  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:41:32.399  4253  4273 D bt_hwcfg: Chipset BCM4354A2
08-16 13:41:32.399  4253  4273 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 13:41:32.400  4253  4273 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 13:41:32.483   873  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-16 13:41:33.061  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 13:41:33.063  4253  4273 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 13:41:33.063  4253  4273 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 13:41:33.181  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:41:33.182  4253  4273 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 13:41:33.211  4253  4273 I bt_hwcfg: vendor lib fwcfg completed
,08-16 13:41:33.211  4253  4273 I bt_vendor: firmware callback
08-16 13:41:33.211  4253  4273 I bt_hci  : firmware_config_callback
,08-16 13:41:33.224  4253  4275 I bt_btu  : btu_task pending for preload complete event
,08-16 13:41:33.224  4253  4275 I bt_btu_task: Bluetooth chip preload is complete
,08-16 13:41:33.225  4253  4275 I bt_btu  : btu_task received preload complete event
,08-16 13:41:33.235  4253  4275 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 13:41:33.235  4253  4275 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 13:41:33.236  4253  4275 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:41:33.236  4253  4275 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:41:33.236  4253  4275 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 13:41:33.236  4253  4275 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 13:41:33.237  4253  4275 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:41:33.237  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 13:41:33.237  4253  4275 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:41:33.237  4253  4275 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:41:33.238  4253  4275 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 13:41:33.238  4253  4275 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:41:33.238  4253  4275 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:41:33.238  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 13:41:33.239  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 13:41:33.370  4253  4275 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bdd9d
,08-16 13:41:33.371  4253  4275 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bdd9d 
,08-16 13:41:33.393  4253  4269 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 13:41:33.394  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 13:41:33.395  4253  4269 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:41:33.400  4253  4269 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:41:33.404  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
,08-16 13:41:33.405  4253  4269 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:41:33.405  4253  4269 D bt_hci  : do_postload posting postload work item
08-16 13:41:33.407  4253  4273 I bt_hci  : event_postload
08-16 13:41:33.407  4253  4273 I bt_vendor: sco_config_cb
08-16 13:41:33.407  4253  4273 I bt_hci  : sco_config_callback postload finished.
08-16 13:41:33.409  4253  4269 D bt_bte_conf: Device ID record 1 : primary
08-16 13:41:33.409  4253  4269 D bt_bte_conf:   vendorId            = 000f
,08-16 13:41:33.410  4253  4269 D bt_bte_conf:   vendorIdSource      = 0001
08-16 13:41:33.410  4253  4269 D bt_bte_conf:   product             = 1200
,08-16 13:41:33.410  4253  4269 D bt_bte_conf:   version             = 1436
08-16 13:41:33.410  4253  4269 D bt_bte_conf:   clientExecutableURL = 
,08-16 13:41:33.410  4253  4269 D bt_bte_conf:   serviceDescription  = 
,08-16 13:41:33.411  4253  4269 D bt_bte_conf:   documentationURL    = 
,08-16 13:41:33.411  4253  4269 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 13:41:33.411  4253  4266 D bt_stack_manager: event_start_up_stack finished
08-16 13:41:33.411  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:33.414  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 13:41:33.414  4253  4273 I bt_vendor: low_power_mode_cb
08-16 13:41:33.414  4253  4265 D BluetoothAdapterProperties: Setting state to 15
08-16 13:41:33.414  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 13:41:33.416  4253  4265 I BluetoothAdapterState: Entering BleOnState
,08-16 13:41:33.416  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:33.420  4253  4265 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 13:41:33.420  4253  4265 D BluetoothAdapterProperties: Setting state to 11
08-16 13:41:33.420  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 13:41:33.424  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:33.433  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:33.433  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:33.435  4253  4253 D HeadsetService: Received start request. Starting profile...
08-16 13:41:33.435  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:33.436  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:33.440  4253  4253 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 13:41:33.440  4253  4253 D HeadsetStateMachine: make
,08-16 13:41:33.450  4253  4253 D HeadsetStateMachine: max_hf_connections = 1
,08-16 13:41:33.451  4253  4253 I bt_bluedroid: get_profile_interface handsfree
,08-16 13:41:33.452  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 13:41:33.453  4253  4269 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-16 13:41:33.453  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:41:33.457  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:33.458  4253  4253 D A2dpService: Received start request. Starting profile...
,08-16 13:41:33.459  4253  4253 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 13:41:33.459  4253  4253 I bt_bluedroid: get_profile_interface avrcp
,08-16 13:41:33.468  4253  4253 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 13:41:33.468  4253  4253 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:41:33.468  4253  4253 D A2dpStateMachine: make
,08-16 13:41:33.470  4253  4253 I bt_bluedroid: get_profile_interface a2dp
,08-16 13:41:33.472  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 13:41:33.476  4253  4284 D A2dpStateMachine: Enter Disconnected: -2
,08-16 13:41:33.478  4253  4253 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 13:41:33.480  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:41:33.480  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:33.482  4026  4026 D BluetoothInputDevice: Proxy object connected
08-16 13:41:33.482  4253  4253 D HidService: Received start request. Starting profile...
,08-16 13:41:33.483  4253  4253 I bt_bluedroid: get_profile_interface hidhost
08-16 13:41:33.483  4253  4253 D HidService: setHidService(): set to: null
08-16 13:41:33.483  4253  4269 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399f3e5
08-16 13:41:33.483  4253  4253 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 13:41:33.484  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 13:41:33.484  4026  4026 D HidProfile: Bluetooth service connected
08-16 13:41:33.484  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:33.485  4253  4253 D HealthService: Received start request. Starting profile...
,08-16 13:41:33.488  4253  4253 I bt_bluedroid: get_profile_interface health
,08-16 13:41:33.490  4253  4253 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 13:41:33.491  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:33.493  4026  4026 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 13:41:33.494  4253  4253 D PanService: Received start request. Starting profile...
08-16 13:41:33.494  4026  4026 D PanProfile: Bluetooth service connected
08-16 13:41:33.494  4253  4253 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:41:33.494  4253  4253 I bt_bluedroid: get_profile_interface pan
,08-16 13:41:33.495  4253  4269 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 13:41:33.500  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:33.503  4026  4026 D BluetoothMap: Proxy object connected
,08-16 13:41:33.503  4253  4253 D BluetoothMapService: Received start request. Starting profile...
08-16 13:41:33.503  4253  4253 D BluetoothMapService: start(),
08-16 13:41:33.503  4026  4026 D MapProfile: Bluetooth service connected
,08-16 13:41:33.503  4026  4026 D BluetoothMap: getConnectedDevices()
08-16 13:41:33.504  4026  4026 D BluetoothMap: Bluetooth is Not enabled
08-16 13:41:33.506  4253  4253 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 13:41:33.508  4253  4253 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 13:41:33.508  4253  4253 D BluetoothMapAppObserver: createReceiver()
,08-16 13:41:33.509  4253  4253 D BluetoothMapAppObserver: initObservers()
,08-16 13:41:33.509  4253  4253 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 13:41:33.517  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:33.517  4253  4253 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:33.518  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.518  4253  4282 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 13:41:33.518  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:33.521  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:33.521  4253  4253 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:33.521  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.521  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:33.522  4253  4253 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:33.522  4253  4253 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:33.522  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.522  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:41:33.523  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.524  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:33.524  4253  4253 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:33.524  4253  4253 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:33.524  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:33.524  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:33.525  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 13:41:33.525  4253  4265 D BluetoothAdapterProperties: ScanMode =  20
,08-16 13:41:33.525  4253  4265 D BluetoothAdapterProperties: State =  11
08-16 13:41:33.528  4253  4269 D BluetoothAdapterProperties: Scan Mode:21
,08-16 13:41:33.528  4253  4269 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:41:33.529  4253  4265 D BluetoothAdapterProperties: Setting state to 12
08-16 13:41:33.529  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 13:41:33.530  1361  1372 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 13:41:33.531  4253  4265 I BluetoothAdapterState: Entering OnState
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:33.533  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:33.533  1361  1361 D BluetoothMap: Proxy object connected
08-16 13:41:33.533  1361  1361 D MapProfile: Bluetooth service connected
08-16 13:41:33.533  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 13:41:33.534   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:33.535  1361  2208 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:41:33.536  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:33.537  4026  4036 D BluetoothMap: onBluetoothStateChange: up=true
08-16 13:41:33.537  1361  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 13:41:33.539  1361  1361 D BluetoothInputDevice: Proxy object connected
,08-16 13:41:33.539  1361  1361 D HidProfile: Bluetooth service connected
08-16 13:41:33.540  4253  4253 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:41:33.540  4026  4037 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 13:41:33.541  4253  4253 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 13:41:33.541  4026  4036 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:33.542  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:33.542  4253  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:33.544   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:41:33.545  1361  1372 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:41:33.545  4253  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:41:33.546  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:33.547  4253  4253 D ObexServerSockets: Succeed to create listening sockets 
08-16 13:41:33.548  4253  4253 D ObexServerSockets0: startAccept()
08-16 13:41:33.548  4253  4253 D ObexServerSockets0: prepareForNewConnect()
08-16 13:41:33.548   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:33.548  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:41:33.548  1361  1361 D PanProfile: Bluetooth service connected
08-16 13:41:33.548  1361  2019 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:33.551  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:33.551  1918  2055 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:41:33.552  4026  4037 D BluetoothPan: onBluetoothStateChange on: true
,08-16 13:41:33.552  4253  4253 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 13:41:33.552   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:33.552  4253  4253 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 13:41:33.553  1361  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:33.553  4253  4291 D ObexServerSockets0: Accepting socket connection...
08-16 13:41:33.553   873   873 D BluetoothA2dp: Proxy object connected
08-16 13:41:33.555  4253  4292 D ObexServerSockets0: Accepting socket connection...
08-16 13:41:33.555  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:33.557  4253  4253 D BluetoothMapService: onReceive
08-16 13:41:33.560  4253  4253 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:41:33.560  4253  4253 D BluetoothMapService: STATE_ON
08-16 13:41:33.554  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 13:41:33.561  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:33.561  4026  4026 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 13:41:33.562  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:33.563   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 13:41:33.564  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:33.565  4026  4026 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 13:41:33.573  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 13:41:33.576  4026  4026 D BluetoothA2dp: Proxy object connected
,08-16 13:41:33.579  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:41:33.585  4026  4026 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:41:33.586  4253  4253 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:41:33.586  4253  4253 D ObexServerSockets0: prepareForNewConnect()
08-16 13:41:33.587  4026  4026 D BluetoothPbap: Proxy object connected
08-16 13:41:33.587  4026  4026 D PbapServerProfile: Bluetooth service connected
08-16 13:41:33.588  1361  1361 D BluetoothPbap: Proxy object connected
08-16 13:41:33.588  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-16 13:41:33.594  4253  4296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:33.608  4253  4300 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:33.610  4253  4300 I BtOppRfcommListener: Accept thread started.
,08-16 13:41:33.636  1918  1930 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.637  1361  2208 D BluetoothHeadset: Proxy object connected
08-16 13:41:33.637   873   873 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.637  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:33.637   873   873 D BluetoothHeadset: Proxy object connected
08-16 13:41:33.637   873   873 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.649   873   890 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.651  1918  1931 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.653   873   890 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.654  1361  2019 D BluetoothHeadset: Proxy object connected
08-16 13:41:33.654  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:33.669  4026  4036 D BluetoothHeadset: Proxy object connected
,08-16 13:41:33.670  4026  4026 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:36.984  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:36.984  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:41:36.986  4253  4265 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 13:41:36.986  4253  4265 D BluetoothAdapterProperties: Setting state to 13
,08-16 13:41:36.986  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 13:41:36.989  4253  4265 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 13:41:36.990  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:36.990  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd399ba removed from the list
08-16 13:41:36.990  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:36.991  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:36.991  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:36.994  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:36.995  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d407c8 added. We now have 4 listener(s)
,08-16 13:41:36.995  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:41:36.996  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:41:37.008  4253  4253 D BluetoothMapService: onReceive
08-16 13:41:37.008  4253  4253 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:41:37.008  4253  4253 D BluetoothMapService: STATE_TURNING_OFF
08-16 13:41:37.008  4253  4253 D BluetoothMapService: MAP Service closeService in
08-16 13:41:37.008  4253  4253 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 13:41:37.008  4253  4253 D ObexServerSockets0: shutdown(block = true)
,08-16 13:41:37.009  4253  4253 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:41:37.010  4253  4253 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 13:41:37.010  4253  4277 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 13:41:37.011  4253  4291 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 13:41:37.011  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:41:37.012  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 13:41:37.013  4253  4292 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 13:41:37.014  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:41:37.014  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d407c8 removed from the list
,08-16 13:41:37.014  4253  4253 D HeadsetService: Received stop request...Stopping profile...
08-16 13:41:37.014  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:37.015  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:37.015  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:37.015  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:37.015  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c567061 added. We now have 4 listener(s)
,08-16 13:41:37.016  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:41:37.016  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:37.016  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:37.017  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:37.017  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:37.018  4253  4253 I BtOppRfcommListener: stopping Accept Thread
08-16 13:41:37.019  4253  4300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 13:41:37.019  4026  4037 D BluetoothHeadset: Proxy object disconnected
,08-16 13:41:37.019  4253  4300 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 13:41:37.021  1918  2055 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:37.021  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 13:41:37.021  1361  2019 D BluetoothHeadset: Proxy object disconnected
,08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:37.021  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:37.021  4253  4253 D A2dpService: Received stop request...Stopping profile...
08-16 13:41:37.022   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:37.022   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 13:41:37.022   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 13:41:37.022  4253  4284 D A2dpStateMachine: Exit Disconnected: -1
08-16 13:41:37.022  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 13:41:37.022  3926  3926 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 13:41:37.022  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:37.024  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 23
08-16 13:41:37.024  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.025  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.027   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 13:41:37.029  4253  4253 D HidService: Received stop request...Stopping profile...
,08-16 13:41:37.029  4253  4253 D HidService: Stopping Bluetooth HidService
08-16 13:41:37.030  4253  4253 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:37.030  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:37.030  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:37.030  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:37.031  4253  4253 D HealthService: Received stop request...Stopping profile...
,08-16 13:41:37.032  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 13:41:37.032  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 13:41:37.033  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 13:41:37.033  1361  1361 D HidProfile: Bluetooth service disconnected
,08-16 13:41:37.033  4026  4026 D HeadsetProfile: Bluetooth service disconnected
08-16 13:41:37.034  4253  4253 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 13:41:37.034  4253  4253 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 13:41:37.035  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:37.035  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:41:37.035  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:37.035  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 13:41:37.035  4253  4269 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 13:41:37.036  4253  4253 D PanService: Received stop request...Stopping profile...
,08-16 13:41:37.039  4253  4253 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 13:41:37.039  4253  4253 D BluetoothMapService: stop()
08-16 13:41:37.040  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 13:41:37.040  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 13:41:37.040  4253  4253 D BluetoothMapAppObserver: deinitObservers()
,08-16 13:41:37.040  4253  4253 D BluetoothMapAppObserver: removeReceiver()
,08-16 13:41:37.042  4253  4253 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:41:37.042  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 13:41:37.041  4026  4026 D DockEventReceiver: finishStartingService: stopping service
08-16 13:41:37.042  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:37.042  1361  1361 D MapProfile: Bluetooth service disconnected
,08-16 13:41:37.042  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:37.042  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:37.044  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 13:41:37.044  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:37.044  4026  4026 D BluetoothA2dp: Proxy object disconnected
08-16 13:41:37.044  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 13:41:37.044  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:41:37.044  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 13:41:37.044  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 13:41:37.044  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 13:41:37.045  4026  4026 D BluetoothInputDevice: Proxy object disconnected
08-16 13:41:37.045  4026  4026 D HidProfile: Bluetooth service disconnected
08-16 13:41:37.045  4253  4253 V BluetoothAdapterState: isTurningOff()=true,
,08-16 13:41:37.045  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:37.045  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:41:37.045  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:37.045  4026  4026 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 13:41:37.046  4253  4253 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 13:41:37.046  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 13:41:37.046  4253  4253 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 13:41:37.046  4253  4253 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:41:37.047  4253  4253 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:41:37.047  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:37.047  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false,
08-16 13:41:37.045  4026  4026 D PanProfile: Bluetooth service disconnected
08-16 13:41:37.048  4253  4253 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 13:41:37.048  4253  4269 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 13:41:37.048  4253  4253 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 13:41:37.049  4253  4253 V BluetoothAdapterState: isTurningOff()=true
08-16 13:41:37.049  4253  4253 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:41:37.049  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:37.049  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:37.049  4253  4253 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 13:41:37.049  4253  4253 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 13:41:37.050  4253  4253 D BluetoothMapService: MAP Service closeService in
08-16 13:41:37.050  4253  4253 V BluetoothAdapterState: isTurningOff()=true
,08-16 13:41:37.050  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:37.050  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false,
,08-16 13:41:37.050  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:37.050  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 13:41:37.051  4253  4265 D BluetoothAdapterProperties: Setting state to 15
,08-16 13:41:37.051  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 13:41:37.051  1361  1372 D BluetoothMap: onBluetoothStateChange: up=false
08-16 13:41:37.051  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:41:37.052  4253  4265 I BluetoothAdapterState: Entering BleOnState
08-16 13:41:37.052   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-16 13:41:37.052  4253  4253 D BluetoothMapService: cleanup()
08-16 13:41:37.052  4253  4253 D BluetoothMapService: MAP Service closeService in
08-16 13:41:37.052  1361  1375 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 13:41:37.053  4026  4026 D BluetoothMap: Proxy object disconnected
,08-16 13:41:37.053  4026  4026 D MapProfile: Bluetooth service disconnected
08-16 13:41:37.053  4026  4036 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 13:41:37.054  1361  2208 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 13:41:37.055  4026  4036 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 13:41:37.055  4026  4037 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 13:41:37.057   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 13:41:37.057  1361  2019 D BluetoothPan: onBluetoothStateChange on: false
08-16 13:41:37.058  4026  4036 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 13:41:37.060   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:37.060  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 13:41:37.060  1918  1930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:37.061  4026  4037 D BluetoothPan: onBluetoothStateChange on: false,
08-16 13:41:37.061   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:37.061  1361  1375 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-16 13:41:37.062  4026  4036 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 13:41:37.062  4253  4265 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 13:41:37.062  4253  4265 D BluetoothAdapterProperties: Setting state to 16
,08-16 13:41:37.062  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 13:41:37.063  4253  4265 D BluetoothAdapterProperties: onBleDisable
08-16 13:41:37.065  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:41:37.065  4253  4266 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 13:41:37.065  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.066  4253  4275 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 13:41:37.066  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 13:41:37.067  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.067  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:41:37.068  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 13:41:37.068  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.070  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:37.073  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 13:41:37.079  4026  4026 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:41:37.268  4253  4269 I bt_hci  : shut_down
,08-16 13:41:37.270  4253  4273 D bt_hwcfg: hw_epilog_process
,08-16 13:41:37.271  4253  4273 I bt_vendor: low_power_mode_cb
,08-16 13:41:37.291  4253  4273 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 13:41:37.292  4253  4273 I bt_vendor: epilog_cb
,08-16 13:41:37.292  4253  4273 I bt_hci  : epilog_finished_callback
,08-16 13:41:37.301  4253  4269 I bt_hci_h4: hal_close
,08-16 13:41:37.302  4253  4269 I bt_userial_vendor: device fd = 51 close
,08-16 13:41:37.437  4253  4266 D bt_stack_manager: event_shut_down_stack finished.
,08-16 13:41:37.438  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 13:41:37.447  4253  4253 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:41:37.447  4253  4265 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 13:41:37.448  4253  4253 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 13:41:37.449  4253  4253 D BtGatt.GattService: stop()
,08-16 13:41:37.449  4253  4253 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 13:41:37.454  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:37.455  4253  4253 V BluetoothAdapterState: isTurningOn()=false
08-16 13:41:37.455  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:37.455  4253  4253 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 13:41:37.456  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 13:41:37.457  4253  4265 D BluetoothAdapterProperties: Setting state to 10
,08-16 13:41:37.457  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 13:41:37.458  4253  4265 I BluetoothAdapterState: Entering OffState
,08-16 13:41:37.460   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 13:41:37.489  4253  4253 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 13:41:37.490  4253  4253 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 13:41:37.490  4253  4266 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 13:41:37.500  4253  4266 D bt_stack_manager: event_clean_up_stack finished.
,08-16 13:41:37.500  4253  4253 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 13:41:37.508  4253  4253 I art     : System.exit called, status: 0
,08-16 13:41:37.509  4253  4253 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 13:41:37.567   873  1702 I ActivityManager: Process com.android.bluetooth (pid 4253) has died
,08-16 13:41:42.028  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:42.076   873   890 I ActivityManager: Start proc 4310:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 13:41:42.207  4310  4310 D AdapterServiceConfig: Adding HeadsetService
,08-16 13:41:42.207  4310  4310 D AdapterServiceConfig: Adding A2dpService
,08-16 13:41:42.208  4310  4310 D AdapterServiceConfig: Adding HidService
,08-16 13:41:42.208  4310  4310 D AdapterServiceConfig: Adding HealthService
,08-16 13:41:42.208  4310  4310 D AdapterServiceConfig: Adding PanService
,08-16 13:41:42.208  4310  4310 D AdapterServiceConfig: Adding GattService
,08-16 13:41:42.208  4310  4310 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 13:41:42.223   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@665cc17:true
,08-16 13:41:42.224  4310  4310 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 13:41:42.229  4310  4310 I bt_bluedroid: init
,08-16 13:41:42.229  4310  4322 I BluetoothAdapterState: Entering OffState
,08-16 13:41:42.234  4310  4323 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 13:41:42.235  4310  4323 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 13:41:42.235  4310  4323 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 13:41:42.236  4310  4323 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 13:41:42.237  4310  4310 I bt_bluedroid: get_profile_interface socket
,08-16 13:41:42.240  4310  4310 I bt_bluedroid: get_profile_interface sdp
,08-16 13:41:42.245  4310  4321 I bt_bluedroid: config_hci_snoop_log
,08-16 13:41:42.246  4310  4326 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 13:41:42.248  4310  4326 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 13:41:42.248   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 13:41:42.257  4310  4322 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 13:41:42.258  4310  4322 D BluetoothAdapterProperties: Setting state to 14
08-16 13:41:42.258  4310  4322 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 13:41:42.262  4310  4322 D BluetoothBondStateMachine: make
,08-16 13:41:42.267  4310  4327 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 13:41:42.276  4310  4322 I BluetoothAdapterState: Entering PendingCommandState
,08-16 13:41:42.276  4310  4310 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 13:41:42.281  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:42.282  4310  4310 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 13:41:42.284  4310  4310 D BtGatt.GattService: Received start request. Starting profile...
08-16 13:41:42.284  4310  4310 D BtGatt.GattService: start()
,08-16 13:41:42.284  4310  4310 I bt_bluedroid: get_profile_interface gatt
,08-16 13:41:42.286  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:42.287  4310  4310 D BtGatt.AdvertiseManager: advertise manager created
,08-16 13:41:42.302  4310  4310 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:42.302  4310  4310 V BluetoothAdapterState: isTurningOn()=false
,08-16 13:41:42.302  4310  4310 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 13:41:42.303  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:42.305  4310  4322 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 13:41:42.306  4310  4322 I bt_bluedroid: enable
,08-16 13:41:42.306  4310  4323 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 13:41:42.307  4310  4323 I bt_hci  : start_up
,08-16 13:41:42.328  4310  4323 I bt_vendor: alloc value 0xb3a40189
,08-16 13:41:42.328  4310  4323 I bt_vendor: init
08-16 13:41:42.328  4310  4323 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 13:41:42.328  4310  4323 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 13:41:42.435  4310  4323 D bt_hci  : start_up starting async portion
,08-16 13:41:42.436  4310  4330 I bt_hci  : event_finish_startup
,08-16 13:41:42.436  4310  4330 I bt_hci_h4: hal_open
08-16 13:41:42.437  4310  4330 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 13:41:42.447  4310  4330 I bt_userial_vendor: device fd = 51 open
,08-16 13:41:42.477  4310  4330 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:41:42.509  4310  4330 D bt_hwcfg: Chipset BCM4354A2
08-16 13:41:42.509  4310  4330 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 13:41:42.510  4310  4330 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 13:41:43.173  4310  4330 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 13:41:43.175  4310  4330 D bt_hwcfg: Settlement delay -- 100 ms
08-16 13:41:43.175  4310  4330 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 13:41:43.292  4310  4330 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 13:41:43.293  4310  4330 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 13:41:43.323  4310  4330 I bt_hwcfg: vendor lib fwcfg completed
,08-16 13:41:43.323  4310  4330 I bt_vendor: firmware callback
,08-16 13:41:43.323  4310  4330 I bt_hci  : firmware_config_callback
,08-16 13:41:43.334  4310  4332 I bt_btu  : btu_task pending for preload complete event
08-16 13:41:43.335  4310  4332 I bt_btu_task: Bluetooth chip preload is complete
08-16 13:41:43.335  4310  4332 I bt_btu  : btu_task received preload complete event
,08-16 13:41:43.346  4310  4332 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 13:41:43.346  4310  4332 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 13:41:43.346  4310  4332 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 13:41:43.347  4310  4332 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 13:41:43.347  4310  4332 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 13:41:43.347  4310  4332 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 13:41:43.348  4310  4332 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 13:41:43.348  4310  4332 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 13:41:43.348  4310  4332 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 13:41:43.348  4310  4332 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 13:41:43.349  4310  4332 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 13:41:43.349  4310  4332 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 13:41:43.349  4310  4332 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 13:41:43.350  4310  4332 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 13:41:43.350  4310  4332 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 13:41:43.485  4310  4332 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bdd9d,
08-16 13:41:43.485  4310  4332 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bdd9d 
,08-16 13:41:43.496  4310  4326 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-16 13:41:43.498  4310  4326 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
,08-16 13:41:43.498  4310  4326 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 13:41:43.501  4310  4326 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 13:41:43.505  4310  4326 D BluetoothAdapterProperties: Scan Mode:20
08-16 13:41:43.505  4310  4326 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 13:41:43.505  4310  4326 D bt_hci  : do_postload posting postload work item
,08-16 13:41:43.506  4310  4330 I bt_hci  : event_postload
08-16 13:41:43.506  4310  4330 I bt_vendor: sco_config_cb
08-16 13:41:43.506  4310  4330 I bt_hci  : sco_config_callback postload finished.
08-16 13:41:43.510  4310  4326 D bt_bte_conf: Device ID record 1 : primary
08-16 13:41:43.510  4310  4326 D bt_bte_conf:   vendorId            = 000f
08-16 13:41:43.510  4310  4326 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 13:41:43.510  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:43.510  4310  4326 D bt_bte_conf:   product             = 1200
,08-16 13:41:43.510  4310  4326 D bt_bte_conf:   version             = 1436
,08-16 13:41:43.511  4310  4326 D bt_bte_conf:   clientExecutableURL = 
08-16 13:41:43.511  4310  4326 D bt_bte_conf:   serviceDescription  = 
,08-16 13:41:43.511  4310  4326 D bt_bte_conf:   documentationURL    = 
08-16 13:41:43.511  4310  4326 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 13:41:43.512  4310  4323 D bt_stack_manager: event_start_up_stack finished
,08-16 13:41:43.514  4310  4322 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 13:41:43.514  4310  4322 D BluetoothAdapterProperties: Setting state to 15
08-16 13:41:43.514  4310  4322 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 13:41:43.514  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:43.515  4310  4322 I BluetoothAdapterState: Entering BleOnState
,08-16 13:41:43.516  4310  4330 I bt_vendor: low_power_mode_cb
,08-16 13:41:43.517  4310  4322 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 13:41:43.517  4310  4322 D BluetoothAdapterProperties: Setting state to 11
,08-16 13:41:43.518  4310  4322 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 13:41:43.522  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:43.523  4310  4310 D HeadsetService: Received start request. Starting profile...
08-16 13:41:43.526  4310  4310 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 13:41:43.527  4310  4310 D HeadsetStateMachine: make
08-16 13:41:43.538  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:41:43.539  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:43.546  4310  4310 D HeadsetStateMachine: max_hf_connections = 1
,08-16 13:41:43.547  4310  4310 I bt_bluedroid: get_profile_interface handsfree
,08-16 13:41:43.548  4310  4326 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 13:41:43.548  4310  4326 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 13:41:43.551  4310  4322 I BluetoothAdapterState: Entering PendingCommandState
08-16 13:41:43.554  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:43.555  4310  4310 D A2dpService: Received start request. Starting profile...
,08-16 13:41:43.555  4310  4310 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 13:41:43.556  4310  4310 I bt_bluedroid: get_profile_interface avrcp
,08-16 13:41:43.563  4310  4310 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 13:41:43.564  4310  4310 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 13:41:43.564  4310  4310 D A2dpStateMachine: make
,08-16 13:41:43.565  4310  4310 I bt_bluedroid: get_profile_interface a2dp
08-16 13:41:43.566  4310  4326 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 13:41:43.568  4310  4340 D A2dpStateMachine: Enter Disconnected: -2
,08-16 13:41:43.570  4310  4310 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 13:41:43.570  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:43.571  4310  4310 D HidService: Received start request. Starting profile...
08-16 13:41:43.571  4310  4310 I bt_bluedroid: get_profile_interface hidhost
,08-16 13:41:43.571  4310  4310 D HidService: setHidService(): set to: null
08-16 13:41:43.571  4310  4326 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399f3e5
08-16 13:41:43.572  4310  4326 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 13:41:43.573  4310  4310 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 13:41:43.574  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:41:43.575  4310  4310 D HealthService: Received start request. Starting profile...
,08-16 13:41:43.576  4310  4310 I bt_bluedroid: get_profile_interface health
,08-16 13:41:43.578  4310  4310 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 13:41:43.579  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:43.580  4310  4310 D PanService: Received start request. Starting profile...
,08-16 13:41:43.581  4310  4310 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 13:41:43.581  4310  4310 I bt_bluedroid: get_profile_interface pan
08-16 13:41:43.582  4310  4326 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 13:41:43.584  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:41:43.585  4310  4310 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
08-16 13:41:43.586  4310  4310 D BluetoothMapService: Received start request. Starting profile...
08-16 13:41:43.586  4310  4310 D BluetoothMapService: start()
,08-16 13:41:43.588  4310  4310 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 13:41:43.589  4310  4310 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER,
08-16 13:41:43.589  4310  4310 D BluetoothMapAppObserver: createReceiver()
,08-16 13:41:43.590  4310  4310 D BluetoothMapAppObserver: initObservers()
,08-16 13:41:43.590  4310  4310 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 13:41:43.596  4310  4310 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:43.596  4310  4310 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:43.596  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:43.596  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isTurningOff()=false,
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:43.599  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:43.600  4310  4310 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:43.600  4310  4310 V BluetoothAdapterState: isTurningOn()=true
,08-16 13:41:43.600  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 13:41:43.602  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:43.600  4310  4338 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 13:41:43.603  4310  4310 V BluetoothAdapterState: isTurningOff()=false
,08-16 13:41:43.603  4310  4310 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:43.603  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:43.603  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
08-16 13:41:43.604  4310  4310 V BluetoothAdapterState: isTurningOff()=false
08-16 13:41:43.604  4310  4310 V BluetoothAdapterState: isTurningOn()=true
08-16 13:41:43.604  4310  4310 V BluetoothAdapterState: isBleTurningOn()=false
08-16 13:41:43.604  4310  4310 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 13:41:43.604  4310  4322 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 13:41:43.605  4310  4322 D BluetoothAdapterProperties: ScanMode =  20
,08-16 13:41:43.605  4310  4322 D BluetoothAdapterProperties: State =  11
08-16 13:41:43.605  4310  4322 D BluetoothAdapterProperties: Setting state to 12
08-16 13:41:43.605  4310  4322 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 13:41:43.605  4310  4322 I BluetoothAdapterState: Entering OnState
08-16 13:41:43.607  1361  2208 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 13:41:43.608  4310  4326 D BluetoothAdapterProperties: Scan Mode:21
,08-16 13:41:43.608  4310  4326 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 13:41:43.612   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:43.612  1361  1375 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:41:43.612  1361  1361 D BluetoothMap: Proxy object connected
,08-16 13:41:43.612  1361  1361 D MapProfile: Bluetooth service connected
08-16 13:41:43.612  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 13:41:43.615  4026  4037 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 13:41:43.616  4310  4310 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:43.616  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:43.617  4310  4310 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 13:41:43.618  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:43.619  4310  4310 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:41:43.619  1361  2208 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:41:43.620  4026  4026 D BluetoothMap: Proxy object connected
,08-16 13:41:43.621  4026  4026 D MapProfile: Bluetooth service connected
,08-16 13:41:43.621  4026  4026 D BluetoothMap: getConnectedDevices()
08-16 13:41:43.622  4026  4036 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 13:41:43.623  4310  4310 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:43.624  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:43.624  4026  4037 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 13:41:43.625  4310  4310 D ObexServerSockets: Succeed to create listening sockets 
08-16 13:41:43.625  4310  4310 D ObexServerSockets0: startAccept()
,08-16 13:41:43.625  4310  4310 D ObexServerSockets0: prepareForNewConnect()
08-16 13:41:43.626   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:41:43.626  1361  2019 D BluetoothPan: onBluetoothStateChange on: true
,08-16 13:41:43.627  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 13:41:43.628  4026  4346 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 13:41:43.628  4310  4310 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 13:41:43.628  4310  4310 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 13:41:43.630   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:43.630  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 13:41:43.630  1361  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 13:41:43.630  1361  1361 D HidProfile: Bluetooth service connected
08-16 13:41:43.630   873   873 D BluetoothA2dp: Proxy object connected
,08-16 13:41:43.632  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 13:41:43.632  1361  1361 D PanProfile: Bluetooth service connected
08-16 13:41:43.633  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 13:41:43.633  1918  1931 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:43.634  4026  4036 D BluetoothPan: onBluetoothStateChange on: true
08-16 13:41:43.634  4310  4348 D ObexServerSockets0: Accepting socket connection...
,08-16 13:41:43.636  4310  4349 D ObexServerSockets0: Accepting socket connection...
,08-16 13:41:43.637   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:41:43.637  4026  4026 D BluetoothInputDevice: Proxy object connected
08-16 13:41:43.637  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 13:41:43.637  4026  4026 D HidProfile: Bluetooth service connected
,08-16 13:41:43.638  4026  4346 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 13:41:43.640   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 13:41:43.641  4026  4026 D BluetoothA2dp: Proxy object connected
,08-16 13:41:43.642  4310  4310 D BluetoothMapService: onReceive,
08-16 13:41:43.642  4310  4310 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 13:41:43.642  4310  4310 D BluetoothMapService: STATE_ON
,08-16 13:41:43.644  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:43.645  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:43.646  4026  4026 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 13:41:43.646  4026  4026 D PanProfile: Bluetooth service connected
,08-16 13:41:43.651  4026  4026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 13:41:43.658  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 13:41:43.659  4026  4026 D DockEventReceiver: finishStartingService: stopping service
,08-16 13:41:43.671  4026  4026 D BluetoothPbap: Proxy object connected
,08-16 13:41:43.671  4026  4026 D PbapServerProfile: Bluetooth service connected
08-16 13:41:43.671  1361  1361 D BluetoothPbap: Proxy object connected
08-16 13:41:43.671  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-16 13:41:43.677  4310  4310 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 13:41:43.677  4310  4310 D ObexServerSockets0: prepareForNewConnect()
,08-16 13:41:43.683  4310  4354 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:43.704  4310  4358 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 13:41:43.707  4310  4358 I BtOppRfcommListener: Accept thread started.
,08-16 13:41:43.713  4026  4036 D BluetoothHeadset: Proxy object connected
08-16 13:41:43.716  4026  4026 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:43.716  1918  2055 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.717  1361  2208 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.718  1361  1361 D HeadsetProfile: Bluetooth service connected
08-16 13:41:43.718   873   873 D BluetoothHeadset: Proxy object connected
08-16 13:41:43.718   873   873 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.718   873   873 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.731   873   890 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.734  1918  1930 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.737   873   890 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.738  1361  1375 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.738  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:43.739  4026  4346 D BluetoothHeadset: Proxy object connected
,08-16 13:41:43.740  4026  4026 D HeadsetProfile: Bluetooth service connected
,08-16 13:41:44.570  1851  1949 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 13:41:44.570  1851  1949 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 13:41:44.621  1522  1522 I ConfigService: onCreate
,08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:47.048  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:47.055  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:47.056  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:47.056  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c567061 removed from the list
,08-16 13:41:47.056  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:41:47.057  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:47.057  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:41:47.060  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:41:47.060  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3119786 added. We now have 4 listener(s)
08-16 13:41:47.060  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:41:47.064   873  1916 D WifiService: setWifiEnabled: false pid=3926, uid=10000
08-16 13:41:47.065   873  1916 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:49.698  1522  1522 I ConfigService: onDestroy
,08-16 13:41:52.078  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:41:52.079   873  1938 D WifiService: setWifiEnabled: true pid=3926, uid=10000
08-16 13:41:52.079   873  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 13:41:52.098   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:52.110  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 13:41:52.115  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 13:41:52.119  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 13:41:52.121  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 13:41:52.128   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-16 13:41:52.129   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 13:41:52.130   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 13:41:52.131   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 13:41:52.131   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 13:41:52.131   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 13:41:52.131   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 13:41:52.142   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 13:41:52.143   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:41:52.143   372   871 D CommandListener: Setting iface cfg
08-16 13:41:52.144   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 13:41:52.144   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 13:41:52.195   873  1307 E native  : do suspend true
,08-16 13:41:52.202   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 13:41:52.203   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 13:41:52.210   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 13:41:53.581   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 13:41:53.725   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.56 rxSuccessRate=10.31 delta 1000 -> 994
,08-16 13:41:53.726   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 13:41:53.727   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:53.744   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 13:41:53.811   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 13:41:53.816  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 13:41:54.252  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 13:41:54.300  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 13:41:54.302  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 13:41:54.310   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.,
,08-16 13:41:54.327   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:41:54.328   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 13:41:54.329   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 13:41:54.356   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 13:41:54.370   372   871 D CommandListener: Setting iface cfg
,08-16 13:41:54.371   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 13:41:54.397   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 13:41:54.418   873  4370 D DhcpClient: Receive thread started
,08-16 13:41:54.510   873  1307 E native  : do suspend false
,08-16 13:41:54.536   873  1866 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 13:41:54.550   873  4370 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172770, domain null
,08-16 13:41:54.551   873  1866 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172770 seconds
,08-16 13:41:54.555   873  1866 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 13:41:54.567   873  4370 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 13:41:54.569   873  1866 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 13:41:54.574   372   871 D CommandListener: Setting iface cfg
,08-16 13:41:54.587   873  1866 D DhcpClient: Scheduling renewal in 86399s
,08-16 13:41:54.588   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-16 13:41:54.589   873  1307 E native  : do suspend true
,08-16 13:41:54.603   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 13:41:54.604   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-16 13:41:54.605   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 13:41:54.608   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 13:41:54.611   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 13:41:54.663   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 13:41:54.664   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 13:41:54.667   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 13:41:54.668   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 13:41:54.671   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 13:41:54.685   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 13:41:54.693   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 13:41:54.693   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 13:41:54.693   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 13:41:54.694   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 13:41:54.694   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-16 13:41:54.694   873  1309 D ConnectivityService:    accepting network in place of null
08-16 13:41:54.696   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 13:41:54.719   873  4369 D NetlinkSocketObserver: NeighborEvent{elapsedMs=220342, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 13:41:54.732   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:54.766   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 13:41:54.774   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 13:41:54.775   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:54.783   873  4368 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.238,2a00:1450:4001:801::200e
,08-16 13:41:54.785   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 13:41:54.788   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:54.805  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:54.808  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:54.814  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:54.815  3926  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:54.818  3926  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:54.821  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 13:41:54.828  1739  1739 D SystemUpdateService: onCreate
,08-16 13:41:54.833  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 13:41:54.849  1739  4379 I SystemUpdateService: active receiver: enabled
,08-16 13:41:54.855  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 13:41:54.856  1739  2415 I iu.UploadsManager: num queued entries: 0
,08-16 13:41:54.864   873  4368 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 11:41:54 GMT], X-Android-Received-Millis=[1471347714863], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471347714830]}
,08-16 13:41:54.864   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 13:41:54.865   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-16 13:41:54.865   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 13:41:54.865  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 13:41:54.866   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 13:41:54.867  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 13:41:54.869  1739  4379 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-16 13:41:54.869  1739  2415 I iu.UploadsManager: num updated entries: 0
,08-16 13:41:54.875  4108  4108 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 13:41:54.879  1739  4381 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 13:41:54.879  1739  4381 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 13:41:54.881  4108  4108 D SprintDMHelper: simOperator: 
08-16 13:41:54.881  4108  4108 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 13:41:54.890  1739  4381 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:41:54.900  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 13:41:54.902  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:41:54.896  1739  4379 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 13:41:54.911  1739  4379 I SystemUpdateService: now status is 0 (complete)
,08-16 13:41:54.912  1739  4379 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 13:41:54.912  1739  4379 I SystemUpdateService: file has been verified
08-16 13:41:54.912  1739  4379 I SystemUpdateService: OTA package size = 12249756
,08-16 13:41:54.916  1739  2415 I iu.SyncManager: NEXT; no task
,08-16 13:41:54.930  1739  4379 I SystemUpdateService: showing system update notification
,08-16 13:41:54.948  1739  1739 D SystemUpdateService: onDestroy
,08-16 13:41:54.965  1522  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 13:41:54.965  1522  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 13:41:54.965  1522  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:41:54.965  1522  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:41:54.979  1739  4381 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-16 13:41:55.008  4078  4385 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 13:41:55.773   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:41:57.106  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:41:57.113  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:41:57.115  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:41:57.116  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3119786 removed from the list
,08-16 13:41:57.116  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:41:57.117  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:41:57.117  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:02.130  3926  4391 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 13:42:02.130  3926  4391 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 13:42:02.701   873  1309 D ConnectivityService: handlePromptUnvalidated 102
,08-16 13:42:05.138  3926  4392 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 13:42:05.139  3926  4391 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 13:42:05.139  3926  4392 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:42:05.140  3926  4391 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:42:05.141  3926  4392 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 13:42:05.141  3926  4391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:42:05.143  3926  4391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:42:05.143  3926  4392 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 13:42:05.147  3926  4395 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Sender)
08-16 13:42:05.150  3926  4391 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 13:42:05.153  3926  4392 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 13:42:05.159  3926  4394 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: OutgoingSocketThread/Sender)
,08-16 13:42:05.161  3926  4396 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: OutgoingSocketThread/Receiver)
,08-16 13:42:05.166  3926  4397 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: IncomingSocketThread/Receiver)
,08-16 13:42:05.167  3926  4397 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: IncomingSocketThread/Receiver)
,08-16 13:42:05.168  3926  4397 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 13:42:05.168  3926  4396 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: OutgoingSocketThread/Receiver)
,08-16 13:42:05.168  3926  4396 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 13:42:05.169  3926  4396 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 13:42:05.171  3926  4397 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 13:42:13.139  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 13:42:13.141  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 13:42:13.148  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78118e8 Bundle[{}]
,08-16 13:42:13.150  3926  3976 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 13:42:13.151  3926  3976 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 13:42:13.153  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 13:42:13.155  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 13:42:13.156  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 13:42:13.156  3926  3976 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 13:42:21.910  1522  2201 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 13:42:23.174  3926  3976 I System.out: Running OutgoingSocketThread
,08-16 13:42:23.179  3926  4400 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-16 13:42:23.179  3926  4400 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 13:42:24.925  3677  4401 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 13:42:24.963  3677  4402 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 13:42:24.996  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:25.002  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:25.053  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:42:25.054  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 13:42:25.054  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:25.054  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-16 13:42:25.102  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:25.107  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:25.144  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:42:25.144  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 13:42:25.144  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:25.144  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:25.174  3677  4402 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 13:42:25.176  3677  4401 E BooksSync: Soft error
08-16 13:42:25.176  3677  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:42:25.176  3677  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:42:25.178  3677  4401 E BooksSync: Sync error
08-16 13:42:25.178  3677  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:42:25.178  3677  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 13:42:25.179  3677  4401 I BooksSync: Finished books sync
,08-16 13:42:25.191   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 249595, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:42:26.188  3926  4403 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 13:42:26.188  3926  4403 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 13:42:26.188  3926  4403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 13:42:26.188  3926  4400 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-16 13:42:26.189  3926  4400 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 13:42:26.189  3926  4400 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:42:26.190  3926  4403 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:42:26.191  3926  4400 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 13:42:26.194  3926  4405 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: IncomingSocketThread/Sender)
08-16 13:42:26.196  3926  4403 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 13:42:26.196  3926  4400 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 13:42:26.204  3926  4406 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: OutgoingSocketThread/Sender)
,08-16 13:42:26.205  3926  4407 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: IncomingSocketThread/Receiver)
,08-16 13:42:26.207  3926  4407 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: IncomingSocketThread/Receiver)
,08-16 13:42:26.208  3926  4407 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 13:42:26.208  3926  4407 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 13:42:26.210  3926  4408 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: OutgoingSocketThread/Receiver)
,08-16 13:42:26.213  3926  4408 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: OutgoingSocketThread/Receiver)
08-16 13:42:26.213  3926  4408 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-16 13:42:26.214  3926  4408 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 13:42:34.192  3926  3976 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 468)
,08-16 13:42:34.194  3926  3976 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 13:42:34.194  3926  3976 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 469)
,08-16 13:42:35.621   873  4369 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261244, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 13:42:37.503  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:37.507  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:37.521  3868  4409 V GoogleAuthProtoRequest: [337] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 13:42:37.560  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-16 13:42:37.560  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-16 13:42:37.561  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:37.561  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:37.590  3868  4409 W ExperimentUpdateService: [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 13:42:37.591  3868  4409 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 13:42:39.204  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 13:42:39.204  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c8847 added. We now have 3 listener(s)
,08-16 13:42:39.211  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:42:39.212  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:42:39.212  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:42:39.213  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:42:39.213  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05d874 added. We now have 4 listener(s)
08-16 13:42:39.214  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 13:42:39.215  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:42:39.226  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:42:39.238  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:42:39.242  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:42:39.242  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:42:39.243  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:42:39.243  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:42:39.243  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:42:39.243  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:42:39.243  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:39.243  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:42:39.243  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:42:39.244  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c8847 removed from the list
08-16 13:42:39.244  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:42:39.244  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05d874 removed from the list
08-16 13:42:39.251  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:39.259  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:39.261  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 13:42:39.261  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:39.263  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:39.264  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:39.268  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:42:39.268  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:39.269  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:39.269  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05d874 not in the list
08-16 13:42:39.269  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:39.270  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:39.273  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:39.274  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 13:42:39.274  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:39.274  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a05d874 not in the list
08-16 13:42:39.275  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:39.275  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:39.275  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:39.276  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c8847 not in the list
08-16 13:42:39.278  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:42:39.278  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dfa612 added. We now have 3 listener(s)
,08-16 13:42:39.285  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:42:39.285  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:42:39.286  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:42:39.286  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:42:39.287  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bf61e3 added. We now have 4 listener(s)
,08-16 13:42:39.287  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:42:39.289  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:42:39.298  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:42:39.312  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:42:39.320  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:42:39.321  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:42:39.322  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:42:39.323  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:42:39.323  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:42:39.323  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:39.324  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 13:42:39.328  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:39.334  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 13:42:39.335  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-16 13:42:39.336  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:39.349  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:42:39.351  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:42:39.351  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:42:39.361  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 13:42:39.361  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 13:42:39.361  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:42:39.361  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:42:39.366  4310  4321 D BtGatt.GattService: registerClient() - UUID=1a970bc8-5abf-4cc8-9b78-9eaa06d36e1d
,08-16 13:42:39.368  4310  4326 D BtGatt.GattService: onClientRegistered() - UUID=1a970bc8-5abf-4cc8-9b78-9eaa06d36e1d, clientIf=5
08-16 13:42:39.369  3926  3938 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 13:42:39.372  4310  4320 D BtGatt.GattService: start scan with filters
,08-16 13:42:39.382  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:42:39.382  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:42:39.382  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:42:39.382  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:42:39.383  4310  4329 D BtGatt.ScanManager: handling starting scan
,08-16 13:42:39.386  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:42:39.386  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 13:42:39.386  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:42:39.387  4310  4329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d9868fc
,08-16 13:42:39.389  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:42:39.393  3926  3976 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 13:42:39.393  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:42:39.393  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:42:39.393  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:39.393  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:42:39.393  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:42:39.393  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:42:39.393  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:42:39.393  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:42:39.393  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:42:39.394  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:42:39.396  3926  3976 D BluetoothAdapter: STATE_ON
08-16 13:42:39.397  4310  4321 D BtGatt.GattService: stopScan() - queue size =1
,08-16 13:42:39.398  4310  4320 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:42:39.400  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:42:39.400  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:42:39.400  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 13:42:39.401  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:42:39.401  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 13:42:39.402  4310  4326 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:42:39.403  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:39.404  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:42:39.405  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:42:39.405  4310  4329 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 13:42:39.405  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:42:39.405  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:42:39.406  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:42:39.410  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:42:39.410  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:42:39.410  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:42:39.423  4310  4326 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 13:42:39.423  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:39.424  4310  4329 D BtGatt.ScanManager: Starting BLE batch scan
08-16 13:42:39.425  4310  4329 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 13:42:39.464  4310  4326 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:42:39.465  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:39.487  4310  4326 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:42:39.488  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:39.517  4310  4326 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 13:42:39.517  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:39.518  4310  4329 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:42:39.540  4310  4326 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 13:42:39.540  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:39.541  4310  4329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:42:39.551  4310  4326 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 13:42:39.552  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:39.911  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:42:39.912  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:42:39.912  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:42:41.787   873  4369 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 13:42:42.410  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:42:42.411  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 13:42:42.411  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 13:42:42.412  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:42.413  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:42.413  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:42:42.414  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 13:42:42.414  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dfa612 removed from the list
08-16 13:42:42.415  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:42:42.415  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bf61e3 removed from the list,
08-16 13:42:42.415  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:42:42.416  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:42.418  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:42.418  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:42.421  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:42.422  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:42.422  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:42.422  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bf61e3 not in the list
08-16 13:42:42.423  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:42.423  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:42.426  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:42.427  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:42.427  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:42.427  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bf61e3 not in the list
,08-16 13:42:42.427  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:42:42.428  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:42.428  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:42.428  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dfa612 not in the list
08-16 13:42:42.431  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:42:42.431  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78fc20c added. We now have 3 listener(s)
,08-16 13:42:42.437  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:42:42.437  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:42:42.437  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:42:42.437  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:42:42.437  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69d7755 added. We now have 4 listener(s)
08-16 13:42:42.437  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:42:42.438  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:42:42.441  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:42:42.446  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:42:42.448  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:42:42.449  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:42:42.449  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 13:42:42.450  3926  3976 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 13:42:42.450  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 13:42:42.450  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 13:42:42.450  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 13:42:42.450  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 13:42:42.451  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:42.451  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 13:42:42.452  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 13:42:42.452  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 13:42:42.452  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 13:42:42.452  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 13:42:42.452  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:42:42.452  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:42:42.453  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:42.458  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:42.458  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:42:42.458  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 13:42:42.458  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 13:42:42.461  3926  4410 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 13:42:42.463  3926  4410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-16 13:42:42.465  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:42:42.467  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 13:42:42.467  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:42:42.470  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 13:42:42.470  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 13:42:42.471  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-16 13:42:42.472  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 13:42:42.472  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 13:42:42.472  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-16 13:42:42.473  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:42:42.477  4310  4350 D BtGatt.GattService: registerClient() - UUID=bdd2e106-63a5-4449-b0fd-fa9a656fb8a2
,08-16 13:42:42.477  4310  4326 D BtGatt.GattService: onClientRegistered() - UUID=bdd2e106-63a5-4449-b0fd-fa9a656fb8a2, clientIf=5
08-16 13:42:42.478  3926  3938 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 13:42:42.480  4310  4328 D BtGatt.AdvertiseManager: message : 0
,08-16 13:42:42.483  4310  4328 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 13:42:42.493  4310  4326 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 13:42:42.502  4310  4326 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 13:42:42.503  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 13:42:42.504  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:42:42.506  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:42:42.507  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 13:42:42.508  3926  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 13:42:42.508  3926  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-16 13:42:42.508  3926  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 13:42:42.508  3926  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 13:42:42.508  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 13:42:42.510  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 13:42:42.515  3926  3926 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 13:42:42.516  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 13:42:43.017  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 13:42:43.018  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 13:42:43.018  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:42:45.511  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:42:45.512  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-16 13:42:45.512  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 13:42:45.512  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 13:42:45.513  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-16 13:42:45.513  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 13:42:45.516  3926  4410 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 13:42:45.516  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:42:45.517  3926  4410 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-16 13:42:45.517  3926  3976 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-16 13:42:45.517  3926  4410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 13:42:45.517  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:42:45.517  3926  3926 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 13:42:45.517  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 13:42:45.518  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 13:42:45.518  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 13:42:45.518  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:42:45.521  3926  3976 D BluetoothAdapter: STATE_ON
08-16 13:42:45.521  3926  3976 D BluetoothLeScanner: could not find callback wrapper
08-16 13:42:45.522  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:42:45.522  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 13:42:45.524  4310  4328 D BtGatt.AdvertiseManager: message : 1
08-16 13:42:45.526  4310  4328 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 13:42:45.535  4310  4326 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-16 13:42:45.535  4310  4326 D BtGatt.GattService: Client app is not null!
,08-16 13:42:45.536  4310  4320 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:42:45.537  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:42:45.538  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-16 13:42:45.538  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 13:42:45.538  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-16 13:42:45.538  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-16 13:42:45.540  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:42:45.540  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:42:45.540  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 13:42:45.541  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:42:45.542  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:42:45.542  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:45.543  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:42:45.543  3926  3926 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 13:42:45.546  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:42:45.546  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78fc20c removed from the list
,08-16 13:42:45.546  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:42:45.546  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:42:45.550  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 13:42:45.550  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:42:45.549  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69d7755 removed from the list
08-16 13:42:45.551  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:42:45.551  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:45.552  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:45.552  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:45.554  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 13:42:45.554  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:45.554  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:45.555  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69d7755 not in the list
08-16 13:42:45.555  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:45.555  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:45.557  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 13:42:45.558  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:45.558  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:45.558  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69d7755 not in the list
08-16 13:42:45.558  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:45.558  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:45.558  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:45.559  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78fc20c not in the list
,08-16 13:42:45.560  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:42:45.560  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e34ee36 added. We now have 3 listener(s)
,08-16 13:42:45.565  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:42:45.565  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 13:42:45.565  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:42:45.565  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:42:45.566  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21137 added. We now have 4 listener(s)
,08-16 13:42:45.566  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 13:42:45.567  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:42:45.572  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:42:45.579  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:42:45.581  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:42:45.582  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 13:42:45.584  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 13:42:45.584  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 13:42:45.584  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 13:42:45.584  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 13:42:45.584  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 13:42:45.584  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 13:42:45.587  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:42:45.588  3926  3976 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 13:42:45.589  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 13:42:45.594  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 13:42:45.596  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 13:42:45.596  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 13:42:45.602  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 13:42:45.602  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 13:42:45.602  3926  3976 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 13:42:45.603  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:42:45.607  4310  4320 D BtGatt.GattService: registerClient() - UUID=a595e3b3-a2d7-4074-8e77-58bda61d7334
,08-16 13:42:45.608  4310  4326 D BtGatt.GattService: onClientRegistered() - UUID=a595e3b3-a2d7-4074-8e77-58bda61d7334, clientIf=5
08-16 13:42:45.609  3926  3937 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 13:42:45.609  4310  4350 D BtGatt.GattService: start scan with filters
,08-16 13:42:45.614  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 13:42:45.614  4310  4329 D BtGatt.ScanManager: handling starting scan
08-16 13:42:45.614  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 13:42:45.615  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 13:42:45.615  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 13:42:45.623  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 13:42:45.624  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 13:42:45.625  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 13:42:45.630  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 13:42:45.630  4310  4326 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 13:42:45.630  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:45.631  4310  4329 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 13:42:45.640  4310  4326 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 13:42:45.640  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:45.640  4310  4329 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 13:42:45.640  4310  4329 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 13:42:45.654  4310  4326 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 13:42:45.655  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:45.662  4310  4326 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 13:42:45.662  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:46.051  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:42:46.125  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 13:42:46.125  3926  3926 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 13:42:46.125  3926  3926 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 13:42:47.169  4310  4310 D BtGatt.ScanManager: awakened up at time 272792
,08-16 13:42:47.171  4310  4329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 13:42:47.220  4310  4326 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 13:42:47.220  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 13:42:47.221  4310  4326 D BtGatt.GattService: current time is 272845079150
,08-16 13:42:47.224  4310  4326 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -91, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 13:42:47.228  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 13:42:47.231  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 13:42:47.232  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 13:42:47.233  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 13:42:47.234  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 13:42:47.235  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 13:42:48.643  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 13:42:48.643  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 13:42:48.644  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 13:42:48.644  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 13:42:48.644  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 13:42:48.645  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 13:42:48.645  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 13:42:48.645  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 13:42:48.646  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 13:42:48.646  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 13:42:48.646  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 13:42:48.649  3926  3976 D BluetoothAdapter: STATE_ON
,08-16 13:42:48.651  4310  4320 D BtGatt.GattService: stopScan() - queue size =1
08-16 13:42:48.653  4310  4350 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 13:42:48.655  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 13:42:48.657  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 13:42:48.657  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 13:42:48.657  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 13:42:48.658  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 13:42:48.663  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 13:42:48.663  4310  4310 D BtGatt.ScanManager: awakened up at time 274287
08-16 13:42:48.664  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 13:42:48.664  3926  3976 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 13:42:48.664  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 13:42:48.671  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 13:42:48.676  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:42:48.677  3926  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 13:42:48.677  4310  4326 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 13:42:48.677  3926  3926 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 13:42:48.677  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:48.678  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:48.679  4310  4329 D BtGatt.ScanManager: stopping BLe Batch
,08-16 13:42:48.679  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.679  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:42:48.679  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:42:48.680  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e34ee36 removed from the list
08-16 13:42:48.680  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:48.680  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21137 removed from the list
08-16 13:42:48.680  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:42:48.681  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:48.682  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.682  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:48.686  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:48.686  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:48.687  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:42:48.687  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21137 not in the list
08-16 13:42:48.687  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.687  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:48.690  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:48.690  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:48.690  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 13:42:48.691  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21137 not in the list
08-16 13:42:48.691  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 13:42:48.691  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.691  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:48.691  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e34ee36 not in the list
,08-16 13:42:48.694  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 13:42:48.694  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f72910 added. We now have 3 listener(s)
,08-16 13:42:48.698  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 13:42:48.698  4310  4326 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 13:42:48.699  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:48.699  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 13:42:48.699  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 13:42:48.699  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 13:42:48.700  4310  4329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 13:42:48.700  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f8c09 added. We now have 4 listener(s)
08-16 13:42:48.700  3926  3976 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 13:42:48.701  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 13:42:48.705  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 13:42:48.713  3926  3976 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 13:42:48.715  3926  3976 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 13:42:48.716  3926  3976 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 13:42:48.716  3926  3976 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 13:42:48.716  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 13:42:48.716  3926  3976 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 13:42:48.716  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:48.716  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.716  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 13:42:48.716  3926  3976 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 13:42:48.717  3926  3976 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f72910 removed from the list
08-16 13:42:48.717  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:48.717  3926  3976 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f8c09 removed from the list
08-16 13:42:48.718  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:42:48.718  3926  3976 D io.jxcore.node.ConnectivityMonitor: stop
08-16 13:42:48.719  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:48.719  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.720  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:48.720  4310  4326 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-16 13:42:48.720  4310  4326 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 13:42:48.721  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:48.721  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:48.721  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:48.721  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f8c09 not in the list
08-16 13:42:48.721  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.722  3926  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 13:42:48.722  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 13:42:48.722  4310  4326 D BtGatt.GattService: current time is 274346260946
08-16 13:42:48.722  4310  4326 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -99, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 13:42:48.723  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 13:42:48.723  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 13:42:48.723  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 13:42:48.723  3926  3976 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 13:42:48.723  4310  4326 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 13:42:48.723  3926  3976 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f8c09 not in the list
08-16 13:42:48.723  3926  3976 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 13:42:48.723  3926  3976 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 13:42:48.723  3926  3976 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 13:42:48.723  3926  3976 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f72910 not in the list
,08-16 13:42:49.178  3926  3926 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 13:42:53.727  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 13:42:53.727  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 13:42:53.728  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 13:42:53.728  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 13:42:53.729  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 13:42:53.729  3926  3976 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-16 13:42:57.161  3677  4412 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 13:42:57.223  3677  4413 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 13:42:57.274  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:57.283  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:57.370  1522  2390 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:42:57.370  1522  2390 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 13:42:57.371  1522  2390 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:57.371  1522  2390 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:57.457  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:57.461  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:57.516  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 13:42:57.516  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 13:42:57.517  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:57.517  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:57.556  3677  4413 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 13:42:57.558  3677  4412 E BooksSync: Soft error
08-16 13:42:57.558  3677  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:42:57.558  3677  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 13:42:57.559  3677  4412 E BooksSync: Sync error
08-16 13:42:57.559  3677  4412 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 13:42:57.559  3677  4412 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 13:42:57.560  3677  4412 I BooksSync: Finished books sync
,08-16 13:42:57.574   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282717, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:42:57.782  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-16 13:42:57.787  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 13:42:57.850  1522  2304 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 13:42:57.850  1522  2304 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 13:42:57.850  1522  2304 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 13:42:57.851  1522  2304 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:57.891  3621  4415 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 13:42:57.891  3621  4415 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at blb.a(PG:3937)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at czp.a(PG:18188)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:42:57.891  3621  4415 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	... 12 more
08-16 13:42:57.891  3621  4415 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at fal.a(PG:38)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:42:57.891  3621  4415 E HttpOperation: 	... 14 more
,08-16 13:42:57.964  1522  2075 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 13:42:57.964  1522  2075 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 13:42:57.964  1522  2075 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 13:42:57.964  1522  2075 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 13:42:57.994  3621  4415 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 13:42:57.994  3621  4415 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jdm.a(PG:82)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jcs.o(PG:406)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jcn.a(PG:1379)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jcs.i(PG:143)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at hec.a(PG:42)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at hee.a(PG:102)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at czr.a(PG:65)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at kka.a(PG:108)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at czp.a(PG:19176)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at czp.a(PG:9081)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at czq.run(PG:1686)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:42:57.994  3621  4415 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jdj.a(PG:4091)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jdj.a(PG:1125)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jdm.a(PG:77)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	... 15 more
08-16 13:42:57.994  3621  4415 E HttpOperation: Caused by: faj: BadAuthentication
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at fal.a(PG:38)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	at jdj.a(PG:4089)
08-16 13:42:57.994  3621  4415 E HttpOperation: 	... 17 more
,08-16 13:42:57.994  3621  4415 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 13:42:57.994  3621  4415 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at hec.a(PG:42)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at hee.a(PG:102)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at czr.a(PG:65)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at kka.a(PG:108)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	... 15 more
08-16 13:42:57.994  3621  4415 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at fal.a(PG:38)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 13:42:57.994  3621  4415 E ExperimentLoader: 	... 17 more
,08-16 13:42:58.160   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 282849, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 13:43:00.754  3926  4424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: My test thread name)
,08-16 13:43:02.752  3926  3976 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 480
,08-16 13:43:02.753  3926  3976 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 480, name: My test thread name)
,08-16 13:43:02.759  3926  4425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 481, name: My test thread name)
,08-16 13:43:02.760  3926  4425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 481, thread name: My test thread name)
08-16 13:43:02.760  3926  4425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 481, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 13:43:02.764  3926  3976 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 13:43:02.773  3926  4426 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: My test thread name)
,08-16 13:43:02.774  3926  4426 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 485, thread name: My test thread name): Test exception.
08-16 13:43:02.774  3926  4426 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 485, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 13:43:02.782  3926  3976 I jxcore-log: Total number of executed tests:  82
08-16 13:43:02.782  3926  3976 I jxcore-log: 
,08-16 13:43:02.783  3926  3976 I jxcore-log: Number of passed tests:  82
08-16 13:43:02.783  3926  3976 I jxcore-log: 
08-16 13:43:02.783  3926  3976 I jxcore-log: Number of failed tests:  0
08-16 13:43:02.783  3926  3976 I jxcore-log: 
,08-16 13:43:02.784  3926  3976 I jxcore-log: Number of ignored tests:  0
08-16 13:43:02.784  3926  3976 I jxcore-log: 
08-16 13:43:02.786  3926  3976 I jxcore-log: Total duration:  146600
08-16 13:43:02.786  3926  3976 I jxcore-log: 
,08-16 13:43:02.787  3926  3976 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 13:43:02.787  3926  3976 I jxcore-log: 
,08-16 13:43:02.788  3926  4424 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
08-16 13:43:02.800  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.800  3926  3976 I jxcore-log: 
,08-16 13:43:02.814  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.814  3926  3976 I jxcore-log: 
,08-16 13:43:02.817  3926  3926 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 13:43:02.818  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.818  3926  3976 I jxcore-log: 
08-16 13:43:02.821  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.821  3926  3976 I jxcore-log: 
08-16 13:43:02.824  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 13:43:02.824  3926  3976 I jxcore-log: 
,08-16 13:43:02.828  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.828  3926  3976 I jxcore-log: 
,08-16 13:43:02.834  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.834  3926  3976 I jxcore-log: 
,08-16 13:43:02.838  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.838  3926  3976 I jxcore-log: 
,08-16 13:43:02.840  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 13:43:02.840  3926  3976 I jxcore-log: 
,08-16 13:43:02.842  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.842  3926  3976 I jxcore-log: 
,08-16 13:43:02.843  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.843  3926  3976 I jxcore-log: 
,08-16 13:43:02.844  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.844  3926  3976 I jxcore-log: 
,08-16 13:43:02.845  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.845  3926  3976 I jxcore-log: 
08-16 13:43:02.846  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.846  3926  3976 I jxcore-log: 
,08-16 13:43:02.847  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.847  3926  3976 I jxcore-log: 
,08-16 13:43:02.848  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.848  3926  3976 I jxcore-log: 
08-16 13:43:02.849  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.849  3926  3976 I jxcore-log: 
,08-16 13:43:02.849  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.849  3926  3976 I jxcore-log: 
08-16 13:43:02.850  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.850  3926  3976 I jxcore-log: 
,08-16 13:43:02.851  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.851  3926  3976 I jxcore-log: 
,08-16 13:43:02.852  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.852  3926  3976 I jxcore-log: 
08-16 13:43:02.853  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.853  3926  3976 I jxcore-log: 
,08-16 13:43:02.853  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.853  3926  3976 I jxcore-log: 
08-16 13:43:02.854  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.854  3926  3976 I jxcore-log: 
,08-16 13:43:02.855  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.855  3926  3976 I jxcore-log: 
08-16 13:43:02.856  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.856  3926  3976 I jxcore-log: 
,08-16 13:43:02.857  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.857  3926  3976 I jxcore-log: 
,08-16 13:43:02.857  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.857  3926  3976 I jxcore-log: 
08-16 13:43:02.858  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.858  3926  3976 I jxcore-log: 
,08-16 13:43:02.859  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.859  3926  3976 I jxcore-log: 
08-16 13:43:02.860  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.860  3926  3976 I jxcore-log: 
,08-16 13:43:02.861  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.861  3926  3976 I jxcore-log: 
,08-16 13:43:02.861  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.861  3926  3976 I jxcore-log: 
08-16 13:43:02.862  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.862  3926  3976 I jxcore-log: 
,08-16 13:43:02.863  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.863  3926  3976 I jxcore-log: 
,08-16 13:43:02.864  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.864  3926  3976 I jxcore-log: 
08-16 13:43:02.864  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 13:43:02.864  3926  3976 I jxcore-log: 
,08-16 13:43:02.865  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.865  3926  3976 I jxcore-log: 
,08-16 13:43:02.866  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 13:43:02.866  3926  3976 I jxcore-log: 
08-16 13:43:02.867  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.867  3926  3976 I jxcore-log: 
,08-16 13:43:02.868  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.868  3926  3976 I jxcore-log: 
08-16 13:43:02.868  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.868  3926  3976 I jxcore-log: 
08-16 13:43:02.869  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.869  3926  3976 I jxcore-log: 
08-16 13:43:02.870  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.870  3926  3976 I jxcore-log: 
08-16 13:43:02.871  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.871  3926  3976 I jxcore-log: 
,08-16 13:43:02.872  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.872  3926  3976 I jxcore-log: 
,08-16 13:43:02.873  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 13:43:02.873  3926  3976 I jxcore-log: 
,08-16 13:43:02.874  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.874  3926  3976 I jxcore-log: 
,08-16 13:43:02.875  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.875  3926  3976 I jxcore-log: 
,08-16 13:43:02.876  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 13:43:02.876  3926  3976 I jxcore-log: 
,08-16 13:43:02.876  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 13:43:02.876  3926  3976 I jxcore-log: 
,08-16 13:43:02.877  3926  3976 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 13:43:02.877  3926  3976 I jxcore-log: 
,08-16 13:43:03.428  4427  4427 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 13:43:03.434  4427  4427 D AndroidRuntime: CheckJNI is OFF
,08-16 13:43:03.477  4427  4427 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 13:43:03.525  4427  4427 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 13:43:03.549  4427  4427 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 13:43:03.560   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 13:43:03.561   873   886 I ActivityManager: Killing 3926:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 13:43:03.657   873  1913 D GraphicsStats: Buffer count: 2
,08-16 13:43:03.658   873  1916 I WindowState: WIN DEATH: Window{9f9f68e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 13:43:03.659   873  1308 D WifiService: Client connection lost with reason: 4
,08-16 13:43:03.682   873   896 W PackageSettings: Skipping PackageSetting{f8d0d9 com.example.hello/10273} due to missing metadata
,08-16 13:43:03.724   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 13:43:03.724   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-16 13:43:03.725   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 13:43:03.725   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231),
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 13:43:03.725   873   886 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 13:43:03.725   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:03.725   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:03.725   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:43:03.725   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 13:43:03.726   873   886 I ActivityManager:   Force finishing activity ActivityRecord{2a909d7 u0 com.test.thalitest/.MainActivity t2},
,08-16 13:43:03.735   873  1913 W ActivityManager: Spurious death for ProcessRecord{d8d99f3 0:com.test.thalitest/u0a0}, curProc for 3926: null
,08-16 13:43:03.741   873   896 I art     : Starting a blocking GC Explicit
,08-16 13:43:03.783   873   896 I art     : Explicit concurrent mark sweep GC freed 15092(1005KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 707us total 40.121ms
,08-16 13:43:03.815   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 13:43:03.820  4427  4427 I art     : System.exit called, status: 0
,08-16 13:43:03.820  4427  4427 I AndroidRuntime: VM exiting with result code 0.
,08-16 13:43:03.830   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 13:43:03.852   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 13:43:03.855  4310  4310 D BluetoothMapAppObserver: onReceive
08-16 13:43:03.856  4310  4310 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 13:43:03.862  1851  1851 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 13:43:03.867   873  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 13:43:03.867  2151  2289 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 13:43:03.868  3764  3764 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 13:43:03.876  1851  4438 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 13:43:03.887  1851  4438 I Decoder : createOrResetDecoder
,08-16 13:43:03.894  1918  1918 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 13:43:03.927   873  1702 I ActivityManager: Start proc 4441:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 13:43:03.935  1522  1522 I ConfigService: onCreate
,08-16 13:43:03.941  1522  4452 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 13:43:03.941  1522  4452 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 13:43:03.941  1522  4452 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-16 13:43:03.945  1522  4452 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 13:43:03.954   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 13:43:03.964  1851  4438 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 13:43:03.977  4441  4441 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 13:43:03.980  1933  2015 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 13:43:03.983   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 13:43:03.984   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 13:43:03.984   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 13:43:03.984   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 13:43:03.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 13:43:03.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 13:43:03.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 13:43:03.984   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:03.984   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:03.984   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:43:03.989   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 13:43:03.989   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 13:43:03.989   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:03.989   873   886 E DropBoxManagerService: 	... 13 more
,08-16 13:43:03.993   873  1913 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3926 uid 10000
,08-16 13:43:03.994   873  2705 I ActivityManager: Start proc 4455:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-16 13:43:03.994  1851  1851 I Keyboard.Facilitator: onFinishInput()
--------- beginning of crash
08-16 13:43:03.994  1933  2015 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 13:43:03.994  1933  2015 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1933
08-16 13:43:03.994  1933  2015 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:03.994  1933  2015 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:43:03.996   873  1916 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 13:43:03.996   873  4460 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:43:03.996   873  4460 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:03.996   873  4460 E DropBoxManagerService: 	... 5 more
,08-16 13:43:03.999  1851  4438 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 13:43:04.000  1933  2015 I Process : Sending signal. PID: 1933 SIG: 9
08-16 13:43:04.004  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 13:43:04.004  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 13:43:04.011  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 13:43:04.011  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 13:43:04.012  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 13:43:04.012  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 13:43:04.012  1851  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 13:43:04.012  1851  4438 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 13:43:04.013  1851  4438 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-16 13:43:04.013  1851  4438 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 13:43:04.013  1851  4438 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 13:43:04.013  1851  4438 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 13:43:04.044  4441  4441 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 13:43:04.051   873   883 I WindowState: WIN DEATH: Window{434a283 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 13:43:04.051   873  1913 D GraphicsStats: Buffer count: 1
,08-16 13:43:04.066   873  1953 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1933) has died
,08-16 13:43:04.066  4441  4469 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	,at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.066  4441  4469 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: ,	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.068  4441  4469 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 13:43:04.068   873  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 13:43:04.077   873  1953 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 13:43:04.094  4441  4472 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 13:43:04.103   873   886 I ActivityManager: Start proc 4473:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 13:43:04.109  4441  4469 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 13:43:04.114   873  1938 I ActivityManager: Start proc 4484:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 13:43:04.149  4473  4473 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:43:04.149  4473  4473 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:43:04.149  4473  4473 D AndroidRuntime: Shutting down VM
,08-16 13:43:04.158  4473  4473 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:43:04.158  4473  4473 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4473
08-16 13:43:04.158  4473  4473 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:43:04.158  4473  4473 E AndroidRuntime: 	... 10 more
,08-16 13:43:04.159   873  1916 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 13:43:04.160   873  4499 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:43:04.160   873  4499 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:04.160   873  4499 E DropBoxManagerService: 	... 5 more
08-16 13:43:04.160  4473  4473 I Process : Sending signal. PID: 4473 SIG: 9
,08-16 13:43:04.172  4441  4472 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.172  4441  4472 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:43:04.173  4441  4472 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 13:43:04.173  4441  4472 E AndroidRuntime: Process: android.process.acore, PID: 4441
08-16 13:43:04.173  4441  4472 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.173  4441  4472 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 13:43:04.175  1739  4498 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 13:43:04.176  1739  4498 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 13:43:04.181   873  4500 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:43:04.181   873  4500 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:04.181   873  4500 E DropBoxManagerService: 	... 5 more
,08-16 13:43:04.183  4441  4472 I Process : Sending signal. PID: 4441 SIG: 9
,08-16 13:43:04.185  4484  4484 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 13:43:04.186  1739  4498 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 13:43:04.187  1739  4498 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 13:43:04.190   873  1913 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4473) has died
,08-16 13:43:04.191   873  1913 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 13:43:04.206   873   886 I ActivityManager: Start proc 4503:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 13:43:04.208   277   277 E lowmemorykiller: Error writing /proc/4441/oom_score_adj; errno=22
,08-16 13:43:04.209   277   277 E lowmemorykiller: Error writing /proc/4441/oom_score_adj; errno=22
,08-16 13:43:04.224   873  1915 I ActivityManager: Killing 3816:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 13:43:04.244  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 13:43:04.244  1522  1522 D AndroidRuntime: Shutting down VM
,08-16 13:43:04.246  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:43:04.246  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-16 13:43:04.246  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 13:43:04.246  1522  1522 E AndroidRuntime: 	... 8 more
,08-16 13:43:04.247  4503  4503 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:43:04.247  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 13:43:04.247  4503  4503 D AndroidRuntime: Shutting down VM
,08-16 13:43:04.276   873  1387 I ActivityManager: Process android.process.acore (pid 4441) has died
,08-16 13:43:04.276   873  1387 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-16 13:43:04.281  4503  4503 E AndroidRuntime: FATAL EXCEPTION: main
08-16 13:43:04.281  4503  4503 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4503
08-16 13:43:04.281  4503  4503 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 13:43:04.281  4503  4503 E AndroidRuntime: 	... 10 more
,08-16 13:43:04.283   873  4516 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:43:04.283   873  4516 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:04.283   873  4516 E DropBoxManagerService: 	... 5 more
,08-16 13:43:04.284   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 13:43:04.285   873  4517 E DropBoxManagerService: Can't write: system_app_crash
08-16 13:43:04.285   873  4517 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 13:43:04.285   873  4517 E DropBoxManagerService: 	... 5 more
,08-16 13:43:04.288  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
,08-16 13:43:04.288  4503  4503 I Process : Sending signal. PID: 4503 SIG: 9
08-16 13:43:04.291  1739  4498 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 13:43:04.292  1739  4498 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 13:43:04.321   873  1308 D WifiService: Client connection lost with reason: 4
,08-16 13:43:04.325   873  1947 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4503) has died
,08-16 13:43:04.327   873  1947 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
