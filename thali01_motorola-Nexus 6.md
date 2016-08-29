#### Test 81444731606602a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-29 13:28:36.503   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
08-29 13:28:36.811  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:28:36.822  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:28:36.825  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 13:28:36.863  1502  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 13:28:36.864  1502  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:28:36.864  1502  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:36.864  1502  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 13:28:36.890  3622  3622 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 13:28:36.890  3622  3622 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 13:28:36.891  3622  3622 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 13:28:37.834  3841  3841 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 13:28:37.839  3841  3841 D AndroidRuntime: CheckJNI is OFF
08-29 13:28:37.883  3841  3841 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 13:28:37.934  3841  3841 I Radio-JNI: register_android_hardware_Radio DONE
08-29 13:28:37.958  3841  3841 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:28:37.963   872  1986 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 13:28:38.016  2016  3829 W SearchService: Abort, client detached.
08-29 13:28:38.022  3841  3841 D AndroidRuntime: Shutting down VM
08-29 13:28:38.024  2016  2513 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1bf108
08-29 13:28:38.025  2016  2534 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 13:28:38.027  2016  2016 I HotwordDetector: Closing mic
08-29 13:28:38.042   872  2219 I ActivityManager: Start proc 3850:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 13:28:38.074   376  2536 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 13:28:38.078   376  2536 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 13:28:38.092   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 13:28:38.095  2016  2532 I MicroRecognitionRnrImpl: Detection finished
08-29 13:28:38.095  2016  2529 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 13:28:38.132  3850  3850 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 13:28:38.178  3850  3850 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 13:28:38.187  3850  3850 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1354-1357)
08-29 13:28:38.187  3850  3850 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:28:38.203  3850  3850 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f16ac95}
08-29 13:28:38.203  3850  3850 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 13:28:38.204  3850  3850 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:28:38.210  3850  3850 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 13:28:38.211  3850  3850 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 13:28:38.245  3850  3850 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 13:28:38.263  3850  3850 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:28:38.263  3850  3850 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:28:38.263  3850  3850 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:28:38.263  3850  3850 I Adreno  : Build Date                       : 10/20/15
,08-29 13:28:38.263  3850  3850 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:28:38.263  3850  3850 I Adreno  : Local Branch                     : M14
08-29 13:28:38.263  3850  3850 I Adreno  : Remote Branch                    : 
08-29 13:28:38.263  3850  3850 I Adreno  : Remote Branch                    : 
08-29 13:28:38.263  3850  3850 I Adreno  : Reconstruct Branch               : 
,08-29 13:28:38.357   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c2a1e56:true
,08-29 13:28:38.410  3850  3850 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 13:28:38.438  3850  3850 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 13:28:38.508  3850  3889 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 13:28:38.525  3850  3875 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 13:28:38.555  3850  3889 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 13:28:38.577  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-29 13:28:38.623   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +600ms
,08-29 13:28:38.700  3850  3850 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3850
,08-29 13:28:38.818  3850  3850 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:28:38.863   872  1987 I ActivityManager: Killing 3165:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,08-29 13:28:38.916   872  1987 I ActivityManager: Killing 3506:com.android.settings/1000 (adj 15): empty #18
,08-29 13:28:38.981  3850  3891 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1682245328
,08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 13:28:38.986  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d0d410 added. We now have 1 listener(s)
,08-29 13:28:38.989  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 13:28:38.990  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:28:38.991  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:28:38.991  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 13:28:38.994  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@635d72f added. We now have 1 listener(s)
08-29 13:28:38.994  3850  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:28:38.997   872  1309 D WifiService: New client listening to asynchronous messages
,08-29 13:28:39.003  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:28:39.003  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 13:28:39.003  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 13:28:39.003  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-29 13:28:39.003  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 13:28:39.006  3850  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:39.006  3850  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 13:28:39.016  3850  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:39.016  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:28:39.016  3850  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:28:39.016  3850  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:28:39.017  3850  3891 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:28:39.021  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:39.023  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:39.052  3850  3850 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:28:39.527   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 13:28:39.901  3850  3900 W jxcore-log: Initializing JXcore engine
,08-29 13:28:39.901  3850  3900 W jxcore-log: JXcore engine is ready
,08-29 13:28:39.937  3900  3900 W Thread-334: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 13:28:39.937  3900  3900 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10109]" dev="sockfs" ino=10109 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 13:28:39.937  3900  3900 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 13:28:39.937  3900  3900 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24998]" dev="sockfs" ino=24998 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 13:28:39.950  3850  3900 W jxcore-log: Starting JXcore engine
,08-29 13:28:40.029  3850  3900 W jxcore-log: Platform android
08-29 13:28:40.029  3850  3900 W jxcore-log: 
,08-29 13:28:40.029  3850  3900 W jxcore-log: Process ARCH arm
08-29 13:28:40.029  3850  3900 W jxcore-log: 
,08-29 13:28:40.263  3850  3900 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:28:40.263  3850  3900 I jxcore-log: 
,08-29 13:28:40.264  3850  3900 W jxcore-log: JXcore engine is started
,08-29 13:28:40.275  3850  3891 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 13:28:40.281  3850  3850 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 13:28:40.354   872  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-29 13:28:45.926  3270  3908 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 13:28:45.941  3270  3909 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 13:28:45.952  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:45.954  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:45.984  1502  2129 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 13:28:45.985  1502  2129 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 13:28:45.985  1502  2129 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 13:28:45.985  1502  2129 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:46.018  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:46.020  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:46.052  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 13:28:46.052  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 13:28:46.052  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:46.053  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:46.076  3270  3909 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 13:28:46.077  3270  3908 E BooksSync: Soft error
08-29 13:28:46.077  3270  3908 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 13:28:46.077  3270  3908 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 13:28:46.077  3270  3908 E BooksSync: Sync error
08-29 13:28:46.077  3270  3908 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 13:28:46.077  3270  3908 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 13:28:46.078  3270  3908 I BooksSync: Finished books sync
08-29 13:28:46.083   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129041, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 13:28:48.608   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 13:28:50.170  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 13:28:50.170  3850  3900 I jxcore-log: 
,08-29 13:28:50.172  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 13:28:50.172  3850  3900 I jxcore-log: 
,08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:50.187  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:50.195  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:50.201  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:28:50.201  3850  3900 I jxcore-log: 
,08-29 13:28:50.209  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:28:50.209  3850  3900 I jxcore-log: 
,08-29 13:28:50.728  3850  3900 D executeNativeTests: Running unit tests
,08-29 13:28:50.821  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:28:50.821  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 added. We now have 2 listener(s)
08-29 13:28:50.822  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:28:50.822  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:28:50.822  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:28:50.823  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:28:50.823  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e added. We now have 2 listener(s)
08-29 13:28:50.823  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:28:50.824  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:28:50.828  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:50.843  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:50.848  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:50.848  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:28:50.850  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:28:50.852  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:50.853  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:28:50.853  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-29 13:28:50.856  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:50.857  3850  3900 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 13:28:50.857  3850  3900 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 13:28:50.857  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:28:50.857  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:28:50.857  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:28:50.858  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:50.858  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:50.859  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:50.859  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:50.859  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.859  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:28:50.859  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:28:50.859  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 removed from the list
,08-29 13:28:50.860  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:28:50.860  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e removed from the list
08-29 13:28:50.860  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:50.860  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.861  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.861  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.862  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:50.862  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:50.863  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:50.863  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:50.867  3850  3900 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 13:28:50.868  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:50.868  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:50.868  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:28:50.868  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:50.868  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.868  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.869  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:50.869  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:50.869  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:50.869  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:50.869  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.869  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.869  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.869  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.872  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:50.873  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:50.873  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:50.873  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:50.893  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:28:50.893  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:28:50.893  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:28:50.894  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:28:50.894  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:28:50.894  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:28:50.894  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:28:50.895  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:28:50.895  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:28:50.895  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:28:50.895  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:28:50.896  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:28:50.896  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:28:50.896  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:28:50.897  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:28:50.898  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:28:50.898  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:28:50.898  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:28:50.898  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:50.898  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:50.898  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:50.898  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:50.898  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.898  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.898  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:50.898  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:50.898  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:50.898  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:50.898  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.899  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.899  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:50.899  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:50.900  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:50.901  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:50.901  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:50.901  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:50.901  3850  3900 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:28:50.903  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:50.913  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:28:50.917  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:50.917  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:28:50.919  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:28:50.919  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:28:50.920  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:28:50.920  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:28:50.920  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:28:50.923  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:50.928  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:50.930  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:28:50.930  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:28:50.936  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:28:50.939  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:28:50.939  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:28:50.944  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 13:28:50.950  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 13:28:50.950  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:28:50.951  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:28:50.953  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:28:50.956  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:28:50.969  2853  2866 D BtGatt.GattService: registerClient() - UUID=e3bde312-67c3-4266-bbd6-afa940897fa8
,08-29 13:28:50.970  2853  2904 D BtGatt.GattService: onClientRegistered() - UUID=e3bde312-67c3-4266-bbd6-afa940897fa8, clientIf=5
08-29 13:28:50.971  3850  3862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:28:50.973  2853  3060 D BtGatt.GattService: start scan with filters
,08-29 13:28:50.984  2853  2909 D BtGatt.ScanManager: handling starting scan
,08-29 13:28:50.985  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:28:50.986  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:28:50.987  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:28:50.987  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:28:50.990  2853  2909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:28:50.994  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:28:50.994  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:28:50.995  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:28:50.998  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:28:51.003  2853  2904 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:28:51.003  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.004  2853  2909 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:28:51.008  3850  3900 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:28:51.023  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:28:51.023  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.024  2853  2909 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:28:51.024  2853  2909 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 13:28:51.024  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.025  3850  3900 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:28:51.025  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.025  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:28:51.026  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.026  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:28:51.027  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:28:51.027  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:28:51.027  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:28:51.027  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:28:51.029  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:28:51.030  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:28:51.031  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:28:51.032  2853  3040 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:28:51.034  2853  2864 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:28:51.034  2853  2904 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:28:51.035  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.035  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:28:51.035  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:28:51.036  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:28:51.036  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:28:51.036  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:28:51.038  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:28:51.038  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:28:51.039  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:28:51.039  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:28:51.040  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:28:51.041  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:28:51.041  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.043  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:28:51.043  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.043  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:28:51.044  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.044  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.044  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:28:51.044  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
,08-29 13:28:51.044  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.045  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.045  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.045  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.047  3850  3900 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:28:51.049  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:51.051  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:28:51.051  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.051  2853  2909 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:51.054  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:51.056  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:51.056  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:28:51.056  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:28:51.056  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:28:51.056  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:28:51.056  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:28:51.056  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:28:51.057  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:28:51.057  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.057  2853  2909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:28:51.058  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.061  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.062  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:28:51.062  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:28:51.063  2853  2904 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:28:51.063  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.066  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:28:51.067  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:28:51.067  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:28:51.071  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:28:51.071  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:28:51.071  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:28:51.072  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:28:51.074  2853  3040 D BtGatt.GattService: registerClient() - UUID=4ce73012-7cd9-4066-918d-cf76dd427abb
,08-29 13:28:51.075  2853  2904 D BtGatt.GattService: onClientRegistered() - UUID=4ce73012-7cd9-4066-918d-cf76dd427abb, clientIf=5
08-29 13:28:51.075  3850  3862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:28:51.075  2853  3060 D BtGatt.GattService: start scan with filters
,08-29 13:28:51.079  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:28:51.079  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:28:51.079  2853  2909 D BtGatt.ScanManager: handling starting scan
08-29 13:28:51.079  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:28:51.079  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:28:51.082  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:28:51.082  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:28:51.083  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:28:51.084  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:28:51.085  2853  2904 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:28:51.086  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.086  2853  2909 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:28:51.086  3850  3900 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:28:51.089  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:28:51.089  3850  3900 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:28:51.089  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.089  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:28:51.089  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.089  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:28:51.089  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:28:51.090  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:28:51.090  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 13:28:51.090  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:28:51.090  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:28:51.090  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:28:51.091  3850  3900 D BluetoothAdapter: STATE_ON
08-29 13:28:51.091  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:28:51.091  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.091  2853  3040 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:28:51.092  2853  2909 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:28:51.092  2853  2909 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:28:51.092  2853  3060 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:28:51.092  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:28:51.092  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:28:51.092  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:28:51.093  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:28:51.093  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:28:51.094  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.094  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:28:51.094  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:28:51.094  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:28:51.095  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:28:51.095  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.095  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.096  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.096  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.096  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.096  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:28:51.096  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.096  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.096  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.096  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.096  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.097  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.097  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.097  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.097  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.098  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.098  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.098  3850  3900 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:28:51.100  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:51.101  2853  2904 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:28:51.102  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:51.105  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:51.106  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:51.107  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:28:51.107  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:28:51.107  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 13:28:51.108  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:28:51.108  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:28:51.108  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:28:51.108  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:28:51.108  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.109  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.111  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:28:51.111  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:28:51.111  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.114  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:28:51.115  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 13:28:51.115  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:28:51.116  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:28:51.116  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.116  2853  2909 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:28:51.119  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:28:51.119  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:28:51.119  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:28:51.120  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:28:51.122  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:28:51.122  2853  3060 D BtGatt.GattService: registerClient() - UUID=6eb19f3e-b051-4016-af9d-3a9e2e637e00
,08-29 13:28:51.122  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.122  2853  2904 D BtGatt.GattService: onClientRegistered() - UUID=6eb19f3e-b051-4016-af9d-3a9e2e637e00, clientIf=5
,08-29 13:28:51.122  2853  2909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:28:51.122  3850  3862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:28:51.123  2853  2866 D BtGatt.GattService: start scan with filters
,08-29 13:28:51.127  2853  2904 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:28:51.127  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.128  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:28:51.128  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:28:51.128  2853  2909 D BtGatt.ScanManager: handling starting scan
08-29 13:28:51.128  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:28:51.128  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:28:51.131  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:28:51.131  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:28:51.131  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:28:51.133  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:28:51.134  2853  2904 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:28:51.134  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.134  2853  2909 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:28:51.136  3850  3900 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:28:51.136  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.136  3850  3900 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:28:51.136  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.136  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:28:51.136  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.136  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:28:51.136  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:28:51.136  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:28:51.137  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 13:28:51.137  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:28:51.137  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:28:51.137  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:28:51.138  3850  3900 D BluetoothAdapter: STATE_ON
08-29 13:28:51.138  2853  2866 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:28:51.139  2853  3040 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:28:51.139  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:28:51.139  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:28:51.139  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:28:51.139  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:28:51.139  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:28:51.140  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.141  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:28:51.141  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:28:51.141  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:28:51.141  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:28:51.141  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.141  2853  2909 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:28:51.141  2853  2909 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:28:51.141  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:28:51.142  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.142  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.142  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.143  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.143  3850  3900 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:28:51.143  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:28:51.143  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.143  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.143  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.143  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:28:51.143  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.143  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.144  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.144  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.144  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.144  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.144  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:28:51.145  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.145  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.145  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:28:51.145  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.146  3850  3900 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:28:51.146  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.146  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.146  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.146  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.147  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.147  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.147  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.147  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.147  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.147  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:28:51.147  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.147  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.147  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.147  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.148  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.148  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.148  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.148  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.149  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:28:51.149  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.149  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:28:51.149  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.149  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.149  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.150  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.150  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.150  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.150  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.150  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.150  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.150  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.150  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.150  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.151  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.151  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.151  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.151  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.152  3850  3900 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 13:28:51.152  2853  2904 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:28:51.152  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.152  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.152  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.152  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:28:51.152  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.152  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.153  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.153  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.153  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.153  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.153  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.153  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.153  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.153  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.153  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:28:51.154  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.154  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.154  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.154  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.155  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 13:28:51.155  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.155  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.155  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:28:51.155  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.155  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.155  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.155  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.156  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.156  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.156  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.156  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.156  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:28:51.156  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.156  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.157  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.157  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.157  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.157  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:28:51.157  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.157  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.158  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:28:51.159  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:28:51.159  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:28:51.159  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:28:51.160  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:28:51.160  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:28:51.160  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:28:51.160  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.160  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.160  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.160  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.160  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.160  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.161  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.161  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.161  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.161  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.161  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.161  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.161  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.162  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.162  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.162  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:28:51.162  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.162  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:28:51.163  3850  3900 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:28:51.163  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:28:51.164  2853  2904 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:28:51.164  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.164  2853  2909 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:28:51.166  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:28:51.166  3850  3900 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-29 13:28:51.166  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:28:51.166  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:28:51.166  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:28:51.166  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:28:51.166  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:28:51.167  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:28:51.168  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:28:51.169  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-29 13:28:51.169  3850  3900 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:28:51.170  3850  3900 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:28:51.170  2853  2904 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:28:51.170  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:28:51.170  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:28:51.170  3850  3900 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:28:51.170  2853  2909 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:28:51.170  3850  3900 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-29 13:28:51.170  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:28:51.170  3850  3900 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:28:51.170  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:28:51.175  2853  2904 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:28:51.176  2853  2904 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:28:51.177  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 13:28:51.179  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:28:51.179  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 13:28:51.179  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:28:51.180  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-29 13:28:51.180  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:28:51.180  3850  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-29 13:28:51.180  3850  3900 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:28:51.181  3850  3900 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 13:28:51.181  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.181  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:28:51.181  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.182  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.182  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.182  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.182  3850  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:28:51.182  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:28:51.182  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.182  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.183  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.183  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.183  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.183  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.183  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.183  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:28:51.184  3850  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-29 13:28:51.184  3850  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 398)
08-29 13:28:51.184  3850  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 398)
,08-29 13:28:51.184  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.185  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:28:51.185  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.185  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.185  3850  3900 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:28:51.186  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.186  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.186  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.184  3850  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-29 13:28:51.186  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.186  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.186  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.186  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
,08-29 13:28:51.186  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.186  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.186  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.186  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.186  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.186  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.186  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.187  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.188  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.188  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.188  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.188  3850  3900 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:28:51.188  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.188  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.188  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:28:51.189  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.189  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.189  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.189  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.189  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.189  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.189  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.189  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.189  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.189  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.189  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.190  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.190  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.190  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:28:51.190  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.191  3850  3900 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:28:51.191  3850  3900 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:28:51.191  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:28:51.191  3850  3900 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:28:51.191  3850  3900 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-29 13:28:51.191  3850  3900 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:28:51.191  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:28:51.191  3850  3900 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:28:51.191  3850  3900 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:28:51.192  3850  3900 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:28:51.192  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:28:51.192  3850  3900 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:28:51.192  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.192  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:28:51.192  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.192  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.192  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.192  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.192  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.192  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.192  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.192  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.192  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.192  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.193  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.193  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.193  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.193  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.193  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.194  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.194  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.194  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.194  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.194  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
,08-29 13:28:51.194  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.194  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.194  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.194  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.194  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.194  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.195  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.195  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.195  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.195  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.195  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.195  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:28:51.195  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.195  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.195  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.195  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.195  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.195  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.195  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.195  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.195  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.195  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.195  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.195  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.196  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.196  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.196  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.196  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.196  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.197  3850  3900 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:28:51.197  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:28:51.198  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:28:51.199  3850  3900 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:28:51.199  3850  3900 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 13:28:51.199  3850  3850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:28:51.199  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:28:51.199  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:28:51.199  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.199  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:28:51.200  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:28:51.200  3850  3850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:28:51.200  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.200  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.200  3850  3900 I org.thaliproject.p2p.btconn,ectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:28:51.200  3850  3918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:28:51.200  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.200  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.201  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.201  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.201  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:28:51.201  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:28:51.202  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.202  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.202  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.202  3850  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 13:28:51.202  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.202  3850  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:28:51.202  3850  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:28:51.202  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.202  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.202  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.202  3850  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
08-29 13:28:51.202  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.202  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.202  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.202  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.203  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.203  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.203  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.203  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:28:51.204  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.204  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.204  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.204  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.205  3850  3900 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:28:51.205  3850  3900 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:28:51.205  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:28:51.205  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 13:28:51.205  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.206  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.206  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.206  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.206  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.206  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.206  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.206  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.206  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.206  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:28:51.206  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.206  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.206  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.206  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.207  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.207  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.207  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.208  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.211  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.211  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.211  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:28:51.212  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.212  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.212  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.212  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.212  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.212  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.212  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.212  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.212  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.212  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.212  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.213  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.213  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.213  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.213  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.214  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:28:51.214  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:28:51.214  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:28:51.214  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:28:51.214  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.214  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.214  3850  3900 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f7dd99 not in the list
08-29 13:28:51.214  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.214  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
08-29 13:28:51.214  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:28:51.214  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:28:51.214  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.214  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:28:51.214  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:28:51.215  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:28:51.215  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:28:51.215  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:28:51.215  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364285e not in the list
,08-29 13:28:51.216  3850  3900 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:28:51.216  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:28:51.216  3850  3900 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:28:51.216  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:28:51.216  3850  3900 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:28:51.216  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 13:28:51.218  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:28:51.218  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:28:51.218  3850  3900 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:28:51.218  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:28:51.218  3850  3900 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 13:28:51.218  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-29 13:28:51.218  3850  3900 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:28:51.219  3850  3900 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-29 13:28:51.220  3850  3900 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:28:51.220  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:28:51.220  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f16810 added. We now have 2 listener(s)
08-29 13:28:51.220  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:28:51.223  3850  3900 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 13:28:51.223   872  1987 D WifiService: setWifiEnabled: true pid=3850, uid=10000
08-29 13:28:51.223   872  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:28:51.224  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:28:51.224  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5de5f09 added. We now have 3 listener(s)
08-29 13:28:51.224  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:28:51.233  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:28:51.233  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a99650e added. We now have 4 listener(s)
,08-29 13:28:51.233  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:28:51.235  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:28:51.235  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ee7b2f added. We now have 5 listener(s)
08-29 13:28:51.235  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:28:51.237   872  2006 D WifiService: setWifiEnabled: false pid=3850, uid=10000
08-29 13:28:51.237   872  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:28:51.243  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:28:51.244  2853  2900 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 13:28:51.245  2853  2900 D BluetoothAdapterProperties: Setting state to 13
,08-29 13:28:51.245  2853  2900 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 13:28:51.245  2853  2900 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:28:51.245  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:51.245  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:51.246  2853  2900 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:28:51.247  2853  2904 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:28:51.247  2853  2900 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 13:28:51.247  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.247  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:51.247  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:28:51.250  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.251  2853  2853 D BluetoothMapService: onReceive
,08-29 13:28:51.251  2853  2853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:28:51.251  2853  2853 D BluetoothMapService: STATE_TURNING_OFF
08-29 13:28:51.252  2853  2853 D BluetoothMapService: MAP Service closeService in
,08-29 13:28:51.252  2853  2853 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 13:28:51.252  2853  2853 D ObexServerSockets0: shutdown(block = true)
08-29 13:28:51.252  2853  2853 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 13:28:51.252  2853  2853 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:28:51.253  2853  3061 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 13:28:51.253  2853  3062 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 13:28:51.253  2853  3037 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 13:28:51.255  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.255  2853  2853 I BtOppRfcommListener: stopping Accept Thread
08-29 13:28:51.256  2853  3550 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:28:51.257  2853  3550 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:28:51.257  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:51.257  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:28:51.257  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.258  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:51.262  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.263   872   885 I ActivityManager: Start proc 3921:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 13:28:51.267  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.263  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 13:28:51.269  2853  2853 D HeadsetService: Received stop request...Stopping profile...
08-29 13:28:51.271   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 13:28:51.271  1950  1962 D BluetoothHeadset: Proxy object disconnected
08-29 13:28:51.272  2853  2853 D A2dpService: Received stop request...Stopping profile...
08-29 13:28:51.272  2853  3053 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:28:51.272  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.273  2364  2543 D BluetoothHeadset: Proxy object disconnected
08-29 13:28:51.274   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 13:28:51.274   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 13:28:51.274   872   872 D BluetoothA2dp: Proxy object disconnected
08-29 13:28:51.275   872  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 13:28:51.275   872  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 13:28:51.275   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:28:51.275   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:28:51.279  2853  2853 D HidService: Received stop request...Stopping profile...
08-29 13:28:51.279  2853  2853 D HidService: Stopping Bluetooth HidService
08-29 13:28:51.283   872  2094 D DhcpClient: Clearing IP address
08-29 13:28:51.283   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:28:51.287  2853  2853 D HealthService: Received stop request...Stopping profile...
,08-29 13:28:51.288  2853  2853 V BluetoothAdapterState: isTurningOff()=true
,08-29 13:28:51.288  2853  2853 V BluetoothAdapterState: isTurningOn()=false
08-29 13:28:51.288  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:28:51.288  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:28:51.289  1502  2599 V NativeCrypto: Read error: ssl=0x9b05e800: I/O error during system call, Connection timed out
08-29 13:28:51.290   372   870 D CommandListener: Setting iface cfg
,08-29 13:28:51.290  2364  2364 D HeadsetProfile: Bluetooth service disconnected
08-29 13:28:51.290  2364  2364 D BluetoothA2dp: Proxy object disconnected
08-29 13:28:51.290  2364  2364 D BluetoothInputDevice: Proxy object disconnected
08-29 13:28:51.290  2364  2364 D HidProfile: Bluetooth service disconnected
,08-29 13:28:51.291   872  2221 D DhcpClient: Receive thread stopped
08-29 13:28:51.291  1502  2599 V NativeCrypto: SSL shutdown failed: ssl=0x9b05e800: I/O error during system call, Broken pipe
08-29 13:28:51.292   872  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 13:28:51.292   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 13:28:51.292   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 13:28:51.293   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:28:51.293  2853  2853 D PanService: Received stop request...Stopping profile...
08-29 13:28:51.294   395   395 E Parcel  : Reading a NULL string not supported here.
08-29 13:28:51.296   872  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 13:28:51.299  2364  2364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:28:51.300  2364  2364 D PanProfile: Bluetooth service disconnected
,08-29 13:28:51.305  2853  2853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 13:28:51.305  2853  2904 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:28:51.305  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:28:51.305  2853  2853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:28:51.305  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:28:51.305  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:28:51.305  2853  2904 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 13:28:51.306  2853  2853 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:28:51.306  2853  2853 D BluetoothMapService: stop()
08-29 13:28:51.306  2853  2853 D BluetoothMapAppObserver: deinitObservers()
08-29 13:28:51.306  2853  2853 D BluetoothMapAppObserver: removeReceiver()
,08-29 13:28:51.307  2853  2853 V BluetoothAdapterState: isTurningOff()=true
,08-29 13:28:51.307  2853  2853 V BluetoothAdapterState: isTurningOn()=false
08-29 13:28:51.308  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:28:51.308  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isTurningOff()=true
08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:28:51.310  2853  2853 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:28:51.310  2853  2853 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isTurningOff()=true
,08-29 13:28:51.310  2853  2853 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:28:51.311  2853  2853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 13:28:51.311  2853  2904 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:28:51.311  2853  2904 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:28:51.311  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:28:51.311  2853  2904 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:28:51.311  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:28:51.311  2853  2853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:28:51.311  2853  3034 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 13:28:51.311  2853  3034 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 13:28:51.311  2853  3034 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isTurningOff()=true
08-29 13:28:51.311  2853  3034 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isTurningOn()=false
08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:28:51.311  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:28:51.311  2853  2853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:28:51.312  2853  2853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:28:51.312  2853  2853 D BluetoothMapService: MAP Service closeService in
08-29 13:28:51.312  2853  2853 V BluetoothAdapterState: isTurningOff()=true
08-29 13:28:51.312  2853  2853 V BluetoothAdapterState: isTurningOn()=false
08-29 13:28:51.312  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:28:51.312  2853  2853 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:28:51.312  2853  2853 D BluetoothMapService: cleanup()
08-29 13:28:51.313  2853  2853 D BluetoothMapService: MAP Service closeService in
08-29 13:28:51.313  2853  2900 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 13:28:51.313  2853  2900 D BluetoothAdapterProperties: Setting state to 15
08-29 13:28:51.313  2853  2900 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-29 13:28:51.313  2853  2900 I BluetoothAdapterState: Entering BleOnState
,08-29 13:28:51.315   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:28:51.315   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:28:51.315  2364  2375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:28:51.316  2364  2543 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 13:28:51.317  2364  2377 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:28:51.317  1950  1964 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:28:51.318  2364  2375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:28:51.318  2364  2364 D BluetoothMap: Proxy object disconnected
,08-29 13:28:51.319  2364  2364 D MapProfile: Bluetooth service disconnected
08-29 13:28:51.320   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:28:51.321  2364  2377 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:28:51.321   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:28:51.321  2364  2543 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:28:51.322  2853  2900 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:28:51.322  2853  2900 D BluetoothAdapterProperties: Setting state to 16
,08-29 13:28:51.322  2853  2900 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 13:28:51.322  2853  2900 D BluetoothAdapterProperties: onBleDisable
08-29 13:28:51.322  2853  2900 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:28:51.323  2853  2901 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 13:28:51.323  2853  2904 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:28:51.324  2853  3034 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:28:51.324  2853  3034 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:28:51.324  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:51.325  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:51.325  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:51.325  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:51.328  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:51.328  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:51.328  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.328  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:51.330  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.331  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.339  3921  3921 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 13:28:51.345   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:28:51.350  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:28:51.355  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:28:51.358   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f8ad9e:true
,08-29 13:28:51.368   872  2219 I ActivityManager: Start proc 3937:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 13:28:51.369   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 13:28:51.370   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:28:51.371   872  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-29 13:28:51.371   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:28:51.373   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:28:51.376  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:28:51.377  3522  3522 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d421837 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 13:28:51.377   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:28:51.377  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:28:51.381   872  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:28:51.382  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:51.382  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:51.383  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:51.383  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:51.384  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:51.385  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:51.385  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:51.385  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:28:51.389  1886  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:28:51.402  3921  3921 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 13:28:51.406  3921  3921 D BluetoothMap: Create BluetoothMap proxy object
,08-29 13:28:51.413  3937  3937 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 13:28:51.415  3921  3921 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 13:28:51.420   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 13:28:51.425  3921  3921 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:28:51.435   872  1712 I ActivityManager: Killing 3319:com.google.android.gm/u0a78 (adj 15): empty #17
,08-29 13:28:51.526  2853  2904 I bt_hci  : shut_down
,08-29 13:28:51.527  2853  2910 D bt_hwcfg: hw_epilog_process
,08-29 13:28:51.528  2853  2910 I bt_vendor: low_power_mode_cb
,08-29 13:28:51.553  2853  2910 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 13:28:51.554  2853  2910 I bt_vendor: epilog_cb
08-29 13:28:51.554  2853  2910 I bt_hci  : epilog_finished_callback
,08-29 13:28:51.557  2853  2904 I bt_hci_h4: hal_close
,08-29 13:28:51.557  2853  2904 I bt_userial_vendor: device fd = 51 close
,08-29 13:28:51.569  3937  3937 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.569  3937  3937 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:28:51.569  3937  3937 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.569  3937  3937 D Str,ictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:28:51.569  3937  3937 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.569  3937  3937 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.569  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.570  3937  3937 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.570  3937  3937 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.570  3937  3937 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 13:28:51.570  3937  3937 D StrictMode: 	,at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.570  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.571  3937  3937 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:28:51.571  3937  3937 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 13:28:51.578  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:28:51.587  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:28:51.596  3921  3921 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:28:51.612   872  1987 I ActivityManager: Killing 3522:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 13:28:51.683  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:28:51.700  1713  1713 D SystemUpdateService: onCreate
,08-29 13:28:51.702  3850  3850 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:28:51.703  2853  2901 D bt_stack_manager: event_shut_down_stack finished.
08-29 13:28:51.704  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-29 13:28:51.704  2853  2900 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:28:51.708  2853  2853 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:28:51.708  2853  2900 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 13:28:51.709  2853  2853 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 13:28:51.709  2853  2853 D BtGatt.GattService: stop()
08-29 13:28:51.709  2853  2853 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:28:51.712  2853  2853 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:28:51.712  2853  2853 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:28:51.712  2853  2853 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:28:51.712  2853  2853 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 13:28:51.713  2853  2900 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 13:28:51.713  2853  2900 D BluetoothAdapterProperties: Setting state to 10
,08-29 13:28:51.714  2853  2900 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 13:28:51.714  2853  2900 I BluetoothAdapterState: Entering OffState
08-29 13:28:51.717   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 13:28:51.723  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-29 13:28:51.725  1713  2569 I iu.UploadsManager: num queued entries: 0
,08-29 13:28:51.725  1713  2569 I iu.UploadsManager: num updated entries: 0
,08-29 13:28:51.725  1713  2569 I iu.SyncManager: NEXT; no task
,08-29 13:28:51.731  2853  2853 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 13:28:51.732  2853  2853 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 13:28:51.732  2853  2853 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:28:51.732  2853  2901 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 13:28:51.735  2853  2901 D bt_stack_manager: event_clean_up_stack finished.
,08-29 13:28:51.739  2853  2853 I art     : System.exit called, status: 0
08-29 13:28:51.739  2853  2853 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:28:51.750  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:28:51.752  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:28:51.763  1713  3972 I SystemUpdateService: active receiver: enabled,
,08-29 13:28:51.770   872  2223 I ActivityManager: Start proc 3975:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 13:28:51.783  1713  3972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:28:51.807  1713  3972 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 13:28:51.808   872  1712 I ActivityManager: Process com.android.bluetooth (pid 2853) has died
08-29 13:28:51.808  1713  3972 I SystemUpdateService: now status is 0 (complete)
08-29 13:28:51.808  1713  3972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:28:51.808  1713  3972 I SystemUpdateService: file has been verified
08-29 13:28:51.810  1713  3972 I SystemUpdateService: OTA package size = 12249756
,08-29 13:28:51.822  1713  3972 I SystemUpdateService: showing system update notification
,08-29 13:28:51.832  1713  1713 D SystemUpdateService: onDestroy
,08-29 13:28:51.839  3975  3975 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 13:28:51.841  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:28:51.850  3975  3975 D SprintDMHelper: simOperator: 
,08-29 13:28:51.850  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:28:51.864   872  2224 I ActivityManager: Start proc 3989:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 13:28:51.914  3937  3968 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:28:51.964   872  2219 I ActivityManager: Start proc 4004:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 13:28:51.969   872  2219 I ActivityManager: Killing 2725:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 13:28:51.971   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b25d75:true
,08-29 13:28:52.062  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 13:28:52.124  4004  4004 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 13:28:52.124  4004  4004 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:28:52.124  4004  4004 I GAv4    :   adb logcat -s GAv4
,08-29 13:28:52.144  4004  4004 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:28:52.151  4004  4004 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:28:52.173  4004  4021 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:28:52.267  4004  4004 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 13:28:52.304  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 13:28:52.311  4004  4004 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5478-5481)
,08-29 13:28:52.311  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:28:52.321  4004  4004 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4201879}
,08-29 13:28:52.321  4004  4004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 13:28:52.321  4004  4004 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:28:52.328  4004  4004 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 13:28:52.329  4004  4004 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 13:28:52.352  4004  4004 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 13:28:52.365  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:28:52.365  4004  4004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:28:52.365  4004  4004 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:28:52.365  4004  4004 I Adreno  : Build Date                       : 10/20/15
08-29 13:28:52.365  4004  4004 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:28:52.365  4004  4004 I Adreno  : Local Branch                     : M14
08-29 13:28:52.365  4004  4004 I Adreno  : Remote Branch                    : 
08-29 13:28:52.365  4004  4004 I Adreno  : Remote Branch                    : 
08-29 13:28:52.365  4004  4004 I Adreno  : Reconstruct Branch               : 
,08-29 13:28:52.428  4004  4004 I NSApplication: Starting up...
,08-29 13:28:52.436  4004  4050 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 13:28:52.467   872  2006 I ActivityManager: Start proc 4055:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 13:28:52.468   872  2006 I ActivityManager: Killing 3177:android.process.acore/u0a5 (adj 15): empty #17
,08-29 13:28:52.546  4055  4055 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 13:28:52.739   872  1386 I ActivityManager: Killing 3734:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 13:28:52.846   872  2224 I ActivityManager: Start proc 4069:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 13:28:52.895  4069  4069 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-29 13:28:52.942  4069  4069 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 13:28:52.957   872  1712 I ActivityManager: Killing 3749:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 13:28:54.250   872  2006 D WifiService: setWifiEnabled: true pid=3850, uid=10000
,08-29 13:28:54.250   872  2006 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:28:54.264   872  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:28:54.272  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:54.272  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:54.272  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:54.274  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:54.277  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:54.277  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:28:54.278  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:54.278  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:28:54.309   872  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:28:54.310   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 13:28:54.311   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 13:28:54.312   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:28:54.312   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 13:28:54.312   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 13:28:54.313   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 13:28:54.327   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 13:28:54.328   872  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=12.00 delta 1000 -> 994
,08-29 13:28:54.329   372   870 D CommandListener: Setting iface cfg
,08-29 13:28:54.330   872  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '138 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 138 Failed to set address (No such device)'
08-29 13:28:54.330   872  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:28:54.339   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 13:28:54.339   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:28:54.346   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:28:54.377   872  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 13:28:54.380   872  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:28:54.416   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:28:54.418  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:28:54.842  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:28:54.883  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:28:54.884  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:28:54.891   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:28:54.899   872  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:28:54.899   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:28:54.900   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 13:28:54.928   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:28:54.949   372   870 D CommandListener: Setting iface cfg
,08-29 13:28:54.950   872  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 13:28:54.972   872  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 13:28:54.975   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:28:54.991   872  4102 D DhcpClient: Receive thread started
,08-29 13:28:55.076   872  1308 E native  : do suspend false
,08-29 13:28:55.097   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 13:28:55.154   872  4102 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-29 13:28:55.155   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-29 13:28:55.158   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:28:55.172   872  4102 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 13:28:55.173   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:28:55.178   372   870 D CommandListener: Setting iface cfg
,08-29 13:28:55.189   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 13:28:55.191   872  2094 D DhcpClient: Scheduling renewal in 86399s
,08-29 13:28:55.200   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 13:28:55.201   872  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 13:28:55.202   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:28:55.202   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 13:28:55.203   872  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:28:55.206   872  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 13:28:55.247   872  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 13:28:55.248   872  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 13:28:55.249   872  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-29 13:28:55.249   872  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-29 13:28:55.250   872  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 13:28:55.259   872  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 13:28:55.265   872  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 13:28:55.265   872  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-29 13:28:55.265   872  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-29 13:28:55.265   872  1310 D ConnectivityService:    accepting network in place of null
08-29 13:28:55.265   872  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 13:28:55.266   872  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -58]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:28:55.267   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:28:55.284   872  4101 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138454, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 13:28:55.307   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:28:55.347   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:28:55.352   872  4100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,08-29 13:28:55.355   872  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 13:28:55.355   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:28:55.365   872  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 13:28:55.370   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:28:55.379  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:55.380  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:28:55.380  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:55.380  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:55.383  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:28:55.383  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:28:55.383  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:55.384  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:28:55.393  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:28:55.397  1713  1713 D SystemUpdateService: onCreate
,08-29 13:28:55.399  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:28:55.403  1713  4113 I SystemUpdateService: active receiver: enabled
,08-29 13:28:55.409  1713  4113 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:28:55.413  1713  4113 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-29 13:28:55.413  1713  4113 I SystemUpdateService: now status is 0 (complete)
08-29 13:28:55.413  1713  4113 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:28:55.413  1713  4113 I SystemUpdateService: file has been verified
08-29 13:28:55.414  1713  4113 I SystemUpdateService: OTA package size = 12249756
,08-29 13:28:55.421  1713  4113 I SystemUpdateService: showing system update notification
,08-29 13:28:55.427  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:28:55.429  1713  2569 I iu.UploadsManager: num queued entries: 0
,08-29 13:28:55.429  1713  2569 I iu.UploadsManager: num updated entries: 0
08-29 13:28:55.430  1713  2569 I iu.SyncManager: NEXT; no task
08-29 13:28:55.431  1713  4117 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 13:28:55.431  1713  4117 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 13:28:55.432  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:28:55.432  1713  4117 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 13:28:55.433  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:28:55.434  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:28:55.436  1713  1713 D SystemUpdateService: onDestroy
,08-29 13:28:55.439  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:55.441  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:55.442   872  4100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 11:28:55 GMT], X-Android-Received-Millis=[1472470135441], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472470135407]}
08-29 13:28:55.443   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 13:28:55.443   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 13:28:55.443   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 13:28:55.444  3975  3975 D SprintDMHelper: simOperator: 
,08-29 13:28:55.444  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 13:28:55.444   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 13:28:55.473  1502  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:28:55.473  1502  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 13:28:55.473  1502  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:55.473  1502  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:55.493  1713  4117 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-29 13:28:55.537  3190  4126 V KeepSync: Connecting to GoogleApiClient
08-29 13:28:55.537   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 13:28:55.584  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 13:28:55.585  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 13:28:55.585  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:55.585  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:55.597  1713  4127 V BaseAuthAsyncOperation: access token request failed
,08-29 13:28:55.605  3190  4126 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 13:28:55.615  1502  3123 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 13:28:55.615  1502  3123 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 13:28:55.615  1502  3123 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:55.616  1502  3123 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:55.627  3145  4125 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 13:28:55.627  3145  4125 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jdm.a(PG:82)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jcs.o(PG:406)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jcn.a(PG:1379)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jcs.i(PG:143)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at blb.a(PG:3937)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at czp.a(PG:18188)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at czp.a(PG:9081)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at czq.run(PG:1686)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 13:28:55.627  3145  4125 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jdj.a(PG:4091)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jdj.a(PG:1125)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jdm.a(PG:77)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	... 12 more
08-29 13:28:55.627  3145  4125 E HttpOperation: Caused by: faj: BadAuthentication
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at fal.a(PG:38)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	at jdj.a(PG:4089)
08-29 13:28:55.627  3145  4125 E HttpOperation: 	... 14 more
,08-29 13:28:55.650  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 13:28:55.652  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 13:28:55.652  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:55.653  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:55.659  1502  2129 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 13:28:55.659  1502  2129 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 13:28:55.659  1502  2129 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:55.659  1502  2129 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:55.671  3190  4126 E KeepSync: IOException
08-29 13:28:55.671  3190  4126 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 13:28:55.671  3190  4126 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 13:28:55.671  3190  4126 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 13:28:55.671  3190  4126 E KeepSync: 	... 10 more
,08-29 13:28:55.671  3190  4126 W KeepSync: Sync result 2
,08-29 13:28:55.674   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 131773, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 13:28:55.679  3145  4125 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 13:28:55.679  3145  4125 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jdm.a(PG:82)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jcs.o(PG:406)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jcn.a(PG:1379)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jcs.i(PG:143)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at hec.a(PG:42)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at hee.a(PG:102)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at czr.a(PG:65)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at kka.a(PG:108)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at czp.a(PG:19176)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at czp.a(PG:9081)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at czq.run(PG:1686)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 13:28:55.679  3145  4125 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jdj.a(PG:4091)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jdj.a(PG:1125)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jdm.a(PG:77)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	... 15 more
08-29 13:28:55.679  3145  4125 E HttpOperation: Caused by: faj: BadAuthentication
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at fal.a(PG:38)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	at jdj.a(PG:4089)
08-29 13:28:55.679  3145  4125 E HttpOperation: 	... 17 more
,08-29 13:28:55.679  3145  4125 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 13:28:55.679  3145  4125 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at hec.a(PG:42)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at hee.a(PG:102)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at czr.a(PG:65)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at kka.a(PG:108)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	... 15 more
08-29 13:28:55.679  3145  4125 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at fal.a(PG:38)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 13:28:55.679  3145  4125 E ExperimentLoader: 	... 17 more
,08-29 13:28:55.722  2280  4120 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 13:28:55.780   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130950, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 13:28:56.355   872  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 13:28:57.181  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:28:57.236  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 13:28:57.236  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 13:28:57.236  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:28:57.236  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:28:57.260   872  1987 D WifiService: setWifiEnabled: false pid=3850, uid=10000
08-29 13:28:57.260   872  1987 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 13:28:57.260  3622  3622 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 13:28:57.261  3622  3622 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 13:28:57.261  3622  3622 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 13:28:57.277   872  1986 I ActivityManager: Killing 3567:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 13:28:57.294  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 13:28:57.300   872  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 13:28:57.300   872  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 13:28:57.301   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:28:57.303   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:28:57.312   872  2094 D DhcpClient: Clearing IP address
,08-29 13:28:57.313   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:28:57.319  1502  4128 V NativeCrypto: Read error: ssl=0x9add6000: I/O error during system call, Connection timed out
,08-29 13:28:57.321  1502  4128 V NativeCrypto: SSL shutdown failed: ssl=0x9add6000: I/O error during system call, Broken pipe
,08-29 13:28:57.322   872  1425 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-29 13:28:57.324   872  4100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-29 13:28:57.326   372   870 D CommandListener: Setting iface cfg
08-29 13:28:57.325   872  4100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
08-29 13:28:57.330   872  4102 D DhcpClient: Receive thread stopped
,08-29 13:28:57.335   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 13:28:57.335   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 13:28:57.339   395   395 E Parcel  : Reading a NULL string not supported here.
08-29 13:28:57.341   872  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-29 13:28:57.341   872  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 13:28:57.345   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 13:28:57.355   872  4100 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-29 13:28:57.376   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:28:57.399   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:28:57.400   872  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 13:28:57.400   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:28:57.400   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:28:57.404   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:28:57.406  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:57.406  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:28:57.406  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:57.407  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:57.407  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:57.407  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:57.407  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:57.407  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:28:57.414   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:28:57.419  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:57.419  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:28:57.419  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:28:57.419  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:28:57.420   872  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 13:28:57.420  1886  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:28:57.420  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:28:57.420  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:28:57.421  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:28:57.421  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:28:57.424  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:28:57.428  1713  1713 D SystemUpdateService: onCreate
,08-29 13:28:57.431  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:28:57.440  1713  4139 I SystemUpdateService: active receiver: enabled
,08-29 13:28:57.442  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:28:57.444  1713  2569 I iu.UploadsManager: num queued entries: 0
,08-29 13:28:57.444  1713  2569 I iu.UploadsManager: num updated entries: 0
,08-29 13:28:57.445  1713  2569 I iu.SyncManager: NEXT; no task
,08-29 13:28:57.448  1713  4139 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:28:57.450  1713  4139 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 13:28:57.451  1713  4139 I SystemUpdateService: now status is 0 (complete)
08-29 13:28:57.451  1713  4139 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 13:28:57.451  1713  4139 I SystemUpdateService: file has been verified
08-29 13:28:57.451  1713  4139 I SystemUpdateService: OTA package size = 12249756
,08-29 13:28:57.453  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:28:57.455  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 13:28:57.457  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:28:57.461  3975  3975 D SprintDMHelper: simOperator: 
,08-29 13:28:57.461  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 13:28:57.494  2280  4143 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 13:28:57.503  1713  4139 I SystemUpdateService: showing system update notification
,08-29 13:28:57.509   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-29 13:28:57.511   872  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 13:28:57.511   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 13:28:57.522  1713  1713 D SystemUpdateService: onDestroy
,08-29 13:29:00.300   872   889 I ActivityManager: Start proc 4147:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 13:29:00.398  4147  4147 D AdapterServiceConfig: Adding HeadsetService
,08-29 13:29:00.398  4147  4147 D AdapterServiceConfig: Adding A2dpService
08-29 13:29:00.399  4147  4147 D AdapterServiceConfig: Adding HidService
,08-29 13:29:00.399  4147  4147 D AdapterServiceConfig: Adding HealthService
08-29 13:29:00.399  4147  4147 D AdapterServiceConfig: Adding PanService
08-29 13:29:00.399  4147  4147 D AdapterServiceConfig: Adding GattService
,08-29 13:29:00.399  4147  4147 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:29:00.416   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e32a92:true
,08-29 13:29:00.418  4147  4147 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 13:29:00.426  4147  4159 I BluetoothAdapterState: Entering OffState
,08-29 13:29:00.426  4147  4147 I bt_bluedroid: init
,08-29 13:29:00.430  4147  4160 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 13:29:00.430  4147  4160 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:29:00.430  4147  4160 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:29:00.430  4147  4160 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 13:29:00.431  4147  4147 I bt_bluedroid: get_profile_interface socket
,08-29 13:29:00.434  4147  4147 I bt_bluedroid: get_profile_interface sdp
,08-29 13:29:00.438  4147  4158 I bt_bluedroid: config_hci_snoop_log
,08-29 13:29:00.442   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:29:00.442  4147  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:29:00.447  4147  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:29:00.452  4147  4159 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 13:29:00.452  4147  4159 D BluetoothAdapterProperties: Setting state to 14
08-29 13:29:00.452  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:29:00.455  4147  4159 D BluetoothBondStateMachine: make
,08-29 13:29:00.459  4147  4164 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:29:00.465  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:29:00.467  4147  4147 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 13:29:00.471  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77,
08-29 13:29:00.472  4147  4147 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:29:00.472  4147  4147 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:29:00.472  4147  4147 D BtGatt.GattService: start()
08-29 13:29:00.473  4147  4147 I bt_bluedroid: get_profile_interface gatt
,08-29 13:29:00.474  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
08-29 13:29:00.474  4147  4147 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:29:00.487  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:00.487  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:00.487  4147  4147 V BluetoothAdapterState: isBleTurningOn()=true
08-29 13:29:00.487  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:00.488  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 13:29:00.489  4147  4159 I bt_bluedroid: enable
08-29 13:29:00.489  4147  4160 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 13:29:00.489  4147  4160 I bt_hci  : start_up
,08-29 13:29:00.499  4147  4160 I bt_vendor: alloc value 0xb39c0189
,08-29 13:29:00.499  4147  4160 I bt_vendor: init
08-29 13:29:00.499  4147  4160 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 13:29:00.499  4147  4160 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:29:00.608  4147  4160 D bt_hci  : start_up starting async portion
,08-29 13:29:00.608  4147  4167 I bt_hci  : event_finish_startup
,08-29 13:29:00.609  4147  4167 I bt_hci_h4: hal_open
08-29 13:29:00.609  4147  4167 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:29:00.621  4147  4167 I bt_userial_vendor: device fd = 51 open
,08-29 13:29:00.652  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:29:00.682  4147  4167 D bt_hwcfg: Chipset BCM4354A2
,08-29 13:29:00.682  4147  4167 D bt_hwcfg: Target name = [BCM4354A2]
08-29 13:29:00.683  4147  4167 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:29:01.347  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:29:01.349  4147  4167 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 13:29:01.349  4147  4167 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:29:01.467  4147  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:29:01.468  4147  4167 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:29:01.497  4147  4167 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:29:01.497  4147  4167 I bt_vendor: firmware callback
08-29 13:29:01.497  4147  4167 I bt_hci  : firmware_config_callback
,08-29 13:29:01.510  4147  4169 I bt_btu  : btu_task pending for preload complete event
,08-29 13:29:01.510  4147  4169 I bt_btu_task: Bluetooth chip preload is complete
08-29 13:29:01.511  4147  4169 I bt_btu  : btu_task received preload complete event
,08-29 13:29:01.522  4147  4169 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:29:01.522  4147  4169 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:29:01.522  4147  4169 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:29:01.522  4147  4169 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 13:29:01.523  4147  4169 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:29:01.523  4147  4169 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 13:29:01.523  4147  4169 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:29:01.524  4147  4169 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 13:29:01.525  4147  4169 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:29:01.525  4147  4169 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:29:01.525  4147  4169 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 13:29:01.527  4147  4169 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:29:01.527  4147  4169 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:29:01.528  4147  4169 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 13:29:01.528  4147  4169 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:29:01.661  4147  4169 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393dd9d
,08-29 13:29:01.662  4147  4169 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393dd9d 
,08-29 13:29:01.672  4147  4163 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:29:01.675  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:29:01.676  4147  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:29:01.679  4147  4163 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 13:29:01.683  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:29:01.683  4147  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:29:01.686  4147  4163 D bt_hci  : do_postload posting postload work item
08-29 13:29:01.687  4147  4167 I bt_hci  : event_postload
08-29 13:29:01.687  4147  4167 I bt_vendor: sco_config_cb
08-29 13:29:01.687  4147  4167 I bt_hci  : sco_config_callback postload finished.
,08-29 13:29:01.688  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:01.692  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:01.695  4147  4163 D bt_bte_conf: Device ID record 1 : primary
,08-29 13:29:01.695  4147  4163 D bt_bte_conf:   vendorId            = 000f
,08-29 13:29:01.695  4147  4167 I bt_vendor: low_power_mode_cb
08-29 13:29:01.695  4147  4163 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 13:29:01.696  4147  4163 D bt_bte_conf:   product             = 1200
,08-29 13:29:01.696  4147  4163 D bt_bte_conf:   version             = 1436
08-29 13:29:01.696  4147  4163 D bt_bte_conf:   clientExecutableURL = 
,08-29 13:29:01.696  4147  4163 D bt_bte_conf:   serviceDescription  = 
,08-29 13:29:01.697  4147  4163 D bt_bte_conf:   documentationURL    = 
08-29 13:29:01.697  4147  4163 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:29:01.697  4147  4160 D bt_stack_manager: event_start_up_stack finished
08-29 13:29:01.699  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
08-29 13:29:01.699  4147  4159 D BluetoothAdapterProperties: Setting state to 15
,08-29 13:29:01.700  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 13:29:01.703  4147  4159 I BluetoothAdapterState: Entering BleOnState
,08-29 13:29:01.713  4147  4159 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 13:29:01.713  4147  4159 D BluetoothAdapterProperties: Setting state to 11
08-29 13:29:01.713  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 13:29:01.722  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:01.729  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:01.734  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:01.731  4147  4147 D HeadsetService: Received start request. Starting profile...
,08-29 13:29:01.738  4147  4147 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 13:29:01.738  4147  4147 D HeadsetStateMachine: make
,08-29 13:29:01.740  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:29:01.747  4147  4147 D HeadsetStateMachine: max_hf_connections = 1
,08-29 13:29:01.747  4147  4147 I bt_bluedroid: get_profile_interface handsfree
,08-29 13:29:01.748  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 13:29:01.748  4147  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 13:29:01.757  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:01.758  4147  4147 D A2dpService: Received start request. Starting profile...
,08-29 13:29:01.759  4147  4147 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 13:29:01.760  4147  4147 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:29:01.776  4147  4147 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:29:01.777  4147  4147 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 13:29:01.777  4147  4147 D A2dpStateMachine: make
,08-29 13:29:01.778  4147  4147 I bt_bluedroid: get_profile_interface a2dp
,08-29 13:29:01.779  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 13:29:01.782  4147  4178 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:29:01.784  4147  4147 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:29:01.787  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:01.788  4147  4147 D HidService: Received start request. Starting profile...
08-29 13:29:01.789  4147  4147 I bt_bluedroid: get_profile_interface hidhost
08-29 13:29:01.789  4147  4163 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391f3e5
08-29 13:29:01.789  4147  4147 D HidService: setHidService(): set to: null
08-29 13:29:01.789  3921  3921 D BluetoothInputDevice: Proxy object connected
08-29 13:29:01.789  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 13:29:01.789  3921  3921 D HidProfile: Bluetooth service connected
,08-29 13:29:01.790  4147  4147 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:29:01.791  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
08-29 13:29:01.791  4147  4147 D HealthService: Received start request. Starting profile...
,08-29 13:29:01.791  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:29:01.793  4147  4147 I bt_bluedroid: get_profile_interface health
,08-29 13:29:01.794  4147  4147 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:29:01.794  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:01.795  4147  4147 D PanService: Received start request. Starting profile...
,08-29 13:29:01.796  3921  3921 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:29:01.796  4147  4147 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:29:01.796  4147  4147 I bt_bluedroid: get_profile_interface pan
08-29 13:29:01.796  4147  4163 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:29:01.796  3921  3921 D PanProfile: Bluetooth service connected
,08-29 13:29:01.801  4147  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:01.803  4147  4147 D BluetoothMapService: Received start request. Starting profile...
,08-29 13:29:01.803  4147  4147 D BluetoothMapService: start()
08-29 13:29:01.805  4147  4147 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 13:29:01.807  4147  4147 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 13:29:01.807  4147  4147 D BluetoothMapAppObserver: createReceiver()
,08-29 13:29:01.803  3921  3921 D BluetoothMap: Proxy object connected
,08-29 13:29:01.809  3921  3921 D MapProfile: Bluetooth service connected
08-29 13:29:01.809  4147  4147 D BluetoothMapAppObserver: initObservers()
,08-29 13:29:01.809  3921  3921 D BluetoothMap: getConnectedDevices()
,08-29 13:29:01.809  4147  4147 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 13:29:01.810  3921  3921 D BluetoothMap: Bluetooth is Not enabled
,08-29 13:29:01.826  4147  4176 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 13:29:01.826  4147  4147 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:01.826  4147  4147 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:01.826  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:01.826  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:01.829  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:01.829  4147  4147 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:01.829  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:01.829  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:01.830  4147  4147 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:01.830  4147  4147 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:01.830  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:01.830  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:01.831  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:01.832  4147  4147 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:01.832  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:01.832  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:01.832  4147  4147 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:01.833  4147  4147 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:01.833  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:01.833  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:01.834  4147  4147 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:01.834  4147  4147 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:01.834  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:29:01.834  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:01.835  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:29:01.836  4147  4159 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:29:01.836  4147  4159 D BluetoothAdapterProperties: State =  11
,08-29 13:29:01.837  4147  4163 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:29:01.837  4147  4159 D BluetoothAdapterProperties: Setting state to 12
08-29 13:29:01.838  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 13:29:01.838  4147  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:29:01.838   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:29:01.839   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:29:01.840  3921  3931 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:29:01.840  4147  4159 I BluetoothAdapterState: Entering OnState
,08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:01.842  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:29:01.841  3921  3932 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:29:01.842   872   872 D BluetoothA2dp: Proxy object connected
,08-29 13:29:01.844  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:01.844  4147  4147 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:29:01.846  4147  4147 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 13:29:01.847  4147  4147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:01.849  2364  2377 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:01.849  2364  2375 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:01.850  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:29:01.851  2364  2543 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:29:01.851  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:29:01.852  2364  2364 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:29:01.853  2364  2364 D PanProfile: Bluetooth service connected
,08-29 13:29:01.853  3921  3931 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:29:01.853  1950  2122 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:01.854  2364  2375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:29:01.855  3921  3932 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:29:01.855   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:01.855  2364  2364 D BluetoothA2dp: Proxy object connected
08-29 13:29:01.856  2364  2543 D BluetoothMap: onBluetoothStateChange: up=true,
,08-29 13:29:01.857  2364  2364 D BluetoothMap: Proxy object connected
08-29 13:29:01.857  2364  2364 D MapProfile: Bluetooth service connected
,08-29 13:29:01.857  2364  2364 D BluetoothMap: getConnectedDevices()
08-29 13:29:01.857   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:01.857  2364  2375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:29:01.858  4147  4147 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:01.859  2364  2364 D BluetoothInputDevice: Proxy object connected
,08-29 13:29:01.859  2364  2364 D HidProfile: Bluetooth service connected
08-29 13:29:01.860   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:29:01.862  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:01.862  4147  4147 D ObexServerSockets: Succeed to create listening sockets 
,08-29 13:29:01.863  4147  4147 D ObexServerSockets0: startAccept()
,08-29 13:29:01.863  4147  4147 D ObexServerSockets0: prepareForNewConnect()
08-29 13:29:01.864  4147  4147 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 13:29:01.865  4147  4147 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 13:29:01.865  4147  4147 D BluetoothMapService: onReceive
08-29 13:29:01.865  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:01.865  4147  4147 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:29:01.865  4147  4147 D BluetoothMapService: STATE_ON
,08-29 13:29:01.867  4147  4185 D ObexServerSockets0: Accepting socket connection...
,08-29 13:29:01.868  4147  4184 D ObexServerSockets0: Accepting socket connection...
08-29 13:29:01.868  3921  3921 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 13:29:01.872  3921  3921 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 13:29:01.877  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:29:01.878  3921  3921 D BluetoothA2dp: Proxy object connected
,08-29 13:29:01.882  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:29:01.883  3921  3921 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:29:01.889  3921  3921 D BluetoothPbap: Proxy object connected
,08-29 13:29:01.889  3921  3921 D PbapServerProfile: Bluetooth service connected
08-29 13:29:01.889  2364  2364 D BluetoothPbap: Proxy object connected
08-29 13:29:01.889  2364  2364 D PbapServerProfile: Bluetooth service connected
08-29 13:29:01.890  4147  4147 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 13:29:01.890  4147  4147 D ObexServerSockets0: prepareForNewConnect()
,08-29 13:29:01.896  4147  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:01.911  4147  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:01.912  4147  4194 I BtOppRfcommListener: Accept thread started.
,08-29 13:29:01.940   872   872 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.941  1950  1962 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.941  2364  2375 D BluetoothHeadset: Proxy object connected
08-29 13:29:01.942  2364  2364 D HeadsetProfile: Bluetooth service connected
,08-29 13:29:01.942   872   872 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.942   872   872 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.949  2364  2377 D BluetoothHeadset: Proxy object connected
08-29 13:29:01.949  2364  2364 D HeadsetProfile: Bluetooth service connected
,08-29 13:29:01.954  1950  2078 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.956   872   889 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.957   872   889 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.975  3921  3931 D BluetoothHeadset: Proxy object connected
,08-29 13:29:01.976  3921  3921 D HeadsetProfile: Bluetooth service connected
,08-29 13:29:03.268   872  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-29 13:29:03.277  4147  4159 D BluetoothAdapterState: Current state: ON, message: 23,
,08-29 13:29:03.277  4147  4159 D BluetoothAdapterProperties: Setting state to 13
,08-29 13:29:03.277  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 13:29:03.279  4147  4159 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 13:29:03.283  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:29:03.292  4147  4147 D BluetoothMapService: onReceive
,08-29 13:29:03.292  4147  4147 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:29:03.292  4147  4147 D BluetoothMapService: STATE_TURNING_OFF
,08-29 13:29:03.295  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:29:03.295  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:29:03.296  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:03.296  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:03.296  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 13:29:03.293  4147  4147 D BluetoothMapService: MAP Service closeService in
08-29 13:29:03.299  4147  4147 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 13:29:03.299  4147  4147 D ObexServerSockets0: shutdown(block = true)
,08-29 13:29:03.300  4147  4184 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 13:29:03.301  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:29:03.301  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:29:03.302  4147  4147 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:29:03.303  4147  4185 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 13:29:03.304  4147  4172 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 13:29:03.305  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:29:03.305  4147  4147 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:03.305  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:03.305  4147  4147 I BtOppRfcommListener: stopping Accept Thread
08-29 13:29:03.306  3850  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:29:03.306  4147  4194 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:29:03.306  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:03.306  4147  4194 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:29:03.308  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:03.312  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:03.312  4147  4147 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:29:03.316   872   872 D BluetoothHeadset: Proxy object disconnected
,08-29 13:29:03.317  1950  2122 D BluetoothHeadset: Proxy object disconnected
08-29 13:29:03.317  2364  2375 D BluetoothHeadset: Proxy object disconnected
08-29 13:29:03.318  2364  2364 D HeadsetProfile: Bluetooth service disconnected
,08-29 13:29:03.318  4147  4147 D A2dpService: Received stop request...Stopping profile...
08-29 13:29:03.318   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 13:29:03.318   872   872 D BluetoothHeadset: Proxy object disconnected
08-29 13:29:03.318  4147  4178 D A2dpStateMachine: Exit Disconnected: -1
,08-29 13:29:03.319  3921  3931 D BluetoothHeadset: Proxy object disconnected
08-29 13:29:03.320  2364  2364 D BluetoothA2dp: Proxy object disconnected
08-29 13:29:03.320   872   872 D BluetoothA2dp: Proxy object disconnected
08-29 13:29:03.320  4147  4147 D HidService: Received stop request...Stopping profile...
08-29 13:29:03.320  4147  4147 D HidService: Stopping Bluetooth HidService
,08-29 13:29:03.321  2364  2364 D BluetoothInputDevice: Proxy object disconnected
08-29 13:29:03.321  2364  2364 D HidProfile: Bluetooth service disconnected
08-29 13:29:03.322  4147  4147 D HealthService: Received stop request...Stopping profile...
08-29 13:29:03.323  4147  4147 D PanService: Received stop request...Stopping profile...
08-29 13:29:03.324  2364  2364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:29:03.324  2364  2364 D PanProfile: Bluetooth service disconnected
08-29 13:29:03.325  3921  3921 D DockEventReceiver: finishStartingService: stopping service
08-29 13:29:03.327  3921  3921 D HeadsetProfile: Bluetooth service disconnected
08-29 13:29:03.328  3921  3921 D BluetoothA2dp: Proxy object disconnected
,08-29 13:29:03.328  3921  3921 D BluetoothInputDevice: Proxy object disconnected
08-29 13:29:03.328  3921  3921 D HidProfile: Bluetooth service disconnected
08-29 13:29:03.328  3921  3921 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:29:03.328  4147  4147 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:29:03.328  3921  3921 D PanProfile: Bluetooth service disconnected
08-29 13:29:03.328  4147  4147 D BluetoothMapService: stop()
08-29 13:29:03.330  4147  4147 D BluetoothMapAppObserver: deinitObservers()
,08-29 13:29:03.330  4147  4147 D BluetoothMapAppObserver: removeReceiver()
08-29 13:29:03.330  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:29:03.332  3921  3921 D BluetoothMap: Proxy object disconnected
08-29 13:29:03.333  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.333  3921  3921 D MapProfile: Bluetooth service disconnected
08-29 13:29:03.333  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.333  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:03.333  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:03.334  2364  2364 D BluetoothMap: Proxy object disconnected
08-29 13:29:03.334  2364  2364 D MapProfile: Bluetooth service disconnected
08-29 13:29:03.334  4147  4147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:29:03.334  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 13:29:03.335  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:29:03.335  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:29:03.335  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:29:03.336  4147  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
,08-29 13:29:03.336  4147  4147 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:29:03.337  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.337  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.337  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:03.337  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:03.338  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 13:29:03.338  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:29:03.338  4147  4169 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:29:03.338  4147  4169 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:29:03.338  4147  4169 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:29:03.338  4147  4169 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:29:03.338  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 13:29:03.339  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.339  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.339  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:03.339  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:03.339  4147  4147 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:29:03.339  4147  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 13:29:03.340  4147  4147 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:29:03.340  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.340  4147  4147 V BluetoothAdapterState: isTurningOn()=false
,08-29 13:29:03.340  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:03.340  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:03.340  4147  4147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:29:03.340  4147  4163 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 13:29:03.341  4147  4147 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 13:29:03.341  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.341  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.341  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:03.341  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:03.342  4147  4147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 13:29:03.342  4147  4147 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 13:29:03.344  3921  3921 D BluetoothPbap: Proxy object disconnected
,08-29 13:29:03.344  3921  3921 D PbapServerProfile: Bluetooth service disconnected
08-29 13:29:03.344  2364  2364 D BluetoothPbap: Proxy object disconnected
08-29 13:29:03.344  2364  2364 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:29:03.345  4147  4147 D BluetoothMapService: MAP Service closeService in
,08-29 13:29:03.345  4147  4147 V BluetoothAdapterState: isTurningOff()=true
08-29 13:29:03.345  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.345  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:29:03.345  4147  4147 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:03.345  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 13:29:03.345  4147  4159 D BluetoothAdapterProperties: Setting state to 15
08-29 13:29:03.345  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 13:29:03.346  4147  4147 D BluetoothMapService: cleanup()
08-29 13:29:03.346  4147  4147 D BluetoothMapService: MAP Service closeService in
,08-29 13:29:03.347  4147  4159 I BluetoothAdapterState: Entering BleOnState
08-29 13:29:03.348   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:29:03.348   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:29:03.348  3921  3931 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:29:03.349  3921  4197 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:29:03.350  2364  2375 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:29:03.350  2364  2543 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:29:03.351  2364  2377 D BluetoothPan: onBluetoothStateChange on: false
08-29 13:29:03.351  3921  3932 D BluetoothPan: onBluetoothStateChange on: false
,08-29 13:29:03.352  1950  1962 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:29:03.352  2364  2375 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:29:03.353  3921  3931 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:29:03.353   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:29:03.353  2364  2543 D BluetoothMap: onBluetoothStateChange: up=false
08-29 13:29:03.354  3921  4197 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:29:03.354  3921  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 13:29:03.355   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 13:29:03.355  2364  2377 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:29:03.356  4147  4159 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 13:29:03.356  4147  4159 D BluetoothAdapterProperties: Setting state to 16
08-29 13:29:03.356  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 13:29:03.356  4147  4159 D BluetoothAdapterProperties: onBleDisable
,08-29 13:29:03.358  4147  4160 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-29 13:29:03.359  4147  4169 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:29:03.359  4147  4169 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 13:29:03.360  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:03.360  4147  4163 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:29:03.361  4147  4159 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:29:03.362  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:03.363  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:03.363  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 13:29:03.366  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:03.367  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:29:03.369  3921  3921 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:29:03.559  4147  4163 I bt_hci  : shut_down
,08-29 13:29:03.570  4147  4167 I bt_vendor: low_power_mode_cb
,08-29 13:29:03.570  4147  4167 D bt_hwcfg: hw_epilog_process
,08-29 13:29:03.590  4147  4167 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 13:29:03.590  4147  4167 I bt_vendor: epilog_cb
08-29 13:29:03.590  4147  4167 I bt_hci  : epilog_finished_callback
,08-29 13:29:03.597  4147  4163 I bt_hci_h4: hal_close
,08-29 13:29:03.599  4147  4163 I bt_userial_vendor: device fd = 51 close
,08-29 13:29:03.724  4147  4160 D bt_stack_manager: event_shut_down_stack finished.
,08-29 13:29:03.725  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 13:29:03.731  4147  4159 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 13:29:03.732  4147  4147 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 13:29:03.734  4147  4147 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 13:29:03.735  4147  4147 D BtGatt.GattService: stop()
08-29 13:29:03.735  4147  4147 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:29:03.740  4147  4147 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:03.740  4147  4147 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:03.740  4147  4147 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:29:03.741  4147  4147 V BluetoothAdapterState: isBleTurningOff()=true
08-29 13:29:03.741  4147  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 13:29:03.742  4147  4159 D BluetoothAdapterProperties: Setting state to 10
08-29 13:29:03.742  4147  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 13:29:03.744  4147  4159 I BluetoothAdapterState: Entering OffState
,08-29 13:29:03.747   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 13:29:03.774  4147  4147 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 13:29:03.775  4147  4147 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 13:29:03.775  4147  4160 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 13:29:03.782  4147  4160 D bt_stack_manager: event_clean_up_stack finished.
,08-29 13:29:03.782  4147  4147 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:29:03.787  4147  4147 I art     : System.exit called, status: 0
,08-29 13:29:03.788  4147  4147 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:29:03.842   872  1712 I ActivityManager: Process com.android.bluetooth (pid 4147) has died
,08-29 13:29:06.274  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:29:06.274  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:09.282  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:09.282  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@384e2c5 added. We now have 6 listener(s)
08-29 13:29:09.283  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:09.287  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:29:09.287  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60ac41a added. We now have 7 listener(s)
08-29 13:29:09.287  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:09.289  3850  3900 I System.out: IsBluetoothEnabled
,08-29 13:29:09.301  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:09.347   872   889 I ActivityManager: Start proc 4206:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 13:29:09.501  4206  4206 D AdapterServiceConfig: Adding HeadsetService
,08-29 13:29:09.502  4206  4206 D AdapterServiceConfig: Adding A2dpService
08-29 13:29:09.502  4206  4206 D AdapterServiceConfig: Adding HidService
,08-29 13:29:09.502  4206  4206 D AdapterServiceConfig: Adding HealthService
08-29 13:29:09.502  4206  4206 D AdapterServiceConfig: Adding PanService
08-29 13:29:09.503  4206  4206 D AdapterServiceConfig: Adding GattService
,08-29 13:29:09.503  4206  4206 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 13:29:09.522   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e429687:true
,08-29 13:29:09.522  4206  4206 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 13:29:09.527  4206  4206 I bt_bluedroid: init
,08-29 13:29:09.528  4206  4218 I BluetoothAdapterState: Entering OffState
,08-29 13:29:09.532  4206  4219 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:29:09.532  4206  4219 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:29:09.532  4206  4219 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 13:29:09.532  4206  4219 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 13:29:09.533  4206  4206 I bt_bluedroid: get_profile_interface socket
,08-29 13:29:09.535  4206  4206 I bt_bluedroid: get_profile_interface sdp
,08-29 13:29:09.539  4206  4222 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:29:09.541  4206  4217 I bt_bluedroid: config_hci_snoop_log
,08-29 13:29:09.542  4206  4222 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:29:09.544   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:29:09.554  4206  4218 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 13:29:09.555  4206  4218 D BluetoothAdapterProperties: Setting state to 14
08-29 13:29:09.555  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 13:29:09.560  4206  4218 D BluetoothBondStateMachine: make
,08-29 13:29:09.566  4206  4218 I BluetoothAdapterState: Entering PendingCommandState
,08-29 13:29:09.566  4206  4223 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:29:09.568  4206  4206 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 13:29:09.572  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:09.573  4206  4206 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:29:09.573  4206  4206 D BtGatt.GattService: Received start request. Starting profile...
08-29 13:29:09.574  4206  4206 D BtGatt.GattService: start()
08-29 13:29:09.574  4206  4206 I bt_bluedroid: get_profile_interface gatt
,08-29 13:29:09.575  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
08-29 13:29:09.575  4206  4206 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:29:09.586  4206  4206 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:09.586  4206  4206 V BluetoothAdapterState: isTurningOn()=false
08-29 13:29:09.587  4206  4206 V BluetoothAdapterState: isBleTurningOn()=true
08-29 13:29:09.587  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:09.587  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 13:29:09.588  4206  4218 I bt_bluedroid: enable
08-29 13:29:09.588  4206  4219 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 13:29:09.589  4206  4219 I bt_hci  : start_up
,08-29 13:29:09.609  4206  4219 I bt_vendor: alloc value 0xb39c0189
,08-29 13:29:09.609  4206  4219 I bt_vendor: init
08-29 13:29:09.610  4206  4219 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 13:29:09.611  4206  4219 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 13:29:09.718  4206  4219 D bt_hci  : start_up starting async portion
,08-29 13:29:09.718  4206  4226 I bt_hci  : event_finish_startup
,08-29 13:29:09.719  4206  4226 I bt_hci_h4: hal_open
08-29 13:29:09.719  4206  4226 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 13:29:09.730  4206  4226 I bt_userial_vendor: device fd = 51 open
,08-29 13:29:09.761  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 13:29:09.792  4206  4226 D bt_hwcfg: Chipset BCM4354A2
,08-29 13:29:09.792  4206  4226 D bt_hwcfg: Target name = [BCM4354A2]
08-29 13:29:09.794  4206  4226 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 13:29:10.013   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 13:29:10.025  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-29 13:29:10.034   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 13:29:10.034   872   892 I Adreno  : Build Date                       : 10/20/15
08-29 13:29:10.034   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 13:29:10.034   872   892 I Adreno  : Local Branch                     : M14
08-29 13:29:10.034   872   892 I Adreno  : Remote Branch                    : 
08-29 13:29:10.034   872   892 I Adreno  : Remote Branch                    : 
08-29 13:29:10.034   872   892 I Adreno  : Reconstruct Branch               : 
,08-29 13:29:10.080   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (296 us)
,08-29 13:29:10.473  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 13:29:10.476  4206  4226 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 13:29:10.476  4206  4226 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 13:29:10.594  4206  4226 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
08-29 13:29:10.598  4206  4226 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 13:29:10.623  4206  4226 I bt_hwcfg: vendor lib fwcfg completed
,08-29 13:29:10.625  4206  4226 I bt_vendor: firmware callback
08-29 13:29:10.625  4206  4226 I bt_hci  : firmware_config_callback
,08-29 13:29:10.637  4206  4230 I bt_btu  : btu_task pending for preload complete event
,08-29 13:29:10.640  4206  4230 I bt_btu_task: Bluetooth chip preload is complete
,08-29 13:29:10.642  4206  4230 I bt_btu  : btu_task received preload complete event
,08-29 13:29:10.653  4206  4230 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:29:10.653  4206  4230 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 13:29:10.654  4206  4230 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 13:29:10.654  4206  4230 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:29:10.654  4206  4230 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:29:10.654  4206  4230 I         : BTE_InitTraceLevels -- TRC_A2D
,08-29 13:29:10.655  4206  4230 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:29:10.655  4206  4230 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:29:10.655  4206  4230 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:29:10.655  4206  4230 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 13:29:10.656  4206  4230 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:29:10.659  4206  4230 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:29:10.659  4206  4230 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:29:10.659  4206  4230 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:29:10.659  4206  4230 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 13:29:10.708  3850  3850 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:29:10.708  3850  3850 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 13:29:10.767   872   886 W Looper  : Ignoring unexpected epoll events 0x1 on fd 187 that is no longer registered.
08-29 13:29:10.767  3850  3850 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a78913 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@719b4b, 16908290=android.view.AbsSavedState$1@719b4b}, android:focusedViewId=100}]}]
08-29 13:29:10.767  3850  3850 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 13:29:10.767  3850  3850 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:29:10.767  3850  3850 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 13:29:10.768   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 13:29:10.777   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 13:29:10.782   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 13:29:10.786   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-29 13:29:10.786   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 13:29:10.796  4206  4230 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393dd9d
,08-29 13:29:10.796  4206  4230 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393dd9d 
,08-29 13:29:10.805  4206  4222 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 13:29:10.806  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 13:29:10.806  4206  4222 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 13:29:10.807  4206  4222 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 13:29:10.808  4206  4222 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:29:10.808  4206  4222 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:29:10.808  4206  4222 D bt_hci  : do_postload posting postload work item
,08-29 13:29:10.808  4206  4226 I bt_hci  : event_postload
,08-29 13:29:10.808  4206  4226 I bt_vendor: sco_config_cb,
,08-29 13:29:10.809  4206  4226 I bt_hci  : sco_config_callback postload finished.
,08-29 13:29:10.810  4206  4222 D bt_bte_conf: Device ID record 1 : primary
,08-29 13:29:10.810  4206  4222 D bt_bte_conf:   vendorId            = 000f
,08-29 13:29:10.810  4206  4222 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 13:29:10.810  4206  4222 D bt_bte_conf:   product             = 1200
,08-29 13:29:10.810  4206  4222 D bt_bte_conf:   version             = 1436
08-29 13:29:10.810  4206  4222 D bt_bte_conf:   clientExecutableURL = 
,08-29 13:29:10.810  4206  4222 D bt_bte_conf:   serviceDescription  = 
08-29 13:29:10.810  4206  4222 D bt_bte_conf:   documentationURL    = 
,08-29 13:29:10.810  4206  4222 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:29:10.810  4206  4219 D bt_stack_manager: event_start_up_stack finished
08-29 13:29:10.810  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:10.810  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 13:29:10.811  4206  4218 D BluetoothAdapterProperties: Setting state to 15
08-29 13:29:10.811  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 13:29:10.811  4206  4218 I BluetoothAdapterState: Entering BleOnState
08-29 13:29:10.813  4206  4218 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 13:29:10.813  4206  4218 D BluetoothAdapterProperties: Setting state to 11
08-29 13:29:10.813  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 13:29:10.817  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
08-29 13:29:10.818  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:10.819  4206  4206 D HeadsetService: Received start request. Starting profile...
08-29 13:29:10.819  4206  4226 I bt_vendor: low_power_mode_cb
08-29 13:29:10.822  4206  4206 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:29:10.822  4206  4206 D HeadsetStateMachine: make
08-29 13:29:10.831  4206  4206 D HeadsetStateMachine: max_hf_connections = 1
08-29 13:29:10.831  4206  4206 I bt_bluedroid: get_profile_interface handsfree
,08-29 13:29:10.832  4206  4218 I BluetoothAdapterState: Entering PendingCommandState
08-29 13:29:10.832  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 13:29:10.832  4206  4222 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 13:29:10.833  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:10.834  4206  4206 D A2dpService: Received start request. Starting profile...
08-29 13:29:10.834  4206  4206 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 13:29:10.835  4206  4206 I bt_bluedroid: get_profile_interface avrcp
,08-29 13:29:10.840  4206  4206 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:29:10.840  4206  4206 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:29:10.840  4206  4206 D A2dpStateMachine: make
,08-29 13:29:10.841  4206  4206 I bt_bluedroid: get_profile_interface a2dp
,08-29 13:29:10.841  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 13:29:10.843  4206  4240 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:29:10.845  4206  4206 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:29:10.845  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:10.846  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:29:10.846  4206  4206 D HidService: Received start request. Starting profile...
,08-29 13:29:10.847  4206  4206 I bt_bluedroid: get_profile_interface hidhost
08-29 13:29:10.847  4206  4222 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391f3e5
,08-29 13:29:10.847  4206  4222 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 13:29:10.847  4206  4206 D HidService: setHidService(): set to: null
08-29 13:29:10.847  4206  4206 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 13:29:10.848  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:10.848  4206  4206 D HealthService: Received start request. Starting profile...
08-29 13:29:10.850  4206  4206 I bt_bluedroid: get_profile_interface health
,08-29 13:29:10.851  4206  4206 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:29:10.852  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:10.852  4206  4206 D PanService: Received start request. Starting profile...
,08-29 13:29:10.852  4206  4206 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:29:10.852  4206  4206 I bt_bluedroid: get_profile_interface pan
,08-29 13:29:10.853  4206  4222 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:29:10.855  4206  4206 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:10.856  4206  4206 D BluetoothMapService: Received start request. Starting profile...
,08-29 13:29:10.856  4206  4206 D BluetoothMapService: start()
,08-29 13:29:10.858  4206  4206 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 13:29:10.858  4206  4206 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 13:29:10.858  4206  4206 D BluetoothMapAppObserver: createReceiver()
,08-29 13:29:10.859  4206  4206 D BluetoothMapAppObserver: initObservers()
08-29 13:29:10.859  4206  4206 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 13:29:10.865  4206  4237 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 13:29:10.865  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:10.865  4206  4206 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:10.866  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:10.866  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:10.867  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:10.867  4206  4206 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:10.867  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:10.867  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:10.869  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isTurningOff()=false
,08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isTurningOn()=true
08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isTurningOff()=false
08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isTurningOn()=true
,08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isBleTurningOn()=false
08-29 13:29:10.870  4206  4206 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 13:29:10.870  4206  4218 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 13:29:10.871  4206  4218 D BluetoothAdapterProperties: ScanMode =  20
,08-29 13:29:10.871  4206  4218 D BluetoothAdapterProperties: State =  11
08-29 13:29:10.872  4206  4222 D BluetoothAdapterProperties: Scan Mode:21
,08-29 13:29:10.873  4206  4222 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:29:10.873  4206  4218 D BluetoothAdapterProperties: Setting state to 12
08-29 13:29:10.873  4206  4218 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:29:10.873   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:10.873   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:29:10.874  3921  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 13:29:10.874  4206  4218 I BluetoothAdapterState: Entering OnState
08-29 13:29:10.875   872   872 D BluetoothA2dp: Proxy object connected
,08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:10.875  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:10.877  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:29:10.878  3921  3931 D BluetoothPbap: onBluetoothStateChange: up=true,
,08-29 13:29:10.880  2364  2375 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:10.880  2364  2377 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:29:10.882  2364  2543 D BluetoothPan: onBluetoothStateChange on: true
,08-29 13:29:10.884  3921  3932 D BluetoothPan: onBluetoothStateChange on: true
08-29 13:29:10.884  2364  2364 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:29:10.885  2364  2364 D PanProfile: Bluetooth service connected
08-29 13:29:10.885  4206  4206 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 13:29:10.886  1950  2078 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:29:10.886  4206  4206 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 13:29:10.886  2364  2377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:29:10.887  4206  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:29:10.888  2364  2364 D BluetoothA2dp: Proxy object connected
,08-29 13:29:10.888  3921  3921 D BluetoothInputDevice: Proxy object connected
08-29 13:29:10.888  3921  3921 D HidProfile: Bluetooth service connected
08-29 13:29:10.889  3921  3931 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:29:10.890  4206  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:29:10.890   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:10.891  2364  2375 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:29:10.891  4206  4206 D ObexServerSockets: Succeed to create listening sockets 
,08-29 13:29:10.891  4206  4206 D ObexServerSockets0: startAccept()
,08-29 13:29:10.891  4206  4206 D ObexServerSockets0: prepareForNewConnect()
08-29 13:29:10.892  3921  4197 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:29:10.893  4206  4206 D BluetoothSdpJni: sdpCreateMapMasRecordNative:,
08-29 13:29:10.893  4206  4206 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 13:29:10.894  4206  4245 D ObexServerSockets0: Accepting socket connection...
,08-29 13:29:10.895  2364  2364 D BluetoothMap: Proxy object connected
,08-29 13:29:10.895  3921  4197 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 13:29:10.895  2364  2364 D MapProfile: Bluetooth service connected
,08-29 13:29:10.895  2364  2364 D BluetoothMap: getConnectedDevices()
08-29 13:29:10.895  4206  4246 D ObexServerSockets0: Accepting socket connection...
,08-29 13:29:10.895   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 13:29:10.895  2364  2377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:29:10.897  2364  2364 D BluetoothInputDevice: Proxy object connected
,08-29 13:29:10.897  2364  2364 D HidProfile: Bluetooth service connected
08-29 13:29:10.900  4206  4206 D BluetoothMapService: onReceive
08-29 13:29:10.900  4206  4206 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:29:10.900  4206  4206 D BluetoothMapService: STATE_ON
08-29 13:29:10.900   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:29:10.901  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:10.903  3921  3921 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:29:10.903  3921  3921 D PanProfile: Bluetooth service connected
08-29 13:29:10.903  3921  3921 D BluetoothA2dp: Proxy object connected
,08-29 13:29:10.904  3921  3921 D BluetoothMap: Proxy object connected
08-29 13:29:10.905  3921  3921 D MapProfile: Bluetooth service connected
08-29 13:29:10.905  3921  3921 D BluetoothMap: getConnectedDevices()
,08-29 13:29:10.910  3921  3921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:29:10.915  3921  3921 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:29:10.915  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:29:10.921  4206  4206 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 13:29:10.921  4206  4206 D ObexServerSockets0: prepareForNewConnect()
08-29 13:29:10.921  3921  3921 D BluetoothPbap: Proxy object connected
08-29 13:29:10.921  3921  3921 D PbapServerProfile: Bluetooth service connected
,08-29 13:29:10.925  2364  2364 D BluetoothPbap: Proxy object connected
08-29 13:29:10.925  2364  2364 D PbapServerProfile: Bluetooth service connected
,08-29 13:29:10.929  4206  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:10.941  4206  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:29:10.943  4206  4255 I BtOppRfcommListener: Accept thread started.
,08-29 13:29:10.976   872   872 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.977  1950  1964 D BluetoothHeadset: Proxy object connected
08-29 13:29:10.977  2364  2543 D BluetoothHeadset: Proxy object connected
08-29 13:29:10.977  2364  2364 D HeadsetProfile: Bluetooth service connected
08-29 13:29:10.978   872   872 D BluetoothHeadset: Proxy object connected
08-29 13:29:10.978   872   872 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.978  3921  3932 D BluetoothHeadset: Proxy object connected
08-29 13:29:10.979  3921  3921 D HeadsetProfile: Bluetooth service connected
08-29 13:29:10.980  2364  2375 D BluetoothHeadset: Proxy object connected
08-29 13:29:10.981  2364  2364 D HeadsetProfile: Bluetooth service connected
,08-29 13:29:10.987  1950  2122 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.991   872   889 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.995  3921  4197 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.996   872   889 D BluetoothHeadset: Proxy object connected
,08-29 13:29:10.998  3921  3921 D HeadsetProfile: Bluetooth service connected
,08-29 13:29:11.020   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 13:29:11.022   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 13:29:11.023   872  1331 D SurfaceControl: Excessive delay in setPowerMode(): 241ms
,08-29 13:29:11.029   872   892 I DreamManagerService: Entering dreamland.
08-29 13:29:11.031   872   892 I PowerManagerService: Dozing...
08-29 13:29:11.031   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 13:29:11.068   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 13:29:11.068   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 13:29:11.080   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:29:11.085   872  1308 E native  : do suspend false
,08-29 13:29:11.094  1937  4257 D NfcService: Discovery configuration equal, not updating.
,08-29 13:29:11.113   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:29:11.121   872  1308 E native  : do suspend true
,08-29 13:29:11.208   376  1486 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 13:29:11.208   376  1486 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:11.324  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:11.330  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:11.333  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:11.334  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b22928 added. We now have 8 listener(s)
08-29 13:29:11.334  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:11.340   872  3342 D WifiService: setWifiEnabled: false pid=3850, uid=10000
08-29 13:29:11.340   872  3342 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:29:11.353  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:11.354   872  2220 D WifiService: setWifiEnabled: true pid=3850, uid=10000
08-29 13:29:11.354   872  2220 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 13:29:11.366   872  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:11.386  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:11.392  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:11.400   872  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-29 13:29:11.401   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 13:29:11.402   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 13:29:11.403   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:29:11.403   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 13:29:11.403   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 13:29:11.403   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 13:29:11.417   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 13:29:11.417   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 13:29:11.418   372   870 D CommandListener: Setting iface cfg
,08-29 13:29:11.427   872  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '163 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 163 Failed to set address (No such device)'
,08-29 13:29:11.427   872  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:29:11.429   872  1308 E native  : do suspend true
,08-29 13:29:11.437   872  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 13:29:11.438   872  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 13:29:11.443   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:12.378  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:12.386  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-29 13:29:12.400  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 13:29:12.404  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:29:12.406  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a78913 Bundle[{}]
,08-29 13:29:12.407  3850  3900 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:29:12.407  3850  3900 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 13:29:12.408  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:29:12.409  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 13:29:12.410  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 13:29:12.410  3850  3900 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:29:12.417  3850  3900 I System.out: Running OutgoingSocketThread
,08-29 13:29:12.419  3850  4266 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-29 13:29:12.421  3850  4266 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37015
,08-29 13:29:12.422  3850  4266 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:29:12.818   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 13:29:12.911   872  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.01 rxSuccessRate=0.01 delta 1000 -> 1000
,08-29 13:29:12.913   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 13:29:12.913   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:29:12.929   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 13:29:12.993   872  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 13:29:12.996  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 13:29:13.420  3850  3900 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-29 13:29:13.421  3850  3900 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-29 13:29:13.426  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 13:29:13.440  3850  3900 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-29 13:29:13.442  3850  3900 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 13:29:13.442  3850  3900 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-29 13:29:13.448  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:29:13.448  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@555e641 added. We now have 2 listener(s)
,08-29 13:29:13.450  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.450  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.450  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.451  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.451  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90107e6 added. We now have 9 listener(s)
08-29 13:29:13.451  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:13.452  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:29:13.455  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:13.459  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:13.461  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:13.462  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:29:13.462  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.462  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94afd4 added. We now have 3 listener(s)
,08-29 13:29:13.463  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:13.464  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.465  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.465  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.465  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:13.465  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.465  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9a57d added. We now have 10 listener(s)
08-29 13:29:13.465  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.465  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:29:13.465  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:29:13.465  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:29:13.465  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.466  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.466  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:29:13.466  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.466  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@555e641 removed from the list
08-29 13:29:13.466  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.466  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90107e6 removed from the list
08-29 13:29:13.466  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:29:13.466  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.467  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.467  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.468  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.468  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:29:13.468  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.468  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90107e6 not in the list
08-29 13:29:13.468  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.468  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.469  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:29:13.470  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.470  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.470  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d9a57d removed from the list
08-29 13:29:13.470  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.470  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.470  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.470  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.470  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f94afd4 removed from the list
08-29 13:29:13.471  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.471  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c5bc72 added. We now have 2 listener(s)
08-29 13:29:13.471  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:29:13.472  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 13:29:13.474  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:29:13.474  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.474  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.474  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.474  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c828c3 added. We now have 9 listener(s)
08-29 13:29:13.475  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:13.475  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:29:13.480  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:29:13.481   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:13.485  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:13.487   872  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 13:29:13.487   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:29:13.487   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 13:29:13.488  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:29:13.488  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:29:13.489  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.489  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e01c79 added. We now have 3 listener(s)
,08-29 13:29:13.491  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.491  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.491  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.491  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:13.491  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:29:13.491  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7af2dbe added. We now have 10 listener(s)
08-29 13:29:13.492  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.492  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:29:13.492  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:29:13.492  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:29:13.492  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:29:13.492  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:29:13.493  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:13.495  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:29:13.496  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:29:13.500   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:29:13.507  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:29:13.508  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 13:29:13.509  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:29:13.509   372   870 D CommandListener: Setting iface cfg
08-29 13:29:13.510   872  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 13:29:13.513  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:29:13.513  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:29:13.513  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:29:13.514  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:29:13.517  4206  4217 D BtGatt.GattService: registerClient() - UUID=454f137e-f2f0-4a21-a3c0-71cbd565c440
,08-29 13:29:13.517  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=454f137e-f2f0-4a21-a3c0-71cbd565c440, clientIf=5
08-29 13:29:13.518  3850  3861 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:29:13.519  4206  4238 D BtGatt.GattService: start scan with filters
,08-29 13:29:13.521   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 13:29:13.523  4206  4225 D BtGatt.ScanManager: handling starting scan
,08-29 13:29:13.524  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:29:13.524  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:29:13.524  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:29:13.525  4206  4225 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df9c77
,08-29 13:29:13.526  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:29:13.528  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:29:13.528  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:29:13.529  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:29:13.529  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 13:29:13.529  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.529  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:29:13.531  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:29:13.534  3850  3900 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:29:13.534  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:29:13.534  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:29:13.534  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.534  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:29:13.534  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:29:13.534  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:29:13.534  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:29:13.535  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:29:13.535  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:29:13.535  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:29:13.536  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:29:13.536  4206  4217 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:29:13.537  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:29:13.538  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.538  4206  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 13:29:13.538  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:29:13.538  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 13:29:13.539  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:29:13.539  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 13:29:13.539  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:29:13.540  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:29:13.540  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:29:13.542  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:29:13.542  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:29:13.543  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:29:13.543  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:29:13.544  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.546  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:29:13.546  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:29:13.546  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:29:13.548   872  4270 D DhcpClient: Receive thread started
,08-29 13:29:13.553  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-29 13:29:13.553  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:29:13.553  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.553  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:29:13.553  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:29:13.554  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-29 13:29:13.554  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:29:13.554  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.554  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.554  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c5bc72 removed from the list
,08-29 13:29:13.554  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:29:13.554  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c828c3 removed from the list
,08-29 13:29:13.554  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:29:13.554  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.555  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.556  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.556  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.557  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.557  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.557  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c828c3 not in the list
,08-29 13:29:13.557  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:29:13.557  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.558  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.558  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.558  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.558  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7af2dbe removed from the list
,08-29 13:29:13.558  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.559  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.559  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.559  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.559  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e01c79 removed from the list
08-29 13:29:13.559  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:29:13.560  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72c67ca added. We now have 2 listener(s)
08-29 13:29:13.561  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:29:13.561  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.564  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.565  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.565  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.565  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.565  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c3ed3b added. We now have 9 listener(s)
08-29 13:29:13.565  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.565  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:29:13.568  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:13.571  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:13.574  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:13.574  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:29:13.575  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:29:13.575  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.575  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:29:13.576  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.576  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e1b1 added. We now have 3 listener(s)
08-29 13:29:13.576  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:13.577  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:13.578  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.578  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.578  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.578  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.578  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2913696 added. We now have 10 listener(s)
,08-29 13:29:13.578  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.578  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:29:13.579  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:29:13.579  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:29:13.579  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:29:13.580  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:29:13.580  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:29:13.583  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 13:29:13.583  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:29:13.586  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:29:13.587  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 13:29:13.587  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:29:13.588  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:29:13.588  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.588  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:29:13.590  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:29:13.591  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:29:13.591  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:29:13.591  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:29:13.594  4206  4217 D BtGatt.GattService: registerClient() - UUID=ba385250-d448-4a85-b728-137664adf6a8
08-29 13:29:13.594  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:29:13.594  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.594  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=ba385250-d448-4a85-b728-137664adf6a8, clientIf=5
08-29 13:29:13.594  3850  3862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 13:29:13.595  4206  4238 D BtGatt.GattService: start scan with filters
,08-29 13:29:13.598  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:29:13.598  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:29:13.598  4206  4225 D BtGatt.ScanManager: handling starting scan
08-29 13:29:13.598  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:29:13.598  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:29:13.602  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:29:13.602  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:29:13.602  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-29 13:29:13.604  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-29 13:29:13.604  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:29:13.604  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.605  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 13:29:13.606  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:29:13.606  3850  3900 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 13:29:13.607  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:29:13.607  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:29:13.607  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:29:13.607  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:29:13.607  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.607  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:29:13.607  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.608  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@72c67ca removed from the list
08-29 13:29:13.608  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:29:13.608  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c3ed3b removed from the list
08-29 13:29:13.608  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:29:13.608  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:29:13.608  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:29:13.608  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:29:13.608  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.608  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.609  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.610  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:29:13.610  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.610  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c3ed3b not in the list
,08-29 13:29:13.610  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:29:13.610  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:29:13.610  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:29:13.610  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 13:29:13.610  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:29:13.610  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 13:29:13.610  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.610  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:29:13.611  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:29:13.611  3850  3900 D BluetoothAdapter: STATE_ON
08-29 13:29:13.611  4206  4238 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:29:13.612  4206  4247 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:29:13.612  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:29:13.612  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:29:13.612  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:29:13.612  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:29:13.613  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:29:13.613  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:29:13.614  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:29:13.614  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:29:13.614  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:29:13.615  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.616  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:29:13.616  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:29:13.616  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:29:13.616  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.616  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.616  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.617  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2913696 removed from the list
08-29 13:29:13.617  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:29:13.617  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.617  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.617  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.617  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@343e1b1 removed from the list
,08-29 13:29:13.618  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.618  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a22622 added. We now have 2 listener(s)
,08-29 13:29:13.619  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.620  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:29:13.620  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.620  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.620  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f4c8b3 added. We now have 9 listener(s)
08-29 13:29:13.620  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:29:13.620  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:29:13.622  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 13:29:13.622  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.623  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:13.626  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:29:13.628  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:13.629  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:29:13.629  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:29:13.629  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4415e9 added. We now have 3 listener(s)
08-29 13:29:13.629  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:29:13.629  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.631  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 13:29:13.631  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.631  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:29:13.631  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.631  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:13.631  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0826e added. We now have 10 listener(s)
08-29 13:29:13.631  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.632  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:29:13.632  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:29:13.632  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:29:13.632  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:29:13.632  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:29:13.633   872  1308 E native  : do suspend false
08-29 13:29:13.633  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:13.635  3850  3900 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 13:29:13.635  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:29:13.638  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 13:29:13.638  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.638  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:29:13.640  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:29:13.641  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 13:29:13.641  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:29:13.644  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 13:29:13.645  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.645  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 13:29:13.647  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:29:13.647  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:29:13.647  3850  3900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:29:13.648   872  2094 D DhcpClient: Broadcasting DHCPDISCOVER
08-29 13:29:13.648  3850  3900 D BluetoothAdapter: STATE_ON
,08-29 13:29:13.650  4206  4217 D BtGatt.GattService: registerClient() - UUID=70d10d77-ff7d-4ce3-82f8-4b7100b7d717
08-29 13:29:13.651  4206  4222 D BtGatt.GattService: onClientRegistered() - UUID=70d10d77-ff7d-4ce3-82f8-4b7100b7d717, clientIf=5
08-29 13:29:13.651  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 13:29:13.651  3850  3862 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 13:29:13.651  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.651  4206  4238 D BtGatt.GattService: start scan with filters
,08-29 13:29:13.654  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:29:13.654  4206  4225 D BtGatt.ScanManager: handling starting scan
08-29 13:29:13.654  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:29:13.654  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:29:13.655  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:29:13.658  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:29:13.658  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:29:13.659  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:29:13.660   872  4270 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-29 13:29:13.660   872  2094 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-29 13:29:13.661  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:29:13.661  4206  4222 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 13:29:13.661  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.661  4206  4225 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 13:29:13.662   872  2094 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 13:29:13.666  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:29:13.666  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:29:13.666  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:29:13.666  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.666  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:29:13.666  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:29:13.667  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:29:13.667  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a22622 removed from the list
08-29 13:29:13.667  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:29:13.667  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f4c8b3 removed from the list
08-29 13:29:13.667  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:29:13.667  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.667  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.668  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 13:29:13.668  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.668  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.668  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 13:29:13.668  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.668  4206  4225 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:29:13.668  4206  4225 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 13:29:13.669  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:29:13.669  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.669  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.669  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f4c8b3 not in the list
08-29 13:29:13.669  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:29:13.669  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 13:29:13.669  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:29:13.669  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:29:13.670  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:29:13.670  3850  3900 D BluetoothAdapter: STATE_ON
08-29 13:29:13.671  4206  4216 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:29:13.671  4206  4238 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 13:29:13.672  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:29:13.672  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:29:13.672  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:29:13.672  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:29:13.672  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:29:13.673   872  4270 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-29 13:29:13.673  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:29:13.673  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:29:13.673  3850  3900 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:29:13.674  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:29:13.674   872  2094 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 13:29:13.674  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.675   372   870 D CommandListener: Setting iface cfg
08-29 13:29:13.676  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:29:13.676  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.676  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.676  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e0826e removed from the list
,08-29 13:29:13.676  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.676  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.676  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:29:13.676  3850  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:29:13.676  3850  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:29:13.678   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 13:29:13.679  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.679  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.679  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4415e9 removed from the list
,08-29 13:29:13.680  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:29:13.680  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@196577a added. We now have 2 listener(s)
08-29 13:29:13.681  4206  4222 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 13:29:13.681  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.682  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.682  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:29:13.682  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.682  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.682  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e069b2b added. We now have 9 listener(s)
,08-29 13:29:13.682  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.683  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:29:13.683   872  1308 E native  : do suspend true
08-29 13:29:13.683   872  2094 D DhcpClient: Scheduling renewal in 86399s
08-29 13:29:13.685  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:29:13.689  3850  3900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:29:13.689  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 13:29:13.690  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 13:29:13.692  3850  3900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:29:13.692  3850  3900 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:29:13.692  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:29:13.693  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51f9921 added. We now have 3 listener(s)
08-29 13:29:13.694  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:29:13.695  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:29:13.695  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 13:29:13.695  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:29:13.696  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:29:13.696  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:29:13.696  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa27146 added. We now have 10 listener(s)
,08-29 13:29:13.696  3850  3900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:29:13.696  3850  3900 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:29:13.696  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:29:13.697  3850  3900 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:29:13.697  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.697  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.697  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:29:13.697  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.697  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@196577a removed from the list
08-29 13:29:13.697  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.697  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e069b2b removed from the list
,08-29 13:29:13.697  3850  3900 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:29:13.697  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.697  4206  4222 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 13:29:13.697  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.698  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:29:13.698  4206  4225 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:29:13.698  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.698   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-29 13:29:13.699   872  1308 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 13:29:13.700  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.700  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.700  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.700  3850  3900 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e069b2b not in the list
08-29 13:29:13.700  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.700  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:29:13.701  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:29:13.701  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:29:13.701  3850  3900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:29:13.701  3850  3900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa27146 removed from the list
08-29 13:29:13.701  3850  3900 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:29:13.701  3850  3900 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:29:13.701  3850  3900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:29:13.701  3850  3900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:29:13.702  3850  3900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51f9921 removed from the list
08-29 13:29:13.702  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 13:29:13.703  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:29:13.703  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 13:29:13.703  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:29:13.703   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 13:29:13.704  4206  4222 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 13:29:13.704  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.704  4206  4225 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 13:29:13.704   872  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 13:29:13.703  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:29:13.707  3850  3900 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:29:13.709  4206  4222 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 13:29:13.710  4206  4222 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 13:29:13.710   872  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:29:13.715  3850  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-29 13:29:13.715  3850  4272 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-29 13:29:13.715  3850  4272 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:29:13.717  3850  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
,08-29 13:29:13.717  3850  4273 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
08-29 13:29:13.717  3850  4273 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:29:13.719  3850  3900 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:29:13.719  3850  3900 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-29 13:29:13.719  3850  3900 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:29:13.719  3850  3900 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:29:13.719  3850  3900 D com.test.thalitest.ThaliTestRunner: Total duration: 22900 ms
,08-29 13:29:13.721  3850  3900 I jxcore-log: *Native tests were executed*
08-29 13:29:13.721  3850  3900 I jxcore-log: 
,08-29 13:29:13.721  3850  3900 I jxcore-log: Total number of executed tests:  80
08-29 13:29:13.721  3850  3900 I jxcore-log: 
08-29 13:29:13.721  3850  3900 I jxcore-log: Number of passed tests:  80
08-29 13:29:13.721  3850  3900 I jxcore-log: 
08-29 13:29:13.721  3850  3900 I jxcore-log: Number of failed tests:  0
08-29 13:29:13.721  3850  3900 I jxcore-log: 
08-29 13:29:13.722  3850  3900 I jxcore-log: Number of ignored tests:  0
08-29 13:29:13.722  3850  3900 I jxcore-log: 
,08-29 13:29:13.722  3850  3900 I jxcore-log: Total duration:  22900
08-29 13:29:13.722  3850  3900 I jxcore-log: 
,08-29 13:29:13.722  3850  3900 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:29:13.722  3850  3900 I jxcore-log: 
,08-29 13:29:13.727  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.727  3850  3900 I jxcore-log: 
08-29 13:29:13.730  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.730  3850  3900 I jxcore-log: 
08-29 13:29:13.731  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.731  3850  3900 I jxcore-log: 
08-29 13:29:13.732  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.732  3850  3900 I jxcore-log: 
08-29 13:29:13.732  3850  3850 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 13:29:13.733  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.733  3850  3900 I jxcore-log: 
08-29 13:29:13.734  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.734  3850  3900 I jxcore-log: 
,08-29 13:29:13.738   872  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 13:29:13.738   872  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 13:29:13.739  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.739  3850  3900 I jxcore-log: 
08-29 13:29:13.739   872  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 13:29:13.740   872  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 13:29:13.741   872  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-29 13:29:13.741  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-29 13:29:13.741  3850  3900 I jxcore-log: 
,08-29 13:29:13.743  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.743  3850  3900 I jxcore-log: 
08-29 13:29:13.744  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.744  3850  3900 I jxcore-log: 
,08-29 13:29:13.745  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.745  3850  3900 I jxcore-log: 
,08-29 13:29:13.747   872  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 13:29:13.748  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:29:13.748  3850  3900 I jxcore-log: 
08-29 13:29:13.749  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.749  3850  3900 I jxcore-log: 
,08-29 13:29:13.750  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.750  3850  3900 I jxcore-log: 
08-29 13:29:13.751  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.751  3850  3900 I jxcore-log: 
08-29 13:29:13.751   872  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 13:29:13.751   872  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 13:29:13.751   872  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 13:29:13.751  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.751  3850  3900 I jxcore-log: 
,08-29 13:29:13.751   872  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 13:29:13.751   872  1310 D ConnectivityService:    accepting network in place of null
08-29 13:29:13.752   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 13:29:13.752   872  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 13:29:13.752  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.752  3850  3900 I jxcore-log: 
08-29 13:29:13.753  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.753  3850  3900 I jxcore-log: 
,08-29 13:29:13.754  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.754  3850  3900 I jxcore-log: 
08-29 13:29:13.755  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.755  3850  3900 I jxcore-log: 
08-29 13:29:13.756  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.756  3850  3900 I jxcore-log: 
,08-29 13:29:13.756  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.756  3850  3900 I jxcore-log: 
,08-29 13:29:13.757  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.757  3850  3900 I jxcore-log: 
,08-29 13:29:13.758  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.758  3850  3900 I jxcore-log: 
,08-29 13:29:13.759  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.759  3850  3900 I jxcore-log: 
08-29 13:29:13.759  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:29:13.759  3850  3900 I jxcore-log: 
,08-29 13:29:13.760  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.760  3850  3900 I jxcore-log: 
08-29 13:29:13.761  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.761  3850  3900 I jxcore-log: 
,08-29 13:29:13.761  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.761  3850  3900 I jxcore-log: 
08-29 13:29:13.762  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.762  3850  3900 I jxcore-log: 
,08-29 13:29:13.763  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.763  3850  3900 I jxcore-log: 
,08-29 13:29:13.763  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.763  3850  3900 I jxcore-log: 
08-29 13:29:13.764  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:29:13.764  3850  3900 I jxcore-log: 
,08-29 13:29:13.769   872  4269 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156939, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 13:29:13.777   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:29:13.799   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 13:29:13.802   872  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 13:29:13.802   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:29:13.805   872  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 13:29:13.808   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:29:13.818  3850  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:29:13.820  3850  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:29:13.821  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:29:13.821  3850  3900 I jxcore-log: 
,08-29 13:29:13.827  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 13:29:13.831  1713  1713 D SystemUpdateService: onCreate
,08-29 13:29:13.834  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 13:29:13.850  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:29:13.852  1713  2569 I iu.UploadsManager: num queued entries: 0
08-29 13:29:13.852  1713  2569 I iu.UploadsManager: num updated entries: 0
08-29 13:29:13.852  1713  2569 I iu.SyncManager: NEXT; no task
,08-29 13:29:13.858   872  4268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:816::200e
,08-29 13:29:13.907  1713  4283 I SystemUpdateService: active receiver: enabled
,08-29 13:29:13.907  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:29:13.909  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 13:29:13.911  1713  4283 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 13:29:13.913  3975  3975 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:29:13.913  1713  4283 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 13:29:13.913  1713  4283 I SystemUpdateService: now status is 0 (complete)
,08-29 13:29:13.914  1713  4283 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 13:29:13.919  1713  4283 I SystemUpdateService: file has been verified
,08-29 13:29:13.919  1713  4283 I SystemUpdateService: OTA package size = 12249756
,08-29 13:29:13.921  1713  4286 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 13:29:13.921  1713  4286 W BaseAppContext: Using Auth Proxy for data requests.
08-29 13:29:13.922  3975  3975 D SprintDMHelper: simOperator: 
08-29 13:29:13.922  3975  3975 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-29 13:29:13.923  1713  4286 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 13:29:13.954  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:29:13.956  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 13:29:13.972  1713  4283 I SystemUpdateService: showing system update notification
,08-29 13:29:13.980  1502  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 13:29:13.980  1502  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 13:29:13.980  1502  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 13:29:13.980  1502  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 13:29:13.983   872  4268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 11:29:13 GMT], X-Android-Received-Millis=[1472470153982], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472470153900]}
,08-29 13:29:13.983   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 13:29:13.984   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 13:29:13.984   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 13:29:13.985   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 13:29:13.990  1713  1713 D SystemUpdateService: onDestroy
,08-29 13:29:13.999  1713  4286 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-29 13:29:14.047  3850  3850 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:29:14.049  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:29:14.049  3850  3900 I jxcore-log: 
,08-29 13:29:14.116  2280  4288 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 13:29:14.116  3850  3850 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:29:14.120  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:29:14.120  3850  3900 I jxcore-log: 
,08-29 13:29:14.177  3850  3850 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:29:14.181  3850  3900 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:29:14.181  3850  3900 I jxcore-log: 
,08-29 13:29:14.321  4280  4280 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 13:29:14.326  4280  4280 D AndroidRuntime: CheckJNI is OFF
,08-29 13:29:14.369  4280  4280 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 13:29:14.414  4280  4280 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 13:29:14.437  4280  4280 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:29:14.448   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-29 13:29:14.448   872   885 I ActivityManager: Killing 3850:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-29 13:29:14.577   872   895 W PackageSettings: Skipping PackageSetting{b267e88 com.example.hello/10273} due to missing metadata
,08-29 13:29:14.582   872  2223 D GraphicsStats: Buffer count: 2
08-29 13:29:14.582   872  1987 I WindowState: WIN DEATH: Window{824c906 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 13:29:14.583   872  1309 D WifiService: Client connection lost with reason: 4
,08-29 13:29:14.620   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 13:29:14.621   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 13:29:14.622   872   895 I art     : Starting a blocking GC Explicit
,08-29 13:29:14.628   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-29 13:29:14.628   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 13:29:14.628   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:14.628   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.628   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:29:14.628   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 13:29:14.630   872   885 I ActivityManager:   Force finishing activity ActivityRecord{8151fef u0 com.test.thalitest/.MainActivity t2}
,08-29 13:29:14.646   872  2220 W ActivityManager: Spurious death for ProcessRecord{3fa6e07 0:com.test.thalitest/u0a0}, curProc for 3850: null
,08-29 13:29:14.668   872   895 I art     : Explicit concurrent mark sweep GC freed 59922(3MB) AllocSpace objects, 15(432KB) LOS objects, 33% free, 29MB/43MB, paused 768us total 45.155ms
,08-29 13:29:14.688   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 13:29:14.693  4280  4280 I art     : System.exit called, status: 0
,08-29 13:29:14.693  4280  4280 I AndroidRuntime: VM exiting with result code 0.
,08-29 13:29:14.700   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-29 13:29:14.723   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 13:29:14.727  4206  4206 D BluetoothMapAppObserver: onReceive
,08-29 13:29:14.728  4206  4206 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 13:29:14.730  1886  2257 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 13:29:14.731  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-29 13:29:14.731  3720  3720 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-29 13:29:14.746  1950  1950 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 13:29:14.748  1873  4304 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 13:29:14.750  1873  4304 I Decoder : createOrResetDecoder
,08-29 13:29:14.767   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:29:14.773   872  3342 I ActivityManager: Start proc 4306:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 13:29:14.803   872  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 13:29:14.808  4306  4306 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-29 13:29:14.811  1502  1502 I ConfigService: onCreate
,08-29 13:29:14.825  1873  4304 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 13:29:14.833   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 13:29:14.842   872  1986 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3850 uid 10000
,08-29 13:29:14.844  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-29 13:29:14.871  1965  2040 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 13:29:14.872   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-29 13:29:14.873   872   884 E PackageManager: Failed to write settings, restoring backup
08-29 13:29:14.873   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 13:29:14.873   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 13:29:14.873   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 13:29:14.873   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 13:29:14.873   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 13:29:14.873   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:14.873   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.873   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:14.877   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-29 13:29:14.877   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 13:29:14.877   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:29:14.877   872   885 E DropBoxManagerService: 	... 13 more
,08-29 13:29:14.882  4306  4306 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-29 13:29:14.887   872  1987 I ActivityManager: Start proc 4324:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 13:29:14.887  1965  2040 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 13:29:14.887  1965  2040 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1965
08-29 13:29:14.887  1965  2040 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.887  1965  2040 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:14.889   872  1712 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 13:29:14.890   872  4330 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:29:14.890   872  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:29:14.890   872  4330 E DropBoxManagerService: 	... 5 more
,08-29 13:29:14.894  1965  2040 I Process : Sending signal. PID: 1965 SIG: 9
,08-29 13:29:14.906   872  1425 I ActivityManager: Start proc 4339:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-29 13:29:14.908  4306  4338 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 13:29:14.913  1873  4304 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-29 13:29:14.917  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 13:29:14.917  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-29 13:29:14.919  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 13:29:14.919  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-29 13:29:14.920  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-29 13:29:14.920  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 13:29:14.920  1873  4304 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-29 13:29:14.920  1873  4304 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 13:29:14.920  1873  4304 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-29 13:29:14.921  1873  4304 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 13:29:14.921  1873  4304 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-29 13:29:14.921  1873  4304 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 13:29:14.944  4306  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.944  4306  4321 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.944  4306  4321 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:14.963  4339  4339 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-29 13:29:14.990  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 13:29:14.992  1502  1502 D AndroidRuntime: Shutting down VM
,08-29 13:29:14.995  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:29:14.995  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
08-29 13:29:14.995  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 13:29:14.995  1502  1502 E AndroidRuntime: 	... 8 more
,08-29 13:29:15.000  1502  1502 I Process : Sending signal. PID: 1502 SIG: 9
,08-29 13:29:15.003   872  4356 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:29:15.003   872  4356 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:29:15.003   872  4356 E DropBoxManagerService: 	... 5 more
,08-29 13:29:15.020   872  1425 I ActivityManager: Killing 3772:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 13:29:15.032   872  1309 D WifiService: Client connection lost with reason: 4
,08-29 13:29:15.034  1713  4355 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@c3c073b
,08-29 13:29:15.037   872  1386 D GraphicsStats: Buffer count: 1
,08-29 13:29:15.038   872  1920 I WindowState: WIN DEATH: Window{5870541 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-29 13:29:15.076  4306  4321 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-29 13:29:15.081  4306  4338 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:15.081  4306  4338 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:15.081  4306  4338 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 13:29:15.081  4306  4338 E AndroidRuntime: Process: android.process.acore, PID: 4306
08-29 13:29:15.081  4306  4338 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 13:29:15.081  4306  4338 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 13:29:15.082  4306  4321 I Process : Sending signal. PID: 4306 SIG: 9
,08-29 13:29:15.107   872  1986 I ActivityManager: Process com.google.process.gapps (pid 1502) has died
08-29 13:29:15.108   872  1986 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-29 13:29:15.108   872  1986 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,08-29 13:29:15.108   872  1986 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-29 13:29:15.108   872  1986 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
08-29 13:29:15.110   872  2223 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1965) has died
,08-29 13:29:15.111   872  2223 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40997ms
,08-29 13:29:15.112   872  2223 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-29 13:29:15.115   872  1712 I ActivityManager: Process android.process.acore (pid 4306) has died
,08-29 13:29:15.115   872  1712 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40992ms
,08-29 13:29:15.121  1713  1713 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-29 13:29:15.137   872   885 I ActivityManager: Start proc 4358:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 13:29:15.152   872  1987 I ActivityManager: Start proc 4363:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-29 13:29:15.153   872  2220 W ActivityManager: Can't find mystery application for Crash from pid=4306 uid=10005: android.os.BinderProxy@d8c2ef9
,08-29 13:29:15.154   872  2220 E DropBoxManagerService: Can't write: system_server_crash
08-29 13:29:15.154   872  2220 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12127)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at android.os.Binder.execTransact(Binder.java:453)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 13:29:15.154   872  2220 E DropBoxManagerService: 	... 11 more
,08-29 13:29:15.190  4363  4363 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-29 13:29:15.198  4363  4363 I GservicesProvider: Gservices pushing to system: true; secure/global: true

```
