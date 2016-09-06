#### Test 82914073f44248e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-06 18:56:47.646  3524  3535 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
09-06 18:56:47.665  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 18:56:47.683  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 18:56:47.690  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 18:56:47.775  1515  2175 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-06 18:56:47.776  1515  2175 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-06 18:56:47.776  1515  2175 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 18:56:47.777  1515  2175 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 18:56:47.846  3524  3535 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-06 18:56:49.376  3802  3802 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-06 18:56:49.382  3802  3802 D AndroidRuntime: CheckJNI is OFF
09-06 18:56:49.426  3802  3802 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-06 18:56:49.477  3802  3802 I Radio-JNI: register_android_hardware_Radio DONE
09-06 18:56:49.500  3802  3802 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-06 18:56:49.505   873  2017 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-06 18:56:49.564  2046  2239 W SearchService: Abort, client detached.
09-06 18:56:49.569  2046  2383 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e75a24e
09-06 18:56:49.570  2046  2046 I HotwordDetector: Closing mic
09-06 18:56:49.569  2046  2391 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-06 18:56:49.572  3802  3802 D AndroidRuntime: Shutting down VM
09-06 18:56:49.596   873  1984 I ActivityManager: Start proc 3811:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-06 18:56:49.629   378  2393 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-06 18:56:49.631   378  2393 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-06 18:56:49.635   378  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-06 18:56:49.636  2046  2386 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-06 18:56:49.636  2046  2390 I MicroRecognitionRnrImpl: Detection finished
09-06 18:56:49.680  3811  3811 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-06 18:56:49.700  3811  3811 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-06 18:56:49.705  3811  3811 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8416-8418)
09-06 18:56:49.706  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:56:49.716  3811  3811 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f85195}
09-06 18:56:49.717  3811  3811 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:56:49.717  3811  3811 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 18:56:49.722  3811  3811 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 18:56:49.723  3811  3811 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 18:56:49.734  3811  3811 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-06 18:56:49.743  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 18:56:49.743  3811  3811 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 18:56:49.744  3811  3811 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 18:56:49.744  3811  3811 I Adreno  : Build Date                       : 10/20/15
09-06 18:56:49.744  3811  3811 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 18:56:49.744  3811  3811 I Adreno  : Local Branch                     : M14
09-06 18:56:49.744  3811  3811 I Adreno  : Remote Branch                    : 
09-06 18:56:49.744  3811  3811 I Adreno  : Remote Branch                    : 
09-06 18:56:49.744  3811  3811 I Adreno  : Reconstruct Branch               : 
09-06 18:56:49.779   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab43ffd:true
,09-06 18:56:49.814  3811  3811 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 18:56:49.824  3811  3811 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-06 18:56:49.875  3811  3850 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 18:56:49.884  3811  3836 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-06 18:56:49.920  3811  3850 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 18:56:49.989   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +417ms
,09-06 18:56:50.007  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-06 18:56:50.059  3811  3811 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3811
,09-06 18:56:50.183  3811  3811 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 18:56:50.371  3811  3852 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1686111952
,09-06 18:56:50.381  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 18:56:50.381  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 18:56:50.381  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 18:56:50.381  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 18:56:50.381  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 18:56:50.382  3811  3852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e39d10 added. We now have 1 listener(s)
,09-06 18:56:50.387  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-06 18:56:50.389  3811  3852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,09-06 18:56:50.390  3811  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:56:50.390  3811  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-06 18:56:50.394  3811  3852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d19f42f added. We now have 1 listener(s)
,09-06 18:56:50.394  3811  3852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:56:50.399   873  1308 D WifiService: New client listening to asynchronous messages
,09-06 18:56:50.400  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:56:50.400  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-06 18:56:50.401  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 18:56:50.402  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 18:56:50.402  3811  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-06 18:56:50.405  3811  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:56:50.406  3811  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-06 18:56:50.412  3811  3852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:56:50.412  3811  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:56:50.412  3811  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-06 18:56:50.413  3811  3852 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:56:50.414  3811  3852 I io.jxcore.node.LifeCycleMonitor: start: OK
09-06 18:56:50.415  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:56:50.417  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:56:50.438   873  2014 I ActivityManager: Killing 2982:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-06 18:56:50.470   873  2014 I ActivityManager: Killing 3219:com.google.android.gm/u0a78 (adj 15): empty #18
,09-06 18:56:50.573  3811  3811 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 18:56:51.405  3811  3862 W jxcore-log: Initializing JXcore engine
,09-06 18:56:51.405  3811  3862 W jxcore-log: JXcore engine is ready
,09-06 18:56:51.443  3862  3862 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-06 18:56:51.443  3862  3862 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11852]" dev="sockfs" ino=11852 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-06 18:56:51.443  3862  3862 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 18:56:51.443  3862  3862 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25114]" dev="sockfs" ino=25114 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-06 18:56:51.456  3811  3862 W jxcore-log: Starting JXcore engine
,09-06 18:56:51.539  3811  3862 W jxcore-log: Platform android
09-06 18:56:51.539  3811  3862 W jxcore-log: 
09-06 18:56:51.539  3811  3862 W jxcore-log: Process ARCH arm
09-06 18:56:51.539  3811  3862 W jxcore-log: 
,09-06 18:56:51.834  3811  3862 I jxcore-log: JXcore Cordova bridge is ready!
09-06 18:56:51.834  3811  3862 I jxcore-log: 
,09-06 18:56:51.834  3811  3862 W jxcore-log: JXcore engine is started
,09-06 18:56:51.842  3811  3852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 18:56:51.847  3811  3811 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 18:56:54.057   873  1839 D NetlinkSocketObserver: NeighborEvent{elapsedMs=112770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-06 18:56:59.807  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 18:56:59.815  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 18:56:59.817  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 18:56:59.836  1515  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-06 18:56:59.837  1515  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-06 18:56:59.837  1515  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 18:56:59.837  1515  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 18:56:59.853  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-06 18:56:59.854  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-06 18:56:59.854  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-06 18:57:01.508  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 18:57:01.508  3811  3862 I jxcore-log: 
,09-06 18:57:01.512  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 18:57:01.512  3811  3862 I jxcore-log: 
,09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:01.525  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:01.532  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:01.542  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 18:57:01.542  3811  3862 I jxcore-log: 
,09-06 18:57:01.553  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 18:57:01.553  3811  3862 I jxcore-log: 
,09-06 18:57:02.063  3811  3862 D executeNativeTests: Running unit tests
,09-06 18:57:02.121  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:02.121  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 added. We now have 2 listener(s)
,09-06 18:57:02.122  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:02.122  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:02.123  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:02.123  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:02.123  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e added. We now have 2 listener(s)
,09-06 18:57:02.123  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:02.124  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:02.129  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.139  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:02.142  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:02.142  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:02.145  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:57:02.149  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:02.149  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 18:57:02.149  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 18:57:02.151  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 18:57:02.154  3811  3862 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 18:57:02.155  3811  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:57:02.155  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:02.155  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 18:57:02.155  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 18:57:02.157  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.159  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.159  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:02.160  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:02.161  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.162  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:02.162  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:02.163  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 removed from the list
09-06 18:57:02.164  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.164  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e removed from the list
,09-06 18:57:02.164  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.165  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.166  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.167  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.168  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.169  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:02.169  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.169  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.171  3811  3862 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 18:57:02.172  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.172  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.172  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.172  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.172  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.172  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.172  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.172  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.172  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.172  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.172  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.172  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.172  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.173  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.174  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.174  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.174  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.174  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 18:57:02.180  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:57:02.181  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-06 18:57:02.182  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 18:57:02.182  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:57:02.182  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:57:02.182  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:57:02.182  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.182  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.182  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.182  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.182  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.182  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.182  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.182  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.182  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.183  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.183  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.183  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.183  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.183  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.184  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.184  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.184  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.184  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.185  3811  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:57:02.186  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.193  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:02.197  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.197  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:02.199  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:02.199  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:02.199  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:02.199  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.199  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:02.199  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:57:02.202  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.205  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 18:57:02.205  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:57:02.211  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:57:02.213  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 18:57:02.214  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:02.218  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 18:57:02.221  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 18:57:02.222  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 18:57:02.222  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:02.223  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 18:57:02.224  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:02.228  2688  2817 D BtGatt.GattService: registerClient() - UUID=2cc23f1f-1791-41d8-b0c2-7b6d43a1733d
09-06 18:57:02.229  2688  2707 D BtGatt.GattService: onClientRegistered() - UUID=2cc23f1f-1791-41d8-b0c2-7b6d43a1733d, clientIf=5
09-06 18:57:02.231  3811  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 18:57:02.232  2688  2700 D BtGatt.GattService: start scan with filters
09-06 18:57:02.236  2688  2711 D BtGatt.ScanManager: handling starting scan
09-06 18:57:02.236  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 18:57:02.236  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:02.236  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:02.236  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:02.237  2688  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:02.238  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:02.239  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:02.239  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:02.240  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:02.243  3811  3862 I io.jxcore.node.ConnectionHelper: start: OK
09-06 18:57:02.245  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.245  3811  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:02.246  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.246  2688  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 18:57:02.250  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 18:57:02.250  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.250  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:02.250  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:02.250  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.250  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:02.250  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:02.250  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:02.251  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:02.251  2688  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 18:57:02.251  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 18:57:02.251  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:02.253  2688  2826 D BtGatt.GattService: stopScan() - queue size =1
09-06 18:57:02.254  2688  2825 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:02.254  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:02.254  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:02.254  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 18:57:02.254  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:02.255  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:02.255  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:02.255  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:02.256  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 18:57:02.256  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:57:02.256  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:02.257  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-06 18:57:02.257  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:02.257  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:02.257  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-06 18:57:02.257  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.257  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:02.257  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.257  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.258  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.258  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.258  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.258  3811  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 18:57:02.259  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 18:57:02.259  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-06 18:57:02.259  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:02.259  2688  2711 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:02.259  2688  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.272  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:02.275  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:02.276  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:02.276  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:02.276  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:02.277  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:02.277  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:02.278  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:57:02.278  2688  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 18:57:02.278  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.278  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.281  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.284  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-06 18:57:02.284  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:02.286  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 18:57:02.286  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.287  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:02.288  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-06 18:57:02.288  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:02.292  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 18:57:02.292  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.292  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 18:57:02.292  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:02.292  2688  2711 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:02.292  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 18:57:02.293  3811  3862 D BluetoothAdapter: STATE_ON
,09-06 18:57:02.296  2688  2699 D BtGatt.GattService: registerClient() - UUID=00ba97b1-362b-471b-b9f4-9ec55e873b71
,09-06 18:57:02.296  2688  2707 D BtGatt.GattService: onClientRegistered() - UUID=00ba97b1-362b-471b-b9f4-9ec55e873b71, clientIf=5
09-06 18:57:02.297  3811  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 18:57:02.297  2688  2825 D BtGatt.GattService: start scan with filters
09-06 18:57:02.298  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 18:57:02.298  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.298  2688  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 18:57:02.302  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:02.302  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:02.302  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:02.302  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:02.304  2688  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 18:57:02.304  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.305  2688  2711 D BtGatt.ScanManager: handling starting scan
,09-06 18:57:02.306  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:02.306  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:02.306  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 18:57:02.308  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:02.312  2688  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-06 18:57:02.312  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.312  2688  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 18:57:02.312  3811  3862 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 18:57:02.314  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.315  3811  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 18:57:02.315  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.315  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 18:57:02.315  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.315  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:02.315  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 18:57:02.315  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 18:57:02.315  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:02.315  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 18:57:02.316  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 18:57:02.316  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:02.316  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 18:57:02.316  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.316  2688  2711 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:02.317  2688  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 18:57:02.317  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:02.317  2688  2826 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:02.318  2688  2699 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:02.318  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-06 18:57:02.318  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 18:57:02.319  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 18:57:02.319  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 18:57:02.319  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:02.320  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:02.320  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 18:57:02.320  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 18:57:02.320  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:02.320  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:02.321  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:02.322  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 18:57:02.322  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.322  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 18:57:02.322  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:02.322  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:02.322  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.322  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.322  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list,
09-06 18:57:02.322  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.322  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.323  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-06 18:57:02.323  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.324  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.324  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:02.324  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.324  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.325  2688  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 18:57:02.325  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.325  3811  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 18:57:02.326  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.330  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:02.330  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 18:57:02.331  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.331  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:02.331  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:02.331  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:57:02.332  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 18:57:02.332  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:02.332  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:02.332  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:02.334  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:02.336  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:02.336  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 18:57:02.336  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:57:02.337  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 18:57:02.337  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.337  2688  2711 D BtGatt.ScanManager: stopping BLe Batch
,09-06 18:57:02.340  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:02.340  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 18:57:02.340  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:02.343  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-06 18:57:02.343  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.343  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 18:57:02.343  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:02.343  2688  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
09-06 18:57:02.343  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
09-06 18:57:02.344  3811  3862 D BluetoothAdapter: STATE_ON,
09-06 18:57:02.346  2688  2699 D BtGatt.GattService: registerClient() - UUID=8426b2a0-ed6d-41ea-bdfc-3e132c719739,
09-06 18:57:02.346  2688  2707 D BtGatt.GattService: onClientRegistered() - UUID=8426b2a0-ed6d-41ea-bdfc-3e132c719739, clientIf=5
,09-06 18:57:02.346  3811  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 18:57:02.347  2688  2825 D BtGatt.GattService: start scan with filters
,09-06 18:57:02.348  2688  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 18:57:02.348  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:02.350  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:02.350  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:02.350  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 18:57:02.350  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:02.350  2688  2711 D BtGatt.ScanManager: handling starting scan
09-06 18:57:02.352  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:02.352  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:02.352  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:02.353  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:02.355  3811  3862 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 18:57:02.355  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.355  3811  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:02.355  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.355  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 18:57:02.355  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.355  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:02.355  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:02.355  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-06 18:57:02.355  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:02.355  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:02.355  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 18:57:02.356  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 18:57:02.356  2688  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 18:57:02.356  3811  3862 D BluetoothAdapter: STATE_ON
,09-06 18:57:02.356  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.357  2688  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-06 18:57:02.357  2688  2825 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:02.358  2688  2700 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:02.358  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:02.359  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 18:57:02.359  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:02.359  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 18:57:02.359  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:02.361  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:02.361  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:02.361  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 18:57:02.361  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:57:02.362  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:02.362  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-06 18:57:02.362  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.362  2688  2711 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:02.363  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:02.363  2688  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 18:57:02.363  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:02.363  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:02.363  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 18:57:02.363  3811  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:02.363  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.363  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.363  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:02.363  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.364  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:02.364  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.364  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.364  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.364  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.364  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.364  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.364  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.365  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.365  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.365  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.365  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.366  3811  3862 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 18:57:02.366  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.366  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.366  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:02.366  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.366  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.366  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.366  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.366  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.367  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.367  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.367  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.367  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.367  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.367  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.368  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.368  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.368  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.368  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.368  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:57:02.369  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.369  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.369  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:02.369  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.369  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 18:57:02.369  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.369  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.369  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.369  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.369  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.369  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.369  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.369  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 18:57:02.369  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.370  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.370  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-06 18:57:02.370  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.370  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.371  3811  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 18:57:02.371  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.371  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.371  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:02.371  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:02.371  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.371  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.371  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.371  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.372  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.372  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.372  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.372  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.372  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.372  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.372  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.372  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:02.372  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.372  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.373  2688  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 18:57:02.373  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.373  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 18:57:02.373  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.373  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.375  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:02.375  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.375  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.375  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.375  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
,09-06 18:57:02.375  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.375  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.375  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.376  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.376  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.376  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.376  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.376  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.376  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.376  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.376  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.377  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 18:57:02.378  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:57:02.378  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:02.378  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 18:57:02.378  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:57:02.379  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:57:02.379  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 18:57:02.379  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:02.379  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:02.379  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.379  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.379  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.379  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.379  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.379  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.379  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:02.379  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
,09-06 18:57:02.380  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:02.380  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.380  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:02.380  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:02.380  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.380  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.380  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:02.380  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.381  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.381  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 18:57:02.381  3811  3862 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:57:02.381  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 18:57:02.384  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:02.385  3811  3862 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-06 18:57:02.386  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:57:02.387  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 18:57:02.387  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:57:02.387  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-06 18:57:02.387  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:57:02.387  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 18:57:02.388  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:57:02.389  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:57:02.389  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:57:02.389  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 18:57:02.388  2688  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 18:57:02.389  3811  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:02.389  3811  3862 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 18:57:02.389  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.389  2688  2711 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:02.389  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:02.390  3811  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:02.390  3811  3862 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 18:57:02.390  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:02.390  3811  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:02.390  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 18:57:02.393  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 18:57:02.394  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 18:57:02.394  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 18:57:02.394  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 18:57:02.396  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 18:57:02.396  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 18:57:02.396  3811  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:02.396  3811  3862 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 18:57:02.396  3811  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-06 18:57:02.397  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.397  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.397  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.397  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.397  2688  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 18:57:02.397  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.397  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.397  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.397  2688  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 18:57:02.397  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 18:57:02.398  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.398  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.398  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.398  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.398  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.398  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.398  3811  3871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:57:02.398  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.398  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.399  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.399  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.399  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.399  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.399  3811  3862 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 18:57:02.400  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.400  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.400  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.402  3811  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-06 18:57:02.402  3811  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
09-06 18:57:02.402  2688  2814 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-06 18:57:02.402  3811  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-06 18:57:02.402  3811  3872 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
09-06 18:57:02.403  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.403  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.403  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.403  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.403  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.403  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.403  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.403  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.403  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.403  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.403  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.404  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.404  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.404  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.404  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.404  2688  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 18:57:02.405  2688  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:02.405  3811  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 18:57:02.405  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.405  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.405  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.405  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.405  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.405  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.405  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.405  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.405  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.406  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.406  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.406  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.406  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.406  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.406  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.406  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.407  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.407  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.407  3811  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 18:57:02.407  3811  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 18:57:02.407  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:57:02.407  3811  3862 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 18:57:02.407  3811  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:57:02.407  3811  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 18:57:02.408  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:02.408  3811  3862 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 18:57:02.408  3811  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:57:02.408  3811  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:57:02.408  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:02.408  3811  3862 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 18:57:02.408  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.408  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.408  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.408  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.408  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.408  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.408  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.408  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.409  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.409  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.409  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.409  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.409  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.409  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.410  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.410  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.410  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.410  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.410  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.410  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.411  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.411  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.411  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.411  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.411  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.411  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.411  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.411  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.411  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.411  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.411  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.412  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.412  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.412  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.412  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.412  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.412  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.412  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.412  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.412  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.412  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.413  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.413  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.413  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.413  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.413  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.413  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.414  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.414  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.414  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.414  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.415  3811  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 18:57:02.415  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:02.416  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 18:57:02.417  3811  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 18:57:02.417  3811  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 18:57:02.417  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 18:57:02.417  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:02.417  3811  3811 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 18:57:02.418  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.418  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 18:57:02.418  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 18:57:02.418  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.418  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.418  3811  3811 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 18:57:02.418  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:02.418  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.418  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.418  3811  3873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:57:02.419  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:02.419  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.419  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.419  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:02.419  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.419  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:02.419  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.420  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.420  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.420  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.420  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:02.420  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.420  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.420  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.420  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.420  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.420  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.420  3811  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-06 18:57:02.420  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.420  3811  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 18:57:02.420  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.420  3811  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 18:57:02.421  3811  3811 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 18:57:02.421  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:02.421  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.421  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.421  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.422  3811  3862 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 18:57:02.422  3811  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:57:02.422  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:02.422  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:57:02.422  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.422  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.423  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.423  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.423  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.423  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.423  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.423  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.423  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.423  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.423  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.423  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.423  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.423  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.424  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.424  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.424  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.424  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.427  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.427  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.427  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.427  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.427  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.427  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.427  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.427  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.428  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.428  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.428  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.428  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.428  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.428  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.428  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.428  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.429  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.429  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.429  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:02.429  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:02.429  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:02.429  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:02.429  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.429  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.429  3811  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a263299 not in the list
09-06 18:57:02.430  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.430  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.430  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:02.430  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.430  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.430  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:02.430  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:02.431  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:02.431  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:02.431  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:02.431  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@104595e not in the list
09-06 18:57:02.431  3811  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 18:57:02.431  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:57:02.432  3811  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-06 18:57:02.432  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-06 18:57:02.432  3811  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 18:57:02.432  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:02.433  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:57:02.433  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-06 18:57:02.434  3811  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 18:57:02.434  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 18:57:02.434  3811  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 18:57:02.434  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-06 18:57:02.434  3811  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 18:57:02.434  3811  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-06 18:57:02.435  3811  3862 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 18:57:02.436  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:02.436  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8743110 added. We now have 2 listener(s)
,09-06 18:57:02.436  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:02.438  3811  3862 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 18:57:02.438   873  1921 D WifiService: setWifiEnabled: true pid=3811, uid=10000
,09-06 18:57:02.438   873  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 18:57:02.438  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:02.439  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cbf409 added. We now have 3 listener(s)
09-06 18:57:02.439  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:02.443  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:02.443  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d27d60e added. We now have 4 listener(s)
09-06 18:57:02.443  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:02.445  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:02.445  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a02982f added. We now have 5 listener(s)
,09-06 18:57:02.445  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:02.447   873  1983 D WifiService: setWifiEnabled: false pid=3811, uid=10000
09-06 18:57:02.447   873  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-06 18:57:02.452  2688  2703 D BluetoothAdapterState: Current state: ON, message: 23
09-06 18:57:02.452  2688  2703 D BluetoothAdapterProperties: Setting state to 13
09-06 18:57:02.452  2688  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 18:57:02.452  2688  2703 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 18:57:02.453  2688  2703 I BluetoothAdapterState: Entering PendingCommandState
,09-06 18:57:02.453  2688  2707 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:02.454  2688  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 18:57:02.454  2688  2688 D BluetoothMapService: onReceive
09-06 18:57:02.454  2688  2688 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:02.454  2688  2688 D BluetoothMapService: STATE_TURNING_OFF
09-06 18:57:02.454  2688  2688 D BluetoothMapService: MAP Service closeService in
09-06 18:57:02.454  2688  2688 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 18:57:02.455  2688  2688 D ObexServerSockets0: shutdown(block = true)
09-06 18:57:02.455  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 18:57:02.455  2688  2827 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 18:57:02.455  2688  2688 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 18:57:02.455  2688  2814 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 18:57:02.456  2688  2828 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-06 18:57:02.456  2688  2688 I BtOppRfcommListener: stopping Accept Thread
09-06 18:57:02.457  2688  3425 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:57:02.457  2688  3425 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 18:57:02.458  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.458  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:02.458  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.459  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.460  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.468  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-06 18:57:02.471   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 18:57:02.471   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-06 18:57:02.471   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 18:57:02.471   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 18:57:02.477   873  1845 D DhcpClient: Clearing IP address
09-06 18:57:02.477   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:57:02.480   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:02.481   873   886 I ActivityManager: Start proc 3876:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-06 18:57:02.482  1515  3453 V NativeCrypto: Read error: ssl=0x9b6f3800: I/O error during system call, Connection timed out
09-06 18:57:02.483  1515  3453 V NativeCrypto: SSL shutdown failed: ssl=0x9b6f3800: I/O error during system call, Broken pipe
09-06 18:57:02.484  2688  2688 D HeadsetService: Received stop request...Stopping profile...
09-06 18:57:02.484  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:02.487  1967  1982 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:02.487   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:02.487   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:02.487   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:02.487  1362  1375 D BluetoothHeadset: Proxy object disconnected
,09-06 18:57:02.488  2688  2688 D A2dpService: Received stop request...Stopping profile...
09-06 18:57:02.489  2688  2820 D A2dpStateMachine: Exit Disconnected: -1
09-06 18:57:02.489  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:02.489  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:02.490   873   873 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:02.490  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-06 18:57:02.491  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.491  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:02.491  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:02.491   873  2014 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-06 18:57:02.492   873  1837 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-06 18:57:02.490  1362  1362 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:02.493  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.493  2688  2688 D HidService: Received stop request...Stopping profile...
09-06 18:57:02.493  2688  2688 D HidService: Stopping Bluetooth HidService
09-06 18:57:02.494  1362  1362 D BluetoothInputDevice: Proxy object disconnected
09-06 18:57:02.494  1362  1362 D HidProfile: Bluetooth service disconnected
09-06 18:57:02.494   873  1837 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-06 18:57:02.495  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.495  2688  2688 V BluetoothAdapterState: isTurningOn()=false
,09-06 18:57:02.495   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-06 18:57:02.495  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.495  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.495   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-06 18:57:02.496   873  1850 D DhcpClient: Receive thread stopped
09-06 18:57:02.496   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 18:57:02.498  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.498  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 18:57:02.498  2688  2688 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:57:02.498  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-06 18:57:02.498  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:02.498  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:02.499  2688  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 18:57:02.499  2688  2707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-06 18:57:02.500   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
09-06 18:57:02.501   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-06 18:57:02.503   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-06 18:57:02.502   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:57:02.503   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-06 18:57:02.506  2688  2688 D HealthService: Received stop request...Stopping profile...
,09-06 18:57:02.509   397   397 E Parcel  : Reading a NULL string not supported here.
09-06 18:57:02.509   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-06 18:57:02.510  2688  2688 D PanService: Received stop request...Stopping profile...
09-06 18:57:02.511  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.511  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:02.511  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.511  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.511  2688  2688 D BluetoothMapService: Received stop request...Stopping profile...
09-06 18:57:02.511  2688  2688 D BluetoothMapService: stop()
09-06 18:57:02.513  2688  2688 D BluetoothMapAppObserver: deinitObservers()
09-06 18:57:02.513  2688  2688 D BluetoothMapAppObserver: removeReceiver()
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.515  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:02.516  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.516  2688  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:02.516  2688  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:02.516  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:57:02.516  2688  2797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:02.516  1362  1362 D PanProfile: Bluetooth service disconnected
09-06 18:57:02.516  2688  2797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:02.516  2688  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 18:57:02.516  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:57:02.516  2688  2688 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:57:02.516  2688  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.516  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.517  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:57:02.517  2688  2707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 18:57:02.517  1362  1362 D BluetoothMap: Proxy object disconnected
09-06 18:57:02.517  1362  1362 D MapProfile: Bluetooth service disconnected
09-06 18:57:02.517  2688  2688 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.517  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.518  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:57:02.518  2688  2688 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 18:57:02.518  2688  2688 D BluetoothMapService: MAP Service closeService in
09-06 18:57:02.519  2688  2688 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:02.519  2688  2688 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:02.519  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:02.519  2688  2688 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:02.519  2688  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 18:57:02.519  2688  2688 D BluetoothMapService: cleanup()
09-06 18:57:02.519  2688  2688 D BluetoothMapService: MAP Service closeService in
09-06 18:57:02.519  2688  2703 D BluetoothAdapterProperties: Setting state to 15
09-06 18:57:02.519  2688  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 18:57:02.520  2688  2703 I BluetoothAdapterState: Entering BleOnState
09-06 18:57:02.520  1362  2089 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:02.521  1362  2090 D BluetoothPan: onBluetoothStateChange on: false
09-06 18:57:02.521  1967  2118 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:02.522  1362  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:02.522   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:02.522   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:02.522  1362  2089 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 18:57:02.523  1362  2090 D BluetoothMap: onBluetoothStateChange: up=false
09-06 18:57:02.523   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 18:57:02.524  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:57:02.526   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:02.526   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:02.526  2688  2703 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 18:57:02.527  2688  2703 D BluetoothAdapterProperties: Setting state to 16
09-06 18:57:02.527  2688  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 18:57:02.528  1905  2338 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:57:02.528  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:02.528  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:02.529  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.529  2688  2703 D BluetoothAdapterProperties: onBleDisable
09-06 18:57:02.529  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:02.529  2688  2703 I BluetoothAdapterState: Entering PendingCommandState
09-06 18:57:02.530  2688  2704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 18:57:02.531  2688  2707 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:02.531  2688  2797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 18:57:02.531  2688  2797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:02.531  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:02.531  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:02.532  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:02.532  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:02.533  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.534   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 18:57:02.534  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.536  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.536  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.551   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:02.574   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:02.575   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-06 18:57:02.575   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:02.577   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:02.580  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:02.580  3413  3413 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a24f009 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-06 18:57:02.581  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:02.597  3876  3876 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-06 18:57:02.609  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:02.614  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:57:02.614   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b90fb7b:true
,09-06 18:57:02.626   873  1372 I ActivityManager: Start proc 3897:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-06 18:57:02.637   374   871 E Netd    : netlink response contains error (No such file or directory)
,09-06 18:57:02.638   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 18:57:02.651  3876  3876 D LocalBluetoothProfileManager: Adding local MAP profile
,09-06 18:57:02.653  3876  3876 D BluetoothMap: Create BluetoothMap proxy object
,09-06 18:57:02.660  3897  3897 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-06 18:57:02.661  3876  3876 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-06 18:57:02.671  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:02.679   873   884 I ActivityManager: Killing 3064:com.google.android.talk/u0a61 (adj 15): empty #17
,09-06 18:57:02.734  2688  2707 I bt_hci  : shut_down
,09-06 18:57:02.738  2688  2714 I bt_vendor: low_power_mode_cb
,09-06 18:57:02.741  2688  2714 D bt_hwcfg: hw_epilog_process
,09-06 18:57:02.767  2688  2714 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 18:57:02.767  2688  2714 I bt_vendor: epilog_cb
09-06 18:57:02.767  2688  2714 I bt_hci  : epilog_finished_callback
,09-06 18:57:02.769  2688  2707 I bt_hci_h4: hal_close
,09-06 18:57:02.770  2688  2707 I bt_userial_vendor: device fd = 51 close
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.k.d(PG:583)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.exists(File.java:361)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.808  3897  3897 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:02.808  3897  3897 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-06 18:57:02.845   873  1921 I ActivityManager: Start proc 3927:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-06 18:57:02.846   873  1921 I ActivityManager: Killing 3576:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-06 18:57:02.894  2688  2704 D bt_stack_manager: event_shut_down_stack finished.
,09-06 18:57:02.895  2688  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 18:57:02.896  2688  2703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 18:57:02.897  2688  2688 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 18:57:02.898  2688  2688 D BtGatt.GattService: Received stop request...Stopping profile...
,09-06 18:57:02.898  2688  2688 D BtGatt.GattService: stop()
,09-06 18:57:02.899  2688  2688 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 18:57:02.902  2688  2688 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:02.902  2688  2688 V BluetoothAdapterState: isTurningOn()=false
,09-06 18:57:02.902  2688  2688 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:02.902  2688  2688 V BluetoothAdapterState: isBleTurningOff()=true
09-06 18:57:02.903  2688  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-06 18:57:02.903  2688  2703 D BluetoothAdapterProperties: Setting state to 10
09-06 18:57:02.903  2688  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 18:57:02.904  2688  2703 I BluetoothAdapterState: Entering OffState
,09-06 18:57:02.906   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 18:57:02.909  3927  3927 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-06 18:57:02.915  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-06 18:57:02.915  2688  2688 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 18:57:02.915  2688  2704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-06 18:57:02.916  2688  2704 D bt_stack_manager: event_clean_up_stack finished.
09-06 18:57:02.916  2688  2688 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 18:57:02.921  3811  3811 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:02.931  2688  2688 I art     : System.exit called, status: 0
09-06 18:57:02.931  2688  2688 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 18:57:02.971   873  1984 I ActivityManager: Process com.android.bluetooth (pid 2688) has died
,09-06 18:57:03.077  3927  3947 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 18:57:03.077  3927  3947 I Babel_SMS: MmsConfig.loadMmsSettings
09-06 18:57:03.078  3927  3947 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-06 18:57:03.078  3927  3947 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 18:57:03.116  3927  3947 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-06 18:57:03.116  3927  3947 I Babel_SMS: MmsConfig.loadFromResources
,09-06 18:57:03.122  3927  3947 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 18:57:03.122  3927  3947 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-06 18:57:03.174  3927  3927 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:57:03.180  3927  3927 I Babel_Crash: startup - clean
,09-06 18:57:03.217  3927  3927 I Babel_telephony: TeleModule.launchCompleted
,09-06 18:57:03.257   873  1372 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 18:57:03.288  3927  3927 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-06 18:57:03.296  3927  3927 W Babel   : BAM#gBA: invalid account id: -1
,09-06 18:57:03.300  3927  3927 W Babel   : BAM#gBA: invalid account id: -1
,09-06 18:57:03.300  3927  3927 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-06 18:57:03.305   873   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-06 18:57:03.317  3927  3953 I Babel   : deleted: false for 0
,09-06 18:57:03.336   873  1921 I ActivityManager: Start proc 3955:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-06 18:57:03.400  3927  3927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:03.427  3955  3955 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-06 18:57:03.476  3927  3927 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 18:57:03.490  3927  3927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:03.504  3927  3927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:03.508  3927  3927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:03.519  3927  3927 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:03.543  3927  3927 I vclib   : onServiceConnected
,09-06 18:57:03.550  3955  3955 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-06 18:57:03.563  3897  3923 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 18:57:03.593  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:03.622   873  2015 I ActivityManager: Start proc 3980:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-06 18:57:03.625  3876  3876 D DockEventReceiver: finishStartingService: stopping service
09-06 18:57:03.628   873   884 I ActivityManager: Killing 3413:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-06 18:57:03.682   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@afd52d3:true
,09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding HeadsetService
,09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding A2dpService
09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding HidService
,09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding HealthService
09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding PanService
,09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding GattService
,09-06 18:57:03.762  3980  3980 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 18:57:03.767   873  1921 I ActivityManager: Killing 3463:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-06 18:57:03.800  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:03.811  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 18:57:03.818  1727  1727 D SystemUpdateService: onCreate
,09-06 18:57:03.828  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 18:57:03.845  1727  3992 I SystemUpdateService: active receiver: enabled
,09-06 18:57:03.853  1727  3992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 18:57:03.861  1727  3992 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 18:57:03.861  1727  3992 I SystemUpdateService: now status is 0 (complete)
09-06 18:57:03.862  1727  3992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 18:57:03.862  1727  3992 I SystemUpdateService: file has been verified
09-06 18:57:03.863  1727  3992 I SystemUpdateService: OTA package size = 12249756
,09-06 18:57:03.863  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 18:57:03.868  1727  2301 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:03.870  1727  3992 I SystemUpdateService: showing system update notification,
,09-06 18:57:03.870  1727  2301 I iu.UploadsManager: num updated entries: 0
,09-06 18:57:03.871  1727  2301 I iu.SyncManager: NEXT; no task
,09-06 18:57:03.894  1727  1727 D SystemUpdateService: onDestroy
,09-06 18:57:03.897  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 18:57:03.898  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 18:57:03.921   873  2018 I ActivityManager: Start proc 3994:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-06 18:57:03.991  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-06 18:57:03.998  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:04.003  3994  3994 D SprintDMHelper: simOperator: 
,09-06 18:57:04.003  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 18:57:04.044   873  2018 I ActivityManager: Start proc 4006:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-06 18:57:04.045   873  2018 I ActivityManager: Killing 3507:android.process.acore/u0a5 (adj 15): empty #17
,09-06 18:57:04.225   873  1984 I ActivityManager: Start proc 4021:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-06 18:57:04.229  3927  4020 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 18:57:04.233   873  1936 I ActivityManager: Killing 3667:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-06 18:57:04.281  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-06 18:57:04.340  4021  4021 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 18:57:04.340  4021  4021 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 18:57:04.340  4021  4021 I GAv4    :   adb logcat -s GAv4
,09-06 18:57:04.357  4021  4021 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 18:57:04.364  4021  4021 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 18:57:04.389  4021  4038 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 18:57:04.504  4021  4021 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-06 18:57:04.543  4021  4021 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-06 18:57:04.552  4021  4021 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3262-3265)
,09-06 18:57:04.552  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 18:57:04.572  4021  4021 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56ced79}
,09-06 18:57:04.572  4021  4021 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 18:57:04.573  4021  4021 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 18:57:04.582  4021  4021 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 18:57:04.584  4021  4021 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 18:57:04.607  4021  4021 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-06 18:57:04.623  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 18:57:04.623  4021  4021 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 18:57:04.623  4021  4021 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 18:57:04.623  4021  4021 I Adreno  : Build Date                       : 10/20/15
09-06 18:57:04.623  4021  4021 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 18:57:04.623  4021  4021 I Adreno  : Local Branch                     : M14
09-06 18:57:04.623  4021  4021 I Adreno  : Remote Branch                    : 
09-06 18:57:04.623  4021  4021 I Adreno  : Remote Branch                    : 
09-06 18:57:04.623  4021  4021 I Adreno  : Reconstruct Branch               : 
,09-06 18:57:04.687  4021  4021 I NSApplication: Starting up...
,09-06 18:57:04.695  4021  4067 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 18:57:04.728   873  1984 I ActivityManager: Start proc 4072:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-06 18:57:04.734   873  1984 I ActivityManager: Killing 3682:com.android.musicfx/u0a18 (adj 15): empty #17
,09-06 18:57:04.812  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-06 18:57:05.023   873  1983 I ActivityManager: Killing 2179:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-06 18:57:05.493   873  1983 D WifiService: setWifiEnabled: true pid=3811, uid=10000
,09-06 18:57:05.494   873  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:57:05.512   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-06 18:57:05.525  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:05.525  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:05.526  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:05.526  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:05.529  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:05.530  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:05.530  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:05.530  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:05.563   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-06 18:57:05.564   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 18:57:05.564   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 18:57:05.565   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-06 18:57:05.566   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-06 18:57:05.566   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-06 18:57:05.566   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 18:57:05.582   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=13.00 delta 1000 -> 994
,09-06 18:57:05.582   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 18:57:05.585   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:05.586   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-06 18:57:05.587   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 18:57:05.598   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 18:57:05.598   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:05.606   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 18:57:05.653   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 18:57:05.656  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 18:57:05.716   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 18:57:05.722   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 18:57:06.119  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 18:57:06.163  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 18:57:06.165  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 18:57:06.172   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 18:57:06.187   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 18:57:06.187   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 18:57:06.187   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:06.213   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:06.227   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:06.228   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,09-06 18:57:06.245   873  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-06 18:57:06.248   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 18:57:06.275   873  4096 D DhcpClient: Receive thread started
,09-06 18:57:06.361   873  1307 E native  : do suspend false
,09-06 18:57:06.379   873  1845 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 18:57:06.405   873  4096 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172697, domain null
,09-06 18:57:06.406   873  1845 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172697 seconds
,09-06 18:57:06.410   873  1845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 18:57:06.424   873  4096 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 18:57:06.425   873  1845 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 18:57:06.430   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:06.441   873  1845 D DhcpClient: Scheduling renewal in 86399s
09-06 18:57:06.443   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 18:57:06.454   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 18:57:06.457   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 18:57:06.457   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled,
,09-06 18:57:06.458   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 18:57:06.462   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,09-06 18:57:06.472   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 18:57:06.538   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 18:57:06.538   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
09-06 18:57:06.539   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-06 18:57:06.540   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-06 18:57:06.541   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-06 18:57:06.549   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-06 18:57:06.556   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-06 18:57:06.556   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-06 18:57:06.556   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-06 18:57:06.556   873  1309 D ConnectivityService:    accepting network in place of null
,09-06 18:57:06.557   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-06 18:57:06.558   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 18:57:06.559   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 18:57:06.566   873  4094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125279, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 18:57:06.612   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:06.649   873  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:817::200e
,09-06 18:57:06.678   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:06.688   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 18:57:06.689   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:06.695   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-06 18:57:06.697   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:06.706  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.706  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:06.707  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:06.707  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.711  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.711  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:06.712  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:06.712  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:06.723  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 18:57:06.726  1727  1727 D SystemUpdateService: onCreate
,09-06 18:57:06.730  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 18:57:06.732   873  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 16:57:06 GMT], X-Android-Received-Millis=[1473181026731], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473181026700]}
,09-06 18:57:06.733   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 18:57:06.733  1727  4108 I SystemUpdateService: active receiver: enabled
09-06 18:57:06.734   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-06 18:57:06.734   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-06 18:57:06.735   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 18:57:06.740  1727  4108 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 18:57:06.742  1727  4108 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-06 18:57:06.742  1727  4108 I SystemUpdateService: now status is 0 (complete)
,09-06 18:57:06.742  1727  4108 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 18:57:06.742  1727  4108 I SystemUpdateService: file has been verified
09-06 18:57:06.743  1727  4108 I SystemUpdateService: OTA package size = 12249756
,09-06 18:57:06.747  1727  4108 I SystemUpdateService: showing system update notification
,09-06 18:57:06.753  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 18:57:06.759  1727  2301 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:06.761  1727  2301 I iu.UploadsManager: num updated entries: 0
,09-06 18:57:06.764  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 18:57:06.764  1727  2301 I iu.SyncManager: NEXT; no task
,09-06 18:57:06.765  1727  4112 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 18:57:06.765  1727  4112 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 18:57:06.765  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 18:57:06.766  1727  1727 D SystemUpdateService: onDestroy
09-06 18:57:06.767  1727  4112 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
09-06 18:57:06.767  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:06.771  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 18:57:06.772  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 18:57:06.774  3994  3994 D SprintDMHelper: simOperator: 
,09-06 18:57:06.774  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 18:57:06.799  1515  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 18:57:06.799  1515  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 18:57:06.800  1515  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-06 18:57:06.800  1515  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 18:57:06.819  1727  4112 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-06 18:57:06.958  3927  4115 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 18:57:07.286  1727  1727 I GCM     : Message from null null
,09-06 18:57:07.287  1727  1727 E GCM     : Dropping message from null
,09-06 18:57:07.688   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-06 18:57:08.446   873  1984 I ActivityManager: Killing 3705:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-06 18:57:08.506   873  1921 D WifiService: setWifiEnabled: false pid=3811, uid=10000
,09-06 18:57:08.507   873  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:57:08.536  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-06 18:57:08.540   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 18:57:08.540   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-06 18:57:08.540   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 18:57:08.541   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:08.554   873  1845 D DhcpClient: Clearing IP address
,09-06 18:57:08.554   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:57:08.557   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:08.559  1515  4122 V NativeCrypto: Read error: ssl=0x9a9bb000: I/O error during system call, Connection timed out
09-06 18:57:08.561  1515  4122 V NativeCrypto: SSL shutdown failed: ssl=0x9a9bb000: I/O error during system call, Broken pipe
,09-06 18:57:08.567   873  4096 D DhcpClient: Receive thread stopped
,09-06 18:57:08.569   873  2014 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-06 18:57:08.570   873  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-06 18:57:08.570   873  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:817::200e
,09-06 18:57:08.571   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-06 18:57:08.571   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-06 18:57:08.585   873  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-06 18:57:08.586   397   397 E Parcel  : Reading a NULL string not supported here.
09-06 18:57:08.589   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
09-06 18:57:08.589   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-06 18:57:08.590   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 18:57:08.619   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:08.644   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:08.644   374   871 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:57:08.645   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-06 18:57:08.645   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 18:57:08.647   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:08.652  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:08.652  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:08.652  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.653  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:08.654  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:08.654  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:08.654  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.654  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:08.656   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
09-06 18:57:08.658   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 18:57:08.660  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:08.660  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:08.660  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.660  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:08.661  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:08.661  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:08.661  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:08.661  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:08.663  1905  2338 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:57:08.674  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 18:57:08.678  1727  1727 D SystemUpdateService: onCreate
,09-06 18:57:08.680  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 18:57:08.683  1727  4131 I SystemUpdateService: active receiver: enabled
,09-06 18:57:08.690  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 18:57:08.693  1727  2301 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:08.695  1727  4131 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-06 18:57:08.697  1727  4131 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-06 18:57:08.697  1727  4131 I SystemUpdateService: now status is 0 (complete)
09-06 18:57:08.697  1727  4131 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-06 18:57:08.697  1727  4131 I SystemUpdateService: file has been verified
09-06 18:57:08.697  1727  4131 I SystemUpdateService: OTA package size = 12249756
,09-06 18:57:08.698  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 18:57:08.699  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-06 18:57:08.701  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:08.695  1727  2301 I iu.UploadsManager: num updated entries: 0
,09-06 18:57:08.705  3994  3994 D SprintDMHelper: simOperator: 
,09-06 18:57:08.705  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-06 18:57:08.712  1727  2301 I iu.SyncManager: NEXT; no task
,09-06 18:57:08.724   374   871 E Netd    : netlink response contains error (No such file or directory)
,09-06 18:57:08.725   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-06 18:57:08.726   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-06 18:57:08.733  3927  4135 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-06 18:57:08.739  1727  4131 I SystemUpdateService: showing system update notification
,09-06 18:57:08.794  1727  1727 D SystemUpdateService: onDestroy
,09-06 18:57:11.558   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4162130:true
,09-06 18:57:11.561  3980  3980 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 18:57:11.566  3980  3980 I bt_bluedroid: init
,09-06 18:57:11.567  3980  4139 I BluetoothAdapterState: Entering OffState
,09-06 18:57:11.569  3980  4140 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 18:57:11.569  3980  4140 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 18:57:11.570  3980  4140 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 18:57:11.570  3980  4140 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 18:57:11.571  3980  3980 I bt_bluedroid: get_profile_interface socket
,09-06 18:57:11.575  3980  3980 I bt_bluedroid: get_profile_interface sdp
,09-06 18:57:11.582  3980  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 18:57:11.583  3980  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 18:57:11.585  3980  3990 I bt_bluedroid: config_hci_snoop_log
,09-06 18:57:11.597   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 18:57:11.607  3980  4139 D BluetoothAdapterState: Current state: OFF, message: 0
09-06 18:57:11.607  3980  4139 D BluetoothAdapterProperties: Setting state to 14
09-06 18:57:11.607  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 18:57:11.609  3980  4139 D BluetoothBondStateMachine: make
,09-06 18:57:11.612  3980  4144 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 18:57:11.616  3980  3980 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 18:57:11.619  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:11.620  3980  3980 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:57:11.621  3980  4139 I BluetoothAdapterState: Entering PendingCommandState
09-06 18:57:11.621  3980  3980 D BtGatt.GattService: Received start request. Starting profile...
09-06 18:57:11.621  3980  3980 D BtGatt.GattService: start()
,09-06 18:57:11.621  3980  3980 I bt_bluedroid: get_profile_interface gatt
09-06 18:57:11.622  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:11.623  3980  3980 D BtGatt.AdvertiseManager: advertise manager created
,09-06 18:57:11.634  3980  3980 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:11.634  3980  3980 V BluetoothAdapterState: isTurningOn()=false
,09-06 18:57:11.635  3980  3980 V BluetoothAdapterState: isBleTurningOn()=true
,09-06 18:57:11.636  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:11.636  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-06 18:57:11.637  3980  4139 I bt_bluedroid: enable
09-06 18:57:11.637  3980  4140 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-06 18:57:11.637  3980  4140 I bt_hci  : start_up
,09-06 18:57:11.646  3980  4140 I bt_vendor: alloc value 0xb3a44189
,09-06 18:57:11.646  3980  4140 I bt_vendor: init
,09-06 18:57:11.646  3980  4140 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 18:57:11.646  3980  4140 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 18:57:11.689   873   882 I art     : Background partial concurrent mark sweep GC freed 60688(3MB) AllocSpace objects, 10(288KB) LOS objects, 33% free, 29MB/43MB, paused 1.093ms total 102.381ms
,09-06 18:57:11.752  3980  4140 D bt_hci  : start_up starting async portion
,09-06 18:57:11.752  3980  4147 I bt_hci  : event_finish_startup
09-06 18:57:11.752  3980  4147 I bt_hci_h4: hal_open
,09-06 18:57:11.752  3980  4147 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 18:57:11.759  3980  4147 I bt_userial_vendor: device fd = 51 open
,09-06 18:57:11.794  3980  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 18:57:11.827  3980  4147 D bt_hwcfg: Chipset BCM4354A2
09-06 18:57:11.827  3980  4147 D bt_hwcfg: Target name = [BCM4354A2]
09-06 18:57:11.828  3980  4147 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 18:57:12.491  3980  4147 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 18:57:12.493  3980  4147 D bt_hwcfg: Settlement delay -- 100 ms
,09-06 18:57:12.493  3980  4147 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 18:57:12.609  3980  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 18:57:12.611  3980  4147 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 18:57:12.641  3980  4147 I bt_hwcfg: vendor lib fwcfg completed
,09-06 18:57:12.641  3980  4147 I bt_vendor: firmware callback
,09-06 18:57:12.641  3980  4147 I bt_hci  : firmware_config_callback
,09-06 18:57:12.654  3980  4149 I bt_btu  : btu_task pending for preload complete event
,09-06 18:57:12.654  3980  4149 I bt_btu_task: Bluetooth chip preload is complete
,09-06 18:57:12.654  3980  4149 I bt_btu  : btu_task received preload complete event
,09-06 18:57:12.664  3980  4149 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 18:57:12.664  3980  4149 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 18:57:12.665  3980  4149 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 18:57:12.665  3980  4149 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 18:57:12.665  3980  4149 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:57:12.665  3980  4149 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 18:57:12.666  3980  4149 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:57:12.666  3980  4149 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 18:57:12.666  3980  4149 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 18:57:12.666  3980  4149 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 18:57:12.667  3980  4149 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 18:57:12.667  3980  4149 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 18:57:12.667  3980  4149 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 18:57:12.668  3980  4149 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 18:57:12.668  3980  4149 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 18:57:12.803  3980  4149 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c1d9d
,09-06 18:57:12.804  3980  4149 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c1d9d 
,09-06 18:57:12.814  3980  4143 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 18:57:12.815  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 18:57:12.816  3980  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 18:57:12.820  3980  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 18:57:12.824  3980  4143 D BluetoothAdapterProperties: Scan Mode:20
,09-06 18:57:12.824  3980  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 18:57:12.824  3980  4143 D bt_hci  : do_postload posting postload work item
,09-06 18:57:12.827  3980  4147 I bt_hci  : event_postload
09-06 18:57:12.827  3980  4147 I bt_vendor: sco_config_cb
09-06 18:57:12.827  3980  4147 I bt_hci  : sco_config_callback postload finished.
09-06 18:57:12.829  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:12.831  3980  4143 D bt_bte_conf: Device ID record 1 : primary
09-06 18:57:12.831  3980  4143 D bt_bte_conf:   vendorId            = 000f
,09-06 18:57:12.831  3980  4143 D bt_bte_conf:   vendorIdSource      = 0001
09-06 18:57:12.832  3980  4143 D bt_bte_conf:   product             = 1200
,09-06 18:57:12.832  3980  4143 D bt_bte_conf:   version             = 1436
09-06 18:57:12.832  3980  4143 D bt_bte_conf:   clientExecutableURL = 
09-06 18:57:12.832  3980  4143 D bt_bte_conf:   serviceDescription  = 
09-06 18:57:12.832  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:12.832  3980  4143 D bt_bte_conf:   documentationURL    = 
09-06 18:57:12.833  3980  4143 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-06 18:57:12.833  3980  4140 D bt_stack_manager: event_start_up_stack finished
09-06 18:57:12.834  3980  4147 I bt_vendor: low_power_mode_cb
,09-06 18:57:12.834  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-06 18:57:12.835  3980  4139 D BluetoothAdapterProperties: Setting state to 15
,09-06 18:57:12.835  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
09-06 18:57:12.837  3980  4139 I BluetoothAdapterState: Entering BleOnState
09-06 18:57:12.842  3980  4139 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 18:57:12.842  3980  4139 D BluetoothAdapterProperties: Setting state to 11
09-06 18:57:12.842  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 18:57:12.854  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:12.857  3980  3980 D HeadsetService: Received start request. Starting profile...
,09-06 18:57:12.865  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:12.867  3980  3980 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:57:12.867  3980  3980 D HeadsetStateMachine: make
,09-06 18:57:12.869  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:12.874  3980  4139 I BluetoothAdapterState: Entering PendingCommandState
,09-06 18:57:12.876  3980  3980 D HeadsetStateMachine: max_hf_connections = 1
,09-06 18:57:12.877  3980  3980 I bt_bluedroid: get_profile_interface handsfree
,09-06 18:57:12.877  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 18:57:12.877  3980  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-06 18:57:12.881  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:12.881  3980  3980 D A2dpService: Received start request. Starting profile...
,09-06 18:57:12.882  3980  3980 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 18:57:12.882  3980  3980 I bt_bluedroid: get_profile_interface avrcp
,09-06 18:57:12.887  3980  3980 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 18:57:12.887  3980  3980 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:57:12.887  3980  3980 D A2dpStateMachine: make
,09-06 18:57:12.888  3980  3980 I bt_bluedroid: get_profile_interface a2dp
,09-06 18:57:12.890  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 18:57:12.890  3980  4159 D A2dpStateMachine: Enter Disconnected: -2
09-06 18:57:12.891  3980  3980 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 18:57:12.892  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:12.893  3980  3980 D HidService: Received start request. Starting profile...
,09-06 18:57:12.893  3980  3980 I bt_bluedroid: get_profile_interface hidhost
09-06 18:57:12.893  3876  3876 D BluetoothInputDevice: Proxy object connected
09-06 18:57:12.893  3980  3980 D HidService: setHidService(): set to: null
09-06 18:57:12.893  3980  4143 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a33e5
09-06 18:57:12.893  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 18:57:12.894  3980  3980 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 18:57:12.894  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:12.895  3876  3876 D HidProfile: Bluetooth service connected
09-06 18:57:12.895  3980  3980 D HealthService: Received start request. Starting profile...
,09-06 18:57:12.896  3980  3980 I bt_bluedroid: get_profile_interface health
,09-06 18:57:12.898  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:12.898  3980  3980 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 18:57:12.899  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:12.900  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 18:57:12.900  3980  3980 D PanService: Received start request. Starting profile...
09-06 18:57:12.900  3980  3980 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:57:12.900  3980  3980 I bt_bluedroid: get_profile_interface pan
09-06 18:57:12.900  3876  3876 D PanProfile: Bluetooth service connected
,09-06 18:57:12.901  3980  4143 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 18:57:12.903  3980  3980 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:12.904  3876  3876 D BluetoothMap: Proxy object connected
,09-06 18:57:12.905  3876  3876 D MapProfile: Bluetooth service connected
09-06 18:57:12.905  3980  3980 D BluetoothMapService: Received start request. Starting profile...
09-06 18:57:12.905  3980  3980 D BluetoothMapService: start()
,09-06 18:57:12.905  3876  3876 D BluetoothMap: getConnectedDevices()
09-06 18:57:12.906  3876  3876 D BluetoothMap: Bluetooth is Not enabled
,09-06 18:57:12.907  3980  3980 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 18:57:12.908  3980  3980 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-06 18:57:12.908  3980  3980 D BluetoothMapAppObserver: createReceiver()
,09-06 18:57:12.909  3980  3980 D BluetoothMapAppObserver: initObservers()
09-06 18:57:12.909  3980  3980 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 18:57:12.915  3980  4157 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 18:57:12.915  3980  3980 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:12.916  3980  3980 V BluetoothAdapterState: isTurningOn()=true
,09-06 18:57:12.916  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:12.916  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:12.917  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:12.918  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:12.918  3980  3980 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:12.918  3980  3980 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:12.918  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:12.918  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:12.920  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:12.920  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-06 18:57:12.921  3980  4139 D BluetoothAdapterProperties: ScanMode =  20
09-06 18:57:12.921  3980  4139 D BluetoothAdapterProperties: State =  11
09-06 18:57:12.923  3980  4139 D BluetoothAdapterProperties: Setting state to 12
09-06 18:57:12.923  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 18:57:12.923  3980  4139 I BluetoothAdapterState: Entering OnState
,09-06 18:57:12.923  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 18:57:12.924  3980  4143 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:57:12.924  3980  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 18:57:12.926  3876  3887 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 18:57:12.927  1362  1362 D BluetoothA2dp: Proxy object connected
,09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:12.928  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:12.929  1362  2089 D BluetoothPan: onBluetoothStateChange on: true
,09-06 18:57:12.930  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:12.931  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 18:57:12.932  1362  1362 D PanProfile: Bluetooth service connected
09-06 18:57:12.932  1967  2118 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:12.932  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:12.933   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:12.933  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:12.933  3876  3889 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 18:57:12.933  3876  3887 D BluetoothPan: onBluetoothStateChange on: true
09-06 18:57:12.933   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:12.934  3876  3889 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 18:57:12.934  1362  2090 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 18:57:12.935  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:12.935  3980  3980 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 18:57:12.936  3980  3980 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-06 18:57:12.936  1362  1362 D BluetoothInputDevice: Proxy object connected
09-06 18:57:12.936  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 18:57:12.937  1362  1362 D HidProfile: Bluetooth service connected
,09-06 18:57:12.937  3980  3980 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:57:12.938  1362  1362 D BluetoothMap: Proxy object connected
09-06 18:57:12.938  1362  2089 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 18:57:12.938  1362  1362 D MapProfile: Bluetooth service connected
09-06 18:57:12.938  1362  1362 D BluetoothMap: getConnectedDevices()
,09-06 18:57:12.939  3980  3980 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:12.939   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:12.939   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:12.940  3980  3980 D ObexServerSockets: Succeed to create listening sockets 
09-06 18:57:12.940   873   873 D BluetoothA2dp: Proxy object connected
09-06 18:57:12.940  3980  3980 D ObexServerSockets0: startAccept()
09-06 18:57:12.941  3980  3980 D ObexServerSockets0: prepareForNewConnect()
09-06 18:57:12.944  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:12.944  3980  3980 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-06 18:57:12.944  3980  3980 D BluetoothSdpJni: SDP Create record success - handle: 0
09-06 18:57:12.945   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 18:57:12.945  3980  3980 D BluetoothMapService: onReceive
09-06 18:57:12.945  3980  3980 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:12.945  3980  3980 D BluetoothMapService: STATE_ON
09-06 18:57:12.945  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:12.946  3980  4166 D ObexServerSockets0: Accepting socket connection...
09-06 18:57:12.947  3876  3876 D LocalBluetoothProfileManager: Adding local A2DP profile
09-06 18:57:12.947  3980  4165 D ObexServerSockets0: Accepting socket connection...
,09-06 18:57:12.952  3876  3876 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-06 18:57:12.957  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:12.960  3876  3876 D BluetoothA2dp: Proxy object connected
,09-06 18:57:12.963  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:12.970  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:12.977  1362  1362 D BluetoothPbap: Proxy object connected
,09-06 18:57:12.977  1362  1362 D PbapServerProfile: Bluetooth service connected
09-06 18:57:12.977  3876  3876 D BluetoothPbap: Proxy object connected
09-06 18:57:12.977  3980  3980 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-06 18:57:12.977  3980  3980 D ObexServerSockets0: prepareForNewConnect()
09-06 18:57:12.978  3876  3876 D PbapServerProfile: Bluetooth service connected
,09-06 18:57:12.990  3980  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:13.013  3980  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:13.015  3980  4174 I BtOppRfcommListener: Accept thread started.
,09-06 18:57:13.034  1967  2164 D BluetoothHeadset: Proxy object connected
09-06 18:57:13.034   873   873 D BluetoothHeadset: Proxy object connected
,09-06 18:57:13.034   873   873 D BluetoothHeadset: Proxy object connected
,09-06 18:57:13.034   873   873 D BluetoothHeadset: Proxy object connected
09-06 18:57:13.034  1362  1376 D BluetoothHeadset: Proxy object connected
,09-06 18:57:13.035  1362  1362 D HeadsetProfile: Bluetooth service connected
,09-06 18:57:13.039   873   890 D BluetoothHeadset: Proxy object connected
,09-06 18:57:13.055  3876  3887 D BluetoothHeadset: Proxy object connected
,09-06 18:57:13.056  3876  3876 D HeadsetProfile: Bluetooth service connected
,09-06 18:57:14.524  3980  4139 D BluetoothAdapterState: Current state: ON, message: 23
09-06 18:57:14.524  3980  4139 D BluetoothAdapterProperties: Setting state to 13
09-06 18:57:14.524  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 18:57:14.526  3980  4139 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 18:57:14.536  3980  3980 D BluetoothMapService: onReceive
,09-06 18:57:14.536  3980  3980 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:14.537  3980  3980 D BluetoothMapService: STATE_TURNING_OFF
,09-06 18:57:14.538  3980  3980 D BluetoothMapService: MAP Service closeService in
,09-06 18:57:14.538  3980  3980 D BluetoothMapMasInstance0: MAP Service shutdown
09-06 18:57:14.538  3980  3980 D ObexServerSockets0: shutdown(block = true)
09-06 18:57:14.539  3980  4165 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-06 18:57:14.542  3980  4139 I BluetoothAdapterState: Entering PendingCommandState
,09-06 18:57:14.542  3980  3980 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-06 18:57:14.543  3980  4166 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-06 18:57:14.546  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:14.547  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:14.547  3980  4152 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-06 18:57:14.548  3980  3980 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-06 18:57:14.549  3980  3980 I BtOppRfcommListener: stopping Accept Thread,
09-06 18:57:14.549  3980  4174 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 18:57:14.550  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:14.550  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:14.552  3980  4174 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-06 18:57:14.552  3980  4143 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:14.553  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-06 18:57:14.553  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 18:57:14.556  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:14.556  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:14.557  3811  3811 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:14.557  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:14.560  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:14.561  3980  3980 D HeadsetService: Received stop request...Stopping profile...
09-06 18:57:14.562   873  1309 D ConnectivityService: handlePromptUnvalidated 101
09-06 18:57:14.562  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:14.564  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 18:57:14.565  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:14.569  1967  1980 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.569   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.569   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.570  3980  3980 D A2dpService: Received stop request...Stopping profile...
09-06 18:57:14.570  3980  4159 D A2dpStateMachine: Exit Disconnected: -1
09-06 18:57:14.570  3876  3889 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.570   873   873 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.571  1362  1376 D BluetoothHeadset: Proxy object disconnected
09-06 18:57:14.572  1362  1362 D HeadsetProfile: Bluetooth service disconnected
09-06 18:57:14.572   873   873 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:14.572  3876  3876 D HeadsetProfile: Bluetooth service disconnected
09-06 18:57:14.572  1362  1362 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:14.572  3876  3876 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:14.574  1362  1362 D BluetoothPbap: Proxy object disconnected
09-06 18:57:14.574  1362  1362 D PbapServerProfile: Bluetooth service disconnected
09-06 18:57:14.574  3980  3980 D HidService: Received stop request...Stopping profile...
,09-06 18:57:14.574  3980  3980 D HidService: Stopping Bluetooth HidService
,09-06 18:57:14.575  1362  1362 D BluetoothInputDevice: Proxy object disconnected
09-06 18:57:14.575  1362  1362 D HidProfile: Bluetooth service disconnected
09-06 18:57:14.576  3980  3980 D HealthService: Received stop request...Stopping profile...
09-06 18:57:14.576  3876  3876 D BluetoothPbap: Proxy object disconnected
,09-06 18:57:14.576  3876  3876 D PbapServerProfile: Bluetooth service disconnected
,09-06 18:57:14.577  3876  3876 D BluetoothInputDevice: Proxy object disconnected
,09-06 18:57:14.577  3876  3876 D HidProfile: Bluetooth service disconnected
,09-06 18:57:14.580  3980  3980 D PanService: Received stop request...Stopping profile...,
09-06 18:57:14.582  3876  3876 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:57:14.582  3876  3876 D PanProfile: Bluetooth service disconnected
09-06 18:57:14.583  3980  3980 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:14.583  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.583  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:14.583  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.583  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:57:14.583  1362  1362 D PanProfile: Bluetooth service disconnected
09-06 18:57:14.585  3980  3980 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 18:57:14.585  3980  3980 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 18:57:14.585  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.585  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.585  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.585  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-06 18:57:14.585  3980  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-06 18:57:14.585  3980  3980 D BluetoothMapService: Received stop request...Stopping profile...
09-06 18:57:14.585  3980  3980 D BluetoothMapService: stop()
09-06 18:57:14.586  3980  3980 D BluetoothMapAppObserver: deinitObservers()
09-06 18:57:14.586  3980  3980 D BluetoothMapAppObserver: removeReceiver()
09-06 18:57:14.587  1362  1362 D BluetoothMap: Proxy object disconnected
09-06 18:57:14.587  1362  1362 D MapProfile: Bluetooth service disconnected
09-06 18:57:14.588  3980  3980 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:14.588  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.588  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:14.588  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.589  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.589  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.590  3980  4149 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:14.590  3980  4149 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:14.590  3980  4149 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:14.590  3980  3980 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:14.590  3980  4149 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:14.590  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.590  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-06 18:57:14.590  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:14.590  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.590  3980  3980 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:57:14.590  3980  3980 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:57:14.591  3980  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-06 18:57:14.591  3980  3980 V BluetoothAdapterState: isTurningOff()=true
,09-06 18:57:14.591  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.591  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:14.591  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.591  3980  3980 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:57:14.591  3980  4143 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-06 18:57:14.592  3980  3980 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 18:57:14.592  3980  3980 V BluetoothAdapterState: isTurningOff()=true
09-06 18:57:14.592  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.592  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:14.592  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.592  3980  3980 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:57:14.593  3980  3980 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 18:57:14.593  3980  3980 D BluetoothMapService: MAP Service closeService in
09-06 18:57:14.593  3980  3980 V BluetoothAdapterState: isTurningOff()=true
,09-06 18:57:14.593  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:14.593  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:14.593  3980  3980 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:14.594  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-06 18:57:14.594  3980  4139 D BluetoothAdapterProperties: Setting state to 15
09-06 18:57:14.594  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-06 18:57:14.594  3876  3876 D BluetoothMap: Proxy object disconnected
09-06 18:57:14.595  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:14.595  3980  3980 D BluetoothMapService: cleanup()
09-06 18:57:14.595  3980  3980 D BluetoothMapService: MAP Service closeService in
09-06 18:57:14.596  3876  3889 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:57:14.595  3980  4139 I BluetoothAdapterState: Entering BleOnState
09-06 18:57:14.594  3876  3876 D MapProfile: Bluetooth service disconnected
09-06 18:57:14.598  1362  1375 D BluetoothPan: onBluetoothStateChange on: false
09-06 18:57:14.599  1967  1982 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:14.599  1362  2090 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:14.599   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 18:57:14.600  3876  3887 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 18:57:14.601  3876  3889 D BluetoothPan: onBluetoothStateChange on: false
09-06 18:57:14.601   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-06 18:57:14.601  3876  3887 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 18:57:14.602  1362  2089 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 18:57:14.602  3876  3889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:14.603  1362  1376 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 18:57:14.603  1362  1375 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:57:14.604   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-06 18:57:14.604  3876  3887 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:14.604   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:14.605  3980  4139 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-06 18:57:14.605  3980  4139 D BluetoothAdapterProperties: Setting state to 16
09-06 18:57:14.605  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-06 18:57:14.606  3980  4139 D BluetoothAdapterProperties: onBleDisable
,09-06 18:57:14.607  3980  4139 I BluetoothAdapterState: Entering PendingCommandState
09-06 18:57:14.607  3980  4140 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-06 18:57:14.608  3980  4149 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 18:57:14.608  3980  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-06 18:57:14.608  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:14.609  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:14.609  3980  4143 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:14.611  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-06 18:57:14.611  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:14.612  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:14.616  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:14.619  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:14.808  3980  4143 I bt_hci  : shut_down
,09-06 18:57:14.809  3980  4147 D bt_hwcfg: hw_epilog_process
,09-06 18:57:14.821  3980  4147 I bt_vendor: low_power_mode_cb
,09-06 18:57:14.847  3980  4147 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-06 18:57:14.847  3980  4147 I bt_vendor: epilog_cb
09-06 18:57:14.847  3980  4147 I bt_hci  : epilog_finished_callback
,09-06 18:57:14.855  3980  4143 I bt_hci_h4: hal_close
,09-06 18:57:14.856  3980  4143 I bt_userial_vendor: device fd = 51 close
,09-06 18:57:14.990  3980  4140 D bt_stack_manager: event_shut_down_stack finished.
,09-06 18:57:14.992  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-06 18:57:15.000  3980  4139 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-06 18:57:15.001  3980  3980 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:57:15.002  3980  3980 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 18:57:15.003  3980  3980 D BtGatt.GattService: stop()
,09-06 18:57:15.003  3980  3980 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 18:57:15.008  3980  3980 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:15.008  3980  3980 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:15.009  3980  3980 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:15.009  3980  3980 V BluetoothAdapterState: isBleTurningOff()=true
09-06 18:57:15.010  3980  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-06 18:57:15.011  3980  4139 D BluetoothAdapterProperties: Setting state to 10
,09-06 18:57:15.012  3980  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-06 18:57:15.014  3980  4139 I BluetoothAdapterState: Entering OffState
,09-06 18:57:15.016   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 18:57:15.038  3980  3980 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-06 18:57:15.039  3980  3980 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-06 18:57:15.039  3980  4140 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-06 18:57:15.042  3980  4140 D bt_stack_manager: event_clean_up_stack finished.
09-06 18:57:15.042  3980  3980 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 18:57:15.044  3980  3980 I art     : System.exit called, status: 0
,09-06 18:57:15.045  3980  3980 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 18:57:15.106   873  1618 I ActivityManager: Process com.android.bluetooth (pid 3980) has died
,09-06 18:57:17.520  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:17.520  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:20.528  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:20.529  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a36c7c5 added. We now have 6 listener(s)
09-06 18:57:20.529  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:20.533  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:20.534  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18f451a added. We now have 7 listener(s)
09-06 18:57:20.534  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:20.535  3811  3862 I System.out: IsBluetoothEnabled
,09-06 18:57:20.547  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:20.597   873   890 I ActivityManager: Start proc 4185:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-06 18:57:20.717  4185  4185 D AdapterServiceConfig: Adding HeadsetService
,09-06 18:57:20.717  4185  4185 D AdapterServiceConfig: Adding A2dpService
09-06 18:57:20.717  4185  4185 D AdapterServiceConfig: Adding HidService
09-06 18:57:20.717  4185  4185 D AdapterServiceConfig: Adding HealthService
09-06 18:57:20.717  4185  4185 D AdapterServiceConfig: Adding PanService
,09-06 18:57:20.718  4185  4185 D AdapterServiceConfig: Adding GattService
09-06 18:57:20.718  4185  4185 D AdapterServiceConfig: Adding BluetoothMapService
,09-06 18:57:20.732   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3da296d:true
,09-06 18:57:20.734  4185  4185 D BluetoothAdapterState: make() - Creating AdapterState
,09-06 18:57:20.743  4185  4185 I bt_bluedroid: init
,09-06 18:57:20.744  4185  4197 I BluetoothAdapterState: Entering OffState
,09-06 18:57:20.746  4185  4198 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 18:57:20.746  4185  4198 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 18:57:20.746  4185  4198 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 18:57:20.746  4185  4198 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 18:57:20.747  4185  4185 I bt_bluedroid: get_profile_interface socket
,09-06 18:57:20.749  4185  4185 I bt_bluedroid: get_profile_interface sdp
,09-06 18:57:20.750  4185  4201 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-06 18:57:20.752  4185  4201 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 18:57:20.753  4185  4196 I bt_bluedroid: config_hci_snoop_log
,09-06 18:57:20.755   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 18:57:20.764  4185  4197 D BluetoothAdapterState: Current state: OFF, message: 0
,09-06 18:57:20.765  4185  4197 D BluetoothAdapterProperties: Setting state to 14
,09-06 18:57:20.765  4185  4197 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-06 18:57:20.767  4185  4197 D BluetoothBondStateMachine: make
,09-06 18:57:20.770  4185  4202 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 18:57:20.772  4185  4197 I BluetoothAdapterState: Entering PendingCommandState
,09-06 18:57:20.774  4185  4185 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-06 18:57:20.776  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:20.777  4185  4185 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 18:57:20.778  4185  4185 D BtGatt.GattService: Received start request. Starting profile...
,09-06 18:57:20.778  4185  4185 D BtGatt.GattService: start()
09-06 18:57:20.778  4185  4185 I bt_bluedroid: get_profile_interface gatt
09-06 18:57:20.778  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:20.778  4185  4185 D BtGatt.AdvertiseManager: advertise manager created
,09-06 18:57:20.786  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:20.786  4185  4185 V BluetoothAdapterState: isTurningOn()=false
09-06 18:57:20.786  4185  4185 V BluetoothAdapterState: isBleTurningOn()=true
09-06 18:57:20.786  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:20.787  4185  4197 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-06 18:57:20.787  4185  4197 I bt_bluedroid: enable
,09-06 18:57:20.787  4185  4198 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-06 18:57:20.788  4185  4198 I bt_hci  : start_up
,09-06 18:57:20.793  4185  4198 I bt_vendor: alloc value 0xb3a54189
,09-06 18:57:20.794  4185  4198 I bt_vendor: init
09-06 18:57:20.794  4185  4198 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-06 18:57:20.794  4185  4198 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-06 18:57:20.902  4185  4198 D bt_hci  : start_up starting async portion
,09-06 18:57:20.903  4185  4205 I bt_hci  : event_finish_startup
09-06 18:57:20.903  4185  4205 I bt_hci_h4: hal_open
09-06 18:57:20.903  4185  4205 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-06 18:57:20.912  4185  4205 I bt_userial_vendor: device fd = 51 open
,09-06 18:57:20.945  4185  4205 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 18:57:20.976  4185  4205 D bt_hwcfg: Chipset BCM4354A2
,09-06 18:57:20.976  4185  4205 D bt_hwcfg: Target name = [BCM4354A2]
,09-06 18:57:20.977  4185  4205 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-06 18:57:21.652  4185  4205 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-06 18:57:21.654  4185  4205 D bt_hwcfg: Settlement delay -- 100 ms
09-06 18:57:21.654  4185  4205 I bt_hwcfg: Setting fw settlement delay to 100 
,09-06 18:57:21.771  4185  4205 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-06 18:57:21.772  4185  4205 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-06 18:57:21.802  4185  4205 I bt_hwcfg: vendor lib fwcfg completed
,09-06 18:57:21.802  4185  4205 I bt_vendor: firmware callback
09-06 18:57:21.803  4185  4205 I bt_hci  : firmware_config_callback
,09-06 18:57:21.815  4185  4207 I bt_btu  : btu_task pending for preload complete event
,09-06 18:57:21.816  4185  4207 I bt_btu_task: Bluetooth chip preload is complete
,09-06 18:57:21.816  4185  4207 I bt_btu  : btu_task received preload complete event
,09-06 18:57:21.826  4185  4207 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 18:57:21.826  4185  4207 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-06 18:57:21.826  4185  4207 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 18:57:21.826  4185  4207 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-06 18:57:21.827  4185  4207 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:57:21.827  4185  4207 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 18:57:21.827  4185  4207 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:57:21.828  4185  4207 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 18:57:21.828  4185  4207 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 18:57:21.828  4185  4207 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 18:57:21.828  4185  4207 I         : BTE_InitTraceLevels -- TRC_SDP
,09-06 18:57:21.829  4185  4207 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 18:57:21.829  4185  4207 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 18:57:21.829  4185  4207 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-06 18:57:21.829  4185  4207 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-06 18:57:21.962  4185  4207 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d1d9d
,09-06 18:57:21.963  4185  4207 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d1d9d 
,09-06 18:57:21.973  4185  4201 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-06 18:57:21.974  4185  4201 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-06 18:57:21.975  4185  4201 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-06 18:57:21.979  4185  4201 D BluetoothAdapterProperties: Name is: Nexus 6
,09-06 18:57:21.985  4185  4201 D BluetoothAdapterProperties: Scan Mode:20
,09-06 18:57:21.987  4185  4201 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 18:57:21.988  4185  4201 D bt_hci  : do_postload posting postload work item
,09-06 18:57:21.988  4185  4205 I bt_hci  : event_postload
09-06 18:57:21.988  4185  4205 I bt_vendor: sco_config_cb
,09-06 18:57:21.989  4185  4205 I bt_hci  : sco_config_callback postload finished.
,09-06 18:57:21.991  4185  4201 D bt_bte_conf: Device ID record 1 : primary
,09-06 18:57:21.991  4185  4201 D bt_bte_conf:   vendorId            = 000f
,09-06 18:57:21.991  4185  4201 D bt_bte_conf:   vendorIdSource      = 0001
09-06 18:57:21.992  4185  4201 D bt_bte_conf:   product             = 1200
09-06 18:57:21.992  4185  4201 D bt_bte_conf:   version             = 1436
,09-06 18:57:21.992  4185  4201 D bt_bte_conf:   clientExecutableURL = 
09-06 18:57:21.992  4185  4201 D bt_bte_conf:   serviceDescription  = 
,09-06 18:57:21.992  4185  4201 D bt_bte_conf:   documentationURL    = 
09-06 18:57:21.993  4185  4201 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-06 18:57:21.994  4185  4198 D bt_stack_manager: event_start_up_stack finished
09-06 18:57:21.995  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 18:57:21.995  4185  4197 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-06 18:57:21.996  4185  4197 D BluetoothAdapterProperties: Setting state to 15
09-06 18:57:21.996  4185  4197 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-06 18:57:21.997  4185  4197 I BluetoothAdapterState: Entering BleOnState
,09-06 18:57:21.998  4185  4205 I bt_vendor: low_power_mode_cb
,09-06 18:57:22.003  4185  4197 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-06 18:57:22.003  4185  4197 D BluetoothAdapterProperties: Setting state to 11
,09-06 18:57:22.004  4185  4197 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-06 18:57:22.012  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:22.014  4185  4185 D HeadsetService: Received start request. Starting profile...
,09-06 18:57:22.018  4185  4185 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 18:57:22.018  4185  4185 D HeadsetStateMachine: make
,09-06 18:57:22.021  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:22.032  4185  4185 D HeadsetStateMachine: max_hf_connections = 1
,09-06 18:57:22.033  4185  4185 I bt_bluedroid: get_profile_interface handsfree
09-06 18:57:22.033  4185  4201 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-06 18:57:22.033  4185  4201 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-06 18:57:22.037  4185  4197 I BluetoothAdapterState: Entering PendingCommandState
,09-06 18:57:22.045  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:22.048  4185  4185 D A2dpService: Received start request. Starting profile...
,09-06 18:57:22.049  4185  4185 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 18:57:22.049  4185  4185 I bt_bluedroid: get_profile_interface avrcp
,09-06 18:57:22.055  4185  4185 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 18:57:22.055  4185  4185 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 18:57:22.055  4185  4185 D A2dpStateMachine: make
,09-06 18:57:22.056  4185  4185 I bt_bluedroid: get_profile_interface a2dp
,09-06 18:57:22.057  4185  4201 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-06 18:57:22.061  4185  4216 D A2dpStateMachine: Enter Disconnected: -2
,09-06 18:57:22.063  4185  4185 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 18:57:22.064  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:22.064  4185  4185 D HidService: Received start request. Starting profile...
,09-06 18:57:22.064  4185  4185 I bt_bluedroid: get_profile_interface hidhost
,09-06 18:57:22.065  4185  4185 D HidService: setHidService(): set to: null
09-06 18:57:22.065  4185  4201 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b33e5,
09-06 18:57:22.065  4185  4201 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-06 18:57:22.066  4185  4185 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 18:57:22.067  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:22.067  4185  4185 D HealthService: Received start request. Starting profile...
09-06 18:57:22.067  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:22.069  4185  4185 I bt_bluedroid: get_profile_interface health
,09-06 18:57:22.070  4185  4185 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 18:57:22.071  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:22.071  4185  4185 D PanService: Received start request. Starting profile...
,09-06 18:57:22.071  4185  4185 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:57:22.071  4185  4185 I bt_bluedroid: get_profile_interface pan
09-06 18:57:22.072  4185  4201 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 18:57:22.077  4185  4185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
,09-06 18:57:22.078  4185  4185 D BluetoothMapService: Received start request. Starting profile...
09-06 18:57:22.078  4185  4185 D BluetoothMapService: start()
,09-06 18:57:22.081  4185  4185 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-06 18:57:22.082  4185  4185 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-06 18:57:22.083  4185  4185 D BluetoothMapAppObserver: createReceiver()
,09-06 18:57:22.084  4185  4185 D BluetoothMapAppObserver: initObservers()
,09-06 18:57:22.084  4185  4185 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-06 18:57:22.093  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:22.093  4185  4185 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:22.093  4185  4213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-06 18:57:22.093  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:22.094  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false,
,09-06 18:57:22.097  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:22.097  4185  4185 V BluetoothAdapterState: isTurningOn()=true
,09-06 18:57:22.097  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:22.098  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:22.098  4185  4185 V BluetoothAdapterState: isTurningOff()=false
09-06 18:57:22.098  4185  4185 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:22.098  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:22.098  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
09-06 18:57:22.099  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:22.099  4185  4185 V BluetoothAdapterState: isTurningOn()=true
,09-06 18:57:22.099  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
09-06 18:57:22.099  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:22.103  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isTurningOn()=true
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isTurningOff()=false
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isTurningOn()=true
09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isBleTurningOn()=false
,09-06 18:57:22.104  4185  4185 V BluetoothAdapterState: isBleTurningOff()=false
,09-06 18:57:22.105  4185  4197 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-06 18:57:22.105  4185  4197 D BluetoothAdapterProperties: ScanMode =  20
09-06 18:57:22.105  4185  4197 D BluetoothAdapterProperties: State =  11
09-06 18:57:22.107  4185  4201 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:57:22.107  4185  4201 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:57:22.107  4185  4197 D BluetoothAdapterProperties: Setting state to 12
,09-06 18:57:22.107  4185  4197 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-06 18:57:22.108  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:22.108  4185  4197 I BluetoothAdapterState: Entering OnState
,09-06 18:57:22.111  3876  3889 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 18:57:22.113  1362  1362 D BluetoothA2dp: Proxy object connected
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:22.113  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:22.116  1362  2090 D BluetoothPan: onBluetoothStateChange on: true
,09-06 18:57:22.116  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:22.116  4185  4185 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 18:57:22.117  4185  4185 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-06 18:57:22.118  1967  1982 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:22.118  1362  2089 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:22.119   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:22.119  3876  3887 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 18:57:22.122  3876  3889 D BluetoothPan: onBluetoothStateChange on: true
,09-06 18:57:22.122  4185  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:22.124   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 18:57:22.124  3876  3887 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 18:57:22.126  4185  4185 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:57:22.126  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-06 18:57:22.127  4185  4185 D ObexServerSockets: Succeed to create listening sockets 
09-06 18:57:22.127  4185  4185 D ObexServerSockets0: startAccept()
09-06 18:57:22.127  4185  4185 D ObexServerSockets0: prepareForNewConnect()
09-06 18:57:22.128  3876  3889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-06 18:57:22.129  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
09-06 18:57:22.130  4185  4185 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-06 18:57:22.130  4185  4185 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-06 18:57:22.132  1362  2090 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 18:57:22.132  3876  3876 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 18:57:22.132  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:57:22.132  1362  1362 D PanProfile: Bluetooth service connected
,09-06 18:57:22.132  3876  3876 D PanProfile: Bluetooth service connected
09-06 18:57:22.133  1362  1362 D BluetoothMap: Proxy object connected
09-06 18:57:22.133  1362  1362 D MapProfile: Bluetooth service connected
,09-06 18:57:22.133  1362  1362 D BluetoothMap: getConnectedDevices()
,09-06 18:57:22.134  4185  4222 D ObexServerSockets0: Accepting socket connection...
09-06 18:57:22.135  3876  3876 D BluetoothMap: Proxy object connected
09-06 18:57:22.135  3876  3876 D MapProfile: Bluetooth service connected,
09-06 18:57:22.135  3876  3876 D BluetoothMap: getConnectedDevices()
09-06 18:57:22.135   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-06 18:57:22.135  1362  1362 D BluetoothInputDevice: Proxy object connected
09-06 18:57:22.135  1362  1362 D HidProfile: Bluetooth service connected
,09-06 18:57:22.136  3876  3887 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:22.136  4185  4223 D ObexServerSockets0: Accepting socket connection...
09-06 18:57:22.137   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 18:57:22.138   873   873 D BluetoothA2dp: Proxy object connected
,09-06 18:57:22.141  3876  3876 D BluetoothInputDevice: Proxy object connected
09-06 18:57:22.141  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:22.141  3876  3876 D HidProfile: Bluetooth service connected
,09-06 18:57:22.142   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 18:57:22.140  4185  4185 D BluetoothMapService: onReceive
09-06 18:57:22.142  4185  4185 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:22.142  4185  4185 D BluetoothMapService: STATE_ON
,09-06 18:57:22.142  3876  3876 D BluetoothA2dp: Proxy object connected
,09-06 18:57:22.148  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:22.155  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:22.158  3876  3876 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:22.166  3876  3876 D BluetoothPbap: Proxy object connected
,09-06 18:57:22.166  3876  3876 D PbapServerProfile: Bluetooth service connected
09-06 18:57:22.166  1362  1362 D BluetoothPbap: Proxy object connected
09-06 18:57:22.166  1362  1362 D PbapServerProfile: Bluetooth service connected
,09-06 18:57:22.172  4185  4185 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-06 18:57:22.173  4185  4185 D ObexServerSockets0: prepareForNewConnect()
,09-06 18:57:22.182  4185  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:22.198  4185  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:22.199  4185  4233 I BtOppRfcommListener: Accept thread started.
,09-06 18:57:22.219   873   890 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.219  1967  2118 D BluetoothHeadset: Proxy object connected
09-06 18:57:22.220   873   873 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.220   873   873 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.221  3876  4224 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.221   873   873 D BluetoothHeadset: Proxy object connected
09-06 18:57:22.221  3876  3876 D HeadsetProfile: Bluetooth service connected
09-06 18:57:22.221  1362  1375 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.222  1362  1362 D HeadsetProfile: Bluetooth service connected
,09-06 18:57:22.224   873   890 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.230  3876  3889 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.230  3876  3876 D HeadsetProfile: Bluetooth service connected
,09-06 18:57:22.235   873   890 D BluetoothHeadset: Proxy object connected
,09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:22.571  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:22.577  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:22.581  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:22.582  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d2a884b added. We now have 8 listener(s)
09-06 18:57:22.582  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:22.588   873  1981 D WifiService: setWifiEnabled: false pid=3811, uid=10000
,09-06 18:57:22.588   873  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:57:22.600  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:22.601   873   884 D WifiService: setWifiEnabled: true pid=3811, uid=10000
09-06 18:57:22.602   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-06 18:57:22.618   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:22.639  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:22.640  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:22.641  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:22.646  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 18:57:22.647  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:22.647  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 18:57:22.649  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fed613 Bundle[{}]
,09-06 18:57:22.650  3811  3862 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 18:57:22.651  3811  3862 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 18:57:22.652  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 18:57:22.652  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 18:57:22.653  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 18:57:22.654  3811  3862 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 18:57:22.655   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,09-06 18:57:22.656   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-06 18:57:22.657   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-06 18:57:22.658   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-06 18:57:22.658   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-06 18:57:22.658   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-06 18:57:22.658   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-06 18:57:22.658  3811  3862 I System.out: Running OutgoingSocketThread
09-06 18:57:22.659  3811  4238 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,09-06 18:57:22.660  3811  4238 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49365
09-06 18:57:22.660  3811  4238 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 18:57:22.670   374   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-06 18:57:22.671   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.79 rxSuccessRate=1.00 delta 1000 -> 1000
,09-06 18:57:22.671   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:22.672   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-06 18:57:22.672   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 18:57:22.675   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,09-06 18:57:22.680   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-06 18:57:22.681   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-06 18:57:22.681   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:22.687   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-06 18:57:22.740   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-06 18:57:22.742  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-06 18:57:23.168  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-06 18:57:23.208  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 18:57:23.208  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-06 18:57:23.214   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,09-06 18:57:23.219   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-06 18:57:23.220   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:23.220   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-06 18:57:23.245   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:23.256   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:23.257   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,09-06 18:57:23.274   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 18:57:23.274   873  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-06 18:57:23.276   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-06 18:57:23.285   873  4242 D DhcpClient: Receive thread started
,09-06 18:57:23.366   873  1307 E native  : do suspend false
,09-06 18:57:23.387   873  1845 D DhcpClient: Broadcasting DHCPDISCOVER
,09-06 18:57:23.400   873  4242 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-06 18:57:23.402   873  1845 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-06 18:57:23.405   873  1845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-06 18:57:23.417   873  4242 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-06 18:57:23.418   873  1845 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-06 18:57:23.424   374   871 D CommandListener: Setting iface cfg
,09-06 18:57:23.435   873  1845 D DhcpClient: Scheduling renewal in 86399s
,09-06 18:57:23.439   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-06 18:57:23.450   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-06 18:57:23.451   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,09-06 18:57:23.452   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-06 18:57:23.454   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 18:57:23.458   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,09-06 18:57:23.515   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-06 18:57:23.515   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-06 18:57:23.518   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-06 18:57:23.520   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-06 18:57:23.523   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-06 18:57:23.531   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-06 18:57:23.535   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-06 18:57:23.536   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-06 18:57:23.536   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-06 18:57:23.536   873  1309 D ConnectivityService:    accepting network in place of null
,09-06 18:57:23.536   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-06 18:57:23.537   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-06 18:57:23.537   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-06 18:57:23.559   873  4241 D NetlinkSocketObserver: NeighborEvent{elapsedMs=142272, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-06 18:57:23.568   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:23.600   374   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-06 18:57:23.605   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-06 18:57:23.606   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:23.607   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-06 18:57:23.610   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:23.633   873  4240 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:814::200e
,09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.638  3811  3811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:23.641  3811  3811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:23.650  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-06 18:57:23.652  1727  1727 D SystemUpdateService: onCreate
,09-06 18:57:23.656  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-06 18:57:23.659  3811  3862 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,09-06 18:57:23.660  3811  3862 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,09-06 18:57:23.662  3811  3862 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-06 18:57:23.662  3811  3862 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 18:57:23.662  3811  3862 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,09-06 18:57:23.665  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 18:57:23.665  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a51228 added. We now have 2 listener(s)
,09-06 18:57:23.666  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:23.666  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.666  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.667  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:23.667  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c11b41 added. We now have 9 listener(s)
09-06 18:57:23.667  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:23.667  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:23.670  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.674  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:23.675  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:23.676  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:23.676  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 18:57:23.676  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b975e27 added. We now have 3 listener(s)
,09-06 18:57:23.677  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.678  1727  4251 I SystemUpdateService: active receiver: enabled
,09-06 18:57:23.679  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.681  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:23.681  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:57:23.682  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:57:23.682  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:23.682  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74d28d4 added. We now have 10 listener(s)
,09-06 18:57:23.682  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:23.682  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:23.682  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-06 18:57:23.682  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:23.682  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:23.682  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:23.682  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:23.682  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:23.682  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.683  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a51228 removed from the list
,09-06 18:57:23.683  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.683  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c11b41 removed from the list
,09-06 18:57:23.683  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:23.683  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.683  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.683  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.684  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:23.684  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.684  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.684  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c11b41 not in the list
09-06 18:57:23.684  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.684  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.685  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.685  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.685  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.685  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@74d28d4 removed from the list
09-06 18:57:23.685  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.685  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.685  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.685  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 18:57:23.686  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b975e27 removed from the list
09-06 18:57:23.686  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.686  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6432a7d added. We now have 2 listener(s)
,09-06 18:57:23.688  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:23.688  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:57:23.688  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:57:23.688  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.688  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b395d72 added. We now have 9 listener(s)
09-06 18:57:23.688  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:23.688  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:23.690  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.695  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:23.696  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:23.696  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-06 18:57:23.697  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 18:57:23.697  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.697  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bdfe40 added. We now have 3 listener(s)
09-06 18:57:23.698  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-06 18:57:23.698  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.700  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:23.700  3994  3994 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:23.701  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.701  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.701  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:57:23.701  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.701  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dcf179 added. We now have 10 listener(s),
09-06 18:57:23.701  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:23.701  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:57:23.702  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:23.702  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 18:57:23.702  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:23.702  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:57:23.704  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 18:57:23.704  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:57:23.705  3994  3994 D SprintDMHelper: simOperator: 
09-06 18:57:23.705  3994  3994 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-06 18:57:23.707  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:23.707  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 18:57:23.707  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:23.710  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 18:57:23.710  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:23.710  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:23.710  3811  3862 D BluetoothAdapter: STATE_ON
,09-06 18:57:23.712   873  4240 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 16:57:23 GMT], X-Android-Received-Millis=[1473181043711], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473181043681]}
,09-06 18:57:23.712  4185  4225 D BtGatt.GattService: registerClient() - UUID=8b43b7af-14de-4519-b3e4-f18186a4ec81
09-06 18:57:23.713  4185  4201 D BtGatt.GattService: onClientRegistered() - UUID=8b43b7af-14de-4519-b3e4-f18186a4ec81, clientIf=5
,09-06 18:57:23.713   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-06 18:57:23.713   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-06 18:57:23.713   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-06 18:57:23.713  3811  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 18:57:23.714   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-06 18:57:23.715  4185  4195 D BtGatt.GattService: start scan with filters
,09-06 18:57:23.718  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:23.718  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 18:57:23.718  4185  4204 D BtGatt.ScanManager: handling starting scan
09-06 18:57:23.718  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 18:57:23.718  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:23.719  4185  4204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6c1977
09-06 18:57:23.720  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:23.720  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:23.720  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 18:57:23.720  4185  4201 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 18:57:23.720  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.721  4185  4204 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 18:57:23.722  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:23.722  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 18:57:23.722  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.723  4185  4204 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:23.723  4185  4204 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 18:57:23.723  3811  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:23.723  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:23.723  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 18:57:23.723  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:23.723  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:23.724  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 18:57:23.724  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:23.724  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:23.724  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:23.724  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:23.724  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:23.724  4185  4201 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-06 18:57:23.724  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.724  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:23.725  4185  4225 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:23.725  4185  4195 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:23.725  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:23.725  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:23.725  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 18:57:23.725  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-06 18:57:23.725  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:23.726  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.726  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:23.726  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:23.726  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 18:57:23.726  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:23.726  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:23.727  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:23.727  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:23.727  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:23.727  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:23.728  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-06 18:57:23.728  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.728  4185  4204 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:23.729  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:23.729  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:23.729  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:23.729  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:23.729  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.729  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:23.729  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.729  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6432a7d removed from the list
09-06 18:57:23.730  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.734  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b395d72 removed from the list
09-06 18:57:23.734  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:23.734  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.735  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 18:57:23.735  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.735  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.735  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.735  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.735  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b395d72 not in the list
,09-06 18:57:23.735  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.735  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.737  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:23.737  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.737  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.737  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dcf179 removed from the list
09-06 18:57:23.737  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.737  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:23.737  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.737  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 18:57:23.737  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bdfe40 removed from the list
09-06 18:57:23.731  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 18:57:23.737  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.738  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.738  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb22c35 added. We now have 2 listener(s)
,09-06 18:57:23.738  4185  4204 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 18:57:23.739  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 18:57:23.739  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:57:23.739  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.739  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.739  4185  4201 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 18:57:23.739  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15328ca added. We now have 9 listener(s)
09-06 18:57:23.739  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.739  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:23.739  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:57:23.741  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.746  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:23.750  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:23.750  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:23.750  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.751  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9555558 added. We now have 3 listener(s)
09-06 18:57:23.752  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 18:57:23.752  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.752  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:57:23.752  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.752  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36656b1 added. We now have 10 listener(s)
09-06 18:57:23.752  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:23.752  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:23.753  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.757  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:23.753  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:23.758  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:23.758  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 18:57:23.758  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:23.758  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:23.760  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 18:57:23.760  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:23.763  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:23.763  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 18:57:23.763  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:23.764  1727  4254 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-06 18:57:23.764  1727  4254 W BaseAppContext: Using Auth Proxy for data requests.
,09-06 18:57:23.765  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 18:57:23.766  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:23.766  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 18:57:23.766  1727  4254 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
09-06 18:57:23.766  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:23.769  4185  4221 D BtGatt.GattService: registerClient() - UUID=ebd37930-9f28-4fc0-9dee-874162d08ca0
09-06 18:57:23.769  4185  4201 D BtGatt.GattService: onClientRegistered() - UUID=ebd37930-9f28-4fc0-9dee-874162d08ca0, clientIf=5
,09-06 18:57:23.769  3811  3823 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-06 18:57:23.770  4185  4214 D BtGatt.GattService: start scan with filters
09-06 18:57:23.771  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-06 18:57:23.772  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-06 18:57:23.773  1727  2301 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:23.774  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 18:57:23.774  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:23.774  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:23.774  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:23.774  4185  4204 D BtGatt.ScanManager: handling starting scan
09-06 18:57:23.775  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:23.776  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:23.776  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:23.776  4185  4201 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 18:57:23.776  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.776  4185  4204 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 18:57:23.777  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:23.777  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 18:57:23.777  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.777  4185  4204 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:23.777  4185  4204 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-06 18:57:23.778  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:23.779  3811  3862 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 18:57:23.779  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:23.779  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:23.779  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:23.779  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.779  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.779  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 18:57:23.779  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.779  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb22c35 removed from the list
09-06 18:57:23.779  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.779  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15328ca removed from the list
09-06 18:57:23.779  4185  4201 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 18:57:23.779  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:23.779  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.779  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:23.780  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.780  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 18:57:23.780  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.780  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:23.780  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 18:57:23.780  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.781  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15328ca not in the list
09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 18:57:23.781  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:23.781  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 18:57:23.781  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 18:57:23.782  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:23.782  4185  4214 D BtGatt.GattService: stopScan() - queue size =1
09-06 18:57:23.782  4185  4225 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:23.783  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 18:57:23.783  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 18:57:23.783  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:23.783  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:23.783  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:23.783  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 18:57:23.783  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.783  4185  4204 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:23.783  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:23.784  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:23.784  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:23.784  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:57:23.784  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.785  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.785  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:23.785  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:23.785  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:23.785  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36656b1 removed from the list
09-06 18:57:23.785  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.785  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:23.785  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.785  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:23.786  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.786  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.786  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9555558 removed from the list
,09-06 18:57:23.786  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.786  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b58aced added. We now have 2 listener(s)
,09-06 18:57:23.787  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 18:57:23.787  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.787  4185  4204 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-06 18:57:23.788  4185  4201 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-06 18:57:23.788  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.790  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 18:57:23.790  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.790  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.790  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.790  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c00722 added. We now have 9 listener(s)
09-06 18:57:23.790  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:23.790  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:57:23.793  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:23.796  1727  4251 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.796  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:23.798  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.798  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:23.798  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.798  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6d7770 added. We now have 3 listener(s)
09-06 18:57:23.799  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 18:57:23.799  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.799  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.799  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:23.799  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a02ae9 added. We now have 10 listener(s)
09-06 18:57:23.799  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:23.800  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:57:23.800  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:23.800  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:23.800  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:23.800  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:57:23.800  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:23.801  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:23.802  3811  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-06 18:57:23.802  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 18:57:23.802  1727  2301 I iu.UploadsManager: num updated entries: 0
09-06 18:57:23.803  1727  2301 I iu.SyncManager: NEXT; no task
09-06 18:57:23.804  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:57:23.805  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-06 18:57:23.805  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 18:57:23.808  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 18:57:23.808  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:23.808  3811  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 18:57:23.808  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:23.809  4185  4195 D BtGatt.GattService: registerClient() - UUID=d9e60c93-c80b-47e9-9f79-917962cf5189
09-06 18:57:23.810  4185  4201 D BtGatt.GattService: onClientRegistered() - UUID=d9e60c93-c80b-47e9-9f79-917962cf5189, clientIf=5
09-06 18:57:23.810  3811  3822 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-06 18:57:23.810  4185  4225 D BtGatt.GattService: start scan with filters
09-06 18:57:23.811  1515  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-06 18:57:23.811  1515  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-06 18:57:23.811  1515  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 18:57:23.811  1515  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-06 18:57:23.812  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:23.812  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:23.812  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:23.812  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:23.812  4185  4204 D BtGatt.ScanManager: handling starting scan
09-06 18:57:23.814  4185  4201 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-06 18:57:23.814  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.814  4185  4204 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-06 18:57:23.814  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:23.814  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:23.814  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:23.815  1727  4251 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-06 18:57:23.815  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-06 18:57:23.815  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.815  4185  4204 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:23.815  4185  4204 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-06 18:57:23.815  1727  4251 I SystemUpdateService: now status is 0 (complete)
09-06 18:57:23.815  1727  4251 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-06 18:57:23.815  1727  4251 I SystemUpdateService: file has been verified
09-06 18:57:23.816  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:23.817  4185  4201 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-06 18:57:23.817  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.817  1727  4251 I SystemUpdateService: OTA package size = 12249756
09-06 18:57:23.818  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-06 18:57:23.818  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-06 18:57:23.820  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:23.820  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:23.821  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:23.821  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.821  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.821  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:23.821  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.821  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b58aced removed from the list
09-06 18:57:23.821  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.821  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c00722 removed from the list
09-06 18:57:23.821  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:23.821  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:23.822  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.822  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 18:57:23.822  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.822  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:23.823  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.823  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.823  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.823  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c00722 not in the list
09-06 18:57:23.823  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:23.823  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 18:57:23.823  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:23.823  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:23.824  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 18:57:23.824  3811  3862 D BluetoothAdapter: STATE_ON
09-06 18:57:23.824  4185  4214 D BtGatt.GattService: stopScan() - queue size =1
09-06 18:57:23.825  4185  4195 D BtGatt.GattService: unregisterClient() - clientIf=5
09-06 18:57:23.826  1727  4251 I SystemUpdateService: showing system update notification
09-06 18:57:23.827  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:23.827  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 18:57:23.827  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:23.827  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:23.827  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:23.828  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:23.828  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:23.828  3811  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:23.828  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:57:23.829  4185  4201 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-06 18:57:23.829  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.829  4185  4204 D BtGatt.ScanManager: stopping BLe Batch
,09-06 18:57:23.829  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.829  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.829  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:23.829  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.830  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a02ae9 removed from the list
09-06 18:57:23.830  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:23.830  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.830  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.830  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 18:57:23.830  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6d7770 removed from the list
09-06 18:57:23.830  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.830  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc78ca5 added. We now have 2 listener(s)
09-06 18:57:23.830  1727  4254 E MDM     : [181] SitrepService.a: Error sending sitrep.
09-06 18:57:23.831  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-06 18:57:23.831  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:57:23.831  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.831  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.831  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76f587a added. We now have 9 listener(s)
09-06 18:57:23.832  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:23.832  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:23.832  3811  3811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 18:57:23.832  3811  3811 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:23.832  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:57:23.833  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:23.834  4185  4201 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-06 18:57:23.834  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.834  4185  4204 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:23.836  3811  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:23.837  4185  4201 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-06 18:57:23.837  4185  4201 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-06 18:57:23.838  3811  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:23.838  3811  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:23.839  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:23.839  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf4c488 added. We now have 3 listener(s)
09-06 18:57:23.839  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.840  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-06 18:57:23.840  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:23.840  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:23.841  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:23.841  3811  3811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:23.841  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1494e21 added. We now have 10 listener(s)
,09-06 18:57:23.841  3811  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:23.841  3811  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:23.841  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:23.841  3811  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:23.841  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:23.841  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.841  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:23.841  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.841  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc78ca5 removed from the list
09-06 18:57:23.841  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:23.841  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76f587a removed from the list
09-06 18:57:23.841  3811  3862 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:23.841  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.842  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.842  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:23.842  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:23.842  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:23.842  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.842  3811  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76f587a not in the list
09-06 18:57:23.842  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:23.842  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:23.843  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:23.843  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:23.843  3811  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:23.843  3811  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1494e21 removed from the list
09-06 18:57:23.843  3811  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:23.843  3811  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:23.843  3811  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:23.843  3811  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:23.843  3811  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf4c488 removed from the list
09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 18:57:23.844  3811  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:23.848  3811  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,09-06 18:57:23.848  3811  4264 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-06 18:57:23.848  3811  4264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 18:57:23.849  3811  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,09-06 18:57:23.849  3811  4265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
09-06 18:57:23.849  3811  4265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 18:57:23.851  3811  3862 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-06 18:57:23.851  3811  3862 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 18:57:23.851  3811  3862 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 18:57:23.851  3811  3862 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 18:57:23.851  3811  3862 D com.test.thalitest.ThaliTestRunner: Total duration: 21731 ms
,09-06 18:57:23.852  3811  3862 I jxcore-log: *Native tests were executed*
09-06 18:57:23.852  3811  3862 I jxcore-log: 
,09-06 18:57:23.852  3811  3862 I jxcore-log: Total number of executed tests:  80
09-06 18:57:23.852  3811  3862 I jxcore-log: 
09-06 18:57:23.853  3811  3862 I jxcore-log: Number of passed tests:  80
09-06 18:57:23.853  3811  3862 I jxcore-log: 
09-06 18:57:23.853  3811  3862 I jxcore-log: Number of failed tests:  0
09-06 18:57:23.853  3811  3862 I jxcore-log: 
,09-06 18:57:23.853  3811  3862 I jxcore-log: Number of ignored tests:  0
09-06 18:57:23.853  3811  3862 I jxcore-log: 
,09-06 18:57:23.853  3811  3862 I jxcore-log: Total duration:  21731
09-06 18:57:23.853  3811  3862 I jxcore-log: 
09-06 18:57:23.854  3811  3862 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 18:57:23.854  3811  3862 I jxcore-log: 
,09-06 18:57:23.856  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.856  3811  3862 I jxcore-log: 
09-06 18:57:23.859  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.859  3811  3862 I jxcore-log: 
09-06 18:57:23.860  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.860  3811  3862 I jxcore-log: 
09-06 18:57:23.861  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.861  3811  3862 I jxcore-log: 
09-06 18:57:23.861  3811  3811 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-06 18:57:23.862  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.862  3811  3862 I jxcore-log: 
09-06 18:57:23.863  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.863  3811  3862 I jxcore-log: 
,09-06 18:57:23.865  1727  1727 D SystemUpdateService: onDestroy
09-06 18:57:23.866  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.866  3811  3862 I jxcore-log: 
09-06 18:57:23.867  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.867  3811  3862 I jxcore-log: 
09-06 18:57:23.868  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.868  3811  3862 I jxcore-log: 
09-06 18:57:23.869  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:23.869  3811  3862 I jxcore-log: 
09-06 18:57:23.869  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.869  3811  3862 I jxcore-log: 
09-06 18:57:23.870  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.870  3811  3862 I jxcore-log: 
,09-06 18:57:23.871  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.871  3811  3862 I jxcore-log: 
09-06 18:57:23.872  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.872  3811  3862 I jxcore-log: 
09-06 18:57:23.872  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.872  3811  3862 I jxcore-log: 
09-06 18:57:23.873  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.873  3811  3862 I jxcore-log: 
09-06 18:57:23.873  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.873  3811  3862 I jxcore-log: 
09-06 18:57:23.874  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.874  3811  3862 I jxcore-log: 
09-06 18:57:23.875  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.875  3811  3862 I jxcore-log: 
09-06 18:57:23.875  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.875  3811  3862 I jxcore-log: 
09-06 18:57:23.876  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.876  3811  3862 I jxcore-log: 
09-06 18:57:23.876  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.876  3811  3862 I jxcore-log: 
09-06 18:57:23.877  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.877  3811  3862 I jxcore-log: 
09-06 18:57:23.877  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:23.877  3811  3862 I jxcore-log: 
09-06 18:57:23.878  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.878  3811  3862 I jxcore-log: 
,09-06 18:57:23.878  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:23.878  3811  3862 I jxcore-log: 
09-06 18:57:23.879  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.879  3811  3862 I jxcore-log: 
09-06 18:57:23.879  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.879  3811  3862 I jxcore-log: 
,09-06 18:57:23.880  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.880  3811  3862 I jxcore-log: 
,09-06 18:57:23.881  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.881  3811  3862 I jxcore-log: 
,09-06 18:57:23.881  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.881  3811  3862 I jxcore-log: 
,09-06 18:57:23.884  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:23.884  3811  3862 I jxcore-log: 
,09-06 18:57:23.924  1515  2175 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-06 18:57:23.924  1515  2175 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 18:57:23.925  1515  2175 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 18:57:23.925  1515  2175 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 18:57:23.934  3563  4263 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-06 18:57:23.934  3563  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jdm.a(PG:82)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jcs.o(PG:406)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jcn.a(PG:1379)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jcs.i(PG:143)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at blb.a(PG:3937)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at czp.a(PG:18188)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at czp.a(PG:9081)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at czq.run(PG:1686)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 18:57:23.934  3563  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jdj.a(PG:4091)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jdj.a(PG:1125)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jdm.a(PG:77)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	... 12 more
09-06 18:57:23.934  3563  4263 E HttpOperation: Caused by: faj: BadAuthentication
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at fal.a(PG:38)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	at jdj.a(PG:4089)
09-06 18:57:23.934  3563  4263 E HttpOperation: 	... 14 more
,09-06 18:57:23.960  1515  2068 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-06 18:57:23.960  1515  2068 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-06 18:57:23.960  1515  2068 I GLSUser : [GLSUser] Extracting token using key: Auth
09-06 18:57:23.961  1515  2068 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-06 18:57:23.974  3563  4263 E HttpOperation: [getmobileexperiments] Unexpected exception
09-06 18:57:23.974  3563  4263 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jdm.a(PG:82)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jcs.o(PG:406)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jcn.a(PG:1379)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jcs.i(PG:143)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at hec.a(PG:42)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at hee.a(PG:102)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at czr.a(PG:65)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at kka.a(PG:108)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at czp.a(PG:19176)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at czp.a(PG:9081)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at czq.run(PG:1686)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-06 18:57:23.974  3563  4263 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jdj.a(PG:4091)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jdj.a(PG:1125)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jdm.a(PG:77)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	... 15 more
09-06 18:57:23.974  3563  4263 E HttpOperation: Caused by: faj: BadAuthentication
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at fal.a(PG:38)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	at jdj.a(PG:4089)
09-06 18:57:23.974  3563  4263 E HttpOperation: 	... 17 more
,09-06 18:57:23.975  3563  4263 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-06 18:57:23.975  3563  4263 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jdm.a(PG:82)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jcs.o(PG:406)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jcn.a(PG:1379)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jcs.i(PG:143)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at hec.a(PG:42)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at hee.a(PG:102)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at czr.a(PG:65)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at kka.a(PG:108)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at czp.a(PG:19176)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at czp.a(PG:9081)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at czq.run(PG:1686)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jdj.a(PG:4091)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jdj.a(PG:1125)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jdm.a(PG:77)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	... 15 more
09-06 18:57:23.975  3563  4263 E ExperimentLoader: Caused by: faj: BadAuthentication
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at fal.a(PG:38)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	at jdj.a(PG:4089)
09-06 18:57:23.975  3563  4263 E ExperimentLoader: 	... 17 more
,09-06 18:57:24.070   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130453, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-06 18:57:24.229  3811  3811 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:24.231  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:24.231  3811  3862 I jxcore-log: 
,09-06 18:57:24.286  3811  3811 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:24.288  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:24.288  3811  3862 I jxcore-log: 
,09-06 18:57:24.314  3927  4257 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 18:57:24.332  3811  3811 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:24.334  3811  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:24.334  3811  3862 I jxcore-log: 
,09-06 18:57:24.485  4266  4266 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-06 18:57:24.490  4266  4266 D AndroidRuntime: CheckJNI is OFF
,09-06 18:57:24.529  1515  4259 I GCM     : Ack for not saved message 136,
,09-06 18:57:24.536  4266  4266 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-06 18:57:24.574  4266  4266 I Radio-JNI: register_android_hardware_Radio DONE
,09-06 18:57:24.596  4266  4266 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 18:57:24.605   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-06 18:57:24.605   873   886 I ActivityManager: Killing 3811:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-06 18:57:24.608   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-06 18:57:24.704   873  1618 D GraphicsStats: Buffer count: 2
09-06 18:57:24.704   873  1984 I WindowState: WIN DEATH: Window{6fa226d u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-06 18:57:24.705   873  1308 D WifiService: Client connection lost with reason: 4
,09-06 18:57:24.730   873   886 W ActivityManager: Force removing ActivityRecord{3f784ea u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,09-06 18:57:24.741   873   896 W PackageSettings: Skipping PackageSetting{7c5e788 com.example.hello/10273} due to missing metadata
,09-06 18:57:24.773   873   896 I art     : Starting a blocking GC Explicit
,09-06 18:57:24.778   873  1981 W ActivityManager: Spurious death for ProcessRecord{cf4c488 0:com.test.thalitest/u0a0}, curProc for 3811: null
,09-06 18:57:24.794  3524  3555 W Finsky  : [289] PackageManagerRepository.createPackageState: Package com.test.thalitest not installed
,09-06 18:57:24.813   873  1981 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3811 uid 10000
,09-06 18:57:24.815  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-06 18:57:24.830   873   896 I art     : Explicit concurrent mark sweep GC freed 24119(1617KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 2.024ms total 55.409ms
,09-06 18:57:24.845  2046  2046 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,09-06 18:57:24.860   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-06 18:57:24.865  4266  4266 I art     : System.exit called, status: 0
09-06 18:57:24.865  4266  4266 I AndroidRuntime: VM exiting with result code 0.
09-06 18:57:24.872   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-06 18:57:24.872  2046  4283 I MicroRecognitionRnrImpl: Starting detection.
09-06 18:57:24.873  2046  4285 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@a7ae197
,09-06 18:57:24.877   378  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-06 18:57:24.878   378  4287 I AudioFlinger: AudioFlinger's thread 0xb1e40000 ready to run
09-06 18:57:24.879  2046  4285 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@a7ae197
,09-06 18:57:24.889   378  4287 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,09-06 18:57:24.889   378  4287 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-06 18:57:24.889   378  4287 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-06 18:57:24.894  4185  4185 D BluetoothMapAppObserver: onReceive
,09-06 18:57:24.894  4185  4185 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-06 18:57:24.898  1905  2277 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 18:57:24.900   378  4287 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-06 18:57:24.903  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-06 18:57:24.908   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 18:57:24.915  1878  4288 I Keyboard.Facilitator.DecoderInitializer: run()
,09-06 18:57:24.938  1967  1967 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-06 18:57:24.940  1878  4288 I Decoder : createOrResetDecoder
,09-06 18:57:24.943  3653  3653 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-06 18:57:24.967   873  2017 I ActivityManager: Start proc 4291:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-06 18:57:24.977  1515  1515 I ConfigService: onCreate
,09-06 18:57:24.980  2046  2046 I HotwordWorkerImpl: onReady
,09-06 18:57:25.006  1878  4288 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-06 18:57:25.006   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 18:57:25.028  4291  4291 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-06 18:57:25.041  1878  4288 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-06 18:57:25.043  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-06 18:57:25.043  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-06 18:57:25.045  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-06 18:57:25.045  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-06 18:57:25.046  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-06 18:57:25.046  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-06 18:57:25.046  1878  4288 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-06 18:57:25.046  1878  4288 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-06 18:57:25.046  1878  4288 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-06 18:57:25.047  1878  4288 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-06 18:57:25.047  1878  4288 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-06 18:57:25.047  1878  4288 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-06 18:57:25.077  4291  4291 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-06 18:57:25.089  4291  4309 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-06 18:57:25.099   873  1618 I ActivityManager: Start proc 4310:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-06 18:57:25.113  4291  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:25.113  4291  4307 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:25.114  4291  4307 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 18:57:25.132  4310  4310 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-06 18:57:25.149  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-06 18:57:25.149  1515  1515 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
09-06 18:57:25.150  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
09-06 18:57:25.150  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
09-06 18:57:25.150  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-06 18:57:25.150  1515  1515 E AndroidRuntime: 	... 8 more
,09-06 18:57:25.155   873  4325 E DropBoxManagerService: Can't write: system_app_crash
09-06 18:57:25.155   873  4325 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 18:57:25.155   873  4325 E DropBoxManagerService: 	... 5 more
09-06 18:57:25.169   873  4326 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-06 18:57:25.203  4291  4307 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-06 18:57:25.206   873  4326 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-06 18:57:25.206   873  4326 I Adreno  : Build Date                       : 10/20/15
09-06 18:57:25.206   873  4326 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-06 18:57:25.206   873  4326 I Adreno  : Local Branch                     : M14
09-06 18:57:25.206   873  4326 I Adreno  : Remote Branch                    : 
09-06 18:57:25.206   873  4326 I Adreno  : Remote Branch                    : 
09-06 18:57:25.206   873  4326 I Adreno  : Reconstruct Branch               : 
,09-06 18:57:25.213  4291  4309 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:25.213  4291  4309 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 18:57:25.214  4291  4309 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-06 18:57:25.214  4291  4309 E AndroidRuntime: Process: android.process.acore, PID: 4291
09-06 18:57:25.214  4291  4309 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-06 18:57:25.214  4291  4309 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 18:57:25.214   873  4326 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 18:57:25.218  4291  4307 I Process : Sending signal. PID: 4291 SIG: 9
,09-06 18:57:25.219   873  4327 E DropBoxManagerService: Can't write: system_app_crash
09-06 18:57:25.219   873  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-06 18:57:25.219   873  4327 E DropBoxManagerService: 	... 5 more
,09-06 18:57:25.256   873  1372 I ActivityManager: Process android.process.acore (pid 4291) has died
,09-06 18:57:25.257   873  1372 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-06 18:57:25.330  1985  2210 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-06 18:57:25.333  2046  2046 I HotwordDetector: Closing mic
,09-06 18:57:25.333  2046  2383 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a7ae197
09-06 18:57:25.333  2046  4285 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-06 18:57:25.357  2046  4331 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,09-06 18:57:25.387   378  4287 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-06 18:57:25.388   378  4287 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,09-06 18:57:25.392   378  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-06 18:57:25.399  2046  4283 I MicroRecognitionRnrImpl: Detection finished
,09-06 18:57:25.400  2046  2386 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-06 18:57:25.464   281   281 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
09-06 18:57:25.464   281   281 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=18 dpy=0 numHwLayers=8
09-06 18:57:25.464   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
09-06 18:57:25.464   281   281 E qdoverlay: MdpData failed to play
09-06 18:57:25.464   281   281 E qdoverlay: == Dump MdpData start ==
,09-06 18:57:25.465   281   281 E qdoverlay: == Dump OvFD fd=69 path=/dev/graphics/fb0 start/end ==
09-06 18:57:25.465   281   281 E qdoverlay: mOvData msmfb_overlay_data id=8
09-06 18:57:25.465   281   281 E qdoverlay: data msmfb_data offset=0 memid=25 id=0 flags=0x0 priv=0
09-06 18:57:25.465   281   281 E qdoverlay: == Dump MdpData end ==
09-06 18:57:25.465   281   281 E qdhwcomposer: draw: queue failed for left of dpy = 0
,09-06 18:57:25.465   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
09-06 18:57:25.465   281   281 E qdoverlay: MdpData failed to play
09-06 18:57:25.465   281   281 E qdoverlay: == Dump MdpData start ==
09-06 18:57:25.465   281   281 E qdoverlay: == Dump OvFD fd=72 path=/dev/graphics/fb0 start/end ==
09-06 18:57:25.465   281   281 E qdoverlay: mOvData msmfb_overlay_data id=16
,09-06 18:57:25.465   281   281 E qdoverlay: data msmfb_data offset=0 memid=25 id=0 flags=0x0 priv=0
09-06 18:57:25.465   281   281 E qdoverlay: == Dump MdpData end ==
09-06 18:57:25.465   281   281 E qdhwcomposer: draw: queue failed for right of dpy = 0
09-06 18:57:25.465   281   281 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,09-06 18:57:25.465   281   281 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,09-06 18:57:25.465   281   281 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
09-06 18:57:25.465   281   281 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
09-06 18:57:25.465   281   344 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=0 : Operation not permitted
,09-06 18:57:25.466   281   344 E SurfaceFlinger: eventControl(0, 0) failed Operation not permitted
,09-06 18:57:25.474   281   281 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,09-06 18:57:25.474   281   281 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
09-06 18:57:25.474   281   281 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-06 18:57:25.474   281   281 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,09-06 18:57:25.474   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-06 18:57:25.474   281   281 E qdoverlay: MdpCtrl close error in unset
,09-06 18:57:25.753   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-06 18:57:25.754   281   281 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,09-06 18:57:25.754   281   281 E qdoverlay: MdpCtrl close error in unset

```
