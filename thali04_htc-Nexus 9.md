#### Test 72145431744cc2c_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
07-12 11:36:35.515  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 11:36:35.522  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 11:36:35.524  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 11:36:35.548  1090  1103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:36:35.549  1090  1103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:36:35.549  1090  1103 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:35.549  1090  1103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:35.563  1713  1713 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-12 11:36:35.563  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:36:35.563  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-12 11:36:36.709  2355  2355 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:36:36.713  2355  2355 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:36.746  2355  2355 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:36:36.779  2355  2355 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:36:36.802  2355  2355 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-12 11:36:36.807   563   581 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:36.830  2355  2355 D AndroidRuntime: Shutting down VM
07-12 11:36:36.834  1076  1087 W SearchService: Abort, client detached.
07-12 11:36:36.848   563   753 I ActivityManager: Start proc 2364:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 11:36:36.851  1076  1076 I HotwordDetector: Closing mic
07-12 11:36:36.851  1076  1315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d2b0d7
07-12 11:36:36.866  1076  1076 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-12 11:36:36.877   221   643 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-12 11:36:36.882  1076  1319 I MicroRecognitionRnrImpl: Detection finished
07-12 11:36:36.888  1076  1318 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-12 11:36:36.964  2364  2364 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-12 11:36:37.101  2364  2364 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 11:36:37.125  2364  2364 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 9567-9581)
,07-12 11:36:37.125  2364  2364 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:37.169  2364  2364 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fa80b71}
,07-12 11:36:37.169  2364  2364 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:37.169  2364  2364 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:37.175  2364  2364 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:37.176  2364  2364 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:36:37.206  2364  2380 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,07-12 11:36:37.214  2364  2364 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:36:37.236  2364  2364 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:36:37.236  2364  2364 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:36:37.503   563   607 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@392d16:true
07-12 11:36:37.547  2364  2364 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:37.564  2364  2364 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
07-12 11:36:37.621  2364  2405 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-12 11:36:37.636  2364  2391 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-12 11:36:37.668  2364  2405 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 11:36:37.758   563   608 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +923ms
07-12 11:36:37.762   991   991 I Keyboard.Facilitator: onFinishInput()
07-12 11:36:37.815  2364  2364 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2364
07-12 11:36:37.837   563  1340 I ActivityManager: Killing 1464:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
07-12 11:36:37.865   563  1340 I ActivityManager: Killing 2020:com.google.android.youtube/u0a81 (adj 15): empty #18
07-12 11:36:37.931  2364  2364 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-12 11:36:38.113  2364  2406 D jxcore_app_log: JniHelper::setJavaVM(0xaae0c7b8), pthread_self() = -549734096
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 11:36:38.119  2364  2406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b871c added. We now have 1 listener(s)
07-12 11:36:38.121  2364  2406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
07-12 11:36:38.124  2364  2406 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 11:36:38.125  2364  2406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:36:38.125  2364  2406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:36:38.127  2364  2406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df3eab added. We now have 1 listener(s)
07-12 11:36:38.127  2364  2406 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 11:36:38.145   563   662 D WifiService: New client listening to asynchronous messages
07-12 11:36:38.145  2364  2406 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:38.145  2364  2406 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:36:38.146  2364  2406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:38.146  2364  2406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:38.147  2364  2406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:38.147  2364  2406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 11:36:38.148  2364  2406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:36:38.149  2364  2406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
07-12 11:36:38.154  2364  2406 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:38.154  2364  2406 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:38.154  2364  2406 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:36:38.154  2364  2406 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:36:38.155  2364  2406 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:38.569  2364  2364 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:38.710  2364  2413 W jxcore-log: Initializing JXcore engine
,07-12 11:36:38.710  2364  2413 W jxcore-log: JXcore engine is ready
,07-12 11:36:38.756  2413  2413 W Thread-53: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10067 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-12 11:36:38.756  2413  2413 W Thread-53: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[5635]" dev="sockfs" ino=5635 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 11:36:38.756  2413  2413 W Thread-53: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 11:36:38.756  2413  2413 W Thread-53: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18643]" dev="sockfs" ino=18643 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 11:36:38.768  2364  2413 W jxcore-log: Starting JXcore engine
,07-12 11:36:40.850  2364  2413 W jxcore-log: Platform android
07-12 11:36:40.850  2364  2413 W jxcore-log: 
,07-12 11:36:40.851  2364  2413 W jxcore-log: Process ARCH arm
07-12 11:36:40.851  2364  2413 W jxcore-log: 
,07-12 11:36:40.970  2364  2413 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:40.970  2364  2413 I jxcore-log: 
07-12 11:36:40.970  2364  2413 W jxcore-log: JXcore engine is started
,07-12 11:36:40.973  2364  2406 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:40.975  2364  2364 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:46.610  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:46.610  2364  2413 I jxcore-log: 
07-12 11:36:46.612  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:46.612  2364  2413 I jxcore-log: 
,07-12 11:36:46.614  2364  2413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:46.614  2364  2413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:46.614  2364  2413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:46.614  2364  2413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:46.616  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:46.616  2364  2413 I jxcore-log: 
,07-12 11:36:46.617  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:46.617  2364  2413 I jxcore-log: 
,07-12 11:36:48.862  2364  2413 I jxcore-log: Unit Test app is loaded
07-12 11:36:48.862  2364  2413 I jxcore-log: 
,07-12 11:36:48.866  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:48.866  2364  2413 I jxcore-log: 
,07-12 11:36:48.870  2364  2364 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:36:48.901   563  1906 D WifiService: setWifiEnabled: true pid=2364, uid=10000
,07-12 11:36:48.902   563  1906 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 11:36:48.917   217   632 D SoftapController: Softap fwReload - Ok
,07-12 11:36:49.001   217   632 D CommandListener: Setting iface cfg
,07-12 11:36:49.001   217   632 D CommandListener: Trying to bring down wlan0
,07-12 11:36:49.002   217   632 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:36:49.003   563   661 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 11:36:49.005   563   607 I ActivityManager: Start proc 2438:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 11:36:49.006  2364  2413 I jxcore-log: My device name is: htc-Nexus 9
07-12 11:36:49.006  2364  2413 I jxcore-log: 
,07-12 11:36:49.010  2364  2413 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 11:36:49.010  2364  2413 I jxcore-log: 
,07-12 11:36:49.131  2438  2438 D AdapterServiceConfig: Adding HeadsetService
,07-12 11:36:49.132  2438  2438 D AdapterServiceConfig: Adding A2dpService
07-12 11:36:49.132  2438  2438 D AdapterServiceConfig: Adding HidService
07-12 11:36:49.132  2438  2438 D AdapterServiceConfig: Adding HealthService
07-12 11:36:49.132  2438  2438 D AdapterServiceConfig: Adding PanService
07-12 11:36:49.132  2438  2438 D AdapterServiceConfig: Adding GattService
,07-12 11:36:49.169   563   607 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb44d49:true
,07-12 11:36:49.171  2438  2438 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:36:49.176  2438  2438 I bt_bluedroid: init
,07-12 11:36:49.176  2438  2450 I BluetoothAdapterState: Entering OffState
,07-12 11:36:49.180  2438  2451 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-12 11:36:49.183  2438  2451 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-12 11:36:49.183  2438  2451 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:36:49.183  2438  2451 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:36:49.190  2438  2438 I bt_bluedroid: get_profile_interface socket
,07-12 11:36:49.191  2438  2438 I bt_bluedroid: get_profile_interface sdp
07-12 11:36:49.191  2438  2454 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-12 11:36:49.192  2438  2454 D BluetoothAdapterProperties: Name is: Nexus 9
,07-12 11:36:49.196  2438  2449 I bt_bluedroid: config_hci_snoop_log
,07-12 11:36:49.201   563   607 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-12 11:36:49.203  2438  2450 D BluetoothAdapterState: Current state: OFF, message: 0
07-12 11:36:49.203  2438  2450 D BluetoothAdapterProperties: Setting state to 14
07-12 11:36:49.203  2438  2450 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 11:36:49.204  2438  2450 D BluetoothBondStateMachine: make
,07-12 11:36:49.210  2438  2455 I BluetoothBondStateMachine: StableState(): Entering Off State
07-12 11:36:49.210  2438  2438 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 11:36:49.211  2438  2450 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:36:49.214  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
,07-12 11:36:49.215  2438  2438 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 11:36:49.215  2438  2438 D BtGatt.GattService: Received start request. Starting profile...
,07-12 11:36:49.215  2438  2438 D BtGatt.GattService: start()
,07-12 11:36:49.215  2438  2438 I bt_bluedroid: get_profile_interface gatt
07-12 11:36:49.215  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
,07-12 11:36:49.216  2438  2438 D BtGatt.AdvertiseManager: advertise manager created
,07-12 11:36:49.224  2438  2438 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:36:49.224  2438  2438 V BluetoothAdapterState: isTurningOn()=false
07-12 11:36:49.224  2438  2438 V BluetoothAdapterState: isBleTurningOn()=true
07-12 11:36:49.224  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:49.225  2438  2450 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 11:36:49.225  2438  2450 I bt_bluedroid: enable
07-12 11:36:49.225  2438  2451 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-12 11:36:49.225  2438  2451 I bt_hci  : start_up
,07-12 11:36:49.232  2438  2451 I bt_vendor: alloc value 0xf3c60889
,07-12 11:36:49.232  2438  2451 I bt_vendor: init
,07-12 11:36:49.232  2438  2451 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-12 11:36:49.458  2438  2451 D bt_hci  : start_up starting async portion
,07-12 11:36:49.460  2438  2458 I bt_hci  : event_finish_startup
,07-12 11:36:49.460  2438  2458 I bt_hci_h4: hal_open
,07-12 11:36:49.460  2438  2458 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
,07-12 11:36:49.463  2438  2458 I bt_userial_vendor: device fd = 49 open
,07-12 11:36:49.472  2438  2458 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 11:36:49.503  2438  2458 D bt_hwcfg: Chipset BCM4350C0
,07-12 11:36:49.503  2438  2458 D bt_hwcfg: Target name = [BCM4350C0]
,07-12 11:36:49.503  2438  2458 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-12 11:36:49.665   563   661 D wifi    : set interface wlan0 flags (UP)
,07-12 11:36:49.668   563   661 I WifiHAL : Initializing wifi
07-12 11:36:49.668   563   661 I WifiHAL : Creating socket
,07-12 11:36:49.686   563   661 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 11:36:49.687   563   661 D wifi    : Did set static halHandle = 0x55c97bbed0
,07-12 11:36:49.687   563   661 D wifi    : halHandle = 0x55c97bbed0, mVM = 0x55c8f2bc30, mCls = 0x11d6
07-12 11:36:49.687   563   661 D wifi    : array field set
07-12 11:36:49.687   563   661 I WifiNative-HAL: interface[0] = wlan0
,07-12 11:36:49.690   563  2460 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=368452550352
,07-12 11:36:49.690   563  2460 D wifi    : waitForHalEvents called, vm = 0x55c8f2bc30, obj = 0x11d6, env = 0x55c946c900
,07-12 11:36:49.691   563   661 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:36:49.695  2364  2364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:36:49.695   563   661 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-12 11:36:49.704   563   595 I ActivityManager: Start proc 2462:com.google.android.apps.gcs/u0a83 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-12 11:36:49.781  2462  2462 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,07-12 11:36:49.831  2461  2461 I wpa_supplicant: Successfully initialized wpa_supplicant
07-12 11:36:49.841  2462  2462 W InstanceID/Rpc: Found 10007
07-12 11:36:49.855  2462  2462 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 11:36:49.905  2461  2461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:49.908   563  1919 I ActivityManager: Killing 1799:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-12 11:36:49.952  2461  2461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:49.952  2461  2461 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-12 11:36:50.003  2438  2458 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:36:50.003  2438  2458 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:36:50.003  2438  2458 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:36:50.110  2438  2458 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 11:36:50.111  2438  2458 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-12 11:36:50.136  2438  2458 I bt_hwcfg: vendor lib fwcfg completed
,07-12 11:36:50.136  2438  2458 I bt_vendor: firmware callback
07-12 11:36:50.136  2438  2458 I bt_hci  : firmware_config_callback
,07-12 11:36:50.140  2438  2486 I bt_btu  : btu_task pending for preload complete event
,07-12 11:36:50.140  2438  2486 I bt_btu_task: Bluetooth chip preload is complete
07-12 11:36:50.140  2438  2486 I bt_btu  : btu_task received preload complete event
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_GAP
,07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:36:50.143  2438  2486 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 11:36:50.359  2438  2486 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bdea31
,07-12 11:36:50.359  2438  2486 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bdea31 
07-12 11:36:50.450  2438  2454 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
07-12 11:36:50.453  2438  2454 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 11:36:50.454  2438  2454 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-12 11:36:50.455  2438  2454 D BluetoothAdapterProperties: Name is: Nexus 9
,07-12 11:36:50.456  2438  2454 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:36:50.456  2438  2454 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:50.456  2438  2454 D bt_hci  : do_postload posting postload work item
,07-12 11:36:50.456  2438  2458 I bt_hci  : event_postload
,07-12 11:36:50.456  2438  2458 I bt_vendor: sco_config_cb
07-12 11:36:50.456  2438  2458 I bt_hci  : sco_config_callback postload finished.
,07-12 11:36:50.457  2364  2364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 11:36:50.488  2438  2454 D bt_bte_conf: Device ID record 1 : primary
07-12 11:36:50.488  2438  2454 D bt_bte_conf:   vendorId            = 000f
07-12 11:36:50.488  2438  2454 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 11:36:50.488  2438  2454 D bt_bte_conf:   product             = 1200,
,07-12 11:36:50.488  2438  2454 D bt_bte_conf:   version             = 1436
,07-12 11:36:50.488  2438  2454 D bt_bte_conf:   clientExecutableURL = 
,07-12 11:36:50.488  2438  2454 D bt_bte_conf:   serviceDescription  = 
07-12 11:36:50.488  2438  2454 D bt_bte_conf:   documentationURL    = 
07-12 11:36:50.488  2438  2454 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-12 11:36:50.488  2438  2451 D bt_stack_manager: event_start_up_stack finished
07-12 11:36:50.488  2438  2450 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-12 11:36:50.488  2438  2450 D BluetoothAdapterProperties: Setting state to 15
,07-12 11:36:50.488  2438  2450 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 11:36:50.490  2438  2450 I BluetoothAdapterState: Entering BleOnState
,07-12 11:36:50.494  2438  2450 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-12 11:36:50.494  2438  2450 D BluetoothAdapterProperties: Setting state to 11
,07-12 11:36:50.494  2438  2450 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-12 11:36:50.497  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
,07-12 11:36:50.505  2438  2458 I bt_vendor: low_power_mode_cb
,07-12 11:36:50.506  2438  2438 D HeadsetService: Received start request. Starting profile...
,07-12 11:36:50.510  2438  2438 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:36:50.510  2438  2438 D HeadsetStateMachine: make
,07-12 11:36:50.512   563   595 I ActivityManager: Start proc 2492:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-12 11:36:50.516  2438  2450 I BluetoothAdapterState: Entering PendingCommandState
07-12 11:36:50.530  2438  2438 D HeadsetStateMachine: max_hf_connections = 1
,07-12 11:36:50.530  2438  2438 I bt_bluedroid: get_profile_interface handsfree
,07-12 11:36:50.530  2438  2454 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
,07-12 11:36:50.531  2438  2454 E bt_btif : btif_hf_upstreams_evt: Invalid index 29444
07-12 11:36:50.533  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
07-12 11:36:50.533   563   563 D BluetoothA2dp: Proxy object connected
07-12 11:36:50.537  2438  2438 D A2dpService: Received start request. Starting profile...
07-12 11:36:50.537  2438  2438 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:36:50.538  2438  2438 I bt_bluedroid: get_profile_interface avrcp
07-12 11:36:50.567  2438  2438 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 11:36:50.567  2438  2438 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:50.567  2438  2438 D A2dpStateMachine: make
07-12 11:36:50.579  2438  2438 I bt_bluedroid: get_profile_interface a2dp
07-12 11:36:50.583  2438  2454 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
07-12 11:36:50.585  2438  2438 I BluetoothHidServiceJni: classInitNative: succeeds
07-12 11:36:50.587  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
07-12 11:36:50.588   707   707 D BluetoothInputDevice: Proxy object connected
07-12 11:36:50.590  2438  2438 D HidService: Received start request. Starting profile...
07-12 11:36:50.590  2438  2438 I bt_bluedroid: get_profile_interface hidhost
,07-12 11:36:50.593   707   707 D HidProfile: Bluetooth service connected
07-12 11:36:50.594  2438  2506 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:36:50.594  2438  2454 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bc0099
,07-12 11:36:50.594  2438  2454 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-12 11:36:50.594  2438  2438 D HidService: setHidService(): set to: null
,07-12 11:36:50.595  2438  2438 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 11:36:50.595  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
,07-12 11:36:50.596  2438  2438 D HealthService: Received start request. Starting profile...
07-12 11:36:50.605  2438  2438 I bt_bluedroid: get_profile_interface health
07-12 11:36:50.605  2438  2438 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 11:36:50.606  2438  2438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91a473
07-12 11:36:50.607   707   707 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:36:50.607   707   707 D PanProfile: Bluetooth service connected
,07-12 11:36:50.608  2438  2438 D PanService: Received start request. Starting profile...
07-12 11:36:50.608  2438  2438 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:36:50.608  2438  2438 I bt_bluedroid: get_profile_interface pan
07-12 11:36:50.608  2438  2454 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:50.612  2438  2494 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-12 11:36:50.612  2438  2438 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.613  2438  2438 V BluetoothAdapterState: isTurningOn()=true
,07-12 11:36:50.613  2438  2438 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.613  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOff()=false
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isTurningOn()=true
07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 11:36:50.614  2438  2438 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:36:50.620  2438  2450 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-12 11:36:50.620  2438  2450 D BluetoothAdapterProperties: ScanMode =  20
,07-12 11:36:50.620  2438  2450 D BluetoothAdapterProperties: State =  11
07-12 11:36:50.620  2438  2450 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:50.620  2438  2450 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 11:36:50.621   563   607 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 11:36:50.622   707   887 D BluetoothMap: onBluetoothStateChange: up=true
07-12 11:36:50.623  2364  2364 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-12 11:36:50.625  2438  2454 D BluetoothAdapterProperties: Scan Mode:21
,07-12 11:36:50.625  2438  2454 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:36:50.625   707   887 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-12 11:36:50.625   707   732 D BluetoothPan: onBluetoothStateChange on: true
07-12 11:36:50.625  2438  2450 I BluetoothAdapterState: Entering OnState
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:50.631  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:50.632  2364  2364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:50.632   563   607 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.634   563   607 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.634   563   607 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 11:36:50.634   707   734 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 11:36:50.635  1016  1034 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:36:50.636   707   887 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 11:36:50.637   563   563 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:50.708  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:50.709  2364  2364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:50.709   563   661 D WifiConfigStore: Loading config and enabling all networks 
07-12 11:36:50.724   563   661 D WifiConfigStore: loaded 0 passpoint configs
,07-12 11:36:50.735   563   607 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.735   563   607 D BluetoothHeadset: Proxy object connected
07-12 11:36:50.735   563   607 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.736  1016  1141 D BluetoothHeadset: Proxy object connected
,07-12 11:36:50.740  2492  2492 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,07-12 11:36:50.755   707   926 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:36:50.760   563   661 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-12 11:36:50.761   563   661 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 11:36:50.762   563   661 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 11:36:50.762   563   661 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 11:36:50.762   563   661 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 11:36:50.763   563   661 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 11:36:50.769   563   661 D WifiNative-HAL: Setting external_sim to 1
07-12 11:36:50.770   563   661 D wifi    : setting dfs flag to true, 0x55c97472e0
07-12 11:36:50.770   563   661 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:50.770   563   661 D wifi    : setting scan oui 0x55c97472e0
07-12 11:36:50.770   563   661 D WifiHAL : Sending mac address OUI
07-12 11:36:50.772  1893  1893 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:50.806   707   926 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:36:50.806   707   707 D BluetoothA2dp: Proxy object connected
,07-12 11:36:50.819   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:36:50.821   563   563 D RttService: SCAN_AVAILABLE : 3
07-12 11:36:50.821   217   632 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-12 11:36:50.821   563   677 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:50.821   563   661 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-12 11:36:50.822   217   632 D CommandListener: Setting iface cfg
07-12 11:36:50.823   563   660 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '29 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 29 Failed to set address (No such device)'
07-12 11:36:50.823   563   660 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 11:36:50.827   563   660 D WifiNative-HAL: p2pGetDeviceAddress
07-12 11:36:50.827   563   660 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-12 11:36:50.848   563   753 I ActivityManager: Killing 1907:com.google.android.gm/u0a71 (adj 15): empty #17
,07-12 11:36:50.885  1090  1090 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:50.898   563  1043 I ActivityManager: Start proc 2516:com.google.android.apps.maps/u0a60 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 11:36:50.925   563   661 E native  : do suspend false
,07-12 11:36:50.931   563   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:36:50.931   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:36:50.936   707   734 D BluetoothHeadset: Proxy object connected
07-12 11:36:50.937   707   707 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:50.970  2516  2516 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,07-12 11:36:51.073  2516  2516 D StrictMode: StrictMode policy violation; ~duration=48 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-12 11:36:51.073  2516  2516 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.073  2516  2516 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.073  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.076  2516  2516 D StrictMode: StrictMode policy violation; ~duration=47 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.076  2516  2516 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.076  2516  2516 D StrictMode: StrictMode policy violation; ~duration=31 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.076  2516  2516 D StrictMode: StrictMode policy violation; ~duration=30 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.076  2516  2516 D StrictMode: StrictMode policy violation; ~duration=30 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:36:51.076  2516  2516 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:36:51.086  2492  2492 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 11:36:51.092  1090  1090 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 11:36:51.100   563   607 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36b2912:true
,07-12 11:36:51.104   707   707 D BluetoothPbap: Proxy object connected
07-12 11:36:51.104   707   707 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:51.120  2492  2492 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:36:51.128  2438  2541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:51.130  2438  2545 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:36:51.131  2438  2545 I BtOppRfcommListener: Accept thread started.
07-12 11:36:51.135  2492  2492 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-12 11:36:51.144  2492  2492 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 11:36:51.145  2492  2492 D BluetoothMap: Create BluetoothMap proxy object
07-12 11:36:51.146  2492  2492 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-12 11:36:51.150  2492  2492 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-12 11:36:51.155  2492  2492 D DockEventReceiver: finishStartingService: stopping service
07-12 11:36:51.156  2492  2492 D BluetoothA2dp: Proxy object connected
07-12 11:36:51.159  2492  2492 D BluetoothInputDevice: Proxy object connected
07-12 11:36:51.161  2492  2492 D HidProfile: Bluetooth service connected
07-12 11:36:51.162  2492  2492 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 11:36:51.162  2492  2492 D PanProfile: Bluetooth service connected
07-12 11:36:51.162  2492  2492 D BluetoothPbap: Proxy object connected
07-12 11:36:51.162  2492  2492 D PbapServerProfile: Bluetooth service connected
07-12 11:36:51.191   563   949 I ActivityManager: Killing 2099:com.google.android.music:main/u0a61 (adj 15): empty #17
,07-12 11:36:51.236  2492  2505 D BluetoothHeadset: Proxy object connected
,07-12 11:36:51.237  2492  2492 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:51.312  2516  2533 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 11:36:51.390   563   607 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@217c9be:true
,07-12 11:36:51.671   563   661 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 11:36:51.673   563   661 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-12 11:36:51.675   563   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:51.696   563   661 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-12 11:36:51.738   563   661 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 11:36:51.739  2461  2461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 11:36:52.145  2461  2461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 11:36:52.160  2461  2461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 11:36:52.160  2461  2461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-12 11:36:52.162   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:36:52.169   563   661 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-12 11:36:52.169   563   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:52.169   563   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 11:36:52.180   563   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:52.189   217   632 D CommandListener: Setting iface cfg
,07-12 11:36:52.194   563   661 D WifiStateMachine: Start Dhcp Watchdog 1,
,07-12 11:36:52.205   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:52.205   563   663 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
07-12 11:36:52.206   563   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-12 11:36:52.226   563  2556 D DhcpClient: Receive thread started
,07-12 11:36:52.304   563   661 E native  : do suspend false
,07-12 11:36:52.312   563  2555 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 11:36:52.320   563  2556 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171329, domain null
,07-12 11:36:52.322   563  2555 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171329 seconds
,07-12 11:36:52.323   563  2555 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-12 11:36:52.330   563  2556 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 11:36:52.330   563  2555 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
07-12 11:36:52.331   217   632 D CommandListener: Setting iface cfg
07-12 11:36:52.332   563   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
07-12 11:36:52.334   563  2555 D DhcpClient: Scheduling renewal in 86399s
,07-12 11:36:52.339   563   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 11:36:52.339   563   661 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 11:36:52.340   563   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 11:36:52.340   563   663 D ConnectivityService: Adding iface wlan0 to network 100
,07-12 11:36:52.345   563   661 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:36:52.389   563   663 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-12 11:36:52.389   563   663 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-12 11:36:52.392   563   663 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,07-12 11:36:52.393   563   663 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-12 11:36:52.394   563   663 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-12 11:36:52.401   563   663 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:52.403   563   663 D ConnectivityService: scheduleUnvalidatedPrompt 100
07-12 11:36:52.403   563   663 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.404   563   661 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 11:36:52.404   563   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 11:36:52.404   563   663 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:52.404   563   663 D ConnectivityService:    accepting network in place of null
07-12 11:36:52.405   563   663 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:36:52.416   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134872, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:36:52.444   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:52.478   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:36:52.480   563   663 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,07-12 11:36:52.488   563  2553 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:809::200e
,07-12 11:36:52.488   563   663 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-12 11:36:52.491   563   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,07-12 11:36:52.492   563   663 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,07-12 11:36:52.496   563   607 D Tethering: MasterInitialState.processMessage what=3
,07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:36:52.499  2364  2364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 11:36:52.500  2364  2364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:52.516  1076  1076 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 11:36:52.554  1213  2569 I CheckinService: Checking schedule, now: 1468316212554 next: 1468315513930
,07-12 11:36:52.554  1213  2569 I CheckinService: active receiver: enabled
,07-12 11:36:52.556  1213  2569 I CheckinService: Preparing to send checkin request
,07-12 11:36:52.556  1213  2569 I EventLogService: Accumulating logs since 1468316033326
,07-12 11:36:52.558   563  1007 D AlarmManagerService: Setting time of day to sec=1468316211
,07-12 11:36:51.842   563  1340 I ActivityManager: Start proc 2577:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-12 11:36:51.846   563  2553 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:51 GMT], X-Android-Received-Millis=[1468316211821], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468316211793]}
07-12 11:36:51.849   563   663 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 11:36:51.849   563   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-12 11:36:51.849   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:51.850   563   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 11:36:51.951   563  2597 D GpsLocationProvider: NTP server returned: 1468316211767 (Tue Jul 12 11:36:51 GMT+02:00 2016) reference: 135014 certainty: 8 system time offset: -184
,07-12 11:36:51.962  1213  2599 I iu.SyncManager: SYNC; picasa accounts
,07-12 11:36:51.967  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:36:51.968  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-12 11:36:51.972  2577  2577 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-12 11:36:52.054  1213  1213 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:36:52.060  1213  1213 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:36:52.064  2577  2600 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-12 11:36:52.077  1213  2599 I iu.UploadsManager: num queued entries: 0
,07-12 11:36:52.079  1213  2599 I iu.UploadsManager: num updated entries: 0
07-12 11:36:52.080  1213  2599 I iu.SyncManager: NEXT; no task
,07-12 11:36:52.108  2462  2583 V GoogleAuthProtoRequest: [222] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:36:52.134  1213  2593 I MDM     : [169] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
07-12 11:36:52.134  1213  2593 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 11:36:52.140  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-12 11:36:52.141  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
07-12 11:36:52.153   563   580 I ActivityManager: Start proc 2608:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
07-12 11:36:52.154  1213  2593 V GoogleAuthProtoRequest: [169] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:36:52.190  2577  2600 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 11:36:52.227  2577  2600 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:52.283  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:36:52.283  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:36:52.283  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:52.283  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:52.286  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-12 11:36:52.287  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-12 11:36:52.287  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:52.287  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: [222] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: [222] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:36:52.297  2462  2583 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
07-12 11:36:52.311  1213  2593 E MDM     : [169] SitrepService.a: Error sending sitrep.
07-12 11:36:52.312  1213  2594 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:36:52.332   563  1563 D libgps  : proxy_gps_xtra_inject_xtra_data: called.
,07-12 11:36:52.332   229   229 D gpsd    : WakeLock(Acquire,GPSD)
,07-12 11:36:52.364   229   229 D gpsd    : WakeLock(Release,GPSD)
,07-12 11:36:52.477   229   229 D gpsd    : WakeLock(Acquire,GPSD)
,07-12 11:36:52.477   229   229 D gpsd    : WakeLock(Release,GPSD)
,07-12 11:36:52.534  2577  2577 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-12 11:36:52.562  2577  2590 W art     : Suspending all threads took: 8.944ms
,07-12 11:36:52.730   563  1906 I ActivityManager: Start proc 2650:com.google.android.apps.magazines/u0a62 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:36:52.864  2577  2577 W InstanceID/Rpc: Found 10007
,07-12 11:36:52.879  2650  2650 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm64
,07-12 11:36:52.886  1993  2596 V KeepSync: Connecting to GoogleApiClient
,07-12 11:36:52.887   563   948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:36:52.988  1213  2569 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-12 11:36:53.000   563   662 D WifiService: New client listening to asynchronous messages
,07-12 11:36:53.046  1090  2701 I VacuumService: Vacuum at: now=1468316213046 tag=VacuumService
,07-12 11:36:53.103   563   580 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1213 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:53.130  1893  2660 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-12 11:36:53.163  1213  2569 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-12 11:36:53.276  1213  2624 W DriveInitializer: Awaiting to be initialized
,07-12 11:36:53.284  1213  2707 W DriveInitializer: Background init thread started
,07-12 11:36:53.292  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:36:53.406  1213  2707 W DriveInitializer: Background init thread ended
,07-12 11:36:53.473   563   572 I art     : Background partial concurrent mark sweep GC freed 42182(2MB) AllocSpace objects, 9(392KB) LOS objects, 33% free, 17MB/26MB, paused 10.477ms total 140.703ms
,07-12 11:36:53.475  1090  2714 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-12 11:36:53.485  1090  2714 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:53.508  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:36:53.508  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 11:36:53.508  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:36:53.508  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:53.519  1090  2714 W Uploader:  no longer exists, so no auth token.
,07-12 11:36:53.521  1213  2709 V BaseAuthAsyncOperation: access token request failed
07-12 11:36:53.538  1993  2596 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:36:53.616  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-12 11:36:53.616  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-12 11:36:53.617  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:53.617  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:36:53.627  2650  2650 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 11:36:53.627  2650  2650 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:53.627  2650  2650 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:53.642  2650  2650 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:53.646  2650  2650 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:53.668  2650  2735 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:53.710  1213  2569 W CheckinRequestBuilder: awaiting user notification for token
,07-12 11:36:53.779  2650  2650 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-12 11:36:53.849  2650  2650 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-12 11:36:53.856  2650  2650 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7101-7104)
,07-12 11:36:53.856  2650  2650 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:53.887  2650  2650 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14fb377}
,07-12 11:36:53.917   563   949 I ActivityManager: Start proc 2753:com.google.android.gms.unstable/u0a7 for service com.google.android.gms/.droidguard.DroidGuardService
,07-12 11:36:53.945  2650  2650 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:53.974  2753  2753 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-12 11:36:54.000  2753  2753 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:36:54.000  2753  2753 I MultiDex: install
,07-12 11:36:54.000  2753  2753 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:54.051  2753  2753 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 11:36:54.073  2753  2753 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:54.130  2753  2768 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,07-12 11:36:54.251  2650  2650 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:54.258  2650  2650 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:54.274   221   644 D WVCdm   : Instantiating CDM.
,07-12 11:36:54.276  2753  2764 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:54.281   221   221 I WVCdm   : CdmEngine::OpenSession
07-12 11:36:54.281   221   221 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-12 11:36:54.287   221   221 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,07-12 11:36:54.287   221   221 D oemcrypto_cenc: >> OEMCrypto_Initialize: modular drm 5.00  Jul 20 2015  05:40:21
,07-12 11:36:54.289   221   221 D oemcrypto_cenc: << OEMCrypto_Initialize
07-12 11:36:54.289   221   221 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-12 11:36:54.289   221   221 D oemcrypto_cenc: >> OEMCrypto_IsKeyboxValid
07-12 11:36:54.289   221   221 D oemcrypto_cenc: << OEMCrypto_IsKeyboxValid
07-12 11:36:54.289   221   221 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 11:36:54.289   221   221 D oemcrypto_cenc: >> OEMCrypto_OpenSession
07-12 11:36:54.289   221   221 D oemcrypto_cenc: bool AddSessionHandle(OEMCrypto_SESSION): session:0xaba58f98, status: 1
07-12 11:36:54.289   221   221 D oemcrypto_cenc: << OEMCrypto_OpenSession
07-12 11:36:54.289   221   221 D oemcrypto_cenc: >> OEMCrypto_GetRandom
,07-12 11:36:54.296   221   221 D oemcrypto_cenc: << OEMCrypto_GetRandom
07-12 11:36:54.312   221   221 E oemcrypto_cenc: OEMCrypto_SecurityLevel
07-12 11:36:54.289  2650  2650 E SysUtils: ApplicationContext is null in ApplicationStatus
07-12 11:36:54.315   221   221 D oemcrypto_cenc: >> OEMCrypto_LoadDeviceRSAKey
07-12 11:36:54.316   221   221 D oemcrypto_cenc: << OEMCrypto_LoadDeviceRSAKey
07-12 11:36:54.316   221   221 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:36:54.317   221   669 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-12 11:36:54.317   221   669 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-12 11:36:54.317   221   669 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:36:54.317   221   669 D oemcrypto_cenc: >> OEMCrypto_GetDeviceID
07-12 11:36:54.317   221   669 D oemcrypto_cenc: << OEMCrypto_GetDeviceID
07-12 11:36:54.317   221   669 D oemcrypto_cenc: >> OEMCrypto_SupportsUsageTable
,07-12 11:36:54.353   221   669 D oemcrypto_cenc: << OEMCrypto_SupportsUsageTable
,07-12 11:36:54.353   221   669 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-12 11:36:54.353   221   669 D oemcrypto_cenc: OEMCrypto_GetHDCPCapability
,07-12 11:36:54.353   221   669 D oemcrypto_cenc: >> OEMCrypto_GenerateNonce
07-12 11:36:54.353   221   669 D oemcrypto_cenc: << OEMCrypto_GenerateNonce
07-12 11:36:54.353   221   669 D WVCdm   : PrepareKeyRequest: nonce=587032114
07-12 11:36:54.353   221   669 D oemcrypto_cenc: >> OEMCrypto_GenerateRSASignature
07-12 11:36:54.395  2711  2711 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1652419944.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1652419944.dex
07-12 11:36:54.419   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:36:54.431   221   669 D oemcrypto_cenc: << OEMCrypto_GenerateRSASignature
07-12 11:36:54.432   221   669 I WVCdm   : CdmEngine::CloseSession
07-12 11:36:54.432   221   669 D oemcrypto_cenc: >> OEMCrypto_CloseSession
07-12 11:36:54.432   221   669 D oemcrypto_cenc: bool RemoveSessionHandle(OEMCrypto_SESSION): session: 0xaba58f98, status: 1
,07-12 11:36:54.434   221   669 D oemcrypto_cenc: << OEMCrypto_CloseSession
07-12 11:36:54.434   221   669 D oemcrypto_cenc: >> OEMCrypto_Terminate
07-12 11:36:54.434   221   669 D oemcrypto_cenc: << OEMCrypto_Terminate
,07-12 11:36:54.481  1090  2714 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-12 11:36:54.481  1090  2714 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,07-12 11:36:54.481  1090  2714 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:36:54.481  1090  2714 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:54.488  1090  2714 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:36:54.488  1090  2714 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:36:54.488  1090  2714 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:36:54.532  2650  2650 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:36:54.539  2650  2650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:36:54.539  2650  2650 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:36:54.578   563   593 I ActivityManager: Start proc 2784:com.google.android.apps.books/u0a28 for service com.google.android.apps.books/.service.SyncService
,07-12 11:36:54.597  1090  2714 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-12 11:36:54.597  1090  2714 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:36:54.597  1090  2714 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:54.598  1090  2714 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:54.609  1090  2714 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:36:54.609  1090  2714 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:36:54.609  1090  2714 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:36:54.627  2784  2784 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm64
,07-12 11:36:54.859  2711  2711 I dex2oat : dex2oat took 532.993ms (threads: 2) arena alloc=230KB java alloc=37KB native alloc=758KB free=65KB
,07-12 11:36:54.965  2753  2762 I art     : Background partial concurrent mark sweep GC freed 18693(1498KB) AllocSpace objects, 12(508KB) LOS objects, 40% free, 12MB/20MB, paused 5.837ms total 47.062ms
,07-12 11:36:54.972  2784  2784 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:36:54.988  2784  2784 I BooksApp: Created application version: 3.6.9 (30609)
,07-12 11:36:55.187  2804  2804 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,07-12 11:36:55.280  2804  2804 I dex2oat : dex2oat took 92.928ms (threads: 2) arena alloc=33KB java alloc=44KB native alloc=650KB free=45KB
,07-12 11:36:55.287  2753  2764 W System  : ClassLoader referenced unknown path: 
,07-12 11:36:55.426  2650  2814 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 11:36:55.462  2650  2650 I NSApplication: Starting up...
,07-12 11:36:55.480   563  1043 I ActivityManager: Start proc 2820:com.google.android.apps.photos/u0a66 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 11:36:55.482   563  1043 I ActivityManager: Killing 1589:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-12 11:36:55.626  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:36:55.626  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:36:55.626  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:55.626  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:36:55.662  1993  2596 E KeepSync: IOException
07-12 11:36:55.662  1993  2596 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:36:55.662  1993  2596 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:36:55.662  1993  2596 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:36:55.662  1993  2596 E KeepSync: 	... 10 more
,07-12 11:36:55.664  1993  2596 W KeepSync: Sync result 2
,07-12 11:36:55.677   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 27222, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:36:55.722  2784  2803 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:36:55.935  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:36:55.948  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:36:55.949  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:36:55.949  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:55.949  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:36:55.962  1713  1713 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:36:55.962  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:36:55.962  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-12 11:36:56.071   563   948 I ActivityManager: Killing 1859:android.process.acore/u0a3 (adj 15): empty #17
,07-12 11:36:56.256  2820  2820 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 11:36:56.277   563   948 E libprocessgroup: failed to kill 1 processes for processgroup 1859
,07-12 11:36:56.800  2784  2842 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:36:57.001  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:36:57.001  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:36:57.001  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:57.001  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:36:57.030  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:36:57.030  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:36:57.030  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:57.030  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:36:57.050  2784  2842 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:36:57.088  2784  2803 E BooksSync: Soft error
07-12 11:36:57.088  2784  2803 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:36:57.088  2784  2803 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:36:57.089  2784  2803 E BooksSync: Sync error
07-12 11:36:57.089  2784  2803 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:36:57.089  2784  2803 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:36:57.089  2784  2803 I BooksSync: Finished books sync
,07-12 11:36:57.285  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:36:57.285  2364  2413 I jxcore-log: 
,07-12 11:36:57.305   563   948 I ActivityManager: Killing 2252:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-12 11:36:57.398  2200  2209 W art     : Suspending all threads took: 42.921ms
,07-12 11:36:57.432   563  1340 I ActivityManager: Start proc 2844:com.google.android.calendar/u0a31 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-12 11:36:57.539  2844  2844 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm64
,07-12 11:36:57.750   563  1043 I ActivityManager: Start proc 2860:com.android.providers.calendar/u0a2 for content provider com.android.providers.calendar/.CalendarProvider2
,07-12 11:36:57.839  2860  2860 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm64
,07-12 11:36:57.899   563   580 I ActivityManager: Start proc 2875:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-12 11:36:57.900   563   580 I ActivityManager: Killing 2134:com.google.android.gms.wearable/u0a7 (adj 15): empty #17
,07-12 11:36:58.095   221   644 D WVCdm   : Instantiating CDM.
,07-12 11:36:58.096   221   886 I WVCdm   : CdmEngine::OpenSession
07-12 11:36:58.097   221   886 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-12 11:36:58.099   221   886 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-12 11:36:58.099   221   886 D oemcrypto_cenc: >> OEMCrypto_Initialize: modular drm 5.00  Jul 20 2015  05:40:21
07-12 11:36:58.100   221   886 D oemcrypto_cenc: << OEMCrypto_Initialize
07-12 11:36:58.100   221   886 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-12 11:36:58.100   221   886 D oemcrypto_cenc: >> OEMCrypto_IsKeyboxValid
07-12 11:36:58.100   221   886 D oemcrypto_cenc: << OEMCrypto_IsKeyboxValid
07-12 11:36:58.100   221   886 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-12 11:36:58.100   221   886 D oemcrypto_cenc: >> OEMCrypto_OpenSession
,07-12 11:36:58.100   221   886 D oemcrypto_cenc: bool AddSessionHandle(OEMCrypto_SESSION): session:0xaba53ba0, status: 1
07-12 11:36:58.100   221   886 D oemcrypto_cenc: << OEMCrypto_OpenSession
07-12 11:36:58.100   221   886 D oemcrypto_cenc: >> OEMCrypto_GetRandom
,07-12 11:36:58.102   221   886 D oemcrypto_cenc: << OEMCrypto_GetRandom
07-12 11:36:58.102   221   886 E oemcrypto_cenc: OEMCrypto_SecurityLevel
07-12 11:36:58.102   221   886 D oemcrypto_cenc: >> OEMCrypto_LoadDeviceRSAKey
07-12 11:36:58.102   221   886 D oemcrypto_cenc: << OEMCrypto_LoadDeviceRSAKey
07-12 11:36:58.102   221   886 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-12 11:36:58.110   221   221 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,07-12 11:36:58.110   221   221 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,07-12 11:36:58.110   221   221 I WVCdm   : CdmEngine::GenerateKeyRequest
07-12 11:36:58.110   221   221 D oemcrypto_cenc: >> OEMCrypto_GetDeviceID
07-12 11:36:58.110   221   221 D oemcrypto_cenc: << OEMCrypto_GetDeviceID
07-12 11:36:58.111   221   221 D oemcrypto_cenc: >> OEMCrypto_SupportsUsageTable
07-12 11:36:58.114   563   580 E libprocessgroup: failed to kill 1 processes for processgroup 2134
,07-12 11:36:58.114   563   580 I ActivityManager: Killing 2269:com.android.musicfx/u0a14 (adj 15): empty #18
,07-12 11:36:58.117   221   221 D oemcrypto_cenc: << OEMCrypto_SupportsUsageTable
,07-12 11:36:58.117   221   221 E oemcrypto_cenc: OEMCrypto_APIVersion: 10
07-12 11:36:58.117   221   221 D oemcrypto_cenc: OEMCrypto_GetHDCPCapability
07-12 11:36:58.117   221   221 D oemcrypto_cenc: >> OEMCrypto_GenerateNonce
07-12 11:36:58.117   221   221 D oemcrypto_cenc: << OEMCrypto_GenerateNonce
07-12 11:36:58.117   221   221 D WVCdm   : PrepareKeyRequest: nonce=3213231384
,07-12 11:36:58.117   221   221 D oemcrypto_cenc: >> OEMCrypto_GenerateRSASignature
,07-12 11:36:58.157   221   221 D oemcrypto_cenc: << OEMCrypto_GenerateRSASignature
,07-12 11:36:58.157   221   886 I WVCdm   : CdmEngine::CloseSession
,07-12 11:36:58.158   221   886 D oemcrypto_cenc: >> OEMCrypto_CloseSession
07-12 11:36:58.158   221   886 D oemcrypto_cenc: bool RemoveSessionHandle(OEMCrypto_SESSION): session: 0xaba53ba0, status: 1
07-12 11:36:58.160   221   886 D oemcrypto_cenc: << OEMCrypto_CloseSession
,07-12 11:36:58.160   221   886 D oemcrypto_cenc: >> OEMCrypto_Terminate
07-12 11:36:58.160   221   886 D oemcrypto_cenc: << OEMCrypto_Terminate
,07-12 11:36:58.169  1213  2569 I CheckinRequestBuilder: Classify the device as Tablet.
,07-12 11:36:58.170  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:36:58.170  2364  2413 I jxcore-log: 
,07-12 11:36:58.195  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:36:58.195  2364  2413 I jxcore-log: 
07-12 11:36:58.200  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:36:58.200  2364  2413 I jxcore-log: 
,07-12 11:36:58.217  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:36:58.217  2364  2413 I jxcore-log: 
,07-12 11:36:58.221  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:36:58.221  2364  2413 I jxcore-log: 
,07-12 11:36:58.244  2860  2860 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@fa80b71(com.android.providers.calendar.CalendarProvider2@86f7d56)
,07-12 11:36:58.257  2844  2844 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-12 11:36:58.280  2875  2875 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-12 11:36:58.292   563  1139 I ActivityManager: Killing 2291:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,07-12 11:36:58.299   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 27222, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:36:58.372  2875  2875 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-12 11:36:58.372  2875  2875 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:36:58.372  2875  2875 I GAv4    :   adb logcat -s GAv4
,07-12 11:36:58.388  2875  2875 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.394  2875  2875 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.414  2875  2901 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:36:58.470  1090  1440 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 11:36:58.472  1090  1090 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 11:36:58.485  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:36:58.505  1213  1213 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-12 11:36:58.525   563  1906 I ActivityManager: Start proc 2905:com.google.android.gms.wearable/u0a7 for service com.google.android.gms/.wearable.service.WearableService
,07-12 11:36:58.542  1213  1223 W art     : Suspending all threads took: 13.014ms
,07-12 11:36:58.579  2905  2905 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-12 11:36:58.593  2905  2905 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:36:58.593  2905  2905 I MultiDex: install
,07-12 11:36:58.593  2905  2905 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:58.636  2905  2905 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 11:36:58.664  2905  2905 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:36:58.674  2905  2905 D WearableService: callingUid 10007, callindPid: 2905
,07-12 11:36:58.698  1054  1459 E MDM     : [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-12 11:36:58.709  2905  2919 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,07-12 11:36:58.720  1213  2569 W System.err: java.lang.Exception: Error converting session
,07-12 11:36:58.726  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
,07-12 11:36:58.726  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
,07-12 11:36:58.729  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-12 11:36:58.729  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-12 11:36:58.729  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-12 11:36:58.729  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
07-12 11:36:58.730  1213  2569 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
,07-12 11:36:58.730  1213  2569 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-12 11:36:58.732  1213  2569 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
,07-12 11:36:58.732  1213  2569 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-12 11:36:58.733  1213  2569 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-12 11:36:58.733  1213  2569 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-12 11:36:58.733  1213  2569 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-12 11:36:58.733  1213  2569 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
07-12 11:36:58.733  1213  2569 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
,07-12 11:36:58.736  1213  2921 D LocationInitializer: Restart initialization of location
,07-12 11:36:58.733  1213  2569 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
,07-12 11:36:58.747  1213  2569 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
,07-12 11:36:58.747  1213  2569 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
,07-12 11:36:58.750  1054  1218 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:36:58.750  1090  2922 W FusedLocationProvider: location=null
07-12 11:36:58.753  1213  2569 W System.err: ,	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
07-12 11:36:58.754  1213  2569 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-12 11:36:58.754  1213  2569 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:36:58.754  1213  2569 W System.err: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:36:58.754  1213  2569 W System.err: Caused by: java.io.IOException: Invalid session data
07-12 11:36:58.754  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
07-12 11:36:58.754  1213  2569 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
07-12 11:36:58.754  1213  2569 W System.err: 	... 25 more
,07-12 11:36:58.783  1090  1090 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 11:36:58.787  1090  1456 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 11:36:58.792  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:36:58.794  1213  1213 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-12 11:36:58.805  1054  1426 E MDM     : [91] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-12 11:36:58.821  1213  2927 D LocationInitializer: Restart initialization of location
,07-12 11:36:58.842  1054  1218 W GCoreFlp: No location to return for getLastLocation()
,07-12 11:36:58.842  1090  2928 W FusedLocationProvider: location=null
,07-12 11:36:58.970  1213  2569 I CheckinTask: Sending checkin request (9410 bytes)
,07-12 11:36:59.399  2860  2860 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-12 11:36:59.399  2860  2860 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-12 11:36:59.428  1213  2569 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-12 11:36:59.429  1213  2569 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-12 11:36:59.488  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-12 11:36:59.488  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-12 11:36:59.488  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:36:59.488  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:36:59.497  1213  2569 W CheckinRequestBuilder: awaiting user notification for token
,07-12 11:36:59.516  1213  2569 I CheckinRequestBuilder: Classify the device as Tablet.
,07-12 11:36:59.539  1213  2569 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-12 11:36:59.545  1213  2569 I CheckinService: Checking schedule, now: 1468316219545 next: 1468358364539
,07-12 11:36:59.545  1213  2569 I CheckinService: active receiver: disabled
,07-12 11:36:59.563  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 11:36:59.565  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
07-12 11:36:59.570  1090  1404 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-12 11:36:59.615   563   663 D ConnectivityService: handlePromptUnvalidated 100
,07-12 11:36:59.968  2784  2801 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:02.844  2844  2872 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:03.167   563   948 I ActivityManager: Killing 2235:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-12 11:37:03.808   563  1340 I ActivityManager: Killing 1076:com.google.android.googlequicksearchbox:search/u0a22 (adj 15): empty #17
,07-12 11:37:03.829   563   662 D WifiService: Client connection lost with reason: 4
,07-12 11:37:03.996  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:37:03.996  2364  2413 I jxcore-log: 
,07-12 11:37:04.004  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:37:04.004  2364  2413 I jxcore-log: 
,07-12 11:37:04.011  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:37:04.011  2364  2413 I jxcore-log: 
,07-12 11:37:04.100  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:37:04.100  2364  2413 I jxcore-log: 
,07-12 11:37:04.459   563   581 I ActivityManager: Killing 2516:com.google.android.apps.maps/u0a60 (adj 15): empty #17
,07-12 11:37:04.480   563   581 I ActivityManager: Killing 2492:com.android.settings/1000 (adj 15): empty #18
,07-12 11:37:04.599  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:37:04.599  2364  2413 I jxcore-log: 
,07-12 11:37:04.629  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:37:04.629  2364  2413 I jxcore-log: 
,07-12 11:37:04.636  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:37:04.636  2364  2413 I jxcore-log: 
,07-12 11:37:04.745  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:37:04.745  2364  2413 I jxcore-log: 
,07-12 11:37:04.758  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:37:04.758  2364  2413 I jxcore-log: 
,07-12 11:37:04.762  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:37:04.762  2364  2413 I jxcore-log: 
,07-12 11:37:04.767  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:37:04.767  2364  2413 I jxcore-log: 
,07-12 11:37:04.776  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:37:04.776  2364  2413 I jxcore-log: 
,07-12 11:37:04.787  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:37:04.787  2364  2413 I jxcore-log: 
,07-12 11:37:04.830  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:37:04.830  2364  2413 I jxcore-log: 
,07-12 11:37:04.835  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:37:04.835  2364  2413 I jxcore-log: 
,07-12 11:37:04.850  2364  2413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:37:04.850  2364  2413 I jxcore-log: 
,07-12 11:37:04.859  2364  2413 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 11:37:04.860  2364  2413 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 11:37:04.860  2364  2413 I jxcore-log: 
,07-12 11:37:04.903  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 11:37:04.903  2364  2413 I jxcore-log: 
,07-12 11:37:04.904  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:37:04.904  2364  2413 I jxcore-log: 
,07-12 11:37:04.904  2364  2413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:37:04.904  2364  2413 I jxcore-log: 
,07-12 11:37:05.103  1713  1723 D Finsky  : [140] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-12 11:37:05.142   563   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,07-12 11:37:05.161  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:05.165  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:05.166  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:05.178  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:37:05.178  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 11:37:05.178  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:05.178  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:05.187  1713  1723 D Finsky  : [140] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-12 11:37:08.929  1213  1221 E System  : Uncaught exception thrown by finalizer
,07-12 11:37:08.931  1213  1221 E System  : java.lang.NullPointerException: ssl_session == null
07-12 11:37:08.931  1213  1221 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-12 11:37:08.931  1213  1221 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-12 11:37:08.931  1213  1221 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-12 11:37:08.931  1213  1221 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-12 11:37:08.931  1213  1221 E System  : 	at java.lang.Thread.run(Thread.java:818)
,07-12 11:37:09.616   563   653 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 11:37:09.618   563   595 I ActivityManager: Start proc 2951:com.google.android.googlequicksearchbox:search/u0a22 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,07-12 11:37:09.746  1054  1054 V GmsNetworkLocationProvi: DISABLE
,07-12 11:37:09.751  1054  1054 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-12 11:37:09.809   563   593 D ActivityRecognitionProxy: AR HW instance not available, binding will be a no-op.
,07-12 11:37:09.913   563   753 I ActivityManager: Start proc 2973:com.google.android.partnersetup/u0a11 for content provider com.google.android.partnersetup/.RlzAppProvider
,07-12 11:37:09.956   563   948 I ActivityManager: Start proc 2987:android.process.acore/u0a3 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-12 11:37:09.975  2973  2973 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm64
,07-12 11:37:10.013  2987  2987 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,07-12 11:37:10.046  2987  2987 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,07-12 11:37:10.054   563  1043 I ActivityManager: Killing 2462:com.google.android.apps.gcs/u0a83 (adj 15): empty #17
,07-12 11:37:10.066  2987  3004 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-12 11:37:10.075  1213  3006 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-12 11:37:10.077  1213  3006 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-12 11:37:10.083  1213  1328 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-12 11:37:10.092  2951  3008 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-12 11:37:10.187  2951  3008 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,07-12 11:37:10.210  2987  3004 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-12 11:37:10.210  2987  3004 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-12 11:37:10.223   563   753 I ActivityManager: Start proc 3012:com.google.android.gm.exchange/u0a70 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,07-12 11:37:10.238   563  1340 I ActivityManager: Killing 2608:com.android.chrome/u0a34 (adj 15): empty #17
,07-12 11:37:10.280  3012  3012 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm64
,07-12 11:37:10.302   563   580 I ActivityManager: Start proc 3024:com.google.android.gm/u0a71 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,07-12 11:37:10.317   563   753 I ActivityManager: Start proc 3035:com.google.process.gapps/u0a85 for content provider com.google.android.syncadapters.contacts/.GalProvider
,07-12 11:37:10.328   563  1139 I ActivityManager: Killing 2577:com.google.android.youtube/u0a81 (adj 15): empty #17
,07-12 11:37:10.361   563   948 I ActivityManager: Killing 2650:com.google.android.apps.magazines/u0a62 (adj 15): empty #17
,07-12 11:37:10.384  3024  3024 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm64
,07-12 11:37:10.425  3024  3051 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-12 11:37:10.432  3035  3035 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm64
,07-12 11:37:10.436  3024  3050 I Gmail   : getAccountsCursor
,07-12 11:37:10.441  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.449  3035  3035 I GoogleHttpClient: GMS http client unavailable, use old client
,07-12 11:37:10.459  2987  3004 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-12 11:37:10.469  2987  3004 I ContactDirectoryManager: Discovered 0 contact directories in 302ms
,07-12 11:37:10.479  3024  3024 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:37:10.513  3024  3063 E Gmail   : Error finding the version of the Email provider.....
07-12 11:37:10.513  3024  3063 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-12 11:37:10.513  3024  3063 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:10.513  3024  3063 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:37:10.513  3024  3063 W EmailMigration: We do not support migrating this version of the Email provider.
,07-12 11:37:10.514  3024  3050 I Gmail   : getAccountsCursor
,07-12 11:37:10.517  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.540   563   580 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-12 11:37:10.543  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.558  3024  3069 I Gmail   : Observing account changes for notifications
,07-12 11:37:10.559  3012  3012 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:37:10.572  3012  3012 I Exchange: EasService.onCreate
,07-12 11:37:10.579  3012  3074 I Exchange: RestartPingTask
,07-12 11:37:10.586  3012  3012 I Exchange: RestartPingsTask did not start any pings.
,07-12 11:37:10.586  3012  3012 I Exchange: PSS stopIfIdle
07-12 11:37:10.586  3012  3012 I Exchange: PSS has no active accounts; stopping service.
07-12 11:37:10.587  3012  3012 I Exchange: onDestroy
,07-12 11:37:10.601  3024  3073 I Gmail   : notifyAccountChanged
,07-12 11:37:10.603  3024  3051 I Gmail   : getAccountsCursor
,07-12 11:37:10.606  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.607  3024  3073 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 11:37:10.611  3024  3073 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-12 11:37:10.616  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.617  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:10.620  3024  3073 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-12 11:37:10.622  3024  3073 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-12 11:37:10.654  3024  3050 I Gmail   : getAccountsCursor
,07-12 11:37:10.662  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:13.914  1054  1463 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:37:14.810   563   948 I ActivityManager: Killing 2784:com.google.android.apps.books/u0a28 (adj 15): empty #17
,07-12 11:37:15.027   563   949 I ActivityManager: Killing 2875:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-12 11:37:15.513  3024  3057 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:15.596  3012  3072 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:27.523   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=170770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:37:28.516   563  1043 I ActivityManager: Start proc 3081:com.google.android.apps.gcs/u0a83 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,07-12 11:37:28.587  3081  3081 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,07-12 11:37:28.590   563   580 I ActivityManager: Start proc 3093:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-12 11:37:28.631  3093  3093 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-12 11:37:28.655  3081  3081 W InstanceID/Rpc: Found 10007
,07-12 11:37:28.667  3081  3081 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 11:37:28.684  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:28.685  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:28.701  3081  3116 V GoogleAuthProtoRequest: [293] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:37:28.719  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:28.731  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:37:28.731  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:37:28.731  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:28.731  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:28.738  3093  3117 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-12 11:37:28.740  1713  1713 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:37:28.740  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:37:28.741  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-12 11:37:28.748  1090  2621 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:37:28.748  1090  2621 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:37:28.748  1090  2621 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:28.748  1090  2621 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:28.757  3081  3116 W ExperimentUpdateService: [293] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: [293] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:37:28.758  3081  3116 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:37:28.760   563   948 I ActivityManager: Killing 1993:com.google.android.keep/u0a72 (adj 15): empty #17
,07-12 11:37:28.803  3081  3126 V GoogleAuthProtoRequest: [294] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:37:28.818  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:37:28.818  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:37:28.819  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:28.819  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: [294] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: [294] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:37:28.831  3081  3126 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:37:28.847  3093  3117 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-12 11:37:28.923  3093  3117 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:37:28.985  3093  3093 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-12 11:37:29.005  3131  3131 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1311737736.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1311737736.dex
07-12 11:37:29.005   563   593 I ActivityManager: Start proc 3136:com.google.android.keep/u0a72 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,07-12 11:37:29.022  3136  3136 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm64
,07-12 11:37:29.198  3131  3131 I dex2oat : dex2oat took 193.622ms (threads: 2) arena alloc=177KB java alloc=37KB native alloc=758KB free=65KB
,07-12 11:37:29.205  3093  3093 W InstanceID/Rpc: Found 10007
,07-12 11:37:29.214  3136  3169 V KeepSync: Connecting to GoogleApiClient
,07-12 11:37:29.215   563  1919 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:37:29.268  1090  2621 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 11:37:29.268  1090  2621 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:37:29.268  1090  2621 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:29.268  1090  2621 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:29.276  1213  3198 V BaseAuthAsyncOperation: access token request failed
,07-12 11:37:29.278  3136  3169 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:37:29.352  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:37:29.352  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:37:29.352  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:29.352  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:29.364  3136  3169 E KeepSync: IOException
07-12 11:37:29.364  3136  3169 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:37:29.364  3136  3169 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:29.364  3136  3169 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:37:29.364  3136  3169 E KeepSync: 	... 10 more
,07-12 11:37:29.365  3136  3169 W KeepSync: Sync result 2
,07-12 11:37:29.369   563  1919 I ActivityManager: Killing 2820:com.google.android.apps.photos/u0a66 (adj 15): empty #17
,07-12 11:37:29.372   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 170095, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:29.783   563   948 I ActivityManager: Killing 2860:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-12 11:37:31.601   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:37:34.064  3136  3143 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@85fe6d4)
,07-12 11:37:34.312   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:37:36.972   991  1082 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:37:36.972   991  1082 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:37:37.004  1090  1090 I ConfigService: onCreate
,07-12 11:37:42.083  1090  1090 I ConfigService: onDestroy
,07-12 11:37:57.656   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:37:59.328  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:59.334  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:59.357  3081  3213 V GoogleAuthProtoRequest: [296] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:37:59.373  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:37:59.373  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:37:59.373  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:59.373  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: [296] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: [296] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:37:59.384  3081  3213 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:37:59.429  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:59.446  1090  1090 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:59.465  1090  2621 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:37:59.465  1090  2621 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:37:59.465  1090  2621 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:59.465  1090  2621 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:59.478  1713  1713 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:37:59.478  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:37:59.478  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-12 11:37:59.723   563   593 I ActivityManager: Start proc 3220:com.google.android.apps.books/u0a28 for service com.google.android.apps.books/.service.SyncService
,07-12 11:37:59.739  3220  3220 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm64
,07-12 11:37:59.759  1090  3214 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,07-12 11:37:59.805  3220  3220 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:37:59.810  3220  3220 I BooksApp: Created application version: 3.6.9 (30609)
,07-12 11:37:59.835  3220  3238 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:37:59.905  3220  3244 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:37:59.929  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:37:59.929  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:37:59.929  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:59.929  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:59.946  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:37:59.947  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:37:59.947  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:59.947  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:59.954  3220  3244 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:37:59.954  3220  3238 E BooksSync: Soft error
07-12 11:37:59.954  3220  3238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:59.954  3220  3238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:37:59.954  3220  3238 E BooksSync: Sync error
07-12 11:37:59.954  3220  3238 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:59.954  3220  3238 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:37:59.955  3220  3238 I BooksSync: Finished books sync
,07-12 11:37:59.958   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 173436, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:38:04.522   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=207770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:38:04.808  3220  3236 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:38:05.216   563  1906 I ActivityManager: Killing 2844:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-12 11:38:09.841  1713  1723 D Finsky  : [140] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-12 11:38:09.859  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:09.876  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:09.881  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:09.901  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:38:09.901  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 11:38:09.902  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:09.902  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:09.920  1713  1723 D Finsky  : [140] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-12 11:38:11.609   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:38:27.843   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:38:29.919  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:29.922  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:29.923  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:29.933  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 11:38:29.933  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:38:29.933  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:29.933  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:29.942  1713  1713 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-12 11:38:29.943  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:38:29.943  1713  1713 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-12 11:38:31.611   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:38:31.799  3136  3249 V KeepSync: Connecting to GoogleApiClient
,07-12 11:38:31.799   563   948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:38:31.856  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:38:31.857  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:38:31.857  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:31.857  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:31.870  1213  3250 V BaseAuthAsyncOperation: access token request failed
,07-12 11:38:31.872  3136  3249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:38:31.915  1090  2621 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:38:31.915  1090  2621 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:38:31.915  1090  2621 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:31.915  1090  2621 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:31.924  3136  3249 E KeepSync: IOException
07-12 11:38:31.924  3136  3249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:38:31.924  3136  3249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:38:31.924  3136  3249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:38:31.924  3136  3249 E KeepSync: 	... 10 more
07-12 11:38:31.924  3136  3249 W KeepSync: Sync result 2
,07-12 11:38:31.928   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 234958, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:38:46.102   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:38:49.132   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:38:53.712  1090  1253 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:38:57.203   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:39:00.008  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:00.010  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:00.023  3081  3251 V GoogleAuthProtoRequest: [297] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:39:00.043  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:39:00.043  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:39:00.043  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:39:00.043  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: [297] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: [297] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:39:00.052  3081  3251 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:39:03.814  3220  3252 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:39:03.825  3220  3253 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:39:03.840  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:39:03.840  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:39:03.840  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:39:03.840  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:03.863  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:39:03.863  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:39:03.863  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:39:03.863  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:03.874  3220  3253 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:39:03.875  3220  3252 E BooksSync: Soft error
07-12 11:39:03.875  3220  3252 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:39:03.875  3220  3252 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:39:03.875  3220  3252 E BooksSync: Sync error
07-12 11:39:03.875  3220  3252 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:39:03.875  3220  3252 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:39:03.875  3220  3252 I BooksSync: Finished books sync
,07-12 11:39:03.880   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 266984, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:39:06.819   563   611 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:39:06.823   563   611 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:39:06.839   991   991 I Keyboard.Facilitator: onFinishInput()
07-12 11:39:06.840   171  1207 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (216 us)
,07-12 11:39:06.980  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:39:06.982  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:39:07.000  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55814cf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@419c0c, 16908290=android.view.AbsSavedState$1@419c0c}, android:focusedViewId=100}]}]
,07-12 11:39:07.000  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:39:07.001  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-12 11:39:07.001  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:39:07.017   563   572 I art     : Background partial concurrent mark sweep GC freed 3485(215KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 9.203ms total 105.278ms
,07-12 11:39:07.570   563   611 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:39:07.577   563   611 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-12 11:39:07.582   563   608 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:39:07.586   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55abc0c430
,07-12 11:39:07.587   171   171 D hwcomposer: hwc_blank: display 0: blank
07-12 11:39:07.587   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-12 11:39:07.912   563   680 D SurfaceControl: Excessive delay in setPowerMode(): 332ms
,07-12 11:39:07.945   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:39:07.964   563   661 E native  : do suspend false
,07-12 11:39:07.982   563   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:39:08.041   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:39:08.046   563   661 E native  : do suspend true
,07-12 11:39:08.455   563   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,07-12 11:39:11.615   563   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,07-12 11:39:15.395   563   653 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-12 11:39:15.406   563   563 V KeyguardServiceDelegate: onStartedWakingUp()
,07-12 11:39:15.407   991   991 I Keyboard.Facilitator: onFinishInput()
07-12 11:39:15.414   563   611 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-12 11:39:15.435  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-12 11:39:15.435  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-12 11:39:15.447   563   611 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@fbccda3)
,07-12 11:39:15.448  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-12 11:39:15.448  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-12 11:39:15.451   563   949 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-12 11:39:15.456   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:39:15.461   563   661 E native  : do suspend false
,07-12 11:39:15.467   563   608 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-12 11:39:15.467  1054  1054 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
07-12 11:39:15.470   171   171 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x55abc0c430
07-12 11:39:15.470   171   171 D hwcomposer: hwc_blank: display 0: unblank
07-12 11:39:15.470   171   171 D hwcomposer: hwc_blank_display: display 0: [1 -> 0]
07-12 11:39:15.470   171   171 D hwcomposer: Display 0 layer clip is 1536 x 2048
,07-12 11:39:15.470   171   171 D hwcomposer: Display 0 device clip is 1536 x 2048
07-12 11:39:15.479   563   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:39:15.519   563   753 I ActivityManager: Start proc 3257:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-12 11:39:15.550   563   596 I CwMcuSensor: CwMcuSensor::flush: fd = 198, sensors_id = 0, path = /sys/class/htc_sensorhub/sensor_hub/flush, err = 0
,07-12 11:39:15.551   563   611 I DisplayPowerController: Unblocked screen on after 137 ms
,07-12 11:39:15.551   563   611 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-12 11:39:15.568  3257  3257 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm64
,07-12 11:39:15.661   563   753 I ActivityManager: Killing 2753:com.google.android.gms.unstable/u0a7 (adj 15): empty #17
,07-12 11:39:15.751   563   680 D SurfaceControl: Excessive delay in setPowerMode(): 284ms
,07-12 11:39:35.962   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:39:43.844   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:39:51.725   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:39:54.754   563   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:40:11.129  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:11.141  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:11.146  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:11.194  1090  1103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:40:11.194  1090  1103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 11:40:11.195  1090  1103 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:40:11.195  1090  1103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:40:11.228  1090  1103 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-12 11:40:11.228  1090  1103 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:40:11.244  1713  1746 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:40:11.244  1713  1746 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-12 11:40:11.244  1713  1746 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-12 11:40:11.244  1713  1746 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-12 11:40:11.244  1713  1746 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-12 11:40:11.244  1713  1746 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-12 11:40:11.244  1713  1746 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:40:15.439   991  1082 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:40:15.440   991  1082 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:40:15.473  1090  1090 I ConfigService: onCreate
,07-12 11:40:15.964   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:40:16.296   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:40:17.202  2438  2494 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-12 11:40:20.523  1090  1090 I ConfigService: onDestroy
,07-12 11:40:35.968   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:40:36.664  3136  3277 V KeepSync: Connecting to GoogleApiClient
07-12 11:40:36.665   563  1043 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:40:36.734  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:36.738  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:36.768  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:40:36.769  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:40:36.769  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:40:36.770  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:40:36.799  1213  3278 V BaseAuthAsyncOperation: access token request failed
,07-12 11:40:36.802  3136  3277 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:40:36.873  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:40:36.873  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:40:36.873  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:40:36.873  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:40:36.882  3136  3277 E KeepSync: IOException
07-12 11:40:36.882  3136  3277 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:40:36.882  3136  3277 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:40:36.882  3136  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:40:36.882  3136  3277 E KeepSync: 	... 10 more
,07-12 11:40:36.882  3136  3277 W KeepSync: Sync result 2
,07-12 11:40:36.886   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 359852, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:40:39.682   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=362930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:40:56.923   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=380171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:41:00.121  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:00.123  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:00.131  3081  3279 V GoogleAuthProtoRequest: [298] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:41:00.146  1090  1103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:41:00.146  1090  1103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 11:41:00.146  1090  1103 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:41:00.146  1090  1103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: [298] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: [298] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:41:00.157  3081  3279 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:41:11.513  3220  3280 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:41:11.546  3220  3281 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:41:11.562  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:11.564  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:11.598  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:41:11.598  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:41:11.598  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:41:11.598  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:11.637  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:11.640  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:11.669  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:41:11.669  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:41:11.669  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:41:11.669  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:11.696  3220  3281 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:41:11.697  3220  3280 E BooksSync: Soft error
07-12 11:41:11.697  3220  3280 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:41:11.697  3220  3280 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:41:11.697  3220  3280 E BooksSync: Sync error
07-12 11:41:11.697  3220  3280 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:41:11.697  3220  3280 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:41:11.697  3220  3280 I BooksSync: Finished books sync
,07-12 11:41:11.700   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 394684, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:41:15.474  1054  1463 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:41:15.975   563   661 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,07-12 11:41:16.379   563   611 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-12 11:41:16.380   563   611 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:41:16.504  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:41:16.504  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:41:16.511   991   991 I Keyboard.Facilitator: onFinishInput()
,07-12 11:41:16.523  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55814cf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@419c0c, 16908290=android.view.AbsSavedState$1@419c0c}, android:focusedViewId=100}]}]
,07-12 11:41:16.523  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:41:16.523  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:41:16.524  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:41:16.570   563   572 I art     : Background partial concurrent mark sweep GC freed 67143(4MB) AllocSpace objects, 25(496KB) LOS objects, 33% free, 17MB/26MB, paused 725us total 141.794ms
,07-12 11:41:16.961   563   611 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:41:16.971   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55abc0c430
,07-12 11:41:16.971   563   608 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-12 11:41:16.971   171   171 D hwcomposer: hwc_blank: display 0: blank
07-12 11:41:16.972   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-12 11:41:17.299   563   680 D SurfaceControl: Excessive delay in setPowerMode(): 328ms
,07-12 11:41:17.325   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:41:17.333   563   661 E native  : do suspend true
,07-12 11:41:25.017   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=408264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:41:35.978   563   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 21, 22 -> obsolete
,07-12 11:41:52.403   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=435650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:42:16.552   991  1082 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:42:16.553   991  1082 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:42:16.598  1090  1090 I ConfigService: onCreate
,07-12 11:42:19.950   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=463197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:42:21.698  1090  1090 I ConfigService: onDestroy
,07-12 11:42:25.977   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=469224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE},
,07-12 11:43:18.723   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=521970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:44:16.697   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=579944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:44:44.803   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=608051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:44:46.319  3136  3289 V KeepSync: Connecting to GoogleApiClient
,07-12 11:44:46.320   563   948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:44:46.412  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:44:46.418  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:44:46.465  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:44:46.466  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:44:46.466  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:44:46.466  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:44:46.499  1213  3290 V BaseAuthAsyncOperation: access token request failed
,07-12 11:44:46.502  3136  3289 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:44:46.617  1090  2621 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:44:46.618  1090  2621 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:44:46.620  1090  2621 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:44:46.620  1090  2621 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:44:46.641  3136  3289 E KeepSync: IOException
07-12 11:44:46.641  3136  3289 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:44:46.641  3136  3289 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:44:46.641  3136  3289 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:44:46.641  3136  3289 E KeepSync: 	... 10 more
,07-12 11:44:46.641  3136  3289 W KeepSync: Sync result 2
,07-12 11:44:46.646   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 609486, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:45:00.245  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:00.247  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:00.259  3081  3291 V GoogleAuthProtoRequest: [299] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:45:00.291  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:45:00.291  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 11:45:00.291  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:45:00.292  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: [299] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: [299] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:45:00.307  3081  3291 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:45:16.524   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=639771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:45:26.865   563   595 I ActivityManager: Start proc 3296:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-12 11:45:26.974  3220  3308 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:45:27.004  3296  3296 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-12 11:45:27.004  3220  3309 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:45:27.014  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:27.016  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:27.039  3296  3296 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-12 11:45:27.039  3296  3296 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:45:27.039  3296  3296 I GAv4    :   adb logcat -s GAv4
,07-12 11:45:27.041  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:45:27.041  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:45:27.042  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:27.042  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:27.062  3296  3296 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:45:27.066  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:27.068  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:27.071  3296  3296 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:45:27.093  1090  1209 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:45:27.093  1090  1209 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:45:27.093  1090  1209 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:27.093  1090  1209 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:27.100  3296  3313 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:45:27.115  3220  3309 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:45:27.117  3220  3308 E BooksSync: Soft error
07-12 11:45:27.117  3220  3308 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:45:27.117  3220  3308 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:45:27.117  3220  3308 E BooksSync: Sync error
07-12 11:45:27.117  3220  3308 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:45:27.117  3220  3308 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:45:27.117  3220  3308 I BooksSync: Finished books sync
,07-12 11:45:27.123   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 650061, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:45:27.124   563   948 I ActivityManager: Killing 2973:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-12 11:45:44.643   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=667890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:48:59.782   563   653 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-12 11:48:59.788   563   611 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-12 11:48:59.796   991   991 I Keyboard.Facilitator: onFinishInput()
07-12 11:48:59.797   563   563 V KeyguardServiceDelegate: onStartedWakingUp()
,07-12 11:48:59.815   563   611 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@fbccda3)
,07-12 11:48:59.816  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-12 11:48:59.817  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-12 11:48:59.820   563   580 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-12 11:48:59.830   171   171 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x55abc0c430
,07-12 11:48:59.830   171   171 D hwcomposer: hwc_blank: display 0: unblank
,07-12 11:48:59.830   171   171 D hwcomposer: hwc_blank_display: display 0: [1 -> 0]
,07-12 11:48:59.830   563   608 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-12 11:48:59.830   171   171 D hwcomposer: Display 0 layer clip is 1536 x 2048
07-12 11:48:59.831   171   171 D hwcomposer: Display 0 device clip is 1536 x 2048
07-12 11:48:59.839  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,07-12 11:48:59.839  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-12 11:48:59.855   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:48:59.860   563   661 E native  : do suspend false
07-12 11:48:59.872   563   596 I CwMcuSensor: CwMcuSensor::flush: fd = 195, sensors_id = 0, path = /sys/class/htc_sensorhub/sensor_hub/flush, err = 0
07-12 11:48:59.872   563   611 I DisplayPowerController: Unblocked screen on after 84 ms
07-12 11:48:59.873   563   611 V KeyguardServiceDelegate: onScreenTurnedOn()
07-12 11:48:59.877   563   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 11:48:59.888  1054  1054 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-12 11:49:00.113   563   680 D SurfaceControl: Excessive delay in setPowerMode(): 283ms
,07-12 11:49:04.896   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=868144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:49:33.016   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=896264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:49:59.798   991  1082 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:49:59.798   991  1082 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:49:59.836  1090  1090 I ConfigService: onCreate
,07-12 11:50:04.921  1090  1090 I ConfigService: onDestroy
,07-12 11:50:59.930  1054  1463 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:51:00.781   563   611 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:51:00.783   563   611 I PowerManagerService: Sleeping (uid 1000)...
,07-12 11:51:00.846   991   991 I Keyboard.Facilitator: onFinishInput()
,07-12 11:51:00.865  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 11:51:00.865  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-12 11:51:00.881  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@55814cf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@419c0c, 16908290=android.view.AbsSavedState$1@419c0c}, android:focusedViewId=100}]}]
07-12 11:51:00.882  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:51:00.882  2364  2364 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:51:00.882  2364  2364 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:51:01.306   563   611 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 11:51:01.320   563   608 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-12 11:51:01.335   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55abc0c430
,07-12 11:51:01.337   171   171 D hwcomposer: hwc_blank: display 0: blank
07-12 11:51:01.337   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-12 11:51:01.661   563   680 D SurfaceControl: Excessive delay in setPowerMode(): 330ms
,07-12 11:51:01.689   563   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:51:01.702   563   661 E native  : do suspend true
,07-12 11:51:36.751   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1019998, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:52:00.887   991  1082 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:52:00.888   991  1082 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:52:00.933  1090  1090 I ConfigService: onCreate
,07-12 11:52:04.910   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1048157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:52:06.034  1090  1090 I ConfigService: onDestroy
,07-12 11:52:35.163   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1078411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:52:58.349   563  2554 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:53:00.414  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:00.416  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:00.426  3081  3324 V GoogleAuthProtoRequest: [300] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:53:00.447  1090  1103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:53:00.447  1090  1103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:53:00.447  1090  1103 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:53:00.447  1090  1103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:00.462  3081  3324 W ExperimentUpdateService: [300] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: [300] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:53:00.463  3081  3324 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:53:05.449  3136  3325 V KeepSync: Connecting to GoogleApiClient
,07-12 11:53:05.450   563   580 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 11:53:05.517  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:05.518  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:05.540  1090  1103 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:53:05.540  1090  1103 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:53:05.540  1090  1103 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:53:05.540  1090  1103 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:05.554  1213  3326 V BaseAuthAsyncOperation: access token request failed
,07-12 11:53:05.555  3136  3325 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:53:05.616  1090  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:53:05.617  1090  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:53:05.617  1090  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:53:05.617  1090  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:05.637  3136  3325 E KeepSync: IOException
07-12 11:53:05.637  3136  3325 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:53:05.637  3136  3325 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:53:05.637  3136  3325 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:53:05.637  3136  3325 E KeepSync: 	... 10 more
,07-12 11:53:05.638  3136  3325 W KeepSync: Sync result 2
,07-12 11:53:05.645   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 1108598, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:53:57.569  3220  3327 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:53:57.628  3220  3328 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 11:53:57.650  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:57.655  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:57.684  1090  1206 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:53:57.684  1090  1206 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:53:57.684  1090  1206 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:53:57.685  1090  1206 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:57.712  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:57.715  1090  1090 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:57.738  1090  1339 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:53:57.738  1090  1339 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:53:57.738  1090  1339 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:53:57.738  1090  1339 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:57.757  3220  3328 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:53:57.759  3220  3327 E BooksSync: Soft error
07-12 11:53:57.759  3220  3327 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:53:57.759  3220  3327 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:53:57.760  3220  3327 E BooksSync: Sync error
07-12 11:53:57.760  3220  3327 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:53:57.760  3220  3327 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:53:57.760  3220  3327 I BooksSync: Finished books sync
,07-12 11:53:57.766   563   593 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1160596, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:54:56.822   563   593 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),07-12 12:00:08.614  3332  3332 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 12:00:08.635  3332  3332 D AndroidRuntime: CheckJNI is OFF
07-12 12:00:08.731  3332  3332 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 12:00:08.816  3332  3332 I Radio-JNI: register_android_hardware_Radio DONE
07-12 12:00:08.875  3332  3332 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 12:00:08.898   563   595 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 12:00:08.899   563   595 I ActivityManager: Killing 2364:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-12 12:00:08.963   563  1919 I WindowState: WIN DEATH: Window{47507c6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 12:00:08.964   563   581 D GraphicsStats: Buffer count: 2
07-12 12:00:08.966   563   662 D WifiService: Client connection lost with reason: 4
07-12 12:00:08.990   563   621 W PackageSettings: Skipping PackageSetting{fb51479 com.example.hello/10095} due to missing metadata
07-12 12:00:09.022   563   621 I art     : Starting a blocking GC Explicit
07-12 12:00:09.074   563   595 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 12:00:09.074   563   595 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 12:00:09.086   563   595 E ActivityManager: Failure starting process com.test.thalitest
07-12 12:00:09.086   563   595 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 12:00:09.086   563   595 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:09.086   563   595 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:09.086   563   595 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:09.086   563   595 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 12:00:09.087   563   595 I ActivityManager:   Force finishing activity ActivityRecord{d626a90 u0 com.test.thalitest/.MainActivity t67}
07-12 12:00:09.101   563  1043 W ActivityManager: Spurious death for ProcessRecord{51e7e96 0:com.test.thalitest/u0a0}, curProc for 2364: null
07-12 12:00:09.135   563   621 I art     : Explicit concurrent mark sweep GC freed 32567(2MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 17MB/26MB, paused 1.890ms total 112.271ms
07-12 12:00:09.153   563   621 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 12:00:09.162  3332  3332 I art     : System.exit called, status: 0
07-12 12:00:09.162  3332  3332 I AndroidRuntime: VM exiting with result code 0.
07-12 12:00:09.191   563   621 I ActivityManager: Start proc 3342:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
07-12 12:00:09.200   563   621 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-12 12:00:09.256   563   595 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 12:00:09.271  1016  1016 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 12:00:09.293   563   653 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 12:00:09.295  1054  1258 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 12:00:09.390   563   659 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak

```
