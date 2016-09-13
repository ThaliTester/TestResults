#### Test 8362733700cd7fa_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-13 12:56:51.648  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 12:56:51.659  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 12:56:51.661  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 12:56:51.698  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-13 12:56:51.699  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 12:56:51.699  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:56:51.699  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 12:56:51.744  3525  3525 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-13 12:56:51.745  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 12:56:51.746  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 12:56:52.803  3796  3796 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 12:56:52.807  3796  3796 D AndroidRuntime: CheckJNI is OFF
09-13 12:56:52.843  3796  3796 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 12:56:52.885  3796  3796 I Radio-JNI: register_android_hardware_Radio DONE
09-13 12:56:52.905  3796  3796 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 12:56:52.912   873  1923 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 12:56:52.954  2065  2079 W SearchService: Abort, client detached.
09-13 12:56:52.972  2065  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2eee805
09-13 12:56:52.972  2065  2065 I HotwordDetector: Closing mic
09-13 12:56:52.972  2065  2345 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 12:56:52.985  3796  3796 D AndroidRuntime: Shutting down VM
09-13 12:56:53.011   873  1922 I ActivityManager: Start proc 3805:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 12:56:53.036   376  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 12:56:53.037   376  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 12:56:53.042   376  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 12:56:53.044  2065  2337 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 12:56:53.045  2065  2344 I MicroRecognitionRnrImpl: Detection finished
09-13 12:56:53.084  3805  3805 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 12:56:53.106  3805  3805 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 12:56:53.122  3805  3805 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 603-615)
09-13 12:56:53.122  3805  3805 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:56:53.147  3805  3805 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a07f220}
09-13 12:56:53.147  3805  3805 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 12:56:53.147  3805  3805 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 12:56:53.154  3805  3805 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 12:56:53.156  3805  3805 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 12:56:53.181  3805  3805 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 12:56:53.220  3805  3805 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 12:56:53.220  3805  3805 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 12:56:53.220  3805  3805 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 12:56:53.220  3805  3805 I Adreno  : Build Date                       : 10/20/15
09-13 12:56:53.220  3805  3805 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 12:56:53.220  3805  3805 I Adreno  : Local Branch                     : M14
09-13 12:56:53.220  3805  3805 I Adreno  : Remote Branch                    : 
09-13 12:56:53.220  3805  3805 I Adreno  : Remote Branch                    : 
09-13 12:56:53.220  3805  3805 I Adreno  : Reconstruct Branch               : 
,09-13 12:56:53.303   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44d0cc6:true
,09-13 12:56:53.347  3805  3805 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 12:56:53.363  3805  3805 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 12:56:53.450  3805  3844 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 12:56:53.476  3805  3830 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 12:56:53.520  3805  3844 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 12:56:53.627   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +641ms
,09-13 12:56:53.635  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 12:56:53.770  3805  3805 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3805
,09-13 12:56:53.810   873  1932 I ActivityManager: Killing 3392:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 12:56:53.870   873  1932 I ActivityManager: Killing 2973:com.google.android.calendar/u0a37 (adj 15): empty #18
,09-13 12:56:53.921  3805  3805 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:56:54.142  3805  3846 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696925392
,09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 12:56:54.148  3805  3846 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4074da4 added. We now have 1 listener(s)
,09-13 12:56:54.152  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 12:56:54.155  3805  3846 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:56:54.156  3805  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:56:54.157  3805  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 12:56:54.163  3805  3846 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6467cd3 added. We now have 1 listener(s)
09-13 12:56:54.164  3805  3846 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:56:54.167   873  1303 D WifiService: New client listening to asynchronous messages
,09-13 12:56:54.168  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:56:54.168  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 12:56:54.169  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 12:56:54.169  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 12:56:54.169  3805  3846 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 12:56:54.178  3805  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:56:54.178  3805  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 12:56:54.185  3805  3846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:56:54.186  3805  3846 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:56:54.186  3805  3846 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 12:56:54.186  3805  3846 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:56:54.187  3805  3846 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 12:56:54.273  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:56:54.287  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:56:54.289  3805  3805 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:56:55.064  3805  3857 W jxcore-log: Initializing JXcore engine
,09-13 12:56:55.064  3805  3857 W jxcore-log: JXcore engine is ready
,09-13 12:56:55.101  3857  3857 W Thread-331: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 12:56:55.101  3857  3857 W Thread-331: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9821]" dev="sockfs" ino=9821 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 12:56:55.101  3857  3857 W Thread-331: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-13 12:56:55.113  3805  3857 W jxcore-log: Starting JXcore engine
,09-13 12:56:55.101  3857  3857 W Thread-331: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27707]" dev="sockfs" ino=27707 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 12:56:55.227  3805  3857 W jxcore-log: Platform android
09-13 12:56:55.227  3805  3857 W jxcore-log: 
,09-13 12:56:55.228  3805  3857 W jxcore-log: Process ARCH arm
09-13 12:56:55.228  3805  3857 W jxcore-log: 
,09-13 12:56:55.443  3805  3857 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:56:55.443  3805  3857 I jxcore-log: 
,09-13 12:56:55.444  3805  3857 W jxcore-log: JXcore engine is started
,09-13 12:56:55.454  3805  3846 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 12:56:55.459  3805  3805 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:56:55.918   873  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 12:57:03.003  3616  3865 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 12:57:03.106  3616  3869 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 12:57:03.118  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:03.119  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:03.134  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 12:57:03.134  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 12:57:03.134  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:03.134  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:03.151  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:03.152  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:03.165  1495  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 12:57:03.165  1495  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 12:57:03.165  1495  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:03.165  1495  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:03.178  3616  3869 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 12:57:03.180  3616  3865 E BooksSync: Soft error
09-13 12:57:03.180  3616  3865 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:57:03.180  3616  3865 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 12:57:03.180  3616  3865 E BooksSync: Sync error
09-13 12:57:03.180  3616  3865 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 12:57:03.180  3616  3865 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 12:57:03.180  3616  3865 I BooksSync: Finished books sync
,09-13 12:57:03.182   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130399, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:57:05.687  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:57:05.687  3805  3857 I jxcore-log: 
,09-13 12:57:05.689  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:57:05.689  3805  3857 I jxcore-log: 
,09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:05.699  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:05.702  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:05.705  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:57:05.705  3805  3857 I jxcore-log: 
,09-13 12:57:05.707  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:57:05.707  3805  3857 I jxcore-log: 
,09-13 12:57:06.216  3805  3857 I jxcore-log: Unit Test app is loaded
09-13 12:57:06.216  3805  3857 I jxcore-log: 
,09-13 12:57:06.222  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:06.222  3805  3857 I jxcore-log: 
,09-13 12:57:06.228  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 12:57:06.228  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7721db0 added. We now have 2 listener(s)
09-13 12:57:06.230  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:06.230  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:57:06.230  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 12:57:06.230  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:57:06.230  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c27429 added. We now have 2 listener(s)
,09-13 12:57:06.230  3805  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:57:06.231  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 12:57:06.233  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:06.240  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:06.244  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:06.244  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:57:06.244  3805  3857 D ExecuteNativeTests: Running unit tests
09-13 12:57:06.245  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:57:06.245  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@770654f added. We now have 3 listener(s)
,09-13 12:57:06.246  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 12:57:06.246  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:57:06.246  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:57:06.246  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:57:06.246  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d364dc added. We now have 3 listener(s)
09-13 12:57:06.246  3805  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:57:06.246  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:57:06.257  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:06.260  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:06.264  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:06.264  3805  3805 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:06.269  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:06.270  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:06.270  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:57:06.271  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:06.277  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:12.074  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:12.093  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:12.099  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:12.195  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:57:12.196  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 12:57:12.197  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:12.197  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:12.258  3525  3525 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 12:57:12.260  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 12:57:12.262  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 12:57:16.365  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:57:16.365  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a added. We now have 4 listener(s)
,09-13 12:57:16.366  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:16.366  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:57:16.366  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:57:16.366  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:57:16.367  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b added. We now have 4 listener(s)
,09-13 12:57:16.367  3805  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 12:57:16.367  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:57:16.372  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:16.382  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:16.385  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:16.385  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:57:16.402  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 12:57:16.404  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:57:16.404  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:57:16.404  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:57:16.404  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:57:16.405  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:16.406  3805  3857 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 12:57:16.406  3805  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 12:57:16.406  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 12:57:16.407  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:16.407  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:16.407  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:16.407  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:16.407  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:16.407  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:16.407  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:16.408  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 12:57:16.408  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a removed from the list
09-13 12:57:16.408  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:16.408  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b removed from the list
,09-13 12:57:16.412  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:16.413  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:16.413  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:16.416  3805  3857 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 12:57:16.416  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:16.416  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:16.416  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:16.417  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:16.417  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:16.417  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:16.417  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:16.417  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:16.417  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:16.423  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 12:57:16.423  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 12:57:16.424  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 12:57:16.425  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 12:57:16.426  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:16.426  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:16.426  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:16.426  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
,09-13 12:57:16.426  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:16.426  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:16.426  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:16.426  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:16.426  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:16.427  3805  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 12:57:16.429  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:16.438  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:16.441  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:16.442  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:57:16.442  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 12:57:16.442  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 12:57:16.443  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:57:16.443  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 12:57:16.443  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:57:16.444  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:16.445  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 12:57:16.448  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:16.449  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 12:57:16.449  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:57:16.450  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:57:16.450  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:16.450  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 12:57:16.451  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:57:16.451  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:16.453  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 12:57:16.457  3805  3871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:16.459  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 12:57:16.459  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 12:57:16.460  3805  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 12:57:16.465  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:16.467  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 12:57:16.468  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:16.471  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 12:57:16.472  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 12:57:16.472  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-13 12:57:16.473  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:16.473  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:16.473  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 12:57:16.474  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:16.482  2658  2780 D BtGatt.GattService: registerClient() - UUID=1932685c-5536-4926-b014-21262e96a0e2
,09-13 12:57:16.483  2658  2679 D BtGatt.GattService: onClientRegistered() - UUID=1932685c-5536-4926-b014-21262e96a0e2, clientIf=5
,09-13 12:57:16.484  3805  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:16.486  2658  2692 D BtGatt.AdvertiseManager: message : 0
,09-13 12:57:16.490  2658  2692 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 12:57:16.503  2658  2679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:16.516  2658  2679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 12:57:16.519  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 12:57:16.519  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:16.524  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:16.528  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:16.528  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 12:57:16.528  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 12:57:16.528  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 12:57:16.529  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 12:57:16.529  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 12:57:16.530  3805  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 12:57:16.533  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 12:57:16.534  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:17.036  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:17.036  3805  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 12:57:17.037  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 12:57:17.037  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 12:57:17.039  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 12:57:17.039  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 12:57:17.040  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 12:57:17.040  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 12:57:17.040  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:17.042  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
09-13 12:57:17.042  3805  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 12:57:17.042  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 12:57:17.043  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 12:57:17.042  3805  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 12:57:17.043  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:17.043  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:57:17.043  3805  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:17.043  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 12:57:17.044  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:57:17.045  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 12:57:17.048  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:17.050  3805  3857 D BluetoothLeScanner: could not find callback wrapper
09-13 12:57:17.050  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:17.050  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 12:57:17.053  2658  2692 D BtGatt.AdvertiseManager: message : 1
,09-13 12:57:17.055  2658  2692 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:17.078  2658  2679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 12:57:17.079  2658  2679 D BtGatt.GattService: Client app is not null!
,09-13 12:57:17.083  2658  2670 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 12:57:17.084  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 12:57:17.085  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 12:57:17.085  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 12:57:17.085  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 12:57:17.085  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 12:57:17.089  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:17.089  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 12:57:17.090  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:57:17.091  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:17.095  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 12:57:17.095  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:17.095  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:17.096  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:17.096  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:17.096  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:17.098  3805  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 12:57:17.098  3805  3857 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 12:57:17.098  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 12:57:17.098  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 12:57:17.099  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:57:17.099  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 12:57:17.099  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:57:17.099  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:17.101  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:57:17.102  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 12:57:17.102  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:57:17.102  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:57:17.102  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:57:17.103  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 12:57:17.103  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:17.103  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:57:17.104  3805  3874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:17.108  3805  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 12:57:17.112  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 12:57:17.112  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 12:57:17.118  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:17.119  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 12:57:17.119  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:17.123  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 12:57:17.123  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:17.123  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,09-13 12:57:17.124  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:17.124  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 12:57:17.124  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 12:57:17.128  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:17.134  2658  2669 D BtGatt.GattService: registerClient() - UUID=185507ad-207c-454b-a11b-b83e530b1eee
,09-13 12:57:17.135  2658  2679 D BtGatt.GattService: onClientRegistered() - UUID=185507ad-207c-454b-a11b-b83e530b1eee, clientIf=5
,09-13 12:57:17.136  3805  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:17.138  2658  2692 D BtGatt.AdvertiseManager: message : 0
,09-13 12:57:17.143  2658  2692 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 12:57:17.166  2658  2679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:17.178  2658  2679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 12:57:17.179  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 12:57:17.180  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 12:57:17.183  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:17.187  3805  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 12:57:17.187  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
,09-13 12:57:17.188  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 12:57:17.188  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 12:57:17.188  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 12:57:17.188  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 12:57:17.189  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 12:57:17.197  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:17.197  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:17.450  1464  1464 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-13 12:57:17.692  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:17.692  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 12:57:17.693  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 12:57:17.693  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:17.695  3805  3874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:57:17.695  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 12:57:17.696  3805  3874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 12:57:17.696  3805  3874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 12:57:17.696  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:57:17.697  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:17.697  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
,09-13 12:57:17.697  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:17.697  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:17.697  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:17.698  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:57:17.698  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:17.698  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:57:17.699  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 12:57:17.702  3805  3857 D BluetoothAdapter: STATE_ON
09-13 12:57:17.703  3805  3857 D BluetoothLeScanner: could not find callback wrapper
,09-13 12:57:17.703  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:17.704  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 12:57:17.707  2658  2692 D BtGatt.AdvertiseManager: message : 1
09-13 12:57:17.708  2658  2692 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:17.726  2658  2679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 12:57:17.726  2658  2679 D BtGatt.GattService: Client app is not null!
09-13 12:57:17.727  2658  2782 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 12:57:17.727  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 12:57:17.727  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 12:57:17.727  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 12:57:17.727  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 12:57:17.727  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 12:57:17.729  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:17.730  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 12:57:17.730  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:57:17.731  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:17.734  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:17.734  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:17.734  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:17.734  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:17.734  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:17.736  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:17.739  3805  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 12:57:17.743  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:17.754  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:17.761  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:17.762  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:57:17.763  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 12:57:17.764  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-13 12:57:17.768  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:17.769  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:17.770  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 12:57:17.771  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:57:17.771  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:17.773  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 12:57:17.775  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:17.775  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 12:57:17.775  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:57:17.776  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 12:57:17.776  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:57:17.778  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 12:57:17.778  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:17.778  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:57:17.780  3805  3876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:17.784  3805  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 12:57:17.787  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 12:57:17.788  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 12:57:17.799  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:17.801  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 12:57:17.801  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:17.806  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 12:57:17.807  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:17.807  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 12:57:17.807  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:17.807  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 12:57:17.807  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 12:57:17.809  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:17.815  2658  2782 D BtGatt.GattService: registerClient() - UUID=5188a1be-6a74-49af-9ba7-8c338e1770da
,09-13 12:57:17.816  2658  2679 D BtGatt.GattService: onClientRegistered() - UUID=5188a1be-6a74-49af-9ba7-8c338e1770da, clientIf=5
,09-13 12:57:17.817  3805  3849 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:17.818  2658  2692 D BtGatt.AdvertiseManager: message : 0
,09-13 12:57:17.826  2658  2692 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 12:57:17.852  2658  2679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:17.874  2658  2679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 12:57:17.875  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 12:57:17.875  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:17.882  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:17.886  3805  3857 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 12:57:17.886  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:57:17.886  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 12:57:17.887  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 12:57:17.887  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 12:57:17.887  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 12:57:17.887  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 12:57:17.895  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true,
09-13 12:57:17.896  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:18.391  3805  3857 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 12:57:18.391  3805  3857 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 12:57:18.392  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 12:57:18.392  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 12:57:18.392  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 12:57:18.393  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 12:57:18.393  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:18.394  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 12:57:18.395  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:57:18.395  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 12:57:18.395  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 12:57:18.395  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:18.396  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 12:57:18.396  3805  3876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:57:18.396  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 12:57:18.396  3805  3876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:57:18.397  3805  3876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:18.397  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:18.398  3805  3857 D BluetoothAdapter: STATE_ON
09-13 12:57:18.399  3805  3857 D BluetoothLeScanner: could not find callback wrapper
09-13 12:57:18.399  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:18.399  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 12:57:18.402  2658  2692 D BtGatt.AdvertiseManager: message : 1
09-13 12:57:18.403  2658  2692 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:18.417  2658  2679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 12:57:18.417  2658  2679 D BtGatt.GattService: Client app is not null!
,09-13 12:57:18.421  2658  2780 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 12:57:18.422  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 12:57:18.422  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 12:57:18.423  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 12:57:18.423  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 12:57:18.423  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 12:57:18.425  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:18.425  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 12:57:18.425  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:57:18.427  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:18.431  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 12:57:18.431  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:18.432  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:18.433  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.433  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.433  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:57:18.433  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.434  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:18.434  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.434  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.434  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.434  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:18.436  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:18.437  3805  3857 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 12:57:18.437  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 12:57:18.438  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:18.439  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:18.439  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.440  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.440  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.440  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:18.440  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.441  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.441  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.441  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:18.444  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 12:57:18.444  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.445  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.445  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.445  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.445  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:18.446  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.446  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.446  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.447  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:18.447  3805  3857 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 12:57:18.447  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.447  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.447  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.448  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.448  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:18.448  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.448  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.448  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.448  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.448  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 12:57:18.449  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.449  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.449  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.449  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.449  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:18.449  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.449  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.449  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.449  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.450  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 12:57:18.452  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:57:18.452  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:57:18.452  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:57:18.453  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 12:57:18.453  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:18.453  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 12:57:18.453  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:18.453  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 12:57:18.453  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 12:57:18.453  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:57:18.454  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 12:57:18.454  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.454  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.454  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:18.454  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.454  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:18.454  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.454  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.454  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.454  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.456  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 12:57:18.456  3805  3857 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 12:57:18.456  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 12:57:18.460  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:57:18.460  3805  3857 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 12:57:18.461  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-13 12:57:18.462  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 12:57:18.462  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 12:57:18.462  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 12:57:18.465  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-13 12:57:18.466  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 12:57:18.466  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-13 12:57:18.467  3805  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:57:18.467  3805  3857 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 12:57:18.467  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:57:18.467  3805  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:57:18.467  3805  3857 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-13 12:57:18.467  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 12:57:18.467  3805  3857 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 12:57:18.467  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 12:57:18.473  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 12:57:18.474  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 12:57:18.474  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 12:57:18.475  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 12:57:18.475  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 12:57:18.475  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 12:57:18.475  3805  3857 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 12:57:18.476  3805  3857 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 12:57:18.476  3805  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 431)
09-13 12:57:18.476  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.476  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.477  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.477  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 12:57:18.477  3805  3879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:18.477  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.477  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:18.478  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.478  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.478  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:18.478  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:18.480  3805  3857 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 12:57:18.480  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.480  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.480  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.481  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
,09-13 12:57:18.481  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:18.481  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.481  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.481  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.481  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.482  3805  3857 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-13 12:57:18.482  3805  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 431
09-13 12:57:18.482  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.482  3805  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 431)
09-13 12:57:18.482  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.482  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.483  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.483  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:18.483  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
,09-13 12:57:18.483  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.483  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.483  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.483  3805  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 431)
09-13 12:57:18.485  2658  2777 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
09-13 12:57:18.485  3805  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 431)
09-13 12:57:18.488  3805  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 12:57:18.488  3805  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 12:57:18.488  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 12:57:18.488  3805  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 12:57:18.488  3805  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 12:57:18.488  3805  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 12:57:18.489  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 12:57:18.489  3805  3857 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 12:57:18.489  3805  3857 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 12:57:18.489  3805  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-13 12:57:18.489  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 12:57:18.489  3805  3857 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 12:57:18.489  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:18.489  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.489  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.489  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:18.489  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:18.490  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:18.490  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:18.490  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:18.490  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:18.490  3805  3857 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 12:57:18.492  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:18.496  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:18.498  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:18.499  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 12:57:18.499  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 12:57:18.499  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,09-13 12:57:18.501  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:18.501  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:18.501  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 12:57:18.501  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 12:57:18.501  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:18.503  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 12:57:18.504  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:18.504  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 12:57:18.504  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 12:57:18.504  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 12:57:18.504  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:57:18.504  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 12:57:18.505  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:18.505  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:57:18.507  3805  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:18.508  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 12:57:18.508  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 12:57:18.509  3805  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 12:57:18.512  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:18.512  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-13 12:57:18.512  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:18.514  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 12:57:18.515  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:18.515  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
,09-13 12:57:18.515  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:18.515  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:18.515  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 12:57:18.516  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:18.518  2658  2670 D BtGatt.GattService: registerClient() - UUID=75713a3f-3602-4ecd-b006-15a5ea9a29e8
,09-13 12:57:18.518  2658  2679 D BtGatt.GattService: onClientRegistered() - UUID=75713a3f-3602-4ecd-b006-15a5ea9a29e8, clientIf=5
,09-13 12:57:18.519  3805  3849 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 12:57:18.520  2658  2692 D BtGatt.AdvertiseManager: message : 0
,09-13 12:57:18.522  2658  2692 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 12:57:18.534  2658  2679 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:18.541  2658  2679 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 12:57:18.541  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 12:57:18.541  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:18.543  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:18.544  3805  3857 I io.jxcore.node.ConnectionHelper: start: OK
09-13 12:57:18.545  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:57:18.545  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 12:57:18.545  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 12:57:18.545  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 12:57:18.545  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 12:57:18.545  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 12:57:18.548  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 12:57:18.548  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:19.049  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:19.049  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:19.049  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 12:57:19.050  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 12:57:19.050  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:19.051  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
,09-13 12:57:19.051  3805  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:57:19.051  3805  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:57:19.051  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:57:19.051  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:19.051  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:19.052  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.051  3805  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:19.052  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:57:19.052  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:19.053  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:57:19.053  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:19.053  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 12:57:19.056  3805  3857 D BluetoothAdapter: STATE_ON
09-13 12:57:19.056  3805  3857 D BluetoothLeScanner: could not find callback wrapper
09-13 12:57:19.056  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:19.057  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 12:57:19.059  2658  2692 D BtGatt.AdvertiseManager: message : 1
09-13 12:57:19.060  2658  2692 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:19.084  2658  2679 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 12:57:19.084  2658  2679 D BtGatt.GattService: Client app is not null!
09-13 12:57:19.087  2658  2782 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 12:57:19.089  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 12:57:19.089  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 12:57:19.090  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 12:57:19.093  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 12:57:19.094  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 12:57:19.097  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:19.098  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 12:57:19.098  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:57:19.100  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:19.105  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
,09-13 12:57:19.105  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:19.105  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:19.105  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:19.105  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:19.105  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:19.113  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:19.114  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:19.114  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.115  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:19.115  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.115  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
,09-13 12:57:19.115  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:19.116  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.116  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.120  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:57:19.120  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:19.121  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:57:19.122  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 12:57:19.122  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 12:57:19.122  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 12:57:19.122  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 12:57:19.122  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 12:57:19.122  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:19.122  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 12:57:19.122  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 12:57:19.123  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:19.123  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:19.123  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.123  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:57:19.123  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.123  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.123  3805  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:57:19.124  3805  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:19.125  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:19.125  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
,09-13 12:57:19.125  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:19.125  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:19.125  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.125  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:19.125  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.125  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:19.125  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:19.127  3805  3857 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 12:57:19.127  3805  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 12:57:19.127  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 12:57:19.129  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:19.129  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:19.129  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 12:57:19.130  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:19.130  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:19.130  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.130  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:19.130  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.130  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:19.130  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:19.130  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.130  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:19.138  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:19.138  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.138  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.139  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
,09-13 12:57:19.139  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.139  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
09-13 12:57:19.139  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:19.140  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.140  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:19.142  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:19.142  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:19.143  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:19.143  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f9d86a not in the list
09-13 12:57:19.143  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:19.144  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14da15b not in the list
,09-13 12:57:19.144  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:19.144  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:19.144  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:19.147  3805  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-13 12:57:19.147  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 12:57:19.148  3805  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-13 12:57:19.148  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 12:57:19.148  3805  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 12:57:19.149  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 12:57:19.152  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 12:57:19.152  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 12:57:19.153  3805  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 12:57:19.153  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 12:57:19.153  3805  3857 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 12:57:19.153  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 12:57:19.153  3805  3857 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 12:57:19.153  3805  3857 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 12:57:19.154  3805  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 12:57:19.154  3805  3857 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 12:57:19.154  3805  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 12:57:19.155  3805  3857 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 12:57:19.155  3805  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 12:57:19.155  3805  3857 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 12:57:19.156  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:57:19.156  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ac7528 added. We now have 4 listener(s)
,09-13 12:57:19.157  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 12:57:19.158  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:57:19.158  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:57:19.158  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:57:19.158  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8104241 added. We now have 4 listener(s)
09-13 12:57:19.158  3805  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:57:19.159  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:57:19.161  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:19.165  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:19.167  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:19.167  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:57:19.168  3805  3857 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 12:57:19.169   873   883 D WifiService: setWifiEnabled: true pid=3805, uid=10000
,09-13 12:57:19.169   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:19.169  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:19.171  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:19.175   873  1923 D WifiService: setWifiEnabled: false pid=3805, uid=10000
,09-13 12:57:19.175   873  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:19.195  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 12:57:19.200   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 12:57:19.200   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 12:57:19.200   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 12:57:19.201   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:19.212   873  2108 D DhcpClient: Clearing IP address
,09-13 12:57:19.213   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 12:57:19.217   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:19.219  1495  2537 V NativeCrypto: Read error: ssl=0x9a5c5600: I/O error during system call, Connection timed out
,09-13 12:57:19.222  1495  2537 V NativeCrypto: SSL shutdown failed: ssl=0x9a5c5600: I/O error during system call, Broken pipe
,09-13 12:57:19.227   873  2113 D DhcpClient: Receive thread stopped
,09-13 12:57:19.228   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 12:57:19.229   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 12:57:19.232   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 12:57:19.234   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 12:57:19.237   420   420 E Parcel  : Reading a NULL string not supported here.
,09-13 12:57:19.237   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-13 12:57:19.242   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 12:57:19.246  2016  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:57:19.248   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.249  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:19.252  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.257  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:19.259  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:19.262   873   886 I ActivityManager: Start proc 3887:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 12:57:19.263   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:19.268  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.273  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.276  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:19.295   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:19.308  3887  3887 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 12:57:19.320   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-13 12:57:19.321   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-13 12:57:19.321   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:19.323   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-13 12:57:19.328  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.329  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.332  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.335  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.336  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:19.371  3887  3887 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 12:57:19.385   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 12:57:19.385   873  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 12:57:19.388  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 12:57:19.390  1711  1711 D SystemUpdateService: onCreate
,09-13 12:57:19.401  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 12:57:19.413  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 12:57:19.414  1711  3919 I SystemUpdateService: active receiver: enabled
,09-13 12:57:19.415  1711  2515 I iu.UploadsManager: num queued entries: 0
,09-13 12:57:19.416  1711  2515 I iu.UploadsManager: num updated entries: 0
,09-13 12:57:19.416  1711  2515 I iu.SyncManager: NEXT; no task
,09-13 12:57:19.420  1711  3919 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 12:57:19.422  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-13 12:57:19.422  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 12:57:19.425  1711  3919 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 12:57:19.425  1711  3919 I SystemUpdateService: now status is 0 (complete)
09-13 12:57:19.425  1711  3919 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 12:57:19.425  1711  3919 I SystemUpdateService: file has been verified
09-13 12:57:19.425  1711  3919 I SystemUpdateService: OTA package size = 12249756
,09-13 12:57:19.432  1711  3919 I SystemUpdateService: showing system update notification
,09-13 12:57:19.437   873   884 I ActivityManager: Start proc 3921:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 12:57:19.451  1711  1711 D SystemUpdateService: onDestroy
,09-13 12:57:19.459   873  1923 I ActivityManager: Killing 3247:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-13 12:57:19.480  3921  3921 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 12:57:19.482  3921  3921 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:19.488  3921  3921 D SprintDMHelper: simOperator: 
,09-13 12:57:19.488  3921  3921 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 12:57:19.508   873  1923 I ActivityManager: Start proc 3934:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 12:57:19.509   873  1923 I ActivityManager: Killing 3582:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 12:57:19.626  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 12:57:19.655   873  1923 I ActivityManager: Start proc 3949:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 12:57:19.657   873  1923 I ActivityManager: Killing 3460:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 12:57:19.680  3805  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:19.683   873  1958 D WifiService: setWifiEnabled: true pid=3805, uid=10000
,09-13 12:57:19.684   873  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:19.690   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.696  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.697  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.701  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.702  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:19.703   873  1302 D WifiConfigStore: loaded 0 passpoint configs
,09-13 12:57:19.704   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 12:57:19.705   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.705  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:19.705   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 12:57:19.706   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 12:57:19.706   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 12:57:19.706   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 12:57:19.707  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:19.709  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:19.713   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 12:57:19.713  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:19.713   372   872 D CommandListener: Setting iface cfg
09-13 12:57:19.714   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=18.75 rxSuccessRate=30.00 delta 1000 -> 994
09-13 12:57:19.714   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-13 12:57:19.714   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 12:57:19.716   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 12:57:19.720   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 12:57:19.720   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:19.721   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 12:57:19.737   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 12:57:19.768   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 12:57:19.771  3949  3949 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 12:57:19.833  3949  3949 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 12:57:19.833  3949  3949 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 12:57:19.833  3949  3949 I GAv4    :   adb logcat -s GAv4
,09-13 12:57:19.848  3949  3949 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:57:19.856  3949  3949 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:57:19.882  3949  3968 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:57:19.993  3949  3949 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 12:57:20.037  3949  3949 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 12:57:20.047  3949  3949 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7537-7540)
,09-13 12:57:20.047  3949  3949 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 12:57:20.058  3949  3949 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aab67d4}
,09-13 12:57:20.058  3949  3949 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 12:57:20.058  3949  3949 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:57:20.067  3949  3949 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 12:57:20.068  3949  3949 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 12:57:20.085  3949  3949 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 12:57:20.101  3949  3949 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 12:57:20.101  3949  3949 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 12:57:20.101  3949  3949 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 12:57:20.101  3949  3949 I Adreno  : Build Date                       : 10/20/15
09-13 12:57:20.101  3949  3949 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 12:57:20.101  3949  3949 I Adreno  : Local Branch                     : M14
09-13 12:57:20.101  3949  3949 I Adreno  : Remote Branch                    : 
09-13 12:57:20.101  3949  3949 I Adreno  : Remote Branch                    : 
09-13 12:57:20.101  3949  3949 I Adreno  : Reconstruct Branch               : 
,09-13 12:57:20.163  3949  3949 I NSApplication: Starting up...
,09-13 12:57:20.168  3949  3997 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 12:57:20.188  3805  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.195   873  2137 I ActivityManager: Start proc 4002:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 12:57:20.198   873  2137 I ActivityManager: Killing 3507:android.process.acore/u0a5 (adj 15): empty #17
,09-13 12:57:20.242  2658  2674 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 12:57:20.243  2658  2674 D BluetoothAdapterProperties: Setting state to 13,
,09-13 12:57:20.243  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 12:57:20.244  2658  2674 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 12:57:20.246  2658  2674 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:20.247  2658  2679 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:57:20.248  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 12:57:20.250  2658  2658 D BluetoothMapService: onReceive
09-13 12:57:20.250  2658  2658 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:57:20.250  2658  2658 D BluetoothMapService: STATE_TURNING_OFF
09-13 12:57:20.250  2658  2658 D BluetoothMapService: MAP Service closeService in
,09-13 12:57:20.250  2658  2658 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 12:57:20.250  2658  2658 D ObexServerSockets0: shutdown(block = true)
,09-13 12:57:20.251  2658  2658 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 12:57:20.251  2658  2658 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 12:57:20.251  2658  2801 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 12:57:20.252  2658  2777 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!,
09-13 12:57:20.252  2658  2802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 12:57:20.256  2658  2658 I BtOppRfcommListener: stopping Accept Thread
,09-13 12:57:20.256  2658  3443 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:57:20.256  2658  3443 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 12:57:20.261  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:20.261  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:20.263  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.263  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:20.264  2658  2658 D HeadsetService: Received stop request...Stopping profile...
,09-13 12:57:20.265  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:20.265  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:20.266  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.266   873   873 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:20.266  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:20.266   873   873 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:20.266  1942  2277 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:20.268  1355  2325 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:20.268  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:20.268  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:20.269  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.269  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:20.270  2658  2658 V BluetoothAdapterState: isTurningOff()=true
,09-13 12:57:20.270  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.270  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.270  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 12:57:20.271  2658  2658 D A2dpService: Received stop request...Stopping profile...
09-13 12:57:20.272  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:20.272  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:20.273  2658  2658 D HidService: Received stop request...Stopping profile...
09-13 12:57:20.273  2658  2658 D HidService: Stopping Bluetooth HidService
,09-13 12:57:20.273  2658  2784 D A2dpStateMachine: Exit Disconnected: -1
09-13 12:57:20.274   873   873 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:20.274   873   873 D BluetoothA2dp: Proxy object disconnected
,09-13 12:57:20.274  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:20.275  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:20.276  1355  1355 D HeadsetProfile: Bluetooth service disconnected
09-13 12:57:20.276  1355  1355 D BluetoothA2dp: Proxy object disconnected
,09-13 12:57:20.276  1355  1355 D BluetoothInputDevice: Proxy object disconnected
09-13 12:57:20.276  1355  1355 D HidProfile: Bluetooth service disconnected
09-13 12:57:20.277  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.278  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.279  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.280  2658  2658 D HealthService: Received stop request...Stopping profile...
,09-13 12:57:20.280  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.281  2658  2658 V BluetoothAdapterState: isTurningOff()=true
,09-13 12:57:20.281  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.281  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.281  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 12:57:20.282  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 12:57:20.282  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 12:57:20.282  2658  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 12:57:20.282  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 12:57:20.282  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 12:57:20.282  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:20.283  2658  2679 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 12:57:20.283  2658  2658 D PanService: Received stop request...Stopping profile...
09-13 12:57:20.284  2658  2658 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 12:57:20.284  2658  2658 D BluetoothMapService: stop()
09-13 12:57:20.284  2658  2658 D BluetoothMapAppObserver: deinitObservers()
09-13 12:57:20.285  2658  2658 D BluetoothMapAppObserver: removeReceiver()
09-13 12:57:20.286  2658  2658 V BluetoothAdapterState: isTurningOff()=true
,09-13 12:57:20.286  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.286  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.286  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:20.287  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:20.287  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:20.287  2658  2758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:57:20.287  2658  2758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:57:20.288  2658  2758 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:57:20.288  2658  2758 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:57:20.288  2658  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 12:57:20.288  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 12:57:20.289  2658  2679 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 12:57:20.289  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 12:57:20.289  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:20.289  2658  2658 V BluetoothAdapterState: isTurningOn()=false
,09-13 12:57:20.289  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.289  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:20.289  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 12:57:20.290  2658  2679 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-13 12:57:20.290  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:57:20.290  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:20.290  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.290  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.290  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:20.291  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 12:57:20.291  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 12:57:20.292  2658  2658 D BluetoothMapService: MAP Service closeService in
09-13 12:57:20.292  2658  2658 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:20.292  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.292  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:20.293  2658  2658 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:20.293  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 12:57:20.293  2658  2674 D BluetoothAdapterProperties: Setting state to 15
09-13 12:57:20.293  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 12:57:20.294  2658  2674 I BluetoothAdapterState: Entering BleOnState
09-13 12:57:20.294  1355  2078 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 12:57:20.294  2658  2658 D BluetoothMapService: cleanup()
09-13 12:57:20.294  2658  2658 D BluetoothMapService: MAP Service closeService in
09-13 12:57:20.295  1355  1377 D BluetoothPan: onBluetoothStateChange on: false
,09-13 12:57:20.295   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:20.295   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:20.295  1355  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-13 12:57:20.296  1942  2264 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:20.296   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:57:20.296   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 12:57:20.296  1355  2325 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 12:57:20.297  1355  2078 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:57:20.298  1355  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:20.298  2658  2674 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 12:57:20.298  2658  2674 D BluetoothAdapterProperties: Setting state to 16
09-13 12:57:20.298  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 12:57:20.299  2658  2674 D BluetoothAdapterProperties: onBleDisable
09-13 12:57:20.299  2658  2675 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 12:57:20.300  2658  2679 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:57:20.299  2658  2674 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:20.301  2658  2758 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 12:57:20.301  2658  2758 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:20.301  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.305  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.306  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.307  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.308  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.309  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.310  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.311  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:20.326  4002  4002 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 12:57:20.507  2658  2679 I bt_hci  : shut_down
,09-13 12:57:20.510   873  1958 I ActivityManager: Killing 3689:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 12:57:20.556  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 12:57:20.585  2658  2694 D bt_hwcfg: hw_epilog_process
,09-13 12:57:20.585  2658  2694 I bt_vendor: low_power_mode_cb,
,09-13 12:57:20.592  2658  2694 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 12:57:20.592  2658  2694 I bt_vendor: epilog_cb
09-13 12:57:20.593  2658  2694 I bt_hci  : epilog_finished_callback
,09-13 12:57:20.614   873  1380 I ActivityManager: Start proc 4021:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 12:57:20.621  2658  2679 I bt_hci_h4: hal_close
,09-13 12:57:20.622  2658  2679 I bt_userial_vendor: device fd = 51 close
,09-13 12:57:20.668  4021  4021 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 12:57:20.680  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 12:57:20.687   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9c850ce:true
,09-13 12:57:20.688  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:20.729   873  1389 I ActivityManager: Start proc 4033:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 12:57:20.736  2658  2675 D bt_stack_manager: event_shut_down_stack finished.
,09-13 12:57:20.738  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 12:57:20.739  4021  4021 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 12:57:20.740  2658  2674 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 12:57:20.740  2658  2658 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:57:20.741  2658  2658 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 12:57:20.741  2658  2658 D BtGatt.GattService: stop()
,09-13 12:57:20.741  2658  2658 D BtGatt.AdvertiseManager: advertise clients cleared
09-13 12:57:20.741  3805  4006 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:20.742  2658  2658 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:20.742  2658  2658 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:20.742  2658  2658 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:20.742  2658  2658 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 12:57:20.742  2658  2674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 12:57:20.743  2658  2674 D BluetoothAdapterProperties: Setting state to 10
,09-13 12:57:20.744  2658  2674 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 12:57:20.744  2658  2674 I BluetoothAdapterState: Entering OffState
09-13 12:57:20.745   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-13 12:57:20.751  2658  2658 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 12:57:20.751  2658  2658 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 12:57:20.751  2658  2658 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 12:57:20.751  2658  2675 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 12:57:20.753  2658  2675 D bt_stack_manager: event_clean_up_stack finished.
09-13 12:57:20.753  2658  2658 I art     : System.exit called, status: 0
09-13 12:57:20.754  2658  2658 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 12:57:20.766  4021  4021 D BluetoothMap: Create BluetoothMap proxy object
,09-13 12:57:20.774  4021  4021 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 12:57:20.781  4033  4033 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 12:57:20.787   873  1922 I ActivityManager: Process com.android.bluetooth (pid 2658) has died
,09-13 12:57:20.788   873  1922 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 12:57:20.790  4021  4021 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:57:20.794   873  1913 I ActivityManager: Killing 3704:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 12:57:20.987  4033  4033 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 12:57:20.987  4033  4033 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.987  4033  4033 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.987  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.988  4033  4033 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.988  4033  4033 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.988  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.989  4033  4033 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.989  4033  4033 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.989  4033  4033 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:20.989  4033  4033 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:20.995  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 12:57:20.998  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 12:57:21.023  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 12:57:21.023  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 12:57:21.037   873  2137 I ActivityManager: Start proc 4066:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-13 12:57:21.039  4021  4021 D DockEventReceiver: finishStartingService: stopping service
09-13 12:57:21.042   873  1963 I ActivityManager: Killing 2198:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 12:57:21.094   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:21.116   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 12:57:21.116   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:57:21.116   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 12:57:21.135   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:21.142   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:21.143   873  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 12:57:21.159   873  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-13 12:57:21.160   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 12:57:21.161   873  4081 D DhcpClient: Receive thread started
,09-13 12:57:21.182  4066  4066 D AdapterServiceConfig: Adding HeadsetService
,09-13 12:57:21.182  4066  4066 D AdapterServiceConfig: Adding A2dpService
09-13 12:57:21.182  4066  4066 D AdapterServiceConfig: Adding HidService
09-13 12:57:21.182  4066  4066 D AdapterServiceConfig: Adding HealthService,
09-13 12:57:21.182  4066  4066 D AdapterServiceConfig: Adding PanService
09-13 12:57:21.183  4066  4066 D AdapterServiceConfig: Adding GattService
,09-13 12:57:21.183  4066  4066 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 12:57:21.186  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:57:21.196   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f8f57c7:true
09-13 12:57:21.196  4066  4066 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 12:57:21.198  4066  4066 I bt_bluedroid: init
,09-13 12:57:21.198  4066  4083 I BluetoothAdapterState: Entering OffState
,09-13 12:57:21.200  4066  4084 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-13 12:57:21.200  4066  4084 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 12:57:21.200  4066  4084 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 12:57:21.200  4066  4084 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 12:57:21.201  4066  4066 I bt_bluedroid: get_profile_interface socket
,09-13 12:57:21.202  4066  4066 I bt_bluedroid: get_profile_interface sdp
09-13 12:57:21.203  4066  4087 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-13 12:57:21.204  4066  4087 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 12:57:21.204  4066  4076 I bt_bluedroid: config_hci_snoop_log
,09-13 12:57:21.205   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-13 12:57:21.209  4066  4083 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 12:57:21.209  4066  4083 D BluetoothAdapterProperties: Setting state to 14
09-13 12:57:21.209  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 12:57:21.210  4066  4083 D BluetoothBondStateMachine: make
,09-13 12:57:21.212  4066  4088 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 12:57:21.214  4066  4083 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:21.214  4066  4066 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 12:57:21.216  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:21.217  4066  4066 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 12:57:21.217  4066  4066 D BtGatt.GattService: Received start request. Starting profile...
09-13 12:57:21.217  4066  4066 D BtGatt.GattService: start()
09-13 12:57:21.217  4066  4066 I bt_bluedroid: get_profile_interface gatt
,09-13 12:57:21.218  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:21.218  4066  4066 D BtGatt.AdvertiseManager: advertise manager created
,09-13 12:57:21.222  4066  4066 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:21.222  4066  4066 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:21.222  4066  4066 V BluetoothAdapterState: isBleTurningOn()=true
09-13 12:57:21.222  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:21.222  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 12:57:21.222  4066  4083 I bt_bluedroid: enable
,09-13 12:57:21.222  4066  4084 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 12:57:21.223  4066  4084 I bt_hci  : start_up
,09-13 12:57:21.228  4066  4084 I bt_vendor: alloc value 0xb39f0189
,09-13 12:57:21.228  4066  4084 I bt_vendor: init
09-13 12:57:21.228  4066  4084 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 12:57:21.228  4066  4084 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 12:57:21.242   873  1302 E native  : do suspend false
,09-13 12:57:21.248  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 12:57:21.251   873  2108 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 12:57:21.265   873  4081 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172675, domain null
,09-13 12:57:21.266   873  2108 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172675 seconds
,09-13 12:57:21.267   873  2108 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 12:57:21.291   873  4081 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 12:57:21.292   873  2108 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 12:57:21.295  4033  4054 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 12:57:21.295   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:21.298   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 12:57:21.302   873  2108 D DhcpClient: Scheduling renewal in 86399s
,09-13 12:57:21.309   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 12:57:21.310   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 12:57:21.310   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@98f82d5:true
09-13 12:57:21.310   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 12:57:21.311   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 12:57:21.312   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 12:57:21.318   873  1304 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 12:57:21.333  4066  4084 D bt_hci  : start_up starting async portion
,09-13 12:57:21.333  4066  4092 I bt_hci  : event_finish_startup
09-13 12:57:21.333  4066  4092 I bt_hci_h4: hal_open
09-13 12:57:21.333  4066  4092 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-13 12:57:21.338  4066  4092 I bt_userial_vendor: device fd = 51 open
,09-13 12:57:21.362   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 12:57:21.362   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 12:57:21.363   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-13 12:57:21.364   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 12:57:21.365   873  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 12:57:21.378  4066  4092 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 12:57:21.381   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 12:57:21.385   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 12:57:21.385   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 12:57:21.385   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 12:57:21.386   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 12:57:21.386   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-13 12:57:21.386   873  1304 D ConnectivityService:    accepting network in place of null
09-13 12:57:21.388   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 12:57:21.408  4066  4092 D bt_hwcfg: Chipset BCM4354A2
,09-13 12:57:21.408  4066  4092 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 12:57:21.409  4066  4092 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 12:57:21.416   873  4080 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148909, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:57:21.451   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:21.484   873  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 12:57:21.492   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:21.496   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 12:57:21.496   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 12:57:21.500   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-13 12:57:21.499   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 12:57:21.520  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:21.520  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:21.521  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:21.521  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:21.525  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:21.525  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:21.526  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:21.526  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:21.530  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:21.530  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:21.533  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-13 12:57:21.534  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 12:57:21.534  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:21.534  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:21.538  1711  1711 D SystemUpdateService: onCreate
,09-13 12:57:21.538  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:21.538  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:21.539  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:21.539  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:21.547  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 12:57:21.550  1711  4109 I SystemUpdateService: active receiver: enabled
,09-13 12:57:21.558  1711  4109 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 12:57:21.560  1711  4109 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 12:57:21.560  1711  4109 I SystemUpdateService: now status is 0 (complete)
09-13 12:57:21.560  1711  4109 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 12:57:21.560  1711  4109 I SystemUpdateService: file has been verified
09-13 12:57:21.560  1711  4109 I SystemUpdateService: OTA package size = 12249756
,09-13 12:57:21.562   873  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 10:57:21 GMT], X-Android-Received-Millis=[1473764241561], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473764241537]}
,09-13 12:57:21.562   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-13 12:57:21.563   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 12:57:21.563   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 12:57:21.564   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 12:57:21.565  1711  4109 I SystemUpdateService: showing system update notification
,09-13 12:57:21.570  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 12:57:21.572  1711  2515 I iu.UploadsManager: num queued entries: 0
,09-13 12:57:21.574  1711  2515 I iu.UploadsManager: num updated entries: 0
,09-13 12:57:21.577  1711  2515 I iu.SyncManager: NEXT; no task
,09-13 12:57:21.579  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 12:57:21.581  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 12:57:21.583  1711  4115 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 12:57:21.583  1711  4115 W BaseAppContext: Using Auth Proxy for data requests.
09-13 12:57:21.585  1711  4115 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
09-13 12:57:21.587  1711  1711 D SystemUpdateService: onDestroy
,09-13 12:57:21.591  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:21.592  3921  3921 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-13 12:57:21.593  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:21.610  3921  3921 D SprintDMHelper: simOperator: 
,09-13 12:57:21.610  3921  3921 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 12:57:21.631  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 12:57:21.631  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 12:57:21.631  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:21.631  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:21.651  1711  4115 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-13 12:57:21.677  3039  4110 V KeepSync: Connecting to GoogleApiClient
,09-13 12:57:21.678   873  1380 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 12:57:21.684  1495  2383 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:57:21.684  1495  2383 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 12:57:21.684  1495  2383 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:21.684  1495  2383 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:21.697  3562  4114 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 12:57:21.697  3562  4114 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at blb.a(PG:3937)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at czp.a(PG:18188)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:57:21.697  3562  4114 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	... 12 more
09-13 12:57:21.697  3562  4114 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at fal.a(PG:38)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:57:21.697  3562  4114 E HttpOperation: 	... 14 more
,09-13 12:57:21.732  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 12:57:21.732  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 12:57:21.732  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:21.732  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:21.746  2286  4120 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 12:57:21.747  1495  2060 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 12:57:21.747  1495  2060 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 12:57:21.747  1495  2060 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:57:21.747  1495  2060 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:21.753  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 12:57:21.755  3562  4114 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 12:57:21.755  3562  4114 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jdm.a(PG:82)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jcs.o(PG:406)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jcn.a(PG:1379)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jcs.i(PG:143)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at hec.a(PG:42)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at hee.a(PG:102)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at czr.a(PG:65)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at kka.a(PG:108)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at czp.a(PG:19176)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at czp.a(PG:9081)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at czq.run(PG:1686)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:57:21.755  3562  4114 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jdj.a(PG:4091)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jdj.a(PG:1125)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jdm.a(PG:77)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	... 15 more
09-13 12:57:21.755  3562  4114 E HttpOperation: Caused by: faj: BadAuthentication
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at fal.a(PG:38)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	at jdj.a(PG:4089)
09-13 12:57:21.755  3562  4114 E HttpOperation: 	... 17 more
09-13 12:57:21.755  3562  4114 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 12:57:21.755  3562  4114 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at hec.a(PG:42)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at hee.a(PG:102)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at czr.a(PG:65)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at kka.a(PG:108)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	... 15 more
09-13 12:57:21.755  3562  4114 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at fal.a(PG:38)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 12:57:21.755  3562  4114 E ExperimentLoader: 	... 17 more
,09-13 12:57:21.765  1711  4126 V BaseAuthAsyncOperation: access token request failed
,09-13 12:57:21.766  3039  4110 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 12:57:21.831  1495  2383 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 12:57:21.831  1495  2383 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 12:57:21.831  1495  2383 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:21.831  1495  2383 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:21.841   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131552, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:57:21.850  3039  4110 E KeepSync: IOException
09-13 12:57:21.850  3039  4110 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 12:57:21.850  3039  4110 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 12:57:21.850  3039  4110 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 12:57:21.850  3039  4110 E KeepSync: 	... 10 more
09-13 12:57:21.850  3039  4110 W KeepSync: Sync result 2
,09-13 12:57:21.862   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 131460, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 12:57:21.892  4066  4092 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-13 12:57:21.892  4066  4092 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 12:57:21.892  4066  4092 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 12:57:22.009  4066  4092 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-13 12:57:22.011  4066  4092 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 12:57:22.042  4066  4092 I bt_hwcfg: vendor lib fwcfg completed
,09-13 12:57:22.043  4066  4092 I bt_vendor: firmware callback
09-13 12:57:22.043  4066  4092 I bt_hci  : firmware_config_callback
,09-13 12:57:22.056  4066  4129 I bt_btu  : btu_task pending for preload complete event
,09-13 12:57:22.056  4066  4129 I bt_btu_task: Bluetooth chip preload is complete
,09-13 12:57:22.056  4066  4129 I bt_btu  : btu_task received preload complete event
,09-13 12:57:22.066  4066  4129 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 12:57:22.066  4066  4129 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 12:57:22.067  4066  4129 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 12:57:22.067  4066  4129 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 12:57:22.067  4066  4129 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 12:57:22.068  4066  4129 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 12:57:22.068  4066  4129 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 12:57:22.068  4066  4129 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 12:57:22.068  4066  4129 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 12:57:22.069  4066  4129 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 12:57:22.069  4066  4129 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 12:57:22.069  4066  4129 I         : BTE_InitTraceLevels -- TRC_GATT
,09-13 12:57:22.069  4066  4129 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 12:57:22.070  4066  4129 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 12:57:22.070  4066  4129 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 12:57:22.205  4066  4129 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396dd9d
,09-13 12:57:22.206  4066  4129 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396dd9d 
,09-13 12:57:22.219  4066  4087 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 12:57:22.227  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 12:57:22.228  4066  4087 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 12:57:22.230  4066  4087 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 12:57:22.238  4066  4087 D BluetoothAdapterProperties: Scan Mode:20
09-13 12:57:22.239  4066  4087 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 12:57:22.239  4066  4087 D bt_hci  : do_postload posting postload work item
09-13 12:57:22.240  4066  4092 I bt_hci  : event_postload
,09-13 12:57:22.240  4066  4092 I bt_vendor: sco_config_cb
,09-13 12:57:22.240  4066  4092 I bt_hci  : sco_config_callback postload finished.
,09-13 12:57:22.245  4066  4087 D bt_bte_conf: Device ID record 1 : primary
,09-13 12:57:22.245  4066  4087 D bt_bte_conf:   vendorId            = 000f
,09-13 12:57:22.245  4066  4087 D bt_bte_conf:   vendorIdSource      = 0001
09-13 12:57:22.245  4066  4087 D bt_bte_conf:   product             = 1200
,09-13 12:57:22.246  4066  4087 D bt_bte_conf:   version             = 1436
,09-13 12:57:22.246  4066  4092 I bt_vendor: low_power_mode_cb
,09-13 12:57:22.246  4066  4087 D bt_bte_conf:   clientExecutableURL = 
09-13 12:57:22.246  4066  4087 D bt_bte_conf:   serviceDescription  = 
09-13 12:57:22.247  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.246  4066  4087 D bt_bte_conf:   documentationURL    = 
09-13 12:57:22.248  4066  4087 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-13 12:57:22.248  4066  4084 D bt_stack_manager: event_start_up_stack finished
09-13 12:57:22.253  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 12:57:22.254  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.254  4066  4083 D BluetoothAdapterProperties: Setting state to 15
09-13 12:57:22.255  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-13 12:57:22.258  4066  4083 I BluetoothAdapterState: Entering BleOnState
09-13 12:57:22.259  3805  4044 E BluetoothAdapter: BT is in BLE_ON State
09-13 12:57:22.262  4066  4083 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 12:57:22.262  4066  4083 D BluetoothAdapterProperties: Setting state to 11
,09-13 12:57:22.262  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 12:57:22.263  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.266  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.272  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:22.272  4066  4066 D HeadsetService: Received start request. Starting profile...
,09-13 12:57:22.275  4066  4066 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 12:57:22.276  4066  4066 D HeadsetStateMachine: make
,09-13 12:57:22.280  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.283  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.285  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.287  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.289  4066  4066 D HeadsetStateMachine: max_hf_connections = 1
09-13 12:57:22.289  4066  4066 I bt_bluedroid: get_profile_interface handsfree
,09-13 12:57:22.289  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 12:57:22.289  4066  4087 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 12:57:22.293  4066  4083 I BluetoothAdapterState: Entering PendingCommandState
09-13 12:57:22.298  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:22.299  4066  4066 D A2dpService: Received start request. Starting profile...
,09-13 12:57:22.299  4066  4066 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 12:57:22.299  4066  4066 I bt_bluedroid: get_profile_interface avrcp
,09-13 12:57:22.304  4066  4066 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 12:57:22.304  4066  4066 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-13 12:57:22.304  4066  4066 D A2dpStateMachine: make
,09-13 12:57:22.306  4066  4066 I bt_bluedroid: get_profile_interface a2dp
09-13 12:57:22.306  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 12:57:22.307  4066  4136 D A2dpStateMachine: Enter Disconnected: -2
09-13 12:57:22.308  4066  4066 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 12:57:22.309  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:22.309  4066  4066 D HidService: Received start request. Starting profile...
09-13 12:57:22.310  4066  4066 I bt_bluedroid: get_profile_interface hidhost
09-13 12:57:22.310  4066  4087 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394f3e5
09-13 12:57:22.310  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 12:57:22.310  4066  4066 D HidService: setHidService(): set to: null
09-13 12:57:22.310  4066  4066 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 12:57:22.311  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:22.312  4066  4066 D HealthService: Received start request. Starting profile...
,09-13 12:57:22.313  4066  4066 I bt_bluedroid: get_profile_interface health
,09-13 12:57:22.315  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:22.315  4066  4066 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-13 12:57:22.316  4021  4021 D BluetoothInputDevice: Proxy object connected
09-13 12:57:22.316  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:22.317  4066  4066 D PanService: Received start request. Starting profile...
09-13 12:57:22.317  4066  4066 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 12:57:22.318  4066  4066 I bt_bluedroid: get_profile_interface pan
,09-13 12:57:22.318  4066  4087 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 12:57:22.320  4066  4134 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 12:57:22.320  4066  4066 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:22.320  4066  4066 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:22.320  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.320  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.320  4021  4021 D HidProfile: Bluetooth service connected
,09-13 12:57:22.321  4021  4021 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:57:22.323  4021  4021 D PanProfile: Bluetooth service connected
09-13 12:57:22.323  4066  4066 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:22.326  4066  4066 D BluetoothMapService: Received start request. Starting profile...
09-13 12:57:22.326  4066  4066 D BluetoothMapService: start()
09-13 12:57:22.328  4066  4066 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 12:57:22.329  4066  4066 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 12:57:22.329  4066  4066 D BluetoothMapAppObserver: createReceiver()
09-13 12:57:22.329  4021  4021 D BluetoothMap: Proxy object connected
,09-13 12:57:22.330  4021  4021 D MapProfile: Bluetooth service connected
09-13 12:57:22.330  4021  4021 D BluetoothMap: getConnectedDevices()
,09-13 12:57:22.330  4066  4066 D BluetoothMapAppObserver: initObservers()
09-13 12:57:22.330  4066  4066 D BluetoothMapAppObserver: getEnabledAccountItems()
09-13 12:57:22.331  4021  4021 D BluetoothMap: Bluetooth is Not enabled
09-13 12:57:22.335  4066  4066 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:22.335  4066  4066 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:22.335  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.335  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isTurningOn()=true
,09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.336  4066  4066 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.337  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 12:57:22.337  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 12:57:22.337  4066  4083 D BluetoothAdapterProperties: ScanMode =  20
09-13 12:57:22.337  4066  4083 D BluetoothAdapterProperties: State =  11
09-13 12:57:22.338  4066  4087 D BluetoothAdapterProperties: Scan Mode:21
09-13 12:57:22.339  4066  4087 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 12:57:22.340  4066  4083 D BluetoothAdapterProperties: Setting state to 12
,09-13 12:57:22.340  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 12:57:22.341  4021  4031 D BluetoothPan: onBluetoothStateChange on: true
09-13 12:57:22.341  4066  4083 I BluetoothAdapterState: Entering OnState
09-13 12:57:22.341  1355  2325 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 12:57:22.343  3805  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 12:57:22.345  3805  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 12:57:22.345  1355  1355 D BluetoothInputDevice: Proxy object connected
09-13 12:57:22.345  1355  1355 D HidProfile: Bluetooth service connected
09-13 12:57:22.346  1355  1381 D BluetoothPan: onBluetoothStateChange on: true
,09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.350  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:22.350  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 12:57:22.350  1355  1355 D PanProfile: Bluetooth service connected
,09-13 12:57:22.352  4021  4032 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 12:57:22.352  4021  4031 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 12:57:22.353  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:22.354   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:57:22.354   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:22.355  1355  2078 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 12:57:22.355  4066  4066 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 12:57:22.356  4066  4066 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 12:57:22.357  1355  1355 D BluetoothMap: Proxy object connected
09-13 12:57:22.357  1355  1355 D MapProfile: Bluetooth service connected
09-13 12:57:22.357  1355  1355 D BluetoothMap: getConnectedDevices()
,09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.358  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:22.358  4066  4066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:22.359  4021  4032 D BluetoothMap: onBluetoothStateChange: up=true
09-13 12:57:22.359  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.362  4066  4066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:22.362  1942  1957 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:22.363   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.363  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:22.363  4066  4066 D ObexServerSockets: Succeed to create listening sockets 
,09-13 12:57:22.363  4066  4066 D ObexServerSockets0: startAccept()
,09-13 12:57:22.363  4066  4066 D ObexServerSockets0: prepareForNewConnect()
09-13 12:57:22.364   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:22.364  1355  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 12:57:22.365  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.365  4066  4143 D ObexServerSockets0: Accepting socket connection...
,09-13 12:57:22.366  4066  4066 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 12:57:22.366  4066  4066 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 12:57:22.367  4066  4144 D ObexServerSockets0: Accepting socket connection...
,09-13 12:57:22.367   873   873 D BluetoothA2dp: Proxy object connected
,09-13 12:57:22.367  1355  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:57:22.370  1355  1355 D BluetoothA2dp: Proxy object connected
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.370  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:22.370  1355  2078 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:57:22.372  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:22.372   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 12:57:22.373  4066  4066 D BluetoothMapService: onReceive
,09-13 12:57:22.373  4066  4066 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-13 12:57:22.374  4066  4066 D BluetoothMapService: STATE_ON
09-13 12:57:22.374  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.375  4021  4021 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 12:57:22.376  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.378  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.380  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.380  4021  4021 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 12:57:22.387  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 12:57:22.389  4021  4021 D BluetoothA2dp: Proxy object connected
,09-13 12:57:22.394  4066  4066 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 12:57:22.394  4066  4066 D ObexServerSockets0: prepareForNewConnect(),
,09-13 12:57:22.398  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:22.406  4021  4021 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:57:22.407  4021  4021 D BluetoothPbap: Proxy object connected
09-13 12:57:22.408  4021  4021 D PbapServerProfile: Bluetooth service connected
,09-13 12:57:22.410  1355  1355 D BluetoothPbap: Proxy object connected
,09-13 12:57:22.410  1355  1355 D PbapServerProfile: Bluetooth service connected
,09-13 12:57:22.427  4066  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:22.447  4066  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:22.449  4066  4152 I BtOppRfcommListener: Accept thread started.
,09-13 12:57:22.457   873   873 D BluetoothHeadset: Proxy object connected
,09-13 12:57:22.457   873   873 D BluetoothHeadset: Proxy object connected
09-13 12:57:22.457  1942  1954 D BluetoothHeadset: Proxy object connected
09-13 12:57:22.457  1355  2325 D BluetoothHeadset: Proxy object connected,
09-13 12:57:22.457  1355  1355 D HeadsetProfile: Bluetooth service connected
09-13 12:57:22.458   873   873 D BluetoothHeadset: Proxy object connected
,09-13 12:57:22.463  1942  2115 D BluetoothHeadset: Proxy object connected
,09-13 12:57:22.463   873   890 D BluetoothHeadset: Proxy object connected
,09-13 12:57:22.470  1355  2078 D BluetoothHeadset: Proxy object connected
09-13 12:57:22.471  1355  1355 D HeadsetProfile: Bluetooth service connected
,09-13 12:57:22.484  4021  4031 D BluetoothHeadset: Proxy object connected
,09-13 12:57:22.485  4021  4021 D HeadsetProfile: Bluetooth service connected
,09-13 12:57:22.495   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 12:57:22.687   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 12:57:22.699  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 12:57:22.709   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 12:57:22.709   873   893 I Adreno  : Build Date                       : 10/20/15
09-13 12:57:22.709   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 12:57:22.709   873   893 I Adreno  : Local Branch                     : M14
09-13 12:57:22.709   873   893 I Adreno  : Remote Branch                    : 
09-13 12:57:22.709   873   893 I Adreno  : Remote Branch                    : 
09-13 12:57:22.709   873   893 I Adreno  : Reconstruct Branch               : 
,09-13 12:57:22.743   281   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (196 us)
,09-13 12:57:22.769  3805  4044 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.774  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:22.775  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:22.789  4066  4083 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 12:57:22.789  4066  4083 D BluetoothAdapterProperties: Setting state to 13
,09-13 12:57:22.789  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 12:57:22.791  4066  4083 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 12:57:22.792  4066  4083 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:22.795  4066  4087 D BluetoothAdapterProperties: Scan Mode:20
,09-13 12:57:22.795  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 12:57:22.799  4066  4066 D HeadsetService: Received stop request...Stopping profile...
,09-13 12:57:22.801  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.801  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:22.802  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:22.802  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:22.802   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 12:57:22.802   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 12:57:22.803  4021  4032 D BluetoothHeadset: Proxy object disconnected
,09-13 12:57:22.804  4021  4021 D HeadsetProfile: Bluetooth service disconnected
,09-13 12:57:22.806  1942  2264 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:22.807  1355  1377 D BluetoothHeadset: Proxy object disconnected
09-13 12:57:22.808  1355  1355 D HeadsetProfile: Bluetooth service disconnected
09-13 12:57:22.809   873   873 D BluetoothHeadset: Proxy object disconnected
,09-13 12:57:22.811  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:22.811  4066  4066 D A2dpService: Received stop request...Stopping profile...
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.811  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:22.812  4066  4136 D A2dpStateMachine: Exit Disconnected: -1
09-13 12:57:22.813  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:22.813  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:22.817  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:22.817  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:22.817  1355  1355 D BluetoothA2dp: Proxy object disconnected
,09-13 12:57:22.818   873   873 D BluetoothA2dp: Proxy object disconnected
09-13 12:57:22.819  3805  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:22.819  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:22.819  4066  4066 V BluetoothAdapterState: isTurningOff()=true
,09-13 12:57:22.819  4066  4066 V BluetoothAdapterState: isTurningOn()=false
,09-13 12:57:22.820  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.820  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.824  4066  4066 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 12:57:22.824  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 12:57:22.824  4066  4066 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 12:57:22.824  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:22.824  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:22.824  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 12:57:22.825  4066  4087 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-13 12:57:22.825  4066  4066 D HidService: Received stop request...Stopping profile...
09-13 12:57:22.825  4066  4066 D HidService: Stopping Bluetooth HidService
09-13 12:57:22.826  1355  1355 D BluetoothInputDevice: Proxy object disconnected
,09-13 12:57:22.826  1355  1355 D HidProfile: Bluetooth service disconnected
09-13 12:57:22.827  4066  4066 D HealthService: Received stop request...Stopping profile...
09-13 12:57:22.828  4066  4066 D PanService: Received stop request...Stopping profile...
,09-13 12:57:22.829  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 12:57:22.829  1355  1355 D PanProfile: Bluetooth service disconnected
09-13 12:57:22.829  4066  4066 D BluetoothMapService: Received stop request...Stopping profile...
09-13 12:57:22.830  4066  4066 D BluetoothMapService: stop()
,09-13 12:57:22.830  4021  4021 D BluetoothA2dp: Proxy object disconnected
09-13 12:57:22.830  4066  4066 D BluetoothMapAppObserver: deinitObservers()
09-13 12:57:22.830  4066  4066 D BluetoothMapAppObserver: removeReceiver()
,09-13 12:57:22.831  1355  1355 D BluetoothMap: Proxy object disconnected
,09-13 12:57:22.832  1355  1355 D MapProfile: Bluetooth service disconnected
09-13 12:57:22.832  4066  4066 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:22.832  4066  4066 V BluetoothAdapterState: isTurningOn()=false
,09-13 12:57:22.832  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.832  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 12:57:22.833  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 12:57:22.833  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 12:57:22.833  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 12:57:22.834  4066  4129 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:57:22.834  4066  4129 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:57:22.834  4066  4129 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 12:57:22.834  4066  4066 V BluetoothAdapterState: isTurningOff()=true
,09-13 12:57:22.834  4066  4129 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 12:57:22.834  4066  4066 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:22.834  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.834  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.834  4066  4066 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 12:57:22.834  4066  4087 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 12:57:22.835  4066  4066 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 12:57:22.835  4066  4066 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:22.835  4066  4066 V BluetoothAdapterState: isTurningOn()=false
,09-13 12:57:22.835  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.835  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.835  4066  4066 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 12:57:22.835  4066  4087 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 12:57:22.836  4066  4066 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 12:57:22.836  4066  4066 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:22.836  4066  4066 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:22.836  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.836  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.837  4066  4066 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 12:57:22.837  4066  4066 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 12:57:22.838  4066  4066 D BluetoothMapService: MAP Service closeService in
09-13 12:57:22.838  4066  4066 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 12:57:22.838  4066  4066 D ObexServerSockets0: shutdown(block = true)
09-13 12:57:22.838  4066  4143 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 12:57:22.839  4066  4066 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 12:57:22.839  4021  4021 D BluetoothInputDevice: Proxy object disconnected
09-13 12:57:22.839  4021  4021 D HidProfile: Bluetooth service disconnected
09-13 12:57:22.839  4066  4144 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 12:57:22.841  4066  4131 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!,
09-13 12:57:22.841  4066  4066 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 12:57:22.841  4066  4066 V BluetoothAdapterState: isTurningOff()=true
09-13 12:57:22.841  4066  4066 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:22.841  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
09-13 12:57:22.841  4066  4066 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:22.842  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-13 12:57:22.842  4066  4083 D BluetoothAdapterProperties: Setting state to 15
09-13 12:57:22.842  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 12:57:22.846  4066  4083 I BluetoothAdapterState: Entering BleOnState
,09-13 12:57:22.844  4066  4066 D BluetoothMapService: cleanup()
09-13 12:57:22.847  4066  4066 D BluetoothMapService: MAP Service closeService in
09-13 12:57:22.847  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.849  4066  4066 I BtOppRfcommListener: stopping Accept Thread
09-13 12:57:22.850  4066  4152 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 12:57:22.850  4021  4032 D BluetoothPan: onBluetoothStateChange on: false
09-13 12:57:22.850  4066  4152 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 12:57:22.850  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.851  1355  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 12:57:22.852  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.854  1355  2325 D BluetoothPan: onBluetoothStateChange on: false
09-13 12:57:22.855  4021  4031 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 12:57:22.846  4021  4021 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 12:57:22.855  4021  4021 D PanProfile: Bluetooth service disconnected
,09-13 12:57:22.856  4021  4032 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 12:57:22.857   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:22.857   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 12:57:22.857  1355  2078 D BluetoothMap: onBluetoothStateChange: up=false
09-13 12:57:22.859  4021  4032 D BluetoothMap: onBluetoothStateChange: up=false
09-13 12:57:22.859  4021  4031 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:57:22.857  4021  4021 D BluetoothMap: Proxy object disconnected
09-13 12:57:22.861  4021  4021 D MapProfile: Bluetooth service disconnected
09-13 12:57:22.861  1942  1957 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:22.863   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:57:22.863  4021  4032 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:22.863   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 12:57:22.863  1355  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 12:57:22.865  1355  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 12:57:22.865  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 12:57:22.866  1355  2325 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 12:57:22.866  4066  4083 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 12:57:22.866  4066  4083 D BluetoothAdapterProperties: Setting state to 16
09-13 12:57:22.866  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 12:57:22.867  4066  4083 D BluetoothAdapterProperties: onBleDisable
09-13 12:57:22.867  4066  4083 I BluetoothAdapterState: Entering PendingCommandState
09-13 12:57:22.868  4066  4084 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 12:57:22.869  4066  4129 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 12:57:22.869  4066  4129 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 12:57:22.874  4066  4087 D BluetoothAdapterProperties: Scan Mode:20
,09-13 12:57:22.876  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.878  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 12:57:22.879  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.882  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:22.887  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.890  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.892  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:22.921  4021  4021 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:57:22.922  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 12:57:22.926  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:22.927  4021  4021 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:57:23.071  4066  4087 I bt_hci  : shut_down
,09-13 12:57:23.071  4066  4092 I bt_vendor: low_power_mode_cb
09-13 12:57:23.072  4066  4092 D bt_hwcfg: hw_epilog_process
,09-13 12:57:23.099  4066  4092 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 12:57:23.099  4066  4092 I bt_vendor: epilog_cb
09-13 12:57:23.099  4066  4092 I bt_hci  : epilog_finished_callback
09-13 12:57:23.101  4066  4087 I bt_hci_h4: hal_close
,09-13 12:57:23.103  4066  4087 I bt_userial_vendor: device fd = 51 close
,09-13 12:57:23.231  4066  4084 D bt_stack_manager: event_shut_down_stack finished.
,09-13 12:57:23.234  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 12:57:23.239  4066  4083 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 12:57:23.240  4066  4066 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 12:57:23.242  4066  4066 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 12:57:23.242  4066  4066 D BtGatt.GattService: stop()
,09-13 12:57:23.242  4066  4066 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 12:57:23.247  4066  4066 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:23.247  4066  4066 V BluetoothAdapterState: isTurningOn()=false
,09-13 12:57:23.247  4066  4066 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:23.248  4066  4066 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 12:57:23.249  4066  4083 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 12:57:23.249  4066  4083 D BluetoothAdapterProperties: Setting state to 10
,09-13 12:57:23.250  4066  4083 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10,
,09-13 12:57:23.253  4066  4083 I BluetoothAdapterState: Entering OffState
09-13 12:57:23.253   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 12:57:23.280  4066  4066 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 12:57:23.280  4066  4066 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 12:57:23.280  4066  4084 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 12:57:23.285  4066  4084 D bt_stack_manager: event_clean_up_stack finished.
,09-13 12:57:23.285  4066  4066 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 12:57:23.289  4066  4066 I art     : System.exit called, status: 0
,09-13 12:57:23.289  4066  4066 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 12:57:23.291  3805  4153 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:23.292  3805  4153 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:23.292  3805  4153 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 12:57:23.292  3805  4153 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:23.300  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:23.307   279   279 E lowmemorykiller: Error writing /proc/4066/oom_score_adj; errno=22
,09-13 12:57:23.388  3805  3805 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 12:57:23.388  3805  3805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 12:57:23.421   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 12:57:23.422   873  1389 I ActivityManager: Process com.android.bluetooth (pid 4066) has died
,09-13 12:57:23.423   873  1389 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 12:57:23.426   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 12:57:23.430   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 12:57:23.432   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,09-13 12:57:23.432   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 12:57:23.432  3805  3805 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@582ca76 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9845d27, 16908290=android.view.AbsSavedState$1@9845d27}, android:focusedViewId=100}]}]
09-13 12:57:23.432  3805  3805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 12:57:23.433  3805  3805 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 12:57:23.433  3805  3805 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 12:57:23.671   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 12:57:23.675   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 12:57:23.676   873  1328 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,09-13 12:57:23.680   873   893 I DreamManagerService: Entering dreamland.
09-13 12:57:23.682   873   893 I PowerManagerService: Dozing...
,09-13 12:57:23.683   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 12:57:23.744   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 12:57:23.745   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 12:57:23.758   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:23.763   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 12:57:23.765   873  1302 E native  : do suspend false
,09-13 12:57:23.773   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 12:57:23.778  1929  4161 D NfcService: Discovery configuration equal, not updating.
,09-13 12:57:23.793   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:23.798   873  1302 E native  : do suspend true
,09-13 12:57:23.872   376  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 12:57:23.873   376  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 12:57:24.459   873   886 I ActivityManager: Start proc 4166:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 12:57:24.597  4166  4166 D AdapterServiceConfig: Adding HeadsetService
,09-13 12:57:24.597  4166  4166 D AdapterServiceConfig: Adding A2dpService
09-13 12:57:24.598  4166  4166 D AdapterServiceConfig: Adding HidService
,09-13 12:57:24.598  4166  4166 D AdapterServiceConfig: Adding HealthService
09-13 12:57:24.599  4166  4166 D AdapterServiceConfig: Adding PanService
,09-13 12:57:24.599  4166  4166 D AdapterServiceConfig: Adding GattService
09-13 12:57:24.600  4166  4166 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 12:57:24.625   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91a813c:true
,09-13 12:57:24.626  4166  4166 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 12:57:24.636  4166  4166 I bt_bluedroid: init
,09-13 12:57:24.636  4166  4178 I BluetoothAdapterState: Entering OffState
,09-13 12:57:24.643  4166  4179 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 12:57:24.644  4166  4179 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 12:57:24.644  4166  4179 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 12:57:24.644  4166  4179 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 12:57:24.646  4166  4166 I bt_bluedroid: get_profile_interface socket
,09-13 12:57:24.652  4166  4166 I bt_bluedroid: get_profile_interface sdp
,09-13 12:57:24.653  4166  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 12:57:24.659  4166  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 12:57:24.660  4166  4177 I bt_bluedroid: config_hci_snoop_log
,09-13 12:57:24.661   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 12:57:24.669  4166  4178 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 12:57:24.670  4166  4178 D BluetoothAdapterProperties: Setting state to 14
,09-13 12:57:24.670  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 12:57:24.674  4166  4178 D BluetoothBondStateMachine: make
,09-13 12:57:24.678  4166  4183 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 12:57:24.686  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:24.687  4166  4166 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 12:57:24.692  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:24.694  4166  4166 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 12:57:24.695  4166  4166 D BtGatt.GattService: Received start request. Starting profile...
,09-13 12:57:24.695  4166  4166 D BtGatt.GattService: start()
,09-13 12:57:24.695  4166  4166 I bt_bluedroid: get_profile_interface gatt
,09-13 12:57:24.697  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:24.697  4166  4166 D BtGatt.AdvertiseManager: advertise manager created
,09-13 12:57:24.707  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:24.707  4166  4166 V BluetoothAdapterState: isTurningOn()=false
09-13 12:57:24.707  4166  4166 V BluetoothAdapterState: isBleTurningOn()=true
09-13 12:57:24.708  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:24.708  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 12:57:24.708  4166  4178 I bt_bluedroid: enable
09-13 12:57:24.708  4166  4179 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 12:57:24.709  4166  4179 I bt_hci  : start_up
,09-13 12:57:24.718  4166  4179 I bt_vendor: alloc value 0xb39f0189
,09-13 12:57:24.718  4166  4179 I bt_vendor: init
09-13 12:57:24.718  4166  4179 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 12:57:24.718  4166  4179 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 12:57:24.814  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 12:57:24.824  4166  4179 D bt_hci  : start_up starting async portion
,09-13 12:57:24.828  4166  4186 I bt_hci  : event_finish_startup
09-13 12:57:24.828  4166  4186 I bt_hci_h4: hal_open
,09-13 12:57:24.828  4166  4186 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 12:57:24.835  4166  4186 I bt_userial_vendor: device fd = 51 open
,09-13 12:57:24.838  3949  3949 I art     : Waiting for a blocking GC DisableMovingGc
,09-13 12:57:24.843  3949  3949 I art     : Starting a blocking GC DisableMovingGc
,09-13 12:57:24.866  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 12:57:24.898  4166  4186 D bt_hwcfg: Chipset BCM4354A2
,09-13 12:57:24.899  4166  4186 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 12:57:24.899  4166  4186 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 12:57:25.322  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 12:57:25.528  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 12:57:25.530  4166  4186 D bt_hwcfg: Settlement delay -- 100 ms
09-13 12:57:25.530  4166  4186 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 12:57:25.647  4166  4186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 12:57:25.649  4166  4186 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 12:57:25.678  4166  4186 I bt_hwcfg: vendor lib fwcfg completed
,09-13 12:57:25.678  4166  4186 I bt_vendor: firmware callback
09-13 12:57:25.678  4166  4186 I bt_hci  : firmware_config_callback
,09-13 12:57:25.691  4166  4188 I bt_btu  : btu_task pending for preload complete event
,09-13 12:57:25.691  4166  4188 I bt_btu_task: Bluetooth chip preload is complete
09-13 12:57:25.692  4166  4188 I bt_btu  : btu_task received preload complete event
,09-13 12:57:25.701  4166  4188 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 12:57:25.702  4166  4188 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 12:57:25.702  4166  4188 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 12:57:25.702  4166  4188 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 12:57:25.703  4166  4188 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 12:57:25.703  4166  4188 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 12:57:25.703  4166  4188 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 12:57:25.703  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 12:57:25.704  4166  4188 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 12:57:25.704  4166  4188 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 12:57:25.704  4166  4188 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 12:57:25.704  4166  4188 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 12:57:25.705  4166  4188 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 12:57:25.705  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 12:57:25.705  4166  4188 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 12:57:25.829  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 12:57:25.838  4166  4188 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396dd9d
,09-13 12:57:25.839  4166  4188 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396dd9d 
,09-13 12:57:25.846  4166  4182 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 12:57:25.849  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 12:57:25.850  4166  4182 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 12:57:25.852  4166  4182 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 12:57:25.855  4166  4182 D BluetoothAdapterProperties: Scan Mode:20
,09-13 12:57:25.855  4166  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 12:57:25.856  4166  4182 D bt_hci  : do_postload posting postload work item
09-13 12:57:25.856  4166  4186 I bt_hci  : event_postload
,09-13 12:57:25.857  4166  4186 I bt_vendor: sco_config_cb
09-13 12:57:25.857  4166  4186 I bt_hci  : sco_config_callback postload finished.
09-13 12:57:25.858  4166  4182 D bt_bte_conf: Device ID record 1 : primary
09-13 12:57:25.859  4166  4182 D bt_bte_conf:   vendorId            = 000f
,09-13 12:57:25.859  4166  4182 D bt_bte_conf:   vendorIdSource      = 0001
09-13 12:57:25.859  4166  4182 D bt_bte_conf:   product             = 1200
09-13 12:57:25.859  4166  4182 D bt_bte_conf:   version             = 1436
09-13 12:57:25.860  4166  4182 D bt_bte_conf:   clientExecutableURL = 
09-13 12:57:25.860  4166  4182 D bt_bte_conf:   serviceDescription  = ,
09-13 12:57:25.860  4166  4182 D bt_bte_conf:   documentationURL    = 
09-13 12:57:25.860  4166  4182 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 12:57:25.861  4166  4179 D bt_stack_manager: event_start_up_stack finished
,09-13 12:57:25.862  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 12:57:25.863  4166  4178 D BluetoothAdapterProperties: Setting state to 15
09-13 12:57:25.863  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 12:57:25.864  4166  4186 I bt_vendor: low_power_mode_cb
09-13 12:57:25.865  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:25.867  4166  4178 I BluetoothAdapterState: Entering BleOnState
09-13 12:57:25.869  4166  4178 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 12:57:25.870  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:25.870  4166  4178 D BluetoothAdapterProperties: Setting state to 11
09-13 12:57:25.870  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 12:57:25.878  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:25.883  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:25.885  4166  4166 D HeadsetService: Received start request. Starting profile...
09-13 12:57:25.885  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:25.887  4166  4166 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 12:57:25.888  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:25.890  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:25.890  4166  4166 D HeadsetStateMachine: make
09-13 12:57:25.894  4166  4178 I BluetoothAdapterState: Entering PendingCommandState
,09-13 12:57:25.898  4166  4166 D HeadsetStateMachine: max_hf_connections = 1
09-13 12:57:25.898  4166  4166 I bt_bluedroid: get_profile_interface handsfree
,09-13 12:57:25.898  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 12:57:25.899  4166  4182 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 12:57:25.906  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:25.907  4166  4166 D A2dpService: Received start request. Starting profile...
,09-13 12:57:25.907  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:25.908  4166  4166 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 12:57:25.909  4166  4166 I bt_bluedroid: get_profile_interface avrcp
,09-13 12:57:25.914  4166  4166 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 12:57:25.914  4166  4166 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 12:57:25.915  4166  4166 D A2dpStateMachine: make
,09-13 12:57:25.916  4166  4166 I bt_bluedroid: get_profile_interface a2dp
,09-13 12:57:25.916  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 12:57:25.920  4166  4197 D A2dpStateMachine: Enter Disconnected: -2
,09-13 12:57:25.921  4166  4166 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 12:57:25.922  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:25.922  4166  4166 D HidService: Received start request. Starting profile...
09-13 12:57:25.922  4166  4166 I bt_bluedroid: get_profile_interface hidhost
,09-13 12:57:25.923  4166  4182 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394f3e5
09-13 12:57:25.923  4166  4182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 12:57:25.923  4166  4166 D HidService: setHidService(): set to: null
,09-13 12:57:25.924  4166  4166 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 12:57:25.924  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
09-13 12:57:25.925  4166  4166 D HealthService: Received start request. Starting profile...
,09-13 12:57:25.926  4166  4166 I bt_bluedroid: get_profile_interface health
,09-13 12:57:25.927  4166  4166 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 12:57:25.927  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:25.928  4166  4166 D PanService: Received start request. Starting profile...
,09-13 12:57:25.928  4166  4166 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 12:57:25.928  4166  4166 I bt_bluedroid: get_profile_interface pan
09-13 12:57:25.929  4166  4182 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 12:57:25.932  4166  4166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:25.932  4166  4166 D BluetoothMapService: Received start request. Starting profile...
,09-13 12:57:25.932  4166  4166 D BluetoothMapService: start()
,09-13 12:57:25.936  4166  4166 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 12:57:25.937  4166  4166 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 12:57:25.937  4166  4166 D BluetoothMapAppObserver: createReceiver()
,09-13 12:57:25.938  4166  4166 D BluetoothMapAppObserver: initObservers()
,09-13 12:57:25.939  4166  4166 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 12:57:25.951  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:25.951  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,09-13 12:57:25.951  4166  4195 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 12:57:25.951  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.951  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 12:57:25.954  4166  4166 V BluetoothAdapterState: isTurningOff()=false
,09-13 12:57:25.954  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,09-13 12:57:25.954  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.954  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:25.955  4166  4166 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:25.955  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,09-13 12:57:25.955  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.955  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:25.956  4166  4166 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:25.956  4166  4166 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:25.956  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.956  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isTurningOn()=true
09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isTurningOff()=false
09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isTurningOn()=true
,09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 12:57:25.957  4166  4166 V BluetoothAdapterState: isBleTurningOff()=false
09-13 12:57:25.959  4166  4178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 12:57:25.959  4166  4178 D BluetoothAdapterProperties: ScanMode =  20
09-13 12:57:25.959  4166  4178 D BluetoothAdapterProperties: State =  11
,09-13 12:57:25.965  4166  4182 D BluetoothAdapterProperties: Scan Mode:21
,09-13 12:57:25.965  4166  4182 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 12:57:25.965  4166  4178 D BluetoothAdapterProperties: Setting state to 12
,09-13 12:57:25.965  4166  4178 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 12:57:25.966  4166  4178 I BluetoothAdapterState: Entering OnState
09-13 12:57:25.966  4021  4032 D BluetoothPan: onBluetoothStateChange on: true
,09-13 12:57:25.968  1355  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 12:57:25.970  4166  4166 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 12:57:25.970  4166  4166 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:25.971  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:25.972  1355  2078 D BluetoothPan: onBluetoothStateChange on: true
,09-13 12:57:25.975  4166  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:25.975  4021  4031 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 12:57:25.977  4021  4032 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 12:57:25.977  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:25.978   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:57:25.979   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:25.979  1355  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-13 12:57:25.979  4166  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:25.980  4021  4031 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 12:57:25.981  4166  4166 D ObexServerSockets: Succeed to create listening sockets 
,09-13 12:57:25.981  4166  4166 D ObexServerSockets0: startAccept()
,09-13 12:57:25.981  4166  4166 D ObexServerSockets0: prepareForNewConnect()
,09-13 12:57:25.981  4021  4032 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:25.982  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 12:57:25.983  4166  4166 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 12:57:25.983  4166  4166 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 12:57:25.984  1942  1954 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:25.986   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 12:57:25.985  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:57:25.986  1355  1355 D PanProfile: Bluetooth service connected
09-13 12:57:25.986  1355  1355 D BluetoothInputDevice: Proxy object connected
09-13 12:57:25.986  1355  1355 D HidProfile: Bluetooth service connected
,09-13 12:57:25.985  4166  4204 D ObexServerSockets0: Accepting socket connection...
,09-13 12:57:25.987  4021  4032 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:25.987   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 12:57:25.987   873   873 D BluetoothA2dp: Proxy object connected
09-13 12:57:25.987  1355  2325 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 12:57:25.989  1355  2078 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 12:57:25.989  1355  1355 D BluetoothMap: Proxy object connected
09-13 12:57:25.989  1355  1355 D MapProfile: Bluetooth service connected
09-13 12:57:25.989  1355  1355 D BluetoothMap: getConnectedDevices()
09-13 12:57:25.989  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:25.991  1355  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 12:57:25.991  1355  1355 D BluetoothA2dp: Proxy object connected
09-13 12:57:25.985  4021  4021 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 12:57:25.985  4166  4205 D ObexServerSockets0: Accepting socket connection...
09-13 12:57:25.991  4021  4021 D PanProfile: Bluetooth service connected
09-13 12:57:25.992  4021  4021 D BluetoothInputDevice: Proxy object connected
09-13 12:57:25.992  4021  4021 D HidProfile: Bluetooth service connected
09-13 12:57:25.994  4166  4166 D BluetoothMapService: onReceive
,09-13 12:57:25.995  4166  4166 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 12:57:25.995   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 12:57:25.995  4166  4166 D BluetoothMapService: STATE_ON
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:25.996  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:25.999  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:25.999  4021  4021 D BluetoothMap: Proxy object connected
09-13 12:57:25.999  4021  4021 D MapProfile: Bluetooth service connected
09-13 12:57:25.999  4021  4021 D BluetoothMap: getConnectedDevices()
09-13 12:57:26.002  4021  4021 D BluetoothA2dp: Proxy object connected
,09-13 12:57:26.002  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:26.006  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:26.008  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:26.009  4021  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 12:57:26.016  4166  4166 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 12:57:26.016  4166  4166 D ObexServerSockets0: prepareForNewConnect()
09-13 12:57:26.019  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 12:57:26.024  4021  4021 D DockEventReceiver: finishStartingService: stopping service
,09-13 12:57:26.030  4021  4021 D BluetoothPbap: Proxy object connected
,09-13 12:57:26.030  4021  4021 D PbapServerProfile: Bluetooth service connected
09-13 12:57:26.031  1355  1355 D BluetoothPbap: Proxy object connected
09-13 12:57:26.031  1355  1355 D PbapServerProfile: Bluetooth service connected
,09-13 12:57:26.034  4166  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:26.056  4166  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 12:57:26.059  4166  4214 I BtOppRfcommListener: Accept thread started.
,09-13 12:57:26.080   873   873 D BluetoothHeadset: Proxy object connected
09-13 12:57:26.080   873   873 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.080  4021  4032 D BluetoothHeadset: Proxy object connected
09-13 12:57:26.081  4021  4021 D HeadsetProfile: Bluetooth service connected,
09-13 12:57:26.081  1942  2115 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.082  1355  1381 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.083  1355  1355 D HeadsetProfile: Bluetooth service connected
09-13 12:57:26.083   873   873 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.085  1942  2277 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.087  4021  4031 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.088  4021  4021 D HeadsetProfile: Bluetooth service connected
09-13 12:57:26.088   873   890 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.091  1355  2325 D BluetoothHeadset: Proxy object connected
,09-13 12:57:26.091  1355  1355 D HeadsetProfile: Bluetooth service connected
,09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:26.338  3805  4158 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:26.343  3805  4158 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:26.350  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:26.351   873   883 D WifiService: setWifiEnabled: false pid=3805, uid=10000
09-13 12:57:26.351   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:26.357   873  1963 D WifiService: setWifiEnabled: false pid=3805, uid=10000
,09-13 12:57:26.358   873  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:26.374  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 12:57:26.379   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 12:57:26.379   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 12:57:26.380   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 12:57:26.380   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:26.395   873  1302 E native  : do suspend true
,09-13 12:57:26.402   873  2108 D DhcpClient: Clearing IP address
,09-13 12:57:26.403   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 12:57:26.406   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:26.413  1495  4125 V NativeCrypto: Read error: ssl=0x9a5c5600: I/O error during system call, Connection timed out
,09-13 12:57:26.415  1495  4125 V NativeCrypto: SSL shutdown failed: ssl=0x9a5c5600: I/O error during system call, Broken pipe
,09-13 12:57:26.418   873  3123 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-13 12:57:26.419   873  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-13 12:57:26.420   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 12:57:26.421   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-13 12:57:26.423   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 12:57:26.424   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 12:57:26.424   873  1302 E native  : do suspend true
,09-13 12:57:26.430   420   420 E Parcel  : Reading a NULL string not supported here.
,09-13 12:57:26.436   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 12:57:26.436   873  4078 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-13 12:57:26.437   873  4081 D DhcpClient: Receive thread stopped
,09-13 12:57:26.438   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 12:57:26.442   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 12:57:26.454   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.459  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.460  2016  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 12:57:26.462  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:26.462   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.466  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.468  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.472  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.473   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:26.474  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.496   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:26.498   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 12:57:26.499   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:26.503   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-13 12:57:26.506  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:26.508  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:26.509  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:26.519  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-13 12:57:26.523  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 12:57:26.527  1711  1711 D SystemUpdateService: onCreate
,09-13 12:57:26.529  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 12:57:26.533  1711  4226 I SystemUpdateService: active receiver: enabled
,09-13 12:57:26.539  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 12:57:26.543  1711  2515 I iu.UploadsManager: num queued entries: 0
,09-13 12:57:26.544  1711  2515 I iu.UploadsManager: num updated entries: 0
09-13 12:57:26.544  1711  2515 I iu.SyncManager: NEXT; no task
,09-13 12:57:26.545  1711  4226 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 12:57:26.548  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 12:57:26.549  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 12:57:26.551  3921  3921 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:26.555  3921  3921 D SprintDMHelper: simOperator: 
,09-13 12:57:26.555  3921  3921 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 12:57:26.560  1711  4226 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 12:57:26.560  1711  4226 I SystemUpdateService: now status is 0 (complete)
09-13 12:57:26.560  1711  4226 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 12:57:26.563  1711  4226 I SystemUpdateService: file has been verified
,09-13 12:57:26.564   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 12:57:26.565   873  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 12:57:26.565   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 12:57:26.567  1711  4226 I SystemUpdateService: OTA package size = 12249756
,09-13 12:57:26.568  2286  4229 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 12:57:26.583  1711  4226 I SystemUpdateService: showing system update notification
,09-13 12:57:26.591  1711  1711 D SystemUpdateService: onDestroy
,09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.867  3805  4215 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.872  3805  4215 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.880  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:26.881   873  1958 D WifiService: setWifiEnabled: true pid=3805, uid=10000
,09-13 12:57:26.881   873  1958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:26.890   873  2005 D WifiService: setWifiEnabled: true pid=3805, uid=10000
09-13 12:57:26.890   873  2005 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 12:57:26.893   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.910  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.913  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.916   873  1302 D WifiConfigStore: loaded 0 passpoint configs
09-13 12:57:26.917   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 12:57:26.918   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.918  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:26.918   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 12:57:26.919   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 12:57:26.919   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 12:57:26.919   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-13 12:57:26.920  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:26.924  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:26.927  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:26.933   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 12:57:26.933   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 12:57:26.934   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:26.935   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 12:57:26.935   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 12:57:26.942   873  1302 E native  : do suspend true
,09-13 12:57:26.942   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
09-13 12:57:26.943   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 12:57:26.951   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:27.404  3805  4231 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 12:57:27.412  3805  4231 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 12:57:27.421  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:27.423  3805  3857 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 12:57:27.424   873  1923 D WifiService: setWifiEnabled: true pid=3805, uid=10000
09-13 12:57:27.424   873  1923 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 12:57:27.440  3805  4235 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 12:57:27.440  3805  4235 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 12:57:27.959  3805  4235 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-13 12:57:27.959  3805  4237 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 12:57:27.961  3805  4237 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:57:27.962  3805  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:27.963  3805  4235 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 12:57:27.963  3805  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:27.963  3805  4235 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:57:27.964  3805  4237 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 12:57:27.967  3805  4235 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:27.970  3805  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: IncomingSocketThread/Sender)
,09-13 12:57:27.973  3805  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: IncomingSocketThread/Receiver)
,09-13 12:57:27.975  3805  4235 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 12:57:27.974  3805  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: OutgoingSocketThread/Sender)
09-13 12:57:27.975  3805  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 493, thread name: IncomingSocketThread/Receiver)
,09-13 12:57:27.975  3805  4241 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 12:57:27.976  3805  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 493, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 12:57:27.978  3805  4243 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: OutgoingSocketThread/Receiver)
,09-13 12:57:27.979  3805  4243 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 495, thread name: OutgoingSocketThread/Receiver)
09-13 12:57:27.979  3805  4243 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 12:57:27.980  3805  4243 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 495, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 12:57:28.126   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 12:57:28.215   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.56 rxSuccessRate=9.38 delta 1000 -> 994
,09-13 12:57:28.217   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 12:57:28.217   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:28.231   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 12:57:28.299   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 12:57:28.300  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 12:57:28.463  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 12:57:28.465  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 12:57:28.472  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@582ca76 Bundle[{}]
,09-13 12:57:28.474  3805  3857 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 12:57:28.474  3805  3857 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 12:57:28.475  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 12:57:28.475  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 12:57:28.476  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 12:57:28.476  3805  3857 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 12:57:28.485  3805  4245 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 12:57:28.485  3805  4245 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 12:57:28.495  3805  4247 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 12:57:28.496  3805  4247 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-13 12:57:28.496  3805  4247 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:28.496  3805  4245 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 12:57:28.496  3805  4245 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 12:57:28.497  3805  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:28.498  3805  4247 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:28.498  3805  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 12:57:28.499  3805  4247 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 12:57:28.500  3805  4245 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 12:57:28.501  3805  4249 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 506, name: IncomingSocketThread/Sender)
09-13 12:57:28.505  3805  4250 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 507, name: OutgoingSocketThread/Sender)
09-13 12:57:28.505  3805  4252 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 509, name: OutgoingSocketThread/Receiver)
09-13 12:57:28.506  3805  4252 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 509, thread name: OutgoingSocketThread/Receiver)
09-13 12:57:28.506  3805  4251 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 508, name: IncomingSocketThread/Receiver)
09-13 12:57:28.506  3805  4252 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 12:57:28.506  3805  4252 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 509, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 12:57:28.507  3805  4251 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 508, thread name: IncomingSocketThread/Receiver)
09-13 12:57:28.507  3805  4251 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 12:57:28.507  3805  4251 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 508, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 12:57:28.755  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 12:57:28.803  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 12:57:28.804  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 12:57:28.813   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 12:57:28.831   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 12:57:28.831   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 12:57:28.831   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 12:57:28.859   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 12:57:28.868  2016  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:57:28.880   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:28.883   873  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 12:57:28.896   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 12:57:28.916   873  4255 D DhcpClient: Receive thread started
,09-13 12:57:29.002   873  1302 E native  : do suspend false
,09-13 12:57:29.010  3805  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 518)
,09-13 12:57:29.012  3805  3857 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 12:57:29.013  3805  3857 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 519)
,09-13 12:57:29.018  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 12:57:29.018  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 added. We now have 5 listener(s)
,09-13 12:57:29.020  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 12:57:29.020  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 12:57:29.020  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 12:57:29.020  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 12:57:29.020  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d added. We now have 5 listener(s)
,09-13 12:57:29.021  3805  3857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:57:29.021  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:57:29.024   873  2108 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 12:57:29.027  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 12:57:29.033  3805  3857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 12:57:29.037  3805  3857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 12:57:29.037  3805  3857 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:57:29.040  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:57:29.042  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:29.042  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:29.042  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:57:29.042  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 12:57:29.042  3805  3857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 removed from the list
,09-13 12:57:29.042  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:29.042  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d removed from the list
09-13 12:57:29.044  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 12:57:29.045  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:29.045  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:29.046  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-13 12:57:29.046  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 12:57:29.049  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 12:57:29.050  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 12:57:29.050  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 12:57:29.050  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:29.054   873  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
09-13 12:57:29.054   873  2108 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
09-13 12:57:29.055  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:57:29.055   873  2108 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
09-13 12:57:29.056  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 12:57:29.057  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 12:57:29.059  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 12:57:29.059  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:57:29.060  3805  4256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:29.060  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 12:57:29.060  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:29.060  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 12:57:29.064  3805  4256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 12:57:29.065  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 12:57:29.065  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 12:57:29.070  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:29.071  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 12:57:29.073  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:29.075   873  4255 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 12:57:29.075   873  2108 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 12:57:29.077   372   872 D CommandListener: Setting iface cfg
,09-13 12:57:29.078  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 12:57:29.078  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:29.079  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-13 12:57:29.080  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:29.081   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 12:57:29.080  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 12:57:29.081  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 12:57:29.082   873  2108 D DhcpClient: Scheduling renewal in 86399s
09-13 12:57:29.082   873  1302 E native  : do suspend true
,09-13 12:57:29.083  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:29.090  4166  4176 D BtGatt.GattService: registerClient() - UUID=94aee5e0-ec32-449a-93f7-04fa1a460616
,09-13 12:57:29.091  4166  4182 D BtGatt.GattService: onClientRegistered() - UUID=94aee5e0-ec32-449a-93f7-04fa1a460616, clientIf=5
,09-13 12:57:29.092  3805  3816 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:29.097  4166  4184 D BtGatt.AdvertiseManager: message : 0
,09-13 12:57:29.098   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 12:57:29.099   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
09-13 12:57:29.099   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-13 12:57:29.099  4166  4184 D BtGatt.AdvertiseManager: starting multi advertising
09-13 12:57:29.104   873  1304 D ConnectivityService: Adding iface wlan0 to network 102
09-13 12:57:29.104   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 12:57:29.111  4166  4182 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:29.118  4166  4182 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 12:57:29.119  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 12:57:29.119  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:29.121  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:29.122  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:29.122  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 12:57:29.123  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 12:57:29.123  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 12:57:29.123  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 12:57:29.123  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 12:57:29.125  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 12:57:29.125  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:29.141   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 12:57:29.141   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 12:57:29.143   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 12:57:29.145   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-13 12:57:29.147   873  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 12:57:29.178   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 12:57:29.181   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-13 12:57:29.181   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 12:57:29.181   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 12:57:29.181   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 12:57:29.181   873  1304 D ConnectivityService:    accepting network in place of null
09-13 12:57:29.181   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 12:57:29.182   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 12:57:29.194   873  4254 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156687, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 12:57:29.200   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:29.219   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 12:57:29.222   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 12:57:29.222   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:29.224   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-13 12:57:29.227   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:29.232  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:29.235  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:29.241  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:29.244  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:29.246  2065  2065 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-13 12:57:29.248  1711  1711 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:57:29.250  3805  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:57:29.252  1711  1711 D SystemUpdateService: onCreate
,09-13 12:57:29.253  3805  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:57:29.255  1711  1711 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 12:57:29.267   873  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 12:57:29.275  1711  4266 I SystemUpdateService: active receiver: enabled
,09-13 12:57:29.279  1711  1711 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 12:57:29.281  1711  2515 I iu.UploadsManager: num queued entries: 0
,09-13 12:57:29.282  1711  2515 I iu.UploadsManager: num updated entries: 0
,09-13 12:57:29.287  1711  4266 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 12:57:29.290  1711  1711 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 12:57:29.292  1711  1711 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 12:57:29.295  3921  3921 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 12:57:29.299  1711  4269 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 12:57:29.299  1711  4269 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 12:57:29.302  1711  4269 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 12:57:29.303  3921  3921 D SprintDMHelper: simOperator: 
,09-13 12:57:29.303  3921  3921 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 12:57:29.311  1711  4266 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 12:57:29.311  1711  4266 I SystemUpdateService: now status is 0 (complete)
,09-13 12:57:29.311  1711  4266 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 12:57:29.311  1711  4266 I SystemUpdateService: file has been verified
09-13 12:57:29.311  1711  4266 I SystemUpdateService: OTA package size = 12249756
09-13 12:57:29.318  1711  2515 I iu.SyncManager: NEXT; no task
,09-13 12:57:29.322   873  4253 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 10:57:29 GMT], X-Android-Received-Millis=[1473764249321], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473764249300]}
,09-13 12:57:29.323   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-13 12:57:29.324   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-13 12:57:29.324   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 12:57:29.324  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:29.327   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 12:57:29.328  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:29.339  1711  4266 I SystemUpdateService: showing system update notification
,09-13 12:57:29.368  1711  1711 D SystemUpdateService: onDestroy
,09-13 12:57:29.377  1495  3007 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 12:57:29.378  1495  3007 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 12:57:29.378  1495  3007 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:57:29.378  1495  3007 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:29.386   873  1304 D ConnectivityService: handlePromptUnvalidated 101
,09-13 12:57:29.400  1711  4269 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-13 12:57:29.426  2286  4271 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 12:57:29.626  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:29.627  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 12:57:29.627  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:30.223   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 12:57:32.129  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 12:57:32.129  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 12:57:32.129  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 12:57:32.130  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 12:57:32.130  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:32.131  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:32.131  3805  4256 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:57:32.131  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 12:57:32.131  3805  4256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:57:32.132  3805  4256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:32.132  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 12:57:32.132  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 12:57:32.133  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:57:32.133  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 12:57:32.134  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 12:57:32.134  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 12:57:32.137  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:32.137  3805  3857 D BluetoothLeScanner: could not find callback wrapper
,09-13 12:57:32.137  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:32.138  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 12:57:32.140  4166  4184 D BtGatt.AdvertiseManager: message : 1
,09-13 12:57:32.141  4166  4184 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:32.152  4166  4182 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 12:57:32.152  4166  4182 D BtGatt.GattService: Client app is not null!
,09-13 12:57:32.154  4166  4193 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 12:57:32.154  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 12:57:32.154  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 12:57:32.154  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 12:57:32.154  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 12:57:32.155  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 12:57:32.157  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:32.157  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 12:57:32.157  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 12:57:32.158  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:32.159  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 12:57:32.159  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:32.159  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:32.159  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:32.159  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-13 12:57:32.159  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:32.161  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:32.161  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:32.162  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:32.162  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 not in the list
09-13 12:57:32.162  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:32.162  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d not in the list
09-13 12:57:32.163  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:32.163  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:32.163  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:32.165  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:57:32.167  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:57:32.167  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 12:57:32.167  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 12:57:32.167  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:32.167  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 12:57:32.170  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 12:57:32.171  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 12:57:32.174  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 12:57:32.175  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 12:57:32.175  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 12:57:32.180  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 12:57:32.181  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 12:57:32.182  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 12:57:32.182  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:32.185  4166  4203 D BtGatt.GattService: registerClient() - UUID=111a516c-c9bc-45d3-9d77-616953adee2b
09-13 12:57:32.185  4166  4182 D BtGatt.GattService: onClientRegistered() - UUID=111a516c-c9bc-45d3-9d77-616953adee2b, clientIf=5
09-13 12:57:32.186  3805  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:32.187  4166  4206 D BtGatt.GattService: start scan with filters
,09-13 12:57:32.193  4166  4185 D BtGatt.ScanManager: handling starting scan
09-13 12:57:32.193  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 12:57:32.194  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 12:57:32.194  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 12:57:32.194  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 12:57:32.197  4166  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aa27daa
,09-13 12:57:32.199  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 12:57:32.199  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:32.199  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 12:57:32.201  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:32.211  4166  4182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 12:57:32.211  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:32.212  4166  4185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 12:57:32.219  4166  4182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 12:57:32.219  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 12:57:32.219  4166  4185 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 12:57:32.220  4166  4185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 12:57:32.230  4166  4182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 12:57:32.230  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:32.236  4166  4182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 12:57:32.236  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:32.700  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 12:57:32.701  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:57:32.701  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:33.766  4166  4166 D BtGatt.ScanManager: awakened up at time 161259
,09-13 12:57:33.817  4166  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 12:57:33.850  4166  4182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 12:57:33.850  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:33.851  4166  4182 D BtGatt.GattService: current time is 161345157905
,09-13 12:57:33.853  4166  4182 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, -126, -22, -96, 83, -39, -56, 1, -128, -71, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -97, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 12:57:33.856  4166  4182 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
,09-13 12:57:33.859  4166  4182 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65]
09-13 12:57:33.860  4166  4182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 12:57:33.860  4166  4182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 12:57:33.861  4166  4182 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 12:57:33.865  3805  3805 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 6], added - the peer count is 1
,09-13 12:57:33.865  3805  3805 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 6], added - the peer count is 2
,09-13 12:57:33.865  3805  3805 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 6], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-13 12:57:33.866  3805  3805 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 6], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-13 12:57:33.918  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:34.029  1495  4282 I VacuumService: Vacuum at: now=1473764254029 tag=VacuumService
,09-13 12:57:34.172  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 12:57:34.191  1495  4283 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 12:57:34.195  1495  4283 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:57:34.224  1495  4283 W Uploader:  no longer exists, so no auth token.
,09-13 12:57:34.235  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 12:57:34.235  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 12:57:34.235  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:34.235  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:34.259  3525  3525 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 12:57:34.259  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 12:57:34.259  3525  3525 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 12:57:34.353  4166  4166 D BtGatt.ScanManager: awakened up at time 161847
,09-13 12:57:34.355  4166  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 12:57:34.374  4166  4182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 12:57:34.374  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:34.775   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 15 -> obsolete
,09-13 12:57:35.205  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 12:57:35.205  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:35.205  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 12:57:35.205  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 not in the list
,09-13 12:57:35.205  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:35.205  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 12:57:35.206  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:35.206  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 12:57:35.206  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 12:57:35.206  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 12:57:35.208  3805  3857 D BluetoothAdapter: STATE_ON
,09-13 12:57:35.209  4166  4193 D BtGatt.GattService: stopScan() - queue size =1
09-13 12:57:35.211  4166  4206 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 12:57:35.212  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 12:57:35.212  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 12:57:35.212  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 12:57:35.213  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 12:57:35.213  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 12:57:35.224  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:35.224  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 12:57:35.224  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-13 12:57:35.224  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:57:35.226  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:35.226  3805  3857 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 12:57:35.228  4166  4166 D BtGatt.ScanManager: awakened up at time 162721
,09-13 12:57:35.233  4166  4182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 12:57:35.233  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 12:57:35.233  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 12:57:35.233  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:35.233  4166  4185 D BtGatt.ScanManager: stopping BLe Batch
,09-13 12:57:35.233  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:35.234  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d not in the list
,09-13 12:57:35.234  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:35.234  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:35.235  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:35.237  3805  3857 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-13 12:57:35.237  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-13 12:57:35.237  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:35.238  3805  3857 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 12:57:35.238  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 12:57:35.238  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:57:35.240  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 12:57:35.240  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 12:57:35.241  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 12:57:35.241  4166  4182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 12:57:35.241  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 12:57:35.242  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 12:57:35.242  4166  4185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 12:57:35.242  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 12:57:35.243  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 12:57:35.243  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 12:57:35.243  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 12:57:35.246  3805  3857 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 12:57:35.246  3805  3857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 12:57:35.250  4166  4182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 12:57:35.250  4166  4182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 12:57:35.250  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 12:57:35.251  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 12:57:35.251  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 12:57:35.253  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 12:57:35.253  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 12:57:35.253  3805  4292 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 12:57:35.253  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-13 12:57:35.253  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:35.253  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 12:57:35.253  3805  3857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 12:57:35.254  3805  3857 D BluetoothAdapter: STATE_ON
09-13 12:57:35.255  3805  4292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 12:57:35.256  4166  4193 D BtGatt.GattService: registerClient() - UUID=7cc3fbbd-51b5-4dc8-9a6d-b114571ddee0
09-13 12:57:35.257  4166  4182 D BtGatt.GattService: onClientRegistered() - UUID=7cc3fbbd-51b5-4dc8-9a6d-b114571ddee0, clientIf=5
09-13 12:57:35.257  3805  3816 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 12:57:35.258  4166  4184 D BtGatt.AdvertiseManager: message : 0
09-13 12:57:35.260  4166  4184 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 12:57:35.270  4166  4182 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 12:57:35.276  4166  4182 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 12:57:35.276  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 12:57:35.276  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 12:57:35.278  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 12:57:35.279  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:35.279  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 12:57:35.279  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 12:57:35.279  3805  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 12:57:35.279  3805  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 12:57:35.279  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 12:57:35.281  3805  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:35.282  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 12:57:35.624  1495  4283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 12:57:35.625  1495  4283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-13 12:57:35.625  1495  4283 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:35.625  1495  4283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:35.643  1495  4283 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:57:35.643  1495  4283 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:57:35.643  1495  4283 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:57:35.783  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 12:57:35.783  3805  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 12:57:35.783  3805  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 12:57:35.926   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 15 -> obsolete
,09-13 12:57:36.027  1495  4283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-13 12:57:36.027  1495  4283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 12:57:36.027  1495  4283 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 12:57:36.027  1495  4283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:36.047  1495  4283 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:57:36.047  1495  4283 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:57:36.047  1495  4283 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:57:36.705  1495  4283 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 12:57:36.705  1495  4283 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 12:57:36.706  1495  4283 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 12:57:36.706  1495  4283 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 12:57:36.731  1495  4283 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 12:57:36.731  1495  4283 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 12:57:36.731  1495  4283 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 12:57:37.188   873  1304 D ConnectivityService: handlePromptUnvalidated 102
,09-13 12:57:38.282  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:38.283  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 12:57:38.283  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 12:57:38.284  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 12:57:38.284  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 12:57:38.285  3805  3857 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 12:57:38.285  3805  4292 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 12:57:38.285  3805  4292 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 12:57:38.286  3805  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 12:57:38.286  3805  4292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 12:57:38.286  3805  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 12:57:38.286  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 not in the list
,09-13 12:57:38.287  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 12:57:38.287  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 12:57:38.287  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 12:57:38.287  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 12:57:38.288  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 12:57:38.290  3805  3857 D BluetoothAdapter: STATE_ON
09-13 12:57:38.291  3805  3857 D BluetoothLeScanner: could not find callback wrapper
09-13 12:57:38.291  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 12:57:38.291  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 12:57:38.295  4166  4184 D BtGatt.AdvertiseManager: message : 1
09-13 12:57:38.297  4166  4184 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 12:57:38.306  4166  4182 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 12:57:38.307  4166  4182 D BtGatt.GattService: Client app is not null!
,09-13 12:57:38.308  4166  4193 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 12:57:38.310  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 12:57:38.310  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 12:57:38.311  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 12:57:38.311  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 12:57:38.311  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 12:57:38.313  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 12:57:38.313  3805  3857 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 12:57:38.313  3805  3857 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 12:57:38.314  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:38.318  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d not in the list
,09-13 12:57:38.318  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
09-13 12:57:38.318  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:38.318  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:38.319  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:38.319  3805  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 12:57:38.320  3805  3857 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 12:57:38.320  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 12:57:38.320  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 12:57:38.320  3805  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 12:57:38.320  3805  3857 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e7bbd4 not in the list
09-13 12:57:38.320  3805  3857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 12:57:38.320  3805  3857 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bddc17d not in the list
09-13 12:57:38.320  3805  3857 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 12:57:38.320  3805  3857 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 12:57:38.320  3805  3857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 12:57:38.321  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 12:57:38.321  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 12:57:38.321  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 12:57:38.321  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 12:57:38.322  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 12:57:38.322  3805  3857 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 12:57:38.333  3805  4297 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 539, name: My test thread name)
,09-13 12:57:38.821  3805  3805 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 12:57:40.333  3805  3857 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 539
,09-13 12:57:40.334  3805  3857 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 539, name: My test thread name)
,09-13 12:57:40.341  3805  4297 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 539, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-13 12:57:40.342  3805  4299 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 540, name: My test thread name)
,09-13 12:57:40.342  3805  4299 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 540, thread name: My test thread name)
,09-13 12:57:40.343  3805  4299 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 540, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 12:57:40.348  3805  3857 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 12:57:40.357  3805  4300 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 544, name: My test thread name)
,09-13 12:57:40.358  3805  4300 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 544, thread name: My test thread name): Test exception.
09-13 12:57:40.359  3805  4300 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 544, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 12:57:40.365  3805  3857 I jxcore-log: Total number of executed tests:  82
09-13 12:57:40.365  3805  3857 I jxcore-log: 
,09-13 12:57:40.366  3805  3857 I jxcore-log: Number of passed tests:  82
09-13 12:57:40.366  3805  3857 I jxcore-log: 
,09-13 12:57:40.367  3805  3857 I jxcore-log: Number of failed tests:  0
09-13 12:57:40.367  3805  3857 I jxcore-log: 
,09-13 12:57:40.369  3805  3857 I jxcore-log: Number of ignored tests:  0
09-13 12:57:40.369  3805  3857 I jxcore-log: 
,09-13 12:57:40.369  3805  3857 I jxcore-log: Total duration:  23997
09-13 12:57:40.369  3805  3857 I jxcore-log: 
,09-13 12:57:40.374  3805  3857 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 12:57:40.374  3805  3857 I jxcore-log: 
,09-13 12:57:40.377  3805  3857 I jxcore-log: My device name is: motorola-Nexus 6
09-13 12:57:40.377  3805  3857 I jxcore-log: 
09-13 12:57:40.384  3805  3857 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 12:57:40.384  3805  3857 I jxcore-log: 
09-13 12:57:40.392  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.392  3805  3857 I jxcore-log: 
,09-13 12:57:40.394  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.394  3805  3857 I jxcore-log: 
09-13 12:57:40.396  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.396  3805  3857 I jxcore-log: 
09-13 12:57:40.397  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.397  3805  3857 I jxcore-log: 
,09-13 12:57:40.402  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.402  3805  3857 I jxcore-log: 
,09-13 12:57:40.404  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.404  3805  3857 I jxcore-log: 
,09-13 12:57:40.405  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.405  3805  3857 I jxcore-log: 
09-13 12:57:40.406  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.406  3805  3857 I jxcore-log: 
09-13 12:57:40.407  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.407  3805  3857 I jxcore-log: 
09-13 12:57:40.408  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.408  3805  3857 I jxcore-log: 
,09-13 12:57:40.411  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.411  3805  3857 I jxcore-log: 
09-13 12:57:40.412  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.412  3805  3857 I jxcore-log: 
,09-13 12:57:40.414  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.414  3805  3857 I jxcore-log: 
,09-13 12:57:40.416  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.416  3805  3857 I jxcore-log: 
,09-13 12:57:40.417  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.417  3805  3857 I jxcore-log: 
,09-13 12:57:40.418  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 12:57:40.418  3805  3857 I jxcore-log: 
09-13 12:57:40.419  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.419  3805  3857 I jxcore-log: 
09-13 12:57:40.420  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.420  3805  3857 I jxcore-log: 
09-13 12:57:40.420  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.420  3805  3857 I jxcore-log: 
,09-13 12:57:40.421  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.421  3805  3857 I jxcore-log: 
09-13 12:57:40.422  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.422  3805  3857 I jxcore-log: 
,09-13 12:57:40.423  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.423  3805  3857 I jxcore-log: 
09-13 12:57:40.423  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.423  3805  3857 I jxcore-log: 
,09-13 12:57:40.424  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.424  3805  3857 I jxcore-log: 
,09-13 12:57:40.425  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.425  3805  3857 I jxcore-log: 
09-13 12:57:40.426  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.426  3805  3857 I jxcore-log: 
,09-13 12:57:40.426  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.426  3805  3857 I jxcore-log: 
,09-13 12:57:40.428  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.428  3805  3857 I jxcore-log: 
,09-13 12:57:40.429  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.429  3805  3857 I jxcore-log: 
09-13 12:57:40.429  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.429  3805  3857 I jxcore-log: 
,09-13 12:57:40.431  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-13 12:57:40.431  3805  3857 I jxcore-log: 
,09-13 12:57:40.432  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.432  3805  3857 I jxcore-log: 
,09-13 12:57:40.432  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.432  3805  3857 I jxcore-log: 
,09-13 12:57:40.433  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.433  3805  3857 I jxcore-log: 
,09-13 12:57:40.434  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.434  3805  3857 I jxcore-log: 
09-13 12:57:40.434  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.434  3805  3857 I jxcore-log: 
,09-13 12:57:40.435  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.435  3805  3857 I jxcore-log: 
09-13 12:57:40.436  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.436  3805  3857 I jxcore-log: 
09-13 12:57:40.436  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.436  3805  3857 I jxcore-log: 
,09-13 12:57:40.437  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.437  3805  3857 I jxcore-log: 
,09-13 12:57:40.438  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.438  3805  3857 I jxcore-log: 
09-13 12:57:40.438  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.438  3805  3857 I jxcore-log: 
09-13 12:57:40.439  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.439  3805  3857 I jxcore-log: 
09-13 12:57:40.440  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 12:57:40.440  3805  3857 I jxcore-log: 
09-13 12:57:40.440  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.440  3805  3857 I jxcore-log: 
09-13 12:57:40.441  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.441  3805  3857 I jxcore-log: 
,09-13 12:57:40.442  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.442  3805  3857 I jxcore-log: 
,09-13 12:57:40.442  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.442  3805  3857 I jxcore-log: 
09-13 12:57:40.443  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 12:57:40.443  3805  3857 I jxcore-log: 
09-13 12:57:40.444  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.444  3805  3857 I jxcore-log: 
09-13 12:57:40.445  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.445  3805  3857 I jxcore-log: 
09-13 12:57:40.445  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:57:40.445  3805  3857 I jxcore-log: 
09-13 12:57:40.447  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.447  3805  3857 I jxcore-log: 
09-13 12:57:40.447  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 12:57:40.447  3805  3857 I jxcore-log: 
09-13 12:57:40.448  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 12:57:40.448  3805  3857 I jxcore-log: 
09-13 12:57:40.449  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 12:57:40.449  3805  3857 I jxcore-log: 
09-13 12:57:40.450  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 12:57:40.450  3805  3857 I jxcore-log: 
,09-13 12:57:40.451  3805  3857 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 12:57:40.451  3805  3857 I jxcore-log: 
,09-13 12:57:41.041  4301  4301 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 12:57:41.048  4301  4301 D AndroidRuntime: CheckJNI is OFF
,09-13 12:57:41.090  4301  4301 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 12:57:41.137  4301  4301 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 12:57:41.158  4301  4301 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 12:57:41.168   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 12:57:41.169   873   886 I ActivityManager: Killing 3805:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 12:57:41.250   873   896 W PackageSettings: Skipping PackageSetting{c04580f com.example.hello/10273} due to missing metadata
,09-13 12:57:41.280   873   896 I art     : Starting a blocking GC Explicit
,09-13 12:57:41.296   873  1922 I WindowState: WIN DEATH: Window{d83376 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 12:57:41.297   873  1303 D WifiService: Client connection lost with reason: 4
09-13 12:57:41.298   873  1924 D GraphicsStats: Buffer count: 2
,09-13 12:57:41.317   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-13 12:57:41.336   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 12:57:41.336   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 12:57:41.337   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-13 12:57:41.337   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 12:57:41.337   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.337   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.337   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:57:41.337   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 12:57:41.337   873   886 I ActivityManager:   Force finishing activity ActivityRecord{a80339f u0 com.test.thalitest/.MainActivity t4}
,09-13 12:57:41.341   873   896 I art     : Explicit concurrent mark sweep GC freed 27978(1868KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.559ms total 59.476ms
,09-13 12:57:41.343   873  1913 W ActivityManager: Spurious death for ProcessRecord{85af6ab 0:com.test.thalitest/u0a0}, curProc for 3805: null
,09-13 12:57:41.368   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 12:57:41.373   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 12:57:41.377  4301  4301 I art     : System.exit called, status: 0
,09-13 12:57:41.377  4301  4301 I AndroidRuntime: VM exiting with result code 0.
,09-13 12:57:41.393   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 12:57:41.396  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 12:57:41.399  4166  4166 D BluetoothMapAppObserver: onReceive
,09-13 12:57:41.399  4166  4166 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 12:57:41.399  2016  2299 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 12:57:41.406  1867  4312 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 12:57:41.407  3675  3675 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-13 12:57:41.408   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 12:57:41.411  1867  4312 I Decoder : createOrResetDecoder
,09-13 12:57:41.432   873   884 I ActivityManager: Start proc 4314:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 12:57:41.432  1942  1942 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 12:57:41.457  1495  1495 I ConfigService: onCreate
,09-13 12:57:41.479  4314  4314 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 12:57:41.478  1495  4327 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-13 12:57:41.495   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 12:57:41.498   873  1922 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3805 uid 10000
,09-13 12:57:41.499  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 12:57:41.505  1867  4312 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 12:57:41.543  4314  4314 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 12:57:41.551  1959  2056 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 12:57:41.552  4314  4329 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.552  4314  4329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:57:41.553   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 12:57:41.554  1867  4312 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 12:57:41.554   873   885 E PackageManager: Failed to write settings, restoring backup
09-13 12:57:41.554   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 12:57:41.554   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 12:57:41.554   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 12:57:41.554   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 12:57:41.554   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 12:57:41.554   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.554   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.554   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:57:41.558   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-13 12:57:41.558   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:57:41.558   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:57:41.558   873   886 E DropBoxManagerService: 	... 13 more
09-13 12:57:41.558  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 12:57:41.558  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 12:57:41.562  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 12:57:41.562  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 12:57:41.563  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 12:57:41.563  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 12:57:41.563  1867  4312 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 12:57:41.563  1867  4312 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 12:57:41.563  1867  4312 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-13 12:57:41.564  1867  4312 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 12:57:41.564  1867  4312 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 12:57:41.564  1867  4312 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 12:57:41.568   873  1958 I ActivityManager: Start proc 4333:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 12:57:41.587   873   884 I ActivityManager: Start proc 4345:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 12:57:41.588  1959  2056 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 12:57:41.588  1959  2056 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1959
09-13 12:57:41.588  1959  2056 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.588  1959  2056 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 12:57:41.591   873  1389 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 12:57:41.592   873  4351 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:57:41.592   873  4351 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:57:41.592   873  4351 E DropBoxManagerService: 	... 5 more
,09-13 12:57:41.660  1959  2056 I Process : Sending signal. PID: 1959 SIG: 9
,09-13 12:57:41.670  4314  4332 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 12:57:41.673  4333  4333 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.697  4314  4329 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 12:57:41.724  1495  1495 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-13 12:57:41.727  1495  1495 D AndroidRuntime: Shutting down VM
,09-13 12:57:41.728  1495  1495 E AndroidRuntime: FATAL EXCEPTION: main
09-13 12:57:41.728  1495  1495 E AndroidRuntime: Process: com.google.process.gapps, PID: 1495
09-13 12:57:41.728  1495  1495 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 12:57:41.728  1495  1495 E AndroidRuntime: 	... 8 more
,09-13 12:57:41.737  1495  1495 I Process : Sending signal. PID: 1495 SIG: 9
09-13 12:57:41.738   873  4364 E DropBoxManagerService: Can't write: system_app_crash
09-13 12:57:41.738   873  4364 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 12:57:41.738   873  4364 E DropBoxManagerService: 	... 5 more
,09-13 12:57:41.744   873  1958 I ActivityManager: Killing 3728:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 12:57:41.813   873  1303 D WifiService: Client connection lost with reason: 4
,09-13 12:57:41.831  4314  4329 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 12:57:41.837  4314  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.837  4314  4332 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 12:57:41.838  4314  4332 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 12:57:41.838  4314  4332 E AndroidRuntime: Process: android.process.acore, PID: 4314
09-13 12:57:41.838  4314  4332 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 12:57:41.838  4314  4332 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 12:57:41.839  4314  4329 I Process : Sending signal. PID: 4314 SIG: 9
,09-13 12:57:41.856   873   883 I ActivityManager: Process com.google.process.gapps (pid 1495) has died
09-13 12:57:41.857   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-13 12:57:41.857   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-13 12:57:41.857   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms

```
