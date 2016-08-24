#### Test 8251899684424f3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 17:07:49.348  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:07:49.357  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 17:07:49.359  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 17:07:49.405  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 17:07:49.405  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 17:07:49.406  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:07:49.406  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 17:07:49.452  3505  3505 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 17:07:49.453  3505  3505 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 17:07:49.458  3505  3505 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-24 17:07:49.933  3780  3780 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 17:07:49.938  3780  3780 D AndroidRuntime: CheckJNI is OFF
08-24 17:07:49.980  3780  3780 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 17:07:50.028  3780  3780 I Radio-JNI: register_android_hardware_Radio DONE
08-24 17:07:50.050  3780  3780 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 17:07:50.054   874  2223 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 17:07:50.082  2036  2050 W SearchService: Abort, client detached.
08-24 17:07:50.094  2036  2036 I HotwordDetector: Closing mic
08-24 17:07:50.095  2036  2343 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@bcaede5
08-24 17:07:50.095  2036  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 17:07:50.122  3780  3780 D AndroidRuntime: Shutting down VM
08-24 17:07:50.146   376  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 17:07:50.148   376  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 17:07:50.155   376  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 17:07:50.156  2036  2355 I MicroRecognitionRnrImpl: Detection finished
08-24 17:07:50.156  2036  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 17:07:50.160   874  2221 I ActivityManager: Start proc 3789:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 17:07:50.227  3789  3789 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 17:07:50.256  3789  3789 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 17:07:50.265  3789  3789 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 234-238)
08-24 17:07:50.266  3789  3789 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:07:50.303  3789  3789 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e2e60a}
08-24 17:07:50.304  3789  3789 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 17:07:50.304  3789  3789 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 17:07:50.313  3789  3789 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 17:07:50.315  3789  3789 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:07:50.356  3789  3789 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 17:07:50.387  3789  3789 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:50.387  3789  3789 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:50.387  3789  3789 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 17:07:50.387  3789  3789 I Adreno  : Build Date                       : 10/20/15
08-24 17:07:50.387  3789  3789 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 17:07:50.387  3789  3789 I Adreno  : Local Branch                     : M14
08-24 17:07:50.387  3789  3789 I Adreno  : Remote Branch                    : 
08-24 17:07:50.387  3789  3789 I Adreno  : Remote Branch                    : 
08-24 17:07:50.387  3789  3789 I Adreno  : Reconstruct Branch               : 
,08-24 17:07:50.512   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e30284:true
,08-24 17:07:50.535  3789  3789 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 17:07:50.551  3789  3789 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 17:07:50.618  3789  3828 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 17:07:50.644  3789  3814 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 17:07:50.696  3789  3828 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 17:07:50.809   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +688ms
,08-24 17:07:50.812  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-24 17:07:50.877  3789  3789 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3789
,08-24 17:07:50.946   874  1695 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-24 17:07:50.969  3789  3789 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 17:07:51.014   874  1695 I ActivityManager: Killing 3192:com.google.android.gm/u0a78 (adj 15): empty #18
,08-24 17:07:51.137  3789  3830 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1680672464
,08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 17:07:51.141  3789  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a43b76e added. We now have 1 listener(s)
,08-24 17:07:51.144  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 17:07:51.146  3789  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:07:51.146  3789  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:07:51.146  3789  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true,
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 17:07:51.149  3789  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44fa0a5 added. We now have 1 listener(s)
08-24 17:07:51.150  3789  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:07:51.152   874  1317 D WifiService: New client listening to asynchronous messages
08-24 17:07:51.153  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:07:51.153  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 17:07:51.153  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 17:07:51.153  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 17:07:51.153  3789  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 17:07:51.156  3789  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:51.156  3789  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 17:07:51.167  3789  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:51.168  3789  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:51.168  3789  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 17:07:51.168  3789  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:51.168  3789  3830 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 17:07:51.170  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:07:51.172  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:51.198  3789  3789 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 17:07:52.034  3789  3838 W jxcore-log: Initializing JXcore engine
,08-24 17:07:52.034  3789  3838 W jxcore-log: JXcore engine is ready
,08-24 17:07:52.069  3838  3838 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 17:07:52.069  3838  3838 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13187]" dev="sockfs" ino=13187 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 17:07:52.069  3838  3838 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 17:07:52.069  3838  3838 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25998]" dev="sockfs" ino=25998 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 17:07:52.083  3789  3838 W jxcore-log: Starting JXcore engine
,08-24 17:07:52.162  3789  3838 W jxcore-log: Platform android
08-24 17:07:52.162  3789  3838 W jxcore-log: 
,08-24 17:07:52.162  3789  3838 W jxcore-log: Process ARCH arm
08-24 17:07:52.162  3789  3838 W jxcore-log: 
,08-24 17:07:52.294   874  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 17:07:52.399  3789  3838 I jxcore-log: JXcore Cordova bridge is ready!
08-24 17:07:52.399  3789  3838 I jxcore-log: 
,08-24 17:07:52.400  3789  3838 W jxcore-log: JXcore engine is started
,08-24 17:07:52.408  3789  3830 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 17:07:52.412  3789  3789 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 17:07:52.637   874  1891 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 17:07:56.078  3593  3846 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 17:07:56.150  3593  3847 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 17:07:56.159  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:07:56.161  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:07:56.198  1524  2407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 17:07:56.198  1524  2407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 17:07:56.199  1524  2407 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:07:56.199  1524  2407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:07:56.219  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:07:56.220  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:07:56.234  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 17:07:56.234  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 17:07:56.234  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:07:56.234  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:07:56.247  3593  3847 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 17:07:56.248  3593  3846 E BooksSync: Soft error
08-24 17:07:56.248  3593  3846 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 17:07:56.248  3593  3846 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 17:07:56.248  3593  3846 E BooksSync: Sync error
08-24 17:07:56.248  3593  3846 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 17:07:56.248  3593  3846 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 17:07:56.248  3593  3846 I BooksSync: Finished books sync
,08-24 17:07:56.252   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126004, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 17:08:02.364  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 17:08:02.364  3789  3838 I jxcore-log: 
,08-24 17:08:02.367  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 17:08:02.367  3789  3838 I jxcore-log: 
,08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:02.379  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:02.385  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:02.387  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 17:08:02.387  3789  3838 I jxcore-log: 
,08-24 17:08:02.389  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 17:08:02.389  3789  3838 I jxcore-log: 
,08-24 17:08:02.883  3789  3838 D executeNativeTests: Running unit tests
,08-24 17:08:02.943  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:02.943  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be added. We now have 2 listener(s)
,08-24 17:08:02.944  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:02.944  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:02.944  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:02.944  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:02.944  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f added. We now have 2 listener(s)
08-24 17:08:02.944  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:02.945  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:02.953  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:02.964  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:02.970  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:02.971  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:02.979  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:02.980  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:08:02.980  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:08:02.981  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 17:08:02.984  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:02.985  3789  3838 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 17:08:02.986  3789  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-24 17:08:02.986  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 17:08:02.987  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 17:08:02.987  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:08:02.988  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-24 17:08:02.989  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:02.989  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:02.990  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:02.991  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:02.992  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:02.993  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:02.993  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be removed from the list
,08-24 17:08:02.994  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:02.994  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f removed from the list
,08-24 17:08:02.994  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:02.996  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.002  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.003  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.004  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:03.005  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:03.005  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.005  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.007  3789  3838 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-24 17:08:03.007  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.007  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.008  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:03.008  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.008  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.008  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.008  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.008  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.008  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.008  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:03.008  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.008  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.008  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.008  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.009  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:03.009  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:03.009  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.009  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.015  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 17:08:03.015  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:08:03.015  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:08:03.016  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:08:03.017  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:08:03.018  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:08:03.018  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.018  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.018  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.018  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.019  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.019  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.019  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.019  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.019  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.019  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.019  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.019  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.019  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 17:08:03.019  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.020  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.020  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.020  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.020  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.021  3789  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:08:03.023  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:03.027  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:03.030  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:03.030  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:03.030  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:08:03.031  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 17:08:03.031  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:03.032  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.032  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:08:03.033  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.035  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.037  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 17:08:03.037  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:03.042  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:03.044  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 17:08:03.044  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:03.046  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-24 17:08:03.049  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-24 17:08:03.050  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:03.050  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:08:03.051  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:03.052  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:03.056  2703  2888 D BtGatt.GattService: registerClient() - UUID=ce4341a3-e880-4333-9cc8-c0544c00a014
,08-24 17:08:03.057  2703  2755 D BtGatt.GattService: onClientRegistered() - UUID=ce4341a3-e880-4333-9cc8-c0544c00a014, clientIf=5
,08-24 17:08:03.059  3789  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 17:08:03.060  2703  2717 D BtGatt.GattService: start scan with filters
,08-24 17:08:03.064  2703  2760 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:03.064  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:03.064  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-24 17:08:03.065  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 17:08:03.065  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:03.065  2703  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:03.069  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.069  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:03.069  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.071  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:03.074  2703  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:03.074  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.074  2703  2760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 17:08:03.076  3789  3838 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:08:03.080  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.080  3789  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:03.080  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.080  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 17:08:03.080  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.081  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 17:08:03.081  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 17:08:03.081  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 17:08:03.081  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:03.081  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:03.082  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:03.082  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:03.083  3789  3838 D BluetoothAdapter: STATE_ON
08-24 17:08:03.083  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 17:08:03.083  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.083  2703  2760 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:08:03.084  2703  2760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 17:08:03.084  2703  2888 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:03.085  2703  2717 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-24 17:08:03.086  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:03.086  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:03.087  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:08:03.087  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:03.087  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:03.088  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:03.089  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:03.089  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:03.089  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:03.090  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:03.092  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:03.092  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:03.092  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.092  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:03.092  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:03.092  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:03.092  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
,08-24 17:08:03.092  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.092  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.094  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:03.094  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.095  3789  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:08:03.096  2703  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 17:08:03.096  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.099  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.105  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 17:08:03.105  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:03.106  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:03.109  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:03.109  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:03.111  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:08:03.111  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
,08-24 17:08:03.111  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:03.111  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.111  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:08:03.114  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.114  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:03.114  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.115  2703  2760 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:08:03.117  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 17:08:03.117  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:08:03.118  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.123  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 17:08:03.123  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.123  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:08:03.123  2703  2760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 17:08:03.124  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 17:08:03.125  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:03.129  2703  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 17:08:03.130  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.130  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:03.130  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:08:03.131  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:03.134  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:03.139  2703  2888 D BtGatt.GattService: registerClient() - UUID=13a48467-db27-418e-8875-e58d9c2a28ae
,08-24 17:08:03.139  2703  2755 D BtGatt.GattService: onClientRegistered() - UUID=13a48467-db27-418e-8875-e58d9c2a28ae, clientIf=5
,08-24 17:08:03.140  3789  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 17:08:03.140  2703  2715 D BtGatt.GattService: start scan with filters
,08-24 17:08:03.145  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:03.145  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-24 17:08:03.145  2703  2760 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:03.145  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 17:08:03.146  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:03.149  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.149  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.150  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:03.152  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:03.156  2703  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:03.156  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.157  2703  2760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 17:08:03.157  3789  3838 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:08:03.161  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.161  3789  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:03.161  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.161  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:08:03.161  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.162  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 17:08:03.162  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 17:08:03.162  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 17:08:03.162  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:03.162  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:03.162  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:03.162  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:03.163  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:03.164  2703  3469 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:03.165  2703  2715 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 17:08:03.165  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 17:08:03.165  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:08:03.165  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.165  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 17:08:03.166  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:08:03.166  2703  2760 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:08:03.166  2703  2760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 17:08:03.166  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:03.166  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:03.168  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:03.169  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:03.169  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:03.169  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:03.170  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:03.171  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:03.171  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:03.171  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:03.172  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:03.172  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.172  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:03.172  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list,
,08-24 17:08:03.172  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.172  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.172  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop,
,08-24 17:08:03.172  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.173  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.173  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.174  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.174  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.174  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.174  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.175  3789  3838 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:08:03.177  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.180  2703  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 17:08:03.180  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:03.187  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:03.189  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 17:08:03.189  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.190  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:03.190  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:03.191  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:08:03.191  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 17:08:03.191  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 17:08:03.191  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:03.191  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:03.195  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.197  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 17:08:03.197  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:08:03.198  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.198  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:03.198  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.198  2703  2760 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:03.204  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:03.204  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 17:08:03.205  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:03.207  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 17:08:03.207  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.207  2703  2760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 17:08:03.209  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:08:03.209  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:03.209  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:03.210  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:03.213  2703  2715 D BtGatt.GattService: registerClient() - UUID=1a87f2e8-33ba-4c00-bbd1-0db6fd76e419
,08-24 17:08:03.214  2703  2755 D BtGatt.GattService: onClientRegistered() - UUID=1a87f2e8-33ba-4c00-bbd1-0db6fd76e419, clientIf=5
,08-24 17:08:03.214  3789  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 17:08:03.214  2703  2888 D BtGatt.GattService: start scan with filters
,08-24 17:08:03.215  2703  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 17:08:03.215  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:03.217  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:03.218  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 17:08:03.218  2703  2760 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:03.218  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 17:08:03.218  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:03.221  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.221  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:08:03.221  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:03.223  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:03.226  3789  3838 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:08:03.226  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.226  3789  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:03.227  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.227  2703  2755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:03.227  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.227  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:08:03.227  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.227  2703  2760 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 17:08:03.227  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 17:08:03.227  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:08:03.227  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-24 17:08:03.227  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:03.227  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:03.227  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:03.227  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-24 17:08:03.228  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:03.229  2703  2888 D BtGatt.GattService: stopScan() - queue size =1,
08-24 17:08:03.230  2703  2717 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-24 17:08:03.231  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-24 17:08:03.231  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 17:08:03.231  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:08:03.231  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:08:03.231  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:03.232  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:03.232  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:08:03.232  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:03.232  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:03.233  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:03.235  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 17:08:03.235  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
,08-24 17:08:03.235  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.235  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:03.235  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:03.235  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.235  2703  2760 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:03.235  3789  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:03.235  2703  2760 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 17:08:03.235  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.235  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:03.235  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:03.236  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.236  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:03.236  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list,
,08-24 17:08:03.236  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.236  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.236  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:03.236  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.237  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.237  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.238  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.238  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.239  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.239  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.239  3789  3838 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 17:08:03.240  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.240  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.240  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.241  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.241  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.241  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.241  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
,08-24 17:08:03.241  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.241  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.241  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:03.241  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.241  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.242  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.242  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.243  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.243  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:03.243  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.243  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.245  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-24 17:08:03.245  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.245  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.245  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:03.245  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.245  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.245  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.245  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
,08-24 17:08:03.246  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.246  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.246  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop,
08-24 17:08:03.246  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.246  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-24 17:08:03.246  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.246  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.247  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:03.247  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.248  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.248  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.248  3789  3838 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 17:08:03.249  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:03.249  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.249  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.249  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.249  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 17:08:03.249  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.249  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.249  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:03.249  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.250  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.250  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.250  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.250  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.250  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:03.251  2703  2755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 17:08:03.251  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.252  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.252  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:03.252  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.252  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
,08-24 17:08:03.253  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 17:08:03.253  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.253  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.253  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.253  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:03.253  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:03.253  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.254  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.254  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.254  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.254  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.254  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.254  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.254  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.254  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.255  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.255  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.255  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.255  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.256  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:08:03.258  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:08:03.258  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:08:03.259  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:08:03.259  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:08:03.259  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:08:03.259  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.259  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.259  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.259  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 17:08:03.259  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.259  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.259  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.259  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.260  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listene,r org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.260  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.260  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.260  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.260  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.260  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.260  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.260  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.261  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.262  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.262  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.262  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.263  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:08:03.263  3789  3838 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:08:03.263  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 17:08:03.269  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:08:03.269  3789  3838 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 17:08:03.269  2703  2755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:03.269  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.269  2703  2760 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:08:03.270  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:08:03.270  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:08:03.270  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:08:03.270  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:08:03.270  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:08:03.271  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:08:03.272  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:08:03.273  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:08:03.273  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 17:08:03.273  3789  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:08:03.273  3789  3838 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 17:08:03.274  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:08:03.274  3789  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:08:03.274  3789  3838 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 17:08:03.274  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:08:03.274  3789  3838 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:08:03.274  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 17:08:03.278  2703  2755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 17:08:03.278  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.278  2703  2760 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 17:08:03.279  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 17:08:03.280  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 17:08:03.280  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 17:08:03.280  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 17:08:03.280  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 17:08:03.281  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 17:08:03.281  3789  3838 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:08:03.281  3789  3838 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 17:08:03.282  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.282  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.282  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.284  2703  2755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 17:08:03.284  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.284  2703  2755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:03.284  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.284  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.284  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 17:08:03.284  3789  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-24 17:08:03.285  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.285  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.285  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.285  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.285  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.285  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.285  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.285  3789  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-24 17:08:03.285  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.286  3789  3852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:03.286  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.286  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.286  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.286  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.287  3789  3838 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 17:08:03.287  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.287  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.288  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.288  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.288  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.288  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.288  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.289  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.289  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.289  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.289  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.289  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.289  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.289  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.292  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.292  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.292  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.292  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.293  3789  3838 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 17:08:03.293  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.293  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.293  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.293  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.293  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.293  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.294  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.294  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.294  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.294  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.294  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.294  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.294  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.294  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.295  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.295  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.295  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.295  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.295  3789  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 17:08:03.295  3789  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 17:08:03.295  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:08:03.295  3789  3838 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 17:08:03.295  3789  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:08:03.295  3789  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 17:08:03.296  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:08:03.296  3789  3838 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 17:08:03.296  3789  3838 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:08:03.296  3789  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:08:03.296  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:08:03.296  3789  3838 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 17:08:03.296  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.296  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.296  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.296  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.296  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.296  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.296  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.296  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.296  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.297  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.297  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.297  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.297  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.297  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.298  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.298  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.298  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.298  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.299  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.299  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.299  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.299  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.299  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.299  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.299  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.299  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.299  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.299  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.299  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.299  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.299  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.299  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.299  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.299  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.299  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.300  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.300  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.300  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.300  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.300  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.300  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.300  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.300  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.300  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.300  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.300  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.300  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.302  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.302  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.302  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.302  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.303  3789  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 17:08:03.303  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.304  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 17:08:03.304  3789  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 17:08:03.304  3789  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 17:08:03.305  3789  3789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 17:08:03.305  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 17:08:03.305  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:08:03.305  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.305  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 17:08:03.305  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 17:08:03.305  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 17:08:03.305  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.305  3789  3838 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 17:08:03.306  3789  3789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 17:08:03.306  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.306  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.306  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:03.306  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:03.306  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:03.306  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.306  3789  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:03.306  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.307  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:03.307  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:03.307  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:03.307  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:03.307  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.307  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.308  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.308  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.308  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.308  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.308  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.308  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.308  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.308  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.308  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.308  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.308  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.308  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.308  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.309  3789  3854 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 17:08:03.309  3789  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 17:08:03.309  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.309  3789  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 17:08:03.309  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.309  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.309  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.309  3789  3789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 17:08:03.310  3789  3838 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 17:08:03.311  3789  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:08:03.311  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:08:03.311  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:08:03.311  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.311  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.311  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.311  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.311  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.311  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.311  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.311  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.311  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.311  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.311  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.311  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.312  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.312  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.313  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.314  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.314  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.315  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.319  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.319  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:03.320  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.320  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.320  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.320  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.320  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.320  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.320  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.320  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.320  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.320  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.320  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.321  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.321  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.321  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.322  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.322  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.322  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:03.323  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:03.323  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:03.323  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:03.323  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.323  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.323  3789  3838 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@614d6be not in the list
08-24 17:08:03.323  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.323  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.323  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:03.324  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.324  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.324  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:03.324  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:03.326  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:03.326  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:03.326  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:03.326  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@541831f not in the list
08-24 17:08:03.327  3789  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 17:08:03.327  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:08:03.327  3789  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 17:08:03.327  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:08:03.328  3789  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 17:08:03.328  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:08:03.330  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:08:03.330  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 17:08:03.331  3789  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 17:08:03.331  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:08:03.331  3789  3838 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 17:08:03.331  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:08:03.331  3789  3838 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 17:08:03.331  3789  3838 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 17:08:03.332  3789  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 17:08:03.332  3789  3838 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 17:08:03.333  3789  3838 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 17:08:03.333  3789  3838 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 17:08:03.333  3789  3838 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 17:08:03.333  3789  3838 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 17:08:03.334  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:03.335  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80802e9 added. We now have 2 listener(s)
08-24 17:08:03.335  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:03.337  3789  3838 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 17:08:03.337   874  1927 D WifiService: setWifiEnabled: true pid=3789, uid=10000
08-24 17:08:03.337   874  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 17:08:03.338  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:03.338  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5826b6e added. We now have 3 listener(s)
08-24 17:08:03.339  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:03.347  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:03.348  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a57720f added. We now have 4 listener(s)
08-24 17:08:03.348  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:03.350  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:03.350  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@296529c added. We now have 5 listener(s)
08-24 17:08:03.351  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:03.355   874  1398 D WifiService: setWifiEnabled: false pid=3789, uid=10000
08-24 17:08:03.355   874  1398 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:08:03.358  2703  2751 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 17:08:03.359  2703  2751 D BluetoothAdapterProperties: Setting state to 13
08-24 17:08:03.359  2703  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:08:03.359  2703  2751 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 17:08:03.359  2703  2751 I BluetoothAdapterState: Entering PendingCommandState
08-24 17:08:03.360  2703  2755 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:03.360  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:03.361  2703  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-24 17:08:03.363  2703  2703 D BluetoothMapService: onReceive
08-24 17:08:03.363  2703  2703 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:03.364  2703  2703 D BluetoothMapService: STATE_TURNING_OFF
08-24 17:08:03.364  2703  2703 D BluetoothMapService: MAP Service closeService in
,08-24 17:08:03.364  2703  2703 D BluetoothMapMasInstance0: MAP Service shutdown
,08-24 17:08:03.364  2703  2703 D ObexServerSockets0: shutdown(block = true)
,08-24 17:08:03.365  2703  2703 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 17:08:03.365  2703  2703 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 17:08:03.365  2703  2896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 17:08:03.365  2703  2897 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-24 17:08:03.367  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:03.367  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:03.367  2703  2885 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 17:08:03.368  2703  2703 I BtOppRfcommListener: stopping Accept Thread
08-24 17:08:03.368  2703  3426 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 17:08:03.368  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:03.368  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:03.369  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:03.369  2703  3426 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 17:08:03.371  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.373  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.374  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 17:08:03.376  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:03.376  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:03.377   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 17:08:03.377   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-24 17:08:03.377   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 17:08:03.377   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:03.378  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:03.378  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:03.381  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.384  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.384   874   887 I ActivityManager: Start proc 3857:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-24 17:08:03.387  2703  2703 D HeadsetService: Received stop request...Stopping profile...
08-24 17:08:03.387  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.388  1359  1379 D BluetoothHeadset: Proxy object disconnected
,08-24 17:08:03.388  1940  2133 D BluetoothHeadset: Proxy object disconnected
,08-24 17:08:03.388   874   874 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:03.388   874   874 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:03.388   874   874 D BluetoothHeadset: Proxy object disconnected
,08-24 17:08:03.389  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-24 17:08:03.390  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.390  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.390  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.390  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:03.391  2703  2703 D A2dpService: Received stop request...Stopping profile...
08-24 17:08:03.391  2703  2891 D A2dpStateMachine: Exit Disconnected: -1
08-24 17:08:03.392   874  1893 D DhcpClient: Clearing IP address
,08-24 17:08:03.393   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:08:03.395   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:03.395  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:03.395   874   874 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:03.397  2703  2703 D HidService: Received stop request...Stopping profile...
08-24 17:08:03.397  2703  2703 D HidService: Stopping Bluetooth HidService
,08-24 17:08:03.397  1524  2486 V NativeCrypto: Read error: ssl=0xb068fa00: I/O error during system call, Connection timed out
08-24 17:08:03.398  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-24 17:08:03.398  1359  1359 D HidProfile: Bluetooth service disconnected
,08-24 17:08:03.398  2703  2703 D HealthService: Received stop request...Stopping profile...
08-24 17:08:03.399  1524  2486 V NativeCrypto: SSL shutdown failed: ssl=0xb068fa00: I/O error during system call, Broken pipe
,08-24 17:08:03.401   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 17:08:03.401   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-24 17:08:03.401   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-24 17:08:03.402   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 17:08:03.404   403   403 E Parcel  : Reading a NULL string not supported here.
,08-24 17:08:03.406   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-24 17:08:03.408   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-24 17:08:03.406  2703  2703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 17:08:03.413  2703  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-24 17:08:03.413  2703  2703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:08:03.413  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:03.413  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
08-24 17:08:03.413  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:03.413  2703  2755 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-24 17:08:03.416   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:03.417  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:03.417  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:03.417  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:03.417  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:03.418   874  1894 D DhcpClient: Receive thread stopped
,08-24 17:08:03.419   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:08:03.421  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:03.421  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:03.421  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:03.421  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:03.421  2703  2703 D PanService: Received stop request...Stopping profile...
08-24 17:08:03.423  2703  2703 D BluetoothMapService: Received stop request...Stopping profile...
08-24 17:08:03.424  2703  2703 D BluetoothMapService: stop()
08-24 17:08:03.424  2703  2703 D BluetoothMapAppObserver: deinitObservers()
08-24 17:08:03.424  2703  2703 D BluetoothMapAppObserver: removeReceiver()
,08-24 17:08:03.425  1993  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:08:03.425  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.425  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.425  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.425  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:03.427  2703  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-24 17:08:03.427  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.427  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.427  2703  2879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:03.427  2703  2879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:03.427  2703  2879 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:08:03.427  2703  2879 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:03.427  2703  2703 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:08:03.427  2703  2703 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.427  2703  2755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 17:08:03.427  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:03.427  2703  2703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-24 17:08:03.427  2703  2755 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 17:08:03.428  2703  2703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:08:03.428  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.428  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.428  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.428  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:03.428  2703  2703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-24 17:08:03.428  2703  2703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:08:03.429  2703  2703 D BluetoothMapService: MAP Service closeService in
08-24 17:08:03.429  2703  2703 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:03.429  2703  2703 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:03.429  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 17:08:03.429  2703  2703 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:03.429  2703  2703 D BluetoothMapService: cleanup()
08-24 17:08:03.429  2703  2703 D BluetoothMapService: MAP Service closeService in
,08-24 17:08:03.429  2703  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 17:08:03.429  2703  2751 D BluetoothAdapterProperties: Setting state to 15
08-24 17:08:03.429  2703  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 17:08:03.433   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:03.433   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:03.433   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 17:08:03.433  1359  1719 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 17:08:03.433  2703  2751 I BluetoothAdapterState: Entering BleOnState
08-24 17:08:03.435  1359  1717 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 17:08:03.438  1359  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:03.438  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 17:08:03.438  1359  1359 D PanProfile: Bluetooth service disconnected
08-24 17:08:03.438  1359  1379 D BluetoothPan: onBluetoothStateChange on: false
08-24 17:08:03.439   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:03.439  1940  2263 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 17:08:03.439  1359  1717 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:08:03.440  1359  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-24 17:08:03.441  2703  2751 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 17:08:03.441  2703  2751 D BluetoothAdapterProperties: Setting state to 16
,08-24 17:08:03.442  2703  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 17:08:03.442  2703  2751 D BluetoothAdapterProperties: onBleDisable
08-24 17:08:03.443  2703  2752 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 17:08:03.443  2703  2751 I BluetoothAdapterState: Entering PendingCommandState
08-24 17:08:03.444  1359  1359 D BluetoothMap: Proxy object disconnected
,08-24 17:08:03.444  2703  2755 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:03.444  2703  2879 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 17:08:03.444  2703  2879 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 17:08:03.444  3789  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,08-24 17:08:03.444  1359  1359 D MapProfile: Bluetooth service disconnected
,08-24 17:08:03.446  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.447  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.449  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.450  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.455   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:03.467  3857  3857 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-24 17:08:03.474   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:03.476   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-24 17:08:03.476   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:03.477   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-24 17:08:03.481  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:03.482  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:03.482  3372  3372 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a43b76e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-24 17:08:03.487  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:03.491   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40802e3:true
,08-24 17:08:03.492  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:03.504   874   884 I ActivityManager: Start proc 3875:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-24 17:08:03.512  3857  3857 D LocalBluetoothProfileManager: Adding local MAP profile
,08-24 17:08:03.514  3857  3857 D BluetoothMap: Create BluetoothMap proxy object
,08-24 17:08:03.528   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-24 17:08:03.530  3857  3857 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-24 17:08:03.541  3857  3857 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:03.546   874  1956 I ActivityManager: Killing 3372:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 17:08:03.553  3875  3875 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-24 17:08:03.648  2703  2755 I bt_hci  : shut_down
08-24 17:08:03.648  2703  2761 D bt_hwcfg: hw_epilog_process
,08-24 17:08:03.652  2703  2761 I bt_vendor: low_power_mode_cb
,08-24 17:08:03.680  2703  2761 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 17:08:03.680  2703  2761 I bt_vendor: epilog_cb
08-24 17:08:03.680  2703  2761 I bt_hci  : epilog_finished_callback
,08-24 17:08:03.684  2703  2755 I bt_hci_h4: hal_close
,08-24 17:08:03.685  2703  2755 I bt_userial_vendor: device fd = 51 close
,08-24 17:08:03.745  3875  3875 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.745  3875  3875 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.745  3875  3875 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.745  3875  3875 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.745  3875  3875 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.745  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.746  3875  3875 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.746  3875  3875 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.746  3875  3875 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:03.746  3875  3875 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:03.782   874  1939 I ActivityManager: Start proc 3906:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-24 17:08:03.783   874  1939 I ActivityManager: Killing 3557:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 17:08:03.808  3789  3789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:03.838  2703  2752 D bt_stack_manager: event_shut_down_stack finished.
,08-24 17:08:03.839  2703  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 17:08:03.843  2703  2703 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:08:03.843  2703  2751 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 17:08:03.843  3906  3906 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-24 17:08:03.843  2703  2703 D BtGatt.GattService: Received stop request...Stopping profile...
,08-24 17:08:03.843  2703  2703 D BtGatt.GattService: stop()
08-24 17:08:03.844  2703  2703 D BtGatt.AdvertiseManager: advertise clients cleared
08-24 17:08:03.845  2703  2703 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:03.845  2703  2703 V BluetoothAdapterState: isTurningOn()=false
,08-24 17:08:03.845  2703  2703 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:03.845  2703  2703 V BluetoothAdapterState: isBleTurningOff()=true
08-24 17:08:03.846  2703  2751 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-24 17:08:03.846  2703  2751 D BluetoothAdapterProperties: Setting state to 10
,08-24 17:08:03.847  2703  2751 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 17:08:03.848  2703  2751 I BluetoothAdapterState: Entering OffState
08-24 17:08:03.849   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 17:08:03.865  2703  2703 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 17:08:03.865  2703  2703 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 17:08:03.865  2703  2703 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 17:08:03.865  2703  2752 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 17:08:03.868  2703  2752 D bt_stack_manager: event_clean_up_stack finished.
,08-24 17:08:03.870  2703  2703 I art     : System.exit called, status: 0
,08-24 17:08:03.870  2703  2703 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 17:08:03.956   874  1939 I ActivityManager: Process com.android.bluetooth (pid 2703) has died
,08-24 17:08:03.969  3906  3906 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 17:08:03.995  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:04.019   874  1398 I ActivityManager: Start proc 3933:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-24 17:08:04.022  3857  3857 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:04.030   874   884 I ActivityManager: Killing 3443:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 17:08:04.159  3933  3933 D AdapterServiceConfig: Adding HeadsetService
08-24 17:08:04.160  3933  3933 D AdapterServiceConfig: Adding A2dpService
08-24 17:08:04.160  3933  3933 D AdapterServiceConfig: Adding HidService
08-24 17:08:04.160  3933  3933 D AdapterServiceConfig: Adding HealthService
,08-24 17:08:04.160  3933  3933 D AdapterServiceConfig: Adding PanService
,08-24 17:08:04.162  3933  3933 D AdapterServiceConfig: Adding GattService
,08-24 17:08:04.162  3933  3933 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 17:08:04.166  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:04.177  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 17:08:04.179  1724  1724 D SystemUpdateService: onCreate
,08-24 17:08:04.182  3875  3897 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-24 17:08:04.183  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 17:08:04.185  1724  3947 I SystemUpdateService: active receiver: enabled
,08-24 17:08:04.189  1724  3947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 17:08:04.191  1724  3947 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 17:08:04.192  1724  3947 I SystemUpdateService: now status is 0 (complete)
,08-24 17:08:04.192  1724  3947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 17:08:04.192  1724  3947 I SystemUpdateService: file has been verified
,08-24 17:08:04.192  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 17:08:04.193  1724  3947 I SystemUpdateService: OTA package size = 12249756
,08-24 17:08:04.196  1724  2453 I iu.UploadsManager: num queued entries: 0
,08-24 17:08:04.196  1724  2453 I iu.UploadsManager: num updated entries: 0
,08-24 17:08:04.200  1724  2453 I iu.SyncManager: NEXT; no task
,08-24 17:08:04.204  1724  3947 I SystemUpdateService: showing system update notification
,08-24 17:08:04.207   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff6136c:true
,08-24 17:08:04.211  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 17:08:04.212  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 17:08:04.226   874  1999 I ActivityManager: Start proc 3949:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-24 17:08:04.228  1724  1724 D SystemUpdateService: onDestroy
,08-24 17:08:04.264  3949  3949 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 17:08:04.269  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:04.275  3949  3949 D SprintDMHelper: simOperator: 
,08-24 17:08:04.276  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 17:08:04.306   874  1695 I ActivityManager: Start proc 3961:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 17:08:04.307   874  1695 I ActivityManager: Killing 3488:android.process.acore/u0a5 (adj 15): empty #17
,08-24 17:08:04.435  2289  3975 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 17:08:04.471   874  2223 I ActivityManager: Start proc 3976:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 17:08:04.474   874  2223 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 17:08:04.519  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 17:08:04.573  3976  3976 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 17:08:04.573  3976  3976 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 17:08:04.573  3976  3976 I GAv4    :   adb logcat -s GAv4
,08-24 17:08:04.589  3976  3976 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:08:04.595  3976  3976 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:08:04.627  3976  3993 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:08:04.733  3976  3976 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 17:08:04.770  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 17:08:04.784  3976  3976 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4754-4757)
,08-24 17:08:04.785  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 17:08:04.798  3976  3976 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {342d81e}
,08-24 17:08:04.798  3976  3976 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 17:08:04.799  3976  3976 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 17:08:04.813  3976  3976 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-24 17:08:04.815  3976  3976 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:08:04.832  3976  3976 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 17:08:04.846  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:08:04.846  3976  3976 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 17:08:04.846  3976  3976 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 17:08:04.846  3976  3976 I Adreno  : Build Date                       : 10/20/15
08-24 17:08:04.846  3976  3976 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 17:08:04.846  3976  3976 I Adreno  : Local Branch                     : M14
08-24 17:08:04.846  3976  3976 I Adreno  : Remote Branch                    : 
08-24 17:08:04.846  3976  3976 I Adreno  : Remote Branch                    : 
08-24 17:08:04.846  3976  3976 I Adreno  : Reconstruct Branch               : 
,08-24 17:08:04.934  3976  3976 I NSApplication: Starting up...
,08-24 17:08:04.959  3976  4022 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 17:08:04.959   874  2221 I ActivityManager: Start proc 4027:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 17:08:04.963   874  2221 I ActivityManager: Killing 3687:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 17:08:05.066  4027  4027 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 17:08:05.284   874  1942 I ActivityManager: Killing 2208:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-24 17:08:06.374   874  1926 D WifiService: setWifiEnabled: true pid=3789, uid=10000
,08-24 17:08:06.374   874  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:08:06.389   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-24 17:08:06.396  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:06.397  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:06.397  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:06.397  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:06.401  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:06.402  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:06.402  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:06.402  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:06.428   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-24 17:08:06.429   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-24 17:08:06.430   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 17:08:06.431   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 17:08:06.431   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-24 17:08:06.431   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 17:08:06.432   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 17:08:06.446   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 17:08:06.447   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:06.448   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-24 17:08:06.449   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 17:08:06.450   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.38 rxSuccessRate=11.25 delta 1000 -> 994
,08-24 17:08:06.453   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 17:08:06.453   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 17:08:06.478   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 17:08:06.478   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:06.487   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 17:08:06.545   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 17:08:06.550  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 17:08:06.971  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 17:08:07.019  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 17:08:07.021  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 17:08:07.027   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:07.046   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 17:08:07.046   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:08:07.047   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 17:08:07.067   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:07.083   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:07.084   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 17:08:07.104   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-24 17:08:07.108   874  4050 D DhcpClient: Receive thread started
,08-24 17:08:07.110   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 17:08:07.202   874  1315 E native  : do suspend false
,08-24 17:08:07.223   874  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 17:08:07.236   874  4050 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-24 17:08:07.237   874  1893 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-24 17:08:07.240   874  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 17:08:07.257   874  4050 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 17:08:07.258   874  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 17:08:07.263   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:07.273   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 17:08:07.274   874  1893 D DhcpClient: Scheduling renewal in 86399s
,08-24 17:08:07.293   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 17:08:07.297   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 17:08:07.297   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 17:08:07.298   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 17:08:07.310   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-24 17:08:07.321   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 17:08:07.352   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 17:08:07.353   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 17:08:07.354   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-24 17:08:07.355   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-24 17:08:07.356   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 17:08:07.364   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 17:08:07.369   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 17:08:07.369   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-24 17:08:07.369   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-24 17:08:07.369   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 17:08:07.369   874  1318 D ConnectivityService:    accepting network in place of null
08-24 17:08:07.370   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 17:08:07.371   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 17:08:07.379   874  4049 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137352, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 17:08:07.402   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:07.441   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:07.447   874  4048 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.206,2a00:1450:4001:814::200e
,08-24 17:08:07.448   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 17:08:07.448   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:07.462   874   891 D Tethering: MasterInitialState.processMessage what=3
08-24 17:08:07.470  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:07.470  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:07.472  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.473  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:07.473   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-24 17:08:07.479  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:07.479  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:07.479  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.479  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:07.487  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-24 17:08:07.491  1724  1724 D SystemUpdateService: onCreate
,08-24 17:08:07.496  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 17:08:07.498  1724  4061 I SystemUpdateService: active receiver: enabled
,08-24 17:08:07.502  1724  4061 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 17:08:07.504  1724  4061 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 17:08:07.505  1724  4061 I SystemUpdateService: now status is 0 (complete)
,08-24 17:08:07.505  1724  4061 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 17:08:07.505  1724  4061 I SystemUpdateService: file has been verified
,08-24 17:08:07.506  1724  4061 I SystemUpdateService: OTA package size = 12249756
,08-24 17:08:07.513  1724  4061 I SystemUpdateService: showing system update notification
,08-24 17:08:07.514   874  4048 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:08:07 GMT], X-Android-Received-Millis=[1472051287513], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472051287488]}
,08-24 17:08:07.516   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 17:08:07.516   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 17:08:07.516   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 17:08:07.517   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 17:08:07.522  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 17:08:07.524  1724  2453 I iu.UploadsManager: num queued entries: 0
,08-24 17:08:07.524  1724  2453 I iu.UploadsManager: num updated entries: 0
08-24 17:08:07.525  1724  2453 I iu.SyncManager: NEXT; no task
,08-24 17:08:07.534  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 17:08:07.536  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 17:08:07.540  1724  1724 D SystemUpdateService: onDestroy
08-24 17:08:07.542  1724  4066 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-24 17:08:07.542  1724  4066 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 17:08:07.544  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-24 17:08:07.544  1724  4066 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 17:08:07.548  3949  3949 D SprintDMHelper: simOperator: 
08-24 17:08:07.548  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 17:08:07.555  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:08:07.557  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:08:07.585  1524  2035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 17:08:07.586  1524  2035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 17:08:07.586  1524  2035 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:07.586  1524  2035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:08:07.608  1724  4066 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-24 17:08:07.621  3034  4070 V KeepSync: Connecting to GoogleApiClient
,08-24 17:08:07.622   874  1927 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 17:08:07.667  2289  4069 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 17:08:07.674  1524  2407 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 17:08:07.674  1524  2407 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 17:08:07.674  1524  2407 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:07.674  1524  2407 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:08:07.680  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 17:08:07.680  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 17:08:07.680  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:07.680  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 17:08:07.688  1724  4075 V BaseAuthAsyncOperation: access token request failed
08-24 17:08:07.690  3544  4072 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 17:08:07.690  3544  4072 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jdm.a(PG:82)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jcs.o(PG:406)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jcn.a(PG:1379)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jcs.i(PG:143)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at blb.a(PG:3937)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at czp.a(PG:18188)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at czp.a(PG:9081)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at czq.run(PG:1686)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:07.690  3544  4072 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jdj.a(PG:4091)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jdj.a(PG:1125)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jdm.a(PG:77)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	... 12 more
08-24 17:08:07.690  3544  4072 E HttpOperation: Caused by: faj: BadAuthentication
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at fal.a(PG:38)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	at jdj.a(PG:4089)
08-24 17:08:07.690  3544  4072 E HttpOperation: 	... 14 more
,08-24 17:08:07.696  3034  4070 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 17:08:07.762  1524  2041 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 17:08:07.762  1524  2041 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 17:08:07.762  1524  2041 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:07.763  1524  2041 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:08:07.774  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 17:08:07.774  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-24 17:08:07.775  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:07.775  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 17:08:07.775  3544  4072 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 17:08:07.775  3544  4072 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jdm.a(PG:82)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jcs.o(PG:406)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jcn.a(PG:1379)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jcs.i(PG:143)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at hec.a(PG:42)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at hee.a(PG:102)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at czr.a(PG:65)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at kka.a(PG:108)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at czp.a(PG:19176)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at czp.a(PG:9081)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at czq.run(PG:1686)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:07.775  3544  4072 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jdj.a(PG:4091)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jdj.a(PG:1125)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jdm.a(PG:77)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	... 15 more
08-24 17:08:07.775  3544  4072 E HttpOperation: Caused by: faj: BadAuthentication
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at fal.a(PG:38)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	at jdj.a(PG:4089)
08-24 17:08:07.775  3544  4072 E HttpOperation: 	... 17 more
,08-24 17:08:07.775  3544  4072 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 17:08:07.775  3544  4072 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at hec.a(PG:42)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at hee.a(PG:102)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at czr.a(PG:65)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at kka.a(PG:108)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	... 15 more
08-24 17:08:07.775  3544  4072 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at fal.a(PG:38)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 17:08:07.775  3544  4072 E ExperimentLoader: 	... 17 more
,08-24 17:08:07.804  3034  4070 E KeepSync: IOException
08-24 17:08:07.804  3034  4070 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 17:08:07.804  3034  4070 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 17:08:07.804  3034  4070 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 17:08:07.804  3034  4070 E KeepSync: 	... 10 more
,08-24 17:08:07.804  3034  4070 W KeepSync: Sync result 2
,08-24 17:08:07.812   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 130422, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 17:08:07.886   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128373, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 17:08:08.448   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 17:08:09.225   874  1927 I ActivityManager: Killing 3715:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-24 17:08:09.383   874  1942 D WifiService: setWifiEnabled: false pid=3789, uid=10000
,08-24 17:08:09.383   874  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:08:09.419  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 17:08:09.427   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 17:08:09.428   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-24 17:08:09.428   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 17:08:09.429   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:09.449   874  1893 D DhcpClient: Clearing IP address
,08-24 17:08:09.449   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:08:09.455   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:09.464  1524  4076 V NativeCrypto: Read error: ssl=0x9b3afc00: I/O error during system call, Connection timed out
,08-24 17:08:09.468  1524  4076 V NativeCrypto: SSL shutdown failed: ssl=0x9b3afc00: I/O error during system call, Broken pipe
,08-24 17:08:09.476   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-24 17:08:09.477   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-24 17:08:09.480   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-24 17:08:09.481   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-24 17:08:09.484   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:08:09.488   403   403 E Parcel  : Reading a NULL string not supported here.
08-24 17:08:09.494   874  4050 D DhcpClient: Receive thread stopped
,08-24 17:08:09.501   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:09.504  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:09.505  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:08:09.505  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:09.505  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:09.506   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-24 17:08:09.506   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:08:09.507  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:09.507  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:09.507  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:09.507  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:09.515  1993  2323 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:09.534   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:09.562   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:09.562   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-24 17:08:09.562   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:09.564   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-24 17:08:09.570  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:09.570  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:09.572  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-24 17:08:09.572  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:09.572  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:09.579  1724  1724 D SystemUpdateService: onCreate
,08-24 17:08:09.581  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 17:08:09.590  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 17:08:09.592  1724  2453 I iu.UploadsManager: num queued entries: 0
,08-24 17:08:09.592  1724  2453 I iu.UploadsManager: num updated entries: 0
,08-24 17:08:09.602  1724  4089 I SystemUpdateService: active receiver: enabled
,08-24 17:08:09.605  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 17:08:09.606  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 17:08:09.608  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:09.613  3949  3949 D SprintDMHelper: simOperator: 
08-24 17:08:09.613  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 17:08:09.619  1724  2453 I iu.SyncManager: NEXT; no task
,08-24 17:08:09.626  3976  3976 I art     : Waiting for a blocking GC DisableMovingGc
,08-24 17:08:09.627   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-24 17:08:09.628  3976  3976 I art     : Starting a blocking GC DisableMovingGc
,08-24 17:08:09.629   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-24 17:08:09.642  1724  4089 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 17:08:09.642  2289  4093 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 17:08:09.656  1724  4089 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 17:08:09.657  1724  4089 I SystemUpdateService: now status is 0 (complete)
,08-24 17:08:09.657  1724  4089 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 17:08:09.657  1724  4089 I SystemUpdateService: file has been verified
,08-24 17:08:09.658  1724  4089 I SystemUpdateService: OTA package size = 12249756
,08-24 17:08:09.666  1724  4089 I SystemUpdateService: showing system update notification
,08-24 17:08:09.681  1724  1724 D SystemUpdateService: onDestroy
,08-24 17:08:09.752  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:08:09.795  1524  2035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 17:08:09.796  1524  2035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 17:08:09.796  1524  2035 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:09.796  1524  2035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:08:09.831  3505  3505 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 17:08:09.832  3505  3505 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 17:08:09.832  3505  3505 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-24 17:08:12.440   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@344faa1:true
,08-24 17:08:12.440  3933  3933 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 17:08:12.446  3933  3933 I bt_bluedroid: init
,08-24 17:08:12.446  3933  4096 I BluetoothAdapterState: Entering OffState
,08-24 17:08:12.452  3933  4097 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 17:08:12.452  3933  4097 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 17:08:12.452  3933  4097 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 17:08:12.453  3933  4097 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 17:08:12.454  3933  3933 I bt_bluedroid: get_profile_interface socket
,08-24 17:08:12.457  3933  4100 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 17:08:12.458  3933  3933 I bt_bluedroid: get_profile_interface sdp
08-24 17:08:12.459  3933  4100 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 17:08:12.462  3933  3945 I bt_bluedroid: config_hci_snoop_log
08-24 17:08:12.464   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 17:08:12.470  3933  4096 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 17:08:12.471  3933  4096 D BluetoothAdapterProperties: Setting state to 14
08-24 17:08:12.471  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 17:08:12.475  3933  4096 D BluetoothBondStateMachine: make
,08-24 17:08:12.483  3933  4102 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 17:08:12.487  3933  4096 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:12.488  3933  3933 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 17:08:12.492  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:12.493  3933  3933 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:08:12.494  3933  3933 D BtGatt.GattService: Received start request. Starting profile...
,08-24 17:08:12.494  3933  3933 D BtGatt.GattService: start()
,08-24 17:08:12.494  3933  3933 I bt_bluedroid: get_profile_interface gatt
,08-24 17:08:12.495  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244,
08-24 17:08:12.495  3933  3933 D BtGatt.AdvertiseManager: advertise manager created,
,08-24 17:08:12.505  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:12.505  3933  3933 V BluetoothAdapterState: isTurningOn()=false
,08-24 17:08:12.505  3933  3933 V BluetoothAdapterState: isBleTurningOn()=true
,08-24 17:08:12.506  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:12.506  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 17:08:12.507  3933  4096 I bt_bluedroid: enable
,08-24 17:08:12.507  3933  4097 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 17:08:12.508  3933  4097 I bt_hci  : start_up
,08-24 17:08:12.525  3933  4097 I bt_vendor: alloc value 0xb3939189
,08-24 17:08:12.525  3933  4097 I bt_vendor: init
08-24 17:08:12.525  3933  4097 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 17:08:12.525  3933  4097 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 17:08:12.632  3933  4097 D bt_hci  : start_up starting async portion
,08-24 17:08:12.633  3933  4105 I bt_hci  : event_finish_startup,
,08-24 17:08:12.633  3933  4105 I bt_hci_h4: hal_open
,08-24 17:08:12.633  3933  4105 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 17:08:12.643  3933  4105 I bt_userial_vendor: device fd = 51 open
,08-24 17:08:12.674  3933  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 17:08:12.706  3933  4105 D bt_hwcfg: Chipset BCM4354A2
,08-24 17:08:12.706  3933  4105 D bt_hwcfg: Target name = [BCM4354A2]
,08-24 17:08:12.707  3933  4105 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 17:08:13.379  3933  4105 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 17:08:13.381  3933  4105 D bt_hwcfg: Settlement delay -- 100 ms
08-24 17:08:13.382  3933  4105 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 17:08:13.499  3933  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 17:08:13.500  3933  4105 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 17:08:13.529  3933  4105 I bt_hwcfg: vendor lib fwcfg completed
,08-24 17:08:13.529  3933  4105 I bt_vendor: firmware callback
,08-24 17:08:13.529  3933  4105 I bt_hci  : firmware_config_callback
,08-24 17:08:13.540  3933  4107 I bt_btu  : btu_task pending for preload complete event
,08-24 17:08:13.541  3933  4107 I bt_btu_task: Bluetooth chip preload is complete
,08-24 17:08:13.541  3933  4107 I bt_btu  : btu_task received preload complete event
,08-24 17:08:13.554  3933  4107 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 17:08:13.555  3933  4107 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 17:08:13.555  3933  4107 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-24 17:08:13.555  3933  4107 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-24 17:08:13.556  3933  4107 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 17:08:13.556  3933  4107 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 17:08:13.556  3933  4107 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-24 17:08:13.557  3933  4107 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 17:08:13.557  3933  4107 I         : BTE_InitTraceLevels -- TRC_GAP
,08-24 17:08:13.558  3933  4107 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 17:08:13.558  3933  4107 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 17:08:13.558  3933  4107 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 17:08:13.558  3933  4107 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 17:08:13.558  3933  4107 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:08:13.559  3933  4107 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 17:08:13.700  3933  4107 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-24 17:08:13.701  3933  4107 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-24 17:08:13.712  3933  4100 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 17:08:13.713  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 17:08:13.713  3933  4100 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 17:08:13.717  3933  4100 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 17:08:13.720  3933  4100 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:13.720  3933  4100 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:13.721  3933  4100 D bt_hci  : do_postload posting postload work item
08-24 17:08:13.721  3933  4105 I bt_hci  : event_postload
08-24 17:08:13.721  3933  4105 I bt_vendor: sco_config_cb
08-24 17:08:13.721  3933  4105 I bt_hci  : sco_config_callback postload finished.
08-24 17:08:13.723  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:13.724  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:13.725  3933  4100 D bt_bte_conf: Device ID record 1 : primary
08-24 17:08:13.726  3933  4100 D bt_bte_conf:   vendorId            = 000f
08-24 17:08:13.726  3933  4100 D bt_bte_conf:   vendorIdSource      = 0001
,08-24 17:08:13.726  3933  4100 D bt_bte_conf:   product             = 1200
,08-24 17:08:13.726  3933  4100 D bt_bte_conf:   version             = 1436
,08-24 17:08:13.727  3933  4100 D bt_bte_conf:   clientExecutableURL = 
,08-24 17:08:13.727  3933  4100 D bt_bte_conf:   serviceDescription  = 
,08-24 17:08:13.727  3933  4100 D bt_bte_conf:   documentationURL    = 
08-24 17:08:13.727  3933  4100 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-24 17:08:13.728  3933  4105 I bt_vendor: low_power_mode_cb
08-24 17:08:13.728  3933  4097 D bt_stack_manager: event_start_up_stack finished
,08-24 17:08:13.729  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-24 17:08:13.730  3933  4096 D BluetoothAdapterProperties: Setting state to 15
08-24 17:08:13.731  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 17:08:13.733  3933  4096 I BluetoothAdapterState: Entering BleOnState
,08-24 17:08:13.738  3933  4096 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 17:08:13.739  3933  4096 D BluetoothAdapterProperties: Setting state to 11
08-24 17:08:13.739  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 17:08:13.747  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.749  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.753  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:13.754  3933  3933 D HeadsetService: Received start request. Starting profile...
,08-24 17:08:13.759  3933  3933 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 17:08:13.759  3933  3933 D HeadsetStateMachine: make
,08-24 17:08:13.764  3933  4096 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:13.768  3933  3933 D HeadsetStateMachine: max_hf_connections = 1
,08-24 17:08:13.768  3933  3933 I bt_bluedroid: get_profile_interface handsfree
08-24 17:08:13.768  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 17:08:13.769  3933  4100 E bt_btif : btif_hf_upstreams_evt: Invalid index 1024
,08-24 17:08:13.773  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:13.774  3933  3933 D A2dpService: Received start request. Starting profile...
,08-24 17:08:13.774  3933  3933 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 17:08:13.776  3933  3933 I bt_bluedroid: get_profile_interface avrcp
,08-24 17:08:13.784  3933  3933 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:08:13.784  3933  3933 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:08:13.785  3933  3933 D A2dpStateMachine: make
,08-24 17:08:13.786  3933  3933 I bt_bluedroid: get_profile_interface a2dp
,08-24 17:08:13.786  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 17:08:13.788  3933  4115 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:13.788  3933  3933 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 17:08:13.789  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:13.790  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:13.790  3933  3933 D HidService: Received start request. Starting profile...
08-24 17:08:13.790  3933  3933 I bt_bluedroid: get_profile_interface hidhost
08-24 17:08:13.791  3857  3857 D BluetoothInputDevice: Proxy object connected
08-24 17:08:13.791  3933  4100 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
08-24 17:08:13.791  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 17:08:13.791  3933  3933 D HidService: setHidService(): set to: null
08-24 17:08:13.791  3857  3857 D HidProfile: Bluetooth service connected
,08-24 17:08:13.792  3933  3933 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 17:08:13.792  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
08-24 17:08:13.793  3933  3933 D HealthService: Received start request. Starting profile...
,08-24 17:08:13.794  3933  3933 I bt_bluedroid: get_profile_interface health
,08-24 17:08:13.794  3933  3933 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 17:08:13.795  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:13.796  3857  3857 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:13.796  3933  3933 D PanService: Received start request. Starting profile...
08-24 17:08:13.796  3933  3933 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:13.796  3857  3857 D PanProfile: Bluetooth service connected
08-24 17:08:13.796  3933  3933 I bt_bluedroid: get_profile_interface pan
08-24 17:08:13.797  3933  4100 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:13.799  3933  3933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:13.800  3857  3857 D BluetoothMap: Proxy object connected
08-24 17:08:13.800  3933  3933 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:13.800  3857  3857 D MapProfile: Bluetooth service connected
,08-24 17:08:13.800  3933  3933 D BluetoothMapService: start()
08-24 17:08:13.800  3857  3857 D BluetoothMap: getConnectedDevices()
08-24 17:08:13.801  3857  3857 D BluetoothMap: Bluetooth is Not enabled
,08-24 17:08:13.802  3933  3933 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 17:08:13.803  3933  3933 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-24 17:08:13.803  3933  3933 D BluetoothMapAppObserver: createReceiver()
,08-24 17:08:13.804  3933  3933 D BluetoothMapAppObserver: initObservers()
,08-24 17:08:13.804  3933  3933 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 17:08:13.811  3933  4113 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-24 17:08:13.811  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:13.811  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:13.811  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:13.811  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isTurningOn()=true
,08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:13.813  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:13.815  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:13.815  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:13.815  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:13.815  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:13.816  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:13.816  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 17:08:13.816  3933  4096 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:13.817  3933  4096 D BluetoothAdapterProperties: State =  11
08-24 17:08:13.817  3933  4096 D BluetoothAdapterProperties: Setting state to 12
08-24 17:08:13.817  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:08:13.818  3857  3869 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 17:08:13.818  3933  4100 D BluetoothAdapterProperties: Scan Mode:21
08-24 17:08:13.818  3933  4100 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:13.819  3933  4096 I BluetoothAdapterState: Entering OnState
,08-24 17:08:13.820   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:13.821  3857  3868 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:13.821   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:13.821  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:13.822  3857  3869 D BluetoothPan: onBluetoothStateChange on: true
08-24 17:08:13.822   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:08:13.822  1359  1719 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 17:08:13.822   874   874 D BluetoothA2dp: Proxy object connected
08-24 17:08:13.823  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:13.824  1359  1359 D BluetoothInputDevice: Proxy object connected
08-24 17:08:13.824  1359  1359 D HidProfile: Bluetooth service connected
,08-24 17:08:13.827  1359  1717 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:13.827  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:13.828  1359  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:13.829  1359  1371 D BluetoothPan: onBluetoothStateChange on: true
,08-24 17:08:13.829  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:13.830   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:13.830  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:13.830  1359  1359 D PanProfile: Bluetooth service connected
08-24 17:08:13.830  1940  2263 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:08:13.831  3933  3933 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 17:08:13.831  1359  1717 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:13.831  3933  3933 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 17:08:13.833  3933  3933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:13.832  1359  1359 D BluetoothA2dp: Proxy object connected
,08-24 17:08:13.833  3857  3868 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 17:08:13.833  1359  1371 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:13.835  3933  3933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.835  1359  1359 D BluetoothMap: Proxy object connected
,08-24 17:08:13.835  1359  1359 D MapProfile: Bluetooth service connected
08-24 17:08:13.835  1359  1359 D BluetoothMap: getConnectedDevices()
08-24 17:08:13.836   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 17:08:13.838  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.839  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.840  3933  3933 D ObexServerSockets: Succeed to create listening sockets 
08-24 17:08:13.840  3933  3933 D ObexServerSockets0: startAccept()
,08-24 17:08:13.841  3933  3933 D ObexServerSockets0: prepareForNewConnect()
,08-24 17:08:13.842  3933  3933 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 17:08:13.842  3933  3933 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-24 17:08:13.842  3857  3857 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-24 17:08:13.843  3933  3933 D BluetoothMapService: onReceive
,08-24 17:08:13.843  3933  3933 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:13.843  3933  3933 D BluetoothMapService: STATE_ON
08-24 17:08:13.843  3933  4123 D ObexServerSockets0: Accepting socket connection...
08-24 17:08:13.844  3933  4124 D ObexServerSockets0: Accepting socket connection...
,08-24 17:08:13.847  3857  3857 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 17:08:13.853  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:13.855  3857  3857 D BluetoothA2dp: Proxy object connected
,08-24 17:08:13.868  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:13.876  3857  3857 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:13.877  1359  1359 D BluetoothPbap: Proxy object connected
,08-24 17:08:13.877  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:13.878  3933  3933 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 17:08:13.878  3933  3933 D ObexServerSockets0: prepareForNewConnect()
,08-24 17:08:13.879  3857  3857 D BluetoothPbap: Proxy object connected
,08-24 17:08:13.879  3857  3857 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:13.888  3933  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.908  3933  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.909  3933  4132 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:13.924  1359  1717 D BluetoothHeadset: Proxy object connected
,08-24 17:08:13.924  1359  1359 D HeadsetProfile: Bluetooth service connected
08-24 17:08:13.924  1940  1952 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.924   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.924   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.924   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.929  1359  1379 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.929  1359  1359 D HeadsetProfile: Bluetooth service connected
08-24 17:08:13.930   874   891 D BluetoothHeadset: Proxy object connected
08-24 17:08:13.931  1940  2265 D BluetoothHeadset: Proxy object connected
,08-24 17:08:13.949  3857  3869 D BluetoothHeadset: Proxy object connected
,08-24 17:08:13.950  3857  3857 D HeadsetProfile: Bluetooth service connected
,08-24 17:08:15.375   874  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-24 17:08:15.406  3933  4096 D BluetoothAdapterState: Current state: ON, message: 23
,08-24 17:08:15.406  3933  4096 D BluetoothAdapterProperties: Setting state to 13
08-24 17:08:15.407  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:08:15.408  3933  4096 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 17:08:15.413  3933  4096 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:15.417  3933  4100 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:15.417  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 17:08:15.421  3933  3933 D BluetoothMapService: onReceive
,08-24 17:08:15.421  3933  3933 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:15.422  3933  3933 D BluetoothMapService: STATE_TURNING_OFF
,08-24 17:08:15.423  3933  3933 D BluetoothMapService: MAP Service closeService in
08-24 17:08:15.423  3933  3933 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 17:08:15.423  3933  3933 D ObexServerSockets0: shutdown(block = true)
08-24 17:08:15.424  3933  4123 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 17:08:15.425  3933  3933 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 17:08:15.425  3933  4110 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 17:08:15.426  3933  3933 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 17:08:15.426  3933  4124 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 17:08:15.428  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.428  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.428  3933  3933 I BtOppRfcommListener: stopping Accept Thread
08-24 17:08:15.429  3933  4132 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:08:15.430  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:15.431  3933  4132 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 17:08:15.431  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:15.435  3933  3933 D HeadsetService: Received stop request...Stopping profile...
,08-24 17:08:15.437  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:15.437  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.437  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.440  3789  3789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:15.440  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:15.443  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:15.445  1359  1379 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:15.445  3857  3869 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:15.446  1940  2133 D BluetoothHeadset: Proxy object disconnected
,08-24 17:08:15.446  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:15.446   874   874 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:15.446   874   874 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:15.446   874   874 D BluetoothHeadset: Proxy object disconnected
08-24 17:08:15.448  3933  3933 D A2dpService: Received stop request...Stopping profile...
08-24 17:08:15.448  3933  4115 D A2dpStateMachine: Exit Disconnected: -1
08-24 17:08:15.449  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-24 17:08:15.450  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:15.450   874   874 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:15.452  3933  3933 D HidService: Received stop request...Stopping profile...
08-24 17:08:15.452  3933  3933 D HidService: Stopping Bluetooth HidService
08-24 17:08:15.455  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:15.456  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-24 17:08:15.456  3857  3857 D DockEventReceiver: finishStartingService: stopping service
08-24 17:08:15.456  1359  1359 D HidProfile: Bluetooth service disconnected
08-24 17:08:15.456  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:15.456  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.456  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 17:08:15.457  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:15.457  3857  3857 D HeadsetProfile: Bluetooth service disconnected
08-24 17:08:15.458  3857  3857 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:15.458  3857  3857 D BluetoothInputDevice: Proxy object disconnected
08-24 17:08:15.458  3857  3857 D HidProfile: Bluetooth service disconnected
08-24 17:08:15.459  3933  3933 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 17:08:15.459  3933  3933 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:08:15.460  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 17:08:15.460  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:15.460  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-24 17:08:15.460  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-24 17:08:15.460  3933  4100 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
,08-24 17:08:15.460  3933  3933 D HealthService: Received stop request...Stopping profile...
08-24 17:08:15.462  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:15.462  3933  3933 V BluetoothAdapterState: isTurningOn()=false
,08-24 17:08:15.462  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:15.462  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:15.463  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:15.463  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:15.463  3933  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:08:15.463  3933  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:15.463  3933  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:08:15.463  3933  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 17:08:15.464  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 17:08:15.464  3933  3933 D PanService: Received stop request...Stopping profile...
08-24 17:08:15.464  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:08:15.464  1359  1359 D PanProfile: Bluetooth service disconnected
08-24 17:08:15.465  3933  3933 D BluetoothMapService: Received stop request...Stopping profile...
08-24 17:08:15.465  3933  3933 D BluetoothMapService: stop()
08-24 17:08:15.466  3933  3933 D BluetoothMapAppObserver: deinitObservers()
,08-24 17:08:15.466  3933  3933 D BluetoothMapAppObserver: removeReceiver()
08-24 17:08:15.467  1359  1359 D BluetoothMap: Proxy object disconnected
08-24 17:08:15.467  1359  1359 D MapProfile: Bluetooth service disconnected
,08-24 17:08:15.469  1359  1359 D BluetoothPbap: Proxy object disconnected
08-24 17:08:15.470  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:15.470  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.470  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:15.470  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:15.470  3933  3933 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:08:15.471  3933  4100 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 17:08:15.471  3933  3933 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:08:15.471  3857  3857 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:08:15.471  3857  3857 D PanProfile: Bluetooth service disconnected
08-24 17:08:15.472  3857  3857 D BluetoothMap: Proxy object disconnected
,08-24 17:08:15.472  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:15.472  3857  3857 D MapProfile: Bluetooth service disconnected
,08-24 17:08:15.472  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.472  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:15.472  3857  3857 D BluetoothPbap: Proxy object disconnected
08-24 17:08:15.472  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:15.472  3857  3857 D PbapServerProfile: Bluetooth service disconnected
08-24 17:08:15.472  3933  3933 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-24 17:08:15.472  3933  4100 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 17:08:15.472  3933  3933 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:08:15.473  3933  3933 V BluetoothAdapterState: isTurningOff()=true
08-24 17:08:15.473  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.473  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 17:08:15.473  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:15.473  1359  1359 D PbapServerProfile: Bluetooth service disconnected
08-24 17:08:15.474  3933  3933 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:08:15.474  3933  3933 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:08:15.475  3933  3933 D BluetoothMapService: MAP Service closeService in
08-24 17:08:15.475  3933  3933 V BluetoothAdapterState: isTurningOff()=true
,08-24 17:08:15.475  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.475  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:15.475  3933  3933 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:15.476  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-24 17:08:15.476  3933  4096 D BluetoothAdapterProperties: Setting state to 15
08-24 17:08:15.476  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 17:08:15.476  3933  4096 I BluetoothAdapterState: Entering BleOnState
08-24 17:08:15.476  3857  3869 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 17:08:15.476  3933  3933 D BluetoothMapService: cleanup()
08-24 17:08:15.477  3933  3933 D BluetoothMapService: MAP Service closeService in
08-24 17:08:15.477  3857  3868 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:15.477   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:15.478  3857  3869 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 17:08:15.478   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.478  3857  3868 D BluetoothPan: onBluetoothStateChange on: false
08-24 17:08:15.479   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.479  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 17:08:15.479  1359  1719 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 17:08:15.480  3857  3869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.480  1359  1717 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.480  1359  1379 D BluetoothPan: onBluetoothStateChange on: false
08-24 17:08:15.481   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.481  1940  1955 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 17:08:15.481  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:15.482  3857  3868 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 17:08:15.482  1359  1719 D BluetoothMap: onBluetoothStateChange: up=false
08-24 17:08:15.483  3933  4096 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 17:08:15.483  3933  4096 D BluetoothAdapterProperties: Setting state to 16
08-24 17:08:15.483  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 17:08:15.483  3933  4096 D BluetoothAdapterProperties: onBleDisable
08-24 17:08:15.484  3933  4096 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:15.484  3933  4097 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 17:08:15.485  3933  4100 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:08:15.485  3933  4107 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 17:08:15.485  3933  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 17:08:15.487  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:15.488  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:15.489  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:15.490  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 17:08:15.490  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:15.495  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:08:15.498  3857  3857 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:15.685  3933  4100 I bt_hci  : shut_down
,08-24 17:08:15.698  3933  4105 I bt_vendor: low_power_mode_cb
,08-24 17:08:15.698  3933  4105 D bt_hwcfg: hw_epilog_process
,08-24 17:08:15.722  3933  4105 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-24 17:08:15.722  3933  4105 I bt_vendor: epilog_cb
08-24 17:08:15.722  3933  4105 I bt_hci  : epilog_finished_callback
,08-24 17:08:15.730  3933  4100 I bt_hci_h4: hal_close
,08-24 17:08:15.731  3933  4100 I bt_userial_vendor: device fd = 51 close
,08-24 17:08:15.847  3933  4097 D bt_stack_manager: event_shut_down_stack finished.
,08-24 17:08:15.848  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 17:08:15.854  3933  3933 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:08:15.854  3933  4096 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 17:08:15.858  3933  3933 D BtGatt.GattService: Received stop request...Stopping profile...
,08-24 17:08:15.858  3933  3933 D BtGatt.GattService: stop()
08-24 17:08:15.859  3933  3933 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 17:08:15.864  3933  3933 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:15.864  3933  3933 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:15.865  3933  3933 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:15.865  3933  3933 V BluetoothAdapterState: isBleTurningOff()=true
,08-24 17:08:15.867  3933  4096 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-24 17:08:15.868  3933  4096 D BluetoothAdapterProperties: Setting state to 10
08-24 17:08:15.868  3933  4096 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-24 17:08:15.870  3933  4096 I BluetoothAdapterState: Entering OffState
08-24 17:08:15.871   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 17:08:15.902  3933  3933 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 17:08:15.902  3933  3933 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 17:08:15.903  3933  4097 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 17:08:15.912  3933  4097 D bt_stack_manager: event_clean_up_stack finished.
,08-24 17:08:15.912  3933  3933 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 17:08:15.918  3933  3933 I art     : System.exit called, status: 0
,08-24 17:08:15.919  3933  3933 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 17:08:15.964   874  1695 I ActivityManager: Process com.android.bluetooth (pid 3933) has died
,08-24 17:08:18.403  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:18.403  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:20.327   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 17:08:20.335  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-24 17:08:20.344   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 17:08:20.344   874   894 I Adreno  : Build Date                       : 10/20/15
08-24 17:08:20.344   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 17:08:20.344   874   894 I Adreno  : Local Branch                     : M14
08-24 17:08:20.344   874   894 I Adreno  : Remote Branch                    : 
08-24 17:08:20.344   874   894 I Adreno  : Remote Branch                    : 
08-24 17:08:20.344   874   894 I Adreno  : Reconstruct Branch               : 
,08-24 17:08:20.385   283  2312 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (301 us)
,08-24 17:08:21.062  3789  3789 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:08:21.063  3789  3789 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 17:08:21.096   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-24 17:08:21.097  3789  3789 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9c31f2d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@fedd07a, 16908290=android.view.AbsSavedState$1@fedd07a}, android:focusedViewId=100}]}]
,08-24 17:08:21.098  3789  3789 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 17:08:21.098  3789  3789 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 17:08:21.098  3789  3789 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-24 17:08:21.103   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 17:08:21.109   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 17:08:21.109   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-24 17:08:21.110   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 17:08:21.336   283   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 17:08:21.340   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-24 17:08:21.340   874  1341 D SurfaceControl: Excessive delay in setPowerMode(): 232ms
,08-24 17:08:21.343   874   894 I DreamManagerService: Entering dreamland.
08-24 17:08:21.344   874   894 I PowerManagerService: Dozing...
,08-24 17:08:21.347   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 17:08:21.395   376  1325 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-24 17:08:21.396   376  1325 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 17:08:21.405   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:21.408  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:21.408  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@623202b added. We now have 6 listener(s)
08-24 17:08:21.408  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:21.410  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:21.410  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d03fc88 added. We now have 7 listener(s)
08-24 17:08:21.410  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:21.411  3789  3838 I System.out: IsBluetoothEnabled
,08-24 17:08:21.417   874  1315 E native  : do suspend false
,08-24 17:08:21.420  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:21.426  1925  4145 D NfcService: Discovery configuration equal, not updating.
,08-24 17:08:21.443   874   891 I ActivityManager: Start proc 4148:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 17:08:21.461   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:21.465   874  1315 E native  : do suspend true
,08-24 17:08:21.546   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-24 17:08:21.547   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
08-24 17:08:21.548  4148  4148 D AdapterServiceConfig: Adding HeadsetService
08-24 17:08:21.549  4148  4148 D AdapterServiceConfig: Adding A2dpService
08-24 17:08:21.549  4148  4148 D AdapterServiceConfig: Adding HidService
08-24 17:08:21.549  4148  4148 D AdapterServiceConfig: Adding HealthService
08-24 17:08:21.549  4148  4148 D AdapterServiceConfig: Adding PanService
08-24 17:08:21.549  4148  4148 D AdapterServiceConfig: Adding GattService
08-24 17:08:21.550  4148  4148 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 17:08:21.566   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99c0a99:true
,08-24 17:08:21.567  4148  4148 D BluetoothAdapterState: make() - Creating AdapterState
08-24 17:08:21.570  4148  4148 I bt_bluedroid: init
,08-24 17:08:21.571  4148  4161 I BluetoothAdapterState: Entering OffState
,08-24 17:08:21.578  4148  4162 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 17:08:21.578  4148  4162 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 17:08:21.578  4148  4162 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 17:08:21.578  4148  4162 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 17:08:21.579  4148  4148 I bt_bluedroid: get_profile_interface socket
,08-24 17:08:21.582  4148  4148 I bt_bluedroid: get_profile_interface sdp
,08-24 17:08:21.584  4148  4166 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 17:08:21.587  4148  4166 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 17:08:21.595  4148  4159 I bt_bluedroid: config_hci_snoop_log
,08-24 17:08:21.597   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 17:08:21.604  4148  4161 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 17:08:21.604  4148  4161 D BluetoothAdapterProperties: Setting state to 14
,08-24 17:08:21.604  4148  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-24 17:08:21.606  4148  4161 D BluetoothBondStateMachine: make
,08-24 17:08:21.609  4148  4167 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 17:08:21.613  4148  4148 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 17:08:21.614  4148  4161 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:21.617  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:21.617  4148  4148 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 17:08:21.618  4148  4148 D BtGatt.GattService: Received start request. Starting profile...
08-24 17:08:21.618  4148  4148 D BtGatt.GattService: start()
08-24 17:08:21.618  4148  4148 I bt_bluedroid: get_profile_interface gatt
,08-24 17:08:21.619  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:21.619  4148  4148 D BtGatt.AdvertiseManager: advertise manager created
,08-24 17:08:21.627  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:21.627  4148  4148 V BluetoothAdapterState: isTurningOn()=false
08-24 17:08:21.627  4148  4148 V BluetoothAdapterState: isBleTurningOn()=true
08-24 17:08:21.627  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:21.627  4148  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 17:08:21.628  4148  4161 I bt_bluedroid: enable
08-24 17:08:21.628  4148  4162 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 17:08:21.629  4148  4162 I bt_hci  : start_up
,08-24 17:08:21.648  4148  4162 I bt_vendor: alloc value 0xb3995189
,08-24 17:08:21.648  4148  4162 I bt_vendor: init
08-24 17:08:21.649  4148  4162 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 17:08:21.649  4148  4162 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 17:08:21.760  4148  4162 D bt_hci  : start_up starting async portion
,08-24 17:08:21.760  4148  4170 I bt_hci  : event_finish_startup
08-24 17:08:21.761  4148  4170 I bt_hci_h4: hal_open
,08-24 17:08:21.761  4148  4170 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 17:08:21.769  4148  4170 I bt_userial_vendor: device fd = 51 open
,08-24 17:08:21.801  4148  4170 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 17:08:21.833  4148  4170 D bt_hwcfg: Chipset BCM4354A2
,08-24 17:08:21.833  4148  4170 D bt_hwcfg: Target name = [BCM4354A2]
08-24 17:08:21.834  4148  4170 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 17:08:22.502  4148  4170 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 17:08:22.503  4148  4170 D bt_hwcfg: Settlement delay -- 100 ms
08-24 17:08:22.504  4148  4170 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 17:08:22.552  1524  2157 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 17:08:22.620  4148  4170 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 17:08:22.622  4148  4170 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 17:08:22.651  4148  4170 I bt_hwcfg: vendor lib fwcfg completed
,08-24 17:08:22.651  4148  4170 I bt_vendor: firmware callback
08-24 17:08:22.651  4148  4170 I bt_hci  : firmware_config_callback
,08-24 17:08:22.662  4148  4172 I bt_btu  : btu_task pending for preload complete event
,08-24 17:08:22.662  4148  4172 I bt_btu_task: Bluetooth chip preload is complete
08-24 17:08:22.663  4148  4172 I bt_btu  : btu_task received preload complete event
,08-24 17:08:22.674  4148  4172 I         : BTE_InitTraceLevels -- TRC_HCI,
08-24 17:08:22.674  4148  4172 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-24 17:08:22.674  4148  4172 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 17:08:22.675  4148  4172 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 17:08:22.675  4148  4172 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 17:08:22.675  4148  4172 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 17:08:22.675  4148  4172 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 17:08:22.676  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 17:08:22.676  4148  4172 I         : BTE_InitTraceLevels -- TRC_GAP
,08-24 17:08:22.676  4148  4172 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 17:08:22.676  4148  4172 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 17:08:22.677  4148  4172 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 17:08:22.677  4148  4172 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 17:08:22.677  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 17:08:22.677  4148  4172 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 17:08:22.814  4148  4172 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3912d9d
,08-24 17:08:22.814  4148  4172 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3912d9d 
,08-24 17:08:22.826  4148  4166 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 17:08:22.827  4148  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 17:08:22.828  4148  4166 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-24 17:08:22.831  4148  4166 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 17:08:22.834  4148  4166 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:08:22.835  4148  4166 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:22.835  4148  4166 D bt_hci  : do_postload posting postload work item
08-24 17:08:22.835  4148  4170 I bt_hci  : event_postload
08-24 17:08:22.835  4148  4170 I bt_vendor: sco_config_cb
08-24 17:08:22.836  4148  4170 I bt_hci  : sco_config_callback postload finished.
08-24 17:08:22.839  4148  4166 D bt_bte_conf: Device ID record 1 : primary
08-24 17:08:22.839  4148  4166 D bt_bte_conf:   vendorId            = 000f
08-24 17:08:22.839  4148  4166 D bt_bte_conf:   vendorIdSource      = 0001
08-24 17:08:22.839  4148  4166 D bt_bte_conf:   product             = 1200
,08-24 17:08:22.839  4148  4166 D bt_bte_conf:   version             = 1436
08-24 17:08:22.840  4148  4166 D bt_bte_conf:   clientExecutableURL = 
08-24 17:08:22.840  4148  4166 D bt_bte_conf:   serviceDescription  = 
08-24 17:08:22.840  4148  4166 D bt_bte_conf:   documentationURL    = 
08-24 17:08:22.840  4148  4166 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 17:08:22.841  4148  4162 D bt_stack_manager: event_start_up_stack finished
08-24 17:08:22.843  4148  4170 I bt_vendor: low_power_mode_cb
08-24 17:08:22.843  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:22.844  4148  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-24 17:08:22.844  4148  4161 D BluetoothAdapterProperties: Setting state to 15
08-24 17:08:22.845  4148  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-24 17:08:22.846  4148  4161 I BluetoothAdapterState: Entering BleOnState
,08-24 17:08:22.852  4148  4161 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 17:08:22.852  4148  4161 D BluetoothAdapterProperties: Setting state to 11
,08-24 17:08:22.852  4148  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-24 17:08:22.856  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
08-24 17:08:22.857  4148  4148 D HeadsetService: Received start request. Starting profile...
,08-24 17:08:22.860  4148  4148 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 17:08:22.861  4148  4148 D HeadsetStateMachine: make
08-24 17:08:22.866  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:22.877  4148  4148 D HeadsetStateMachine: max_hf_connections = 1
,08-24 17:08:22.877  4148  4148 I bt_bluedroid: get_profile_interface handsfree
08-24 17:08:22.878  4148  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 17:08:22.878  4148  4166 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-24 17:08:22.878  4148  4161 I BluetoothAdapterState: Entering PendingCommandState
,08-24 17:08:22.884  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:22.885  4148  4148 D A2dpService: Received start request. Starting profile...
,08-24 17:08:22.886  4148  4148 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-24 17:08:22.886  4148  4148 I bt_bluedroid: get_profile_interface avrcp
,08-24 17:08:22.892  4148  4148 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:08:22.892  4148  4148 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 17:08:22.893  4148  4148 D A2dpStateMachine: make
,08-24 17:08:22.894  4148  4148 I bt_bluedroid: get_profile_interface a2dp
08-24 17:08:22.894  4148  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-24 17:08:22.895  4148  4181 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:22.896  4148  4148 I BluetoothHidServiceJni: classInitNative: succeeds
08-24 17:08:22.896  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:22.897  4148  4148 D HidService: Received start request. Starting profile...
,08-24 17:08:22.897  4148  4148 I bt_bluedroid: get_profile_interface hidhost
,08-24 17:08:22.897  4148  4148 D HidService: setHidService(): set to: null
08-24 17:08:22.897  4148  4166 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f43e5
08-24 17:08:22.898  4148  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-24 17:08:22.899  4148  4148 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 17:08:22.900  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
08-24 17:08:22.900  4148  4148 D HealthService: Received start request. Starting profile...
,08-24 17:08:22.901  4148  4148 I bt_bluedroid: get_profile_interface health
,08-24 17:08:22.903  4148  4148 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 17:08:22.903  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
08-24 17:08:22.904  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 17:08:22.904  4148  4148 D PanService: Received start request. Starting profile...
,08-24 17:08:22.904  4148  4148 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:22.904  4148  4148 I bt_bluedroid: get_profile_interface pan
08-24 17:08:22.905  4148  4166 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:22.908  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:22.908  4148  4148 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:22.908  4148  4148 D BluetoothMapService: start()
,08-24 17:08:22.911  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 17:08:22.912  4148  4148 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-24 17:08:22.912  4148  4148 D BluetoothMapAppObserver: createReceiver()
,08-24 17:08:22.914  4148  4148 D BluetoothMapAppObserver: initObservers()
,08-24 17:08:22.914  4148  4148 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 17:08:22.920  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:22.920  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:22.920  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.921  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:22.922  4148  4178 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.922  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:22.923  4148  4148 V BluetoothAdapterState: isTurningOff()=false
,08-24 17:08:22.923  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:22.923  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.923  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isTurningOn()=true
,08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isTurningOff()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isTurningOn()=true
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isBleTurningOn()=false
08-24 17:08:22.925  4148  4148 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 17:08:22.926  4148  4161 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-24 17:08:22.926  4148  4161 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:22.926  4148  4161 D BluetoothAdapterProperties: State =  11
,08-24 17:08:22.929  4148  4166 D BluetoothAdapterProperties: Scan Mode:21
08-24 17:08:22.929  4148  4161 D BluetoothAdapterProperties: Setting state to 12
08-24 17:08:22.929  4148  4161 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 17:08:22.929  4148  4166 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:22.929  4148  4161 I BluetoothAdapterState: Entering OnState
,08-24 17:08:22.929  3857  3869 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 17:08:22.932  3857  3868 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:22.932  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:22.933   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:22.934   874   874 D BluetoothA2dp: Proxy object connected
08-24 17:08:22.934  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:22.934  3857  3857 D BluetoothA2dp: Proxy object connected
08-24 17:08:22.935  3857  3868 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:22.938   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:22.938  3857  3857 D BluetoothMap: Proxy object connected
08-24 17:08:22.938  3857  3868 D BluetoothPan: onBluetoothStateChange on: true
,08-24 17:08:22.939   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:22.940  1359  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 17:08:22.940  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 17:08:22.941  4148  4148 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 17:08:22.941  1359  1371 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 17:08:22.942  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:22.943  3857  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:22.938  3857  3857 D MapProfile: Bluetooth service connected
,08-24 17:08:22.943  3857  3857 D BluetoothMap: getConnectedDevices()
08-24 17:08:22.943  1359  1717 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:08:22.943  4148  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:08:22.944  1359  1719 D BluetoothPan: onBluetoothStateChange on: true
08-24 17:08:22.944  4148  4148 D ObexServerSockets: Succeed to create listening sockets 
08-24 17:08:22.945  4148  4148 D ObexServerSockets0: startAccept()
,08-24 17:08:22.945  4148  4148 D ObexServerSockets0: prepareForNewConnect()
08-24 17:08:22.945   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 17:08:22.945  1940  1952 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 17:08:22.946  1359  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:22.946  4148  4148 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 17:08:22.946  4148  4148 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 17:08:22.948  1359  1359 D BluetoothA2dp: Proxy object connected
08-24 17:08:22.948  3857  3869 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 17:08:22.949  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:22.949  1359  1359 D PanProfile: Bluetooth service connected
08-24 17:08:22.949  1359  1359 D BluetoothInputDevice: Proxy object connected
08-24 17:08:22.949  1359  1359 D HidProfile: Bluetooth service connected
08-24 17:08:22.950  4148  4187 D ObexServerSockets0: Accepting socket connection...
,08-24 17:08:22.950  1359  1371 D BluetoothMap: onBluetoothStateChange: up=true
08-24 17:08:22.950  3857  3857 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:22.950  3857  3857 D PanProfile: Bluetooth service connected
08-24 17:08:22.950  3857  3857 D BluetoothInputDevice: Proxy object connected
08-24 17:08:22.950  3857  3857 D HidProfile: Bluetooth service connected
08-24 17:08:22.952  4148  4186 D ObexServerSockets0: Accepting socket connection...
,08-24 17:08:22.952  1359  1359 D BluetoothMap: Proxy object connected
08-24 17:08:22.952  1359  1359 D MapProfile: Bluetooth service connected
08-24 17:08:22.953  1359  1359 D BluetoothMap: getConnectedDevices()
,08-24 17:08:22.954   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 17:08:22.956  4148  4148 D BluetoothMapService: onReceive
,08-24 17:08:22.956  4148  4148 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:22.956  4148  4148 D BluetoothMapService: STATE_ON
,08-24 17:08:22.957  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:22.960  3857  3857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:22.967  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:22.967  3857  3857 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:22.973  3857  3857 D BluetoothPbap: Proxy object connected
08-24 17:08:22.973  3857  3857 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:22.975  4148  4192 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:22.979  1359  1359 D BluetoothPbap: Proxy object connected
,08-24 17:08:22.979  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:22.992  4148  4148 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 17:08:22.992  4148  4148 D ObexServerSockets0: prepareForNewConnect()
,08-24 17:08:22.996  4148  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:22.997  4148  4198 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:23.041  1359  1371 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.041  1359  1359 D HeadsetProfile: Bluetooth service connected
08-24 17:08:23.041  3857  3869 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.042  3857  3857 D HeadsetProfile: Bluetooth service connected
08-24 17:08:23.042  1940  2265 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.043   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.043   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.043   874   874 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.044  3857  4188 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.045  1359  1379 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.046  1359  1359 D HeadsetProfile: Bluetooth service connected
08-24 17:08:23.046   874   891 D BluetoothHeadset: Proxy object connected
08-24 17:08:23.046  3857  3857 D HeadsetProfile: Bluetooth service connected
08-24 17:08:23.047  1940  2133 D BluetoothHeadset: Proxy object connected
,08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:23.443  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:23.451  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:23.454  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:23.456  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad42621 added. We now have 8 listener(s)
,08-24 17:08:23.456  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:23.463   874  2223 D WifiService: setWifiEnabled: false pid=3789, uid=10000
08-24 17:08:23.464   874  2223 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:08:23.476  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:23.477   874  2221 D WifiService: setWifiEnabled: true pid=3789, uid=10000
,08-24 17:08:23.477   874  2221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 17:08:23.493   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:23.509  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:23.515  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:23.518  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:23.521  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:23.528  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 17:08:23.528  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 17:08:23.530  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9c31f2d Bundle[{}]
,08-24 17:08:23.531  3789  3838 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 17:08:23.531  3789  3838 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 17:08:23.531  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 17:08:23.532  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 17:08:23.532  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 17:08:23.533  3789  3838 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:08:23.535   874  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-24 17:08:23.536   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 17:08:23.537   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-24 17:08:23.537  3789  3838 I System.out: Running OutgoingSocketThread
,08-24 17:08:23.537   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 17:08:23.538   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 17:08:23.538   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 17:08:23.538   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-24 17:08:23.538  3789  4203 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,08-24 17:08:23.539  3789  4203 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42251
08-24 17:08:23.539  3789  4203 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 17:08:23.550   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 17:08:23.550   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,08-24 17:08:23.550   874  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 17:08:23.551   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:23.558   874  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-24 17:08:23.558   874  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 17:08:23.559   874  1315 E native  : do suspend true
,08-24 17:08:23.572   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-24 17:08:23.572   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:23.574   874  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 17:08:23.580   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 17:08:23.581   874  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 17:08:23.664   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 17:08:23.666  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 17:08:24.084  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 17:08:24.128  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 17:08:24.129  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 17:08:24.142   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 17:08:24.154   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 17:08:24.155   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 17:08:24.155   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:24.175   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:24.192   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:24.193   874  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-24 17:08:24.210   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 17:08:24.269   874  4207 D DhcpClient: Receive thread started
,08-24 17:08:24.355   874  1315 E native  : do suspend false
,08-24 17:08:24.378   874  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 17:08:24.391   874  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-24 17:08:24.393   874  1893 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-24 17:08:24.397   874  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 17:08:24.412   874  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 17:08:24.413   874  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 17:08:24.418   372   872 D CommandListener: Setting iface cfg
,08-24 17:08:24.430   874  1893 D DhcpClient: Scheduling renewal in 86399s
,08-24 17:08:24.430   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 17:08:24.434   874  1315 E native  : do suspend true
,08-24 17:08:24.464   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 17:08:24.468   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 17:08:24.470   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-24 17:08:24.473   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-24 17:08:24.484   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 17:08:24.539  3789  3838 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-24 17:08:24.540  3789  3838 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-24 17:08:24.548  3789  3838 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-24 17:08:24.550  3789  3838 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-24 17:08:24.550  3789  3838 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-24 17:08:24.552  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:24.553  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e787a46 added. We now have 2 listener(s)
,08-24 17:08:24.554   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 17:08:24.555  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:24.555  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.555  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:24.555  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.555   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-24 17:08:24.555  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19407 added. We now have 9 listener(s)
08-24 17:08:24.555  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:24.556  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:08:24.557   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 17:08:24.558   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-24 17:08:24.559  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:24.560   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:24.569  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:24.572   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 17:08:24.573  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:24.573  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:24.573  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.574  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c035d added. We now have 3 listener(s)
,08-24 17:08:24.575  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:24.575  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.576  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:24.576  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.576  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b1f4d2 added. We now have 10 listener(s)
08-24 17:08:24.576  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.576  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:24.576  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.576  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:24.576  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.576  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.576  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:24.577  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.577  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e787a46 removed from the list
08-24 17:08:24.577  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.577  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19407 removed from the list
08-24 17:08:24.578   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 17:08:24.578   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-24 17:08:24.578   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-24 17:08:24.578   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 17:08:24.578   874  1318 D ConnectivityService:    accepting network in place of null
08-24 17:08:24.578  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:24.578  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:24.579   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 17:08:24.579  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.579  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.579   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 17:08:24.579  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.581  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:24.581  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.581  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.581  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b19407 not in the list
08-24 17:08:24.581  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.581  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.583  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.583  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.583  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.583  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b1f4d2 removed from the list
08-24 17:08:24.583  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.583  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.583  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.583  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.583  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c035d removed from the list
08-24 17:08:24.584  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.584  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac969a3 added. We now have 2 listener(s)
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.584  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:08:24.586  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:08:24.586  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.586  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:24.586  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.586  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03d4a0 added. We now have 9 listener(s)
08-24 17:08:24.586  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.586  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:08:24.587  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:08:24.589  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:24.590   874  4206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154563, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.592  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:08:24.594  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.594  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:24.594  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.594  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5968c1e added. We now have 3 listener(s)
08-24 17:08:24.596  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:24.596  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.596  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:24.596  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.596  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfefcff added. We now have 10 listener(s)
08-24 17:08:24.596  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.596  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:24.596  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.596  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:24.596  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 17:08:24.597  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:24.597  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:08:24.598  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.599  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 17:08:24.599  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:24.603  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:24.603  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 17:08:24.603  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:24.608  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:24.608  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:24.608  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:24.608  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:24.611  4148  4158 D BtGatt.GattService: registerClient() - UUID=098b4568-da91-48bd-b069-1dc6b22105b9
,08-24 17:08:24.611  4148  4166 D BtGatt.GattService: onClientRegistered() - UUID=098b4568-da91-48bd-b069-1dc6b22105b9, clientIf=5
08-24 17:08:24.612  3789  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 17:08:24.612  4148  4190 D BtGatt.GattService: start scan with filters
,08-24 17:08:24.615  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:24.615  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:24.615  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:24.615  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 17:08:24.616  4148  4169 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:24.618  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:24.618  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:24.618  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:08:24.619  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:24.620  4148  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1964244
,08-24 17:08:24.622  4148  4166 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:24.622  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.622  3789  3838 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:24.622  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.622  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 17:08:24.622  4148  4169 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 17:08:24.622  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.622  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:24.622  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:08:24.622  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:24.622  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:24.622  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:24.623  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:24.623  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 17:08:24.624  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:24.624  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 17:08:24.624  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.624  4148  4190 D BtGatt.GattService: stopScan() - queue size =1
08-24 17:08:24.624  4148  4169 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:08:24.624  4148  4169 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 17:08:24.626  4148  4179 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 17:08:24.626  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:08:24.626  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:24.626  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:24.626  4148  4166 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 17:08:24.626  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:24.626  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.626  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:24.627  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:24.628  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 17:08:24.628  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:24.628  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.628  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:24.628  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:08:24.628  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:24.630  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:24.630   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-24 17:08:24.630  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:24.630  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:24.631  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:24.631  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.631  4148  4169 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:24.633  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:24.633  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 17:08:24.633  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.633  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.633  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:24.633  4148  4169 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 17:08:24.634  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.634  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.634  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:24.634  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:24.634  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac969a3 removed from the list
08-24 17:08:24.634  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.634  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03d4a0 removed from the list
08-24 17:08:24.635  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:24.635  4148  4166 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 17:08:24.635  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.635  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:24.635  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.635  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.637  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.637  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:24.637  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.637  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d03d4a0 not in the list
08-24 17:08:24.637  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.637  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.638  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.639  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.639  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:24.639  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfefcff removed from the list
08-24 17:08:24.639  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.639  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.639  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.639  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.639  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5968c1e removed from the list
,08-24 17:08:24.640  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.640  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d06a1b added. We now have 2 listener(s)
,08-24 17:08:24.643  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:08:24.643  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.644  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:24.644  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.644  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef397b8 added. We now have 9 listener(s)
,08-24 17:08:24.644  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.645  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:24.647  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.653  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:24.656  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.656  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:24.656  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:24.657  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17a00f6 added. We now have 3 listener(s)
,08-24 17:08:24.658  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:24.660  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:08:24.660  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.660  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:24.661  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:24.661  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.661  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818cf7 added. We now have 10 listener(s)
08-24 17:08:24.661  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.661  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:24.662  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:24.662  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:24.662  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:24.662  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:24.662  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 17:08:24.663   874  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:814::200e,
,08-24 17:08:24.666  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 17:08:24.666  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 17:08:24.666   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 17:08:24.669   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-24 17:08:24.669   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 17:08:24.676   874   891 D Tethering: MasterInitialState.processMessage what=3
08-24 17:08:24.677   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-24 17:08:24.679  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.680  3789  3789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:08:24.680  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 17:08:24.681  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 17:08:24.683  3789  3789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.686  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.687  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:08:24.687  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:24.688  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 17:08:24.688  3789  3838 D BluetoothAdapter: STATE_ON
08-24 17:08:24.690  4148  4159 D BtGatt.GattService: registerClient() - UUID=3c158c06-9606-49ff-9115-ba30c9a0c3de
08-24 17:08:24.690  4148  4166 D BtGatt.GattService: onClientRegistered() - UUID=3c158c06-9606-49ff-9115-ba30c9a0c3de, clientIf=5
08-24 17:08:24.691  3789  3800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 17:08:24.691  4148  4158 D BtGatt.GattService: start scan with filters
,08-24 17:08:24.692  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 17:08:24.693  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:24.693  4148  4169 D BtGatt.ScanManager: handling starting scan
08-24 17:08:24.693  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:24.693  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:24.693  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:24.695  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:24.696  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:24.696  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:24.697  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:24.699  4148  4166 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:24.699  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.699  4148  4169 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 17:08:24.700  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:24.701  3789  3838 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 17:08:24.701  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:24.701  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.701  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:24.701  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.701  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.701  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:24.701  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.702  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d06a1b removed from the list
08-24 17:08:24.702  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.702  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef397b8 removed from the list
08-24 17:08:24.702  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:24.702  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:24.703  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.703  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 17:08:24.703  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.703  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:24.704  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.704  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.704  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.704  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef397b8 not in the list
,08-24 17:08:24.705  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:24.705  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:24.705  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:24.705  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:24.705  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 17:08:24.706  3789  3838 D BluetoothAdapter: STATE_ON
08-24 17:08:24.706  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 17:08:24.706  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.706  4148  4189 D BtGatt.GattService: stopScan() - queue size =1
08-24 17:08:24.706  4148  4169 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:24.706  4148  4169 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 17:08:24.707  4148  4190 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 17:08:24.707  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:24.707  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:24.707  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:24.708  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:08:24.708  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:24.708  1724  1724 D SystemUpdateService: onCreate
08-24 17:08:24.709  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:24.709  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:24.709  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:24.709  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:08:24.709  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:24.710  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:24.710  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:24.710  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:24.710  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.711  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.711  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.711  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1818cf7 removed from the list
08-24 17:08:24.711  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.711  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.711  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.711  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.711  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17a00f6 removed from the list
08-24 17:08:24.712  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.712  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b80193 added. We now have 2 listener(s)
08-24 17:08:24.713  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:08:24.714  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.714  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:24.714  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:24.714  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85a5d0 added. We now have 9 listener(s)
08-24 17:08:24.714  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.714  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-24 17:08:24.714  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:08:24.716  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:24.717  4148  4166 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 17:08:24.717  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.721  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:24.723  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.723  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:24.723  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:24.723  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c38ce added. We now have 3 listener(s)
,08-24 17:08:24.724  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 17:08:24.724  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.725  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.725  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 17:08:24.726  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.726  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:24.726  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.726  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d723ef added. We now have 10 listener(s)
,08-24 17:08:24.726  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.726  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:08:24.726  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:24.727  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:24.727  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:24.727  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:24.727  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.730  3789  3838 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 17:08:24.730  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:24.731  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:24.731  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.731  4148  4169 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:24.734  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:24.734  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 17:08:24.734  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:24.737  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 17:08:24.737  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.737  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:08:24.737  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:08:24.737  4148  4169 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 17:08:24.737  3789  3838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:24.737  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:24.739  4148  4158 D BtGatt.GattService: registerClient() - UUID=b5277666-8fff-4880-b804-533c374b81e7
,08-24 17:08:24.739  4148  4166 D BtGatt.GattService: onClientRegistered() - UUID=b5277666-8fff-4880-b804-533c374b81e7, clientIf=5
,08-24 17:08:24.740  3789  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 17:08:24.740  4148  4179 D BtGatt.GattService: start scan with filters
,08-24 17:08:24.742  4148  4166 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 17:08:24.742  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 17:08:24.742  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:08:24.743  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:24.743  4148  4169 D BtGatt.ScanManager: handling starting scan
08-24 17:08:24.743  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 17:08:24.743  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:24.745   874  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:08:24 GMT], X-Android-Received-Millis=[1472051304743], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472051304716]}
,08-24 17:08:24.745  1724  4216 I SystemUpdateService: active receiver: enabled
08-24 17:08:24.745   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 17:08:24.745   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-24 17:08:24.746   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 17:08:24.747  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 17:08:24.748  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:24.748  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:24.748  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:24.748   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 17:08:24.750  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 17:08:24.750  4148  4166 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 17:08:24.750  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.750  4148  4169 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 17:08:24.756  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 17:08:24.756  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.756  4148  4169 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:24.756  4148  4169 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 17:08:24.756  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:24.757  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.757  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:24.757  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.757  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.757  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:24.757  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:24.757  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b80193 removed from the list
08-24 17:08:24.757  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:24.757  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85a5d0 removed from the list
,08-24 17:08:24.757  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:24.757  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-24 17:08:24.758  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.758  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 17:08:24.758  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.758  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.759  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85a5d0 not in the list
08-24 17:08:24.759  1724  2453 I iu.UploadsManager: num queued entries: 0
,08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:24.759  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:24.759  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 17:08:24.759  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 17:08:24.759  1724  2453 I iu.UploadsManager: num updated entries: 0
08-24 17:08:24.760  3789  3838 D BluetoothAdapter: STATE_ON
,08-24 17:08:24.760  4148  4158 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:24.761  4148  4179 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 17:08:24.761  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:24.761  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:24.761  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:08:24.761  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:24.761  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:24.762  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 17:08:24.763  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-24 17:08:24.763  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:24.764  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-24 17:08:24.764  3789  3838 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:24.764  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 17:08:24.766  4148  4166 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-24 17:08:24.766  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.766  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.768  3949  3949 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:24.768  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.768  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.768  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:24.769  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d723ef removed from the list
,08-24 17:08:24.769  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:24.769  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:24.769  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:24.769  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.769  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.769  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30c38ce removed from the list
08-24 17:08:24.769  3789  3789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:24.769  3789  3789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:24.769  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.770  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1c100b added. We now have 2 listener(s)
08-24 17:08:24.771  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:24.771  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.771  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:24.771  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:24.772  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b585ee8 added. We now have 9 listener(s)
08-24 17:08:24.772  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 17:08:24.772  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.772  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.772  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:08:24.774  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:24.776  1724  4219 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-24 17:08:24.776  1724  4219 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:08:24.778  3789  3838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:08:24.778  4148  4166 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 17:08:24.778  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.778  4148  4169 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:08:24.779  3949  3949 D SprintDMHelper: simOperator: 
08-24 17:08:24.779  3949  3949 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-24 17:08:24.779  3789  3838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:08:24.780  3789  3838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:24.780  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:24.780  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30293a6 added. We now have 3 listener(s)
08-24 17:08:24.782  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.782  1724  4219 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 17:08:24.782  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 17:08:24.782  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:24.782  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:24.783  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:24.783  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@979a1e7 added. We now have 10 listener(s)
,08-24 17:08:24.783  3789  3838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:24.783  3789  3789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:24.784  3789  3838 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:24.784  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:24.784  4148  4166 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 17:08:24.784  3789  3838 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:24.784  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.784  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:24.784  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.784  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:24.784  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.784  4148  4169 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 17:08:24.785  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1c100b removed from the list
08-24 17:08:24.785  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.785  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b585ee8 removed from the list
08-24 17:08:24.785  3789  3838 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:24.785  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.786  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.787  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.787  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.788  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:24.788  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:24.788  3789  3838 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b585ee8 not in the list
08-24 17:08:24.788  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.788  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:24.789  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:24.789  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:24.789  3789  3838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:24.789  3789  3838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@979a1e7 removed from the list
08-24 17:08:24.789  3789  3838 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:24.789  3789  3838 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:24.789  3789  3838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:24.789  3789  3838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:24.789  3789  3838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30293a6 removed from the list
08-24 17:08:24.790  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-24 17:08:24.790  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 17:08:24.791  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 17:08:24.791  4148  4166 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 17:08:24.791  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:24.791  4148  4166 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 17:08:24.791  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 17:08:24.791  3789  3838 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:24.796  3789  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,08-24 17:08:24.797  3789  4222 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-24 17:08:24.797  3789  4222 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 17:08:24.798  3789  4223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
08-24 17:08:24.798  3789  4223 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-24 17:08:24.798  3789  4223 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 17:08:24.800  3789  3838 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 17:08:24.800  3789  3838 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 17:08:24.800  3789  3838 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 17:08:24.800  3789  3838 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 17:08:24.800  3789  3838 D com.test.thalitest.ThaliTestRunner: Total duration: 21859 ms
,08-24 17:08:24.802  3789  3838 I jxcore-log: Total number of executed tests:  80
08-24 17:08:24.802  3789  3838 I jxcore-log: 
,08-24 17:08:24.802  3789  3838 I jxcore-log: Number of passed tests:  80
08-24 17:08:24.802  3789  3838 I jxcore-log: 
08-24 17:08:24.802  3789  3838 I jxcore-log: Number of failed tests:  0
08-24 17:08:24.802  3789  3838 I jxcore-log: 
08-24 17:08:24.802  3789  3838 I jxcore-log: Number of ignored tests:  0
08-24 17:08:24.802  3789  3838 I jxcore-log: 
08-24 17:08:24.802  3789  3838 I jxcore-log: Total duration:  21859
08-24 17:08:24.802  3789  3838 I jxcore-log: 
,08-24 17:08:24.803  3789  3838 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 17:08:24.803  3789  3838 I jxcore-log: 
,08-24 17:08:24.806  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.806  3789  3838 I jxcore-log: 
08-24 17:08:24.810  3789  3789 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 17:08:24.810  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.810  3789  3838 I jxcore-log: 
08-24 17:08:24.811  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.811  3789  3838 I jxcore-log: 
08-24 17:08:24.812  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.812  3789  3838 I jxcore-log: 
08-24 17:08:24.813  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.813  3789  3838 I jxcore-log: 
,08-24 17:08:24.815  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.815  3789  3838 I jxcore-log: 
,08-24 17:08:24.817  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.817  3789  3838 I jxcore-log: 
08-24 17:08:24.819  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.819  3789  3838 I jxcore-log: 
08-24 17:08:24.819  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.819  3789  3838 I jxcore-log: 
08-24 17:08:24.820  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:24.820  3789  3838 I jxcore-log: 
08-24 17:08:24.822  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:24.822  3789  3838 I jxcore-log: 
08-24 17:08:24.822  1724  4216 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-24 17:08:24.822  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 17:08:24.822  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:24.822  3789  3838 I jxcore-log: 
08-24 17:08:24.823  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.823  3789  3838 I jxcore-log: 
08-24 17:08:24.824  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 17:08:24.824  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.824  3789  3838 I jxcore-log: 
08-24 17:08:24.824  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.824  3789  3838 I jxcore-log: 
,08-24 17:08:24.825  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.825  3789  3838 I jxcore-log: 
,08-24 17:08:24.826  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.826  3789  3838 I jxcore-log: 
,08-24 17:08:24.826  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.826  3789  3838 I jxcore-log: 
08-24 17:08:24.827  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.827  3789  3838 I jxcore-log: 
,08-24 17:08:24.828  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.828  3789  3838 I jxcore-log: 
,08-24 17:08:24.828  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.828  3789  3838 I jxcore-log: 
,08-24 17:08:24.829  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:24.829  3789  3838 I jxcore-log: 
08-24 17:08:24.829  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:24.829  3789  3838 I jxcore-log: 
,08-24 17:08:24.830  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:24.830  3789  3838 I jxcore-log: 
,08-24 17:08:24.831  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.831  3789  3838 I jxcore-log: 
08-24 17:08:24.831  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:24.831  3789  3838 I jxcore-log: 
,08-24 17:08:24.832  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.832  3789  3838 I jxcore-log: 
,08-24 17:08:24.832  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.832  3789  3838 I jxcore-log: 
,08-24 17:08:24.833  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.833  3789  3838 I jxcore-log: 
08-24 17:08:24.834  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.834  3789  3838 I jxcore-log: 
,08-24 17:08:24.834  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:24.834  3789  3838 I jxcore-log: 
,08-24 17:08:24.845  1724  4216 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 17:08:24.846  1724  2453 I iu.SyncManager: NEXT; no task
,08-24 17:08:24.847  1724  4216 I SystemUpdateService: now status is 0 (complete)
,08-24 17:08:24.847  1724  4216 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 17:08:24.847  1724  4216 I SystemUpdateService: file has been verified
,08-24 17:08:24.848  1724  4216 I SystemUpdateService: OTA package size = 12249756
,08-24 17:08:24.854  1724  4216 I SystemUpdateService: showing system update notification
,08-24 17:08:24.856  1524  2035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-24 17:08:24.856  1524  2035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 17:08:24.856  1524  2035 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 17:08:24.856  1524  2035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 17:08:24.867  1724  1724 D SystemUpdateService: onDestroy
,08-24 17:08:24.870  1724  4219 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-24 17:08:24.952  2289  4224 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 17:08:25.132  3789  3789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:25.135  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:25.135  3789  3838 I jxcore-log: 
,08-24 17:08:25.212  3789  3789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:25.215  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:25.215  3789  3838 I jxcore-log: 
,08-24 17:08:25.271  3789  3789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:25.274  3789  3838 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:25.274  3789  3838 I jxcore-log: 
,08-24 17:08:25.478  4228  4228 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 17:08:25.483  4228  4228 D AndroidRuntime: CheckJNI is OFF
,08-24 17:08:25.525  4228  4228 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 17:08:25.573  4228  4228 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 17:08:25.596  4228  4228 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 17:08:25.609   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-24 17:08:25.609   874   887 I ActivityManager: Killing 3789:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-24 17:08:25.656  1993  2649 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 17:08:25.670   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-24 17:08:25.715   874  2223 D GraphicsStats: Buffer count: 2
08-24 17:08:25.715   874  2221 I WindowState: WIN DEATH: Window{ece14b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 17:08:25.718   874  1317 D WifiService: Client connection lost with reason: 4
,08-24 17:08:25.748   874   898 W PackageSettings: Skipping PackageSetting{e10b001 com.example.hello/10273} due to missing metadata
,08-24 17:08:25.793   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-24 17:08:25.793   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-24 17:08:25.793   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-24 17:08:25.793   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 17:08:25.793   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:25.793   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:25.793   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 17:08:25.793   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 17:08:25.794   874   887 I ActivityManager:   Force finishing activity ActivityRecord{ef20545 u0 com.test.thalitest/.MainActivity t2}
08-24 17:08:25.799   874  1398 W ActivityManager: Spurious death for ProcessRecord{fa5873a 0:com.test.thalitest/u0a0}, curProc for 3789: null
08-24 17:08:25.802   874   898 I art     : Starting a blocking GC Explicit
,08-24 17:08:25.874   874   898 I art     : Explicit concurrent mark sweep GC freed 54799(3MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 1.160ms total 71.779ms
,08-24 17:08:25.919   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 17:08:25.924  4228  4228 I art     : System.exit called, status: 0
,08-24 17:08:25.924  4228  4228 I AndroidRuntime: VM exiting with result code 0.
,08-24 17:08:25.929   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 17:08:25.946   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-24 17:08:25.950  4148  4148 D BluetoothMapAppObserver: onReceive
,08-24 17:08:25.950  4148  4148 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-24 17:08:25.952  1993  2286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 17:08:25.954   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 17:08:25.959  3657  3657 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-24 17:08:25.958  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 17:08:25.978  1940  1940 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 17:08:25.979  1873  4243 I Keyboard.Facilitator.DecoderInitializer: run()
08-24 17:08:25.980   874  1926 I ActivityManager: Start proc 4245:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-24 17:08:26.006  1873  4243 I Decoder : createOrResetDecoder
,08-24 17:08:26.030  1524  1524 I ConfigService: onCreate
,08-24 17:08:26.036  4245  4245 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-24 17:08:26.061   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 17:08:26.064   874  1696 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3789 uid 10000
,08-24 17:08:26.068  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-24 17:08:26.068  1873  4243 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 17:08:26.102  1957  2057 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-24 17:08:26.104   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 17:08:26.105   874   886 E PackageManager: Failed to write settings, restoring backup
08-24 17:08:26.105   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 17:08:26.105   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 17:08:26.105   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 17:08:26.105   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 17:08:26.105   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 17:08:26.105   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.105   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.105   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 17:08:26.109   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-24 17:08:26.109   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 17:08:26.109   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.109   874   887 E DropBoxManagerService: 	... 13 more
,08-24 17:08:26.114   874  1398 I ActivityManager: Start proc 4261:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-24 17:08:26.115  1957  2057 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 17:08:26.115  1957  2057 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1957
08-24 17:08:26.115  1957  2057 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.115  1957  2057 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 17:08:26.118   874  2222 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 17:08:26.118   874  4271 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.118   874  4271 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.118   874  4271 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.121  1957  2057 I Process : Sending signal. PID: 1957 SIG: 9
,08-24 17:08:26.127  1873  4243 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-24 17:08:26.134  4245  4245 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-24 17:08:26.135  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 17:08:26.135  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-24 17:08:26.138  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 17:08:26.138  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 17:08:26.139  1873  4243 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 17:08:26.140  1873  4243 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 17:08:26.140  1873  4243 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 17:08:26.157  4245  4275 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-24 17:08:26.157   874  2222 I ActivityManager: Start proc 4276:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-24 17:08:26.181  4245  4275 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.181  4245  4275 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 17:08:26.182  4245  4275 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 17:08:26.182  4245  4275 E AndroidRuntime: Process: android.process.acore, PID: 4245
08-24 17:08:26.182  4245  4275 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.182  4245  4275 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 17:08:26.184   874  4289 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.184   874  4289 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.184   874  4289 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.195  4245  4275 I Process : Sending signal. PID: 4245 SIG: 9
,08-24 17:08:26.203  4276  4276 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-24 17:08:26.217   281   281 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
,08-24 17:08:26.220   874  1956 D GraphicsStats: Buffer count: 1
,08-24 17:08:26.220   874  2222 I WindowState: WIN DEATH: Window{bfdf4c3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-24 17:08:26.232   874  1927 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1957) has died
,08-24 17:08:26.233   874  1927 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-24 17:08:26.235   874  1927 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 17:08:26.251   874   887 I ActivityManager: Start proc 4293:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 17:08:26.258   281   281 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
08-24 17:08:26.258   281   281 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
,08-24 17:08:26.263  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-24 17:08:26.264  1524  1524 D AndroidRuntime: Shutting down VM
,08-24 17:08:26.264  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
08-24 17:08:26.264  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
08-24 17:08:26.264  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 17:08:26.264  1524  1524 E AndroidRuntime: 	... 8 more
,08-24 17:08:26.273  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
,08-24 17:08:26.275   874  4307 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.275   874  4307 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.275   874  4307 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.283  1724  4291 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-24 17:08:26.285  1724  4291 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-24 17:08:26.296  4293  4293 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.296  4293  4293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:26.297  4293  4293 D AndroidRuntime: Shutting down VM
,08-24 17:08:26.303  4293  4293 E AndroidRuntime: FATAL EXCEPTION: main
08-24 17:08:26.303  4293  4293 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4293
08-24 17:08:26.303  4293  4293 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.303  4293  4293 E AndroidRuntime: 	... 10 more
08-24 17:08:26.304   874  1927 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
08-24 17:08:26.304   874  1927 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-24 17:08:26.305   874  1927 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-24 17:08:26.305   874  1927 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-24 17:08:26.305   874  1317 D WifiService: Client connection lost with reason: 4
,08-24 17:08:26.305   874  1927 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
08-24 17:08:26.307   281   281 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
08-24 17:08:26.308   281   281 E lowmemorykiller: Error writing /proc/4245/oom_score_adj; errno=22
08-24 17:08:26.309   874  2222 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 17:08:26.310  4293  4293 I Process : Sending signal. PID: 4293 SIG: 9
08-24 17:08:26.310   874  4308 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.310   874  4308 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.310   874  4308 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.319  1724  1724 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-24 17:08:26.328   874  1939 I ActivityManager: Start proc 4309:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-24 17:08:26.330   874  1696 I ActivityManager: Process android.process.acore (pid 4245) has died,
,08-24 17:08:26.330   874  1696 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40975ms
,08-24 17:08:26.335   874  1927 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4293) has died
,08-24 17:08:26.336   874  1927 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 17:08:26.340  1724  4291 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 17:08:26.342  1724  4291 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-24 17:08:26.350   874   887 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-24 17:08:26.363  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-24 17:08:26.363  1724  1724 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-24 17:08:26.368  4309  4309 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-24 17:08:26.378  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-24 17:08:26.378  1724  1724 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-24 17:08:26.379  4309  4309 I MultiDex: VM with version 2.1.0 has multidex support
,08-24 17:08:26.380  4309  4309 I MultiDex: install
08-24 17:08:26.380  4309  4309 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 17:08:26.383  1724  4336 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 17:08:26.384  4309  4309 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-24 17:08:26.387  2036  4335 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-24 17:08:26.388  4309  4309 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.390  4309  4309 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 17:08:26.390  4309  4309 D AndroidRuntime: Shutting down VM
08-24 17:08:26.390  4309  4309 E AndroidRuntime: FATAL EXCEPTION: main
08-24 17:08:26.390  4309  4309 E AndroidRuntime: Process: com.google.process.gapps, PID: 4309
08-24 17:08:26.390  4309  4309 E Android,Runtime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.390  4309  4309 E AndroidRuntime: 	... 10 more
,08-24 17:08:26.397  4322  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.397  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 17:08:26.398  4322  4322 D AndroidRuntime: Shutting down VM
08-24 17:08:26.398  1724  4336 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-24 17:08:26.398  1724  4336 E AndroidRuntime: Process: com.google.android.gms, PID: 1724
08-24 17:08:26.398  1724  4336 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 17:08:26.398  1724  4336 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-24 17:08:26.408  4309  4309 I Process : Sending signal. PID: 4309 SIG: 9
,08-24 17:08:26.410  4322  4322 E AndroidRuntime: FATAL EXCEPTION: main
08-24 17:08:26.410  4322  4322 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4322
08-24 17:08:26.410  4322  4322 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 17:08:26.410  4322  4322 E AndroidRuntime: 	... 10 more
,08-24 17:08:26.411   874  1939 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-24 17:08:26.412   874  1939 I ActivityManager: Killing 1724:com.google.android.gms/u0a11 (adj 1): crash
,08-24 17:08:26.413   874  4338 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.413   874  4338 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.413   874  4338 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.414   874  4339 E DropBoxManagerService: Can't write: system_app_crash
08-24 17:08:26.414   874  4339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 17:08:26.414   874  4339 E DropBoxManagerService: 	... 5 more
,08-24 17:08:26.430  2036  4335 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 17:08:26.440   283   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
