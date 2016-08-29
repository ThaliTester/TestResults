#### Test 83070177977a8d1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-29 13:44:27.252  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:27.262  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:27.268  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:27.312  1503  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 13:44:27.312  1503  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:44:27.312  1503  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:44:27.313  1503  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 13:44:27.369  3559  3559 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 13:44:27.369  3559  3559 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 13:44:27.369  3559  3559 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-29 13:44:27.861  3846  3846 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 13:44:27.865  3846  3846 D AndroidRuntime: CheckJNI is OFF
08-29 13:44:27.908  3846  3846 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 13:44:27.957  3846  3846 I Radio-JNI: register_android_hardware_Radio DONE
08-29 13:44:27.978  3846  3846 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 13:44:27.982   871  3264 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 13:44:28.021  2059  2069 W SearchService: Abort, client detached.
08-29 13:44:28.029  2059  2059 I HotwordDetector: Closing mic
08-29 13:44:28.029  3846  3846 D AndroidRuntime: Shutting down VM
08-29 13:44:28.031  2059  2354 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2f4ccd7
08-29 13:44:28.031  2059  2363 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 13:44:28.045   871  1999 I ActivityManager: Start proc 3856:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 13:44:28.081   375  2365 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 13:44:28.083   375  2365 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 13:44:28.088   375  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 13:44:28.090  2059  2359 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 13:44:28.090  2059  2362 I MicroRecognitionRnrImpl: Detection finished
08-29 13:44:28.129  3856  3856 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 13:44:28.153  3856  3856 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 13:44:28.161  3856  3856 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3204-3207)
08-29 13:44:28.161  3856  3856 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:44:28.176  3856  3856 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {62c8f4}
08-29 13:44:28.177  3856  3856 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:44:28.177  3856  3856 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:44:28.182  3856  3856 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 13:44:28.184  3856  3856 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 13:44:28.215  3856  3856 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 13:44:28.249  3856  3856 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:44:28.249  3856  3856 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:44:28.249  3856  3856 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:44:28.249  3856  3856 I Adreno  : Build Date                       : 10/20/15
08-29 13:44:28.249  3856  3856 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:44:28.249  3856  3856 I Adreno  : Local Branch                     : M14
08-29 13:44:28.249  3856  3856 I Adreno  : Remote Branch                    : 
08-29 13:44:28.249  3856  3856 I Adreno  : Remote Branch                    : 
08-29 13:44:28.249  3856  3856 I Adreno  : Reconstruct Branch               : 
,08-29 13:44:28.300   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1785cf:true
,08-29 13:44:28.369  3856  3856 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 13:44:28.392  3856  3856 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 13:44:28.497  3856  3895 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 13:44:28.508  3856  3881 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 13:44:28.550  3856  3895 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 13:44:28.627   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +594ms
,08-29 13:44:28.634  1897  1897 I Keyboard.Facilitator: onFinishInput()
,08-29 13:44:28.726  3856  3856 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3856
,08-29 13:44:28.839   871   882 I ActivityManager: Killing 3219:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 13:44:28.940  3856  3856 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:44:29.061  3856  3897 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681327824
,08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 13:44:29.068  3856  3897 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@938e038 added. We now have 1 listener(s)
,08-29 13:44:29.073  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 13:44:29.073  3856  3897 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:44:29.074  3856  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:44:29.074  3856  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 13:44:29.078  3856  3897 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3bcf77 added. We now have 1 listener(s)
,08-29 13:44:29.078  3856  3897 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:29.083   871  1314 D WifiService: New client listening to asynchronous messages
,08-29 13:44:29.084  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:44:29.084  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 13:44:29.086  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:44:29.086  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:44:29.086  3856  3897 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 13:44:29.088  3856  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:29.088  3856  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 13:44:29.092  3856  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:29.093  3856  3897 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:29.093  3856  3897 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:44:29.093  3856  3897 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:29.093  3856  3897 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:44:29.233  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:29.236  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:29.238  3856  3856 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:44:29.312   871  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 13:44:29.846  3856  3906 W jxcore-log: Initializing JXcore engine
,08-29 13:44:29.847  3856  3906 W jxcore-log: JXcore engine is ready
,08-29 13:44:29.885  3906  3906 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 13:44:29.885  3906  3906 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9865]" dev="sockfs" ino=9865 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 13:44:29.885  3906  3906 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 13:44:29.885  3906  3906 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26744]" dev="sockfs" ino=26744 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 13:44:29.902  3856  3906 W jxcore-log: Starting JXcore engine
,08-29 13:44:29.986  3856  3906 W jxcore-log: Platform android
08-29 13:44:29.986  3856  3906 W jxcore-log: 
,08-29 13:44:29.986  3856  3906 W jxcore-log: Process ARCH arm
08-29 13:44:29.986  3856  3906 W jxcore-log: 
,08-29 13:44:30.206  3856  3906 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:44:30.206  3856  3906 I jxcore-log: 
,08-29 13:44:30.207  3856  3906 W jxcore-log: JXcore engine is started
,08-29 13:44:30.215  3856  3897 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 13:44:30.217  3856  3856 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 13:44:32.199   871  2017 I ActivityManager: Killing 3003:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-29 13:44:38.313  3676  3917 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 13:44:38.338  3676  3919 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 13:44:38.347  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:38.349  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:38.352  3035  3918 V KeepSync: Connecting to GoogleApiClient
08-29 13:44:38.352   871  3262 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 13:44:38.367  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 13:44:38.367  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 13:44:38.367  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:44:38.367  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:38.387  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:38.388  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:38.406  1503  3261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 13:44:38.406  1503  3261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 13:44:38.407  1503  3261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:44:38.407  1503  3261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:38.411  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 13:44:38.411  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 13:44:38.411  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 13:44:38.412  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:38.422  3676  3919 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 13:44:38.423  3676  3917 E BooksSync: Soft error
08-29 13:44:38.423  3676  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 13:44:38.423  3676  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 13:44:38.423  3676  3917 E BooksSync: Sync error
08-29 13:44:38.423  3676  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 13:44:38.423  3676  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 13:44:38.424  3676  3917 I BooksSync: Finished books sync
,08-29 13:44:38.426  1684  3920 V BaseAuthAsyncOperation: access token request failed
,08-29 13:44:38.427   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 132484, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-29 13:44:38.428  3035  3918 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 13:44:38.475  1503  2300 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 13:44:38.475  1503  2300 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 13:44:38.475  1503  2300 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:44:38.475  1503  2300 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:38.493  3035  3918 E KeepSync: IOException
08-29 13:44:38.493  3035  3918 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 13:44:38.493  3035  3918 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:44:38.493  3035  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 13:44:38.493  3035  3918 E KeepSync: 	... 10 more
08-29 13:44:38.493  3035  3918 W KeepSync: Sync result 2
,08-29 13:44:38.505   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132588, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 13:44:40.402  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 13:44:40.402  3856  3906 I jxcore-log: 
,08-29 13:44:40.404  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 13:44:40.404  3856  3906 I jxcore-log: 
,08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:40.415  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:40.419  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:40.421  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:44:40.421  3856  3906 I jxcore-log: 
,08-29 13:44:40.423  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:44:40.423  3856  3906 I jxcore-log: 
,08-29 13:44:40.930  3856  3906 D executeNativeTests: Running unit tests
,08-29 13:44:40.988  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:44:40.988  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 added. We now have 2 listener(s)
,08-29 13:44:40.989  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:44:40.990  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:44:40.990  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:44:40.990  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:40.990  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 added. We now have 2 listener(s)
,08-29 13:44:40.990  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:40.991  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:44:41.002  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.015  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:41.019  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:41.019  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:41.030  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.031  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:44:41.032  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:44:41.032  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:44:41.033  3856  3906 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 13:44:41.033  3856  3906 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:41.033  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:41.033  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 13:44:41.033  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:41.034  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.034  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.034  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.034  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.035  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.035  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.035  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:44:41.035  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 removed from the list
08-29 13:44:41.035  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.035  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 removed from the list
08-29 13:44:41.037  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.037  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.037  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.037  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.038  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.038  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.038  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.038  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.038  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.040  3856  3906 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 13:44:41.040  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.041  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.041  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.041  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.041  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.041  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.041  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.041  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.041  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.041  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.041  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.041  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.041  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.041  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.042  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.042  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.042  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.042  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44,:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:41.047  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:41.048  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:44:41.049  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:41.049  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.049  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.049  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.049  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.049  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.049  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.049  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.049  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.049  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.049  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.049  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.049  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.049  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.050  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.051  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.051  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.051  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.051  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.051  3856  3906 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:41.054  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.057  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:41.059  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.059  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:41.060  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:41.060  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:41.060  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:41.060  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.060  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:41.061  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.063  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.065  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:44:41.065  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:44:41.071  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:44:41.072  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:44:41.073  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:44:41.076  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 13:44:41.080  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 13:44:41.080  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:44:41.080  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:44:41.081  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:44:41.082  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:44:41.084  2528  2541 D BtGatt.GattService: registerClient() - UUID=009ad4bc-1512-45f5-90d1-bf67025319c9
08-29 13:44:41.085  2528  2547 D BtGatt.GattService: onClientRegistered() - UUID=009ad4bc-1512-45f5-90d1-bf67025319c9, clientIf=5
08-29 13:44:41.086  3856  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:44:41.087  2528  2578 D BtGatt.GattService: start scan with filters
08-29 13:44:41.089  2528  2550 D BtGatt.ScanManager: handling starting scan
08-29 13:44:41.089  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:44:41.090  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:41.090  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:44:41.090  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:44:41.091  2528  2550 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:44:41.092  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:41.092  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:41.093  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:44:41.094  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:44:41.098  3856  3906 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:44:41.098  2528  2547 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:44:41.098  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.099  2528  2550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:44:41.103  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.103  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:44:41.103  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.104  3856  3906 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:41.104  2528  2550 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:44:41.104  2528  2550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:44:41.104  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.104  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:44:41.105  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.105  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:41.105  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:41.105  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:44:41.109  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:41.110  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:41.111  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:41.111  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:44:41.112  3856  3906 D BluetoothAdapter: STATE_ON
08-29 13:44:41.113  2528  2570 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:44:41.113  2528  2539 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:44:41.114  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:41.115  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:41.115  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:41.115  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:41.115  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:44:41.116  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.117  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:44:41.117  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:44:41.117  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:41.117  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.117  2528  2547 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:44:41.118  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.118  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.118  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.118  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.118  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.118  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.118  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.118  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.118  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.118  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.118  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.119  3856  3906 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:41.119  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.120  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.124  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:41.126  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.126  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:41.126  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:41.126  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:41.126  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:41.126  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.126  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:44:41.126  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:41.126  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:44:41.129  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.130  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:44:41.130  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:44:41.133  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:44:41.134  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.134  2528  2550 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:44:41.134  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.136  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:44:41.137  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:44:41.137  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:44:41.142  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:44:41.142  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.142  2528  2550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:44:41.143  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:44:41.144  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:44:41.144  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:44:41.145  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:44:41.147  2528  2570 D BtGatt.GattService: registerClient() - UUID=5ddc361f-72da-40f5-94b9-86faa5b18d18
08-29 13:44:41.147  2528  2547 D BtGatt.GattService: onClientRegistered() - UUID=5ddc361f-72da-40f5-94b9-86faa5b18d18, clientIf=5
,08-29 13:44:41.148  3856  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:44:41.148  2528  2541 D BtGatt.GattService: start scan with filters
,08-29 13:44:41.150  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:44:41.150  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:41.150  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:44:41.150  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:44:41.152  2528  2547 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:44:41.152  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.152  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:41.152  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:44:41.152  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:41.153  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:44:41.154  3856  3906 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:44:41.154  2528  2550 D BtGatt.ScanManager: handling starting scan
,08-29 13:44:41.156  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.156  3856  3906 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:41.156  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.156  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:44:41.156  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.157  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:41.157  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:41.157  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:44:41.157  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:41.157  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:41.157  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:41.157  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:44:41.157  3856  3906 D BluetoothAdapter: STATE_ON
08-29 13:44:41.158  2528  2570 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:44:41.158  2528  2541 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:44:41.158  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:41.158  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:41.158  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:41.158  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:41.158  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:44:41.159  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:41.159  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:44:41.159  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:44:41.159  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:41.159  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.161  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:41.161  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.161  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.161  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.161  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
,08-29 13:44:41.161  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.161  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.161  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.161  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.161  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:41.161  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.161  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.162  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.163  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.163  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.163  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.163  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.163  2528  2547 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:44:41.163  3856  3906 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:44:41.163  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.164  2528  2550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:44:41.164  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.169  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:41.171  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-29 13:44:41.171  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:41.171  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:41.171  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:41.171  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:41.171  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:44:41.171  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.171  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.171  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:44:41.171  2528  2550 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:44:41.171  2528  2550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:44:41.173  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:44:41.173  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:44:41.174  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.176  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.177  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:44:41.178  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:44:41.178  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:44:41.181  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:44:41.181  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:44:41.181  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:44:41.181  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:44:41.183  2528  2541 D BtGatt.GattService: registerClient() - UUID=0aa78499-e5e5-4836-afa1-a3b03648ff04
,08-29 13:44:41.184  2528  2547 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:44:41.184  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.184  2528  2547 D BtGatt.GattService: onClientRegistered() - UUID=0aa78499-e5e5-4836-afa1-a3b03648ff04, clientIf=5
08-29 13:44:41.184  3856  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:44:41.185  2528  2570 D BtGatt.GattService: start scan with filters
,08-29 13:44:41.188  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:44:41.188  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:41.188  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:44:41.188  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:44:41.190  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:41.190  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:44:41.190  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:41.190  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:44:41.190  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.191  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:44:41.193  3856  3906 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:44:41.193  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.193  3856  3906 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:41.193  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.193  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:44:41.193  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.193  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:41.193  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 13:44:41.193  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:44:41.193  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:41.193  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-29 13:44:41.193  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:41.193  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:44:41.194  3856  3906 D BluetoothAdapter: STATE_ON
08-29 13:44:41.195  2528  2570 D BtGatt.GattService: stopScan() - queue size =0
08-29 13:44:41.195  2528  2539 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:44:41.195  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:41.195  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:41.195  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:41.195  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:41.195  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:44:41.196  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.196  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:44:41.196  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:44:41.196  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:41.196  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.197  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:44:41.197  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.198  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.198  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:41.198  3856  3906 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:41.198  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.198  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.198  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:41.198  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.198  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:41.198  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.198  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.199  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.199  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:44:41.199  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:41.199  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.199  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.199  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.199  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.199  2528  2550 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:44:41.200  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.200  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 13:44:41.200  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.200  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.200  3856  3906 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:44:41.201  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.201  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.201  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:41.201  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.201  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.201  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.201  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.201  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.201  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.201  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.201  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.201  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.201  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.202  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.202  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.202  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 13:44:41.202  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 13:44:41.202  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.203  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:41.203  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:41.203  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.203  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.203  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.203  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.203  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.203  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.204  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.204  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.204  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 13:44:41.204  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.204  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.204  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.204  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.205  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.205  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:41.205  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.205  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.206  3856  3906 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 13:44:41.206  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.206  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.206  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.206  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:41.206  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.206  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.206  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.206  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.206  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.206  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.206  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:44:41.206  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.207  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.207  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:44:41.207  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.207  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.207  2528  2550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:44:41.208  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:44:41.208  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.208  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.208  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.208  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 13:44:41.208  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.208  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.208  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:41.209  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.209  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.209  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.209  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
,08-29 13:44:41.209  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.209  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.209  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:41.209  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.209  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.209  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.209  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.210  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.210  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:41.210  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.210  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.210  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:44:41.211  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:41.211  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 13:44:41.211  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:41.211  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:44:41.211  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:41.211  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:41.211  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.211  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.211  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:41.211  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.211  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.211  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.211  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.211  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
,08-29 13:44:41.211  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.211  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.212  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.212  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 13:44:41.212  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.212  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.212  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.212  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.213  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.213  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:41.213  3856  3906 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:41.213  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 13:44:41.215  2528  2547 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:44:41.216  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:41.216  3856  3906 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:41.216  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 13:44:41.215  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-29 13:44:41.217  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:41.217  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:44:41.218  3856  3906 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:41.218  3856  3906 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 13:44:41.218  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:41.218  3856  3906 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:41.218  3856  3906 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:44:41.218  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:44:41.218  3856  3906 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:41.218  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:41.219  2528  2550 D BtGatt.ScanManager: handling starting scan
08-29 13:44:41.221  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 13:44:41.221  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-29 13:44:41.221  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 13:44:41.222  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:44:41.222  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 13:44:41.222  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-29 13:44:41.222  3856  3906 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:41.222  3856  3906 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 13:44:41.223  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.223  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.223  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:41.223  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.223  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.223  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.223  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:44:41.224  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
,08-29 13:44:41.224  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.224  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.224  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.224  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.224  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.224  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 13:44:41.224  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.225  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.225  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.225  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.225  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
,08-29 13:44:41.225  3856  3906 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:44:41.226  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.226  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:41.226  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.226  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.226  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.226  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.226  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.226  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.226  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.226  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.226  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.226  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.226  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.226  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.227  2528  2547 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:44:41.227  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.227  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.227  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:41.227  2528  2550 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:44:41.227  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.227  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.228  3856  3906 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:44:41.228  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.228  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:41.228  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.229  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.229  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.229  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.229  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.230  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.230  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.230  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 13:44:41.230  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.230  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.230  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.230  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.231  3856  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 405
08-29 13:44:41.231  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:44:41.231  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.232  2528  2550 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:44:41.232  2528  2550 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:44:41.232  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.232  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.233  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.233  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.233  3856  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 405)
08-29 13:44:41.233  3856  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 405)
08-29 13:44:41.234  3856  3906 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:44:41.234  3856  3906 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:44:41.235  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:41.235  3856  3906 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-29 13:44:41.235  3856  3906 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:44:41.235  3856  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:44:41.235  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:41.235  3856  3906 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:44:41.235  3856  3906 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-29 13:44:41.235  3856  3906 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:41.235  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:41.236  3856  3906 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:44:41.236  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.236  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.236  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.236  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.236  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.236  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.237  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.237  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.237  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.237  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:41.237  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.237  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.237  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.237  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.238  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.239  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.239  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.239  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.239  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.239  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.239  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.240  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.240  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.240  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.240  2528  2547 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:44:41.240  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.240  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.240  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.240  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.240  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.240  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.241  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.241  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.241  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.241  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.241  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.241  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.242  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.242  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.242  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.242  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.242  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.242  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.242  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.242  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.242  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.242  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.242  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.243  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.244  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.244  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:44:41.244  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.244  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.244  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.244  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.246  3856  3906 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:44:41.246  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:41.247  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:44:41.248  3856  3906 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:44:41.248  3856  3906 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 13:44:41.248  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:44:41.248  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:41.248  3856  3856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:44:41.249  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.249  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:44:41.249  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:44:41.249  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:44:41.249  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.249  3856  3906 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:44:41.250  3856  3856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:44:41.250  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.250  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.250  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:44:41.250  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:41.250  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:41.250  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.250  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.251  2528  2547 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:44:41.251  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.251  2528  2550 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:44:41.252  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.252  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.252  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.252  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.252  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:41.252  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:41.252  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.252  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:41.253  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.253  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.253  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.253  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.253  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.253  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.253  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.253  3856  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:41.253  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.253  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.253  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.253  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.254  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.254  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.254  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:41.255  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.256  3856  3906 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:44:41.256  3856  3906 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:41.256  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:41.256  3856  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 13:44:41.256  3856  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:44:41.256  3856  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:44:41.257  2528  2547 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:44:41.257  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.257  2528  2550 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:44:41.258  3856  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 13:44:41.258  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:41.260  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.260  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.260  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.260  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.261  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.261  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.261  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.261  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.262  2528  2547 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:44:41.262  2528  2547 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:44:41.263  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.263  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:41.263  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.263  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.263  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.263  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.264  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.265  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.265  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.265  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.269  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.269  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.269  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.270  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.270  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.270  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.270  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.270  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.270  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.270  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.271  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.271  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.271  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:41.271  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.272  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.272  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.272  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.272  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.273  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:41.273  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:41.273  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:41.273  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:41.273  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.273  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.273  3856  3906 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88f3908 not in the list
08-29 13:44:41.273  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.273  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.273  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:41.273  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.274  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:41.274  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:41.274  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:41.275  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:41.275  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:41.275  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:41.275  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8be8a1 not in the list
08-29 13:44:41.276  3856  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:44:41.276  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:41.276  3856  3906 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:44:41.276  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:41.277  3856  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:44:41.277  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:41.278  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:41.278  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:44:41.279  3856  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:44:41.279  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:41.279  3856  3906 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 13:44:41.279  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:41.279  3856  3906 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:44:41.280  3856  3906 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:44:41.280  3856  3906 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:44:41.280  3856  3906 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 13:44:41.281  3856  3906 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:44:41.281  3856  3906 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-29 13:44:41.281  3856  3906 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:44:41.281  3856  3906 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:44:41.282  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:41.282  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9dd689b added. We now have 2 listener(s)
08-29 13:44:41.282  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:41.284  3856  3906 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 13:44:41.284   871  1682 D WifiService: setWifiEnabled: true pid=3856, uid=10000
08-29 13:44:41.284   871  1682 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:44:41.285  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:41.285  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c06f438 added. We now have 3 listener(s)
08-29 13:44:41.285  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:41.291  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:41.291  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8af3c11 added. We now have 4 listener(s)
08-29 13:44:41.291  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:41.293  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:41.293  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d0ff176 added. We now have 5 listener(s)
08-29 13:44:41.293  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:41.295   871  1402 D WifiService: setWifiEnabled: false pid=3856, uid=10000
,08-29 13:44:41.295   871  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:44:41.300  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:41.300  2528  2543 D BluetoothAdapterState: Current state: ON, message: 23
08-29 13:44:41.300  2528  2543 D BluetoothAdapterProperties: Setting state to 13
08-29 13:44:41.300  2528  2543 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:44:41.301  2528  2543 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 13:44:41.301  2528  2543 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:44:41.303  2528  2528 D BluetoothMapService: onReceive
08-29 13:44:41.303  2528  2528 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:41.303  2528  2528 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:44:41.303  2528  2528 D BluetoothMapService: MAP Service closeService in
08-29 13:44:41.303  2528  2528 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 13:44:41.303  2528  2528 D ObexServerSockets0: shutdown(block = true)
08-29 13:44:41.304  2528  2528 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:44:41.304  2528  2528 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:44:41.304  2528  2580 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 13:44:41.304  2528  2567 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 13:44:41.304  2528  2579 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 13:44:41.304  2528  2528 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:41.305  2528  3412 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:41.305  2528  3412 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:44:41.305  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.305  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:41.307  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.307  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:41.308  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:41.312  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.315  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.315  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:44:41.316   871  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:44:41.316   871  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 13:44:41.316   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:44:41.317   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:41.321  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:41.321  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:41.322  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.322  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:41.322   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:41.323   871  2132 D DhcpClient: Clearing IP address
08-29 13:44:41.323   871   884 I ActivityManager: Start proc 3926:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 13:44:41.325  2528  2547 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:41.325  2528  2543 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 13:44:41.325   371   869 D CommandListener: Setting iface cfg
08-29 13:44:41.326  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.326  1503  2693 V NativeCrypto: Read error: ssl=0x9a4ffa00: I/O error during system call, Connection timed out
08-29 13:44:41.328  2528  2528 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:44:41.329  1503  2693 V NativeCrypto: SSL shutdown failed: ssl=0x9a4ffa00: I/O error during system call, Broken pipe
,08-29 13:44:41.331  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.334  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:41.336   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 13:44:41.336   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 13:44:41.338   394   394 E Parcel  : Reading a NULL string not supported here.
08-29 13:44:41.342  1962  1987 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:41.343  1359  2075 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:41.344   871  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 13:44:41.344  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-29 13:44:41.345   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:44:41.345   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:41.345   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:41.345   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 13:44:41.347  2528  2528 D A2dpService: Received stop request...Stopping profile...
08-29 13:44:41.347  2528  2573 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:44:41.347   871  2184 D DhcpClient: Receive thread stopped
08-29 13:44:41.348   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:41.341   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 13:44:41.349  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:41.349   871   871 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:41.349  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.349  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.349  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.349  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.351  2528  2528 D HidService: Received stop request...Stopping profile...
08-29 13:44:41.351  2528  2528 D HidService: Stopping Bluetooth HidService
08-29 13:44:41.357  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-29 13:44:41.357  1359  1359 D HidProfile: Bluetooth service disconnected
08-29 13:44:41.359  2528  2528 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:41.359  2528  2547 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:44:41.359  2528  2528 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:41.359  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.359  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.359  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.359  2528  2547 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 13:44:41.359   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 13:44:41.361  2528  2528 D HealthService: Received stop request...Stopping profile...
08-29 13:44:41.363  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.363  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.363  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.363  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.364  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:41.364  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:41.366  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.366  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:41.366  2528  2547 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 13:44:41.366  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.366  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.366  2528  2563 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:41.367  2528  2563 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:41.367  2528  2563 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:41.367  2528  2563 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:41.367  2528  2528 D PanService: Received stop request...Stopping profile...
08-29 13:44:41.368  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:44:41.368  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.369  1359  1359 D PanProfile: Bluetooth service disconnected
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:41.369  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:41.369  2528  2528 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:44:41.369  2528  2528 D BluetoothMapService: stop()
08-29 13:44:41.369  2528  2528 D BluetoothMapAppObserver: deinitObservers()
08-29 13:44:41.369  2528  2528 D BluetoothMapAppObserver: removeReceiver()
08-29 13:44:41.369  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:41.369  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:41.370  1359  1359 D BluetoothMap: Proxy object disconnected
08-29 13:44:41.370  1359  1359 D MapProfile: Bluetooth service disconnected
08-29 13:44:41.371   871  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:44:41.373  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.373  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.373  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.373  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.374  2528  2528 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:44:41.374  2528  2547 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:44:41.374  2528  2528 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:44:41.375  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.375  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.375  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.375  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.375  2528  2528 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:44:41.375  2528  2547 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:44:41.375  25,28  2528 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:41.376  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.376  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.376  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.376  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.377  2528  2528 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:41.377  2528  2528 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:44:41.378  2528  2528 D BluetoothMapService: MAP Service closeService in
08-29 13:44:41.378  2528  2528 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:41.379  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.379  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.379  2528  2528 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:41.379  2528  2543 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 13:44:41.379  2528  2543 D BluetoothAdapterProperties: Setting state to 15
08-29 13:44:41.379  2528  2543 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 13:44:41.380  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:41.380  2528  2543 I BluetoothAdapterState: Entering BleOnState
08-29 13:44:41.380   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:41.380  1359  1376 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:44:41.381  1359  2075 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:41.381   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:41.381  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:44:41.382  1359  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:44:41.382  1962  2105 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:41.382   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:41.383   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:41.383  1359  2075 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:44:41.384  2528  2543 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:44:41.384  2528  2543 D BluetoothAdapterProperties: Setting state to 16
08-29 13:44:41.384  2528  2543 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 13:44:41.384  2528  2543 D BluetoothAdapterProperties: onBleDisable
08-29 13:44:41.384  2528  2543 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:44:41.384  2528  2544 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 13:44:41.385  2528  2563 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:44:41.385  2528  2563 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:41.389  2528  2547 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:41.390  2528  2528 D BluetoothMapService: cleanup()
08-29 13:44:41.390  2528  2528 D BluetoothMapService: MAP Service closeService in
08-29 13:44:41.391  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.392  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.392  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.393  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.397   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 13:44:41.402  3926  3926 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-29 13:44:41.407  1857  2270 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:41.416  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 13:44:41.421   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 13:44:41.422   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 13:44:41.422   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 13:44:41.423   871   888 D Tethering: MasterInitialState.processMessage what=3
08-29 13:44:41.426  3452  3452 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@938e038 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 13:44:41.427  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.428  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:41.430  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:41.436   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e3e0ac:true
08-29 13:44:41.441   871  1402 I ActivityManager: Start proc 3943:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 13:44:41.459  3926  3926 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 13:44:41.460  3926  3926 D BluetoothMap: Create BluetoothMap proxy object
08-29 13:44:41.468  3926  3926 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 13:44:41.474   371   869 E Netd    : netlink response contains error (No such file or directory)
08-29 13:44:41.474  3943  3943 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-29 13:44:41.475   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 13:44:41.481  3926  3926 D DockEventReceiver: finishStartingService: stopping service
08-29 13:44:41.488   871  1680 I ActivityManager: Killing 3620:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 13:44:41.587  2528  2547 I bt_hci  : shut_down
,08-29 13:44:41.600  2528  2551 D bt_hwcfg: hw_epilog_process
,08-29 13:44:41.600  2528  2551 I bt_vendor: low_power_mode_cb
,08-29 13:44:41.626  2528  2551 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 13:44:41.627  2528  2551 I bt_vendor: epilog_cb
,08-29 13:44:41.627  2528  2551 I bt_hci  : epilog_finished_callback
,08-29 13:44:41.633  2528  2547 I bt_hci_h4: hal_close
,08-29 13:44:41.634  2528  2547 I bt_userial_vendor: device fd = 51 close
,08-29 13:44:41.653  3943  3943 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.653  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:44:41.654  3943  3943 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:44:41.654  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:44:41.720   871  3047 I ActivityManager: Start proc 3976:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-29 13:44:41.722   871  3047 I ActivityManager: Killing 3452:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 13:44:41.752  3856  3856 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:44:41.801  2528  2544 D bt_stack_manager: event_shut_down_stack finished.
,08-29 13:44:41.802  2528  2543 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:44:41.811  2528  2543 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 13:44:41.811  2528  2528 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:44:41.811  3976  3976 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-29 13:44:41.811  2528  2528 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:44:41.811  2528  2528 D BtGatt.GattService: stop()
08-29 13:44:41.812  2528  2528 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 13:44:41.814  2528  2528 V BluetoothAdapterState: isTurningOff()=false
08-29 13:44:41.814  2528  2528 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:41.814  2528  2528 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:41.814  2528  2528 V BluetoothAdapterState: isBleTurningOff()=true
08-29 13:44:41.814  2528  2543 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 13:44:41.815  2528  2543 D BluetoothAdapterProperties: Setting state to 10
08-29 13:44:41.815  2528  2543 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 13:44:41.815  2528  2543 I BluetoothAdapterState: Entering OffState
08-29 13:44:41.816   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 13:44:41.831  2528  2528 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 13:44:41.831  2528  2528 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 13:44:41.831  2528  2528 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:44:41.832  2528  2544 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 13:44:41.835  2528  2544 D bt_stack_manager: event_clean_up_stack finished.
,08-29 13:44:41.867  2528  2528 I art     : System.exit called, status: 0
08-29 13:44:41.867  2528  2528 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:44:41.903  3976  3976 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 13:44:41.923  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:41.928   871  1402 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,08-29 13:44:41.931   871  1402 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
,08-29 13:44:41.937   871  1402 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-29 13:44:41.937   871  1402 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 13:44:41.937   871  1402 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 13:44:41.966   871  1402 I ActivityManager: Start proc 4004:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-29 13:44:41.967   871   882 W ActivityManager: Spurious death for ProcessRecord{fd8d741 4004:com.android.bluetooth/1002}, curProc for 2528: null
08-29 13:44:41.968  3926  3926 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:41.987  3943  3973 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:44:42.025   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e75250c:true
,08-29 13:44:42.032  4004  4004 D AdapterServiceConfig: Adding HeadsetService
08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding A2dpService
08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding HidService
,08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding HealthService
08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding PanService
08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding GattService
08-29 13:44:42.033  4004  4004 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:44:42.036   871  2015 I ActivityManager: Killing 3507:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 13:44:42.075  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:42.095  1684  1684 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:44:42.100  1684  1684 D SystemUpdateService: onCreate
,08-29 13:44:42.106  1684  1684 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:44:42.110  1684  4016 I SystemUpdateService: active receiver: enabled
,08-29 13:44:42.114  1684  4016 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:44:42.116  1684  4016 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 13:44:42.116  1684  4016 I SystemUpdateService: now status is 0 (complete)
08-29 13:44:42.116  1684  4016 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 13:44:42.116  1684  4016 I SystemUpdateService: file has been verified
08-29 13:44:42.116  1684  4016 I SystemUpdateService: OTA package size = 12249756
08-29 13:44:42.116  1684  1684 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:44:42.120  1684  2595 I iu.UploadsManager: num queued entries: 0
08-29 13:44:42.120  1684  4016 I SystemUpdateService: showing system update notification
,08-29 13:44:42.121  1684  2595 I iu.UploadsManager: num updated entries: 0
08-29 13:44:42.122  1684  2595 I iu.SyncManager: NEXT; no task
,08-29 13:44:42.131  1684  1684 D SystemUpdateService: onDestroy
,08-29 13:44:42.143  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-29 13:44:42.145  1684  1684 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:44:42.177   871  2011 I ActivityManager: Start proc 4018:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 13:44:42.223  4018  4018 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 13:44:42.226  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:42.235  4018  4018 D SprintDMHelper: simOperator: 
08-29 13:44:42.235  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:44:42.259   871  1999 I ActivityManager: Start proc 4030:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-29 13:44:42.262   871  1999 I ActivityManager: Killing 3541:android.process.acore/u0a5 (adj 15): empty #17
,08-29 13:44:42.415   871  3047 I ActivityManager: Start proc 4045:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider,
,08-29 13:44:42.418  3084  4044 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 13:44:42.422   871  1680 I ActivityManager: Killing 3725:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 13:44:42.517  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 13:44:42.582  4045  4045 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 13:44:42.582  4045  4045 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:44:42.582  4045  4045 I GAv4    :   adb logcat -s GAv4
,08-29 13:44:42.597  4045  4045 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:44:42.603  4045  4045 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-29 13:44:42.632  4045  4062 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:44:42.750  4045  4045 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 13:44:42.792  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 13:44:42.803  4045  4045 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7843-7849)
,08-29 13:44:42.804  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:44:42.813  4045  4045 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc0c768}
,08-29 13:44:42.813  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:44:42.814  4045  4045 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:44:42.822  4045  4045 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 13:44:42.824  4045  4045 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 13:44:42.844  4045  4045 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 13:44:42.861  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:44:42.861  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:44:42.861  4045  4045 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:44:42.861  4045  4045 I Adreno  : Build Date                       : 10/20/15
08-29 13:44:42.861  4045  4045 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:44:42.861  4045  4045 I Adreno  : Local Branch                     : M14
08-29 13:44:42.861  4045  4045 I Adreno  : Remote Branch                    : 
08-29 13:44:42.861  4045  4045 I Adreno  : Remote Branch                    : 
08-29 13:44:42.861  4045  4045 I Adreno  : Reconstruct Branch               : 
,08-29 13:44:42.924  4045  4045 I NSApplication: Starting up...
,08-29 13:44:42.946  4045  4091 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 13:44:42.952   871  1680 I ActivityManager: Start proc 4096:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 13:44:42.953   871  1680 I ActivityManager: Killing 3741:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 13:44:43.042  4096  4096 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 13:44:43.243   871  1682 I ActivityManager: Killing 3475:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 13:44:44.311   871  3264 D WifiService: setWifiEnabled: true pid=3856, uid=10000
,08-29 13:44:44.311   871  3264 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:44:44.325   871  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:44:44.335  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:44.335  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:44.336  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:44.336  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:44.339  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:44.340  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:44.340  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:44.340  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:44.367   871  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:44:44.368   871  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 13:44:44.368   871  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 13:44:44.369   871  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:44:44.370   871  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 13:44:44.370   871  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 13:44:44.370   871  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,08-29 13:44:44.392   871  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.50 rxSuccessRate=11.50 delta 1000 -> 994
,08-29 13:44:44.392   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 13:44:44.394   371   869 D CommandListener: Setting iface cfg
08-29 13:44:44.396   871  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
08-29 13:44:44.396   871  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:44:44.401   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 13:44:44.401   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.406   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:44:44.436   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:44:44.437   871  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 13:44:44.438   871  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:44:44.439  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:44:44.863  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:44:44.904  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:44:44.905  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:44:44.913   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:44:44.928   871  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:44:44.928   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.928   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 13:44:44.954   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.970   371   869 D CommandListener: Setting iface cfg
,08-29 13:44:44.973   871  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 13:44:44.991   871  1315 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 13:44:44.995   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:44:45.005   871  4120 D DhcpClient: Receive thread started
,08-29 13:44:45.090   871  1312 E native  : do suspend false
,08-29 13:44:45.110   871  2132 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 13:44:45.126   871  4120 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,08-29 13:44:45.127   871  2132 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,08-29 13:44:45.131   871  2132 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:44:45.153   871  4120 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 13:44:45.154   871  2132 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:44:45.159   371   869 D CommandListener: Setting iface cfg
,08-29 13:44:45.171   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 13:44:45.172   871  2132 D DhcpClient: Scheduling renewal in 86399s
,08-29 13:44:45.190   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 13:44:45.193   871  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 13:44:45.193   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:45.194   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 13:44:45.203   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 13:44:45.217   871  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:44:45.253   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 13:44:45.254   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 13:44:45.257   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 13:44:45.262   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 13:44:45.266   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 13:44:45.276   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:45.282   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 13:44:45.282   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:45.282   871  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 13:44:45.283   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:44:45.283   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:45.283   871  1315 D ConnectivityService:    accepting network in place of null
,08-29 13:44:45.284   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:44:45.313   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:44:45.347   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:44:45.353   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 13:44:45.353   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:45.361   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:44:45.365   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:45.386  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:45.386  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:45.387  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.387  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:45.388  1684  1684 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:44:45.392  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:45.392  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:45.392  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:45.392  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:45.396  1684  1684 D SystemUpdateService: onCreate
,08-29 13:44:45.400  1684  1684 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:44:45.402  1684  4134 I SystemUpdateService: active receiver: enabled
,08-29 13:44:45.405  1684  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:44:45.409  1684  4134 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 13:44:45.409  1684  4134 I SystemUpdateService: now status is 0 (complete)
08-29 13:44:45.409  1684  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 13:44:45.409  1684  4134 I SystemUpdateService: file has been verified
08-29 13:44:45.409  1684  4134 I SystemUpdateService: OTA package size = 12249756
,08-29 13:44:45.415  1684  4134 I SystemUpdateService: showing system update notification
,08-29 13:44:45.420  1684  1684 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:44:45.423  1684  2595 I iu.UploadsManager: num queued entries: 0
,08-29 13:44:45.423  1684  2595 I iu.UploadsManager: num updated entries: 0
08-29 13:44:45.424  1684  2595 I iu.SyncManager: NEXT; no task
,08-29 13:44:45.427  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:44:45.428  1684  1684 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:44:45.430  1684  1684 D SystemUpdateService: onDestroy
,08-29 13:44:45.433  1684  4137 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 13:44:45.433  1684  4137 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 13:44:45.434  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:45.434  1684  4137 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 13:44:45.438  4018  4018 D SprintDMHelper: simOperator: 
08-29 13:44:45.438  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 13:44:45.439  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:45.440  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:44:45.470  1503  2393 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:44:45.470  1503  2393 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 13:44:45.470  1503  2393 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:44:45.470  1503  2393 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:45.484  1684  4137 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-29 13:44:45.982   871  4119 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141028, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 13:44:46.354   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 13:44:46.411   871  4118 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:802::200e
,08-29 13:44:46.854  3084  4139 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 13:44:47.018   871  3262 I ActivityManager: Killing 3765:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 13:44:47.319   871  1682 D WifiService: setWifiEnabled: false pid=3856, uid=10000
08-29 13:44:47.320   871  1682 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:44:47.350  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 13:44:47.357   871  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 13:44:47.357   871  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 13:44:47.358   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:44:47.358   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:47.383   871  2132 D DhcpClient: Clearing IP address
,08-29 13:44:47.385   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:47.391  1503  4145 V NativeCrypto: Read error: ssl=0xaee14c00: I/O error during system call, Connection timed out
08-29 13:44:47.394  1503  4145 V NativeCrypto: SSL shutdown failed: ssl=0xaee14c00: I/O error during system call, Broken pipe
08-29 13:44:47.398   871  4118 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-29 13:44:47.399   371   869 D CommandListener: Setting iface cfg
08-29 13:44:47.401   871  4120 D DhcpClient: Receive thread stopped
08-29 13:44:47.401   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-29 13:44:47.405   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 13:44:47.406   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 13:44:47.412   871  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 13:44:47.414   394   394 E Parcel  : Reading a NULL string not supported here.
08-29 13:44:47.416   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:44:47.417   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:47.428   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 13:44:47.429   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 13:44:47.433  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:47.433  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:47.434  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:47.434  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:47.434  1857  2270 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:47.435  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:47.435  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:47.435  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:47.435  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:47.438   871  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 13:44:47.462   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:44:47.494   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:44:47.495   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 13:44:47.495   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:47.497   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:44:47.500  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:47.503  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:47.505  1684  1684 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:44:47.509  1684  1684 D SystemUpdateService: onCreate
,08-29 13:44:47.512  1684  1684 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:44:47.520  1684  1684 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:44:47.523  1684  2595 I iu.UploadsManager: num queued entries: 0
,08-29 13:44:47.526  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:44:47.527  1684  1684 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:44:47.530  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:47.534  4018  4018 D SprintDMHelper: simOperator: 
,08-29 13:44:47.534  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:44:47.535  1684  4156 I SystemUpdateService: active receiver: enabled
,08-29 13:44:47.536  1684  2595 I iu.UploadsManager: num updated entries: 0
,08-29 13:44:47.548  1684  2595 I iu.SyncManager: NEXT; no task
,08-29 13:44:47.559  3084  4160 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 13:44:47.561   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-29 13:44:47.562   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 13:44:47.562   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 13:44:47.562  1684  4156 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:44:47.576  4045  4045 I art     : Waiting for a blocking GC DisableMovingGc
,08-29 13:44:47.577  1684  4156 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 13:44:47.577  1684  4156 I SystemUpdateService: now status is 0 (complete),
08-29 13:44:47.577  1684  4156 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:44:47.577  1684  4156 I SystemUpdateService: file has been verified
08-29 13:44:47.577  1684  4156 I SystemUpdateService: OTA package size = 12249756
,08-29 13:44:47.579  4045  4045 I art     : Starting a blocking GC DisableMovingGc
,08-29 13:44:47.604  1684  4156 I SystemUpdateService: showing system update notification
,08-29 13:44:47.614  1684  1684 D SystemUpdateService: onDestroy
,08-29 13:44:50.370  4004  4004 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 13:44:50.370   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf9c7e:true
,08-29 13:44:50.376  4004  4004 I bt_bluedroid: init
,08-29 13:44:50.376  4004  4163 I BluetoothAdapterState: Entering OffState
,08-29 13:44:50.379  4004  4164 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 13:44:50.379  4004  4164 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 13:44:50.379  4004  4164 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:44:50.380  4004  4164 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 13:44:50.381  4004  4004 I bt_bluedroid: get_profile_interface socket
08-29 13:44:50.384  4004  4004 I bt_bluedroid: get_profile_interface sdp
08-29 13:44:50.387  4004  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:44:50.389  4004  4015 I bt_bluedroid: config_hci_snoop_log
08-29 13:44:50.391   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:44:50.391  4004  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:44:50.397  4004  4163 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 13:44:50.398  4004  4163 D BluetoothAdapterProperties: Setting state to 14
08-29 13:44:50.398  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:44:50.403  4004  4163 D BluetoothBondStateMachine: make
,08-29 13:44:50.407  4004  4168 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:44:50.412  4004  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:44:50.413  4004  4004 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 13:44:50.416  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:50.417  4004  4004 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:44:50.418  4004  4004 D BtGatt.GattService: Received start request. Starting profile...
,08-29 13:44:50.418  4004  4004 D BtGatt.GattService: start()
,08-29 13:44:50.418  4004  4004 I bt_bluedroid: get_profile_interface gatt
,08-29 13:44:50.419  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:44:50.419  4004  4004 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:44:50.428  4004  4004 V BluetoothAdapterState: isTurningOff()=false
08-29 13:44:50.428  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:44:50.428  4004  4004 V BluetoothAdapterState: isBleTurningOn()=true
08-29 13:44:50.428  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:50.428  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 13:44:50.429  4004  4163 I bt_bluedroid: enable
,08-29 13:44:50.429  4004  4164 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 13:44:50.430  4004  4164 I bt_hci  : start_up
08-29 13:44:50.438  4004  4164 I bt_vendor: alloc value 0xb39f9189
08-29 13:44:50.438  4004  4164 I bt_vendor: init
08-29 13:44:50.438  4004  4164 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 13:44:50.438  4004  4164 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:44:50.544  4004  4164 D bt_hci  : start_up starting async portion
,08-29 13:44:50.545  4004  4171 I bt_hci  : event_finish_startup
,08-29 13:44:50.546  4004  4171 I bt_hci_h4: hal_open
,08-29 13:44:50.546  4004  4171 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:44:50.554  4004  4171 I bt_userial_vendor: device fd = 51 open
,08-29 13:44:50.587  4004  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:44:50.620  4004  4171 D bt_hwcfg: Chipset BCM4354A2
,08-29 13:44:50.620  4004  4171 D bt_hwcfg: Target name = [BCM4354A2]
08-29 13:44:50.621  4004  4171 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:44:51.298  4004  4171 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:44:51.299  4004  4171 D bt_hwcfg: Settlement delay -- 100 ms
08-29 13:44:51.300  4004  4171 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:44:51.416  4004  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:44:51.418  4004  4171 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:44:51.448  4004  4171 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:44:51.448  4004  4171 I bt_vendor: firmware callback
,08-29 13:44:51.448  4004  4171 I bt_hci  : firmware_config_callback
,08-29 13:44:51.461  4004  4173 I bt_btu  : btu_task pending for preload complete event
,08-29 13:44:51.462  4004  4173 I bt_btu_task: Bluetooth chip preload is complete
,08-29 13:44:51.462  4004  4173 I bt_btu  : btu_task received preload complete event
,08-29 13:44:51.472  4004  4173 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 13:44:51.472  4004  4173 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 13:44:51.472  4004  4173 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 13:44:51.473  4004  4173 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:44:51.473  4004  4173 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 13:44:51.473  4004  4173 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:44:51.474  4004  4173 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 13:44:51.474  4004  4173 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 13:44:51.474  4004  4173 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:44:51.474  4004  4173 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:44:51.475  4004  4173 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:44:51.475  4004  4173 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:44:51.475  4004  4173 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:44:51.475  4004  4173 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:44:51.476  4004  4173 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:44:51.614  4004  4173 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-29 13:44:51.614  4004  4173 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d ,
,08-29 13:44:51.629  4004  4167 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:44:51.631  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 13:44:51.631  4004  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:44:51.635  4004  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:44:51.639  4004  4167 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:51.641  4004  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:44:51.641  4004  4167 D bt_hci  : do_postload posting postload work item
,08-29 13:44:51.642  4004  4171 I bt_hci  : event_postload
,08-29 13:44:51.642  4004  4171 I bt_vendor: sco_config_cb
,08-29 13:44:51.642  4004  4171 I bt_hci  : sco_config_callback postload finished.
,08-29 13:44:51.643  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.647  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.647  4004  4167 D bt_bte_conf: Device ID record 1 : primary
,08-29 13:44:51.647  4004  4167 D bt_bte_conf:   vendorId            = 000f
,08-29 13:44:51.647  4004  4167 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 13:44:51.648  4004  4167 D bt_bte_conf:   product             = 1200
,08-29 13:44:51.648  4004  4167 D bt_bte_conf:   version             = 1436
08-29 13:44:51.648  4004  4167 D bt_bte_conf:   clientExecutableURL = 
,08-29 13:44:51.648  4004  4171 I bt_vendor: low_power_mode_cb
,08-29 13:44:51.648  4004  4167 D bt_bte_conf:   serviceDescription  = 
,08-29 13:44:51.648  4004  4167 D bt_bte_conf:   documentationURL    = 
,08-29 13:44:51.649  4004  4167 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:44:51.649  4004  4164 D bt_stack_manager: event_start_up_stack finished
,08-29 13:44:51.650  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 13:44:51.651  4004  4163 D BluetoothAdapterProperties: Setting state to 15
,08-29 13:44:51.651  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 13:44:51.652  4004  4163 I BluetoothAdapterState: Entering BleOnState
,08-29 13:44:51.657  4004  4163 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 13:44:51.657  4004  4163 D BluetoothAdapterProperties: Setting state to 11
,08-29 13:44:51.657  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 13:44:51.663  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:51.665  4004  4004 D HeadsetService: Received start request. Starting profile...
,08-29 13:44:51.672  4004  4004 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 13:44:51.672  4004  4004 D HeadsetStateMachine: make
,08-29 13:44:51.673  4004  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:44:51.678  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.680  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.684  4004  4004 D HeadsetStateMachine: max_hf_connections = 1
,08-29 13:44:51.684  4004  4004 I bt_bluedroid: get_profile_interface handsfree
08-29 13:44:51.684  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 13:44:51.685  4004  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 13:44:51.688  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:51.689  4004  4004 D A2dpService: Received start request. Starting profile...
,08-29 13:44:51.689  4004  4004 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:44:51.690  4004  4004 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:44:51.696  4004  4004 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:44:51.696  4004  4004 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:44:51.696  4004  4004 D A2dpStateMachine: make
,08-29 13:44:51.699  4004  4004 I bt_bluedroid: get_profile_interface a2dp
,08-29 13:44:51.699  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 13:44:51.700  4004  4182 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:44:51.701  4004  4004 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 13:44:51.702  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:44:51.703  4004  4004 D HidService: Received start request. Starting profile...
,08-29 13:44:51.703  4004  4004 I bt_bluedroid: get_profile_interface hidhost
08-29 13:44:51.703  4004  4004 D HidService: setHidService(): set to: null
08-29 13:44:51.703  4004  4167 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-29 13:44:51.704  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 13:44:51.704  4004  4004 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:44:51.704  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:44:51.705  4004  4004 D HealthService: Received start request. Starting profile...
,08-29 13:44:51.706  3926  3926 D BluetoothInputDevice: Proxy object connected
,08-29 13:44:51.708  4004  4004 I bt_bluedroid: get_profile_interface health
08-29 13:44:51.708  3926  3926 D HidProfile: Bluetooth service connected
,08-29 13:44:51.709  4004  4004 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:44:51.709  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:51.711  3926  3926 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:44:51.711  4004  4004 D PanService: Received start request. Starting profile...
08-29 13:44:51.712  4004  4004 D BluetoothPanServiceJni: initializeNative(L110): pan,
,08-29 13:44:51.712  4004  4004 I bt_bluedroid: get_profile_interface pan
,08-29 13:44:51.713  4004  4167 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:44:51.713  3926  3926 D PanProfile: Bluetooth service connected
,08-29 13:44:51.714  4004  4004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:44:51.715  3926  3926 D BluetoothMap: Proxy object connected
,08-29 13:44:51.715  4004  4004 D BluetoothMapService: Received start request. Starting profile...
,08-29 13:44:51.715  4004  4004 D BluetoothMapService: start()
,08-29 13:44:51.715  3926  3926 D MapProfile: Bluetooth service connected
,08-29 13:44:51.716  3926  3926 D BluetoothMap: getConnectedDevices()
08-29 13:44:51.718  3926  3926 D BluetoothMap: Bluetooth is Not enabled
,08-29 13:44:51.727  4004  4004 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 13:44:51.728  4004  4004 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 13:44:51.728  4004  4004 D BluetoothMapAppObserver: createReceiver()
,08-29 13:44:51.729  4004  4004 D BluetoothMapAppObserver: initObservers()
,08-29 13:44:51.729  4004  4004 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 13:44:51.736  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:44:51.736  4004  4004 V BluetoothAdapterState: isTurningOn()=true
08-29 13:44:51.736  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:44:51.736  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:44:51.738  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:51.738  4004  4004 V BluetoothAdapterState: isTurningOff()=false
08-29 13:44:51.738  4004  4179 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:44:51.738  4004  4004 V BluetoothAdapterState: isTurningOn()=true
08-29 13:44:51.739  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:44:51.739  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isTurningOn()=true
08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isTurningOn()=true
08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:44:51.740  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:51.741  4004  4004 V BluetoothAdapterState: isTurningOff()=false
08-29 13:44:51.741  4004  4004 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:44:51.741  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:51.741  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:51.741  4004  4004 V BluetoothAdapterState: isTurningOff()=false
08-29 13:44:51.742  4004  4004 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:44:51.742  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:44:51.742  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:51.743  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:44:51.743  4004  4163 D BluetoothAdapterProperties: ScanMode =  20
,08-29 13:44:51.743  4004  4163 D BluetoothAdapterProperties: State =  11
08-29 13:44:51.743  4004  4163 D BluetoothAdapterProperties: Setting state to 12
08-29 13:44:51.743  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:44:51.744  1359  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:44:51.745  4004  4163 I BluetoothAdapterState: Entering OnState
,08-29 13:44:51.746  4004  4167 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:44:51.747  4004  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:51.751  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:51.751  1359  1359 D BluetoothA2dp: Proxy object connected
,08-29 13:44:51.754  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:51.755  4004  4004 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:44:51.756   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:51.756  4004  4004 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 13:44:51.757  1359  1370 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:51.758  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:51.760  4004  4004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:51.762  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:44:51.762  1359  1359 D PanProfile: Bluetooth service connected
08-29 13:44:51.762  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:51.763  1359  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:44:51.764   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:44:51.767  1359  2075 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:44:51.767  4004  4004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:51.769  4004  4004 D ObexServerSockets: Succeed to create listening sockets 
08-29 13:44:51.769  4004  4004 D ObexServerSockets0: startAccept()
,08-29 13:44:51.769  4004  4004 D ObexServerSockets0: prepareForNewConnect()
08-29 13:44:51.771  4004  4004 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 13:44:51.771  3926  3936 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:44:51.771  1359  1370 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:44:51.772  4004  4004 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 13:44:51.773  4004  4189 D ObexServerSockets0: Accepting socket connection...
08-29 13:44:51.773  1359  1359 D BluetoothMap: Proxy object connected
08-29 13:44:51.773  1359  1359 D MapProfile: Bluetooth service connected
08-29 13:44:51.773  1359  1359 D BluetoothMap: getConnectedDevices()
08-29 13:44:51.774  4004  4188 D ObexServerSockets0: Accepting socket connection...
,08-29 13:44:51.775  3926  3937 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 13:44:51.776  1962  1982 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:44:51.777  3926  3936 D BluetoothPan: onBluetoothStateChange on: true
,08-29 13:44:51.777   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:44:51.778   871   871 D BluetoothA2dp: Proxy object connected
08-29 13:44:51.778   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:44:51.778  1359  2075 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 13:44:51.780  1359  1359 D BluetoothInputDevice: Proxy object connected
,08-29 13:44:51.780  1359  1359 D HidProfile: Bluetooth service connected
,08-29 13:44:51.780  3926  3937 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:44:51.782   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 13:44:51.782  4004  4004 D BluetoothMapService: onReceive
08-29 13:44:51.782  4004  4004 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:51.782  4004  4004 D BluetoothMapService: STATE_ON
08-29 13:44:51.784  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:51.785  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.786  3926  3926 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 13:44:51.789  3926  3926 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 13:44:51.794  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:51.796  3926  3926 D BluetoothA2dp: Proxy object connected
,08-29 13:44:51.800  3926  3926 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:51.801  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:51.808  3926  3926 D BluetoothPbap: Proxy object connected
,08-29 13:44:51.809  4004  4004 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:44:51.809  4004  4004 D ObexServerSockets0: prepareForNewConnect()
08-29 13:44:51.809  3926  3926 D PbapServerProfile: Bluetooth service connected
,08-29 13:44:51.812  1359  1359 D BluetoothPbap: Proxy object connected
,08-29 13:44:51.812  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-29 13:44:51.817   871   880 I art     : Background partial concurrent mark sweep GC freed 63438(3MB) AllocSpace objects, 14(408KB) LOS objects, 33% free, 29MB/43MB, paused 1.584ms total 101.035ms
,08-29 13:44:51.823  4004  4193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:51.829  4004  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:51.830  4004  4197 I BtOppRfcommListener: Accept thread started.
,08-29 13:44:51.858  1962  2105 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.858  1359  2075 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.858  1359  1359 D HeadsetProfile: Bluetooth service connected
08-29 13:44:51.858   871   871 D BluetoothHeadset: Proxy object connected
08-29 13:44:51.858   871   871 D BluetoothHeadset: Proxy object connected
08-29 13:44:51.858   871   871 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.864  1359  1376 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.864  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-29 13:44:51.866   871   888 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.876  1962  1987 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.878   871   888 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.892  3926  3936 D BluetoothHeadset: Proxy object connected
,08-29 13:44:51.892  3926  3926 D HeadsetProfile: Bluetooth service connected
,08-29 13:44:53.287   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-29 13:44:53.332  4004  4163 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 13:44:53.332  4004  4163 D BluetoothAdapterProperties: Setting state to 13
08-29 13:44:53.332  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:44:53.334  4004  4163 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:44:53.336  4004  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:44:53.339  4004  4167 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:53.344  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 13:44:53.344  4004  4004 D BluetoothMapService: onReceive
08-29 13:44:53.345  4004  4004 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:53.346  4004  4004 D BluetoothMapService: STATE_TURNING_OFF
,08-29 13:44:53.348  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:53.348  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:53.351  4004  4004 D BluetoothMapService: MAP Service closeService in
,08-29 13:44:53.351  4004  4004 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 13:44:53.351  4004  4004 D ObexServerSockets0: shutdown(block = true)
,08-29 13:44:53.352  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:53.352  4004  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 13:44:53.353  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:53.355  4004  4004 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:44:53.355  4004  4004 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 13:44:53.356  4004  4189 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 13:44:53.356  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:53.356  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:53.358  4004  4176 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 13:44:53.358  4004  4004 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:53.358  3856  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:53.358  4004  4197 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:44:53.358  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:53.358  4004  4197 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:44:53.360  4004  4004 D HeadsetService: Received stop request...Stopping profile...,
08-29 13:44:53.360  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:53.360  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:53.361  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:53.363  4004  4004 D A2dpService: Received stop request...Stopping profile...
,08-29 13:44:53.363  1962  2123 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:53.363  4004  4182 D A2dpStateMachine: Exit Disconnected: -1,
08-29 13:44:53.364  1359  1370 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:53.365   871   871 D BluetoothHeadset: Proxy object disconnected
,08-29 13:44:53.365   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:53.366  3926  3936 D BluetoothHeadset: Proxy object disconnected
,08-29 13:44:53.367   871   871 D BluetoothHeadset: Proxy object disconnected
08-29 13:44:53.367   871   871 D BluetoothA2dp: Proxy object disconnected
,08-29 13:44:53.371  4004  4004 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:53.371  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:44:53.371  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.371  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:53.372  4004  4004 D HidService: Received stop request...Stopping profile...
,08-29 13:44:53.372  4004  4004 D HidService: Stopping Bluetooth HidService
08-29 13:44:53.373  3926  3926 D DockEventReceiver: finishStartingService: stopping service
08-29 13:44:53.374  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,08-29 13:44:53.374  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-29 13:44:53.375  1359  1359 D BluetoothInputDevice: Proxy object disconnected
,08-29 13:44:53.375  1359  1359 D HidProfile: Bluetooth service disconnected
08-29 13:44:53.375  3926  3926 D HeadsetProfile: Bluetooth service disconnected
08-29 13:44:53.375  3926  3926 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:53.376  4004  4004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:53.376  4004  4004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:44:53.376  4004  4004 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:53.376  4004  4004 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:53.376  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.376  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:53.377  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:44:53.377  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:53.377  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:53.377  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:53.377  4004  4004 D HealthService: Received stop request...Stopping profile...
08-29 13:44:53.378  4004  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-29 13:44:53.378  3926  3926 D BluetoothInputDevice: Proxy object disconnected
08-29 13:44:53.378  3926  3926 D HidProfile: Bluetooth service disconnected
,08-29 13:44:53.384  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:53.385  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 13:44:53.385  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:53.385  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:44:53.385  4004  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:53.385  4004  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:53.385  4004  4173 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:53.385  4004  4173 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:53.385  4004  4004 D PanService: Received stop request...Stopping profile...
08-29 13:44:53.386  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:44:53.386  1359  1359 D PanProfile: Bluetooth service disconnected
08-29 13:44:53.387  4004  4004 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 13:44:53.387  4004  4004 D BluetoothMapService: stop()
08-29 13:44:53.387  3926  3926 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:44:53.387  4004  4004 D BluetoothMapAppObserver: deinitObservers()
,08-29 13:44:53.387  4004  4004 D BluetoothMapAppObserver: removeReceiver()
08-29 13:44:53.387  3926  3926 D PanProfile: Bluetooth service disconnected
,08-29 13:44:53.388  3926  3926 D BluetoothMap: Proxy object disconnected
,08-29 13:44:53.388  3926  3926 D MapProfile: Bluetooth service disconnected
,08-29 13:44:53.388  1359  1359 D BluetoothMap: Proxy object disconnected
,08-29 13:44:53.388  1359  1359 D MapProfile: Bluetooth service disconnected
08-29 13:44:53.388  4004  4004 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:44:53.389  4004  4004 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 13:44:53.389  4004  4004 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:53.389  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.389  4004  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:44:53.390  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:53.390  4004  4004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:44:53.390  4004  4167 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:44:53.390  4004  4004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:53.391  3926  3926 D BluetoothPbap: Proxy object disconnected
,08-29 13:44:53.391  3926  3926 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:44:53.392  1359  1359 D BluetoothPbap: Proxy object disconnected
08-29 13:44:53.392  1359  1359 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:44:53.392  4004  4004 V BluetoothAdapterState: isTurningOff()=true
,08-29 13:44:53.392  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:44:53.392  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.392  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:53.392  4004  4004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:53.392  4004  4004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:44:53.393  4004  4004 D BluetoothMapService: MAP Service closeService in
08-29 13:44:53.393  4004  4004 V BluetoothAdapterState: isTurningOff()=true
08-29 13:44:53.393  4004  4004 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:53.393  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:44:53.393  4004  4004 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:53.393  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 13:44:53.393  4004  4163 D BluetoothAdapterProperties: Setting state to 15
,08-29 13:44:53.394  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 13:44:53.394  4004  4163 I BluetoothAdapterState: Entering BleOnState
08-29 13:44:53.394  4004  4004 D BluetoothMapService: cleanup()
08-29 13:44:53.394  4004  4004 D BluetoothMapService: MAP Service closeService in
08-29 13:44:53.394  1359  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:53.395   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.395  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
,08-29 13:44:53.396  3926  4202 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.396  1359  2075 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.396   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.396  1359  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:44:53.397  3926  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:44:53.397  1359  1370 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:44:53.398  3926  3936 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:53.399  3926  4202 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:44:53.400  1962  1982 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.400  3926  3937 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:44:53.401   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:44:53.401   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:44:53.401  1359  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 13:44:53.402  3926  3936 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 13:44:53.402  4004  4163 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:44:53.402  4004  4163 D BluetoothAdapterProperties: Setting state to 16
08-29 13:44:53.402  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 13:44:53.403  4004  4163 D BluetoothAdapterProperties: onBleDisable
08-29 13:44:53.403  4004  4163 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:44:53.403  4004  4164 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 13:44:53.404  4004  4167 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:53.405  4004  4173 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:44:53.405  4004  4173 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:44:53.409  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:53.410  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:53.411  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:53.413  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:53.413  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:53.414  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:53.415  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:53.417  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:44:53.419  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:53.420  3926  3926 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:53.438  1503  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 13:44:53.438  1503  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:44:53.438  1503  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 13:44:53.438  1503  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:44:53.450  3559  3559 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 13:44:53.450  3559  3559 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 13:44:53.450  3559  3559 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 13:44:53.606  4004  4167 I bt_hci  : shut_down
08-29 13:44:53.606  4004  4171 D bt_hwcfg: hw_epilog_process
,08-29 13:44:53.608  4004  4171 I bt_vendor: low_power_mode_cb
,08-29 13:44:53.629  4004  4171 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 13:44:53.629  4004  4171 I bt_vendor: epilog_cb
08-29 13:44:53.629  4004  4171 I bt_hci  : epilog_finished_callback
,08-29 13:44:53.639  4004  4167 I bt_hci_h4: hal_close
,08-29 13:44:53.641  4004  4167 I bt_userial_vendor: device fd = 51 close
,08-29 13:44:53.760  4004  4164 D bt_stack_manager: event_shut_down_stack finished.
,08-29 13:44:53.761  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:44:53.767  4004  4004 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:44:53.768  4004  4163 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 13:44:53.769  4004  4004 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 13:44:53.769  4004  4004 D BtGatt.GattService: stop()
08-29 13:44:53.770  4004  4004 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:44:53.774  4004  4004 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:44:53.775  4004  4004 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:44:53.775  4004  4004 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:44:53.775  4004  4004 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 13:44:53.776  4004  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 13:44:53.777  4004  4163 D BluetoothAdapterProperties: Setting state to 10
,08-29 13:44:53.777  4004  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 13:44:53.779  4004  4163 I BluetoothAdapterState: Entering OffState
08-29 13:44:53.781   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 13:44:53.801  4004  4004 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 13:44:53.801  4004  4004 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 13:44:53.801  4004  4164 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 13:44:53.804  4004  4164 D bt_stack_manager: event_clean_up_stack finished.
08-29 13:44:53.804  4004  4004 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:44:53.807  4004  4004 I art     : System.exit called, status: 0
08-29 13:44:53.807  4004  4004 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:44:53.848   871  1682 I ActivityManager: Process com.android.bluetooth (pid 4004) has died
,08-29 13:44:55.017   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 13:44:55.037  1897  1897 I Keyboard.Facilitator: onFinishInput()
,08-29 13:44:55.046   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:44:55.046   871   891 I Adreno  : Build Date                       : 10/20/15
08-29 13:44:55.046   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:44:55.046   871   891 I Adreno  : Local Branch                     : M14
08-29 13:44:55.046   871   891 I Adreno  : Remote Branch                    : 
08-29 13:44:55.046   871   891 I Adreno  : Remote Branch                    : 
08-29 13:44:55.046   871   891 I Adreno  : Reconstruct Branch               : 
,08-29 13:44:55.082   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (320 us)
,08-29 13:44:55.738  3856  3856 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:44:55.738  3856  3856 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED,
,08-29 13:44:55.788  3856  3856 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@23199ea Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f531be4, 16908290=android.view.AbsSavedState$1@f531be4}, android:focusedViewId=100}]}]
,08-29 13:44:55.788   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
08-29 13:44:55.788  3856  3856 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-29 13:44:55.788  3856  3856 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:44:55.789  3856  3856 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 13:44:55.795   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 13:44:55.803   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 13:44:55.805   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-29 13:44:55.805   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 13:44:56.038   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 13:44:56.042   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 13:44:56.043   871  1339 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-29 13:44:56.048   871   891 I DreamManagerService: Entering dreamland.
,08-29 13:44:56.049   871   891 I PowerManagerService: Dozing...
,08-29 13:44:56.051   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 13:44:56.101   375  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 13:44:56.101   375  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 13:44:56.114   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:44:56.120   871  1312 E native  : do suspend false
,08-29 13:44:56.121  1947  4211 D NfcService: Discovery configuration equal, not updating.
,08-29 13:44:56.148   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:44:56.156   871  1312 E native  : do suspend true
,08-29 13:44:56.242   375  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 13:44:56.242   375  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 13:44:56.330  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:56.330  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:59.337  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:59.338  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3a884d added. We now have 6 listener(s)
,08-29 13:44:59.338  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:59.342  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:59.342  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a01af02 added. We now have 7 listener(s)
08-29 13:44:59.343  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:59.344  3856  3906 I System.out: IsBluetoothEnabled
,08-29 13:44:59.357  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:59.408   871   888 I ActivityManager: Start proc 4217:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 13:44:59.528  4217  4217 D AdapterServiceConfig: Adding HeadsetService
,08-29 13:44:59.529  4217  4217 D AdapterServiceConfig: Adding A2dpService
,08-29 13:44:59.529  4217  4217 D AdapterServiceConfig: Adding HidService
08-29 13:44:59.529  4217  4217 D AdapterServiceConfig: Adding HealthService
08-29 13:44:59.529  4217  4217 D AdapterServiceConfig: Adding PanService
08-29 13:44:59.529  4217  4217 D AdapterServiceConfig: Adding GattService
,08-29 13:44:59.530  4217  4217 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:44:59.546   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1b7eab:true
,08-29 13:44:59.546  4217  4217 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 13:44:59.550  4217  4217 I bt_bluedroid: init
,08-29 13:44:59.551  4217  4229 I BluetoothAdapterState: Entering OffState
,08-29 13:44:59.558  4217  4230 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 13:44:59.558  4217  4230 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 13:44:59.558  4217  4230 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 13:44:59.559  4217  4230 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 13:44:59.562  4217  4217 I bt_bluedroid: get_profile_interface socket
,08-29 13:44:59.564  4217  4217 I bt_bluedroid: get_profile_interface sdp
,08-29 13:44:59.567  4217  4233 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:44:59.568  4217  4228 I bt_bluedroid: config_hci_snoop_log
,08-29 13:44:59.571  4217  4233 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:44:59.571   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:44:59.580  4217  4229 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 13:44:59.580  4217  4229 D BluetoothAdapterProperties: Setting state to 14
08-29 13:44:59.580  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:44:59.582  4217  4229 D BluetoothBondStateMachine: make
,08-29 13:44:59.586  4217  4234 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:44:59.592  4217  4229 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:44:59.592  4217  4217 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 13:44:59.596  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:59.597  4217  4217 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:44:59.598  4217  4217 D BtGatt.GattService: Received start request. Starting profile...
,08-29 13:44:59.598  4217  4217 D BtGatt.GattService: start()
,08-29 13:44:59.598  4217  4217 I bt_bluedroid: get_profile_interface gatt
08-29 13:44:59.599  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:44:59.599  4217  4217 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:44:59.610  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:44:59.610  4217  4217 V BluetoothAdapterState: isTurningOn()=false
08-29 13:44:59.610  4217  4217 V BluetoothAdapterState: isBleTurningOn()=true
08-29 13:44:59.610  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:44:59.611  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 13:44:59.611  4217  4229 I bt_bluedroid: enable
,08-29 13:44:59.611  4217  4230 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 13:44:59.613  4217  4230 I bt_hci  : start_up
,08-29 13:44:59.630  4217  4230 I bt_vendor: alloc value 0xb3a4d189
,08-29 13:44:59.630  4217  4230 I bt_vendor: init
08-29 13:44:59.631  4217  4230 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 13:44:59.631  4217  4230 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:44:59.739  4217  4230 D bt_hci  : start_up starting async portion
,08-29 13:44:59.740  4217  4237 I bt_hci  : event_finish_startup
,08-29 13:44:59.740  4217  4237 I bt_hci_h4: hal_open
08-29 13:44:59.741  4217  4237 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:44:59.751  4217  4237 I bt_userial_vendor: device fd = 51 open
,08-29 13:44:59.781  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:44:59.813  4217  4237 D bt_hwcfg: Chipset BCM4354A2
,08-29 13:44:59.813  4217  4237 D bt_hwcfg: Target name = [BCM4354A2]
08-29 13:44:59.814  4217  4237 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:45:00.478  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:45:00.480  4217  4237 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 13:45:00.480  4217  4237 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:45:00.597  4217  4237 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:45:00.599  4217  4237 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:45:00.627  4217  4237 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:45:00.628  4217  4237 I bt_vendor: firmware callback
08-29 13:45:00.628  4217  4237 I bt_hci  : firmware_config_callback
,08-29 13:45:00.642  4217  4240 I bt_btu  : btu_task pending for preload complete event
,08-29 13:45:00.642  4217  4240 I bt_btu_task: Bluetooth chip preload is complete
,08-29 13:45:00.642  4217  4240 I bt_btu  : btu_task received preload complete event
,08-29 13:45:00.652  4217  4240 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:45:00.652  4217  4240 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 13:45:00.653  4217  4240 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 13:45:00.653  4217  4240 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:45:00.653  4217  4240 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 13:45:00.653  4217  4240 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 13:45:00.654  4217  4240 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 13:45:00.654  4217  4240 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:45:00.655  4217  4240 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:45:00.655  4217  4240 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 13:45:00.656  4217  4240 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:45:00.657  4217  4240 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:45:00.657  4217  4240 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:45:00.657  4217  4240 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 13:45:00.658  4217  4240 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:45:00.793  4217  4240 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39cad9d
,08-29 13:45:00.793  4217  4240 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39cad9d 
,08-29 13:45:00.803  4217  4233 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:45:00.804  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:45:00.805  4217  4233 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:45:00.808  4217  4233 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:45:00.812  4217  4233 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:45:00.813  4217  4233 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:45:00.814  4217  4233 D bt_hci  : do_postload posting postload work item
,08-29 13:45:00.815  4217  4237 I bt_hci  : event_postload
,08-29 13:45:00.815  4217  4237 I bt_vendor: sco_config_cb
08-29 13:45:00.815  4217  4237 I bt_hci  : sco_config_callback postload finished.
,08-29 13:45:00.819  4217  4233 D bt_bte_conf: Device ID record 1 : primary
08-29 13:45:00.819  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:00.819  4217  4233 D bt_bte_conf:   vendorId            = 000f
08-29 13:45:00.819  4217  4233 D bt_bte_conf:   vendorIdSource      = 0001
08-29 13:45:00.819  4217  4233 D bt_bte_conf:   product             = 1200
08-29 13:45:00.820  4217  4233 D bt_bte_conf:   version             = 1436
08-29 13:45:00.820  4217  4233 D bt_bte_conf:   clientExecutableURL = 
08-29 13:45:00.820  4217  4233 D bt_bte_conf:   serviceDescription  = 
08-29 13:45:00.820  4217  4233 D bt_bte_conf:   documentationURL    = 
,08-29 13:45:00.821  4217  4233 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 13:45:00.821  4217  4230 D bt_stack_manager: event_start_up_stack finished
08-29 13:45:00.822  4217  4237 I bt_vendor: low_power_mode_cb
,08-29 13:45:00.823  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 13:45:00.825  4217  4229 D BluetoothAdapterProperties: Setting state to 15
08-29 13:45:00.825  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 13:45:00.828  4217  4229 I BluetoothAdapterState: Entering BleOnState
,08-29 13:45:00.833  4217  4229 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 13:45:00.833  4217  4229 D BluetoothAdapterProperties: Setting state to 11
08-29 13:45:00.834  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 13:45:00.846  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:45:00.849  4217  4217 D HeadsetService: Received start request. Starting profile...
08-29 13:45:00.852  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:00.856  4217  4217 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 13:45:00.856  4217  4217 D HeadsetStateMachine: make
,08-29 13:45:00.859  4217  4229 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:45:00.863  4217  4217 D HeadsetStateMachine: max_hf_connections = 1
,08-29 13:45:00.864  4217  4217 I bt_bluedroid: get_profile_interface handsfree
08-29 13:45:00.864  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 13:45:00.864  4217  4233 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 13:45:00.869  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:45:00.870  4217  4217 D A2dpService: Received start request. Starting profile...
,08-29 13:45:00.871  4217  4217 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 13:45:00.871  4217  4217 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:45:00.876  4217  4217 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:45:00.876  4217  4217 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:45:00.877  4217  4217 D A2dpStateMachine: make
,08-29 13:45:00.878  4217  4217 I bt_bluedroid: get_profile_interface a2dp
08-29 13:45:00.878  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 13:45:00.880  4217  4249 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:45:00.881  4217  4217 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:45:00.882  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:45:00.882  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde,
08-29 13:45:00.883  4217  4217 D HidService: Received start request. Starting profile...
08-29 13:45:00.883  4217  4217 I bt_bluedroid: get_profile_interface hidhost
08-29 13:45:00.883  4217  4217 D HidService: setHidService(): set to: null
08-29 13:45:00.883  4217  4217 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 13:45:00.884  4217  4233 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ac3e5
08-29 13:45:00.884  4217  4233 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 13:45:00.884  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:45:00.885  4217  4217 D HealthService: Received start request. Starting profile...
,08-29 13:45:00.886  4217  4217 I bt_bluedroid: get_profile_interface health
,08-29 13:45:00.886  4217  4217 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:45:00.887  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
08-29 13:45:00.887  4217  4217 D PanService: Received start request. Starting profile...
,08-29 13:45:00.888  4217  4217 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 13:45:00.888  4217  4217 I bt_bluedroid: get_profile_interface pan
08-29 13:45:00.888  4217  4233 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:45:00.890  4217  4217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:45:00.891  4217  4217 D BluetoothMapService: Received start request. Starting profile...
,08-29 13:45:00.891  4217  4217 D BluetoothMapService: start()
,08-29 13:45:00.893  4217  4217 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 13:45:00.894  4217  4217 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 13:45:00.894  4217  4217 D BluetoothMapAppObserver: createReceiver()
,08-29 13:45:00.895  4217  4217 D BluetoothMapAppObserver: initObservers()
08-29 13:45:00.895  4217  4217 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 13:45:00.902  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:45:00.902  4217  4217 V BluetoothAdapterState: isTurningOn()=true
08-29 13:45:00.902  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:45:00.902  4217  4247 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:45:00.902  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:45:00.903  4217  4217 V BluetoothAdapterState: isTurningOff()=false
08-29 13:45:00.903  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:45:00.903  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isTurningOff()=false
08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:45:00.904  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isTurningOn()=true
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isTurningOff()=false
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isTurningOn()=true
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:45:00.905  4217  4217 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:45:00.906  4217  4229 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:45:00.906  4217  4229 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:45:00.906  4217  4229 D BluetoothAdapterProperties: State =  11
08-29 13:45:00.907  4217  4233 D BluetoothAdapterProperties: Scan Mode:21
,08-29 13:45:00.907  4217  4233 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:45:00.908  4217  4229 D BluetoothAdapterProperties: Setting state to 12
,08-29 13:45:00.908  4217  4229 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:45:00.909  4217  4229 I BluetoothAdapterState: Entering OnState
08-29 13:45:00.909  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:45:00.910   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:45:00.911  1359  4209 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:00.911  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:45:00.912  3926  3936 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:45:00.913  1359  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:45:00.913  1359  1359 D BluetoothA2dp: Proxy object connected
,08-29 13:45:00.913  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:00.913   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:00.914  1359  2075 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 13:45:00.914  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:45:00.915  1359  1359 D PanProfile: Bluetooth service connected
08-29 13:45:00.916  3926  4202 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:45:00.917  1359  1376 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:45:00.919  3926  3936 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:45:00.919  1359  1359 D BluetoothMap: Proxy object connected
,08-29 13:45:00.919  1359  1359 D MapProfile: Bluetooth service connected
08-29 13:45:00.919  1359  1359 D BluetoothMap: getConnectedDevices()
08-29 13:45:00.920  3926  3926 D BluetoothInputDevice: Proxy object connected
08-29 13:45:00.920  3926  3926 D HidProfile: Bluetooth service connected
,08-29 13:45:00.920  4217  4217 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:45:00.921  4217  4217 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 13:45:00.921  3926  3937 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 13:45:00.922  4217  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:45:00.923  1962  2123 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:00.923  3926  4202 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:45:00.924  4217  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:45:00.925  4217  4217 D ObexServerSockets: Succeed to create listening sockets 
08-29 13:45:00.925   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:45:00.925  4217  4217 D ObexServerSockets0: startAccept()
,08-29 13:45:00.925  4217  4217 D ObexServerSockets0: prepareForNewConnect()
,08-29 13:45:00.925   871   871 D BluetoothA2dp: Proxy object connected
08-29 13:45:00.926   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:45:00.926  1359  4209 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:45:00.927  4217  4217 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 13:45:00.927  1359  1359 D BluetoothInputDevice: Proxy object connected
08-29 13:45:00.927  4217  4217 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 13:45:00.927  1359  1359 D HidProfile: Bluetooth service connected
,08-29 13:45:00.928  3926  3937 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:45:00.928  4217  4255 D ObexServerSockets0: Accepting socket connection...
08-29 13:45:00.928  4217  4256 D ObexServerSockets0: Accepting socket connection...
,08-29 13:45:00.931   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 13:45:00.932  4217  4217 D BluetoothMapService: onReceive
08-29 13:45:00.932  4217  4217 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:45:00.932  4217  4217 D BluetoothMapService: STATE_ON
,08-29 13:45:00.933  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:00.934  3926  3926 D BluetoothA2dp: Proxy object connected
,08-29 13:45:00.935  3926  3926 D BluetoothPan: BluetoothPAN Proxy object connected,
08-29 13:45:00.936  3926  3926 D PanProfile: Bluetooth service connected
08-29 13:45:00.936  3926  3926 D BluetoothMap: Proxy object connected
,08-29 13:45:00.936  3926  3926 D MapProfile: Bluetooth service connected
08-29 13:45:00.936  3926  3926 D BluetoothMap: getConnectedDevices()
,08-29 13:45:00.940  3926  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:45:00.946  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:45:00.946  3926  3926 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:45:00.953  3926  3926 D BluetoothPbap: Proxy object connected
,08-29 13:45:00.953  3926  3926 D PbapServerProfile: Bluetooth service connected
,08-29 13:45:00.955  1359  1359 D BluetoothPbap: Proxy object connected
08-29 13:45:00.956  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-29 13:45:00.959  4217  4217 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 13:45:00.959  4217  4217 D ObexServerSockets0: prepareForNewConnect()
,08-29 13:45:00.963  4217  4261 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:45:00.976  4217  4265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:45:00.979  4217  4265 I BtOppRfcommListener: Accept thread started.
,08-29 13:45:01.012  1962  1982 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.012  1359  4209 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.012  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-29 13:45:01.012   871   871 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.012   871   871 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.013  3926  3937 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.013  3926  3936 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.013   871   871 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.013  1359  1376 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.013   871   888 D BluetoothHeadset: Proxy object connected
08-29 13:45:01.014  3926  3926 D HeadsetProfile: Bluetooth service connected
,08-29 13:45:01.016  1359  1359 D HeadsetProfile: Bluetooth service connected
08-29 13:45:01.016  3926  3926 D HeadsetProfile: Bluetooth service connected
,08-29 13:45:01.024  1962  2105 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.026   871   888 D BluetoothHeadset: Proxy object connected
,08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:01.380  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.387  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:01.390  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:01.391  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3965013 added. We now have 8 listener(s)
08-29 13:45:01.391  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:01.397   871  1395 D WifiService: setWifiEnabled: false pid=3856, uid=10000
,08-29 13:45:01.397   871  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:45:01.410  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.412   871  1402 D WifiService: setWifiEnabled: true pid=3856, uid=10000
08-29 13:45:01.412   871  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:45:01.428   871  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:01.444  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.450  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:01.456   871  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:45:01.457   871  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 13:45:01.458   871  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 13:45:01.459   871  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:45:01.459   871  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 13:45:01.459   871  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 13:45:01.459   871  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 13:45:01.481   871  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.05 delta 1000 -> 1000
,08-29 13:45:01.480   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 13:45:01.481   871  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 13:45:01.482   371   869 D CommandListener: Setting iface cfg
,08-29 13:45:01.491   871  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-29 13:45:01.491   871  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:45:01.492   871  1312 E native  : do suspend true
,08-29 13:45:01.503   871  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 13:45:01.504   871  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:45:01.533   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 13:45:01.533   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:45:01.543   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:45:01.590   871  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:45:01.596  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:45:02.025  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:45:02.061  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:45:02.062  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:45:02.068   871  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:45:02.087   871  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:45:02.088   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:45:02.088   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:45:02.119   871  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:45:02.133   371   869 D CommandListener: Setting iface cfg
,08-29 13:45:02.133   871  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 13:45:02.148   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:45:02.164   871  4275 D DhcpClient: Receive thread started
,08-29 13:45:02.253   871  1312 E native  : do suspend false
,08-29 13:45:02.272   871  2132 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 13:45:02.293   871  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-29 13:45:02.294   871  2132 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
08-29 13:45:02.298   871  2132 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:45:02.316   871  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 13:45:02.318   871  2132 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:45:02.322   371   869 D CommandListener: Setting iface cfg
,08-29 13:45:02.333   871  2132 D DhcpClient: Scheduling renewal in 86399s
,08-29 13:45:02.337   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 13:45:02.341   871  1312 E native  : do suspend true
,08-29 13:45:02.363   871  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 13:45:02.367   871  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 13:45:02.369   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 13:45:02.371   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 13:45:02.383   871  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:02.425  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:02.427  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:02.431  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 13:45:02.432  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:45:02.434  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@23199ea Bundle[{}]
,08-29 13:45:02.436  3856  3906 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:45:02.437  3856  3906 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 13:45:02.438  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:45:02.439  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 13:45:02.439  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 13:45:02.440  3856  3906 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:45:02.445  3856  3906 I System.out: Running OutgoingSocketThread
,08-29 13:45:02.446  3856  4278 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 435)
,08-29 13:45:02.447  3856  4278 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38145
,08-29 13:45:02.447  3856  4278 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:45:02.467   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 13:45:02.467   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 13:45:02.469   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 13:45:02.471   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 13:45:02.472   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 13:45:02.480   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 13:45:02.484   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 13:45:02.485   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 13:45:02.485   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 13:45:02.485   871  1315 D ConnectivityService:    accepting network in place of null
08-29 13:45:02.485   871  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 13:45:02.486   871  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:45:02.486   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:45:02.527   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:45:02.575   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:45:02.584   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-29 13:45:02.586   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:45:02.593   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 13:45:02.597   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:02.614  3856  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:02.620  3856  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:45:02.629  1684  1684 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:45:02.633  1684  1684 D SystemUpdateService: onCreate
,08-29 13:45:02.637  1684  1684 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:45:02.658  1684  4285 I SystemUpdateService: active receiver: enabled
,08-29 13:45:02.664  1684  1684 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:45:02.674  1684  4285 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:45:02.675  1684  2595 I iu.UploadsManager: num queued entries: 0
,08-29 13:45:02.675  1684  2595 I iu.UploadsManager: num updated entries: 0
,08-29 13:45:02.679  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:45:02.679  1684  4285 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 13:45:02.680  1684  4285 I SystemUpdateService: now status is 0 (complete)
,08-29 13:45:02.680  1684  4285 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:45:02.680  1684  4285 I SystemUpdateService: file has been verified
,08-29 13:45:02.681  1684  1684 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:45:02.680  1684  4285 I SystemUpdateService: OTA package size = 12249756
,08-29 13:45:02.683  4018  4018 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:45:02.689  1684  4288 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 13:45:02.689  1684  4288 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 13:45:02.690  1684  4288 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 13:45:02.695  4018  4018 D SprintDMHelper: simOperator: 
,08-29 13:45:02.695  4018  4018 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:45:02.697  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:45:02.699  1684  2595 I iu.SyncManager: NEXT; no task
,08-29 13:45:02.705  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:45:02.715  1684  4285 I SystemUpdateService: showing system update notification
,08-29 13:45:02.768  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:45:02.768  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-29 13:45:02.768  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:45:02.768  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:45:02.771  1684  1684 D SystemUpdateService: onDestroy
,08-29 13:45:02.806  1684  4288 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-29 13:45:03.448  3856  3906 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 436)
,08-29 13:45:03.449  3856  3906 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 436)
,08-29 13:45:03.460  3856  3906 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-29 13:45:03.464  3856  3906 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 13:45:03.465  3856  3906 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-29 13:45:03.468  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:45:03.468  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5181250 added. We now have 2 listener(s)
,08-29 13:45:03.470  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:45:03.471  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:03.471  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.471  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:03.471  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab45c49 added. We now have 9 listener(s)
08-29 13:45:03.471  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:03.472  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:03.479  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:03.489  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:03.493  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:45:03.493  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:03.493  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:45:03.493  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8bda6f added. We now have 3 listener(s)
,08-29 13:45:03.495  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.495  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:03.496  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:03.496  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:03.496  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4037c added. We now have 10 listener(s)
08-29 13:45:03.496  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.496  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:03.496  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:03.497  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:03.497  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.497  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.498  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:03.498  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.498  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5181250 removed from the list
08-29 13:45:03.498  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.498  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab45c49 removed from the list
08-29 13:45:03.499  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.499  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:03.500  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.500  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.500  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.502  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.502  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.502  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:03.502  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ab45c49 not in the list
08-29 13:45:03.502  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.502  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.504  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.504  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.504  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:03.504  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bf4037c removed from the list
08-29 13:45:03.504  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.504  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.504  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.504  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.504  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8bda6f removed from the list
08-29 13:45:03.505  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.505  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd7405 added. We now have 2 listener(s)
08-29 13:45:03.507  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.507  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.507  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:03.507  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:03.507  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.508  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1821c5a added. We now have 9 listener(s)
08-29 13:45:03.508  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.509  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:03.515  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:03.524  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:03.528  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:45:03.529  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:03.529  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:45:03.529  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3bdb68 added. We now have 3 listener(s)
08-29 13:45:03.531  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:03.535  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.535  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.535  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:03.536  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.536  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:03.536  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc64b81 added. We now have 10 listener(s)
08-29 13:45:03.537  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.537  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:03.538  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 13:45:03.538  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:03.538  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:03.538  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:45:03.545  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:45:03.546  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:45:03.555  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:45:03.558  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:45:03.558  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:45:03.563  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:45:03.564  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:03.564  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:45:03.565  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:45:03.571  4217  4254 D BtGatt.GattService: registerClient() - UUID=1802ca14-1327-4505-b6e4-38a0152fd5e0
,08-29 13:45:03.573  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=1802ca14-1327-4505-b6e4-38a0152fd5e0, clientIf=5
08-29 13:45:03.573  3856  3868 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:45:03.576  4217  4257 D BtGatt.GattService: start scan with filters
,08-29 13:45:03.583  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:45:03.583  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:45:03.584   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-29 13:45:03.583  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:03.584  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:45:03.583  4217  4236 D BtGatt.ScanManager: handling starting scan
,08-29 13:45:03.588  4217  4236 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22f7dde
,08-29 13:45:03.593  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.593  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.594  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:45:03.597  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:45:03.597  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:03.598  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:45:03.599  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:45:03.606  3856  3906 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:45:03.607  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:45:03.607  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:45:03.608  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.608  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:45:03.608  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:45:03.608  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:45:03.608  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:03.608  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:45:03.609  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:45:03.609  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:45:03.610  3856  3906 D BluetoothAdapter: STATE_ON
08-29 13:45:03.611  4217  4254 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:45:03.612  4217  4246 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:45:03.613  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:45:03.613  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 13:45:03.613  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:45:03.614  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 13:45:03.614  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:45:03.615  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:45:03.615  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.615  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:45:03.616  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:45:03.616  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:03.617  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:45:03.617  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:45:03.617  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:03.618  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:45:03.620  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:45:03.620  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:45:03.621  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:45:03.625  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:45:03.625  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:45:03.625  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:45:03.626  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.626  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.626  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:03.626  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:45:03.626  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd7405 removed from the list
08-29 13:45:03.627  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:03.627  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1821c5a removed from the list
08-29 13:45:03.627  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:45:03.627  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.628  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.628  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.629  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:03.630  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.630  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.630  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1821c5a not in the list,
08-29 13:45:03.630  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.630  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 13:45:03.632  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:03.632  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:03.632  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.632  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc64b81 removed from the list
,08-29 13:45:03.632  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:45:03.632  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.632  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:03.632  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-29 13:45:03.633  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3bdb68 removed from the list
08-29 13:45:03.634  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.634  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b1ebd added. We now have 2 listener(s)
,08-29 13:45:03.637  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.637  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:03.637  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.637  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:03.638  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@547dcb2 added. We now have 9 listener(s)
,08-29 13:45:03.638  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.638  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:45:03.643  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:45:03.643  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.643  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:03.651  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:03.654  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:45:03.655  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:03.655  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.655  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bcaf80 added. We now have 3 listener(s)
08-29 13:45:03.655  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 13:45:03.657  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:03.659  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:45:03.660  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.660  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:03.660  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:03.661  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.661  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcfe9b9 added. We now have 10 listener(s)
08-29 13:45:03.661  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.661  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:45:03.662  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:45:03.662  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:03.662  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:03.662  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:03.662  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:45:03.666  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:45:03.666  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:45:03.666  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:03.672  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:45:03.672  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:45:03.672  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:45:03.675  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:45:03.675  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 13:45:03.675  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:45:03.677  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:45:03.677  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:03.677  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:45:03.678  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:45:03.680  4217  4227 D BtGatt.GattService: registerClient() - UUID=fabaf3eb-a6c7-43a3-839c-974bb8eea7d4
,08-29 13:45:03.681  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=fabaf3eb-a6c7-43a3-839c-974bb8eea7d4, clientIf=5
,08-29 13:45:03.682  3856  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:45:03.682  4217  4257 D BtGatt.GattService: start scan with filters
,08-29 13:45:03.683  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 13:45:03.683  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.683  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:45:03.685  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:45:03.685  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:45:03.685  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:03.685  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:45:03.688  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.688  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:45:03.688  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.690  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:45:03.692  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:45:03.692  3856  3906 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 13:45:03.692  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:03.692  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:45:03.692  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:03.692  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.692  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.692  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:45:03.693  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:45:03.693  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b1ebd removed from the list
08-29 13:45:03.693  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.693  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@547dcb2 removed from the list
08-29 13:45:03.693  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:03.693  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:45:03.694  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.695  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:45:03.695  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.695  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:45:03.696  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:03.696  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.697  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.697  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@547dcb2 not in the list
08-29 13:45:03.697  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:45:03.697  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:03.697  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:45:03.697  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:45:03.697  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:45:03.698  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:45:03.699  4217  4257 D BtGatt.GattService: stopScan() - queue size =0
,08-29 13:45:03.699  4217  4228 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:45:03.699  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:03.699  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:45:03.700  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:45:03.700  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:45:03.700  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:45:03.701  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:45:03.701  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:45:03.701  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:45:03.701  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:03.701  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-29 13:45:03.701  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.702  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.702  4217  4233 D BtGatt.GattService: current time is 158748111760
08-29 13:45:03.702  4217  4233 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 13:45:03.703  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:03.703  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:03.703  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:03.703  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.703  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.703  4217  4233 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 13:45:03.703  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.703  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcfe9b9 removed from the list
08-29 13:45:03.703  4217  4236 D BtGatt.ScanManager: handling starting scan
08-29 13:45:03.703  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:45:03.703  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.703  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.703  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.704  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bcaf80 removed from the list
08-29 13:45:03.704  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.704  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7c6875 added. We now have 2 listener(s)
08-29 13:45:03.706  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.706  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:03.706  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.706  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.706  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a500a added. We now have 9 listener(s)
08-29 13:45:03.706  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.707  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:03.710  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:45:03.710  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.710  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:45:03.710  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.720  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:45:03.720  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.721  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:45:03.721  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:03.721  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:03.724  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.724  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:03.724  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.724  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d0ee98 added. We now have 3 listener(s)
08-29 13:45:03.725  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:45:03.726  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:03.726  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.726  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.726  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3816f1 added. We now have 10 listener(s)
08-29 13:45:03.726  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:03.726  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:03.726  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:03.726  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:03.726  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.726  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:45:03.726  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.729  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.730  3856  3906 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:45:03.730  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:45:03.734  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:45:03.734  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:03.736  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:45:03.736  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 13:45:03.736  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:45:03.739  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:45:03.739  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:03.739  3856  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:45:03.740  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:45:03.742  4217  4257 D BtGatt.GattService: registerClient() - UUID=6be19610-dedf-4671-9958-bb7a36dcfbe7
,08-29 13:45:03.742  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:45:03.742  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.742  4217  4233 D BtGatt.GattService: onClientRegistered() - UUID=6be19610-dedf-4671-9958-bb7a36dcfbe7, clientIf=5
08-29 13:45:03.742  3856  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:45:03.742  4217  4246 D BtGatt.GattService: start scan with filters
,08-29 13:45:03.744  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:45:03.745  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:45:03.745  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:03.745  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:45:03.748  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.748  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:45:03.748  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:03.750  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:45:03.758  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:45:03.758  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:03.758  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.758  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:45:03.758  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:03.759  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:03.759  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.759  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.759  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:45:03.759  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.759  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7c6875 removed from the list
,08-29 13:45:03.759  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:03.760  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a500a removed from the list
08-29 13:45:03.760  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:03.760  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-29 13:45:03.761  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.761  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 13:45:03.761  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.761  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.762  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84a500a not in the list
08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:45:03.762  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:03.762  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:45:03.762  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:45:03.763  3856  3906 D BluetoothAdapter: STATE_ON
,08-29 13:45:03.763  4217  4254 D BtGatt.GattService: stopScan() - queue size =0
08-29 13:45:03.764  4217  4257 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:45:03.766  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:03.766  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 13:45:03.766  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:45:03.766  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:45:03.767  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:45:03.768  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:45:03.768  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:45:03.768  3856  3906 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:45:03.768  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:45:03.768  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:03.768  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-29 13:45:03.768  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:45:03.768  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.769  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:03.769  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.769  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.769  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:03.769  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3816f1 removed from the list
08-29 13:45:03.769  3856  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:03.769  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.769  3856  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:03.770  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.770  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.770  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.770  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d0ee98 removed from the list
,08-29 13:45:03.770  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:03.770  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26312d added. We now have 2 listener(s)
,08-29 13:45:03.772  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:45:03.772  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:03.772  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:03.772  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.772  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90cd662 added. We now have 9 listener(s)
08-29 13:45:03.772  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:03.773  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:03.774  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:03.777  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:45:03.777  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:45:03.778  3856  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:45:03.779  4217  4236 D BtGatt.ScanManager: handling starting scan
,08-29 13:45:03.780  3856  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:45:03.780  3856  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:03.781  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:45:03.781  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11af8b0 added. We now have 3 listener(s)
,08-29 13:45:03.782  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:45:03.783  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:45:03.783  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:03.783  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:03.783  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:03.783  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@861b329 added. We now have 10 listener(s)
08-29 13:45:03.783  3856  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:03.783  3856  3906 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:03.783  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:03.783  3856  3906 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:45:03.783  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.784  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.784  3856  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:03.784  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:03.784  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.784  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26312d removed from the list
08-29 13:45:03.784  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:03.784  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90cd662 removed from the list
08-29 13:45:03.784  3856  3906 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:03.784  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.785  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:03.785  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:03.786  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.786  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:03.786  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.786  3856  3906 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90cd662 not in the list
,08-29 13:45:03.786  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.786  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.787  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:03.787  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:03.787  3856  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:03.787  3856  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@861b329 removed from the list
08-29 13:45:03.787  3856  3906 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:03.787  3856  3906 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:03.787  3856  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:03.787  3856  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:03.787  3856  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11af8b0 removed from the list
,08-29 13:45:03.788  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 13:45:03.788  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:45:03.789  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 13:45:03.789  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:03.789  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:45:03.789  3856  3906 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:03.791  4217  4233 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:45:03.792  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.792  4217  4236 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:45:03.798  3856  4294 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: My test thread name)
,08-29 13:45:03.798  3856  4294 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 449, thread name: My test thread name)
08-29 13:45:03.798  3856  4294 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 449, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:45:03.800  3856  4295 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,08-29 13:45:03.800  3856  4295 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 451, thread name: My test thread name)
08-29 13:45:03.800  3856  4295 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 13:45:03.801  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:45:03.801  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.801  4217  4236 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:45:03.801  4217  4236 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 13:45:03.803  3856  3906 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-29 13:45:03.804  3856  3906 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:45:03.804  3856  3906 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:45:03.804  3856  3906 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-29 13:45:03.804  3856  3906 D com.test.thalitest.ThaliTestRunner: Total duration: 22817 ms
,08-29 13:45:03.807  3856  3906 I jxcore-log: *Native tests were executed*
08-29 13:45:03.807  3856  3906 I jxcore-log: 
,08-29 13:45:03.807  3856  3906 I jxcore-log: Total number of executed tests:  80
08-29 13:45:03.807  3856  3906 I jxcore-log: 
,08-29 13:45:03.808  3856  3906 I jxcore-log: Number of passed tests:  80
08-29 13:45:03.808  3856  3906 I jxcore-log: 
08-29 13:45:03.808  3856  3906 I jxcore-log: Number of failed tests:  0
08-29 13:45:03.808  3856  3906 I jxcore-log: 
,08-29 13:45:03.808  3856  3906 I jxcore-log: Number of ignored tests:  0
08-29 13:45:03.808  3856  3906 I jxcore-log: 
08-29 13:45:03.809  3856  3906 I jxcore-log: Total duration:  22817
08-29 13:45:03.809  3856  3906 I jxcore-log: 
,08-29 13:45:03.810  3856  3906 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:45:03.810  3856  3906 I jxcore-log: 
,08-29 13:45:03.815  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.815  3856  3906 I jxcore-log: 
08-29 13:45:03.817  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.817  3856  3906 I jxcore-log: 
08-29 13:45:03.818  4217  4233 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:45:03.818  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.819  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.819  3856  3906 I jxcore-log: 
08-29 13:45:03.820  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.820  3856  3906 I jxcore-log: 
08-29 13:45:03.820  3856  3856 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 13:45:03.820  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.820  3856  3906 I jxcore-log: 
08-29 13:45:03.822  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.822  3856  3906 I jxcore-log: 
08-29 13:45:03.823  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.823  3856  3906 I jxcore-log: 
08-29 13:45:03.825  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.825  3856  3906 I jxcore-log: 
08-29 13:45:03.825  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.825  3856  3906 I jxcore-log: 
08-29 13:45:03.826  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:03.826  3856  3906 I jxcore-log: 
08-29 13:45:03.827  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:03.827  3856  3906 I jxcore-log: 
,08-29 13:45:03.828  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:03.828  3856  3906 I jxcore-log: 
,08-29 13:45:03.828  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.828  3856  3906 I jxcore-log: 
08-29 13:45:03.829  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.829  3856  3906 I jxcore-log: 
08-29 13:45:03.830  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.830  3856  3906 I jxcore-log: 
08-29 13:45:03.830  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.830  3856  3906 I jxcore-log: 
,08-29 13:45:03.831  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.831  3856  3906 I jxcore-log: 
,08-29 13:45:03.832  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:45:03.832  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.832  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.832  3856  3906 I jxcore-log: 
08-29 13:45:03.833  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.833  3856  3906 I jxcore-log: 
,08-29 13:45:03.833  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.833  3856  3906 I jxcore-log: 
08-29 13:45:03.834  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-29 13:45:03.834  3856  3906 I jxcore-log: 
08-29 13:45:03.835  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:03.835  3856  3906 I jxcore-log: 
08-29 13:45:03.835  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:03.835  3856  3906 I jxcore-log: 
08-29 13:45:03.835  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:03.835  3856  3906 I jxcore-log: 
08-29 13:45:03.836  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.836  3856  3906 I jxcore-log: 
08-29 13:45:03.837  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.837  3856  3906 I jxcore-log: 
,08-29 13:45:03.837  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.837  3856  3906 I jxcore-log: 
08-29 13:45:03.838  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.838  3856  3906 I jxcore-log: 
08-29 13:45:03.839  4217  4233 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:45:03.839  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.839  3856  3906 I jxcore-log: 
08-29 13:45:03.839  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:03.839  4217  4236 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:45:03.840  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:03.840  3856  3906 I jxcore-log: 
,08-29 13:45:03.845  4217  4233 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 13:45:03.846  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:45:03.846  4217  4236 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:45:03.852  4217  4233 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:45:03.852  4217  4233 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:45:04.121  3856  3856 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:45:04.125  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:04.125  3856  3906 I jxcore-log: 
,08-29 13:45:04.204  3856  3856 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:45:04.207  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:04.207  3856  3906 I jxcore-log: 
,08-29 13:45:04.269  3856  3856 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:45:04.272  3856  3906 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:04.272  3856  3906 I jxcore-log: 
,08-29 13:45:04.406  4296  4296 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 13:45:04.411  4296  4296 D AndroidRuntime: CheckJNI is OFF
,08-29 13:45:04.454  4296  4296 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 13:45:04.502  4296  4296 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 13:45:04.525  4296  4296 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:45:04.535   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 13:45:04.536   871   884 I ActivityManager: Killing 3856:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 13:45:04.640   871   894 W PackageSettings: Skipping PackageSetting{5fb42f3 com.example.hello/10273} due to missing metadata
,08-29 13:45:04.654   871  3262 I WindowState: WIN DEATH: Window{99a338c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 13:45:04.656   871  2011 D GraphicsStats: Buffer count: 2
,08-29 13:45:04.656   871  1314 D WifiService: Client connection lost with reason: 4
,08-29 13:45:04.678   871   894 I art     : Starting a blocking GC Explicit
,08-29 13:45:04.697   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 13:45:04.697   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 13:45:04.700   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-29 13:45:04.700   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 13:45:04.700   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:04.700   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.700   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.700   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 13:45:04.701   871   884 I ActivityManager:   Force finishing activity ActivityRecord{a6b43d u0 com.test.thalitest/.MainActivity t2}
,08-29 13:45:04.713   871  1681 W ActivityManager: Spurious death for ProcessRecord{326d517 0:com.test.thalitest/u0a0}, curProc for 3856: null
,08-29 13:45:04.747   871   894 I art     : Explicit concurrent mark sweep GC freed 13758(958KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.062ms total 61.181ms
,08-29 13:45:04.784   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 13:45:04.789  4296  4296 I art     : System.exit called, status: 0
08-29 13:45:04.789  4296  4296 I AndroidRuntime: VM exiting with result code 0.
08-29 13:45:04.791   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 13:45:04.823   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 13:45:04.829  1897  1897 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 13:45:04.829  4217  4217 D BluetoothMapAppObserver: onReceive
08-29 13:45:04.829  4217  4217 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 13:45:04.830  1857  2136 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 13:45:04.836   871  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:45:04.836  3711  3711 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 13:45:04.851  1897  4307 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 13:45:04.852   871  3262 I ActivityManager: Start proc 4309:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 13:45:04.864  1897  4307 I Decoder : createOrResetDecoder
,08-29 13:45:04.880  1962  1962 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 13:45:04.898  4309  4309 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 13:45:04.901  1503  1503 I ConfigService: onCreate
,08-29 13:45:04.907  1503  4322 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-29 13:45:04.919  1897  4307 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 13:45:04.932   871   881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3856 uid 10000
,08-29 13:45:04.934  1897  1897 I Keyboard.Facilitator: onFinishInput()
,08-29 13:45:04.940   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 13:45:04.958  1897  4307 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 13:45:04.960  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-29 13:45:04.960  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 13:45:04.963  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 13:45:04.963  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 13:45:04.964  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 13:45:04.964  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-29 13:45:04.968  1897  4307 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 13:45:04.969  1897  4307 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 13:45:04.969  1897  4307 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 13:45:04.969  1897  4307 I Keyboard.Facilitator.RecurringTaskScheduler: run(),
08-29 13:45:04.969  1897  4307 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 13:45:04.969  1897  4307 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 13:45:04.977  1976  2076 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 13:45:04.977  4309  4309 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 13:45:04.978   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-29 13:45:04.978   871   883 E PackageManager: Failed to write settings, restoring backup
08-29 13:45:04.978   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 13:45:04.978   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 13:45:04.978   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 13:45:04.978   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 13:45:04.978   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 13:45:04.978   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:04.978   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.978   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.983   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-29 13:45:04.983   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 13:45:04.983   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:04.983   871   884 E DropBoxManagerService: 	... 13 more
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0),: Could not open the database in read/write mode.
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.984  4309  4324 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penDatabase(SQLiteDatabase.java:694)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.984  4309  4324 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.990   871  2015 I ActivityManager: Start proc 4327:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 13:45:04.991  1976  2076 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 13:45:04.991  1976  2076 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1976
08-29 13:45:04.991  1976  2076 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:04.991  1976  2076 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:04.993   871  1402 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:45:04.994   871  4332 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:04.994   871  4332 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:04.994   871  4332 E DropBoxManagerService: 	... 5 more
08-29 13:45:04.998  1976  2076 I Process : Sending signal. PID: 1976 SIG: 9
08-29 13:45:05.009   871  3262 I ActivityManager: Start proc 4339:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 13:45:05.048  4309  4345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 13:45:05.051   871  2018 D GraphicsStats: Buffer count: 1
08-29 13:45:05.051   871  2011 I WindowState: WIN DEATH: Window{415b469 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 13:45:05.062   871  1999 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1976) has died
08-29 13:45:05.062   871  1999 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-29 13:45:05.064   871  1999 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 13:45:05.081  4339  4339 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 13:45:05.082   871   884 I ActivityManager: Start proc 4353:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 13:45:05.103  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 13:45:05.104  1503  1503 D AndroidRuntime: Shutting down VM
08-29 13:45:05.104  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:45:05.104  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
08-29 13:45:05.104  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 13:45:05.104  1503  1503 E AndroidRuntime: 	... 8 more
,08-29 13:45:05.110   871  4368 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.110   871  4368 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.110   871  4368 E DropBoxManagerService: 	... 5 more
,08-29 13:45:05.111  1503  1503 I Process : Sending signal. PID: 1503 SIG: 9
,08-29 13:45:05.137  4353  4353 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.137  4353  4353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:45:05.137  4353  4353 D AndroidRuntime: Shutting down VM
,08-29 13:45:05.138   871  1314 D WifiService: Client connection lost with reason: 4
,08-29 13:45:05.143   871  1681 I ActivityManager: Process com.google.process.gapps (pid 1503) has died
,08-29 13:45:05.144   871  1681 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-29 13:45:05.144   871  1681 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-29 13:45:05.144   871  1681 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,08-29 13:45:05.144   871  1681 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,08-29 13:45:05.149  1684  1684 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 13:45:05.154  4353  4353 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:45:05.154  4353  4353 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4353
08-29 13:45:05.154  4353  4353 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.154  4353  4353 E AndroidRuntime: 	... 10 more
,08-29 13:45:05.165   871   881 I ActivityManager: Start proc 4372:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-29 13:45:05.166   871  2011 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:45:05.167   871  4378 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.167   871  4378 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.167   871  4378 E DropBoxManagerService: 	... 5 more
08-29 13:45:05.167  4353  4353 I Process : Sending signal. PID: 4353 SIG: 9
,08-29 13:45:05.191  4372  4372 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 13:45:05.196  4372  4372 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.198  4372  4372 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:45:05.199  4372  4372 D AndroidRuntime: Shutting down VM
08-29 13:45:05.199  4372  4372 E AndroidRuntime: FATAL EXCEPTION: main
08-2,9 13:45:05.199  4372  4372 E AndroidRuntime: Process: com.google.process.gapps, PID: 4372
08-29 13:45:05.199  4372  4372 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:45:05.199  ,4372  4372 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.199  4372  4372 E AndroidRuntime: 	... 10 more
08-29 13:45:05.202  4372  4372 I Process : Sending signal. PID: 4372 SIG: 9
08-29 13:45:05.203   871  4387 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.203   871  4387 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.203   871  4387 E DropBoxManagerService: 	... 5 more
08-29 13:45:05.207  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 13:45:05.207  1684  1684 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 13:45:05.208   871  2015 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4353) has died
08-29 13:45:05.209   871  2015 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 13:45:05.216  4309  4324 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.222  4309  4345 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 13:45:05.222  4309  4345 E AndroidRuntime: Process: android.process.acore, PID: 4309
08-29 13:45:05.222  4309  4345 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.222  4309  4345 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:45:05.223   871   884 I ActivityManager: Start proc 4388:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 13:45:05.226  4309  4324 I Process : Sending signal. PID: 4309 SIG: 9
08-29 13:45:05.229   871  4399 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.229   871  4399 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.229   871  4399 E DropBoxManagerService: 	... 5 more
08-29 13:45:05.232  1684  1684 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 13:45:05.234   871  2018 I ActivityManager: Process com.google.process.gapps (pid 4372) has died
08-29 13:45:05.234  1684  1684 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 13:45:05.235   871  2018 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{787e1d1 u0 com.google.android.gms/.auth.GetToken}
08-29 13:45:05.235   871  2018 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{48757c9 u0 com.google.android.gms/.config.ConfigService}
08-29 13:45:05.235   871  2018 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{1743fb8 u0 com.google.android.gms/.gcm.GcmService}
08-29 13:45:05.235   871  2018 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{a9e692 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-29 13:45:05.245  1684  4402 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 13:45:05.247   871  2018 I ActivityManager: Start proc 4403:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-29 13:45:05.254   279   279 E lowmemorykiller: Error writing /proc/4309/oom_score_adj; errno=22
08-29 13:45:05.254   871  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
08-29 13:45:05.254   279   279 E lowmemorykiller: Error writing /proc/4309/oom_score_adj; errno=22
08-29 13:45:05.256  2059  4401 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 13:45:05.268  1684  4402 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 13:45:05.268  1684  4402 E AndroidRuntime: Process: com.google.android.gms, PID: 1684
08-29 13:45:05.268  1684  4402 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 13:45:05.268  1684  4402 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-29 13:45:05.274   279   279 E lowmemorykiller: Error writing /proc/4309/oom_score_adj; errno=22
,08-29 13:45:05.276   871  4416 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.276   871  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.276   871  4416 E DropBoxManagerService: 	... 5 more
,08-29 13:45:05.284   373   596 E QMI_FW  : xport_send: Sendto failed for port 3072
,08-29 13:45:05.293  4388  4388 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.293  4388  4388 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:45:05.294  4388  4388 D AndroidRuntime: Shutting down VM
,08-29 13:45:05.295   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 13:45:05.300  1684  4402 I Process : Sending signal. PID: 1684 SIG: 9
,08-29 13:45:05.303   279   279 E lowmemorykiller: Error writing /proc/4309/oom_score_adj; errno=22
,08-29 13:45:05.306  4388  4388 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:45:05.306  4388  4388 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4388
08-29 13:45:05.306  4388  4388 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 13:45:05.306  4388  4388 E AndroidRuntime: 	... 10 more
08-29 13:45:05.308   871  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:45:05.309  4403  4403 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-29 13:45:05.310   871  4417 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:05.310   871  4417 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:45:05.310   871  4417 E DropBoxManagerService: 	... 5 more

```
