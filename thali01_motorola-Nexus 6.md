#### Test 8091062436177d0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 09:06:11.470   871  2146 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 09:06:12.200  3639  3639 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 09:06:12.205  3639  3639 D AndroidRuntime: CheckJNI is OFF
08-11 09:06:12.247  3639  3639 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 09:06:12.297  3639  3639 I Radio-JNI: register_android_hardware_Radio DONE
08-11 09:06:12.319  3639  3639 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 09:06:12.323   871  1755 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:06:12.360  1823  1836 W SearchService: Abort, client detached.
08-11 09:06:12.369  1823  1823 I HotwordDetector: Closing mic
08-11 09:06:12.369  1823  2166 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@eaef894
08-11 09:06:12.369  1823  2188 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 09:06:12.370  3639  3639 D AndroidRuntime: Shutting down VM
08-11 09:06:12.392   871  1721 I ActivityManager: Start proc 3648:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 09:06:12.439   374  2191 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 09:06:12.441   374  2191 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 09:06:12.447   374  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 09:06:12.448  1823  2179 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 09:06:12.449  1823  2186 I MicroRecognitionRnrImpl: Detection finished
08-11 09:06:12.476  3648  3648 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 09:06:12.498  3648  3648 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 09:06:12.507  3648  3648 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6498-6501)
08-11 09:06:12.507  3648  3648 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:06:12.522  3648  3648 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cb96d7}
08-11 09:06:12.522  3648  3648 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:06:12.523  3648  3648 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 09:06:12.529  3648  3648 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 09:06:12.530  3648  3648 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 09:06:12.546  3648  3648 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 09:06:12.557  3648  3648 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:06:12.557  3648  3648 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:06:12.557  3648  3648 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 09:06:12.557  3648  3648 I Adreno  : Build Date                       : 10/20/15
08-11 09:06:12.557  3648  3648 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 09:06:12.557  3648  3648 I Adreno  : Local Branch                     : M14
08-11 09:06:12.557  3648  3648 I Adreno  : Remote Branch                    : 
08-11 09:06:12.557  3648  3648 I Adreno  : Remote Branch                    : 
08-11 09:06:12.557  3648  3648 I Adreno  : Reconstruct Branch               : 
,08-11 09:06:12.605   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f3cd3e8:true
,08-11 09:06:12.646  3648  3648 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 09:06:12.658  3648  3648 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 09:06:12.736  3648  3687 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 09:06:12.744  3648  3674 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 09:06:12.775  3648  3687 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 09:06:12.847   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms
,08-11 09:06:12.848  1663  1663 I Keyboard.Facilitator: onFinishInput()
,08-11 09:06:12.925  3648  3648 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3648
,08-11 09:06:13.041  3648  3648 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:06:13.222   871  3074 I ActivityManager: Killing 3095:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 09:06:13.234  3648  3689 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1694893776
,08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 09:06:13.253  3648  3689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39911fa added. We now have 1 listener(s)
,08-11 09:06:13.262  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 09:06:13.264  3648  3689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 09:06:13.265  3648  3689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 09:06:13.266  3648  3689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 09:06:13.271   871  3074 I ActivityManager: Killing 2954:com.google.android.apps.maps/u0a65 (adj 15): empty #18
08-11 09:06:13.271  3648  3689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28375a1 added. We now have 1 listener(s)
08-11 09:06:13.272  3648  3689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 09:06:13.279   871  1313 D WifiService: New client listening to asynchronous messages
,08-11 09:06:13.281  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 09:06:13.281  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 09:06:13.281  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 09:06:13.281  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:06:13.281  3648  3689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 09:06:13.334  3648  3689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 09:06:13.334  3648  3689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 09:06:13.343  3648  3689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:06:13.344  3648  3689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 09:06:13.344  3648  3689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-11 09:06:13.344  3648  3689 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 09:06:13.344  3648  3689 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 09:06:13.533  3648  3648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:06:13.538  3648  3648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 09:06:13.541  3648  3648 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:06:14.527  3648  3698 W jxcore-log: Initializing JXcore engine
,08-11 09:06:14.528  3648  3698 W jxcore-log: JXcore engine is ready
,08-11 09:06:14.575  3698  3698 W Thread-326: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 09:06:14.575  3698  3698 W Thread-326: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12829]" dev="sockfs" ino=12829 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 09:06:14.575  3698  3698 W Thread-326: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 09:06:14.575  3698  3698 W Thread-326: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24897]" dev="sockfs" ino=24897 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 09:06:14.587  3648  3698 W jxcore-log: Starting JXcore engine
,08-11 09:06:14.673  3648  3698 W jxcore-log: Platform android
08-11 09:06:14.673  3648  3698 W jxcore-log: 
,08-11 09:06:14.673  3648  3698 W jxcore-log: Process ARCH arm
08-11 09:06:14.673  3648  3698 W jxcore-log: 
,08-11 09:06:14.831  3648  3698 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:06:14.831  3648  3698 I jxcore-log: 
,08-11 09:06:14.832  3648  3698 W jxcore-log: JXcore engine is started
,08-11 09:06:14.840  3648  3689 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 09:06:14.844  3648  3648 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 09:06:19.371   871  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-11 09:06:22.355  3451  3707 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 09:06:22.385  3451  3708 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 09:06:22.404  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.408  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.510  1500  2848 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 09:06:22.510  1500  2848 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 09:06:22.510  1500  2848 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 09:06:22.510  1500  2848 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:06:22.537  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.540  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.566  1500  2848 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 09:06:22.566  1500  2848 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 09:06:22.566  1500  2848 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:06:22.566  1500  2848 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:06:22.580  3451  3708 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 09:06:22.580  3451  3707 E BooksSync: Soft error
08-11 09:06:22.580  3451  3707 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 09:06:22.580  3451  3707 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 09:06:22.580  3451  3707 E BooksSync: Sync error
08-11 09:06:22.580  3451  3707 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 09:06:22.580  3451  3707 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 09:06:22.580  3451  3707 I BooksSync: Finished books sync
,08-11 09:06:22.644   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126305, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 09:06:22.671  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.676  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.678  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 09:06:22.686  2991  3712 V KeepSync: Connecting to GoogleApiClient
08-11 09:06:22.686   871  1759 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 09:06:22.697  1500  2848 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 09:06:22.697  1500  2848 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 09:06:22.697  1500  2848 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:06:22.698  1500  2848 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:06:22.710  3391  3391 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 09:06:22.710  3391  3391 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 09:06:22.710  3391  3391 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-11 09:06:22.731  1500  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 09:06:22.731  1500  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 09:06:22.732  1500  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:06:22.732  1500  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:06:22.743  1860  3713 V BaseAuthAsyncOperation: access token request failed
08-11 09:06:22.744  2991  3712 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 09:06:22.786  1500  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 09:06:22.786  1500  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 09:06:22.787  1500  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 09:06:22.787  1500  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 09:06:22.800  2991  3712 E KeepSync: IOException
08-11 09:06:22.800  2991  3712 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 09:06:22.800  2991  3712 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 09:06:22.800  2991  3712 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 09:06:22.800  2991  3712 E KeepSync: 	... 10 more
,08-11 09:06:22.800  2991  3712 W KeepSync: Sync result 2
,08-11 09:06:22.812   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126325, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 09:06:25.061  3648  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:06:25.061  3648  3698 I jxcore-log: 
,08-11 09:06:25.063  3648  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:06:25.063  3648  3698 I jxcore-log: 
,08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:06:25.072  3648  3698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 09:06:25.077  3648  3698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 09:06:25.079  3648  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:06:25.079  3648  3698 I jxcore-log: 
,08-11 09:06:25.081  3648  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:06:25.081  3648  3698 I jxcore-log: 
,08-11 09:06:25.420  3648  3698 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 09:06:25.420  3648  3698 I jxcore-log: Failed to execute UT.
08-11 09:06:25.420  3648  3698 I jxcore-log: 
08-11 09:06:25.420  3648  3698 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:06:25.420  3648  3698 I jxcore-log: 
,08-11 09:06:25.423  3648  3698 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:06:25.423  3648  3698 I jxcore-log: 
08-11 09:06:25.433  3648  3648 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 09:06:26.088  3715  3715 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 09:06:26.094  3715  3715 D AndroidRuntime: CheckJNI is OFF
,08-11 09:06:26.138  3715  3715 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 09:06:26.187  3715  3715 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 09:06:26.210  3715  3715 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:06:26.221   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 09:06:26.222   871   884 I ActivityManager: Killing 3648:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 09:06:26.330   871  3074 D GraphicsStats: Buffer count: 2
,08-11 09:06:26.330   871  1388 I WindowState: WIN DEATH: Window{4410718 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:06:26.330   871  1313 D WifiService: Client connection lost with reason: 4
,08-11 09:06:26.355   871   884 W ActivityManager: Force removing ActivityRecord{592e959 u0 com.test.thalitest/.MainActivity t8}: app died, no saved state
,08-11 09:06:26.360   871   894 W PackageSettings: Skipping PackageSetting{316f4b2 com.example.hello/10273} due to missing metadata
,08-11 09:06:26.387   871   894 I art     : Starting a blocking GC Explicit
,08-11 09:06:26.390   871   882 W ActivityManager: Spurious death for ProcessRecord{406c7dd 0:com.test.thalitest/u0a0}, curProc for 3648: null,
,08-11 09:06:26.415   871  1721 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3648 uid 10000
,08-11 09:06:26.417  1663  1663 I Keyboard.Facilitator: onFinishInput()
,08-11 09:06:26.478  1823  3728 I MicroRecognitionRnrImpl: Starting detection.
,08-11 09:06:26.479   871   894 I art     : Explicit concurrent mark sweep GC freed 27565(1738KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.680ms total 91.804ms
,08-11 09:06:26.480  1823  3729 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@9ce361e
,08-11 09:06:26.486   374  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 09:06:26.486   374  3731 I AudioFlinger: AudioFlinger's thread 0xb1e40000 ready to run
08-11 09:06:26.488  1823  3729 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@9ce361e
,08-11 09:06:26.498   374  3731 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-11 09:06:26.498   374  3731 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-11 09:06:26.498   374  3731 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-11 09:06:26.500   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 09:06:26.502  3715  3715 I art     : System.exit called, status: 0
08-11 09:06:26.502  3715  3715 I AndroidRuntime: VM exiting with result code 0.
,08-11 09:06:26.507   374  3731 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-11 09:06:26.511   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 09:06:26.538  2570  2570 D BluetoothMapAppObserver: onReceive
,08-11 09:06:26.538  2570  2570 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-11 09:06:26.543  3521  3521 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-11 09:06:26.544  1663  1663 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 09:06:26.546  1783  2028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:06:26.547  1663  3735 I Keyboard.Facilitator.DecoderInitializer: run()
08-11 09:06:26.547   871  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 09:06:26.549  1663  3735 I Decoder : createOrResetDecoder
,08-11 09:06:26.588  1725  1725 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 09:06:26.589  1823  1823 I HotwordWorkerImpl: onReady
,08-11 09:06:26.599  1500  1500 I ConfigService: onCreate
,08-11 09:06:26.624  1663  3735 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 09:06:26.632  1500  1500 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-11 09:06:26.632  1500  1500 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-11 09:06:26.637   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 09:06:26.638  2969  3739 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 09:06:26.657  1860  3742 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-11 09:06:26.657  1860  3742 D AccountUtils: Clearing selected account for com.test.thalitest
,08-11 09:06:26.667  1663  3735 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-11 09:06:26.669  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-11 09:06:26.669  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 09:06:26.671  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 09:06:26.671  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 09:06:26.672  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-11 09:06:26.672  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-11 09:06:26.673  1663  3735 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 09:06:26.673  1663  3735 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-11 09:06:26.673  1663  3735 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 09:06:26.674  1663  3735 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-11 09:06:26.674  1663  3735 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 09:06:26.675  1663  3735 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-11 09:06:26.685  1860  3742 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-11 09:06:26.689  1860  1860 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-11 09:06:26.690  1860  1860 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-11 09:06:26.699  1860  1860 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-11 09:06:26.699  1860  1860 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-11 09:06:26.703  1860  3751 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-11 09:06:26.706  1860  3748 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-11 09:06:26.706  1860  3748 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-11 09:06:26.710  1860  3748 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,08-11 09:06:26.710  1860  3748 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,08-11 09:06:26.713   871  1388 I ActivityManager: Start proc 3753:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 09:06:26.713  1860  2932 E SQLiteLog: (3850) statement aborts at 167: [DELETE FROM FileContent143 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,--------- beginning of crash
08-11 09:06:26.713  1740  1843 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 09:06:26.713  1740  1843 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1740
08-11 09:06:26.713  1740  1843 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
,08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.713  1740  1843 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.713  1860  2932 E DocListDatabase: Failed to delete from FileContent143 table,
08-11 09:06:26.713  1860  2932 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:327)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(SourceFile:970)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at com.google.android.gms.drive.i.bz.run(SourceFile:51)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.713  1860  2932 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.716  1860  2932 I Process : Sending signal. PID: 1860 SIG: 9
08-11 09:06:26.717   871  1722 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-11 09:06:26.720   279   279 E lowmemorykiller: Error writing /proc/1860/oom_score_adj; errno=22
,08-11 09:06:26.721   871  3759 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:06:26.721   871  3759 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.721   871  3759 E DropBoxManagerService: 	... 5 more
08-11 09:06:26.722  1823  2256 W SearchService: Abort, client detached.
08-11 09:06:26.724   871   883 E PackageManager: Failed to write settings, restoring backup,
08-11 09:06:26.724   871   883 E PackageManager: java.io.IOException: write failed: EROFS (Read-only file system)
08-11 09:06:26.724   871   883 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-11 09:06:26.724   871   883 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-11 09:06:26.724   871   883 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
08-11 09:06:26.724   871   883 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
08-11 09:06:26.724   871   883 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
08-11 09:06:26.724   871   883 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
08-11 09:06:26.724   871   883 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
08-11 09:06:26.724   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
08-11 09:06:26.724   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 09:06:26.724   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 09:06:26.724   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:26.724   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.724   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.724   871   883 E PackageManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-11 09:06:26.724   871   883 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
08-11 09:06:26.724   871   883 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
08-11 09:06:26.724   871   883 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-11 09:06:26.724   871   883 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-11 09:06:26.724   871   883 E PackageManager: 	... 12 more
08-11 09:06:26.726   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-11 09:06:26.726   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.726   871   884 E DropB,oxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 09:06:26.726   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.726   871   884 E DropBoxManagerService: 	... 13 more
08-11 09:06:26.729  1823  1823 I HotwordDetector: Closing mic
08-11 09:06:26.730  1823  2166 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9ce361e
08-11 09:06:26.730  1823  3729 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 09:06:26.734   871  3768 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-11 09:06:26.738  1823  3764 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 09:06:26.756   871   884 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,08-11 09:06:26.780   871  1387 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@bf6915)
,08-11 09:06:26.781   871  1314 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 09:06:26.781   871  1314 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 09:06:26.784   871  3768 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 09:06:26.784   871  3768 I Adreno  : Build Date                       : 10/20/15
08-11 09:06:26.784   871  3768 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 09:06:26.784   871  3768 I Adreno  : Local Branch                     : M14
08-11 09:06:26.784   871  3768 I Adreno  : Remote Branch                    : 
08-11 09:06:26.784   871  3768 I Adreno  : Remote Branch                    : 
08-11 09:06:26.784   871  3768 I Adreno  : Reconstruct Branch               : 
08-11 09:06:26.786   871  1757 I ActivityManager: Process com.google.android.gms (pid 1860) has died
,08-11 09:06:26.786   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
,08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
,08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
,08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.people.service.PeopleService in 21000ms
,08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30999ms
,08-11 09:06:26.787   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 40999ms
08-11 09:06:26.788   871  1757 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInBrokerService in 40999ms
08-11 09:06:26.794   374  3731 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-11 09:06:26.796   374  3731 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-11 09:06:26.796   871  3768 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 09:06:26.802   374  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-11 09:06:26.813  1823  3728 I MicroRecognitionRnrImpl: Detection finished
,08-11 09:06:26.814  1823  2179 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 09:06:26.815   871  1713 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-11 09:06:26.828  1740  1740 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b120a2e new=com.google.android.velvet.VelvetApplication@b120a2e
,08-11 09:06:26.838   871  1755 I ActivityManager: Start proc 3777:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-11 09:06:26.880  1740  1740 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-11 09:06:26.889  3777  3777 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
,08-11 09:06:26.890  1823  3764 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 09:06:26.898  3777  3777 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-11 09:06:26.900  1740  2177 E ReflectionEngine: Failed to save models
08-11 09:06:26.900  1740  2177 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.900  1740  2177 E ReflectionEngine: 	... 16 more
,08-11 09:06:26.905   871  1757 I ActivityManager: Start proc 3790:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-11 09:06:26.910  1823  3764 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-11 09:06:26.922  1740  2177 E ObservedEventLogger: Failed to write the stream file
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2427: open failed: EROFS (Read-only file system)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.922  1740  2177 E ObservedEventLogger: 	... 16 more
,08-11 09:06:26.924  1740  2177 E ObservedEventLogger: Failed to write the stream file
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.924  1740  2177 E ObservedEventLogger: 	... 16 more
,08-11 09:06:26.930  1823  3764 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-11 09:06:26.930  1823  3764 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1823
08-11 09:06:26.930  1823  3764 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.930  1823  3764 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.939  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.940  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.941  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:26.941  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-11 09:06:26.943   871   881 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-11 09:06:26.943   871  3805 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:06:26.943   871  3805 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:26.943   871  3805 E DropBoxManagerService: 	... 5 more
08-11 09:06:26.943   871   881 I ActivityManager: Killing 1823:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-11 09:06:26.977  3777  3806 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.977  3777  3806 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-11 09:06:26.977  3777  3806 E AndroidRuntime: Process: com.android.keychain, PID: 3777
08-11 09:06:26.977  3777  3806 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 09:06:26.977  3777  3806 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 09:06:26.988  3790  3790 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-11 09:06:26.998  3790  3790 I MultiDex: VM with version 2.1.0 has multidex support
08-11 09:06:26.998  3790  3790 I MultiDex: install
08-11 09:06:26.998  3790  3790 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 09:06:27.013   871  1313 D WifiService: Client connection lost with reason: 4
,08-11 09:06:27.020   871  1745 W ActivityManager: Spurious death for ProcessRecord{30eec29 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 1823: null
,08-11 09:06:27.022   871   889 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +203ms
,08-11 09:06:27.024   871  3807 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:06:27.024   871  3807 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 09:06:27.024   871  3807 E DropBoxManagerService: 	... 5 more
,08-11 09:06:27.042  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:27.043  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-11 09:06:27.061   871   871 I ActivityManager: Start proc 3809:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-11 09:06:27.066  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:27.067  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-11 09:06:27.069  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:27.069  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-11 09:06:27.070  1500  3726 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 09:06:27.071  1500  3726 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-11 09:06:27.097   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
,08-11 09:06:27.097   281   281 E qdoverlay: MdpData failed to play
08-11 09:06:27.097   281   281 E qdoverlay: == Dump MdpData start ==
,08-11 09:06:27.097   281   281 E qdoverlay: == Dump OvFD fd=37 path=/dev/graphics/fb0 start/end ==
,08-11 09:06:27.097   281   281 E qdoverlay: mOvData msmfb_overlay_data id=16
,08-11 09:06:27.097   281   281 E qdoverlay: data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
,08-11 09:06:27.097   281   281 E qdoverlay: == Dump MdpData end ==
,08-11 09:06:27.097   281   281 E qdhwcomposer: draw: queue failed for left of dpy = 0
08-11 09:06:27.097   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
,08-11 09:06:27.098   281   281 E qdoverlay: MdpData failed to play
,08-11 09:06:27.098   281   281 E qdoverlay: == Dump MdpData start ==
,08-11 09:06:27.098   281   281 E qdoverlay: == Dump OvFD fd=30 path=/dev/graphics/fb0 start/end ==
08-11 09:06:27.098   281   281 E qdoverlay: mOvData msmfb_overlay_data id=8
,08-11 09:06:27.098   281   281 E qdoverlay: data msmfb_data offset=0 memid=31 id=0 flags=0x0 priv=0
08-11 09:06:27.098   281   281 E qdoverlay: == Dump MdpData end ==
,08-11 09:06:27.098   281   281 E qdhwcomposer: draw: queue failed for right of dpy = 0
,08-11 09:06:27.098   281   281 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
08-11 09:06:27.098   281   281 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
08-11 09:06:27.098   281   281 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
08-11 09:06:27.099   281   281 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-11 09:06:27.102   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20100 id=8
,08-11 09:06:27.102   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,08-11 09:06:27.102   281   281 E qdoverlay: src_rect mdp_rect x=720 y=0 w=720 h=2560
08-11 09:06:27.103   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-11 09:06:27.103   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-11 09:06:27.103   281   281 E qdoverlay: MdpCtrl close error in unset
,08-11 09:06:27.348   281   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
