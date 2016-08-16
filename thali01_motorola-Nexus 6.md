#### Test 8076137450b0c73_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-16 10:24:29.281  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 10:24:29.293  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 10:24:29.296  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 10:24:29.333  1525  1877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 10:24:29.333  1525  1877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 10:24:29.333  1525  1877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:24:29.334  1525  1877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 10:24:29.353  3534  3534 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 10:24:29.354  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 10:24:29.354  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-16 10:24:29.790   873  1318 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-16 10:24:29.947  3825  3825 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 10:24:29.951  3825  3825 D AndroidRuntime: CheckJNI is OFF
08-16 10:24:29.987  3825  3825 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 10:24:30.030  3825  3825 I Radio-JNI: register_android_hardware_Radio DONE
08-16 10:24:30.052  3825  3825 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 10:24:30.057   873  1524 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 10:24:30.098  2027  2038 W SearchService: Abort, client detached.
08-16 10:24:30.103  3825  3825 D AndroidRuntime: Shutting down VM
08-16 10:24:30.105  2027  2027 I HotwordDetector: Closing mic
08-16 10:24:30.106  2027  2319 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1a87e15
08-16 10:24:30.107  2027  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 10:24:30.128   873  1994 I ActivityManager: Start proc 3834:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 10:24:30.162   375  2342 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 10:24:30.163   375  2342 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 10:24:30.172   375  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 10:24:30.174  2027  2338 I MicroRecognitionRnrImpl: Detection finished
08-16 10:24:30.175  2027  2329 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 10:24:30.218  3834  3834 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 10:24:30.248  3834  3834 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 10:24:30.255  3834  3834 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3886-3889)
08-16 10:24:30.256  3834  3834 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:24:30.291  3834  3834 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27fe96e}
08-16 10:24:30.292  3834  3834 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:24:30.293  3834  3834 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 10:24:30.303  3834  3834 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 10:24:30.304  3834  3834 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 10:24:30.332  3834  3834 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 10:24:30.353  3834  3834 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 10:24:30.353  3834  3834 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 10:24:30.353  3834  3834 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 10:24:30.353  3834  3834 I Adreno  : Build Date                       : 10/20/15
08-16 10:24:30.353  3834  3834 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 10:24:30.353  3834  3834 I Adreno  : Local Branch                     : M14
08-16 10:24:30.353  3834  3834 I Adreno  : Remote Branch                    : 
08-16 10:24:30.353  3834  3834 I Adreno  : Remote Branch                    : 
08-16 10:24:30.353  3834  3834 I Adreno  : Reconstruct Branch               : 
,08-16 10:24:30.448   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77da6b8:true
,08-16 10:24:30.509  3834  3834 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 10:24:30.529  3834  3834 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 10:24:30.601  3834  3873 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 10:24:30.608  3834  3859 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 10:24:30.635  3834  3873 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 10:24:30.710   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +601ms
,08-16 10:24:30.712  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 10:24:30.794  3834  3834 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3834
,08-16 10:24:30.957   873   884 I ActivityManager: Killing 3238:com.google.android.gm/u0a78 (adj 15): empty #17
,08-16 10:24:30.977  3834  3834 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 10:24:31.000   873   884 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-16 10:24:31.245  3834  3875 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1681458896
,08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 10:24:31.264  3834  3875 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb7ab1d added. We now have 1 listener(s)
,08-16 10:24:31.275  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 10:24:31.277  3834  3875 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 10:24:31.278  3834  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:24:31.278  3834  3875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 10:24:31.287  3834  3875 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@828dc19 added. We now have 1 listener(s)
,08-16 10:24:31.288  3834  3875 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:24:31.292   873  1319 D WifiService: New client listening to asynchronous messages
08-16 10:24:31.294  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:24:31.294  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 10:24:31.294  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 10:24:31.294  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 10:24:31.294  3834  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 10:24:31.299  3834  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:24:31.299  3834  3875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-16 10:24:31.305  3834  3875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:24:31.305  3834  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:24:31.305  3834  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 10:24:31.305  3834  3875 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:24:31.306  3834  3875 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 10:24:31.518  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:24:31.527  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:24:31.529  3834  3834 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 10:24:32.641  3834  3884 W jxcore-log: Initializing JXcore engine
,08-16 10:24:32.641  3834  3884 W jxcore-log: JXcore engine is ready
,08-16 10:24:32.677  3884  3884 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 10:24:32.677  3884  3884 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9949]" dev="sockfs" ino=9949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 10:24:32.677  3884  3884 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 10:24:32.677  3884  3884 W Thread-329: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23451]" dev="sockfs" ino=23451 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 10:24:32.693  3834  3884 W jxcore-log: Starting JXcore engine
,08-16 10:24:32.782  3834  3884 W jxcore-log: Platform android
08-16 10:24:32.782  3834  3884 W jxcore-log: 
08-16 10:24:32.782  3834  3884 W jxcore-log: Process ARCH arm
08-16 10:24:32.782  3834  3884 W jxcore-log: 
,08-16 10:24:33.001  3834  3884 I jxcore-log: JXcore Cordova bridge is ready!
08-16 10:24:33.001  3834  3884 I jxcore-log: 
,08-16 10:24:33.002  3834  3884 W jxcore-log: JXcore engine is started
,08-16 10:24:33.011  3834  3875 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 10:24:33.016  3834  3834 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 10:24:35.624  3607  3892 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 10:24:35.648  3607  3893 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 10:24:35.659  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:35.662  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:35.703  3626  3891 V KeepSync: Connecting to GoogleApiClient
,08-16 10:24:35.704   873  1524 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-16 10:24:35.706  1525  2444 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 10:24:35.706  1525  2444 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 10:24:35.706  1525  2444 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-16 10:24:35.706  1525  2444 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:24:35.729  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:35.730  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:35.754  1525  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 10:24:35.754  1525  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 10:24:35.754  1525  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:24:35.754  1525  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:24:35.761  1525  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 10:24:35.761  1525  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 10:24:35.761  1525  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:24:35.761  1525  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:24:35.773  3607  3893 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 10:24:35.774  3607  3892 E BooksSync: Soft error
08-16 10:24:35.774  3607  3892 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 10:24:35.774  3607  3892 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 10:24:35.774  3607  3892 E BooksSync: Sync error
08-16 10:24:35.774  3607  3892 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 10:24:35.774  3607  3892 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 10:24:35.774  3607  3892 I BooksSync: Finished books sync
,08-16 10:24:35.776  1754  3895 V BaseAuthAsyncOperation: access token request failed
08-16 10:24:35.777  3626  3891 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 10:24:35.779   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:24:35.817  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 10:24:35.818  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 10:24:35.818  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:24:35.818  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:24:35.835  3626  3891 E KeepSync: IOException
08-16 10:24:35.835  3626  3891 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 10:24:35.835  3626  3891 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:24:35.835  3626  3891 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 10:24:35.835  3626  3891 E KeepSync: 	... 10 more
08-16 10:24:35.835  3626  3891 W KeepSync: Sync result 2
,08-16 10:24:35.840   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128130, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:24:38.559   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 10:24:41.596   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 10:24:49.294  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 10:24:49.294  3834  3884 I jxcore-log: 
,08-16 10:24:49.297  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 10:24:49.297  3834  3884 I jxcore-log: 
,08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:24:49.305  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:24:49.309  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:24:49.311  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 10:24:49.311  3834  3884 I jxcore-log: 
,08-16 10:24:49.313  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 10:24:49.313  3834  3884 I jxcore-log: 
,08-16 10:24:49.693  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:49.708  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:49.714  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:24:49.736  3834  3884 I jxcore-log: Running unit tests
08-16 10:24:49.736  3834  3884 I jxcore-log: 
,08-16 10:24:49.736  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:24:49.737  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b6951c added. We now have 2 listener(s)
,08-16 10:24:49.738  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 10:24:49.738  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 10:24:49.739  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:24:49.739  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 10:24:49.739  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d43525 added. We now have 2 listener(s)
08-16 10:24:49.739  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:24:49.741  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:24:49.754  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:24:49.764  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:24:49.768  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:24:49.768  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:24:49.769  3834  3884 D ExecuteNativeTests: Running unit tests,
,08-16 10:24:49.772  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:24:49.779  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:24:49.782  1525  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 10:24:49.782  1525  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 10:24:49.782  1525  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:24:49.782  1525  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:24:49.821  3534  3534 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 10:24:49.821  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 10:24:49.822  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 10:24:54.852  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 10:24:54.853  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b added. We now have 3 listener(s)
,08-16 10:24:54.855  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 10:24:54.855  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 10:24:54.855  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 10:24:54.855  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 10:24:54.855  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 added. We now have 3 listener(s),
,08-16 10:24:54.855  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:24:54.857  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:24:54.864  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:24:54.878  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:24:54.885  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:24:54.885  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:24:54.891  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:24:54.892  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 10:24:54.895  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 10:24:54.895  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:24:54.895  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:24:54.896  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 10:24:54.901  3834  3884 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 10:24:54.901  3834  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 10:24:54.901  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 10:24:54.902  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 10:24:54.902  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:24:54.902  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 10:24:54.903  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:24:54.906  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:24:54.906  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:24:54.907  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:24:54.907  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.907  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:24:54.908  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 10:24:54.908  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b removed from the list
08-16 10:24:54.908  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:24:54.908  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 removed from the list
08-16 10:24:54.908  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:24:54.909  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:24:54.910  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.910  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:24:54.915  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:24:54.915  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:24:54.915  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:24:54.915  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:24:54.918  3834  3884 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 10:24:54.919  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:24:54.919  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:24:54.919  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:24:54.919  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:24:54.919  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.919  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.919  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:24:54.919  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:24:54.920  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:24:54.920  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:24:54.920  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.920  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.920  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.920  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.922  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:24:54.922  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:24:54.922  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:24:54.923  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:24:54.930  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 10:24:54.930  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 10:24:54.930  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 10:24:54.930  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 10:24:54.930  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 10:24:54.931  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-16 10:24:54.932  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 10:24:54.933  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 10:24:54.933  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:24:54.933  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:24:54.933  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:24:54.934  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:24:54.934  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.935  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.935  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:24:54.935  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:24:54.935  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:24:54.935  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:24:54.935  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.935  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.935  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:24:54.935  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:24:54.937  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:24:54.937  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:24:54.937  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:24:54.937  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:24:54.937  3834  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 10:24:54.939  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:24:54.950  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:24:54.956  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:24:54.957  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:24:54.958  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:24:54.958  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:24:54.958  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:24:54.958  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:24:54.958  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:24:54.960  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:24:54.962  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 10:24:54.962  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 10:24:54.964  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:24:54.971  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:24:54.972  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 10:24:54.973  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 10:24:54.975  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 10:24:54.979  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 10:24:54.979  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 10:24:54.980  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 10:24:54.980  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 10:24:54.981  3834  3884 D BluetoothAdapter: STATE_ON
08-16 10:24:54.987  2707  2720 D BtGatt.GattService: registerClient() - UUID=f26869fc-3fce-4b46-af32-74a2b7fd2a66
08-16 10:24:54.988  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=f26869fc-3fce-4b46-af32-74a2b7fd2a66, clientIf=5
08-16 10:24:54.989  3834  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 10:24:54.991  2707  2907 D BtGatt.GattService: start scan with filters
08-16 10:24:55.008  2707  2766 D BtGatt.ScanManager: handling starting scan
08-16 10:24:55.008  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 10:24:55.008  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 10:24:55.009  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 10:24:55.009  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 10:24:55.009  2707  2766 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:24:55.016  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:24:55.017  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 10:24:55.017  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:24:55.017  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 10:24:55.017  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 10:24:55.017  2707  2766 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 10:24:55.022  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:24:55.023  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 10:24:55.024  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:24:55.024  2707  2766 D BtGatt.ScanManager: Starting BLE batch scan
08-16 10:24:55.024  2707  2766 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 10:24:55.026  3834  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 10:24:55.034  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 10:24:55.034  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:24:55.040  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 10:24:55.040  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:24:55.519  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 10:24:55.519  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 10:24:55.520  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:24:56.550  2707  2707 D BtGatt.ScanManager: awakened up at time 150183
,08-16 10:24:56.552  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:24:56.599  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 10:24:56.599  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:24:56.600  2707  2761 D BtGatt.GattService: current time is 150234091767
,08-16 10:24:56.601  2707  2761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 10:24:56.605  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:24:56.607  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 10:24:56.608  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 10:24:56.609  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 10:24:58.103  2707  2707 D BtGatt.ScanManager: awakened up at time 151737
,08-16 10:24:58.105  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:24:58.118  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 10:24:58.118  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:24:59.030   873  1857 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 10:24:59.387   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 10:24:59.397  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 10:24:59.414   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 10:24:59.414   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 10:24:59.414   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 10:24:59.414   873   893 I Adreno  : Local Branch                     : M14
08-16 10:24:59.414   873   893 I Adreno  : Remote Branch                    : 
08-16 10:24:59.414   873   893 I Adreno  : Remote Branch                    : 
08-16 10:24:59.414   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 10:24:59.462   281   396 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (333 us)
,08-16 10:24:59.616  2707  2707 D BtGatt.ScanManager: awakened up at time 153250
08-16 10:24:59.617  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:24:59.630  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-16 10:24:59.630  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:24:59.630  2707  2761 D BtGatt.GattService: current time is 153263857880
08-16 10:24:59.630  2707  2761 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 10:24:59.630  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:24:59.630  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 10:24:59.747   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 10:25:00.036  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:00.037  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:00.037  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 10:25:00.037  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:00.037  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 10:25:00.038  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 10:25:00.038  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 10:25:00.038  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:25:00.039  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:25:00.045  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 10:25:00.050  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 10:25:00.054  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:25:00.056  2707  2907 D BtGatt.GattService: stopScan() - queue size =1
,08-16 10:25:00.064  2707  2720 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:25:00.064  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 10:25:00.064  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 10:25:00.064  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 10:25:00.065  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 10:25:00.065  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 10:25:00.066  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:25:00.066  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 10:25:00.066  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:25:00.067  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:25:00.067  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:25:00.069  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:25:00.069  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:25:00.069  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:25:00.070  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 10:25:00.070  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:00.070  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:00.070  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:00.070  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:25:00.070  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:00.070  2707  2766 D BtGatt.ScanManager: stopping BLe Batch
,08-16 10:25:00.070  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:00.070  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:00.070  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:00.071  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:00.091  3834  3834 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 10:25:00.091  3834  3834 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 10:25:00.136   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 10:25:00.140  2707  2707 D BtGatt.ScanManager: awakened up at time 153774
,08-16 10:25:00.144   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 10:25:00.147  3834  3834 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@90cc734 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@77e6d02, 16908290=android.view.AbsSavedState$1@77e6d02}, android:focusedViewId=100}]}]
,08-16 10:25:00.148  3834  3834 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 10:25:00.148  3834  3834 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 10:25:00.148  3834  3834 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 10:25:00.149   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 10:25:00.150   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-16 10:25:00.150   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 10:25:00.153  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 10:25:00.153  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:00.153  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:00.166  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-16 10:25:00.166  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:00.166  2707  2761 D BtGatt.GattService: current time is 153800035486
,08-16 10:25:00.166  2707  2761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 10:25:00.167  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:25:00.377   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 10:25:00.381   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 10:25:00.385   873  1342 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-16 10:25:00.389   873   893 I DreamManagerService: Entering dreamland.
,08-16 10:25:00.390   873   893 I PowerManagerService: Dozing...
,08-16 10:25:00.392   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 10:25:00.439   375  1468 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 10:25:00.440   375  1468 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 10:25:00.446   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:25:00.461   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 10:25:00.468   873  1318 E native  : do suspend false
,08-16 10:25:00.477  1917  3905 D NfcService: Discovery configuration equal, not updating.
,08-16 10:25:00.489   873  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 10:25:00.507   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:25:00.510   873  1318 E native  : do suspend true
,08-16 10:25:00.571  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:25:00.589   375  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 10:25:00.590   375  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 10:25:00.952   873  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 10:25:05.136  3834  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 10:25:05.143  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:05.163  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:25:05.170  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:25:05.171  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:25:05.172  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:25:05.172  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 10:25:05.172  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 10:25:05.172  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:25:05.173  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:25:05.179  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:05.184  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 10:25:05.184  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 10:25:05.188  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:05.197  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:25:05.199  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 10:25:05.199  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 10:25:05.208  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 10:25:05.209  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 10:25:05.209  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 10:25:05.211  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:25:05.216  2707  2720 D BtGatt.GattService: registerClient() - UUID=47cf8b25-82e0-4e41-b213-fc0e008ebf9b
,08-16 10:25:05.217  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=47cf8b25-82e0-4e41-b213-fc0e008ebf9b, clientIf=5
,08-16 10:25:05.218  3834  3903 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 10:25:05.219  2707  2721 D BtGatt.GattService: start scan with filters
,08-16 10:25:05.226  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 10:25:05.226  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 10:25:05.226  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 10:25:05.226  2707  2766 D BtGatt.ScanManager: handling starting scan
08-16 10:25:05.226  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 10:25:05.235  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:25:05.237  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:25:05.237  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 10:25:05.243  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 10:25:05.243  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.244  2707  2766 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 10:25:05.244  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:25:05.258  3834  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 10:25:05.261  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 10:25:05.261  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.261  2707  2766 D BtGatt.ScanManager: Starting BLE batch scan
08-16 10:25:05.261  2707  2766 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 10:25:05.264  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:05.264  3834  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 10:25:05.265  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:05.265  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 10:25:05.265  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:05.265  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 10:25:05.265  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 10:25:05.265  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 10:25:05.265  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:25:05.265  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 10:25:05.265  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 10:25:05.265  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 10:25:05.266  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:25:05.267  2707  2721 D BtGatt.GattService: stopScan() - queue size =1
08-16 10:25:05.269  2707  2907 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:25:05.270  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:25:05.270  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 10:25:05.271  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 10:25:05.271  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 10:25:05.271  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 10:25:05.273  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:25:05.274  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 10:25:05.274  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 10:25:05.274  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 10:25:05.275  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:25:05.278  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:25:05.279  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:25:05.279  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:25:05.279  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:05.280  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:05.280  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:25:05.280  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:05.280  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:05.281  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:05.281  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:05.281  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:05.283  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 10:25:05.283  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.283  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:05.284  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:05.286  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:05.287  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:25:05.287  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:05.287  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:05.289  3834  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 10:25:05.291  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 10:25:05.291  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.297  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:25:05.301  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 10:25:05.301  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:05.302  2707  2766 D BtGatt.ScanManager: stopping BLe Batch
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:05.302  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:25:05.304  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:25:05.305  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:25:05.306  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 10:25:05.306  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:25:05.306  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 10:25:05.306  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:25:05.307  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 10:25:05.308  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 10:25:05.308  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:05.308  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 10:25:05.309  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:05.310  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 10:25:05.310  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 10:25:05.312  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:05.315  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:25:05.315  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 10:25:05.316  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 10:25:05.315  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 10:25:05.316  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.319  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 10:25:05.319  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 10:25:05.319  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 10:25:05.319  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:25:05.321  2707  2720 D BtGatt.GattService: registerClient() - UUID=87be292b-7a6e-4e29-9e06-a9c7d25000c9
,08-16 10:25:05.322  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=87be292b-7a6e-4e29-9e06-a9c7d25000c9, clientIf=5
08-16 10:25:05.322  3834  3903 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 10:25:05.322  2707  2721 D BtGatt.GattService: start scan with filters
,08-16 10:25:05.325  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 10:25:05.325  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 10:25:05.325  2707  2766 D BtGatt.ScanManager: handling starting scan
08-16 10:25:05.325  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 10:25:05.325  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 10:25:05.328  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 10:25:05.328  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 10:25:05.328  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:25:05.330  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:25:05.332  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 10:25:05.332  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:05.332  2707  2766 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 10:25:05.332  3834  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 10:25:05.338  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 10:25:05.339  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:05.339  2707  2766 D BtGatt.ScanManager: Starting BLE batch scan
08-16 10:25:05.339  2707  2766 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 10:25:05.351  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 10:25:05.351  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.357  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 10:25:05.357  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:05.779  2179  2649 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 10:25:05.829  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 10:25:05.830  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:25:05.830  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:25:05.959  2707  2707 D BtGatt.ScanManager: awakened up at time 159592
08-16 10:25:05.960  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:05.995  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-16 10:25:05.995  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:05.995  2707  2761 D BtGatt.GattService: current time is 159629283254
,08-16 10:25:05.996  2707  2761 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 10:25:05.996  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:25:05.996  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 10:25:05.996  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 10:25:05.996  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 10:25:06.143  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:06.149  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:06.221  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:25:06.222  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 10:25:06.222  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 10:25:06.223  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:06.274  3003  3911 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 10:25:06.274  3003  3911 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at blb.a(PG:3937)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at czp.a(PG:18188)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:25:06.274  3003  3911 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	... 12 more
08-16 10:25:06.274  3003  3911 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at fal.a(PG:38)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	at jdj.a(PG:4089)
08-16 10:25:06.274  3003  3911 E HttpOperation: 	... 14 more
,08-16 10:25:06.356  1525  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:25:06.356  1525  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 10:25:06.357  1525  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 10:25:06.357  1525  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:06.397  3003  3911 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 10:25:06.397  3003  3911 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at hec.a(PG:42)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at hee.a(PG:102)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at czr.a(PG:65)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at kka.a(PG:108)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at czp.a(PG:19176)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:25:06.397  3003  3911 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	... 15 more
08-16 10:25:06.397  3003  3911 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at fal.a(PG:38)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	at jdj.a(PG:4089)
08-16 10:25:06.397  3003  3911 E HttpOperation: 	... 17 more
,08-16 10:25:06.399  3003  3911 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 10:25:06.399  3003  3911 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at hec.a(PG:42)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at hee.a(PG:102)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at czr.a(PG:65)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at kka.a(PG:108)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	... 15 more
08-16 10:25:06.399  3003  3911 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at fal.a(PG:38)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 10:25:06.399  3003  3911 E ExperimentLoader: 	... 17 more
,08-16 10:25:06.523   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129541, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:25:06.535  2707  2707 D BtGatt.ScanManager: awakened up at time 160168
,08-16 10:25:06.537  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:06.578  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-16 10:25:06.578  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:06.578  2707  2761 D BtGatt.GattService: current time is 160212092895
,08-16 10:25:06.579  2707  2761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-16 10:25:06.579  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:25:06.580  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 10:25:06.580  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:25:06.581  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 10:25:06.582  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-16 10:25:08.083  2707  2707 D BtGatt.ScanManager: awakened up at time 161717
,08-16 10:25:08.085  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:08.102  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 10:25:08.102  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:25:09.605  2707  2707 D BtGatt.ScanManager: awakened up at time 163238
,08-16 10:25:09.608  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:09.644  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-16 10:25:09.644  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:09.645  2707  2761 D BtGatt.GattService: current time is 163278850161
08-16 10:25:09.645  2707  2761 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -89, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 10:25:09.647  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 10:25:09.647  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 10:25:09.803   873  1318 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 10:25:10.333  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 10:25:10.333  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:10.334  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 10:25:10.334  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:10.334  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 10:25:10.335  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 10:25:10.335  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 10:25:10.335  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:25:10.336  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:25:10.336  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 10:25:10.336  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 10:25:10.340  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:25:10.342  2707  2720 D BtGatt.GattService: stopScan() - queue size =1
,08-16 10:25:10.344  2707  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:25:10.345  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 10:25:10.346  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 10:25:10.346  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 10:25:10.347  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 10:25:10.347  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 10:25:10.351  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:25:10.352  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 10:25:10.352  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:25:10.352  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:25:10.355  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 10:25:10.357  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:25:10.357  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:25:10.357  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:25:10.367  2707  2707 D BtGatt.ScanManager: awakened up at time 164000
,08-16 10:25:10.391  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 10:25:10.392  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:10.392  2707  2766 D BtGatt.ScanManager: stopping BLe Batch
,08-16 10:25:10.404  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 10:25:10.404  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:10.404  2707  2766 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:25:10.427  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 10:25:10.427  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:25:10.427  2707  2761 D BtGatt.GattService: current time is 164060942965
,08-16 10:25:10.427  2707  2761 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -93, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 10:25:10.427  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 10:25:10.428  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:25:10.428  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:25:10.428  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 10:25:10.447  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:10.636  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:10.643  1525  3914 I VacuumService: Vacuum at: now=1471335910643 tag=VacuumService
,08-16 10:25:10.699  1525  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 10:25:10.699  1525  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 10:25:10.699  1525  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:25:10.699  1525  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:10.714  3534  3534 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 10:25:10.714  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 10:25:10.714  3534  3534 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 10:25:10.758  1525  3915 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 10:25:10.760  1525  3915 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 10:25:10.781  1525  3915 W Uploader:  no longer exists, so no auth token.
,08-16 10:25:10.858  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:25:10.858  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:10.858  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:25:11.949  1525  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 10:25:11.949  1525  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 10:25:11.949  1525  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:25:11.949  1525  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:11.973  1525  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 10:25:11.973  1525  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 10:25:11.973  1525  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 10:25:12.283  1525  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 10:25:12.283  1525  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 10:25:12.283  1525  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:25:12.283  1525  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:12.308  1525  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 10:25:12.308  1525  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 10:25:12.308  1525  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 10:25:12.866  1525  3915 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-16 10:25:12.867  1525  3915 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 10:25:12.867  1525  3915 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 10:25:12.868  1525  3915 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:12.907  1525  3915 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 10:25:12.907  1525  3915 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 10:25:12.907  1525  3915 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 10:25:15.358  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:15.358  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:15.359  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:25:15.359  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.360  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.360  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 10:25:15.361  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.361  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.361  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.362  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.362  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.364  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.365  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.368  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.368  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.369  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.369  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.372  3834  3884 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 10:25:15.374  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:15.374  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:15.374  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.375  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:15.376  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.376  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.376  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.376  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.377  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.377  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:15.377  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.378  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.378  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.378  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.381  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:15.381  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.381  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.381  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.384  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-16 10:25:15.384  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:15.385  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:15.385  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:25:15.386  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.386  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.386  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.387  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:15.387  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.387  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.387  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.388  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.388  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.388  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.388  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.391  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.391  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.391  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.392  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.393  3834  3884 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 10:25:15.394  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:15.394  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:15.395  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:25:15.395  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.396  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.396  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.396  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.397  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.397  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.397  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:15.397  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.397  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.398  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.398  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.400  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.400  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.400  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.401  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.401  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 10:25:15.401  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:15.402  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:15.402  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.402  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.402  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.402  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.402  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:15.402  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.402  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.402  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.402  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.403  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.403  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.403  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.404  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.404  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:25:15.404  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:15.404  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.405  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 10:25:15.405  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 10:25:15.405  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:25:15.405  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 10:25:15.405  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:25:15.405  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:25:15.406  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 10:25:15.406  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:25:15.406  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 10:25:15.406  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:15.406  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:15.406  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.406  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.407  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.407  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.407  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:15.407  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.407  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list,
08-16 10:25:15.407  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.407  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.407  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.407  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.407  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.409  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.409  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.409  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 10:25:15.409  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.410  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 10:25:15.410  3834  3884 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 10:25:15.410  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 10:25:15.414  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:25:15.414  3834  3884 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer,
08-16 10:25:15.414  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
,08-16 10:25:15.414  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 10:25:15.414  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 10:25:15.415  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-16 10:25:15.416  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 10:25:15.417  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 10:25:15.418  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 10:25:15.418  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 10:25:15.418  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 10:25:15.418  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 10:25:15.418  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 10:25:15.419  3834  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:25:15.419  3834  3884 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 10:25:15.419  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:25:15.419  3834  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:25:15.420  3834  3884 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 10:25:15.420  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 10:25:15.420  3834  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 10:25:15.420  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 10:25:15.424  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 10:25:15.426  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 10:25:15.426  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 10:25:15.427  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 10:25:15.427  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 10:25:15.427  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 10:25:15.428  3834  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 10:25:15.428  3834  3884 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 10:25:15.428  3834  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-16 10:25:15.429  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:15.429  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:15.429  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.429  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:15.430  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.430  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.430  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 10:25:15.431  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.431  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.431  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.432  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:15.432  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.432  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.432  3834  3927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:25:15.432  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.432  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.434  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:15.434  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.434  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:15.434  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list,
08-16 10:25:15.435  3834  3884 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 10:25:15.436  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:15.436  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-16 10:25:15.436  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.437  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.437  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.437  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.437  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.437  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 10:25:15.437  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.437  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:15.437  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.437  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.437  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.437  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.439  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:15.439  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:15.439  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:15.439  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:15.439  3834  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-16 10:25:15.439  3834  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
,08-16 10:25:15.439  2707  2891 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-16 10:25:15.440  3834  3927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-16 10:25:15.440  3834  3928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
,08-16 10:25:15.441  3834  3884 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-16 10:25:15.441  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:15.443  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:25:15.443  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.443  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 10:25:15.443  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.444  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:15.444  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:15.444  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.444  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.444  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.444  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.444  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.444  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:15.444  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.445  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:15.445  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:25:15.445  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.446  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.446  3834  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 10:25:15.446  3834  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString,
08-16 10:25:15.446  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 10:25:15.447  3834  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 10:25:15.447  3834  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-16 10:25:15.447  3834  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 10:25:15.447  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 10:25:15.447  3834  3884 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-16 10:25:15.447  3834  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 10:25:15.447  3834  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 10:25:15.447  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 10:25:15.447  3834  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 10:25:15.447  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:15.447  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:15.448  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:15.448  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:15.448  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.448  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.448  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:15.448  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.448  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.448  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:25:15.448  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.448  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.448  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.448  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.449  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:15.449  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:25:15.449  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.449  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.450  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:15.450  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.450  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:15.450  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:15.450  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:15.450  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:15.450  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:15.450  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:15.450  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:20.451  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:20.452  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.452  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:20.452  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:20.453  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.453  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:20.453  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:20.454  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:20.454  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:20.455  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:20.455  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:20.455  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.455  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:20.456  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:20.456  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:20.456  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:20.457  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:20.457  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.457  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.457  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:20.462  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:20.462  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:20.462  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:20.462  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.474  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 10:25:20.474  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:25:20.476  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 10:25:20.477  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 10:25:20.477  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 10:25:20.477  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 10:25:20.477  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 10:25:20.477  3834  3834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 10:25:20.478  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:20.478  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 10:25:20.478  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-16 10:25:20.478  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 10:25:20.478  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.479  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
08-16 10:25:20.479  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:20.479  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:20.479  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 10:25:20.479  3834  3834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 10:25:20.479  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:25:20.479  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-16 10:25:20.479  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.479  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:20.480  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:25:20.481  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:20.481  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:20.481  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:25:20.481  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:20.481  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:20.481  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:20.481  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.481  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:25:20.481  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.481  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:20.481  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.481  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:25:20.482  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:20.482  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:20.482  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.482  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.482  3834  3929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 10:25:20.482  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:20.482  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.482  3834  3929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 10:25:20.484  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:20.484  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:20.484  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.484  3834  3834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 10:25:20.484  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:20.486  3834  3884 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 10:25:20.487  3834  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 10:25:20.487  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 10:25:20.487  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:25:20.487  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 10:25:20.487  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:20.488  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:20.488  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:25:20.488  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:20.488  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.488  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.488  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:20.488  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.489  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.489  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:20.489  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.489  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.489  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.489  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.491  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:20.492  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:20.492  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.494  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.507  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:25:20.508  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:20.508  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:25:20.508  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:25:20.508  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.509  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.509  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
,08-16 10:25:20.509  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.510  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.510  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:20.510  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.510  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:20.511  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.511  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:20.513  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:25:20.513  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:20.513  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.513  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.515  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 10:25:20.515  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:25:20.515  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:25:20.515  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:25:20.515  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.515  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.515  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f8e9b not in the list
08-16 10:25:20.515  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.515  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
08-16 10:25:20.516  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:20.516  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:25:20.516  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.516  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:20.516  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:20.517  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:25:20.517  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:25:20.517  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:25:20.517  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a52238 not in the list
,08-16 10:25:20.562  2707  2885 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 10:25:20.562  2707  2885 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 10:25:20.982  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:25:25.521  3834  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 10:25:25.521  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 10:25:25.522  3834  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 10:25:25.522  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 10:25:25.522  3834  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 10:25:25.523  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 10:25:25.532  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 10:25:25.533  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 10:25:25.535  3834  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-16 10:25:25.536  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-16 10:25:25.537  3834  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 10:25:25.538  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 10:25:25.538  3834  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 10:25:25.538  3834  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 10:25:25.538  3834  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 10:25:25.539  3834  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 10:25:25.539  3834  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-16 10:25:25.539  3834  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 10:25:25.539  3834  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-16 10:25:25.539  3834  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 10:25:30.542  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 10:25:30.542  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1d548b added. We now have 3 listener(s)
08-16 10:25:30.543  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:25:30.550  3834  3884 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 10:25:30.551   873  1939 D WifiService: setWifiEnabled: true pid=3834, uid=10000
08-16 10:25:30.551   873  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:25:35.555  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:25:35.556  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c18968 added. We now have 4 listener(s)
,08-16 10:25:35.557  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:25:35.579  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:35.579  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c18968 removed from the list
08-16 10:25:35.580  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:35.580  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:35.580  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:25:35.583  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:25:35.584  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db56181 added. We now have 4 listener(s)
08-16 10:25:35.584  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:25:35.589  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:25:35.590  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db56181 removed from the list
08-16 10:25:35.590  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:25:35.590  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:25:35.590  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:25:35.593  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 10:25:35.594  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b60226 added. We now have 4 listener(s)
08-16 10:25:35.594  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:25:35.603   873  1524 D WifiService: setWifiEnabled: false pid=3834, uid=10000
,08-16 10:25:35.603   873  1524 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:25:35.620  2707  2757 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 10:25:35.621  2707  2757 D BluetoothAdapterProperties: Setting state to 13
,08-16 10:25:35.621  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 10:25:35.623  2707  2757 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 10:25:35.623  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:25:35.628  2707  2757 I BluetoothAdapterState: Entering PendingCommandState
08-16 10:25:35.635  2707  2761 D BluetoothAdapterProperties: Scan Mode:20
,08-16 10:25:35.635  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 10:25:35.636  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:35.636  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:25:35.638  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:35.638  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:25:35.638  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:25:35.642  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 10:25:35.644   873  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 10:25:35.644   873  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 10:25:35.644   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 10:25:35.645   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:25:35.646  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.647  2707  2707 D BluetoothMapService: onReceive
08-16 10:25:35.648  2707  2707 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:25:35.648  2707  2707 D BluetoothMapService: STATE_TURNING_OFF
,08-16 10:25:35.648  2707  2707 D BluetoothMapService: MAP Service closeService in
08-16 10:25:35.649  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.649  2707  2707 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 10:25:35.649  2707  2707 D ObexServerSockets0: shutdown(block = true)
,08-16 10:25:35.650  2707  2707 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 10:25:35.652  2707  2913 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 10:25:35.653  2707  2912 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 10:25:35.653  2707  2891 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 10:25:35.654  2707  2707 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 10:25:35.655  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:35.655  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:25:35.655  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.656  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:25:35.656  2707  2707 I BtOppRfcommListener: stopping Accept Thread
08-16 10:25:35.657  2707  3464 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:25:35.657  2707  3464 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 10:25:35.659  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:35.659  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:25:35.662  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.662  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:25:35.665   873  1318 E native  : do suspend true
,08-16 10:25:35.665  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.665   873   886 I ActivityManager: Start proc 3933:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 10:25:35.668  2707  2707 D HeadsetService: Received stop request...Stopping profile...
,08-16 10:25:35.669  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:35.673  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:35.673   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:35.673   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:35.673  1384  2090 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:35.673   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:35.674  1929  1945 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:35.674  1384  1384 D HeadsetProfile: Bluetooth service disconnected
08-16 10:25:35.675  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:35.675  2707  2707 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:35.675  2707  2707 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:35.675  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 10:25:35.675  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:35.676  2707  2707 D A2dpService: Received stop request...Stopping profile...
08-16 10:25:35.677  2707  2896 D A2dpStateMachine: Exit Disconnected: -1
08-16 10:25:35.678   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 10:25:35.678  1384  1384 D BluetoothA2dp: Proxy object disconnected
08-16 10:25:35.680   873  1859 D DhcpClient: Clearing IP address
08-16 10:25:35.680   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:25:35.683  2707  2707 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 10:25:35.683  2707  2707 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 10:25:35.683   371   871 D CommandListener: Setting iface cfg
08-16 10:25:35.684  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 10:25:35.684  2707  2707 D HidService: Received stop request...Stopping profile...
08-16 10:25:35.684  2707  2707 D HidService: Stopping Bluetooth HidService
08-16 10:25:35.684  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 10:25:35.684  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:35.684  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:35.685  2707  2761 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 10:25:35.686  1384  1384 D BluetoothInputDevice: Proxy object disconnected
08-16 10:25:35.686  2707  2707 D HealthService: Received stop request...Stopping profile...
,08-16 10:25:35.686  1384  1384 D HidProfile: Bluetooth service disconnected
08-16 10:25:35.689   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 10:25:35.689   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 10:25:35.689   873  1318 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 10:25:35.690   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 10:25:35.690   873  1318 E native  : do suspend true
08-16 10:25:35.688  2707  2707 D PanService: Received stop request...Stopping profile...
,08-16 10:25:35.695   873  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 10:25:35.697  1384  1384 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 10:25:35.697  1384  1384 D PanProfile: Bluetooth service disconnected
08-16 10:25:35.699  2707  2707 D BluetoothMapService: Received stop request...Stopping profile...
08-16 10:25:35.699  2707  2707 D BluetoothMapService: stop()
08-16 10:25:35.700  2707  2707 D BluetoothMapAppObserver: deinitObservers()
08-16 10:25:35.700   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 10:25:35.700  2707  2707 D BluetoothMapAppObserver: removeReceiver()
08-16 10:25:35.701  2707  2707 V BluetoothAdapterState: isTurningOff()=true
,08-16 10:25:35.701  2707  2707 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:35.701  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:35.701  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:35.703  2707  2707 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:35.703   873  1874 D DhcpClient: Receive thread stopped
08-16 10:25:35.704  1384  1384 D BluetoothMap: Proxy object disconnected
08-16 10:25:35.704  1384  1384 D MapProfile: Bluetooth service disconnected
08-16 10:25:35.704  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 10:25:35.704  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:35.703  2707  2707 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:35.704  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:35.704  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:35.704  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:35.704  2707  2885 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:25:35.704  2707  2885 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:25:35.704  2707  2885 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:25:35.704  2707  2707 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 10:25:35.704  2707  2885 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 10:25:35.705  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 10:25:35.705  2707  2707 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 10:25:35.706  2707  2707 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:35.706  2707  2707 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:35.706  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 10:25:35.706  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:35.706  2707  2707 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 10:25:35.706  2707  2761 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 10:25:35.707  2707  2707 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:25:35.707  2707  2707 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:35.707  2707  2707 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:35.707  1525  2199 V NativeCrypto: Read error: ssl=0x9b625a00: I/O error during system call, Connection timed out
08-16 10:25:35.707  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:35.707  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 10:25:35.708  2707  2707 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 10:25:35.708  2707  2707 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 10:25:35.708  2707  2707 D BluetoothMapService: MAP Service closeService in
08-16 10:25:35.709  2707  2707 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:35.709  2707  2707 V BluetoothAdapterState: isTurningOn()=false
,08-16 10:25:35.709  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:35.709  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:35.710  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 10:25:35.710  2707  2757 D BluetoothAdapterProperties: Setting state to 15
08-16 10:25:35.710  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 10:25:35.710   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:25:35.710  2707  2757 I BluetoothAdapterState: Entering BleOnState
08-16 10:25:35.711  1929  2226 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:35.711   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 10:25:35.711  2707  2707 D BluetoothMapService: cleanup()
08-16 10:25:35.711  2707  2707 D BluetoothMapService: MAP Service closeService in
08-16 10:25:35.711  1384  2090 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 10:25:35.713  1384  2013 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:25:35.713  1384  1397 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 10:25:35.714  1384  1399 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:35.715  1384  2090 D BluetoothPan: onBluetoothStateChange on: false
08-16 10:25:35.716  1384  2013 D BluetoothMap: onBluetoothStateChange: up=false
08-16 10:25:35.716   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 10:25:35.716   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:35.717  2707  2757 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 10:25:35.717  2707  2757 D BluetoothAdapterProperties: Setting state to 16
08-16 10:25:35.717  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 10:25:35.717  2707  2757 D BluetoothAdapterProperties: onBleDisable
08-16 10:25:35.717  2707  2757 I BluetoothAdapterState: Entering PendingCommandState
08-16 10:25:35.718  2707  2758 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 10:25:35.718  2707  2885 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 10:25:35.718  2707  2885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:35.719  2707  2761 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:25:35.722  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.722  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.723  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.723  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:35.727  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.727  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.728  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.728  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:35.729  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.729  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.732  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:35.732  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:35.734  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.734  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.735  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:35.744   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:25:35.746  1525  2199 V NativeCrypto: SSL shutdown failed: ssl=0x9b625a00: I/O error during system call, Broken pipe
,08-16 10:25:35.761   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 10:25:35.761   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:25:35.762   873  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-16 10:25:35.763   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 10:25:35.763   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 10:25:35.765   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 10:25:35.768  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.769  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:35.770  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:35.773  3429  3429 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c6cff48 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 10:25:35.773  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 10:25:35.780  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 10:25:35.783   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:25:35.785   873  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 10:25:35.788  2179  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 10:25:35.788  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.788  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.788  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:35.788  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:35.790  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.790  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.791  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.791  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:35.792  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:35.792  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:35.793  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:35.793  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:35.798  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 10:25:35.802   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ee02e6:true
,08-16 10:25:35.803  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:25:35.815   873  1993 I ActivityManager: Start proc 3952:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 10:25:35.824  3933  3933 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 10:25:35.826  3933  3933 D BluetoothMap: Create BluetoothMap proxy object
,08-16 10:25:35.832  3933  3933 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 10:25:35.840   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 10:25:35.845  3952  3952 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 10:25:35.853  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:25:35.859   873  1992 I ActivityManager: Killing 3094:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 10:25:35.922  2707  2761 I bt_hci  : shut_down
,08-16 10:25:35.923  2707  2768 D bt_hwcfg: hw_epilog_process
08-16 10:25:35.924  2707  2768 I bt_vendor: low_power_mode_cb
,08-16 10:25:35.944  2707  2768 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 10:25:35.944  2707  2768 I bt_vendor: epilog_cb
08-16 10:25:35.945  2707  2768 I bt_hci  : epilog_finished_callback
,08-16 10:25:35.951  2707  2761 I bt_hci_h4: hal_close
,08-16 10:25:35.952  2707  2761 I bt_userial_vendor: device fd = 51 close
,08-16 10:25:36.023  3952  3952 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.023  3952  3952 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.023  3952  3952 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.023  3952  3952 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.023  3952  3952 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.023  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.024  3952  3952 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.024  3952  3952 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.024  3952  3952 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:25:36.024  3952  3952 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:25:36.030  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 10:25:36.038  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:25:36.047  3933  3933 D DockEventReceiver: finishStartingService: stopping service
08-16 10:25:36.065   873   883 I ActivityManager: Start proc 3983:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 10:25:36.078   873   883 I ActivityManager: Killing 3429:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 10:25:36.155  2707  2758 D bt_stack_manager: event_shut_down_stack finished.
,08-16 10:25:36.156  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 10:25:36.160  2707  2707 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 10:25:36.160  2707  2757 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 10:25:36.161  2707  2707 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 10:25:36.161  2707  2707 D BtGatt.GattService: stop()
,08-16 10:25:36.161  2707  2707 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 10:25:36.163  2707  2707 V BluetoothAdapterState: isTurningOff()=false
08-16 10:25:36.163  2707  2707 V BluetoothAdapterState: isTurningOn()=false
,08-16 10:25:36.163  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:36.164  2707  2707 V BluetoothAdapterState: isBleTurningOff()=true
08-16 10:25:36.164  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 10:25:36.165  2707  2757 D BluetoothAdapterProperties: Setting state to 10
08-16 10:25:36.165  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 10:25:36.166  2707  2757 I BluetoothAdapterState: Entering OffState
,08-16 10:25:36.167   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 10:25:36.175  3983  3983 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 10:25:36.183  2707  2707 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 10:25:36.183  2707  2707 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 10:25:36.183  2707  2707 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 10:25:36.184  2707  2758 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 10:25:36.185  2707  2758 D bt_stack_manager: event_clean_up_stack finished.
,08-16 10:25:36.191  2707  2707 I art     : System.exit called, status: 0
,08-16 10:25:36.191  2707  2707 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 10:25:36.257   873  1396 I ActivityManager: Process com.android.bluetooth (pid 2707) has died
,08-16 10:25:36.385  3983  4002 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 10:25:36.385  3983  4002 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 10:25:36.387  3983  4002 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-16 10:25:36.387  3983  4002 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 10:25:36.431  3983  4002 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 10:25:36.431  3983  4002 I Babel_SMS: MmsConfig.loadFromResources
,08-16 10:25:36.432  3983  4002 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 10:25:36.433  3983  4002 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 10:25:36.456  3983  3983 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:25:36.458  3983  3983 I Babel_Crash: startup - clean
,08-16 10:25:36.479  3983  3983 I Babel_telephony: TeleModule.launchCompleted
,08-16 10:25:36.484   873  1396 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 10:25:36.499  3983  3983 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 10:25:36.506  3983  3983 W Babel   : BAM#gBA: invalid account id: -1
,08-16 10:25:36.506  3983  3983 W Babel   : BAM#gBA: invalid account id: -1
,08-16 10:25:36.511  3983  4007 I Babel   : deleted: false for 0
,08-16 10:25:36.506  3983  3983 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 10:25:36.520   873  1682 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 10:25:36.551  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 10:25:36.556  1754  1754 D SystemUpdateService: onCreate
,08-16 10:25:36.581  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 10:25:36.584  1754  4011 I SystemUpdateService: active receiver: enabled
,08-16 10:25:36.591  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 10:25:36.591  1754  4011 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 10:25:36.594  1754  2420 I iu.UploadsManager: num queued entries: 0
,08-16 10:25:36.594  1754  2420 I iu.UploadsManager: num updated entries: 0
,08-16 10:25:36.596  1754  4011 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 10:25:36.597  1754  4011 I SystemUpdateService: now status is 0 (complete)
08-16 10:25:36.597  1754  2420 I iu.SyncManager: NEXT; no task
,08-16 10:25:36.597  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 10:25:36.597  1754  4011 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 10:25:36.597  1754  4011 I SystemUpdateService: file has been verified
08-16 10:25:36.598  1754  4011 I SystemUpdateService: OTA package size = 12249756
08-16 10:25:36.598  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 10:25:36.608  1754  4011 I SystemUpdateService: showing system update notification
,08-16 10:25:36.611   873  1993 I ActivityManager: Start proc 4013:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 10:25:36.637  1754  1754 D SystemUpdateService: onDestroy
,08-16 10:25:36.651  3983  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 10:25:36.656  4013  4013 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 10:25:36.673  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:25:36.686  4013  4013 D SprintDMHelper: simOperator: 
,08-16 10:25:36.686  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 10:25:36.701   873  1524 I ActivityManager: Start proc 4025:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 10:25:36.730  3983  3983 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 10:25:36.748  3983  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 10:25:36.753  3983  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 10:25:36.756  3983  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 10:25:36.773  3983  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 10:25:36.787   873  1683 I ActivityManager: Killing 3578:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 10:25:36.860  3983  3983 I vclib   : onServiceConnected
,08-16 10:25:36.876  3952  3973 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 10:25:36.918   873  1994 I ActivityManager: Start proc 4040:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 10:25:36.921  3983  4039 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 10:25:36.929   873  1524 I ActivityManager: Killing 2783:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 10:25:36.954   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@566d41b:true
,08-16 10:25:36.986  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 10:25:37.049  4040  4040 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 10:25:37.049  4040  4040 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 10:25:37.049  4040  4040 I GAv4    :   adb logcat -s GAv4
,08-16 10:25:37.066  4040  4040 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 10:25:37.074  4040  4040 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 10:25:37.102  4040  4057 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 10:25:37.217  4040  4040 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 10:25:37.254  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 10:25:37.269  4040  4040 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 892-902)
08-16 10:25:37.269  4040  4040 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 10:25:37.279  4040  4040 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c4d342}
,08-16 10:25:37.280  4040  4040 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 10:25:37.280  4040  4040 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 10:25:37.289  4040  4040 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 10:25:37.290  4040  4040 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 10:25:37.313  4040  4040 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 10:25:37.327  4040  4040 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 10:25:37.327  4040  4040 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 10:25:37.327  4040  4040 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 10:25:37.327  4040  4040 I Adreno  : Build Date                       : 10/20/15
08-16 10:25:37.327  4040  4040 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 10:25:37.327  4040  4040 I Adreno  : Local Branch                     : M14
08-16 10:25:37.327  4040  4040 I Adreno  : Remote Branch                    : 
08-16 10:25:37.327  4040  4040 I Adreno  : Remote Branch                    : 
08-16 10:25:37.327  4040  4040 I Adreno  : Reconstruct Branch               : 
,08-16 10:25:37.397  4040  4040 I NSApplication: Starting up...
,08-16 10:25:37.407  4040  4086 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 10:25:37.439   873   883 I ActivityManager: Start proc 4091:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 10:25:37.445   873  1524 I ActivityManager: Killing 3517:android.process.acore/u0a5 (adj 15): empty #17
,08-16 10:25:37.586  4091  4091 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 10:25:37.777   873  1993 I ActivityManager: Killing 3713:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 10:25:37.883   873  1524 I ActivityManager: Start proc 4105:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-16 10:25:37.965  4105  4105 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 10:25:38.025  4105  4105 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 10:25:38.092   873  1682 I ActivityManager: Killing 3728:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 10:25:40.642   873   884 D WifiService: setWifiEnabled: true pid=3834, uid=10000
,08-16 10:25:40.642   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:25:40.663   873  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-16 10:25:40.665  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:40.666  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:40.666  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:40.666  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:40.669  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:40.670  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:40.670  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:40.670  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:40.674  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:40.674  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:40.674  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:40.675  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:40.693   873  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-16 10:25:40.694   873  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 10:25:40.695   873  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 10:25:40.697   873  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 10:25:40.698   873  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 10:25:40.698   873  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 10:25:40.698   873  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 10:25:40.726   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 10:25:40.726   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 10:25:40.729   371   871 D CommandListener: Setting iface cfg
,08-16 10:25:40.736   873  1318 E native  : do suspend true
,08-16 10:25:40.736   873  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 10:25:40.736   873  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 10:25:40.749   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:25:40.757   873  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 10:25:40.761   873  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 10:25:41.720   873  1683 I ActivityManager: Killing 3480:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 10:25:42.109   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 10:25:42.135   873  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=8.31 delta 1000 -> 994
,08-16 10:25:42.137   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 10:25:42.138   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:25:42.149   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 10:25:42.186   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 10:25:42.188  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 10:25:42.602  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 10:25:42.642  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 10:25:42.643  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 10:25:42.651   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:25:42.664   873  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 10:25:42.664   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:25:42.664   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 10:25:42.677   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:25:42.685   371   871 D CommandListener: Setting iface cfg
,08-16 10:25:42.685   873  1318 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 10:25:42.694   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 10:25:42.713   873  4141 D DhcpClient: Receive thread started
,08-16 10:25:42.791   873  1318 E native  : do suspend false
,08-16 10:25:42.810   873  1859 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 10:25:42.822   873  4141 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172627, domain null
,08-16 10:25:42.822   873  1859 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172627 seconds
,08-16 10:25:42.827   873  1859 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 10:25:42.838   873  4141 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 10:25:42.839   873  1859 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 10:25:42.844   371   871 D CommandListener: Setting iface cfg
,08-16 10:25:42.850   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 10:25:42.852   873  1318 E native  : do suspend true
,08-16 10:25:42.852   873  1859 D DhcpClient: Scheduling renewal in 86399s
,08-16 10:25:42.868   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 10:25:42.869   873  1318 D WifiConfigStore: No blacklist allowed without epno enabled
08-16 10:25:42.869   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 10:25:42.872   873  1320 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 10:25:42.876   873  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 10:25:42.937   873  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 10:25:42.938   873  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 10:25:42.941   873  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 10:25:42.943   873  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 10:25:42.947   873  1320 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 10:25:42.964   873  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 10:25:42.977   873  1320 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 10:25:42.978   873  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 10:25:42.979   873  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 10:25:42.979   873  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 10:25:42.980   873  1320 D ConnectivityService:    accepting network in place of null
08-16 10:25:42.982   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 10:25:42.984   873  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 10:25:42.991   873  4140 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 10:25:43.062   873  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:807::200e
08-16 10:25:43.062   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:25:43.110   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:25:43.118   873  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 10:25:43.118   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:25:43.131   873  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 10:25:43.132   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 10:25:43.139  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:43.139  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:25:43.139  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:43.139  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.141   873  4138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 08:25:43 GMT], X-Android-Received-Millis=[1471335943140], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471335943111]}
08-16 10:25:43.146  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:43.147  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:25:43.147   873  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 10:25:43.147  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:43.147  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.147   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 10:25:43.147   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 10:25:43.150   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 10:25:43.151  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:25:43.151  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:25:43.151  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:43.151  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:25:43.155  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 10:25:43.165  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 10:25:43.174  1754  1754 D SystemUpdateService: onCreate
,08-16 10:25:43.177  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 10:25:43.203  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 10:25:43.206  1754  2420 I iu.UploadsManager: num queued entries: 0
,08-16 10:25:43.206  1754  2420 I iu.UploadsManager: num updated entries: 0
,08-16 10:25:43.213  1754  4152 I SystemUpdateService: active receiver: enabled
,08-16 10:25:43.219  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 10:25:43.221  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 10:25:43.223  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:25:43.227  1754  4154 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 10:25:43.228  1754  4154 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 10:25:43.235  4013  4013 D SprintDMHelper: simOperator: 
,08-16 10:25:43.236  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 10:25:43.229  1754  4154 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 10:25:43.265  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:43.270  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:25:43.277  1754  4152 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 10:25:43.280  1754  2420 I iu.SyncManager: NEXT; no task
,08-16 10:25:43.302  1754  4152 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 10:25:43.303  1754  4152 I SystemUpdateService: now status is 0 (complete)
,08-16 10:25:43.307  1754  4152 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 10:25:43.308  1754  4152 I SystemUpdateService: file has been verified
08-16 10:25:43.308  1754  4152 I SystemUpdateService: OTA package size = 12249756
,08-16 10:25:43.334  1754  4152 I SystemUpdateService: showing system update notification
,08-16 10:25:43.351  1525  1877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 10:25:43.351  1525  1877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 10:25:43.351  1525  1877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:25:43.351  1525  1877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:25:43.366  1754  1754 D SystemUpdateService: onDestroy
,08-16 10:25:43.373  1754  4154 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-16 10:25:43.436  3983  4159 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 10:25:44.118   873  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 10:25:45.652   873   884 D WifiService: setWifiEnabled: false pid=3834, uid=10000
08-16 10:25:45.653   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:25:45.695  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 10:25:45.705   873  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 10:25:45.706   873  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 10:25:45.706   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 10:25:45.707   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:25:45.735   873  1318 E native  : do suspend true
,08-16 10:25:45.748   873  1859 D DhcpClient: Clearing IP address
,08-16 10:25:45.750   371   871 D CommandListener: Setting iface cfg
,08-16 10:25:45.758   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:25:45.759   873  4141 D DhcpClient: Receive thread stopped
,08-16 10:25:45.760  1525  4163 V NativeCrypto: Read error: ssl=0x9b06ea00: I/O error during system call, Connection timed out
,08-16 10:25:45.762  1525  4163 V NativeCrypto: SSL shutdown failed: ssl=0x9b06ea00: I/O error during system call, Broken pipe
,08-16 10:25:45.767   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 10:25:45.768   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-16 10:25:45.775   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 10:25:45.777   873  1318 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 10:25:45.778   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 10:25:45.778   873  1318 E native  : do suspend true
08-16 10:25:45.786   873  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 10:25:45.816   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:25:45.847   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:25:45.847   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 10:25:45.853   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 10:25:45.856   873  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 10:25:45.856   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 10:25:45.859   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 10:25:45.862  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.862  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:45.863  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:45.863  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:45.865  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.866  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:45.866  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 10:25:45.866  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:45.867  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.867  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:45.867  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.868  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:45.876  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-16 10:25:45.882  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 10:25:45.883   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 10:25:45.887  1754  1754 D SystemUpdateService: onCreate
,08-16 10:25:45.890  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.890  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:45.890  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.890  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:45.891  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.891  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:45.892  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.892  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:45.892   873  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 10:25:45.894  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:45.894  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:45.894  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:45.894  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:45.894  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-16 10:25:45.896  2179  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 10:25:45.911  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 10:25:45.918  1754  2420 I iu.UploadsManager: num queued entries: 0
,08-16 10:25:45.919  1754  2420 I iu.UploadsManager: num updated entries: 0
,08-16 10:25:45.919  1754  2420 I iu.SyncManager: NEXT; no task
,08-16 10:25:45.920  1754  4173 I SystemUpdateService: active receiver: enabled
,08-16 10:25:45.922  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 10:25:45.924  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 10:25:45.925  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:25:45.930  4013  4013 D SprintDMHelper: simOperator: 
,08-16 10:25:45.930  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 10:25:45.951   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 10:25:45.952   873  1320 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 10:25:45.955  3983  4178 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 10:25:45.959  1754  4173 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 10:25:45.967  1754  4173 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 10:25:45.967  1754  4173 I SystemUpdateService: now status is 0 (complete)
08-16 10:25:45.967  1754  4173 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 10:25:45.967  1754  4173 I SystemUpdateService: file has been verified
,08-16 10:25:45.970  1754  4173 I SystemUpdateService: OTA package size = 12249756
,08-16 10:25:45.975  1754  4173 I SystemUpdateService: showing system update notification
,08-16 10:25:45.985  1754  1754 D SystemUpdateService: onDestroy
,08-16 10:25:50.713   873   890 I ActivityManager: Start proc 4183:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 10:25:50.835  4183  4183 D AdapterServiceConfig: Adding HeadsetService
,08-16 10:25:50.835  4183  4183 D AdapterServiceConfig: Adding A2dpService
08-16 10:25:50.836  4183  4183 D AdapterServiceConfig: Adding HidService
08-16 10:25:50.836  4183  4183 D AdapterServiceConfig: Adding HealthService
,08-16 10:25:50.836  4183  4183 D AdapterServiceConfig: Adding PanService
08-16 10:25:50.836  4183  4183 D AdapterServiceConfig: Adding GattService
08-16 10:25:50.836  4183  4183 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 10:25:50.852  4183  4183 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 10:25:50.852   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d0d49f:true
,08-16 10:25:50.857  4183  4183 I bt_bluedroid: init
,08-16 10:25:50.858  4183  4195 I BluetoothAdapterState: Entering OffState
,08-16 10:25:50.865  4183  4196 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 10:25:50.865  4183  4196 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 10:25:50.866  4183  4196 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 10:25:50.866  4183  4196 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 10:25:50.869  4183  4183 I bt_bluedroid: get_profile_interface socket
,08-16 10:25:50.871  4183  4183 I bt_bluedroid: get_profile_interface sdp
,08-16 10:25:50.875  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 10:25:50.879  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 10:25:50.879  4183  4194 I bt_bluedroid: config_hci_snoop_log
,08-16 10:25:50.883   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 10:25:50.893  4183  4195 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 10:25:50.894  4183  4195 D BluetoothAdapterProperties: Setting state to 14
08-16 10:25:50.894  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 10:25:50.899  4183  4195 D BluetoothBondStateMachine: make
,08-16 10:25:50.905  4183  4200 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 10:25:50.912  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-16 10:25:50.914  4183  4183 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 10:25:50.922  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:50.924  4183  4183 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 10:25:50.925  4183  4183 D BtGatt.GattService: Received start request. Starting profile...
,08-16 10:25:50.925  4183  4183 D BtGatt.GattService: start()
08-16 10:25:50.926  4183  4183 I bt_bluedroid: get_profile_interface gatt
,08-16 10:25:50.928  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:25:50.928  4183  4183 D BtGatt.AdvertiseManager: advertise manager created
,08-16 10:25:50.951  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:25:50.952  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:50.952  4183  4183 V BluetoothAdapterState: isBleTurningOn()=true
08-16 10:25:50.952  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:50.952  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 10:25:50.953  4183  4195 I bt_bluedroid: enable
08-16 10:25:50.954  4183  4196 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 10:25:50.955  4183  4196 I bt_hci  : start_up
,08-16 10:25:50.977  4183  4196 I bt_vendor: alloc value 0xb399c189
,08-16 10:25:50.977  4183  4196 I bt_vendor: init
,08-16 10:25:50.977  4183  4196 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 10:25:50.978  4183  4196 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 10:25:50.983   873  1320 D ConnectivityService: handlePromptUnvalidated 101
,08-16 10:25:51.085  4183  4196 D bt_hci  : start_up starting async portion
,08-16 10:25:51.086  4183  4203 I bt_hci  : event_finish_startup
08-16 10:25:51.086  4183  4203 I bt_hci_h4: hal_open
08-16 10:25:51.086  4183  4203 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 10:25:51.101  4183  4203 I bt_userial_vendor: device fd = 51 open,
,08-16 10:25:51.127  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 10:25:51.159  4183  4203 D bt_hwcfg: Chipset BCM4354A2
,08-16 10:25:51.159  4183  4203 D bt_hwcfg: Target name = [BCM4354A2]
08-16 10:25:51.160  4183  4203 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 10:25:51.820  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 10:25:51.821  4183  4203 D bt_hwcfg: Settlement delay -- 100 ms
08-16 10:25:51.822  4183  4203 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 10:25:51.938  4183  4203 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 10:25:51.940  4183  4203 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 10:25:51.969  4183  4203 I bt_hwcfg: vendor lib fwcfg completed
,08-16 10:25:51.970  4183  4203 I bt_vendor: firmware callback
08-16 10:25:51.970  4183  4203 I bt_hci  : firmware_config_callback
,08-16 10:25:51.981  4183  4205 I bt_btu  : btu_task pending for preload complete event
,08-16 10:25:51.982  4183  4205 I bt_btu_task: Bluetooth chip preload is complete
08-16 10:25:51.982  4183  4205 I bt_btu  : btu_task received preload complete event
,08-16 10:25:51.993  4183  4205 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 10:25:51.994  4183  4205 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 10:25:51.994  4183  4205 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 10:25:51.994  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 10:25:51.995  4183  4205 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 10:25:51.995  4183  4205 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 10:25:51.995  4183  4205 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 10:25:51.996  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 10:25:51.996  4183  4205 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 10:25:51.996  4183  4205 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 10:25:51.997  4183  4205 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 10:25:51.997  4183  4205 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 10:25:51.998  4183  4205 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 10:25:51.998  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 10:25:51.998  4183  4205 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 10:25:52.134  4183  4205 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-16 10:25:52.134  4183  4205 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-16 10:25:52.142  4183  4199 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 10:25:52.144  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 10:25:52.145  4183  4199 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 10:25:52.147  4183  4199 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 10:25:52.150  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
,08-16 10:25:52.150  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 10:25:52.151  4183  4199 D bt_hci  : do_postload posting postload work item
,08-16 10:25:52.153  4183  4203 I bt_hci  : event_postload
08-16 10:25:52.153  4183  4203 I bt_vendor: sco_config_cb
08-16 10:25:52.153  4183  4203 I bt_hci  : sco_config_callback postload finished.
,08-16 10:25:52.155  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.156  4183  4199 D bt_bte_conf: Device ID record 1 : primary
08-16 10:25:52.156  4183  4199 D bt_bte_conf:   vendorId            = 000f
08-16 10:25:52.157  4183  4199 D bt_bte_conf:   vendorIdSource      = 0001
08-16 10:25:52.157  4183  4199 D bt_bte_conf:   product             = 1200
08-16 10:25:52.157  4183  4199 D bt_bte_conf:   version             = 1436
08-16 10:25:52.157  4183  4199 D bt_bte_conf:   clientExecutableURL = 
08-16 10:25:52.157  4183  4199 D bt_bte_conf:   serviceDescription  = 
08-16 10:25:52.158  4183  4199 D bt_bte_conf:   documentationURL    = 
08-16 10:25:52.158  4183  4199 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 10:25:52.159  4183  4203 I bt_vendor: low_power_mode_cb
,08-16 10:25:52.159  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.158  4183  4196 D bt_stack_manager: event_start_up_stack finished
,08-16 10:25:52.161  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 10:25:52.162  4183  4195 D BluetoothAdapterProperties: Setting state to 15
08-16 10:25:52.162  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 10:25:52.163  4183  4195 I BluetoothAdapterState: Entering BleOnState
08-16 10:25:52.164  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:52.168  4183  4195 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 10:25:52.168  4183  4195 D BluetoothAdapterProperties: Setting state to 11
08-16 10:25:52.169  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 10:25:52.174  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:52.175  4183  4183 D HeadsetService: Received start request. Starting profile...
08-16 10:25:52.179  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.181  4183  4183 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 10:25:52.181  4183  4183 D HeadsetStateMachine: make
,08-16 10:25:52.183  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.185  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
08-16 10:25:52.186  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:52.193  4183  4183 D HeadsetStateMachine: max_hf_connections = 1
,08-16 10:25:52.193  4183  4183 I bt_bluedroid: get_profile_interface handsfree
08-16 10:25:52.193  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 10:25:52.193  4183  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 10:25:52.198  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:52.199  4183  4183 D A2dpService: Received start request. Starting profile...
,08-16 10:25:52.199  4183  4183 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 10:25:52.200  4183  4183 I bt_bluedroid: get_profile_interface avrcp
,08-16 10:25:52.205  4183  4183 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 10:25:52.205  4183  4183 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 10:25:52.205  4183  4183 D A2dpStateMachine: make
,08-16 10:25:52.207  4183  4183 I bt_bluedroid: get_profile_interface a2dp
,08-16 10:25:52.207  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 10:25:52.211  4183  4217 D A2dpStateMachine: Enter Disconnected: -2
,08-16 10:25:52.211  4183  4183 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 10:25:52.212  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:52.213  4183  4183 D HidService: Received start request. Starting profile...
,08-16 10:25:52.214  4183  4183 I bt_bluedroid: get_profile_interface hidhost
08-16 10:25:52.214  3933  3933 D BluetoothInputDevice: Proxy object connected
,08-16 10:25:52.214  4183  4183 D HidService: setHidService(): set to: null
,08-16 10:25:52.214  4183  4199 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-16 10:25:52.214  4183  4183 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 10:25:52.214  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 10:25:52.215  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:25:52.215  3933  3933 D HidProfile: Bluetooth service connected
,08-16 10:25:52.216  4183  4183 D HealthService: Received start request. Starting profile...
,08-16 10:25:52.217  4183  4183 I bt_bluedroid: get_profile_interface health
08-16 10:25:52.218  4183  4183 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 10:25:52.218  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:52.219  4183  4183 D PanService: Received start request. Starting profile...
08-16 10:25:52.220  4183  4183 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 10:25:52.220  4183  4183 I bt_bluedroid: get_profile_interface pan
08-16 10:25:52.221  4183  4199 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 10:25:52.220  3933  3933 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 10:25:52.222  4183  4183 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:25:52.222  3933  3933 D PanProfile: Bluetooth service connected
08-16 10:25:52.223  4183  4183 D BluetoothMapService: Received start request. Starting profile...
08-16 10:25:52.223  4183  4183 D BluetoothMapService: start()
08-16 10:25:52.223  3933  3933 D BluetoothMap: Proxy object connected
08-16 10:25:52.224  3933  3933 D MapProfile: Bluetooth service connected
08-16 10:25:52.224  3933  3933 D BluetoothMap: getConnectedDevices()
08-16 10:25:52.225  3933  3933 D BluetoothMap: Bluetooth is Not enabled
08-16 10:25:52.225  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-16 10:25:52.226  4183  4183 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 10:25:52.226  4183  4183 D BluetoothMapAppObserver: createReceiver()
08-16 10:25:52.228  4183  4183 D BluetoothMapAppObserver: initObservers()
08-16 10:25:52.229  4183  4183 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 10:25:52.242  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:25:52.242  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-16 10:25:52.243  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.243  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.243  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.247  4183  4214 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.247  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.248  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:52.249  4183  4183 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:25:52.249  4183  4183 V BluetoothAdapterState: isTurningOn()=true
08-16 10:25:52.249  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:52.249  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:52.250  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 10:25:52.250  4183  4195 D BluetoothAdapterProperties: ScanMode =  20
,08-16 10:25:52.250  4183  4195 D BluetoothAdapterProperties: State =  11
,08-16 10:25:52.250  4183  4195 D BluetoothAdapterProperties: Setting state to 12
08-16 10:25:52.251  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 10:25:52.251  4183  4195 I BluetoothAdapterState: Entering OnState
08-16 10:25:52.252  3933  3943 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 10:25:52.253   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 10:25:52.253  4183  4199 D BluetoothAdapterProperties: Scan Mode:21
08-16 10:25:52.254  4183  4199 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:25:52.255  1929  1945 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:25:52.255   873   873 D BluetoothA2dp: Proxy object connected
,08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:52.258  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:52.256   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:25:52.259  1384  1397 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 10:25:52.260  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 10:25:52.261  4183  4183 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 10:25:52.261  1384  1399 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 10:25:52.262  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:52.263  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:25:52.264  1384  1384 D BluetoothA2dp: Proxy object connected
08-16 10:25:52.265  3933  3944 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 10:25:52.266  1384  2090 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 10:25:52.268  4183  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:52.268  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:52.269  1384  1384 D BluetoothInputDevice: Proxy object connected
,08-16 10:25:52.269  1384  1384 D HidProfile: Bluetooth service connected
,08-16 10:25:52.269  1384  2013 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:25:52.270  4183  4183 D ObexServerSockets: Succeed to create listening sockets 
08-16 10:25:52.270  1384  1399 D BluetoothPan: onBluetoothStateChange on: true
08-16 10:25:52.270  4183  4183 D ObexServerSockets0: startAccept()
08-16 10:25:52.270  4183  4183 D ObexServerSockets0: prepareForNewConnect()
08-16 10:25:52.272  1384  1384 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 10:25:52.272  1384  1384 D PanProfile: Bluetooth service connected
08-16 10:25:52.273  3933  3943 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 10:25:52.272  4183  4183 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 10:25:52.273  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:52.273  4183  4183 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 10:25:52.273  4183  4222 D ObexServerSockets0: Accepting socket connection...
08-16 10:25:52.274  1384  2013 D BluetoothMap: onBluetoothStateChange: up=true
08-16 10:25:52.275  4183  4223 D ObexServerSockets0: Accepting socket connection...
08-16 10:25:52.276  1384  1384 D BluetoothMap: Proxy object connected
,08-16 10:25:52.276  1384  1384 D MapProfile: Bluetooth service connected
,08-16 10:25:52.277  1384  1384 D BluetoothMap: getConnectedDevices()
,08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:52.277  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:52.277  3933  3944 D BluetoothPan: onBluetoothStateChange on: true
08-16 10:25:52.278   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:25:52.278   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:25:52.280   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 10:25:52.280  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:52.280  4183  4183 D BluetoothMapService: onReceive
08-16 10:25:52.281  4183  4183 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:25:52.281  4183  4183 D BluetoothMapService: STATE_ON
08-16 10:25:52.282  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.283  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:52.284  3933  3933 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 10:25:52.285  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:52.288  3933  3933 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 10:25:52.294  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 10:25:52.296  3933  3933 D BluetoothA2dp: Proxy object connected
,08-16 10:25:52.302  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 10:25:52.303  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:25:52.307  3933  3933 D BluetoothPbap: Proxy object connected
,08-16 10:25:52.307  1384  1384 D BluetoothPbap: Proxy object connected
08-16 10:25:52.308  1384  1384 D PbapServerProfile: Bluetooth service connected
08-16 10:25:52.308  3933  3933 D PbapServerProfile: Bluetooth service connected
08-16 10:25:52.308  4183  4183 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 10:25:52.308  4183  4183 D ObexServerSockets0: prepareForNewConnect()
,08-16 10:25:52.310  4183  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:25:52.329  4183  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:25:52.330  4183  4233 I BtOppRfcommListener: Accept thread started.
,08-16 10:25:52.358   873   873 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.358   873   890 D BluetoothHeadset: Proxy object connected
08-16 10:25:52.359   873   873 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.360  1384  1399 D BluetoothHeadset: Proxy object connected
08-16 10:25:52.361  1384  1384 D HeadsetProfile: Bluetooth service connected
,08-16 10:25:52.361   873   873 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.362  1929  2227 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.370  1384  1397 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.371  1384  1384 D HeadsetProfile: Bluetooth service connected
,08-16 10:25:52.378   873   890 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.378   873   890 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.391  3933  3943 D BluetoothHeadset: Proxy object connected
,08-16 10:25:52.393  3933  3933 D HeadsetProfile: Bluetooth service connected
,08-16 10:25:55.674  4183  4195 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 10:25:55.675  4183  4195 D BluetoothAdapterProperties: Setting state to 13
08-16 10:25:55.675  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 10:25:55.677  4183  4195 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 10:25:55.680  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-16 10:25:55.684  4183  4183 D BluetoothMapService: onReceive
,08-16 10:25:55.685  4183  4183 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 10:25:55.685  4183  4183 D BluetoothMapService: STATE_TURNING_OFF
08-16 10:25:55.685  4183  4183 D BluetoothMapService: MAP Service closeService in
08-16 10:25:55.685  4183  4183 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 10:25:55.685  4183  4183 D ObexServerSockets0: shutdown(block = true)
,08-16 10:25:55.686  4183  4183 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 10:25:55.686  4183  4183 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 10:25:55.686  4183  4222 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 10:25:55.687  4183  4210 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 10:25:55.687  4183  4223 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 10:25:55.690  4183  4183 I BtOppRfcommListener: stopping Accept Thread
08-16 10:25:55.690  4183  4233 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 10:25:55.691  4183  4233 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 10:25:55.694  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:25:55.694  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 10:25:55.694  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:55.696  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:25:55.698  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.698  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:55.701  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:55.702  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:55.703  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.703  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:25:55.708  4183  4183 D HeadsetService: Received stop request...Stopping profile...
08-16 10:25:55.710  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 10:25:55.713  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:25:55.713  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:25:55.714   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:55.714   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 10:25:55.714  3834  3834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 10:25:55.714  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:25:55.714  1384  2090 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:55.714   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:55.714  4183  4183 D A2dpService: Received stop request...Stopping profile...
08-16 10:25:55.715  1929  1944 D BluetoothHeadset: Proxy object disconnected
08-16 10:25:55.715  4183  4217 D A2dpStateMachine: Exit Disconnected: -1
08-16 10:25:55.716  1384  1384 D HeadsetProfile: Bluetooth service disconnected
08-16 10:25:55.716  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:55.718  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:55.718  3933  3943 D BluetoothHeadset: Proxy object disconnected
,08-16 10:25:55.718   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 10:25:55.719  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:55.720  1384  1384 D BluetoothA2dp: Proxy object disconnected
08-16 10:25:55.720  4183  4183 D HidService: Received stop request...Stopping profile...
08-16 10:25:55.720  4183  4183 D HidService: Stopping Bluetooth HidService
,08-16 10:25:55.722  1384  1384 D BluetoothInputDevice: Proxy object disconnected
08-16 10:25:55.722  1384  1384 D HidProfile: Bluetooth service disconnected
08-16 10:25:55.722  4183  4183 D HealthService: Received stop request...Stopping profile...
08-16 10:25:55.723  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-16 10:25:55.723  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:55.723  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.723  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:55.724  4183  4183 D PanService: Received stop request...Stopping profile...
08-16 10:25:55.725  1384  1384 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 10:25:55.725  1384  1384 D PanProfile: Bluetooth service disconnected
08-16 10:25:55.726  3933  3933 D DockEventReceiver: finishStartingService: stopping service
08-16 10:25:55.726  4183  4183 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 10:25:55.727  4183  4183 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 10:25:55.727  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 10:25:55.727  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.727  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.727  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.727  4183  4199 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 10:25:55.727  3933  3933 D HeadsetProfile: Bluetooth service disconnected
,08-16 10:25:55.728  3933  3933 D BluetoothA2dp: Proxy object disconnected
08-16 10:25:55.728  3933  3933 D BluetoothInputDevice: Proxy object disconnected
08-16 10:25:55.728  3933  3933 D HidProfile: Bluetooth service disconnected
08-16 10:25:55.728  4183  4183 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:55.728  4183  4183 V BluetoothAdapterState: isTurningOn()=false
,08-16 10:25:55.728  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.728  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 10:25:55.731  4183  4183 D BluetoothMapService: Received stop request...Stopping profile...
08-16 10:25:55.731  4183  4183 D BluetoothMapService: stop()
,08-16 10:25:55.732  4183  4183 D BluetoothMapAppObserver: deinitObservers()
08-16 10:25:55.732  4183  4183 D BluetoothMapAppObserver: removeReceiver()
08-16 10:25:55.732  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:25:55.733  3933  3933 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 10:25:55.734  3933  3933 D PanProfile: Bluetooth service disconnected
,08-16 10:25:55.736  1384  1384 D BluetoothMap: Proxy object disconnected,
,08-16 10:25:55.736  1384  1384 D MapProfile: Bluetooth service disconnected
,08-16 10:25:55.736  3933  3933 D BluetoothMap: Proxy object disconnected
08-16 10:25:55.737  3933  3933 D MapProfile: Bluetooth service disconnected
08-16 10:25:55.737  4183  4183 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:55.737  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.737  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:55.737  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.737  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.738  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:55.738  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 10:25:55.738  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:25:55.738  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 10:25:55.738  4183  4183 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 10:25:55.738  4183  4205 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 10:25:55.738  4183  4183 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 10:25:55.738  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 10:25:55.738  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-16 10:25:55.738  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:55.738  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.738  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:55.738  4183  4199 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 10:25:55.738  4183  4183 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 10:25:55.739  4183  4199 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 10:25:55.739  4183  4183 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 10:25:55.739  4183  4183 V BluetoothAdapterState: isTurningOff()=true
08-16 10:25:55.739  4183  4183 V BluetoothAdapterState: isTurningOn()=false
,08-16 10:25:55.739  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.739  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:55.740  4183  4183 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 10:25:55.740  4183  4183 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 10:25:55.742  1384  1384 D BluetoothPbap: Proxy object disconnected
,08-16 10:25:55.742  1384  1384 D PbapServerProfile: Bluetooth service disconnected
08-16 10:25:55.743  4183  4183 D BluetoothMapService: MAP Service closeService in
08-16 10:25:55.743  4183  4183 V BluetoothAdapterState: isTurningOff()=true
,08-16 10:25:55.743  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:55.743  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:25:55.743  4183  4183 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:25:55.743  3933  3933 D BluetoothPbap: Proxy object disconnected
08-16 10:25:55.743  3933  3933 D PbapServerProfile: Bluetooth service disconnected
08-16 10:25:55.743  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 10:25:55.743  4183  4195 D BluetoothAdapterProperties: Setting state to 15
08-16 10:25:55.743  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 10:25:55.744  4183  4195 I BluetoothAdapterState: Entering BleOnState
08-16 10:25:55.745  4183  4183 D BluetoothMapService: cleanup()
08-16 10:25:55.745  4183  4183 D BluetoothMapService: MAP Service closeService in
,08-16 10:25:55.748  3933  3944 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 10:25:55.749   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:25:55.749  3933  3943 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:55.749  1929  2226 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 10:25:55.750   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:55.750  3933  3944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:25:55.751  1384  1397 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 10:25:55.751  1384  2090 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 10:25:55.752  3933  3943 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 10:25:55.753  1384  2013 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 10:25:55.753  1384  1399 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:55.754  1384  1397 D BluetoothPan: onBluetoothStateChange on: false
08-16 10:25:55.754  3933  3944 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 10:25:55.755  1384  2090 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 10:25:55.756  3933  3943 D BluetoothPan: onBluetoothStateChange on: false
08-16 10:25:55.756   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 10:25:55.756   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 10:25:55.756  4183  4195 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 10:25:55.756  4183  4195 D BluetoothAdapterProperties: Setting state to 16
,08-16 10:25:55.757  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 10:25:55.757  4183  4195 D BluetoothAdapterProperties: onBleDisable
08-16 10:25:55.758  4183  4195 I BluetoothAdapterState: Entering PendingCommandState
,08-16 10:25:55.758  4183  4196 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 10:25:55.759  4183  4205 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 10:25:55.759  4183  4205 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 10:25:55.760  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:55.760  4183  4199 D BluetoothAdapterProperties: Scan Mode:20
08-16 10:25:55.761  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:55.762  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 10:25:55.762  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:55.766  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:55.768  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:25:55.769  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:25:55.770  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:25:55.775  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:25:55.965  4183  4199 I bt_hci  : shut_down
,08-16 10:25:55.974  4183  4203 I bt_vendor: low_power_mode_cb
,08-16 10:25:55.974  4183  4203 D bt_hwcfg: hw_epilog_process
,08-16 10:25:56.000  4183  4203 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 10:25:56.001  4183  4203 I bt_vendor: epilog_cb
08-16 10:25:56.001  4183  4203 I bt_hci  : epilog_finished_callback
,08-16 10:25:56.008  4183  4199 I bt_hci_h4: hal_close
,08-16 10:25:56.010  4183  4199 I bt_userial_vendor: device fd = 51 close
,08-16 10:25:56.134  4183  4196 D bt_stack_manager: event_shut_down_stack finished.
,08-16 10:25:56.135  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 10:25:56.143  4183  4183 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 10:25:56.143  4183  4195 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 10:25:56.146  4183  4183 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 10:25:56.146  4183  4183 D BtGatt.GattService: stop()
,08-16 10:25:56.147  4183  4183 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 10:25:56.152  4183  4183 V BluetoothAdapterState: isTurningOff()=false
08-16 10:25:56.152  4183  4183 V BluetoothAdapterState: isTurningOn()=false
08-16 10:25:56.153  4183  4183 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 10:25:56.153  4183  4183 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 10:25:56.154  4183  4195 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 10:25:56.154  4183  4195 D BluetoothAdapterProperties: Setting state to 10
,08-16 10:25:56.155  4183  4195 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 10:25:56.156  4183  4195 I BluetoothAdapterState: Entering OffState
08-16 10:25:56.158   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 10:25:56.184  4183  4183 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 10:25:56.185  4183  4183 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 10:25:56.188  4183  4196 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 10:25:56.189  4183  4183 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 10:25:56.201  4183  4196 D bt_stack_manager: event_clean_up_stack finished.
,08-16 10:25:56.205  4183  4183 I art     : System.exit called, status: 0
,08-16 10:25:56.205  4183  4183 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 10:25:56.278   873  1939 I ActivityManager: Process com.android.bluetooth (pid 4183) has died
,08-16 10:25:59.438  1864  1966 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 10:25:59.438  1864  1966 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 10:25:59.489  1525  1525 I ConfigService: onCreate
,08-16 10:26:00.674  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:26:00.674  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:26:04.571  1525  1525 I ConfigService: onDestroy
,08-16 10:26:05.679  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:26:05.680  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b60226 removed from the list
08-16 10:26:05.680  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:26:05.680  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:05.681  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:26:05.684  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:05.684  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d9d414 added. We now have 4 listener(s)
08-16 10:26:05.685  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:05.686  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:05.687  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d9d414 removed from the list
08-16 10:26:05.687  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 10:26:05.687  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:05.688  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:05.690  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:05.690  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d594bd added. We now have 4 listener(s)
,08-16 10:26:05.691  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:07.698  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:07.749   873   890 I ActivityManager: Start proc 4243:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 10:26:07.890  4243  4243 D AdapterServiceConfig: Adding HeadsetService
08-16 10:26:07.890  4243  4243 D AdapterServiceConfig: Adding A2dpService
08-16 10:26:07.890  4243  4243 D AdapterServiceConfig: Adding HidService
08-16 10:26:07.891  4243  4243 D AdapterServiceConfig: Adding HealthService
08-16 10:26:07.891  4243  4243 D AdapterServiceConfig: Adding PanService
08-16 10:26:07.891  4243  4243 D AdapterServiceConfig: Adding GattService
08-16 10:26:07.891  4243  4243 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 10:26:07.905   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13bb85f:true
08-16 10:26:07.906  4243  4243 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 10:26:07.913  4243  4243 I bt_bluedroid: init,
08-16 10:26:07.913  4243  4255 I BluetoothAdapterState: Entering OffState
,08-16 10:26:07.917  4243  4256 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 10:26:07.917  4243  4256 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 10:26:07.917  4243  4256 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 10:26:07.918  4243  4256 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 10:26:07.919  4243  4243 I bt_bluedroid: get_profile_interface socket
,08-16 10:26:07.921  4243  4243 I bt_bluedroid: get_profile_interface sdp
,08-16 10:26:07.924  4243  4253 I bt_bluedroid: config_hci_snoop_log
,08-16 10:26:07.926   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 10:26:07.937  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 10:26:07.938  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 10:26:07.940  4243  4255 D BluetoothAdapterState: Current state: OFF, message: 0
08-16 10:26:07.941  4243  4255 D BluetoothAdapterProperties: Setting state to 14
,08-16 10:26:07.941  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 10:26:07.942  4243  4255 D BluetoothBondStateMachine: make
08-16 10:26:07.944  4243  4260 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 10:26:07.948  4243  4243 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 10:26:07.950  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-16 10:26:07.951  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:26:07.952  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 10:26:07.953  4243  4243 D BtGatt.GattService: Received start request. Starting profile...
08-16 10:26:07.953  4243  4243 D BtGatt.GattService: start()
08-16 10:26:07.953  4243  4243 I bt_bluedroid: get_profile_interface gatt
08-16 10:26:07.954  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:26:07.954  4243  4243 D BtGatt.AdvertiseManager: advertise manager created
,08-16 10:26:07.961  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:26:07.961  4243  4243 V BluetoothAdapterState: isTurningOn()=false
08-16 10:26:07.961  4243  4243 V BluetoothAdapterState: isBleTurningOn()=true
08-16 10:26:07.961  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:26:07.961  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 10:26:07.962  4243  4255 I bt_bluedroid: enable
08-16 10:26:07.962  4243  4256 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 10:26:07.963  4243  4256 I bt_hci  : start_up
,08-16 10:26:07.970  4243  4256 I bt_vendor: alloc value 0xb399c189
,08-16 10:26:07.970  4243  4256 I bt_vendor: init
08-16 10:26:07.970  4243  4256 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 10:26:07.970  4243  4256 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 10:26:08.078  4243  4256 D bt_hci  : start_up starting async portion
,08-16 10:26:08.078  4243  4263 I bt_hci  : event_finish_startup
08-16 10:26:08.078  4243  4263 I bt_hci_h4: hal_open
08-16 10:26:08.079  4243  4263 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 10:26:08.088  4243  4263 I bt_userial_vendor: device fd = 51 open
,08-16 10:26:08.122  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 10:26:08.153  4243  4263 D bt_hwcfg: Chipset BCM4354A2
08-16 10:26:08.153  4243  4263 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 10:26:08.154  4243  4263 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 10:26:08.938  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 10:26:08.940  4243  4263 D bt_hwcfg: Settlement delay -- 100 ms
08-16 10:26:08.940  4243  4263 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 10:26:09.058  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 10:26:09.060  4243  4263 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 10:26:09.087  4243  4263 I bt_hwcfg: vendor lib fwcfg completed
,08-16 10:26:09.087  4243  4263 I bt_vendor: firmware callback
08-16 10:26:09.088  4243  4263 I bt_hci  : firmware_config_callback
,08-16 10:26:09.101  4243  4267 I bt_btu  : btu_task pending for preload complete event
,08-16 10:26:09.102  4243  4267 I bt_btu_task: Bluetooth chip preload is complete
08-16 10:26:09.102  4243  4267 I bt_btu  : btu_task received preload complete event
,08-16 10:26:09.113  4243  4267 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 10:26:09.114  4243  4267 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 10:26:09.114  4243  4267 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 10:26:09.114  4243  4267 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 10:26:09.114  4243  4267 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 10:26:09.115  4243  4267 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 10:26:09.115  4243  4267 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 10:26:09.115  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 10:26:09.115  4243  4267 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 10:26:09.116  4243  4267 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 10:26:09.116  4243  4267 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 10:26:09.116  4243  4267 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 10:26:09.117  4243  4267 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 10:26:09.117  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 10:26:09.117  4243  4267 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 10:26:09.270  4243  4267 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
08-16 10:26:09.270  4243  4267 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-16 10:26:09.281  4243  4259 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 10:26:09.284  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 10:26:09.285  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 10:26:09.291  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6,
,08-16 10:26:09.297  4243  4259 D BluetoothAdapterProperties: Scan Mode:20
,08-16 10:26:09.297  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 10:26:09.298  4243  4259 D bt_hci  : do_postload posting postload work item
,08-16 10:26:09.298  4243  4263 I bt_hci  : event_postload
08-16 10:26:09.299  4243  4263 I bt_vendor: sco_config_cb
,08-16 10:26:09.299  4243  4263 I bt_hci  : sco_config_callback postload finished.
08-16 10:26:09.304  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:26:09.305  4243  4263 I bt_vendor: low_power_mode_cb
08-16 10:26:09.307  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:26:09.307  4243  4259 D bt_bte_conf: Device ID record 1 : primary
08-16 10:26:09.307  4243  4259 D bt_bte_conf:   vendorId            = 000f
,08-16 10:26:09.307  4243  4259 D bt_bte_conf:   vendorIdSource      = 0001
08-16 10:26:09.308  4243  4259 D bt_bte_conf:   product             = 1200
08-16 10:26:09.308  4243  4259 D bt_bte_conf:   version             = 1436
08-16 10:26:09.308  4243  4259 D bt_bte_conf:   clientExecutableURL = 
,08-16 10:26:09.308  4243  4259 D bt_bte_conf:   serviceDescription  = 
08-16 10:26:09.308  4243  4259 D bt_bte_conf:   documentationURL    = 
,08-16 10:26:09.309  4243  4259 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 10:26:09.309  4243  4256 D bt_stack_manager: event_start_up_stack finished
08-16 10:26:09.311  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 10:26:09.312  4243  4255 D BluetoothAdapterProperties: Setting state to 15
08-16 10:26:09.312  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 10:26:09.313  4243  4255 I BluetoothAdapterState: Entering BleOnState
,08-16 10:26:09.321  4243  4255 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 10:26:09.322  4243  4255 D BluetoothAdapterProperties: Setting state to 11
08-16 10:26:09.322  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 10:26:09.331  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:09.335  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:09.340  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:26:09.342  4243  4243 D HeadsetService: Received start request. Starting profile...
,08-16 10:26:09.349  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-16 10:26:09.352  4243  4243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 10:26:09.352  4243  4243 D HeadsetStateMachine: make
,08-16 10:26:09.363  4243  4243 D HeadsetStateMachine: max_hf_connections = 1
,08-16 10:26:09.364  4243  4243 I bt_bluedroid: get_profile_interface handsfree
08-16 10:26:09.364  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 10:26:09.364  4243  4259 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 10:26:09.370  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:26:09.371  4243  4243 D A2dpService: Received start request. Starting profile...
,08-16 10:26:09.372  4243  4243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 10:26:09.372  4243  4243 I bt_bluedroid: get_profile_interface avrcp
,08-16 10:26:09.372  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:26:09.381  4243  4243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 10:26:09.381  4243  4243 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 10:26:09.382  4243  4243 D A2dpStateMachine: make
,08-16 10:26:09.384  4243  4243 I bt_bluedroid: get_profile_interface a2dp
,08-16 10:26:09.385  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 10:26:09.390  4243  4276 D A2dpStateMachine: Enter Disconnected: -2
,08-16 10:26:09.391  4243  4243 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 10:26:09.392  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:26:09.393  4243  4243 D HidService: Received start request. Starting profile...
08-16 10:26:09.393  4243  4243 I bt_bluedroid: get_profile_interface hidhost
08-16 10:26:09.394  4243  4259 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
,08-16 10:26:09.394  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 10:26:09.394  4243  4243 D HidService: setHidService(): set to: null
08-16 10:26:09.395  4243  4243 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 10:26:09.396  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:26:09.397  4243  4243 D HealthService: Received start request. Starting profile...
,08-16 10:26:09.399  4243  4243 I bt_bluedroid: get_profile_interface health
,08-16 10:26:09.401  4243  4243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 10:26:09.402  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:26:09.402  4243  4243 D PanService: Received start request. Starting profile...
,08-16 10:26:09.403  4243  4243 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 10:26:09.403  4243  4243 I bt_bluedroid: get_profile_interface pan
,08-16 10:26:09.404  4243  4259 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 10:26:09.407  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
08-16 10:26:09.407  4243  4243 D BluetoothMapService: Received start request. Starting profile...
08-16 10:26:09.408  4243  4243 D BluetoothMapService: start()
,08-16 10:26:09.411  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 10:26:09.412  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 10:26:09.413  4243  4243 D BluetoothMapAppObserver: createReceiver()
,08-16 10:26:09.415  4243  4243 D BluetoothMapAppObserver: initObservers()
08-16 10:26:09.415  4243  4243 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 10:26:09.434  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-16 10:26:09.434  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-16 10:26:09.435  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:26:09.435  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 10:26:09.439  4243  4274 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-16 10:26:09.440  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-16 10:26:09.441  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:26:09.442  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:26:09.442  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-16 10:26:09.442  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,08-16 10:26:09.442  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-16 10:26:09.442  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-16 10:26:09.442  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 10:26:09.442  4243  4255 D BluetoothAdapterProperties: ScanMode =  20
08-16 10:26:09.442  4243  4255 D BluetoothAdapterProperties: State =  11
08-16 10:26:09.443  4243  4255 D BluetoothAdapterProperties: Setting state to 12
08-16 10:26:09.443  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 10:26:09.444  4243  4255 I BluetoothAdapterState: Entering OnState
08-16 10:26:09.444  4243  4259 D BluetoothAdapterProperties: Scan Mode:21
,08-16 10:26:09.444  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 10:26:09.445  3933  3944 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:09.450  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 10:26:09.451  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 10:26:09.451   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 10:26:09.452  4243  4243 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 10:26:09.453  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:26:09.453  3933  3943 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:26:09.454  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:26:09.455  1929  2088 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:26:09.456   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:26:09.457  3933  3944 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 10:26:09.459  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:09.459  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:26:09.461  1384  2090 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 10:26:09.461  4243  4243 D ObexServerSockets: Succeed to create listening sockets 
08-16 10:26:09.461  4243  4243 D ObexServerSockets0: startAccept()
08-16 10:26:09.461  4243  4243 D ObexServerSockets0: prepareForNewConnect()
08-16 10:26:09.463  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:26:09.463  1384  2013 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 10:26:09.464  4243  4243 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 10:26:09.464  4243  4243 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 10:26:09.466  3933  3944 D BluetoothMap: onBluetoothStateChange: up=true
08-16 10:26:09.466   873   873 D BluetoothA2dp: Proxy object connected
08-16 10:26:09.467  1384  1384 D BluetoothA2dp: Proxy object connected
,08-16 10:26:09.467  3933  3933 D BluetoothInputDevice: Proxy object connected
08-16 10:26:09.467  3933  3933 D HidProfile: Bluetooth service connected
08-16 10:26:09.469  4243  4281 D ObexServerSockets0: Accepting socket connection...
08-16 10:26:09.469  4243  4282 D ObexServerSockets0: Accepting socket connection...
08-16 10:26:09.469  1384  1397 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 10:26:09.472  1384  1384 D BluetoothInputDevice: Proxy object connected
08-16 10:26:09.472  1384  1384 D HidProfile: Bluetooth service connected
,08-16 10:26:09.472  1384  1399 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:26:09.474  1384  2090 D BluetoothPan: onBluetoothStateChange on: true
,08-16 10:26:09.474  3933  3933 D BluetoothA2dp: Proxy object connected
,08-16 10:26:09.477  3933  3944 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 10:26:09.477  3933  3933 D BluetoothMap: Proxy object connected
08-16 10:26:09.477  3933  3933 D MapProfile: Bluetooth service connected
08-16 10:26:09.477  1384  1384 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 10:26:09.477  1384  1384 D PanProfile: Bluetooth service connected
08-16 10:26:09.477  3933  3933 D BluetoothMap: getConnectedDevices()
,08-16 10:26:09.478  1384  2013 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 10:26:09.480  3933  3943 D BluetoothPan: onBluetoothStateChange on: true
08-16 10:26:09.480  1384  1384 D BluetoothMap: Proxy object connected
,08-16 10:26:09.480  1384  1384 D MapProfile: Bluetooth service connected
08-16 10:26:09.480  1384  1384 D BluetoothMap: getConnectedDevices()
,08-16 10:26:09.482   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 10:26:09.482   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 10:26:09.484   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 10:26:09.486  4243  4243 D BluetoothMapService: onReceive
08-16 10:26:09.486  4243  4243 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 10:26:09.486  4243  4243 D BluetoothMapService: STATE_ON
08-16 10:26:09.487  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:09.487  3933  3933 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 10:26:09.487  3933  3933 D PanProfile: Bluetooth service connected
08-16 10:26:09.488  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:09.492  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 10:26:09.498  1525  1525 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 10:26:09.504  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,08-16 10:26:09.507  3933  3933 D BluetoothPbap: Proxy object connected
08-16 10:26:09.507  3933  3933 D PbapServerProfile: Bluetooth service connected
,08-16 10:26:09.513  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 10:26:09.514  4243  4243 D ObexServerSockets0: prepareForNewConnect()
08-16 10:26:09.516  1384  1384 D BluetoothPbap: Proxy object connected
08-16 10:26:09.516  1384  1384 D PbapServerProfile: Bluetooth service connected
,08-16 10:26:09.520  4243  4288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:26:09.538  4243  4292 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:26:09.539  4243  4292 I BtOppRfcommListener: Accept thread started.
,08-16 10:26:09.556   873   873 D BluetoothHeadset: Proxy object connected
,08-16 10:26:09.556   873   873 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.556  1929  1945 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.557  1384  1399 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.557   873   890 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.557  1384  1384 D HeadsetProfile: Bluetooth service connected
08-16 10:26:09.557   873   873 D BluetoothHeadset: Proxy object connected
,08-16 10:26:09.557  1929  2227 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.559  3933  4283 D BluetoothHeadset: Proxy object connected
,08-16 10:26:09.559  3933  3933 D HeadsetProfile: Bluetooth service connected
,08-16 10:26:09.573  1384  2090 D BluetoothHeadset: Proxy object connected
,08-16 10:26:09.574  1384  1384 D HeadsetProfile: Bluetooth service connected
,08-16 10:26:09.583   873   890 D BluetoothHeadset: Proxy object connected
08-16 10:26:09.583   873   890 D BluetoothHeadset: Proxy object connected
,08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:09.713  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:26:09.724  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:26:09.725  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:26:09.725  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d594bd removed from the list
08-16 10:26:09.726  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:26:09.726  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:26:09.726  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:09.729  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:09.729  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2701ab2 added. We now have 4 listener(s)
08-16 10:26:09.730  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:09.736   873   884 D WifiService: setWifiEnabled: false pid=3834, uid=10000
,08-16 10:26:09.737   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:26:09.750  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:09.751   873  1994 D WifiService: setWifiEnabled: true pid=3834, uid=10000
08-16 10:26:09.752   873  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 10:26:09.762   873  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:09.780  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:26:09.790  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:09.800  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:26:09.807   873  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-16 10:26:09.807  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 10:26:09.807   873  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 10:26:09.808   873  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 10:26:09.809   873  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 10:26:09.810   873  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 10:26:09.810   873  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 10:26:09.810   873  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 10:26:09.829   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 10:26:09.829   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 10:26:09.831   371   871 D CommandListener: Setting iface cfg
,08-16 10:26:09.883   873  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 10:26:09.884   873  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 10:26:09.892   873  1318 E native  : do suspend true
,08-16 10:26:09.907   873  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 10:26:09.908   873  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 10:26:09.940   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:26:11.308   873  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 10:26:11.444   873  1318 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=9.81 delta 1000 -> 994
,08-16 10:26:11.446   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 10:26:11.446   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:26:11.460   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 10:26:11.506   873  1318 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 10:26:11.508  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 10:26:11.772  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 10:26:11.780  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 10:26:11.781  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:11.782  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2701ab2 removed from the list
,08-16 10:26:11.782  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:26:11.782  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:11.783  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:26:11.935  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 10:26:11.980  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 10:26:11.982  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 10:26:11.991   873  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 10:26:12.007   873  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 10:26:12.008   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 10:26:12.008   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 10:26:12.025   873  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 10:26:12.037   371   871 D CommandListener: Setting iface cfg
,08-16 10:26:12.040   873  1318 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 10:26:12.054   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 10:26:12.082   873  4300 D DhcpClient: Receive thread started
,08-16 10:26:12.167   873  1318 E native  : do suspend false
,08-16 10:26:12.187   873  1859 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 10:26:12.201   873  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172770, domain null
,08-16 10:26:12.202   873  1859 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172770 seconds
,08-16 10:26:12.207   873  1859 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 10:26:12.220   873  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 10:26:12.221   873  1859 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 10:26:12.227   371   871 D CommandListener: Setting iface cfg
,08-16 10:26:12.240   873  1859 D DhcpClient: Scheduling renewal in 86399s
,08-16 10:26:12.241   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-16 10:26:12.244   873  1318 E native  : do suspend true
,08-16 10:26:12.268   873  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 10:26:12.272   873  1318 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 10:26:12.274   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 10:26:12.277   873  1320 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 10:26:12.287   873  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 10:26:12.340   873  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 10:26:12.340   873  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 10:26:12.345   873  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 10:26:12.350   873  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 10:26:12.355   873  1320 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 10:26:12.368   873  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 10:26:12.372   873  1320 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-16 10:26:12.372   873  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 10:26:12.373   873  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 10:26:12.373   873  1320 D ConnectivityService:    accepting network in place of null
,08-16 10:26:12.373   873  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 10:26:12.374   873  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 10:26:12.378   873  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 10:26:12.386   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=226020, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 10:26:12.403   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:26:12.453   873  4298 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.238,2a00:1450:4001:807::200e
,08-16 10:26:12.455   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 10:26:12.463   873  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 10:26:12.463   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:26:12.471   873  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 10:26:12.472   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:26:12.483  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:26:12.487  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:26:12.495  3834  3834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:26:12.498  3834  3834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:26:12.514  2027  2027 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 10:26:12.517  1754  1754 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 10:26:12.519   873  4298 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 08:26:12 GMT], X-Android-Received-Millis=[1471335972519], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471335972494]}
,08-16 10:26:12.522   873  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 10:26:12.522   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 10:26:12.522  1754  1754 D SystemUpdateService: onCreate
08-16 10:26:12.522   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 10:26:12.524   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 10:26:12.527  1754  1754 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 10:26:12.586  1754  1754 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 10:26:12.645  1754  4311 I SystemUpdateService: active receiver: enabled
,08-16 10:26:12.649  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:12.651  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:12.666  1754  1754 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 10:26:12.668  1754  1754 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 10:26:12.671  1754  2420 I iu.UploadsManager: num queued entries: 0
,08-16 10:26:12.672  1754  2420 I iu.UploadsManager: num updated entries: 0
,08-16 10:26:12.673  1754  2420 I iu.SyncManager: NEXT; no task
08-16 10:26:12.676  1754  4311 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 10:26:12.684  4013  4013 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 10:26:12.704  1525  2444 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:26:12.704  1525  2444 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 10:26:12.704  1525  2444 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:12.704  1525  2444 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:12.710  1754  4314 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 10:26:12.710  1754  4314 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 10:26:12.721  4013  4013 D SprintDMHelper: simOperator: 
,08-16 10:26:12.721  4013  4013 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-16 10:26:12.722  1754  4314 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 10:26:12.723  1754  4311 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 10:26:12.723  1754  4311 I SystemUpdateService: now status is 0 (complete)
,08-16 10:26:12.723  1754  4311 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 10:26:12.727  1754  4311 I SystemUpdateService: file has been verified
,08-16 10:26:12.732  3003  4313 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 10:26:12.732  3003  4313 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at blb.a(PG:3937)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at czp.a(PG:18188)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:26:12.732  3003  4313 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	... 12 more
08-16 10:26:12.732  3003  4313 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at fal.a(PG:38)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	at jdj.a(PG:4089)
08-16 10:26:12.732  3003  4313 E HttpOperation: 	... 14 more
,08-16 10:26:12.766  1754  4311 I SystemUpdateService: OTA package size = 12249756
,08-16 10:26:12.792  1525  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:26:12.792  1525  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 10:26:12.792  1525  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:12.792  1525  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:12.814  1754  4311 I SystemUpdateService: showing system update notification
,08-16 10:26:12.817  3003  4313 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 10:26:12.817  3003  4313 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at hec.a(PG:42)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at hee.a(PG:102)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at czr.a(PG:65)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at kka.a(PG:108)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at czp.a(PG:19176)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:26:12.817  3003  4313 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	... 15 more
08-16 10:26:12.817  3003  4313 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at fal.a(PG:38)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	at jdj.a(PG:4089)
08-16 10:26:12.817  3003  4313 E HttpOperation: 	... 17 more
,08-16 10:26:12.817  3003  4313 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 10:26:12.817  3003  4313 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at hec.a(PG:42)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at hee.a(PG:102)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at czr.a(PG:65)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at kka.a(PG:108)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	... 15 more
08-16 10:26:12.817  3003  4313 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at fal.a(PG:38)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 10:26:12.817  3003  4313 E ExperimentLoader: 	... 17 more
,08-16 10:26:12.872  1754  1754 D SystemUpdateService: onDestroy
,08-16 10:26:12.887  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 10:26:12.888  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 10:26:12.888  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 10:26:12.888  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:12.908  3983  4317 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 10:26:12.972   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 221017, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:26:13.002  1754  4314 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-16 10:26:13.463   873  1320 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 10:26:16.795  3834  4324 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-16 10:26:16.796  3834  4324 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 10:26:19.803  3834  4325 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 10:26:19.804  3834  4324 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 10:26:19.809  3834  4325 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 10:26:19.809  3834  4324 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 10:26:19.811  3834  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:26:19.811  3834  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:26:19.812  3834  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:26:19.815  3834  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Sender)
,08-16 10:26:19.815  3834  4325 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 10:26:19.817  3834  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:26:19.820  3834  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Receiver)
,08-16 10:26:19.821  3834  4324 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 10:26:19.823  3834  4328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 424, thread name: IncomingSocketThread/Receiver)
08-16 10:26:19.823  3834  4328 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 10:26:19.824  3834  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 424, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 10:26:19.825  3834  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: OutgoingSocketThread/Sender)
08-16 10:26:19.827  3834  4330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Receiver)
,08-16 10:26:19.828  3834  4330 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: OutgoingSocketThread/Receiver)
,08-16 10:26:19.829  3834  4330 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 10:26:19.829  3834  4330 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192,
,08-16 10:26:20.380   873  1320 D ConnectivityService: handlePromptUnvalidated 102
,08-16 10:26:27.804  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 10:26:27.806  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 10:26:27.812  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@90cc734 Bundle[{}]
,08-16 10:26:27.814  3834  3884 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 10:26:27.815  3834  3884 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 10:26:27.817  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 10:26:27.819  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 10:26:27.822  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 10:26:27.822  3834  3884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 10:26:37.839  3834  3884 I System.out: Running OutgoingSocketThread
,08-16 10:26:37.844  3834  4333 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 10:26:37.845  3834  4333 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 10:26:39.801   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253434, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 10:26:40.853  3834  4334 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 10:26:40.854  3834  4334 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:26:40.854  3834  4334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:26:40.855  3834  4333 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-16 10:26:40.855  3834  4333 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 10:26:40.855  3834  4334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 10:26:40.856  3834  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:26:40.861  3834  4334 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 10:26:40.865  3834  4336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Sender)
,08-16 10:26:40.866  3834  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:26:40.867  3834  4337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Receiver)
,08-16 10:26:40.869  3834  4337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: IncomingSocketThread/Receiver)
08-16 10:26:40.869  3834  4337 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-16 10:26:40.869  3834  4337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 10:26:40.869  3834  4333 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 10:26:40.874  3834  4338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: OutgoingSocketThread/Sender)
,08-16 10:26:40.875  3834  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Receiver)
,08-16 10:26:40.877  3834  4339 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: OutgoingSocketThread/Receiver)
08-16 10:26:40.878  3834  4339 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 10:26:40.878  3834  4339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 10:26:43.302  3607  4341 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 10:26:43.351  3607  4342 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 10:26:43.368  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:43.369  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:43.406  3626  4340 V KeepSync: Connecting to GoogleApiClient
,08-16 10:26:43.406   873  1939 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-16 10:26:43.407  1525  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 10:26:43.407  1525  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 10:26:43.407  1525  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:43.407  1525  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:43.448  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:43.464  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:26:43.540  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 10:26:43.540  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 10:26:43.540  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:43.540  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:43.590  1525  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 10:26:43.590  1525  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 10:26:43.590  1525  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:43.591  1525  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 10:26:43.593  3607  4342 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 10:26:43.594  3607  4341 E BooksSync: Soft error
08-16 10:26:43.594  3607  4341 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 10:26:43.594  3607  4341 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 10:26:43.594  3607  4341 E BooksSync: Sync error
08-16 10:26:43.594  3607  4341 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 10:26:43.594  3607  4341 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 10:26:43.597  3607  4341 I BooksSync: Finished books sync
,08-16 10:26:43.610   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 251633, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:26:43.614  1754  4343 V BaseAuthAsyncOperation: access token request failed
,08-16 10:26:43.615  3626  4340 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 10:26:43.678  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 10:26:43.678  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 10:26:43.678  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:26:43.678  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:26:43.699  3626  4340 E KeepSync: IOException
08-16 10:26:43.699  3626  4340 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 10:26:43.699  3626  4340 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:26:43.699  3626  4340 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 10:26:43.699  3626  4340 E KeepSync: 	... 10 more
,08-16 10:26:43.699  3626  4340 W KeepSync: Sync result 2
,08-16 10:26:43.705   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 250278, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:26:48.858  3834  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,08-16 10:26:48.860  3834  3884 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 10:26:48.860  3834  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,08-16 10:26:53.870  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:26:53.870  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@989ca03 added. We now have 3 listener(s)
,08-16 10:26:53.877  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 10:26:53.878  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:26:53.878  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:26:53.879  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:53.879  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a1d80 added. We now have 4 listener(s)
08-16 10:26:53.879  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:53.881  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:26:53.894  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:26:53.912  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:26:53.920  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:26:53.921  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:26:53.922  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:26:53.924  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:26:53.925  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:26:53.926  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:26:53.928  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:26:53.928  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 10:26:53.932  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:53.932  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:26:53.933  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@989ca03 removed from the list
,08-16 10:26:53.934  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:53.934  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a1d80 removed from the list
,08-16 10:26:53.940  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:53.941  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:26:53.941  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:26:53.942  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:26:53.942  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:53.944  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:26:53.944  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:26:53.944  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:53.944  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a1d80 not in the list
,08-16 10:26:53.944  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:53.944  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:53.946  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 10:26:53.946  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:26:53.946  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:53.946  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c8a1d80 not in the list
,08-16 10:26:53.946  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:26:53.946  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:26:53.946  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:26:53.946  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@989ca03 not in the list,
,08-16 10:26:53.947  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 10:26:53.947  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9412ffe added. We now have 3 listener(s)
08-16 10:26:53.949  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 10:26:53.949  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:26:53.949  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 10:26:53.949  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:53.949  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5035f added. We now have 4 listener(s)
08-16 10:26:53.949  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:53.950  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:26:53.956  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:26:53.963  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 10:26:53.967  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:53.967  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:26:53.967  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:26:53.967  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:26:53.967  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:26:53.968  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:26:53.968  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 10:26:53.984  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 10:26:53.986  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 10:26:53.987  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 10:26:53.988  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:26:53.996  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:26:53.997  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 10:26:53.998  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 10:26:54.006  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 10:26:54.006  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 10:26:54.007  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 10:26:54.008  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:26:54.015  4243  4273 D BtGatt.GattService: registerClient() - UUID=65e2f55d-ecaf-448d-a27b-92e9c6cff9f3
,08-16 10:26:54.016  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=65e2f55d-ecaf-448d-a27b-92e9c6cff9f3, clientIf=5
08-16 10:26:54.018  3834  3845 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 10:26:54.022  4243  4254 D BtGatt.GattService: start scan with filters
,08-16 10:26:54.036  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 10:26:54.036  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 10:26:54.036  4243  4262 D BtGatt.ScanManager: handling starting scan
08-16 10:26:54.036  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 10:26:54.037  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 10:26:54.041  4243  4262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d658a88
,08-16 10:26:54.047  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:26:54.047  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 10:26:54.048  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 10:26:54.054  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:26:54.059  3834  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 10:26:54.059  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 10:26:54.059  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 10:26:54.059  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 10:26:54.060  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:54.060  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 10:26:54.060  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 10:26:54.063  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 10:26:54.060  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:26:54.063  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 10:26:54.063  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:26:54.063  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 10:26:54.063  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 10:26:54.064  3834  3884 D BluetoothAdapter: STATE_ON
08-16 10:26:54.064  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 10:26:54.065  4243  4254 D BtGatt.GattService: stopScan() - queue size =1
,08-16 10:26:54.066  4243  4253 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:26:54.069  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 10:26:54.071  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 10:26:54.071  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 10:26:54.071  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 10:26:54.072  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 10:26:54.075  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:26:54.075  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 10:26:54.075  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:26:54.075  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:26:54.076  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:26:54.077  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 10:26:54.077  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:26:54.077  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:26:54.081  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 10:26:54.082  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:26:54.083  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-16 10:26:54.084  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 10:26:54.098  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 10:26:54.098  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:26:54.107  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 10:26:54.107  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:26:54.120  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 10:26:54.120  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:26:54.121  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,08-16 10:26:54.134  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 10:26:54.134  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:26:54.135  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:26:54.151  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 10:26:54.151  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:26:54.579  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 10:26:54.579  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:26:54.580  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:26:55.244   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 10:26:57.078  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:26:57.079  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:26:57.079  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 10:26:57.080  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:26:57.081  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:57.081  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:26:57.081  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:26:57.081  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9412ffe removed from the list
,08-16 10:26:57.082  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 10:26:57.082  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5035f removed from the list
,08-16 10:26:57.082  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:26:57.083  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:57.084  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:26:57.085  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:57.088  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:26:57.088  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:26:57.089  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:57.089  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5035f not in the list
,08-16 10:26:57.089  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:57.090  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:57.093  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:26:57.093  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:26:57.093  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:26:57.094  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d5035f not in the list
08-16 10:26:57.094  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 10:26:57.094  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:26:57.095  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:26:57.095  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9412ffe not in the list
08-16 10:26:57.097  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 10:26:57.098  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e1c98 added. We now have 3 listener(s)
08-16 10:26:57.099  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 10:26:57.100  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 10:26:57.100  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:26:57.100  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:26:57.100  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@918acf1 added. We now have 4 listener(s)
08-16 10:26:57.100  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:26:57.100  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 10:26:57.104  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:26:57.111  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:26:57.114  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:26:57.114  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:26:57.115  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 10:26:57.117  3834  3884 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 10:26:57.117  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 10:26:57.117  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 10:26:57.117  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 10:26:57.117  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 10:26:57.117  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:26:57.118  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:26:57.120  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 10:26:57.120  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 10:26:57.121  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
,08-16 10:26:57.121  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 10:26:57.121  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-16 10:26:57.121  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:26:57.121  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:26:57.125  3834  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 10:26:57.127  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 10:26:57.127  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 10:26:57.129  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:26:57.129  3834  3834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 10:26:57.132  3834  4344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 10:26:57.133  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:26:57.134  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 10:26:57.134  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 10:26:57.137  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 10:26:57.137  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 10:26:57.138  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-16 10:26:57.139  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 10:26:57.139  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 10:26:57.139  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-16 10:26:57.140  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:26:57.144  4243  4254 D BtGatt.GattService: registerClient() - UUID=bc975320-8ca8-4e21-bd12-9e73a417b918
,08-16 10:26:57.145  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=bc975320-8ca8-4e21-bd12-9e73a417b918, clientIf=5
08-16 10:26:57.145  3834  3903 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 10:26:57.147  4243  4261 D BtGatt.AdvertiseManager: message : 0
,08-16 10:26:57.151  4243  4261 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 10:26:57.162  4243  4259 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 10:26:57.171  4243  4259 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 10:26:57.173  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 10:26:57.173  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 10:26:57.175  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:26:57.177  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 10:26:57.178  3834  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 10:26:57.178  3834  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-16 10:26:57.178  3834  3834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-16 10:26:57.179  3834  3834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 10:26:57.179  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 10:26:57.183  3834  3834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 10:26:57.183  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 10:26:57.684  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 10:26:57.685  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 10:26:57.685  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:27:00.177  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 10:27:00.178  3834  3884 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:27:03.180  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:27:03.181  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-16 10:27:03.181  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 10:27:03.181  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 10:27:03.182  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-16 10:27:03.182  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 10:27:03.186  3834  4344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-16 10:27:03.186  3834  4344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 10:27:03.186  3834  4344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 10:27:03.186  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 10:27:03.187  3834  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 10:27:03.187  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 10:27:03.187  3834  3834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 10:27:03.187  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 10:27:03.188  3834  3834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 10:27:03.188  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 10:27:03.188  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:27:03.188  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 10:27:03.191  3834  3884 D BluetoothAdapter: STATE_ON
08-16 10:27:03.191  3834  3884 D BluetoothLeScanner: could not find callback wrapper
,08-16 10:27:03.192  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:27:03.192  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-16 10:27:03.194  4243  4261 D BtGatt.AdvertiseManager: message : 1
08-16 10:27:03.197  4243  4261 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 10:27:03.208  4243  4259 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-16 10:27:03.208  4243  4259 D BtGatt.GattService: Client app is not null!
,08-16 10:27:03.210  4243  4253 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:27:03.211  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 10:27:03.211  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-16 10:27:03.211  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 10:27:03.211  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-16 10:27:03.211  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-16 10:27:03.214  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 10:27:03.214  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:27:03.214  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:27:03.216  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:27:03.218  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:03.218  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:03.219  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:27:03.219  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:27:03.219  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e1c98 removed from the list
08-16 10:27:03.220  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:27:03.220  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:03.220  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:27:03.220  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@918acf1 removed from the list
08-16 10:27:03.220  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:27:03.220  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:27:03.221  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:03.222  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:27:03.222  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:03.223  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:27:03.224  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:03.224  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:03.224  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@918acf1 not in the list
08-16 10:27:03.224  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:03.224  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:03.226  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:03.226  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:27:03.227  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:03.227  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@918acf1 not in the list
08-16 10:27:03.227  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:03.227  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:03.227  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:03.227  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e1c98 not in the list
,08-16 10:27:03.228  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:27:03.228  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c09462 added. We now have 3 listener(s)
08-16 10:27:03.230  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 10:27:03.230  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:27:03.231  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:27:03.231  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:27:03.231  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f3 added. We now have 4 listener(s)
08-16 10:27:03.231  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 10:27:03.232  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:27:03.238  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:27:03.245  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:27:03.249  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:27:03.249  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 10:27:03.250  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 10:27:03.250  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 10:27:03.250  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 10:27:03.250  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 10:27:03.251  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 10:27:03.253  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:27:03.256  3834  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 10:27:03.256  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 10:27:03.258  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:27:03.265  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 10:27:03.266  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 10:27:03.267  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 10:27:03.273  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 10:27:03.273  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 10:27:03.273  3834  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 10:27:03.274  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:27:03.278  4243  4284 D BtGatt.GattService: registerClient() - UUID=43db7889-ec87-4c39-968a-08941a5ea003
,08-16 10:27:03.279  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=43db7889-ec87-4c39-968a-08941a5ea003, clientIf=5
,08-16 10:27:03.280  3834  3846 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 10:27:03.281  4243  4254 D BtGatt.GattService: start scan with filters
,08-16 10:27:03.287  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 10:27:03.287  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 10:27:03.288  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 10:27:03.288  4243  4262 D BtGatt.ScanManager: handling starting scan
08-16 10:27:03.288  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 10:27:03.295  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:27:03.296  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 10:27:03.296  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 10:27:03.300  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 10:27:03.305  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 10:27:03.305  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:27:03.306  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 10:27:03.318  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 10:27:03.318  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:27:03.318  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-16 10:27:03.319  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 10:27:03.342  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 10:27:03.343  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:27:03.355  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 10:27:03.355  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 10:27:03.721  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:27:03.796  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 10:27:03.797  3834  3834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 10:27:03.797  3834  3834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 10:27:04.867  4243  4243 D BtGatt.ScanManager: awakened up at time 278500
,08-16 10:27:04.870  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:27:04.917  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-16 10:27:04.917  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:27:04.918  4243  4259 D BtGatt.GattService: current time is 278551894979
,08-16 10:27:04.921  4243  4259 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -96, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -99, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:27:04.924  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:27:04.926  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 10:27:04.927  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 10:27:04.930  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 10:27:04.933  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:27:04.933  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 10:27:04.934  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 10:27:06.317  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:27:06.318  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:27:06.318  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 10:27:06.318  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 10:27:06.319  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 10:27:06.319  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 10:27:06.319  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 10:27:06.320  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 10:27:06.320  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 10:27:06.320  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 10:27:06.321  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-16 10:27:06.323  3834  3884 D BluetoothAdapter: STATE_ON
,08-16 10:27:06.325  4243  4254 D BtGatt.GattService: stopScan() - queue size =1
,08-16 10:27:06.327  4243  4273 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 10:27:06.328  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 10:27:06.329  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 10:27:06.329  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 10:27:06.329  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 10:27:06.330  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 10:27:06.334  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:27:06.335  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 10:27:06.335  3834  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 10:27:06.336  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 10:27:06.337  4243  4243 D BtGatt.ScanManager: awakened up at time 279971
08-16 10:27:06.337  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:27:06.341  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:27:06.342  3834  3834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 10:27:06.342  3834  3834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 10:27:06.343  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:06.343  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.344  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 10:27:06.344  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:27:06.344  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c09462 removed from the list
08-16 10:27:06.345  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.346  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f3 removed from the list
08-16 10:27:06.346  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:27:06.346  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:06.348  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 10:27:06.348  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:27:06.349  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
08-16 10:27:06.349  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.349  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:06.353  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:27:06.353  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:06.353  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.353  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f3 not in the list
08-16 10:27:06.353  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.353  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:06.355  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:06.355  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 10:27:06.355  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.355  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139f3 not in the list
08-16 10:27:06.355  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:06.355  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.355  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:06.355  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c09462 not in the list
,08-16 10:27:06.356  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 10:27:06.356  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@914bddc added. We now have 3 listener(s)
08-16 10:27:06.358  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 10:27:06.358  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:27:06.359  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 10:27:06.359  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 10:27:06.359  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 10:27:06.359  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 10:27:06.360  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 10:27:06.360  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60ee5 added. We now have 4 listener(s)
08-16 10:27:06.360  3834  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 10:27:06.361  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 10:27:06.364  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 10:27:06.369  3834  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 10:27:06.371  3834  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 10:27:06.371  3834  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 10:27:06.372  3834  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 10:27:06.372  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 10:27:06.372  3834  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 10:27:06.372  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:06.372  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.372  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 10:27:06.372  3834  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 10:27:06.372  3834  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@914bddc removed from the list
08-16 10:27:06.373  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.373  3834  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60ee5 removed from the list
08-16 10:27:06.374  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 10:27:06.375  3834  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 10:27:06.375  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:06.375  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.375  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 10:27:06.376  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:27:06.377  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:06.377  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.377  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60ee5 not in the list
08-16 10:27:06.377  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.377  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:06.378  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 10:27:06.378  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 10:27:06.378  3834  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 10:27:06.378  3834  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60ee5 not in the list
08-16 10:27:06.378  3834  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 10:27:06.378  3834  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 10:27:06.378  3834  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 10:27:06.378  3834  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@914bddc not in the list
08-16 10:27:06.379  3834  3834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 10:27:06.388  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 10:27:06.389  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 10:27:06.389  4243  4259 D BtGatt.GattService: current time is 280023025385
,08-16 10:27:06.390  4243  4259 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -93, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 10:27:06.391  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 10:27:06.391  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 10:27:06.392  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 10:27:06.393  4243  4259 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 10:27:06.844  3834  3834 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 10:27:11.381  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 10:27:11.382  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 10:27:11.382  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 10:27:11.383  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 10:27:11.383  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 10:27:11.384  3834  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 10:27:13.954  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:27:13.956  1525  1525 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 10:27:14.004  1525  2444 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:27:14.004  1525  2444 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 10:27:14.004  1525  2444 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:27:14.004  1525  2444 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:27:14.048  3003  4351 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 10:27:14.048  3003  4351 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at blb.a(PG:3937)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at czp.a(PG:18188)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:27:14.048  3003  4351 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	... 12 more
08-16 10:27:14.048  3003  4351 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:27:14.048  3003  4351 E HttpOperation: 	at fal.a(PG:38)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	,at jdj.a(PG:4089)
08-16 10:27:14.048  3003  4351 E HttpOperation: 	... 14 more
,08-16 10:27:14.096  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 10:27:14.096  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 10:27:14.096  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:27:14.096  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:27:14.134  3003  4351 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 10:27:14.134  3003  4351 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jdm.a(PG:82)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jcs.o(PG:406)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jcn.a(PG:1379)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jcs.i(PG:143)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at hec.a(PG:42)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at hee.a(PG:102)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at czr.a(PG:65)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at kka.a(PG:108)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at czp.a(PG:19176)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at czp.a(PG:9081)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at czq.run(PG:1686)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:27:14.134  3003  4351 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jdj.a(PG:4091)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jdj.a(PG:1125)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jdm.a(PG:77)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	... 15 more
08-16 10:27:14.134  3003  4351 E HttpOperation: Caused by: faj: BadAuthentication
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at fal.a(PG:38)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	at jdj.a(PG:4089)
08-16 10:27:14.134  3003  4351 E HttpOperation: 	... 17 more
,08-16 10:27:14.134  3003  4351 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 10:27:14.134  3003  4351 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at hec.a(PG:42)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at hee.a(PG:102)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at czr.a(PG:65)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at kka.a(PG:108)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	... 15 more
08-16 10:27:14.134  3003  4351 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at fal.a(PG:38)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 10:27:14.134  3003  4351 E ExperimentLoader: 	... 17 more
,08-16 10:27:14.243   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 258431, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:27:14.291  3626  4354 V KeepSync: Connecting to GoogleApiClient
,08-16 10:27:14.291   873  1682 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 10:27:14.356  1525  1877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 10:27:14.356  1525  1877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 10:27:14.356  1525  1877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:27:14.356  1525  1877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-16 10:27:14.373  1754  4355 V BaseAuthAsyncOperation: access token request failed
,08-16 10:27:14.374  3626  4354 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 10:27:14.418  1525  1536 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 10:27:14.418  1525  1536 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 10:27:14.419  1525  1536 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 10:27:14.419  1525  1536 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 10:27:14.436  3626  4354 E KeepSync: IOException
08-16 10:27:14.436  3626  4354 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 10:27:14.436  3626  4354 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 10:27:14.436  3626  4354 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 10:27:14.436  3626  4354 E KeepSync: 	... 10 more
08-16 10:27:14.436  3626  4354 W KeepSync: Sync result 2
,08-16 10:27:14.453   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 287743, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 10:27:18.409  3834  4356 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,08-16 10:27:20.407  3834  3884 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 457
08-16 10:27:20.408  3834  3884 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 457, name: My test thread name)
,08-16 10:27:20.414  3834  4357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
08-16 10:27:20.415  3834  4357 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: My test thread name)
08-16 10:27:20.415  3834  4357 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 10:27:20.419  3834  3884 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 10:27:20.428  3834  4358 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,08-16 10:27:20.429  3834  4358 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 462, thread name: My test thread name): Test exception.
08-16 10:27:20.429  3834  4358 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 10:27:20.437  3834  3884 I jxcore-log: Total number of executed tests:  82
08-16 10:27:20.437  3834  3884 I jxcore-log: 
,08-16 10:27:20.438  3834  3884 I jxcore-log: Number of passed tests:  82
08-16 10:27:20.438  3834  3884 I jxcore-log: 
08-16 10:27:20.439  3834  3884 I jxcore-log: Number of failed tests:  0
08-16 10:27:20.439  3834  3884 I jxcore-log: 
,08-16 10:27:20.439  3834  3884 I jxcore-log: Number of ignored tests:  0
08-16 10:27:20.439  3834  3884 I jxcore-log: 
08-16 10:27:20.442  3834  3884 I jxcore-log: Total duration:  150581
08-16 10:27:20.442  3834  3884 I jxcore-log: 
,08-16 10:27:20.442  3834  3884 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 10:27:20.442  3834  3884 I jxcore-log: 
,08-16 10:27:20.452  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.452  3834  3884 I jxcore-log: 
08-16 10:27:20.455  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.455  3834  3884 I jxcore-log: 
08-16 10:27:20.457  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.457  3834  3884 I jxcore-log: 
08-16 10:27:20.458  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.458  3834  3884 I jxcore-log: 
,08-16 10:27:20.459  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 10:27:20.459  3834  3884 I jxcore-log: 
,08-16 10:27:20.461  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.461  3834  3884 I jxcore-log: 
,08-16 10:27:20.464  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.464  3834  3884 I jxcore-log: 
,08-16 10:27:20.466  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.466  3834  3884 I jxcore-log: 
,08-16 10:27:20.467  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 10:27:20.467  3834  3884 I jxcore-log: 
,08-16 10:27:20.468  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.468  3834  3884 I jxcore-log: 
,08-16 10:27:20.469  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.469  3834  3884 I jxcore-log: 
08-16 10:27:20.469  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.469  3834  3884 I jxcore-log: 
08-16 10:27:20.470  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.470  3834  3884 I jxcore-log: 
,08-16 10:27:20.471  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.471  3834  3884 I jxcore-log: 
08-16 10:27:20.472  3834  3834 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 10:27:20.472  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.472  3834  3884 I jxcore-log: 
08-16 10:27:20.473  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.473  3834  3884 I jxcore-log: 
08-16 10:27:20.474  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.474  3834  3884 I jxcore-log: 
,08-16 10:27:20.475  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.475  3834  3884 I jxcore-log: 
08-16 10:27:20.476  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.476  3834  3884 I jxcore-log: 
,08-16 10:27:20.477  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.477  3834  3884 I jxcore-log: 
,08-16 10:27:20.478  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.478  3834  3884 I jxcore-log: 
08-16 10:27:20.478  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.478  3834  3884 I jxcore-log: 
,08-16 10:27:20.479  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.479  3834  3884 I jxcore-log: 
,08-16 10:27:20.480  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.480  3834  3884 I jxcore-log: 
08-16 10:27:20.481  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.481  3834  3884 I jxcore-log: 
08-16 10:27:20.481  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.481  3834  3884 I jxcore-log: 
,08-16 10:27:20.482  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.482  3834  3884 I jxcore-log: 
08-16 10:27:20.483  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.483  3834  3884 I jxcore-log: 
08-16 10:27:20.484  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.484  3834  3884 I jxcore-log: 
08-16 10:27:20.484  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.484  3834  3884 I jxcore-log: 
,08-16 10:27:20.485  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.485  3834  3884 I jxcore-log: 
08-16 10:27:20.486  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.486  3834  3884 I jxcore-log: 
08-16 10:27:20.487  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.487  3834  3884 I jxcore-log: 
08-16 10:27:20.487  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.487  3834  3884 I jxcore-log: 
,08-16 10:27:20.488  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.488  3834  3884 I jxcore-log: 
,08-16 10:27:20.489  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.489  3834  3884 I jxcore-log: 
,08-16 10:27:20.490  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.490  3834  3884 I jxcore-log: 
08-16 10:27:20.491  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.491  3834  3884 I jxcore-log: 
08-16 10:27:20.491  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.491  3834  3884 I jxcore-log: 
08-16 10:27:20.492  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.492  3834  3884 I jxcore-log: 
,08-16 10:27:20.492  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 10:27:20.492  3834  3884 I jxcore-log: 
08-16 10:27:20.493  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.493  3834  3884 I jxcore-log: 
08-16 10:27:20.494  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.494  3834  3884 I jxcore-log: 
,08-16 10:27:20.494  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 10:27:20.494  3834  3884 I jxcore-log: 
08-16 10:27:20.495  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.495  3834  3884 I jxcore-log: 
08-16 10:27:20.495  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.495  3834  3884 I jxcore-log: 
08-16 10:27:20.496  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.496  3834  3884 I jxcore-log: 
,08-16 10:27:20.496  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.496  3834  3884 I jxcore-log: 
08-16 10:27:20.497  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.497  3834  3884 I jxcore-log: 
08-16 10:27:20.497  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.497  3834  3884 I jxcore-log: 
08-16 10:27:20.498  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 10:27:20.498  3834  3884 I jxcore-log: 
,08-16 10:27:20.498  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.498  3834  3884 I jxcore-log: 
08-16 10:27:20.499  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.499  3834  3884 I jxcore-log: 
08-16 10:27:20.499  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 10:27:20.499  3834  3884 I jxcore-log: 
08-16 10:27:20.500  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 10:27:20.500  3834  3884 I jxcore-log: 
,08-16 10:27:20.500  3834  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 10:27:20.500  3834  3884 I jxcore-log: 
,08-16 10:27:20.534  3834  4356 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,08-16 10:27:21.057  4359  4359 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 10:27:21.061  4359  4359 D AndroidRuntime: CheckJNI is OFF
,08-16 10:27:21.097  4359  4359 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 10:27:21.139  4359  4359 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 10:27:21.161  4359  4359 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 10:27:21.179   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-16 10:27:21.179   873   886 I ActivityManager: Killing 3834:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 10:27:21.284   873   897 W PackageSettings: Skipping PackageSetting{da8a8b5 com.example.hello/10273} due to missing metadata
,08-16 10:27:21.296   873  1992 D GraphicsStats: Buffer count: 2
,08-16 10:27:21.296   873  1935 I WindowState: WIN DEATH: Window{e042de8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 10:27:21.301   873  1319 D WifiService: Client connection lost with reason: 4
,08-16 10:27:21.319   873   897 I art     : Starting a blocking GC Explicit
,08-16 10:27:21.320   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 10:27:21.321   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 10:27:21.326   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 10:27:21.326   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 10:27:21.326   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.326   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.326   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 10:27:21.326   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 10:27:21.327   873   886 I ActivityManager:   Force finishing activity ActivityRecord{98e45e9 u0 com.test.thalitest/.MainActivity t2}
,08-16 10:27:21.338   873  1992 W ActivityManager: Spurious death for ProcessRecord{4d8457c 0:com.test.thalitest/u0a0}, curProc for 3834: null
,08-16 10:27:21.378   873   897 I art     : Explicit concurrent mark sweep GC freed 21286(1365KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 821us total 57.908ms
,08-16 10:27:21.397   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 10:27:21.399  4359  4359 I art     : System.exit called, status: 0
,08-16 10:27:21.399  4359  4359 I AndroidRuntime: VM exiting with result code 0.
,08-16 10:27:21.405   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 10:27:21.411   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 10:27:21.434   873  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 10:27:21.435  2179  2307 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 10:27:21.436  4243  4243 D BluetoothMapAppObserver: onReceive
08-16 10:27:21.436  4243  4243 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 10:27:21.437  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 10:27:21.437  3699  3699 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 10:27:21.447  1864  4370 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 10:27:21.449  1864  4370 I Decoder : createOrResetDecoder
,08-16 10:27:21.478   873  1939 I ActivityManager: Start proc 4373:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 10:27:21.496  1929  1929 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 10:27:21.499  1525  1525 I ConfigService: onCreate
,08-16 10:27:21.520  4373  4373 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 10:27:21.532  1864  4370 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 10:27:21.548   873  1992 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3834 uid 10000
,08-16 10:27:21.549  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 10:27:21.550   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 10:27:21.574  1864  4370 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 10:27:21.576  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 10:27:21.576  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 10:27:21.578  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 10:27:21.578  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 10:27:21.579  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 10:27:21.579  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 10:27:21.581  1864  4370 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-16 10:27:21.581  1864  4370 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-16 10:27:21.586  1864  4370 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 10:27:21.587  1864  4370 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 10:27:21.587  1864  4370 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-16 10:27:21.587  1864  4370 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 10:27:21.589  1946  2040 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-16 10:27:21.590   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 10:27:21.591   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 10:27:21.591   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 10:27:21.591   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 10:27:21.591   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 10:27:21.591   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 10:27:21.591   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 10:27:21.591   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.591   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.591   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.597   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 10:27:21.597   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 10:27:21.597   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:27:21.597   873   886 E DropBoxManagerService: 	... 13 more
,08-16 10:27:21.602   873   883 I ActivityManager: Start proc 4390:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-16 10:27:21.602  1946  2040 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 10:27:21.602  1946  2040 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1946
08-16 10:27:21.602  1946  2040 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.602  1946  2040 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.604   873  1992 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 10:27:21.604   873  4395 E DropBoxManagerService: Can't write: system_app_crash
08-16 10:27:21.604   873  4395 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:27:21.604   873  4395 E DropBoxManagerService: 	... 5 more
,08-16 10:27:21.642  4373  4373 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 10:27:21.643  1946  2040 I Process : Sending signal. PID: 1946 SIG: 9
,08-16 10:27:21.657  4373  4404 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 10:27:21.663   873  1935 I ActivityManager: Start proc 4405:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 10:27:21.670   873  4299 D NetlinkSocketObserver: NeighborEvent{elapsedMs=295303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 10:27:21.676  4373  4388 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.676  4373  4388 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.700   873  1939 I WindowState: WIN DEATH: Window{b50130f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-16 10:27:21.700   873  1396 D GraphicsStats: Buffer count: 1
08-16 10:27:21.706   873  1935 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1946) has died
08-16 10:27:21.707   873  1935 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 10:27:21.708   873  1935 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 10:27:21.727   873   886 I ActivityManager: Start proc 4419:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 10:27:21.748  4405  4405 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.724  4373  4388 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.773  1525  1525 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 10:27:21.775  1525  1525 D AndroidRuntime: Shutting down VM
08-16 10:27:21.777  1525  1525 E AndroidRuntime: FATAL EXCEPTION: main
08-16 10:27:21.777  1525  1525 E AndroidRuntime: Process: com.google.process.gapps, PID: 1525
08-16 10:27:21.777  1525  1525 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 10:27:21.777  1525  1525 E AndroidRuntime: 	... 8 more
08-16 10:27:21.781   873  4434 E DropBoxManagerService: Can't write: system_app_crash
08-16 10:27:21.781   873  4434 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:27:21.781   873  4434 E DropBoxManagerService: 	... 5 more
08-16 10:27:21.782  1525  1525 I Process : Sending signal. PID: 1525 SIG: 9
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:27:21.782  4419  4419 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:27:21.783  4419  4419 D AndroidRuntime: Shutting down VM
08-16 10:27:21.788  1754  4431 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 10:27:21.790  1754  4431 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 10:27:21.792  4419  4419 E AndroidRuntime: FATAL EXCEPTION: main
08-16 10:27:21.792  4419  4419 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4419
08-16 10:27:21.792  4419  4419 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 10:27:21.792  4419  4419 E AndroidRuntime: 	... 10 more
08-16 10:27:21.794   873  1935 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 10:27:21.795   873  4435 E DropBoxManagerService: Can't write: system_app_crash
08-16 10:27:21.795   873  4435 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:27:21.795   873  4435 E DropBoxManagerService: 	... 5 more
08-16 10:27:21.795  4419  4419 I Process : Sending signal. PID: 4419 SIG: 9
08-16 10:27:21.803  1754  4431 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 10:27:21.805  1754  4431 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 10:27:21.819   873  1939 I ActivityManager: Killing 3751:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-16 10:27:21.831   873  1319 D WifiService: Client connection lost with reason: 4
,08-16 10:27:21.850  4373  4388 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 10:27:21.854  4373  4404 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.854  4373  4404 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.855  4373  4404 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 10:27:21.855  4373  4404 E AndroidRuntime: Process: android.process.acore, PID: 4373
08-16 10:27:21.855  4373  4404 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 10:27:21.855  4373  4404 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 10:27:21.855  4373  4388 I Process : Sending signal. PID: 4373 SIG: 9
,08-16 10:27:21.866   873  1992 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4419) has died
,08-16 10:27:21.867   873  1992 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 10:27:21.875   873  4437 E DropBoxManagerService: Can't write: system_app_crash
08-16 10:27:21.875   873  4437 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 10:27:21.875   873  4437 E DropBoxManagerService: 	... 5 more
,08-16 10:27:21.904   873   886 I ActivityManager: Start proc 4438:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 10:27:21.905   873  1683 I ActivityManager: Process com.google.process.gapps (pid 1525) has died

```
