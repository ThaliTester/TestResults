#### Test 79751015007586f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-12 22:27:21.486  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 22:27:21.503  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 22:27:21.509  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 22:27:21.573  1528  1543 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 22:27:21.574  1528  1543 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 22:27:21.574  1528  1543 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:27:21.574  1528  1543 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 22:27:21.612  3544  3544 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 22:27:21.612  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 22:27:21.613  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-12 22:27:22.152  3800  3800 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 22:27:22.157  3800  3800 D AndroidRuntime: CheckJNI is OFF
08-12 22:27:22.200  3800  3800 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 22:27:22.251  3800  3800 I Radio-JNI: register_android_hardware_Radio DONE
08-12 22:27:22.271  3800  3800 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 22:27:22.276   872  2152 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 22:27:22.317  3800  3800 D AndroidRuntime: Shutting down VM
08-12 22:27:22.320  1986  1997 W SearchService: Abort, client detached.
08-12 22:27:22.328  1986  2337 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2e68f92
08-12 22:27:22.328  1986  2346 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 22:27:22.328  1986  1986 I HotwordDetector: Closing mic
08-12 22:27:22.341   872  1964 I ActivityManager: Start proc 3809:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 22:27:22.395   375  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 22:27:22.396   375  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 22:27:22.407   375  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 22:27:22.410  1986  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 22:27:22.410  1986  2345 I MicroRecognitionRnrImpl: Detection finished
08-12 22:27:22.424  3809  3809 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 22:27:22.444  3809  3809 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 22:27:22.455  3809  3809 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 2640-2647)
08-12 22:27:22.456  3809  3809 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:27:22.476  3809  3809 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {92a0c4}
08-12 22:27:22.476  3809  3809 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:27:22.476  3809  3809 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 22:27:22.483  3809  3809 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 22:27:22.485  3809  3809 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 22:27:22.506  3809  3809 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 22:27:22.516  3809  3809 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 22:27:22.516  3809  3809 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 22:27:22.516  3809  3809 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 22:27:22.516  3809  3809 I Adreno  : Build Date                       : 10/20/15
08-12 22:27:22.516  3809  3809 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 22:27:22.516  3809  3809 I Adreno  : Local Branch                     : M14
08-12 22:27:22.516  3809  3809 I Adreno  : Remote Branch                    : 
08-12 22:27:22.516  3809  3809 I Adreno  : Remote Branch                    : 
08-12 22:27:22.516  3809  3809 I Adreno  : Reconstruct Branch               : 
,08-12 22:27:22.584   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60eede1:true
,08-12 22:27:22.689  3809  3809 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 22:27:22.708  3809  3809 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 22:27:22.778   872   881 I art     : Background partial concurrent mark sweep GC freed 50144(3MB) AllocSpace objects, 9(204KB) LOS objects, 33% free, 29MB/43MB, paused 2.495ms total 109.508ms
,08-12 22:27:22.785  3809  3849 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 22:27:22.794  3809  3834 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 22:27:22.828  3809  3849 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 22:27:22.916   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +591ms
,08-12 22:27:22.929  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-12 22:27:22.991  3809  3809 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3809
,08-12 22:27:23.113  3809  3809 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 22:27:23.153   872  2153 I ActivityManager: Killing 3243:com.google.android.gm/u0a78 (adj 15): empty #17
,08-12 22:27:23.206   872  2153 I ActivityManager: Killing 3132:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-12 22:27:23.356  3809  3851 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1680279248
,08-12 22:27:23.366  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 22:27:23.366  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 22:27:23.366  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 22:27:23.366  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 22:27:23.366  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 22:27:23.367  3809  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b7f08 added. We now have 1 listener(s)
,08-12 22:27:23.370  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 22:27:23.371  3809  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 22:27:23.372  3809  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 22:27:23.372  3809  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 22:27:23.377  3809  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26d887 added. We now have 1 listener(s)
,08-12 22:27:23.379  3809  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 22:27:23.384   872  1308 D WifiService: New client listening to asynchronous messages
,08-12 22:27:23.386  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 22:27:23.386  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 22:27:23.386  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 22:27:23.386  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 22:27:23.386  3809  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 22:27:23.388  3809  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 22:27:23.388  3809  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 22:27:23.395  3809  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:27:23.396  3809  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:27:23.396  3809  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 22:27:23.396  3809  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 22:27:23.397  3809  3851 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 22:27:23.513  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 22:27:23.517  3809  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 22:27:23.519  3809  3809 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 22:27:24.117   872  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 22:27:24.728  3809  3860 W jxcore-log: Initializing JXcore engine
,08-12 22:27:24.728  3809  3860 W jxcore-log: JXcore engine is ready
,08-12 22:27:24.763  3860  3860 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 22:27:24.763  3860  3860 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10568]" dev="sockfs" ino=10568 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 22:27:24.763  3860  3860 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-12 22:27:24.763  3860  3860 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23172]" dev="sockfs" ino=23172 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 22:27:24.776  3809  3860 W jxcore-log: Starting JXcore engine
,08-12 22:27:24.854  3809  3860 W jxcore-log: Platform android
08-12 22:27:24.854  3809  3860 W jxcore-log: 
,08-12 22:27:24.854  3809  3860 W jxcore-log: Process ARCH arm
08-12 22:27:24.854  3809  3860 W jxcore-log: 
,08-12 22:27:25.086  3809  3860 I jxcore-log: JXcore Cordova bridge is ready!
08-12 22:27:25.086  3809  3860 I jxcore-log: 
,08-12 22:27:25.086  3809  3860 W jxcore-log: JXcore engine is started
,08-12 22:27:25.098  3809  3851 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 22:27:25.104  3809  3809 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 22:27:28.764  3606  3868 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 22:27:28.804  3606  3869 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 22:27:28.816  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:28.819  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:28.833  3143  3867 V KeepSync: Connecting to GoogleApiClient
,08-12 22:27:28.834   872  2156 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 22:27:28.843  1528  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 22:27:28.843  1528  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 22:27:28.843  1528  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:27:28.843  1528  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:27:28.872  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:28.876  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:28.909  1528  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 22:27:28.909  1528  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 22:27:28.909  1528  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:27:28.910  1528  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 22:27:28.910  1528  3188 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 22:27:28.910  1528  3188 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 22:27:28.910  1528  3188 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:27:28.911  1528  3188 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:27:28.934  3606  3869 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 22:27:28.935  3606  3868 E BooksSync: Soft error
08-12 22:27:28.935  3606  3868 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 22:27:28.935  3606  3868 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 22:27:28.935  3606  3868 E BooksSync: Sync error
08-12 22:27:28.935  3606  3868 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 22:27:28.935  3606  3868 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 22:27:28.935  3606  3868 I BooksSync: Finished books sync
,08-12 22:27:28.941   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128566, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:27:28.943  1739  3870 V BaseAuthAsyncOperation: access token request failed
,08-12 22:27:28.944  3143  3867 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 22:27:28.981  1528  1543 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 22:27:28.982  1528  1543 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 22:27:28.982  1528  1543 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:27:28.982  1528  1543 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:27:28.999  3143  3867 E KeepSync: IOException
08-12 22:27:28.999  3143  3867 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 22:27:28.999  3143  3867 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:27:28.999  3143  3867 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 22:27:28.999  3143  3867 E KeepSync: 	... 10 more
,08-12 22:27:28.999  3143  3867 W KeepSync: Sync result 2
,08-12 22:27:29.006   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128036, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:27:40.968  3809  3860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 22:27:40.968  3809  3860 I jxcore-log: 
,08-12 22:27:40.971  3809  3860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 22:27:40.971  3809  3860 I jxcore-log: 
,08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:27:40.977  3809  3860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 22:27:40.981  3809  3860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 22:27:40.983  3809  3860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 22:27:40.983  3809  3860 I jxcore-log: 
,08-12 22:27:40.985  3809  3860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 22:27:40.985  3809  3860 I jxcore-log: 
,08-12 22:27:41.326  3809  3860 I jxcore-log: Unit Test app is loaded
08-12 22:27:41.326  3809  3860 I jxcore-log: 
,08-12 22:27:41.332  3809  3860 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 22:27:41.332  3809  3860 I jxcore-log: 
,08-12 22:27:41.336  3809  3860 I jxcore-log: My device name is: motorola-Nexus 6
08-12 22:27:41.336  3809  3860 I jxcore-log: 
,08-12 22:27:41.337  3809  3860 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 22:27:41.337  3809  3860 I jxcore-log: 
,08-12 22:27:41.350  3809  3809 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 22:27:41.865  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:41.879  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:41.884  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:41.932  1528  2330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 22:27:41.933  1528  2330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 22:27:41.933  1528  2330 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:27:41.933  1528  2330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:27:41.953  3544  3544 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 22:27:41.955  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 22:27:41.955  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 22:27:43.683  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 22:27:43.683  3809  3860 I jxcore-log: 
,08-12 22:27:44.324  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 22:27:44.324  3809  3860 I jxcore-log: 
,08-12 22:27:44.350  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 22:27:44.350  3809  3860 I jxcore-log: 
,08-12 22:27:44.944   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 22:27:45.756  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 22:27:45.756  3809  3860 I jxcore-log: 
,08-12 22:27:45.999  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 22:27:45.999  3809  3860 I jxcore-log: 
,08-12 22:27:46.006  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 22:27:46.006  3809  3860 I jxcore-log: 
,08-12 22:27:46.012  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 22:27:46.012  3809  3860 I jxcore-log: 
,08-12 22:27:46.029  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 22:27:46.029  3809  3860 I jxcore-log: 
,08-12 22:27:46.033  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 22:27:46.033  3809  3860 I jxcore-log: 
,08-12 22:27:46.719  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 22:27:46.719  3809  3860 I jxcore-log: 
,08-12 22:27:46.732  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 22:27:46.732  3809  3860 I jxcore-log: 
,08-12 22:27:46.741  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 22:27:46.741  3809  3860 I jxcore-log: 
,08-12 22:27:46.749  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 22:27:46.749  3809  3860 I jxcore-log: 
,08-12 22:27:46.799  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 22:27:46.799  3809  3860 I jxcore-log: 
,08-12 22:27:46.856  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 22:27:46.856  3809  3860 I jxcore-log: 
,08-12 22:27:46.865  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 22:27:46.865  3809  3860 I jxcore-log: 
,08-12 22:27:47.036  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 22:27:47.036  3809  3860 I jxcore-log: 
,08-12 22:27:47.065  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 22:27:47.065  3809  3860 I jxcore-log: 
,08-12 22:27:47.071  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 22:27:47.071  3809  3860 I jxcore-log: 
,08-12 22:27:47.077  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 22:27:47.077  3809  3860 I jxcore-log: 
,08-12 22:27:47.096  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 22:27:47.096  3809  3860 I jxcore-log: 
,08-12 22:27:47.185  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 22:27:47.185  3809  3860 I jxcore-log: 
,08-12 22:27:47.197  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 22:27:47.197  3809  3860 I jxcore-log: 
,08-12 22:27:47.226  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 22:27:47.226  3809  3860 I jxcore-log: 
,08-12 22:27:47.239  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 22:27:47.239  3809  3860 I jxcore-log: 
,08-12 22:27:47.258  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 22:27:47.258  3809  3860 I jxcore-log: 
,08-12 22:27:47.296  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 22:27:47.296  3809  3860 I jxcore-log: 
,08-12 22:27:47.302  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 22:27:47.302  3809  3860 I jxcore-log: 
,08-12 22:27:47.509  3809  3860 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 22:27:47.509  3809  3860 I jxcore-log: 
,08-12 22:27:47.522  3809  3860 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 22:27:47.523  3809  3860 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 22:27:47.523  3809  3860 I jxcore-log: 
,08-12 22:27:47.989   872  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 22:27:52.579   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:27:52.870   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 22:27:52.886   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 22:27:52.886   872   892 I Adreno  : Build Date                       : 10/20/15
08-12 22:27:52.886   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 22:27:52.886   872   892 I Adreno  : Local Branch                     : M14
08-12 22:27:52.886   872   892 I Adreno  : Remote Branch                    : 
08-12 22:27:52.886   872   892 I Adreno  : Remote Branch                    : 
08-12 22:27:52.886   872   892 I Adreno  : Reconstruct Branch               : 
,08-12 22:27:52.881  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-12 22:27:52.939   281  1768 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (646 us)
,08-12 22:27:53.635  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 22:27:53.636  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 22:27:53.675   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 22:27:53.678  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7ca783a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5ffdbf1, 16908290=android.view.AbsSavedState$1@5ffdbf1}, android:focusedViewId=100}]}]
08-12 22:27:53.678  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-12 22:27:53.679  3809  3809 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 22:27:53.679  3809  3809 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 22:27:53.689   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 22:27:53.694   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-12 22:27:53.708   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-12 22:27:53.708   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 22:27:53.963   281   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 22:27:53.968   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 22:27:53.973   872  1332 D SurfaceControl: Excessive delay in setPowerMode(): 280ms
,08-12 22:27:53.978   872   892 I DreamManagerService: Entering dreamland.
,08-12 22:27:53.979   872   892 I PowerManagerService: Dozing...
,08-12 22:27:53.981   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 22:27:54.043   375  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 22:27:54.044   375  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 22:27:54.053   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 22:27:54.071   872  1307 E native  : do suspend false
,08-12 22:27:54.071  1893  3879 D NfcService: Discovery configuration equal, not updating.
,08-12 22:27:54.097   872  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 22:27:54.111   872  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 22:27:54.116   872  1307 E native  : do suspend true
,08-12 22:27:54.173   375  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 22:27:54.174   375  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 22:27:54.560   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 22:27:59.142  2158  2633 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 22:27:59.929  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:27:59.933  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:00.020  1528  2330 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 22:28:00.020  1528  2330 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 22:28:00.021  1528  2330 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:28:00.021  1528  2330 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:00.073  3005  3885 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 22:28:00.073  3005  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at blb.a(PG:3937)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at czp.a(PG:18188)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:28:00.073  3005  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	... 12 more
08-12 22:28:00.073  3005  3885 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at fal.a(PG:38)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:28:00.073  3005  3885 E HttpOperation: 	... 14 more
,08-12 22:28:00.147  1528  3188 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 22:28:00.147  1528  3188 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 22:28:00.147  1528  3188 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:28:00.147  1528  3188 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:00.169  3005  3885 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 22:28:00.169  3005  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at hec.a(PG:42)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at hee.a(PG:102)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at czr.a(PG:65)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at kka.a(PG:108)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at czp.a(PG:19176)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:28:00.169  3005  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	... 15 more
08-12 22:28:00.169  3005  3885 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at fal.a(PG:38)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:28:00.169  3005  3885 E HttpOperation: 	... 17 more
,08-12 22:28:00.169  3005  3885 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 22:28:00.169  3005  3885 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at hec.a(PG:42)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at hee.a(PG:102)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at czr.a(PG:65)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at kka.a(PG:108)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	... 15 more
08-12 22:28:00.169  3005  3885 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at fal.a(PG:38)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 22:28:00.169  3005  3885 E ExperimentLoader: 	... 17 more
,08-12 22:28:00.363   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 159808, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:28:02.131  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:02.354  1528  3888 I VacuumService: Vacuum at: now=1471033682354 tag=VacuumService
08-12 22:28:02.357  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:02.415  1528  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 22:28:02.415  1528  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 22:28:02.415  1528  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:28:02.415  1528  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:02.440  3544  3544 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 22:28:02.440  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 22:28:02.440  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 22:28:02.479  1528  3889 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 22:28:02.482  1528  3889 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 22:28:02.511  1528  3889 W Uploader:  no longer exists, so no auth token.
,08-12 22:28:03.507  1528  3889 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 22:28:03.507  1528  3889 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 22:28:03.507  1528  3889 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:28:03.508  1528  3889 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:03.546  1528  3889 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 22:28:03.546  1528  3889 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 22:28:03.546  1528  3889 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 22:28:03.865  1528  3889 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 22:28:03.865  1528  3889 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 22:28:03.866  1528  3889 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:28:03.866  1528  3889 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:03.923  1528  3889 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 22:28:03.923  1528  3889 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 22:28:03.923  1528  3889 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 22:28:04.130   872  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 22:28:04.364  1528  3889 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 22:28:04.364  1528  3889 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 22:28:04.365  1528  3889 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:28:04.365  1528  3889 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:04.400  1528  3889 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 22:28:04.400  1528  3889 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 22:28:04.400  1528  3889 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 22:28:22.472   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:28:24.405  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:24.413  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:24.418  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:28:24.469  1528  1543 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 22:28:24.470  1528  1543 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 22:28:24.470  1528  1543 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:28:24.471  1528  1543 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:28:24.525  3544  3544 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 22:28:24.527  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 22:28:24.529  3544  3544 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 22:28:29.245   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=189437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 22:28:36.892  1528  2189 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 22:28:43.165   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=203357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:28:50.565   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:28:52.904  1854  1941 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-12 22:28:52.905  1854  1941 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 22:28:52.958  1528  1528 I ConfigService: onCreate
,08-12 22:28:58.043  1528  1528 I ConfigService: onDestroy
,08-12 22:29:08.445   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:29:15.819   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=236010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:29:29.502  3143  3905 V KeepSync: Connecting to GoogleApiClient
08-12 22:29:29.502   872  1938 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 22:29:29.575  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:29:29.580  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:29:29.633  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 22:29:29.633  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 22:29:29.633  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:29:29.633  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:29:29.668  1739  3906 V BaseAuthAsyncOperation: access token request failed
,08-12 22:29:29.670  3143  3905 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 22:29:29.762  1528  3188 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-12 22:29:29.762  1528  3188 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 22:29:29.762  1528  3188 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:29:29.762  1528  3188 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:29:29.799  3143  3905 E KeepSync: IOException
08-12 22:29:29.799  3143  3905 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 22:29:29.799  3143  3905 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:29:29.799  3143  3905 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 22:29:29.799  3143  3905 E KeepSync: 	... 10 more
08-12 22:29:29.799  3143  3905 W KeepSync: Sync result 2
,08-12 22:29:29.812   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 249526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:29:33.725   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:29:41.485   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:29:59.379   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=279570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:30:00.001  3606  3908 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 22:30:00.038  3606  3909 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 22:30:00.056  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:00.059  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:00.105  1528  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 22:30:00.105  1528  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 22:30:00.105  1528  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:30:00.105  1528  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:30:00.141  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:00.146  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:00.189  1528  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 22:30:00.189  1528  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 22:30:00.190  1528  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:30:00.190  1528  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:30:00.204  3606  3909 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 22:30:00.205  3606  3908 E BooksSync: Soft error
08-12 22:30:00.205  3606  3908 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 22:30:00.205  3606  3908 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 22:30:00.205  3606  3908 E BooksSync: Sync error
08-12 22:30:00.205  3606  3908 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 22:30:00.205  3606  3908 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 22:30:00.205  3606  3908 I BooksSync: Finished books sync
,08-12 22:30:00.209   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 251281, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:30:06.832   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=287024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:30:24.712   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=304903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:30:30.630  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:30.631  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:30:30.661  1528  2310 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 22:30:30.661  1528  2310 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 22:30:30.661  1528  2310 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:30:30.661  1528  2310 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:30:30.682  3005  3917 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 22:30:30.682  3005  3917 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at blb.a(PG:3937)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at czp.a(PG:18188)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:30:30.682  3005  3917 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	... 12 more
08-12 22:30:30.682  3005  3917 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at fal.a(PG:38)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:30:30.682  3005  3917 E HttpOperation: 	... 14 more
,08-12 22:30:30.745  1528  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 22:30:30.745  1528  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 22:30:30.745  1528  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:30:30.745  1528  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:30:30.769  3005  3917 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 22:30:30.769  3005  3917 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at hec.a(PG:42)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at hee.a(PG:102)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at czr.a(PG:65)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at kka.a(PG:108)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at czp.a(PG:19176)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:30:30.769  3005  3917 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	... 15 more
08-12 22:30:30.769  3005  3917 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at fal.a(PG:38)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:30:30.769  3005  3917 E HttpOperation: 	... 17 more
,08-12 22:30:30.769  3005  3917 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 22:30:30.769  3005  3917 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at hec.a(PG:42)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at hee.a(PG:102)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at czr.a(PG:65)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at kka.a(PG:108)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	,at czq.run(PG:1686)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jdm.a(PG:77)
,08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	... 15 more
08-12 22:30:30.769  3005  3917 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at fal.a(PG:38)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 22:30:30.769  3005  3917 E ExperimentLoader: 	... 17 more
,08-12 22:30:30.866   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 282431, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:30:32.619   872  2123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=312810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:31:04.355  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:31:04.365  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:31:04.366  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:31:04.396  1528  3188 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 22:31:04.396  1528  3188 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 22:31:04.397  1528  3188 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:31:04.397  1528  3188 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:31:04.409  1528  3188 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 22:31:04.409  1528  3188 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 22:31:04.415  3544  3575 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 22:31:04.415  3544  3575 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 22:31:04.415  3544  3575 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 22:31:04.415  3544  3575 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 22:31:04.415  3544  3575 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 22:31:04.415  3544  3575 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 22:31:04.415  3544  3575 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 22:31:16.909  3809  3860 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 22:31:16.909  3809  3860 I jxcore-log: 
,08-12 22:31:17.526  3931  3931 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 22:31:17.532  3931  3931 D AndroidRuntime: CheckJNI is OFF
,08-12 22:31:17.567  3931  3931 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 22:31:17.609  3931  3931 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 22:31:17.630  3931  3931 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:31:17.644   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 22:31:17.645   872   885 I ActivityManager: Killing 3809:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 22:31:17.793   872   895 W PackageSettings: Skipping PackageSetting{1815503 com.example.hello/10273} due to missing metadata
,08-12 22:31:17.812   872  1308 D WifiService: Client connection lost with reason: 4
,08-12 22:31:17.813   872  1964 D GraphicsStats: Buffer count: 2
,08-12 22:31:17.813   872  1938 I WindowState: WIN DEATH: Window{c0ae224 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:31:17.841   872   895 I art     : Starting a blocking GC Explicit
,08-12 22:31:17.876   872   885 E libprocessgroup: failed to kill 1 processes for processgroup 3809
,08-12 22:31:17.877   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 22:31:17.877   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-12 22:31:17.878   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-12 22:31:17.878   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 22:31:17.878   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:17.878   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:17.878   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:31:17.878   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 22:31:17.879   872   885 I ActivityManager:   Force finishing activity ActivityRecord{5d4dff5 u0 com.test.thalitest/.MainActivity t2}
,08-12 22:31:17.890   872  1964 W ActivityManager: Spurious death for ProcessRecord{a8ec7c1 0:com.test.thalitest/u0a0}, curProc for 3809: null
,08-12 22:31:17.913   872   895 I art     : Explicit concurrent mark sweep GC freed 23275(1602KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.175ms total 71.766ms
,08-12 22:31:17.934   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 22:31:17.937  3931  3931 I art     : System.exit called, status: 0
08-12 22:31:17.937  3931  3931 I AndroidRuntime: VM exiting with result code 0.
,08-12 22:31:17.942   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 22:31:17.968   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 22:31:17.973  2698  2698 D BluetoothMapAppObserver: onReceive
,08-12 22:31:17.974  2698  2698 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 22:31:17.975  2158  2304 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 22:31:17.981   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 22:31:17.986  1854  1854 I Keyboard.Facilitator: resetDictionaries() : en_US
08-12 22:31:17.987  3674  3674 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 22:31:17.989  1854  3942 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 22:31:17.992  1854  3942 I Decoder : createOrResetDecoder
,08-12 22:31:18.022  1907  1907 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 22:31:18.026  1528  1528 I ConfigService: onCreate
,08-12 22:31:18.049  1711  3947 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 22:31:18.064  1711  1757 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjB29B359C1) - 
,--------- beginning of crash
08-12 22:31:18.065  1711  1757 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-12 22:31:18.065  1711  1757 E AndroidRuntime: Process: android.process.acore, PID: 1711
08-12 22:31:18.065  1711  1757 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.065  1711  1757 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 22:31:18.071   872  3949 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.071   872  3949 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.071   872  3949 E DropBoxManagerService: 	... 5 more
,08-12 22:31:18.075  1711  3947 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 22:31:18.075  1711  3947 I Process : Sending signal. PID: 1711 SIG: 9
08-12 22:31:18.075   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 22:31:18.083  1854  3942 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 22:31:18.097  1528  1528 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-12 22:31:18.098  1528  1528 D AndroidRuntime: Shutting down VM
,08-12 22:31:18.100  1528  1528 E AndroidRuntime: FATAL EXCEPTION: main
08-12 22:31:18.100  1528  1528 E AndroidRuntime: Process: com.google.process.gapps, PID: 1528
08-12 22:31:18.100  1528  1528 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 22:31:18.100  1528  1528 E AndroidRuntime: 	... 8 more
,08-12 22:31:18.105  1528  1528 I Process : Sending signal. PID: 1528 SIG: 9
,08-12 22:31:18.106   872  3952 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.106   872  3952 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.106   872  3952 E DropBoxManagerService: 	... 5 more
,08-12 22:31:18.114  1922  2001 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 22:31:18.114   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 22:31:18.115   872   884 E PackageManager: Failed to write settings, restoring backup
08-12 22:31:18.115   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 22:31:18.115   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 22:31:18.115   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 22:31:18.115   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 22:31:18.115   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 22:31:18.115   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.115   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.115   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 22:31:18.116   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-12 22:31:18.116   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 22:31:18.116   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.116   872   885 E DropBoxManagerService: 	... 13 more
,08-12 22:31:18.122  1854  3942 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 22:31:18.124  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 22:31:18.124  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 22:31:18.126  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 22:31:18.126  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 22:31:18.127  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 22:31:18.127  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 22:31:18.127  1854  3942 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 22:31:18.128   872  2152 I ActivityManager: Start proc 3953:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 22:31:18.128  1922  2001 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 22:31:18.128  1922  2001 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1922
08-12 22:31:18.128  1922  2001 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.128  1922  2001 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 22:31:18.129   872  1960 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 22:31:18.130   872  3958 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.130   872  3958 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.130   872  3958 E DropBoxManagerService: 	... 5 more
08-12 22:31:18.133  1922  2001 I Process : Sending signal. PID: 1922 SIG: 9
,08-12 22:31:18.141  1854  3942 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-12 22:31:18.141  1854  3942 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 22:31:18.141  1854  3942 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 22:31:18.141  1854  3942 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-12 22:31:18.142  1854  3942 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 22:31:18.183   872  1308 D WifiService: Client connection lost with reason: 4
,08-12 22:31:18.188   872  2155 I ActivityManager: Process com.google.process.gapps (pid 1528) has died
,08-12 22:31:18.188   872  2155 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 1000ms
08-12 22:31:18.188   872  2155 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
08-12 22:31:18.188   872  2155 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-12 22:31:18.188   872  2155 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,08-12 22:31:18.188   872  1963 D GraphicsStats: Buffer count: 1
08-12 22:31:18.188   872  2155 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 41000ms
08-12 22:31:18.189   872   882 I WindowState: WIN DEATH: Window{ed192d5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-12 22:31:18.203   872  1938 I ActivityManager: Start proc 3966:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
,08-12 22:31:18.214   872  1964 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1922) has died
,08-12 22:31:18.215   872  1964 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 50974ms
,08-12 22:31:18.219   872  2153 I ActivityManager: Process android.process.acore (pid 1711) has died
08-12 22:31:18.220   872  2153 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 50969ms
,08-12 22:31:18.221  1739  1739 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-12 22:31:18.270  3966  3966 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 22:31:18.281  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 22:31:18.281  1739  1739 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 22:31:18.288  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 22:31:18.288  1739  1739 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 22:31:18.293  3966  3966 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 22:31:18.293  3966  3966 I MultiDex: install
08-12 22:31:18.293  3966  3966 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 22:31:18.306   872  1960 I ActivityManager: Start proc 3985:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-12 22:31:18.307  1739  3984 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 22:31:18.309  1986  3983 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 22:31:18.349  1739  3984 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 22:31:18.349  1739  3984 E AndroidRuntime: Process: com.google.android.gms, PID: 1739
08-12 22:31:18.349  1739  3984 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:31:18.349  1739  3984 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-12 22:31:18.354  3966  3966 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-12 22:31:18.357  1739  3984 I Process : Sending signal. PID: 1739 SIG: 9
08-12 22:31:18.358   872  3998 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.358   872  3998 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.358   872  3998 E DropBoxManagerService: 	... 5 more
,08-12 22:31:18.374  1986  3983 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 22:31:18.377   279   279 E lowmemorykiller: Error writing /proc/1739/oom_score_adj; errno=22
,08-12 22:31:18.383  3966  3966 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-12 22:31:18.392  3966  3966 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:31:18.392  3966  3966 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 22:31:18.392  3966  3966 D AndroidRuntime: Shutting down VM
08-12 22:31:18.393  3966  3966 E AndroidRuntime: FATAL EXCEPTION: main
08-12 22:31:18.393  3966  3966 E AndroidRuntime: Process: com.google.process.gapps, PID: 3966
08-12 22:31:18.393  3966  3966 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 22:31:18.393  3966  3966 E AndroidRuntime: 	... 10 more
08-12 22:31:18.395   872  1938 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-12 22:31:18.395   872  1938 I ActivityManager: Killing 3966:com.google.process.gapps/u0a11 (adj 0): crash
08-12 22:31:18.396   872  3999 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:31:18.396   872  3999 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:31:18.396   872  3999 E DropBoxManagerService: 	... 5 more
08-12 22:31:18.401  1986  3983 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 22:31:18.401  1986  3983 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 22:31:18.401  1986  3983 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1986
08-12 22:31:18.401  1986  3983 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.401  1986  3983 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:31:18.424  3985  3985 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 22:31:18.424  3985  3985 D AndroidRuntime: Shutting down VM
,08-12 22:31:18.443   872  2156 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@17de1e3)

```
